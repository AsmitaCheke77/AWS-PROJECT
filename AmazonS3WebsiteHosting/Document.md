# Host a Website on Amazon S3
![name](https://github.com/user-attachments/assets/89c929be-d0f6-46f3-9cba-8d7391c44991)

![1](https://github.com/user-attachments/assets/bcd96bf5-f614-44d3-869c-540b37159323)


## Introducing Today's Project!

### What is Amazon S3
Amazon S3 is a scalable cloud storage service that securely stores and retrieves data. It of ers high durability and availability, making it ideal for backups, archiving, and hosting static websites with a pay as you go pricing model.


### How I used Amazon S3 in this project
In this project, I utilized Amazon S3 to host the static website.


#### One thing I didn't expect in this project was...
I did not expect the Static website hosting on AWS S3 will be that easy.


### This project took me...
It took me about an hour

## How I Set Up an S3 Bucket

Creating an S3 bucket took me about 10 minutes.

The Region I picked for my S3 bucket was Asia Pacific (Mumbai) ap-south-1 because it was the nearest in the listed regions.

S3 bucket names are globally unique! This means after you create a bucket, no other AWS account in the entire world can use your bucket's name unless you delete the bucket.

![2](https://github.com/user-attachments/assets/d4899fcd-0dcf-4057-b3a8-1695986b0f95)

## Upload Website Files to S3

index.html and image assets
'I uploaded two files to my S3 bucket - they were: 1. index.html 2. NextWork - Everyone should be in a job they love_files/

Both files are necessary for this project as one the file is html file which is for user or the user file and another file contain the website assets.

![3](https://github.com/user-attachments/assets/6cfb3e0b-0a10-4256-9c2e-76dfa4b9e282)

## Static Website Hosting on S3

Website hosting means it provides the server space and technology needed to store and serve your websiteʼs files online. It ensures your site is accessible to visitors through the internet.

To enable website hosting with my S3 bucket, I configure it for "Static website hosting" in the S3 properties and set the appropriate index.

## Access Control Lists ACL 
An ACL is a set of rules that decides who can get access to a resource. Enabling ACLs in this S3 setup lets you control who can access and do things with the objects you upload into your bucket. I enabled it.
 
## Bucket Endpoints

Once static website is enabled, S3 produces a bucket endpoint URL, which is the web address provided by Amazon S3 for accessing the static website content hosted in your S3 bucket.

![4](https://github.com/user-attachments/assets/80d694ef-f2fb-43ca-b332-2cc98e5c5c2d)

## An error!

When I first visited the bucket endpoint URL, I saw an '403 Forbidden' error means that you don't have the permissions to view a file or resource on a website.


The reason for this error was that you don't have the permissions to view a file or resource on a website

![5](https://github.com/user-attachments/assets/393f873d-bf36-45bf-b189-f2688d811253)

## Success!

To resolve this connection error, I select both the checkboxes of the objects, selected the Action tab and selected the option as 'Make public using ACL'.

![Successful_Webpage](https://github.com/user-attachments/assets/b431e759-1054-4281-9aa6-885f6c3d7164)








