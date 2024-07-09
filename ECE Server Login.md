# Upload Key to Authman

## Generate a key

Start by opening a terminal and type the following,

```
ssh-keygen -t ed25519
```

## Upload the key to Authman

Go to [SSH Authman](https://authman.uwaterloo.ca/) and login your UWaterloo credentials.

Click <kbd>+Add Key</kbd>.

Go to your terminal and type the command,

```
cat ~/.ssh/id_ed25519.pub
```

Copy the entire string. It will look like,

```
ssh-ed25519 *you public key*
```

# 2. Connect to the Campus VPN

Go to the Following website to get the VPN (If you don't have it)

[Anyconnect Download](https://cn-vpn.uwaterloo.ca/)

Enter the following
>  Username : WatID
Password 1 : WatID Password
Password 2 : push
{.is-info}

Accept the Push on the Duo App

Download the VPN from that link

Install as normal


# 3. Login
Once installed open up your tray icon and right click the Cisco, a button for connect will appear
![ECE-Login-1](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/7223e0a7-7858-49d6-b0ff-498651bd3507)

![ECE-Login-2](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/a2c685d1-80dd-49e4-9654-f3c3a444c7de)



Click it

Put in your login information as before

>  Username : WatID
Password 1 : WatID Password
Password 2 : push
{.is-info}

# Auto Login Script

Download the Zip File from the Github we made
[ECE Login Maker](https://github.com/UWFormulaN/ECE-Server-Login-Script-Maker/releases/tag/ECE-Login-1.0.0)

Extract it and open it

Find the Bash Script inside and double click it

![ECE-Login-3](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/8521b7ca-fca8-4d91-963f-4bd65dbc2235)


The Command window will ask for your WatID. Enter it without spaces

Save the Bash script to your preferred location and preffered name

Run the Bash Script to Login. Make sure you are connected to VPN when doing so

Enjoy
