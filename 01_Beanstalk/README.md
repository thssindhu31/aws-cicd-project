# 01 - Elastic Beanstalk Setup

## Overview
Created AWS Elastic Beanstalk environment to deploy and host the Java web application.

## Steps Performed
- Created EC2 Key Pair (vprobeanskey)
- Created Beanstalk Application (vprofile)
- Created Beanstalk Environment (vprofile-prod1133)
- Platform: Tomcat running on 64-bit Amazon Linux 2023
- Instance Type: t3.micro
- Auto Scaling: Min 2 instances
- Load Balancer: Application Load Balancer
- Rolling updates enabled

