---
title: 'Webhook'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Mar 31 2023'
heroImage: '/webhook.svg'
---


This service is in charge of **receiving** and **saving data** that is **send to it**.
It receive logs and files and save them into a local directory in txt and pdf format.

Used by **Signbox** and **Oneshot** webhook urls on request to save information about the current state of the signature request.
And **save the signed file** into the local directory that are receive from Signbox service.

#### Features
- Save all information send to log and files enpoints
- Retrieve all information as a GET request to log or file endpoint
- Save pdf file in file endpoint receive from a POST request
- Save log file in log endpoinst receive from a POST request