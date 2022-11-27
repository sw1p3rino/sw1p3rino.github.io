---
title: Encrypt Gmail Emails with PGP
date: 2022-11-20 12:00:00 +0200
categories: [Security Advisories]
tags: [Encryption, Privacy, Email, Gmail, FlowCrypt]
---

In this guide I will explain the setup of an easy way to encrypt and decrypt emails sent and received via gmail. I will be doin this using the FlowCrypt browser extension.

**Currently this blogpost is only applicable for Firefox, Google Chrome and the Brave browser.**

I will be showcasing it for firefox but it is basically the same for the others. So here we go:

## Install the FlowCrypt browser extension
1. Access the [FlowCrypt](https://flowcrypt.com/) page and click on **Get Firefox Extension**![Step 1 Installation](\assets\images\posts\FlowCrypt\FlowCrypt_Startpage.png)

2. Click on **Continue to Installation**![Step 2 Installation](\assets\images\posts\FlowCrypt\FlowCrypt_AllowInstall.png)

3. Add the FlowCrypt browser extension![Step 3 Installation](\assets\images\posts\FlowCrypt\FlowCrypt_Add.png)

## Setup FlowCrypt
1. Click on the FlowCrypt symbol in the corner![Step 1 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_Korner.png)

2. Use the Google sign in![Step 2 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_gmail1.png)

3. Choose the account for which you want to use FlowCrypt![Step 3 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_gmail2.png)

4. Give FlowCrypt the permission to manage, read and send emails![Step 4 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_gmail_permissions.png)

5. Create a new key![Step 5 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_NewKey.png)

6. Choose a strong passphrase that you do not use elsewhere, and click **Create and Save**![Step 6 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_Keypass.png)

7. I DO NOT advice you to write down your password using pen and paper. Please memorize the password or use a password manager like [KeePass](https://keepass.info/). Check the box and click **Ok**![Step 7 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_WriteDown.png)

8. And you are DONE! Login to your Gmail account to compose an email.![Step 8 Setup](\assets\images\posts\FlowCrypt\FlowCrypt_Done.png)

## Shoot me an Email
If you want to send me an encrypted email you need to send me your PGP public key so i can responded. Just sign your email with the certificate symbol below and klick send. Signing your email automatically attaches your public key.
![Send Mail](\assets\images\posts\FlowCrypt\FlowCrypt_PubKey.png)