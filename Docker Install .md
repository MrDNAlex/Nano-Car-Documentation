# Installing Docker
This page covers the installation process of Docker on your own personal machine. It will focus mostly on Docker Desktop, the GUI version of the Application





## Docker Desktop Install
Docker Desktop is a very useful tool, it allows you to more visually interact with the containers and better understands the basics at first. Installing it on your own machine will prove to be extremely useful by allowing you to test any container on your own machine before deploying to the ECE Server or other machines.


## Download EXE From Website

Start by going to the Following Website : [Docker Desktop](https://www.docker.com/products/docker-desktop/)


Click on the "Download for Windows" Button. If using a different Operating System it will display something different.

An EXE should now be downloaded on your machine.


## Install Docker

Double Click on the EXE to start the Installation Process. Make sure you are an Admin User on your device

You should be prompted with the following Screen.

Click "Ok"

Then the Window should go through a bunch of processes, this may take several minutes

Once complete you will be prompted to Restart Windows or your OS. Do so.


Once Installed Open the Docker Desktop App, you will be prompted to accept the License Agreements

Accept them.

Use the recommended settings that Docker Provide and Click the Finish Button

Next you can login/signup or you can skip it if you would like

Finally you should receive something like the following


## Checking if Installed Properly

### Version Check

Once Restarted open up Command Prompt and type the following

```
docker -v
```

If it gives you a version, it means Docker has been installed

### Running your First Container

Next we will try running the Hello World Container

Open up a new Command Prompt Window and type the following

```
docker run hello-world
```

Docker will then install a new Image called hello-world which shouldn't take long, and then it will spit out a bunch of text, somewhere in it there will be a message saying "Hello from Docker!"

This means that everything is working as expected

