---
title: 'File Sender'
description: 'Fetch citizen information from Civil Registry API'
pubDate: 'March 13 2023'
heroImage: '/file-sender.webp'
---

File sender service is a API that can help us to **send signed files** to our clients with different options and transport methods.

This are some of the options:
- SFTP
- AWS S3
- REST API
- Others

All of this information is **encrypted**.
##### SFTP
Use an IP to connect to a server using a port, username and password to connect to the server and a directory where files are going to be send.

##### AWS
It uses AWS access key, AWS secret access and a Bucket to connect to S3 and upload files to their bucket in the path the users need to be saved. 

##### REST API
Using rest template to send files in the body as a form data request via API with the authentication method the user requires.

#### FEATURES
- Send files through SFTP
- Upload files to AWS Bucket
- Send files through REST API
- Send files with others methods such as onbase, SOAP, etc



