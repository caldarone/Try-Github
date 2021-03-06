# Try GitHub
Welcome to the Rhode Island version control feedback repository. Here, you'll test various Git features and work with fellow testers to build a repository. If you're viewing this, you were added as a **contributor**, which means you can view, edit, upload, and delete files. However, since this repository is version controlled with Git, it can be reinstated even if you delete important files, such as this README.

Throughout this interactive tutorial, you may run into various questions regarding Git and GitHub software. If you need help, just click on the issues tab above this README. Then, click the green button that says "New issue" and submit a ticket.

<img width="989" alt="screen shot 2016-08-11 at 2 52 18 pm" src="https://cloud.githubusercontent.com/assets/13228316/17600839/5416f340-5fd3-11e6-96c1-55079aa76c73.png">

## Downloading Git and GitHub Desktop
First, you'll need to install Git, the version control software that GitHub is based on. While it may already be installed on your computer, please follow the below steps to make you're running the most recent version of Git. More information about installing Git can be found [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
### GitHub Desktop (Windows and Mac)
If you're using a Windows or Mac operating system, you can download a GUI called GitHub desktop. This provides a graphical interface for making Git commits, creating and using branches, and uploading your code to GitHub. If you've never used Git before or are uncomfortable with the command line interface (CLI), GitHub Desktop is likely your best option.
[Download Github Desktop Here.](https://desktop.github.com/)

![github](https://cloud.githubusercontent.com/assets/13228316/17601159/c8039c8a-5fd4-11e6-869f-8efcb22036fc.jpg)

### Git for Windows
GitHub Desktop will automatically install command line tools on Windows. However, if you want to use Git exclusively via the command line, you can download it by clicking on [this link](http://git-scm.com/download/win) (automatic download).
### Git for Mac
GitHub Desktop will automatically install command line tools on Mac. However, if you want to use Git exclusively via Terminal, you can download it by clicking on [this link](https://git-scm.com/download/mac) (automatic download). Follow the 
### Git for Linux
GitHub Desktop is not currently available on Linux distros. If you're running a Debian-based distro such as Ubuntu, you can use the APT package manager. 

    $ sudo apt-get install git-all

If you're on Fedora or another distributio nthat uses YUM, then use the following command:

    $ sudo apt-get install git-all

## Using Git from the Command Line
If you opted to download the command line tools without GitHub Desktop, or you want more options than GitHub Desktop provides, then you can learn Git following [this tutorial from Code School](https://try.github.io/levels/1/challenges/1).

<img width="1170" alt="screen shot 2016-08-11 at 3 15 14 pm" src="https://cloud.githubusercontent.com/assets/13228316/17601557/bb16f8da-5fd6-11e6-9e43-b6308505f935.png">

## Getting Started with GitHub Desktop
* Once you've downloaded GitHub Desktop and logged into your GitHub account, you'll need to download this repository to your local device. Since you've been added as a contributor to this repository, you can _clone_ the repository, which gives you the ability to make changes and re-upload (i.e., _push_) them to GitHub. You can so this by clicking the "+" sign in the top-left corner of GitHub Desktop, as shown in the image below. Then click "Clone `Try-GitHub`."

![clone-trygithub](https://cloud.githubusercontent.com/assets/13228316/17894970/6fe02f48-6919-11e6-866d-0c0e7ce64e63.PNG)

* Once you've done this, right-click on the `Try-Github` repository, as shown below, and click "Open in Explorer" or "Open in Finder," depending on what operating system you're using.

![openinexplorer](https://cloud.githubusercontent.com/assets/13228316/17895963/de14104e-691c-11e6-9e9a-d008ce9274ab.PNG)

* Open the `Contributors.csv` file with Excel or another spreadsheet application, and add your name, email address, and department to the spreadsheet. Don't worry - we've already got your contact information, this is just practice with the GitHub Desktop software.

![excel](https://cloud.githubusercontent.com/assets/13228316/17895981/f3841fe6-691c-11e6-9d09-07e88cc44ff4.PNG)

* Save the file as a CSV (overwriting the old one) and return to the GitHub Desktop interface. You should see "1 change" listed, and a summary of your changes on the right-hand side. To permanently save this change in the version control system, you need to **commit** it. To do so, fill out the summary field and click "Commit to gh-pages."

![1change](https://cloud.githubusercontent.com/assets/13228316/17896003/02e4f56e-691d-11e6-8972-6719d4c7894f.PNG)

* Now, the new version of `Contributors.csv` has been saved in version control _on your device_. In order to get these changes to show up on the GitHub repository, you'll need to **push** your changes. To do this, just click the "Sync" button in the top-right hand corner. In a couple of seconds, you'll see your changes updated to the GitHub site.

You've now finished the first part of the tutorial!
