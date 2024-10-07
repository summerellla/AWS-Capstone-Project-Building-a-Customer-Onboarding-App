<h1>Building-a-Customer-Onboarding-App</h1>
In your first capstone, you are a cloud application developer working for AnyCompany Bank. The bank has decided to develop and deploy a customer onboarding application on AWS. During customer onboarding, there is a significant exchange of information between AnyCompany Bank and customers. 

<h2>Description</h2>
Customer onboarding is one of the most important stages of a customer’s journey with a bank. During this stage, the bank and customers exchange significant information. This exchange involves obtaining documentation needed to meet regulatory requirements and provide relevant products and services to customers.

AnyCompany Bank has decided to develop and deploy a customer onboarding serverless application on AWS. With the proposed customer onboarding solutions on AWS, the bank can use artificial intelligence (AI), machine learning (ML), and digital tools to streamline the onboarding process. With these solutions, the bank can transform the ways that customers are onboarded and reduce friction during this essential process.

As a cloud developer at AnyCompany Bank, you have been assigned the task of building the new onboarding application on AWS. The application is named Know Your Customer (KYC).
<br />
In this lab, you create and configure the Document S3 bucket and Document Lambda function IAM role resources. These resources are highlighted in the following diagram.

Lab 1 architectural diagram.

![lab1](https://github.com/user-attachments/assets/f32de9e7-3376-4291-a8f0-f86cfc4a1ea6)


Image description: The diagram depicts the KYC application architectural diagram. The diagram highlights the key resources that you need to create and configure in this lab. These two resources are the Document S3 bucket and the Document Lambda function IAM role.

Services used in this lab
Amazon S3
Amazon S3 is an object storage service that offers industry-leading scalability, data availability, security, and performance. It stores and protect any amount of data for a range of use cases, such as data lakes, websites, built-for-the-cloud applications, backups, archives, machine learning, and analytics.

IAM
AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. With IAM, you can centrally manage permissions that control which AWS resources users can access. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.

AWS services not used in this lab
AWS service capabilities used in this lab are limited to what the lab requires. Expect errors when accessing other services or performing actions beyond those provided in this lab guide.
