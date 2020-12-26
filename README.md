# AeroGelWiki
A Serverless Wiki 

# Description
The aim of this is to have a wiki that is statically served from blob storage. When a page is to be edited a JS Markdown editor will be used. The editor will write Markdown to blob storage. A function will then process new markdown files in blob storage and write them to the blob storage for static serving. 

The name comes from Aero Gel - the lightest substance around. 

# ToDo 
- Write a lambda that takes Markdown from one S3 bucket and processes it into HTML in another for statically serving the wiki
- Get one of the JS Markdown editors to read a file from one S3 bucket and write back into it 
- Create the terraform code for the whole setup 

# Links
- https://read.acloud.guru/how-to-add-file-upload-features-to-your-website-with-aws-lambda-and-s3-48bbe9b83eaa
