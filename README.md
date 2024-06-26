<p align='center'>
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTRVQ_OnC2QMpI2i432jpBI1mwyTkycBVdqNoEEbM0T8A&s" width=50% height=50%>
<p/>

  # AWS-Cloud-project #




Iac based project using cloudformation - Automating aws cloud enviroment.  
automated and timed backup for ec2 instances to private s3 bucket using lambdas.


## Project Scope:

* AWS VPC- 2 public and 2 private subnets, security groups, private and public route tables, network acl, internet gateway and endpoint to S3.  
* IAM - 3 iam users, roles and policies for admin, ec2 and s3 access.  
* EC2 - 2 private instances with dockerfile AMI, auto scaling group and load balancer for public instances.  
* S3 - 1 public and 1 private buckets, and a bucket policy.  
* Lambda - timed lambda fucntion to  stop ec2 instance automaticly, tiggering another lambda fucntion that create timestamped backup for the content on the instance to private s3 bucket.  
* CloudFormation - infrastructure as code yml file to automate the process.    


## Architecture:


![AWS Project](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/c50e96ac-bac7-4d4c-a6da-5314678f7b6e)


## Screenshots:


#### VPC:

![VPC Stack](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/562f41df-55c1-4a6b-978f-6c52706f0bce)

#### EC2:

![EC2](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/9f3101a7-6542-47ea-b2d0-f6df827ae1a4)

#### IAM:

![IAM - designer](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/a88ccebe-165e-4c05-9125-6d0281bd6273)

#### Lambda:

![lambda s3](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/a6903ec0-b754-40e5-8e58-29b0124070b0)

![lambda ec2](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/268a33ea-61b4-4c4a-9557-0942fbc2dfbd)

#### S3:

![S3 Stack](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/6c8c85c0-1238-4424-a8e1-777547df71e4)

#### CLoudFormation:

![VPC - CF](https://github.com/Roief8/AWS-Cloud-project/assets/105589810/493af86c-b28b-4e53-8ddd-d467c3281447)

#### Videos:

(Will be added soon...)


