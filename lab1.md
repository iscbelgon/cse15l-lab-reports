# Lab Report 1
In this lab report, I will be explaining the steps as to how to log into a course-specific account on `ieng6` through Visual Studios code and remotely connecting along with trying some commands within the remote conenction.

Through this report, we will be: 
* Installing VScode
* Remotely connecting 
* Trying some commands

We will be continuing assuming that you have successfully found your specific CSE15L account here:

[https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)


## Installation of Visual Studio Code
First we will go about installing Visual Studio code. Of course, the computers in the labs have visual studio installed on the computers. We, however, are interested in installing Visual Studio on our own computers. 

To download Visual Studio code, go to the official website
[https://code.visualstudio.com](https://code.visualstudio.com/)
, download and install. 

![Image](VSscreenshot.png)

Once you download and open up visual studio code, you should get a screen similar to the one above. The color may vary depending on the default settings or depending if you already have it installed and customized the colors. 

For now we have completed the first step of installing visual studio code. 

## Remotely Connecting
After the installation of Visual Studio code, we will be using it to remotely connect to a server using our course-specific account that we found earlier. 

For me, since I am on windows, I downloaded and installed:

[Git for Windows](https://gitforwindows.org/)

I then went in Visual Studio code and set the terminal to use `bash` by default.

We will use `ssh` by opening a new terminal within VScode and typing in the following, exchanging `zz` with the letters in your own account that we searched up earlier. 

`$ ssh cs15lwi23zz@ieng6.ucsd.edu`

If it is your first time connecting to the server, you will be met with a message that you will have to answer by typing `yes`. After pressing enter you will type in your password and will be logged in. 

![LoggingIn](loggingIn.png)

Since it is not my first time logging in and connecting to the server, I am not prompted to answer the yes or no question that is asked upon initial connection. 

We have now successfully connected to a server through our client.

## Trying Some Commands
Our last part of this lab report, we will being running some commands and observing what different useful commands do. 
Specifically, we will be running commands such as `cd`, `ls`, `mkdir`, and `cp`.

`cd` is used to change directory and can be followed with the directory you wish to change it to. Following a directory title with it will change the directory to that said directory.

`ls` is used to list out all the files inside the current directory. 

`pwd` is used to show the current directory you are currently in.

`mkdir` is used to create a new directory. 

`cp` is used to copy files in one directory to another. 

Below is a picture of what you should see when running certain commands. 

![Commands](commands.png)
