# VorkAppAndroid

## Setup Instructions

### Download Java SDK 8

1. Go to http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
2. Download appropriate Java SDK 8 and install it

### Download Android Studio

1. Download Android Studio at http://developer.android.com/sdk/index.html
2. Install

### Setting up Android Studio for GitHub
1. Once installed, launch Android Studio.  If first time, it will download all SDK components.
2. Once you are at the "Welcome to Android Studio Screen" Wizard, click Configure -> Settings
3. In the settings window, navigate to Version Control -> GitHub
4. Fill in your Login and PW and then test the connection to make sure it works
5. Click Apply, and if asked to put in a master pw, you can just click OK to not have one
6. Click OK to close the settings window

### Install Git
1. You will need to install Git.  Go to https://git-scm.com/downloads
2. In the installer, you need to make sure that "git" gets added to PATH
3. In the "Adjusting your PATH environment" selection, make sure to select the last option: "Use Git and optional Unix tools from Windows Command Prompt"
4. If you Android Studio Open, restart it to make sure changes are in effect

### Check out the project from Version Control
1. Verify that you are a collaborator on this GitHub.  If not, I will invite you
2. In the "Welcome to Android Studio" Window, click Check out project from Version Control
3. Clicking the button, will show a drop down menu.  Click GitHub
4. In the Git Repository URL, type in: https://github.com/zeroxiii/VorkAppAndroid.git
5. In the Parent Directory, create a central location where you want your project saved locally to.  Location is up to your prefrence
6. Directory Name should be filled automatically
7. Click Clone
8. This will take everything in the current version of the project and put it on your machine.  Now you can make changes, and those changes you can committ back to the main repo once you are ready
9. Android Studio will ask if you want to open the project you just cloned. Say Yes
10. On the toolbar, navigate to VCS and click Enable Version Control Integration
11. In the new window, be sure to select Git from the dropdown menu
12. Now, you will see a "Version Control" tab appear in your console tab near the bottom.  This tool will let you see your changes and help you committ changes directly with Android Studio
13. You should be good to go now!
