# Lab 1 - Remote Access

In 

## Step 1: Installing VScode

First off, you will want to download and install Visual Studio Code, or VScode for short. Head on over to the [Visual Studio Code Website](https://code.visualstudio.com/) and click the download button.

![Visual Studio Code Screenshot](images/vscodedownload.png)

## Step 2: Remotely Connecting

For this step, you first need to download OpenSSH by going through the tutorial in the following link: [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

Go to the following website to obtain your CSE15L account:

[https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)

Then, open the console in VScode and type out the following command:

```
ssh cs15lwi22###@ieng6.ucsd.edu
```

Replace the ### with whatever your CSE15L account is that you found from the previous website. After this, it will prompt you to enter your password. After this, you should be logged in.

![SSH Login Screenshot](images/sshlogin.png)

## Step 3: Trying Some Commands

Here is a list of some of the basic commands and what they do

- cd - changes the current directory
- ls - lists out the contents in the current directory
- cp - used to copy a file
- cat - reads out a file

![Trying some commands](images/commandTesting.png)

## Step 4: Moving Files with scp

In order to move a file over with scp, you would need to run the command:

```
scp filename cs15lwi22###@ieng6.ucsd.edu:~/
```

replace the (filename) with the name of the file, followed by its' extention. Also make sure to replace the ### with your CSE15L account name.

![Using the scp command to transfer files](images/scpCommand.png)

## Step 5: Setting an SSH Key

## Step 6: Optimizing Remote Running
