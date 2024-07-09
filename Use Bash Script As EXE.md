# Use Bash Scripts and Run them like EXE's

This page will cover how to use and run bash scripts in numerous ways. We will primarily focus on running them like EXE’s


# What is a BASH Script?

A BASH script is a low level simplified programming language that allows user to easily write them in a Notepad app of their choice. The commands that can be executed with bash follow what you would normally input into a Command Line / Terminal. Bash scripts are very useful for automating simple Terminal based tasks. 

# Windows Setup

This section will cover how to set up running the bash scripts on a Windows Machine. 

## 1. Prerequisites

This tutorial will assume you have folowed the Git Installation and have it set up correctly. We will also assume you have installed Notepad++

> [Git Installation](http://wiki.uwformulanano.ca/en/Onboarding/ServersSoftwareApps/GitInstall)
{.is-info}

> [Notepad++ Installation](http://wiki.uwformulanano.ca/en/Onboarding/ServersSoftwareApps/NotepadPPInstall)
{.is-info}


## 2. Download Testing Script

In this setup we will be using a simple yet useful script developped which will speed up the login process to Alex’s Server. 

 

First Step is to download the folder located in the following link.

> [Alex Server Login](https://uofwaterloo-my.sharepoint.com/:f:/g/personal/r37mille_uwaterloo_ca/ElATElM0iYNBi5btpti6HtUBupHE8__remR11q_GtSx00g?email=n2frey%40uwaterloo.ca&e=4LXIKf)
{.is-info}

Extract the downloaded folder.

![BASH_EXE_1](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/04e5d993-b0c6-4d71-976d-62e8fc94efe2)


In the folder you will find a Shell Script named Alex Server Login. We will open it an see it’s contents using Notepad++

## 3. Investigate Bash Script
Click on the Shell Script once and then Right Click it. Select “Edit with Notepad++”. The script should look similar to the following.

![BASH_EXE_2](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/b0caf63a-8caa-4b6f-bf8b-986cc754e737)


This script automates the opening of Command Prompt/Terminal, and then attempts to login to the server. If you have not established your RSA Key you will be required to end the password on start.

We can now close the Notepad++ and we will have the script opened in CMD. 

## 4. Opening Shell Scripts in Command Prompt/Terminal
Find the recently downloaded Shell Script and Click it Once. Right Click it after that and pick “Open With” > “Choose another app”

![BASH_EXE_3](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/33209fd5-24a1-4dcf-bbd2-aa2b0fa6379a)


Click the “Always open .sh with this app” checkbox, and find the Git for Windows App and select it. Click “OK”

![BASH_EXE_4](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/70c04455-e4f9-41b6-9fcf-ce202d388ae7)


A new instance of CMD may open with something like the following displayed on it.

![BASH_EXE_5](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/2e7e0e5e-7144-4980-92a0-5a8032e85277)


> You may be prompted with the password if the RSA Key is not setup.
{.is-info}

This means everything has worked. Now if you go back to Windows File Explorer and double click on your shell script, it should open a new instance of CMD and do the exact same thing. 

![BASH_EXE_6](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/f6f2318f-93ab-4a0a-aee4-743df2ece241)


You will no be able to accelerate tedious and repetitive tasks using Shell scripts made by the Software Team
