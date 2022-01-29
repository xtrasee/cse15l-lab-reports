# **How to Log into a Course-Specific Account**

## **Step One : Installing VScode**

---

- The first step we need to do before logging into a course-specific account is to install VScode. [Click here to install VScode!](https://code.visualstudio.com)

- Once you install and run VScode, your environment should look similar to this:

![pic of vs code environment](https://user-images.githubusercontent.com/92359561/149450527-f2d3b1ec-84ce-4c0b-9e99-1a44108d5329.png)

---

## **Step Two : Remotely Connecting**

---

- We must then look up your source-specific account for CSE15L. [Click Here!](https://sdacs.ucsd.edu/~icc/index.php)

- Once you do your account Lookup, you should be able to find your own course-specific account. It should look something like cs15lwi22zz@ieng6.ucsd.edu but with the zz replaced with your own letters.

- Then type the following into the terminal: ssh cs15lwi22zz@ieng6.ucsd.edu. Next type in yes and it should give you a prompt to enter your password.

- Once you are connected, it should look like this:

![connected](https://user-images.githubusercontent.com/92359561/149451212-4df9bf37-cc50-4dce-9def-228a01f1b5d0.png)

---

## **Step Three : Trying Some Commands**

---

- Try running some commands such as, cd, ls, ls -a, mkdir, pwd.
- You could try these commands for example,

![pic of example commands](https://user-images.githubusercontent.com/92359561/149451512-f506ab53-bf95-44ce-a359-d49ac519beeb.png)

---

## **Step Four : Moving Files with scp**

---

- One way to copy files from your computer to a romote computer is by using the command scp.
- We will always run the command on your computer (the client). First create a file WhereAmI.java and put the following content into the file:

![WhereAmI.java](https://user-images.githubusercontent.com/92359561/149452152-e586036d-781c-43a1-9395-924db2bb146e.png)

- Then, log into your ieng6 with your ssh and run the file using javac and java.

---

## **Step Five : Setting an SSH Key**

---

- To avoid the trouble of having to type in your password everytime you log into your ieng6 using your ssh key, we can create whats called a ssh-keygen. Run ssh-keygen on your computer and it should look like this:
- ![ssh-keygen](https://user-images.githubusercontent.com/92359561/149452820-452ded7f-2825-4c33-850e-3ed64f34136b.png)
- This created two files - one with your private key and one with your public key. Therefore, we now need to copy the public key to the .ssh directory by doing the following steps on the server:

![pub-key](https://user-images.githubusercontent.com/92359561/149453178-b9c20ff0-ecc1-49a7-8bd6-71afd14f1186.png)

---

## **Step Six : Optimizing Remote Running**

---

- Final step! To make remote ßrunning more efficient, you can use semicolons to run multiple commands on the same line and save multiple "enter" keystrokes.

![efficient](https://user-images.githubusercontent.com/92359561/149453719-108f2002-6e76-472f-ac83-f31668aa0a14.png)

- In the example above, I was able to save two "enter" keystrokes.
- You could use the up arrow to retrieve the last command that was runß.

---
