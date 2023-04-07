# Lab Report 1 <br>

---

## Tutorial : How to log-in to a course specific account on ieng6! <br>

**Installing VS Code** <br>
The first step is to download Visual Studio Code. You can dowload it by going to their website linked [here](https://code.visualstudio.com/) and your window should like the one seen below. Click download and follow the download instructions for your designated device.  <br>

![Image](VSCodedowload.png) <br>

Once installed, open up VS Code and you should get a window similar to the one below. If you do, you have sucessfully installed the application! <br>
![Image](oncedowloaded.png) <br> 

**Remotely Connecting** <br>
To remotely connect on your device follow the steps below: <br>
1. Head to the following link to find your account for CSE15L. ([https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)) <br> 
A website like the one shown below should appear.
2. Once there, use "Account Lookup" where you will be prompted to enter your username (ie. the beginning of your ucsd email) and your student ID.
3. A page entitled "Account Lookup Results" should load and under the section "Additional Accounts" navigate to your account for CSE15L. It should 
begin with "cse15l" followed by the quarter you are taking the course (ex. sp23). 
4. Click on it, and copy the username it gives you. It should be the same as the heading that navigated you to that page. 
5. Now it's time to open VS Code and create a new terminal. In this terminal you want to enter `ssh username@ieng6.ucsd.edu`. Of course, substituting 
username with the one you copied from Account Lookup.
6. As it's your first time connecting, you will find the terminal printing a message like this: <br> `Are you sure you want to continue connecting (yes/no/[fingerprint])?`<br>
Type `yes` and you should be greeted with a message similar to "Hello some_username, you are currently logged into ieng6..." <br>

You are now remotely connected to a computer in the CSE basement!

**Trying Out Commands!** <br>

