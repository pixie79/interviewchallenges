---
layout: post
title:  "Challenge AWS AMI Server Setup"
date:   2014-01-31 20:58:00
permalink: challenges/ami
categories: pig, python, ami, ruby
---

I have provided the below AWS AMI image which is release to the community, using that image you can create a Free AWS small ec2 server with the steps below.

##AWS Cluster set up

Go to http://aws.amazon.com/console/

Select 'Sign Up' in the top right hand corner. Follow the instructions to set up your account. Don't worry too much about the Billing info-- it's free for Micro servers which is what you'll be using for the challenges.

On your dashboard there will be the option to go to the EC2 Dashboard.

In this screen, select 'Launch Instance' [tip: if you're worried about being charged, select the 'Free tier only' option.]

Go to 'Community AMIs' and search for:
```
interviewchallenges - ami-bcb741cb
```

Make sure it's a Micro (should default to that) and Launch the Instance. Everything should be on the instance-- the data set, Pig, etc. 
