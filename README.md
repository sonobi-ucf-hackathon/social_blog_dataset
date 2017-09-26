# Social Blog Dataset

A blog is a personal journal published on the Web consisting of discrete entries (“posts”) typically displayed in reverse chronological order. A conventional blog may combine text, images, and links to other blogs and web pages. Community blogging platforms have made traditional blogging more interactive by adding additional social and participatory features. They allow the creation of online profiles in which links to other bloggers are specified. This blogger to blogger declared social ties that specify the blogger’s interests and endorsement of other bloggers, creating a social network
through which blog updates are automatically disseminated.

In this repository, we are publishing a dataset collected from a social blogging platform.
This dataset has profile and social network information of 26,811 bloggers.

Files
----------
https://github.com/sonobi-ucf-hackathon/social_blog_dataset/raw/master/data.zip

data.zip contains two files. 1) profile_data.txt and 2) adj_list.txt

1) profile_data.txt: each row represents profile attributes of a blogger. Attributes are separated by '|'

Example row: 26810|MrORobert|Public|1996-03-13|Male|nan|In A Relationship|2014-10-22|nan|nan|68|4|0|4|0|2|0|1|170|791 days ago

Profile attributes are described below:

Serial: serial number of the blogger starting from 1  

Name:	blogger name 

Visibility:	whether the profile is public/private or 	

Birthday: date of birth	

Gender:	gender of the blogger	

Location: blogger location		

Status: married/single etc.

Joined: when the blogger joined	

Job: job of the blogger		

Language: language of the blogger	

BlogTraffic: total profile hits   

Posts: number of posts written by the blogger	

MyComments: number of comments posted by the blogger to other blog posts	

UserComments: number of others bloggers' comments the blogger received 

Photos: number of photos uploaded by the blogger	

Friends: number of friends of the blogger	

Following: number of bloggers the blogger is following

Followers: number of followers of the blogger	 			

Points: number of points the blogger earned from the platform e.g., posting blogs, comments, daily login 	

LastOnline: when (e.g., days/hours ago) the blogger was last seen online 

2) adj_list.txt: each row represents friendship network of a blogger, they are separated by '|'   

Example row:  theatre22|artulovehandmade|bigbighead|chieftaz|Destiny70|FIRESBREATH|katskorner|kazimamun|mamakat|nathanbrydn|rusty-armor

First entry ("theatre22") is the blogger and rest of the entries (e.g., artulovehandmade, bigbighead, ...., rusty-armor) are his/her friends.

Project Ideas
----------

What cool things can be done with this dataset! Here are some pointers.

* Can you identify most influential or important bloggers in the network? How do you measure the influence or importance?

* Can you recommend some interesting bloggers whom a blogger can follow and send friend request? 

* Is there any gender difference? Can you predict a blogger's gender from contribution? (Example gender differences in wikipedia editing http://people.ischool.berkeley.edu/~coye/Pubs/Articles/GenderWikiSym2011.pdf)

* Can you predict blogger churn or retention in the community?

* Do you think single bloggers are more active in the platform? 



