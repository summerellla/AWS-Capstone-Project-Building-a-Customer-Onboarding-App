<h1>Capstone Project: Building a Customer Onboarding App - Lab 01</h1>
<h1>Description</h1>
Customer onboarding is one of the most important stages of a customer’s journey with a bank. During this stage, the bank and customers exchange significant information. This exchange involves obtaining documentation needed to meet regulatory requirements and provide relevant products and services to customers.
<br />


AnyCompany Bank has decided to develop and deploy a customer onboarding serverless application on AWS. With the proposed customer onboarding solutions on AWS, the bank can use artificial intelligence (AI), machine learning (ML), and digital tools to streamline the onboarding process. With these solutions, the bank can transform the ways that customers are onboarded and reduce friction during this essential process.
<br />




As a cloud developer at AnyCompany Bank, you have been assigned the task of building the new onboarding application on AWS. The application is named Know Your Customer (KYC).
In this lab, you create and configure the Document S3 bucket and Document Lambda function IAM role resources. These resources are highlighted in the following diagram.
<br />



<b>Lab 1 architectural diagram.</b> <br />

![374242867-f32de9e7-3376-4291-a8f0-f86cfc4a1ea6](https://github.com/user-attachments/assets/c5923f85-2c90-42da-9eb2-1fefac2f8a7d)


Image description: The diagram depicts the KYC application architectural diagram. The diagram highlights the key resources that you need to create and configure in this lab. These two resources are the Document S3 bucket and the Document Lambda function IAM role. <br />

<h2>Services used in this lab:</h2> 
<b>Amazon S3: </b>Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It stores and protect any amount of data for a range of use cases, such as data lakes, websites, built-for-the-cloud applications, backups, archives, machine learning, and analytics.

<b>IAM AWS Identity and Access Management:</b> (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.

<h2>Walkthrough:</h2>

<br />
First, I used the AWS Management Console to create an S3 bucket where I configured the settings so the name included my account ID, the bucket encryption was set to SSE-S3, and the bucket was set to not be public.
<br />

![lab-1(1)](https://github.com/user-attachments/assets/6041c244-22ab-4a00-b8c8-8397bfdee8b5)




<br />

Next, I configured a policy on the document bucket that I created in the previous task to deny all Amazon S3 actions from any principal over HTTP (TLS is not used).
<br />
![aws-lab1(2)](https://github.com/user-attachments/assets/f68b2978-0008-4c79-b422-8537397f2ae4)

<br />
As a final step, I created the IAM role for the Lambda function and added Amazon S3 permissions to the role so the Lambda function can read, write, and delete objects from the document bucket that I previosuly created.
<br />

![aws-lab1(3)](https://github.com/user-attachments/assets/fa6f8a6e-dd33-456c-a448-4a512d881e78)


<br />

![aws-lab1(4)](https://github.com/user-attachments/assets/617a0bb1-c5da-4443-859a-c23c35709218)

<br />

<h2>Summary</h2>

In this lab, I created an S3 bucket to store the customers’ documents, making sure it was no public. I configured a bucket policy to deny any Amazon S3 actions over HTTP (TLS is not used).
And I configured an IAM role for an AWS Lambda function and set the role permissions. This lab enhanced my skills in configuring bucket policies and IAM roles and permissions. <br />
