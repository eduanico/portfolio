---
title: 'ID4Face'
description: 'Id4face Api for Eclipsoft S.A.'
pubDate: 'Oct 19 2022'
heroImage: '/id4face.webp'
---


### Passive Liveness Validation API

Built using Java with Spring Boot as Framework.
I managed to validate a person liveness integrating our country civil registry to allocate the reference image used by our validation engine in AWS Rekognition.
Using metrics to prevent **spoofing attacks** and **identity duplicity attacks**.  
This API helped our customers to validate persons liveness in an easy way using API-REST libraries and security methods as JWT Tokens. Some production examples of use are in the **electronic signature** area and **onboarding flows**. 

Link to try it for free: <a href="https://id4face.eclipsoft.com" target="_blank">ID4Face</a>

##### Some more features...

Besides that, it has some more features to validate front and rear id cards for Ecuadorian citizens using the country civil registry information, also to validate a person whitin a video and to validate if a person says the correct code in a video analizing audio to text and voice recognition. 

It auto generates a extra-document when validation is done, showing reference and evidence images and the response of the validation request.

In addition, it can read and get information from de identification card and returned it as a json response.

Build reports and download them using filters as well to get all events from a client in an specific date.

#### Features
- Upload reference image
- Validate photo with Check-Id
- Validate photo without Check-Id
- Validate front id card
- Validate rear id card
- Validate selfie photo
- Get text from id card
- Retrieve validation extra document
- Voice recognition
- Video validation
- Query and download report by filters
- Restrictions based on roles
- JWT Security Authentication 