# RSA Key Setup

This page will cover how to setup an RSA key for your device and no longer need to enter the password to login to Alex’s Server

# What is a RSA Key For?

The RSA Key will allow a person who has it setup to seemelessly connect to a SSH connection without the need of a password. 


# Windows Setup

## Prerequisites
We will assume you've completed the following 2 tutorials

### Git Bash
> [Git Installation](http://wiki.uwformulanano.ca/en/Onboarding/ServersSoftwareApps/GitInstall)
{.is-info}

### Notepad ++ Installation
> [Notepad++ Installation](http://wiki.uwformulanano.ca/en/Onboarding/ServersSoftwareApps/NotepadPPInstall)
{.is-info}

## 1. Open Git Bash
Open a new Instance of Git Bash

![RSA_Key_1](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/cf08eb2d-9b62-4258-a3c4-be0ee92d5b25)

![RSA_Key_2](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/f000b5fd-dddf-4534-89a2-abfdb70d10a5)


Move to the “.ssh” folder using the following command

> cd .ssh
{.is-info}


![RSA_Key_3](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/caf4ecc8-61ae-4719-9758-5e674ad4a5c9)


Use the following command to create an RSA Key

> ssh-keyge -t rsa
{.is-info}


You will be prompted with a few things press “Enter” for all of them. You will receive something similar to the following


![RSA_Key_4](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/2701d22e-cdc4-4301-894e-4cf79de92538)


Now enter the follwing command

> ssh-copy-id -i id_rsa.pub -p 55515 formulan@69.60.237.4
{.is-info}


![RSA_Key_5](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/d29806b4-75f8-4a63-84e0-281b54f5f366)



Enter “yes”

![RSA_Key_6](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/368a6c5c-0c31-433c-829d-01ddf2e5f6e9)

Enter the FormulaN Server password for the last time. You can find it here

> [Alex Server Login](http://wiki.uwformulanano.ca/en/Onboarding/ServersSoftwareApps/AlexServerLogin)
{.is-info}

![RSA_Key_7](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/7c483d85-0a73-409f-bf7d-73ee6093ed28)

Now Test out the following command

> ss -p 55515 formulan@69.60.237.4
{.is-info}

If done right you will not be prompted with a password and will receive the following

![RSA_Key_8](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/8e472047-2c7e-4c60-84dd-7a8ac93c0759)

# Testing Login Script

Download the Bash Login script from the following link 

> [Alex Server Login](https://uofwaterloo-my.sharepoint.com/:f:/g/personal/r37mille_uwaterloo_ca/ElATElM0iYNBi5btpti6HtUBupHE8__remR11q_GtSx00g?email=n2frey%40uwaterloo.ca&e=4LXIKf)
{.is-info}

![RSA_Key_9](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/ea3483a1-1a1f-4498-bf60-9843215eb14c)

Make sure you’ve completed the following tutorial

> [Use Bash Scripts as EXE's](http://wiki.uwformulanano.ca/en/Onboarding/ServersSoftwareApps/BASHEXE)
{.is-info}

Double Click on the Shell Script, A Command Prompt / Terminal Window should open.

If everything has been setup correctly you will receive the following, and will have logged into the server without the need for a password

![RSA_Key_10](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/47c97a8c-1fed-4e4e-8b4a-10e1b07996c3)






