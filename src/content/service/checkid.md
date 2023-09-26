---
title: 'Check Id'
description: 'Fetch citizen information from Civil Registry API'
pubDate: 'Jul 01 2022'
heroImage: '/check-id.png'
---

Built using Spring Framework with Reactor and Java. It is a high load service so reactive programming was a logic option to take charge of this requests load. 
Fetching citizen data from our Country Civil Registry that can be either **demographic** or **biometric** data of the citizen.

It has a feature as well to validate data using nui for demographic information and nui with fingerprint for biometric information, where the customer sends data to validate if it is correct.

#### Features
- Fetch citizen demographic data
- Fetch citizen biometric data
- Validate citizen demographic data
- Validate citizen biometric data
- Restrictions based on roles
- JWT Security Authentication 
- Query and download reports by filters