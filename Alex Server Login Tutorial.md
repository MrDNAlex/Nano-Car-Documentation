# Server Login

## Login Info
Username : formulan
Password : NanoCar10^-9
SSH port : 55515
Remote Desktop Port : 55516
IP : 69.60.237.4


## Login Commands
Commands needed to login into the server

### SSH
Command needed for SSH Login

> ssh formulan@69.60.237.4 -p 55515
{.is-info}

### Remote Desktop
Command needed for Remote Desktop Login
> 69.60.237.4:55516
{.is-info}


# Windows
This covers how to login through SSH and Remote Desktop on Windows OS

## SSH Login

SSH stands for Server Side Host, this will allow you to connect to the server through the Terminal / Command Line App on your Operating System. The downsides to this method is it’s more complicated nature and it’s visual limitations as all you can do is see text.

### 1. Open Terminal in Admin Mode
The first step is to open the terminal with administrator privileges. 

In the Windows Search bar type “Terminal”


![alex_server_login_1](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/c20ef064-2a9f-4bc4-bce0-4e7d73f83e17)


Click the “Run as administrator” button, you will be prompted with a admin pop up.

Click Yes to allow the app to make changes 

A Terminal Instance should now be open

![alex_server_login_2](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/4254bcee-d19b-4f4c-950b-a047547b0393)


You may receive text that will end with (yes/no). Type in “Yes” and click “Enter” in the command prompt.

### 2. Type in Login Command
Type in or Paste in the Following Command

> ssh formulan@69.60.237.4 -p 55515
{.is-info}

Press enter and you should be prompted with a password

![alex_server_login_3](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/8dd8020e-d431-4f75-b4c9-77aeffbd22ee)


### 3. Enter Password


> As you type nothing will seem to appear. Do not worry about it, you are actually typing. Focus on inputting the password.
{.is-warning}

Enter the password:

> NanoCar10^-9
{.is-info}


### 4. Successfully Logged In

You will know if you're logged in if your Terminal looks like the following

![alex_server_login_4](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/42e728e1-c343-4660-b04b-80374dce9391)

## Remote Desktop Login

Remote Desktop is a way to login to a computer from a outside the network and have as close to an identical experience as if you were there in person. This will provide a GUI (Visible UI) that the user can interact with. This is very helpful if the tasks require visual assitance and understanding and allows you to use the server similarly to you would Windows.

### 1. Open Remote Desktop App

Remote Desktop can be found by typing “Remote Desktop” in the Windows Search Bar.

Admin access is not needed. Open the app as you would normally

![alex_server_login_5](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/9dabff49-457c-423a-b82a-4543e725a2b7)


### 2. Modify Settings

Given this screen click the “Show Options” Drop Down

![alex_server_login_6](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/e3d80f57-3832-4b12-8d4e-06549295cc67)


This will expand to this screen

![alex_server_login_7](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/5561e230-d465-477a-9f9f-da18771b297f)


Go to the Display tab and lower your resolution to around 720p

![alex_server_login_8](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/0dab27b5-d91b-437d-babc-03fa9931b91f)


Go back to the General Screen and click “Hide Options” to return to the following screen.

![alex_server_login_9](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/f4ef3f24-b269-4863-9575-c5de1e599f6b)


### 3. Logging Into Server

In the “Computer” Text Box enter the following command and click “Connect”

> 69.60.237.4:55516
{.is-info}

You may receive a warning type screen. Click the do not show again box and Click the “Ok” Box

The following Screen should appear

![alex_server_login_10](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/ad7bc7aa-3e4c-4920-8c17-a21f58af64b5)


Enter the Following Login Info and click “Ok”

> Username : formulan
Password : NanoCar10^-9
{.is-info}

![alex_server_login_11](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/5f148daf-1e31-4bb9-af0c-2eb48ab3a87a)


### 4. Successful Login Screen
 You should see the following screen if you have successfully logged in.
 
![alex_server_login_12](https://github.com/MrDNAlex/Old-Nano-Car-Documentation/assets/93613553/eca9def5-338e-41b9-b66b-eea4ae08b24b)
