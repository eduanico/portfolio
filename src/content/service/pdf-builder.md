---
title: 'Pdf Builder'
description: 'Fetch citizen information from Civil Registry API'
pubDate: 'Mar 13 2023'
heroImage: '/pdfbuilder.png'
---


This service help our customers to **build pdf** from **templates** using Spring Framework, JAVA and thymeleaf, as well as other libraries for other features.
It can build the pdf using different templates with variables sent in API REST request body, it can also **print a signature** with image, name, date and nui using a **location** sent in the request body.

Automate the signatures location if customers send a **word to find** in the pdf, it search for the word in the file and print the signature right **above it**, this is done by using a text reader engine.

#### Features
- Build pdfs using template and variables
- Stamp signatures rubrics sending positions or default positions on db
- Stamp signatures rubrics with automatic positions using a "word to find" in the pdf file