# Sleep Easy Backups
The program creates compressed backups for cloud accounts (Google, Dropbox, OneDrive, etc)

## Background
Imagine the following scenarios: 
- Someone got the credentials to your cloud account (Google, Dropbox, OneDrive), deleted all your documents, and emptied the trash. 
- You delete an email, certain that you'll never need it. A few days later, you realize that you need the email.
- You need to access a document saved in the cloud, but the website is down and you don't have local copy of the document.

What now? 

The best option might be recover from a physical backup that stored locally or on another cloud account. Many cloud providers do not natively support any backup. Sleep Easy Backups intends to solve the problem by automating backups for cloud services, which allowing users to sleep easy.

----

## Goal
- Introduce an program that don't have technical knowledge requirement to use

### Features
- Compressed backup
- Incremental and full backup
- Option to configure backup schedule
- Summary and alerts emails

### Cloud Providers
- Google GSuite (GDrive, Gmail)
- Microsoft OneDrive (OneNote)
- Dropbox
- Facebook
- Twitter
- Instagram

----

## Roadmap
#### Implement primary features
- [ ] Compressed backups for each API [In progress]
- [ ] Interactive CLI
#### Implement secondary features
- [ ] Incremental backups
- [ ] Automate backups
- [ ] Summary and alert emails
#### Implement tertiary features
- [ ] GUI
- [ ] User configuration
#### Create an Android App with exists codebase
