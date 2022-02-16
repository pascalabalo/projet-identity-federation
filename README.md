# AWS-Identity-Federation-SAML
A Self-Directed Journey to AWS Identity Federation Mastery - Microsoft variant
AWS Service/Feature Coverage:

AWS IAM users & roles
Architecture
The following image provides a visual representation of what you are about to construct during this initial exercise.
![image](https://user-images.githubusercontent.com/73201241/154366601-6652ae21-d95a-439f-986c-2a2e1e98de3a.png)


Exercise architecture

Attention

You should use this architecture and associated AWS CloudFormation template for demonstration and learning purposes ONLY. The template contains default passwords and has not been hardened in any way beyond the default configuration provided by the Amazon Machine Image (AMI). Furthermore, the IdP infrastructure has been simplified to focus on the learning objectives and is not set up for availability and scalability, and is not appropriate for production use.

Prerequisites
The following list identifies the prerequisites for this workshop. If you have not assembled these elements, please the take time to do so now:

A minimum of one (ideally two) non-production AWS account of which you are comfortable changing the security posture.
To participate in the multiple account portion of the workshop, you must have two non-production AWS accounts. Within each AWS account, you need an IAM user with the following permissions: iam:*, ec2:*, and s3:*
To create new AWS Account, click here and then follow the on-screen instructions.
A basic VPC in one of your accounts using the us-east-1 Region and including one public subnet, an IGW, and appropriate routing tables.
Note: The default VPC created for you meets these requirements. Unless you have intentionally deleted this VPC, no action is required.
Note: If you do not have a basic VPC available, or would simply like to create a new one for this exercise, you can utilize this CloudFormation template
A working Python 3.x installation on your local workstation. Python downloads
A working AWS CLI installation on your local workstation. See the instructions.
The Firefox browser with the SAML tracer add-on installed
A working RDP client on your local client machine. The Remote Desktop Client application is a native utility for Windows. Apple's Microsoft Remote Desktop or Microsoft's Remote Desktop Connection Client for Mac are common choices for Mac. Linux users can use rdesktop or any of the RDP clients available through your relevant distribution's software repository.
Permissions on your local workstation to edit host file entries.
