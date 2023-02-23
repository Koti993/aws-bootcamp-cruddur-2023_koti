# Week 0 — Billing and Architecture
	Using billing preference and providing mail ID to get the billing alerts 

	Used cloudwatch alarms to setup the billing alert

	Created Budget for the AWS account

	Activated Cost allocation tags named as Name, Env, Descripton, account

	Understanding how cost explorer works as for generating reports 

	Enabled MFA for root account and user account in AWS

	Exploring IAM ,CloudTrail, Organizations services and Understading its use case 

	Experimenting with CLI commands for Budget and SNS notification

	Setting up workspace in gitpod and Validating the access to VS code

	Created Lucid Chart with respect to the project

Refernce for lucid chart -> https://lucid.app/lucidchart/invitations/accept/inv_219bf4e2-59e3-4b7a-8b26-d173b8b3f367

![image](https://user-images.githubusercontent.com/111625550/220999319-976d4614-342c-4e29-a078-423317082512.png)

--------------------------------------------------------------------------------------------------------------
Notes
---------------------------------------------------------------------------------------------------------------
> Billing Dashboard
2 ways to set billing alert
*aws calculator for a month it estimates the cost for 730 hrs
10 alarms are free 
* Billing Data only shows up in Northern Virginia Region
______________
Cloud security
______________
Protects and prevents further technical  risk from Data, application and services in cloud environment

Why cloud security?
>Reduces data breach
>Network, Application and service is protected in cloud env agaianst malicious data theft
>Reduces Human error
_____________________
CloudTrail
_____________________
Keeps Track of API calls from the services and is available as Report with User and Resource information
Audit logs for Incident Response/Forensic
Monitor Data Security & Residence
_________________
IAM users
_________________
3 kinds of Users
IAM user/Local AWS user
System User
federated user
**Principle of least privileges
IAM roles
2types of IAM roles and Policies
Attached to user 
attached to resource
------------------------------------------------------------------------------------------------------------------
