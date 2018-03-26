---
title: "Proxy Servers for Skype for Business Online"
ms.author: tonysmit
author: tonysmit
manager: serdars
ms.reviewer: jastark
ms.date: 01/22/2018
ms.topic: article
ms.assetid: 7acaf2c2-35fa-490f-84cd-822e446e0fc7
ms.tgt.pltfrm: cloud
ms.service: skype-for-business-online
ms.collection: Adm_Skype4B_Online
ms.audience: Admin
appliesto:
- Skype for Business 
- Microsoft Teams
localization_priority: Normal
f1keywords: None
ms.custom:
- Optimization
description: "This article will help you with guidance about using a proxy server with Skype for Business."
---

# Proxy Servers for Skype for Business Online

This article will help you with guidance about using a proxy server with Skype for Business.
  
## Not using a proxy server is recommended

Microsoft recommends using the Internet and a simple network design for optimal connectivity and performance in Office 365. A key goal in the network design should be reducing the round-trip time (RTT) from your network into the Microsoft global network and ensure that the network traffic is not hair pinned or centralized to specific locations. Microsoft also does not support or recommend the use of proxy devices or any other infrastructure that may filter, decrypt, inspect or take protocol or content specific action on Office 365 traffic. Use the Office 365 connectivity principles to manage your traffic and get the best performance when connecting to Office 365. See https://aka.ms/Office365Networking

As such, When it comes to Skype for Business traffic over proxies, Microsoft recommends bypassing proxies. Proxies don't make Skype for Business more secure because its traffic is already encrypted.
  
And having a proxy can cause issues. Performance-related problems can be introduced to the environment through latency and packet loss. Issues such as these will result in a negative experience in such Skype for Business scenarios as audio and video, where real-time streams are essential.
  
## If you need to use a proxy server

Some organizations have no option to bypass a proxy for Skype for Business traffic. If that's the case for you, the problems mentioned above need to be kept in mind.
  
Microsoft also strongly recommends:
  
- Using external DNS resolution
    
- Using direct UDP based routing
    
- Allowing UDP traffic
    
- Following the other recommendations in our Networking guidelines:
    
  - [Media Quality and Network Connectivity Performance in Skype for Business Online](https://support.office.com/en-us/article/Media-Quality-and-Network-Connectivity-Performance-in-Skype-for-Business-Online-5fe3e01b-34cf-44e0-b897-b0b2a83f0917)
    
  - [Optimizing your network for Skype for Business Online](https://support.office.com/en-us/article/Optimizing-your-network-for-Skype-for-Business-Online-b363bdca-b00d-4150-96c3-ec7eab5a8a43)
    
Following this guidance should minimize potential problems.
  
## Related topics

[Optimizing your network for Skype for Business Online](https://support.office.com/en-us/article/Optimizing-your-network-for-Skype-for-Business-Online-b363bdca-b00d-4150-96c3-ec7eab5a8a43)

## Feedback?
To provide product feedback or to let us know how we're doing, see [Skype for Business Feedback](https://www.skypefeedback.com).
