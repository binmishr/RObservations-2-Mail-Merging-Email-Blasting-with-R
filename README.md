# RObservations-2-Mail-Merging-Email-Blasting-with-R

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

Alot of individuals think that to use R or a programming language at work you need to be a software engineer, data analyst, data scientist etc. This can be discouraging to some who don’t work in this discipline and want to break into this field, but presently work an administrative or sales role that does not require or need such skills.

But there are a variety of admistrative tasks that implimenting R can prove useful- even at the entry level. What if I told you that you can automate prospecting emails and mail merges with R? This is of particular importance if you are looking to prospect new clients, run a campaign for your organization or network with other businesses and move past introductions and save time.

This blog post is based on personal experience of what I have used for businesses to automate the prospecting process and have successfully avoided their spam folder to my knowledge (i.e. all prospects I reached out to got back to me).

NOTE: But in this post we are going to look at how to Automate Mail merges ( or Email Blasts)
The problem:

To keep things simple, suppose I have gathered a list of leads with names and emails which for emailing purposes is enough data to make a simple mail merge (or email blast).

(Of course, for our case- this data is made up)

buisness_owners <- data.frame(Name=c("Aaron","Susan","Tim"),
                              Email=c("aaron_gillman@aaronsties.com", "sue@suesflowers.ca","tim@buckto.org"))

buisness_owners

##    Name                        Email
## 1 Aaron aaron_gillman@aaronsties.com
## 2 Susan           sue@suesflowers.ca
## 3   Tim               tim@buckto.org

Using the emayili package
