
# AWS Cloud Quick Start Guide
![AWS](https://www.logo.wine/a/logo/Amazon_Web_Services/Amazon_Web_Services-Logo.wine.svg)

## TOC
[Overview of AWS Cloud](https://github.com/NagendraHV/markdown/blob/main/QSG_2_Nagendra.md#overview-of-aws-cloud)
[Getting started with AWS](https://github.com/NagendraHV/markdown/blob/main/QSG_2_Nagendra.md#getting-started-with-aws)
 - [Create a new account](https://github.com/NagendraHV/markdown/blob/main/QSG_2_Nagendra.md#create-a-new-account)
 - [Sign in to your AWS console](https://github.com/NagendraHV/markdown/blob/main/QSG_2_Nagendra.md#sign-in-to-your-aws-console)
	
## Overview of AWS Cloud

**Amazon Web Services** (AWS) is the leading cloud computing platform and it provides over 200 cloud services like computing, storage, database, etc over the internet. It is suitable for start-ups and large enterprises and is secure and cost-effective as you only need to pay as you use the services.

**AWS** provides services for many kinds of products and it is popular for its services like computing, database, storage, application development, analytics, game development, security, etc. **AWS** offers you free trials for many of its product services after you sign in to **AWS**.
![AWS]()


**Popular featured services of AWS**

* **Amazon EC2:** Amazon Elastic Compute Cloud is a cloud-based computing service that developers use to build applications and manage their application requirements.

* **Amazon S3:** Amazon Simple Storage Service is a cloud-based storage service that can be used for storing data and developers can access it for computing.

* **Amazon DynamoDB:** Amazon  DynamoDB is a managed NoSQL database service that is flexible and offers reliable performance.

* **Amazon RDS:** Amazon Relational Database Service (RDS) is a managed relational database service developers use to operate and access relational databases.

* **AWS Lambda:**   It is  a  computing service that helps developers do serverless computing and run code without the need for servers.

* **Amazon VPC:** Amazon VPC helps developers deploy resources in a private virtual cloud and gives complete control over the network environment.

* **AWS IAM:** AWS Identity Access Management helps control and manage user access to AWS services.

**Benefits**

* It offers a wide range of services in one place.

* It follows a pay-as-you-go policy making it cost-effective.

* It helps you manage your resources more efficiently.

* It offers a free trial for most of the services.

## Getting started with AWS
**AWS  Cloud** offers many services that you can access with an **AWS** account. You need to create a new free tier account and sign in to your **AWS** account to use the service.
### Create a new account
You can create a new free-tier account and start using free trials of the services.

**Prerequisites**

*	Root user email address

*	Valid phone number

*	Active Debit or Credit card

*	Valid ID (Driving license, PAN, Voter ID, or Passport)


To create,

1. On your browser, go to the **AWS** web page and select **Create an AWS Account.**
![AWS](https://github.com/NagendraHV/markdown/blob/b8be5270ddd303c399283487bf445f93a674a532/images/AWS0.png)
3. On the **Sign-up** **for AWS** page, perform the following steps:
	1. Enter the details for the following fields:
		*	Root user email address
		*	AWS account name
	2. Select **Verify email address**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws1.png)
	4.  Enter the verification code that is sent to your email and select **Verify**.
	5. In the **Create your password** section, create and confirm the Root user password and select **Continue (step 1 of 5)**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws3.png)
	6. In the **Contact Information** section, perform the following:
		a. Select one of the following:
		*	**Business – for your work, school, or organization**
		*	**Personal – for your own projects**
Let us select **Personal – for your own projects**.	

		b. Enter all the required contact details. 
		c.    Select the checkbox and  agree to the terms.
		d.   Select **Continue (step 2 of 5)**.
		![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws4.png)
		

	6.   In the Billing Information section, enter all the required payment details and select **Verify and Continue (step 3 of 5)**.
	![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws5.png)
	7.   Enter the OTP you received to confirm payment and select **Make** **Payment.**
	8.  In the **Confirm your identity** section, enter all the required details and select **Verify and Continue (step 4 of 5)**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws6.png)
	9.  In the **Confirm your identity** section, perform the following:
		*   Select the method to receive the verification code.  
		*  Select country code and enter the phone number.
		* Enter the captcha and select **Send SMS (step 4 of 5)**. 

		 ![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/AWS7.png)
	10.  Enter the verification code you received and select **Continue (step 4 of 5)**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws8.png)
	11.  Select your desired plan for your **AWS** account or select **Basic support - Free** and select **Complete sign up**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws9.png)
4.  Select **Go to the AWS Management Console**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws10.png)
5.  On the **AWS Management Console** page, select **Sign in to the Console**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws11.png)
6.  On the **Keep your account secure** page, select one of the options to register for **MFA** and select **Next** to activate **MFA** or select **Skip for now**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/MFA1.png)
![Console](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws12.png)
Your **AWS** account is created and **MFA** is activated.	
	










### Sign in to your AWS console
You can sign in to your **AWS** console using email address, password, and **MFA** PassKey.

**Prerequisites**
*	**AWS** account
*	Sign-in credentials: user email and password
*	**MFA** passkey


To sign in,
1. On your browser, go to the **AWS** web page and select **Sign in to the Console**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/sign%20in0.png)
2. On the **Sign** **in** page, perform the following:
	a. Select the user type as **Root user** and enter the email address.
	b. Select **Next.**
	![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/sign%20in2.png)
3.   On the **Root user sign** **in** page, enter the valid password and select **Sign** **in**.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/sign%20in3.png)
4.  On the **MFA** page, complete the authentication.
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/sign%20in4.png)
![AWS](https://github.com/NagendraHV/markdown/blob/077ba938087a218dbc629459799c02fac6f68b62/images/aws12.png)
AWS Console page is displayed
