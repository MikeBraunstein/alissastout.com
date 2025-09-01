Professional website ReadMe

Before you begin:
1. Setup an AWS enviornment: AWS Free Tier https://www.google.com/aclk?sa=L&ai=DChsSEwiqnczh5rePAxW5Un8AHdy4IBkYACICCAEQABoCb2E&ae=2&aspm=1&co=1&ase=2&gclid=CjwKCAjwiNXFBhBKEiwAPSaPCRIKY7CANdmDwU-5Gy-D0M6OD_RAJ1Kzrl7rJ1jER-EFzzlR_WxkGhoCCmoQAvD_BwE&cce=2&category=acrcp_v1_35&sig=AOD64_0idy-FtYA-8XEj88IASdgXWNvNaw&q&nis=4&adurl&ved=2ahUKEwj7ksTh5rePAxVXgmoFHdUoGccQ0Qx6BAgXEAE
2. Create an IAM user apart from your root: IAM User https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html
 - Always create 2 factor authentication and other security best practices for your Root and subsequent accounts!!!
3. Create an Access Key for your accounts
 - WARNING: Creating an access key is dangerous and alternative methods should be used for production data.
4. (optional) update your Config and Credentials file in your .aws/ folder under your user account directory.
 - This will help you to quickly and easily make AWS CLI commands while you work.
 - WARNING: Be sure to secure these files and/or change your credentials and access keys regularly.
5. Download this repository locally:
   1. download and install AWS CLI
   2. use the command: "aws s3 cp <source> <destination>
