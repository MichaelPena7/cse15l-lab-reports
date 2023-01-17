**Lab Report 1**

For this lab report, I will be describing a step by step process in the method I used to download VSCode, using it to remotely connect, then attempting some commands!

For the first part, it was atypical of a standard download. This is because my chromebook runs ChromeOS rather than Windows, making installation of VSCode slightly tricky. Firstly, I had to download Linux on my computer, which essentially would act like a program that VSCode could use to run. To do this, yousimply had to look up "Linux" in your chromebook's settings. Although this is the screen I have since I already downloaded Linux, normally you would have an option to download Linux rather tham the option to remove Linux as shown here in this screenshot.

![Image](WhereLinuxIs.png)

After waiting a few minutes for Linux to download, I was now ready to download VSCode! I went over to the installation download website through a quick google search of "VSCode Download"

![Image](WhichToDownload.png)

Here, I had to pick the small "arm64" under the .deb in the middle underneath the penguin. This was the version I needed to download in order for VSCode to run on my laptop specifically. Finally, once it finished downloading, I was now ready to begin using VSCode!

To start connecting remotely with the rest of my classmates, I opened a new file and opened up its terminal. It ended up looking something like this

![Image](StartUp.png)

From there, I had to type out "ssh cs15lwi23xx@ieng6.ucsd.edu" into the terminal. However, rather than the "xx", I replaced those with my unique set of characters. I was able to get those through login in in the website here: https://sdacs.ucsd.edu/~icc/index.php. From there, you login with your UCSD account user and your PID. You then had to quickly update a password for this class, as being new to the CSE15L class, we haven't logged in to the class yet. Once you login, however, it will immediately display your unique two characters as I mentioned before. However, since we just updated the password for CSE15L, we have to wait a couple of minutes for the system to process the change, as we do in fact need that specific password to login to our VSCode account. Once the 5-10 minutes are up, you are now set to login!

![Image](RemotelyConnecting.png)
![Image](Confirmation.png)

Once you type in "ssh cs15lwi23xx@ieng6.ucsd.edu" with your special characters replacing "xx", you will be asked for a password. A successful attempt results in these two images above! Unfortunately for me, I actually forgot about the downtime needed for your account to process the password change, resulting in the 47 attempt message shown in the picture. However, this did give me a glimpse of what occurs when you fail a password. The first two failed attempts will repeat the "Password:" line. Next, the next three attempts will warn you that permission has been denied. Once you enter the fifth failed attempt, VSCode will halt the password entering process all together and kick you out of the command, meaning you have to reenter "ssh cs15lwi23xx@ieng6.ucsd.edu" for another 5 attempts!

![Image](FailedPassword.png)

Back to VSCode, with connecting remotely with others I was now able to try out some commands!
