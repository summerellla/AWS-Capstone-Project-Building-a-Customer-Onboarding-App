<h1>Capstone Project: Building a Customer Onboarding App - Lab 02</h1>
<h2>Description</h2>
As a cloud developer at AnyCompany Bank, you have been assigned the task of building the new onboarding application on Amazon Web Services (AWS). The application is named Know Your Customer (KYC).<br>
<br>


This is the second lab of a series of labs that build the KYC application for banking services. Your goal is to build the solution over 10 labs. In each lab, you build a few components of the overall solution.<br>

In this lab, you create an Amazon DynamoDB table to store customer data, create an Amazon Simple Notification Service (Amazon SNS) topic to send application notifications, and add DynamoDB and Amazon SNS permissions to the AWS Lambda function AWS Identity and Access Management (IAM) role.
<br />



<b>Lab 1 architectural diagram</b> <br />
![image](https://github.com/user-attachments/assets/b5712124-8f7b-424a-b587-9a030cfe299e) <br>

Image description: The diagram depicts the KYC application architectural diagram. The diagram highlights the key resources that you must create and configure in this lab. These resources are the Customer DynamoDB table, the Document Lambda function IAM role, and the SNS topic.<br>

<h2>Services used in this lab</h2>

<b>Amazon S3</b><br>
Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It stores and protect any amount of data for a range of use cases, such as data lakes, websites, built-for-the-cloud applications, backups, archives, machine learning (ML), and analytics.<br>

<b>Amazon SNS</b><br>
Amazon Simple Notification Service (Amazon SNS) is a managed service that provides message delivery from publishers to subscribers (also known as producers and consumers). Publishers communicate asynchronously with subscribers by sending messages to a topic, which is a logical access point and communication channel. Clients can subscribe to the Amazon SNS topic and receive published messages using a supported endpoint type, such as Amazon Data Firehose, Amazon SQS, AWS Lambda, HTTP, email, mobile push notifications, and mobile text messages (SMS).<br>

<b>DynamoDB</b><br>
Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability. DynamoDB lets you offload the administrative burdens of operating and scaling a distributed database so that you don’t have to worry about hardware provisioning, setup and configuration, replication, software patching, or cluster scaling. DynamoDB also offers encryption at rest, which eliminates the operational burden and complexity involved in protecting sensitive data.<br>

<b>IAM</b><br>
AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.<br>

<h2>Walkthrough:</h2>
