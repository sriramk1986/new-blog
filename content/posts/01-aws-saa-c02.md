+++
title = "How I passed the AWS Certified Solutions Architect - Associate (SAA-C02) exam"
description = ""
type = ["posts","post"]
tags = [
    "aws",
    "cloud",
    "certification",
]
date = "2020-07-23"
categories = [
    "Certification",
]
# series = ["Hugo 101"]
[ author ]
  name = "Sriram Krishnan"
+++

![AWS Solutions Architect](/aws-sol-architect.png)

I took the AWS Certified Solutions Architect - Associate (SAA-C02) exam around a week back and managed to pass it with a score of 838. Having had no prior experience of the AWS ecosystem prior to preparing for the test, I thought of penning down a few pointers and tips on how I prepared so that others may find it helpful.

## TL;DR Here are the courses I recommend

[Adrian Cantrill's course](https://learn.cantrill.io/) or the one by [Neil Davis](https://www.udemy.com/course/aws-certified-solutions-architect-associate-hands-on-labs/) for concepts. [Jon Bonso](https://tutorialsdojo.com/) for practice tests.

## Preparation

I initially started off with the [Linux Academy](https://linuxacademy.com/) course. The course was pretty detailed and had hands-on labs after each topic. This was useful especially as I could use the Linux Academy AWS environment to spin up instances without worrying about the cost. 

However, after reading through a few forums - especially r/AWSCertifications on reddit, I realized that the course on Linux Academy was meant for SAA-C01, the earlier version of the exam and didn't have the updated course contents meant for the SAA-C02. 

I also signed up for a 7 day trail on [A Cloud Guru](https://acloud.guru/). While the course was well taught, it suffered from the same drawback as the Linux Academy course. The course was outdated and seemed to lack a lot of concepts meant for the newer version of the exam. 

After looking through the forums for recommendations on courses, I decided to enroll for [Neal Davis']((https://www.udemy.com/course/aws-certified-solutions-architect-associate-hands-on-labs/)) Udemy course as well as [Adrian Cantrill's course](https://learn.cantrill.io/). According to me, these are the 2 best resources to prepare for the certification. Neal Davis takes a more practical approach towards the exam and keeps the course exam-focussed whereas Adrian Cantrill takes a more holistic picture and tries to focus on concepts along with the exam requirements. As a suggestion, if you have time loads of time to prepare and want to learn the intricacies of AWS, go for Adrian's course. If you are under a time constraint, and wish to get the exam done and dusted quickly, go for Neil's course.

Along with the above courses, I also enrolled for [Jon Bonso's](https://tutorialsdojo.com/) practice tests. These are the single best resources to test your preparation as they replicate the test almost to the tee. The bonus is the detailed explanation for each question so you will know exactly where you are going wrong. 

In my initial attempt at the 6 tests, I scored mainly in the range of 65-80. However, in the second attempt, after a review of all questions, I managed to score 80+ in all tests. 

## The Exam

The exam has 65 questions with a score range of 100-1000. The passing score is 720. The questions have to be attempted within 130 minutes. There are 2 categories of questions:
1. Pick 1 correct option out of 4
2. Pick 2 correct options out of 5

The 2nd category of questions are tougher but are fewer in number. 

My exam was slightly tougher than Jon Bonso's practice tests in the sense that I had to read the question extremely careful so as to not miss out on keywords. Hence, it took me a bit more to get through the 65 questions than usual. Still, its not a time consuming exam as I managed to finish the exam with 30 minutes to spare. Once I was done, I clicked on the submit button and after a few nervous minutes spent filling a survey, I was relieved to see the screen display a 'Pass'.


## Important Topics

The exam majorly focussed on FSx, CloudFront, S3, EC2, ELB, RDS/DynamoDB. There were also few questions on SNS, SQS, Kinesis, Snowball from what I recollect. 

## Additional Resources

1. Good intro to VPC - [Link](https://www.youtube.com/watch?v=hiKPPy584Mg)
2. Detailed notes from Adrian's course - [Link](https://github.com/alozano-77/AWS-SAA-C02-Course)
3. Advice on Taking the AWS Solutions Architect - [Link](https://medium.com/capital-one-tech/advice-on-taking-the-aws-solutions-architect-associate-exam-from-someone-who-just-passed-eaaaabaf8c1c)

