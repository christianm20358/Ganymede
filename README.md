# The Ganymede Project #
**If you could see the earth illuminated when you were in a place as dark as night,**
**it would look to you more splendid than the moon - Galileo Galilei**

This repository is for documenting the development of a Cybersecurity application that will eventually
be able to provide tools corresponding to each of the CIS18 Critical Security Controls. To that end, there
will be several major individual applications:

**Ganymede**

Ganymede will be the brain that coordinates the work of the other applications. It will track logging and incidents and 
will be the main point of contact for security professionals to oversee events across the entire domain. 

**Europa**

Europa will be a webapp, the main feature will be a credential store free for anyone to use, and optional additional services geared
towards Enterprises. This will be the face of the ecosystem to most non-security users of the Ganymede ecosystem. There will be many
additional features documented in the wiki page.

**Titan**

Titan will be a desktop application providing endpoint protection and data collection that will be sent to Ganymede. It will not have a gui,
it will be invisible to end users. Eventually it will go beyond tracking and logging and provide anti-malware and anti-virus capabilities
as well.

# Completed Features #
 - [X] Websocket API - Go

 - [X] Random Password/Passphrase Generator - Go

 - [X] JSON Encoder/Decoder - Go

# In Progress Features #
 - [ ] Password vault - Vuejs front end

 - [ ] Axios API Endpoint - JavaScript

 - [ ] JWT for Websocket Security - Go

**Europa Password Generator Rough Mockup**

![image](https://user-images.githubusercontent.com/82122466/168933757-c1e3ca57-90ce-4234-8fee-36d3936012b0.png)

# Version 1.0 Desired Features #
Functions:

 - [ ] User/Device Database
 - [ ] AAA Server
 - [ ] Password Generator
 - [ ] MISP Client
 - [ ] Password Storage
 - [ ] Password Health Checking
 - [ ] MFA Server

Screens:
 - Profile
 - Vault
    - Folders
    - Favorites
    - Vault Item Type (Logins, )
 - Password Generator
 - File Encryption
 - URL Decoder
 - MFA Authenticator
 - Password Health
