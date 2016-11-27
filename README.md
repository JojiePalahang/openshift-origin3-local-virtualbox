# Openshift Origin V3 Local Machine - (Virtual box)
 [Source](https://blog.openshift.com/using-openshift-3-on-your-local-environment/)

# Requirements
 - Virtual box
 - Vagrant
 - Internet Connection

# To Use
 - Install all required software
 - Clone this project `git clone git@github.com:JojiePalahang/openshift-origin3-local-virtualbox.git`
 - Goto the directory `cd openshift-origin3-local-virtualbox`
 - Execute this command `vagrant up`, this will may take much time
 - Authenticate to OpenShift 3 with the web console
   <p>Now that we have everything up and running, you probably want to authenticate to the platform.<br>
   Let’s start by using the web console.  Open up your browser and go to the following URL: <underline>https://10.2.2.2:8443</underline></p>
 - If things worked correctly, you should see the following screen:
    ![Log In Page](docs/image002-1024x531.png?raw=true)
 - <p>You can enter anything you wish for username/password as the authentication is open 
    (there is already an account for admin/password that has a sample project in it). 
    If the user doesn’t exist, it will be created.  Once you have logged in, you should see the following:
    </p>

   ![Home Page](docs/image03-1024x268.png?raw=true) 