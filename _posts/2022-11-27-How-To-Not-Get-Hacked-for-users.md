---
title: How to not get hacked (for users)
date: 2022-11-27 21:00:00 +0200
categories: [Security Advisories]
tags: [Encryption, 2FA, Passwords, Enduser]
---

In this guide, I would like to present simple, basic and easy to understand steps to protect yourself from cyberattacks. This should be understandable for everyone and I will follow up in future posts on why these steps are needed.

## 1. Use 2-Factor-Authentication at least on important accounts
Honestly, you should use 2-Factor-Authentication (2FA) everywhere you can. But the absolute minimum is for everything thats connected to your bank account, like PayPal, Amazon or your banking app and your email account. Why your email account?
Because it is very likely that the passwords of **most if not all of your accounts** can be reset with your email account. This means that all of these accounts can easily be compromised if you lose control of your email account. This can include your PayPal, Amazon, Facebook, Instagram, Twitter, Steam, University or School accounts and many more. Introducing a second authentication factor prevents attackers from getting into your account, even if they obtain the password.

## 2. Use unique and strong passwords
Don't reuse passwords, especially not for important accounts like those for payment or email address. You can have a password stronger than Conor McGregor and still have it compromised. But how, you may ask? Let my introduce you to the concept of willful negligence. 
Passwords should  **never** be stored in plain text, but run through a hashing function that makes the password irreversibly  different. Nevertheless, there are some website owners that put your unecrypted password in places where it does not belong:

<iframe width="560" height="315" src="https://www.youtube.com/embed/WBwkPI3JMEE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Therefore, if such a webpage is hacked, (which is likely due to the obvious lack of cybersecurity awareness) your password is exposed and all accounts where the same password is used, can be compromised. 

As a sidenote, a password can not be considered unique if you just change a slight detail. Attackers will figure out that "ThisIsMyPassword13" could be your new password, if the password "ThisIsMyPassword12" was leaked. Furthermore, your passwords should be [strong enough](https://www.webroot.com/us/en/resources/tips-articles/how-do-i-create-a-strong-password) to be actually protective. A simple generation of secure passwords can be done by a [password manager](#3-hail-the-almighty-password-manager)  


## 3. Hail the almighty password manager
Unique passwords for every account? How could you possibly remember all of them? Here is the good news, you don't have to. There are applications called password managers which can store all your passwords securely. My favorite password manager is [KeePass](https://keepass.info/). It can store and generate passwords and even autofill them, so I don't have to type my 25 character password. You only have to remember **one master password** to access all the other ones, but it has to be strong!
>It is very important to backup you password manager database, or you might loose access to all your accounts at once :/
{: .prompt-warning }

## 4. Encrypt your PC's hard drive
It is very likely that your PC's or Laptop's hard drive is unencrypted if you didn't explicitly activate encryption. This means everyone with access to your computer has access to all your files and data. Whoever found or stole your PC can just remove the hard drive, plug it into his own PC and use it like it is just another drive (since it is), with all your files on it. This takes no more than 3 minutes and requires little skill. I therefore strongly suggest that you encrypt your hard drive with something like [VeraCrypt](https://www.veracrypt.fr/en/Home.html) or [BitLocker](https://support.microsoft.com/en-us/windows/turn-on-device-encryption-0c453637-bc88-5f74-5105-741561aae838#ID0EBD=Windows_10).

## 5. Update your systems
If you regularly click away your update popup, I would ask you to reconsider. Updates are often security-related and are released because attackers have found a new way to exploit a vulnerability in the software. Keeping your system up to date is the easiest way to close these holes in your security. This is not only the case for your operating system (e.g. Windows) but also the software you are using (e.g. Firefox). Install updates as soon as they are available. Otherwise, your computer may be compromised just by being connected to the Internet.

## Change your default passwords
All devices you buy that provide any login functionality have potentially default passwords. These passwords can easily be googled  or read in the manual. This includes your Network Attached Storage (NAS), Router, Switches and many more. If you have internet access at home, you likely have a router which is using default credentials, if you didn't change it. Everyone, who knows which router you use, can just google your username and password. Whole [websites](https://192-168-1-1ip.mobi/default-router-passwords-list/) are dedicated to just listing the credentials of such devices. To avoid that someone maliciously configures or just breaks your device, I recommend changing the default username and password. 

On a sidenote, this is not only the case for devices connected to a network. If you have an electronic safe it is likely that it has **two** pins to open it. The normal and the master pin. Read the manual and **change both** or else anyone with the ability to google has access to the contents of your safe.



Please be aware that this list ist not exhaustive and could contain many more steps. In my opinion, these are just the simplest steps that achieve the greatest effect.