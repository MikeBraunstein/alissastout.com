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
5. Configure s3 bucket(s) for statick web hosting:
   To enable static website hosting
    1. Sign in to the AWS Management Console and open the Amazon S3 console at https://console.aws.amazon.com/s3/.
    2. In the left navigation pane, choose General purpose buckets.
    3. In the buckets list, choose the name of the bucket that you want to enable static website hosting for.
    4. Choose Properties.
    5. Under Static website hosting, choose Edit.
    6.  Choose Use this bucket to host a website.
    7.   Under Static website hosting, choose Enable.
    8.   In Index document, enter the file name of the index document, typically index.html.
    9.   The index document name is case sensitive and must exactly match the file name of the HTML index document that you plan to upload to your S3 bucket. When you configure a bucket for website hosting, you must specify an index document. Amazon S3 returns this index document when requests are made to the root domain or any of the subfolders. For more information, see Configuring an index document.
    10. To provide your own custom error document for 4XX class errors, in Error document, enter the custom error document file name.
    11. The error document name is case sensitive and must exactly match the file name of the HTML error document that you plan to upload to your S3 bucket. If you don't specify a custom error document and an error occurs, Amazon S3 returns a default HTML error document. For more information, see Configuring a custom error document.
    12. (Optional) If you want to specify advanced redirection rules, in Redirection rules, enter JSON to describe the rules.
       For example, you can conditionally route requests according to specific object key names or prefixes in the request. For more information, see Configure redirection rules to use advanced conditional redirects.
    13. Choose Save changes.
    14. Amazon S3 enables static website hosting for your bucket. At the bottom of the page, under Static website hosting, you see the website endpoint for your bucket.
    15. Under Static website hosting, note the Endpoint.
    16. The Endpoint is the Amazon S3 website endpoint for your bucket. After you finish configuring your bucket as a static website, you can use this endpoint to test your website.
