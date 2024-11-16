**PROCEDURE TO INSTALL GIT BASH ON A WINDOWS OS**
- Go to a new Browser, then type in Google "git download".
- Then click on the "Git-Downloads" under "Git SCM"
- Locate the green box at the right and click on “Download for Windows.”
- Then under “Download for Windows”, click on “**click here to download**”.
- Then go to your Downloads Directory in your OS and click there to locate the git file that you just downloaded.
- Now, locate **Git 2.43.0-64-bit** and double click on it to install it.
- Then click on “Next”, “Next”, “Next”,
- Now click on “Install.”
- Select “Google chrome”
- Then select “Always” to run it.

**[POCEDURE TO SETUP CLOUD SDK FOR A GOUGLE CLOUD ENVIRONMENT]**

Go to Google search bar and type to search for “**download google cloud sdk**”
- Then locate and click on “install the gcloud CLI/Google Cloud CLI Documentation.”
- It will default you to your OS under “**installation Instructions**”, and your OS will be underlined in blue.
  
  - **For Windows**:
- Click on “**Google Cloud CLI Installer**”. This will download the package for cloud sdk
- Now, go to "Downloads" in your OS and click on it to see the cloud sdk which you have just downloaded.
 
- We need to install python first because it is a prerequisite. So, go to your search bar and click there to search for “Microsoft store”.
- In the search bar of Microsoft store, click there to search for python and take python 3.11.
- Now click on “**Get**” at the top right to start downloading.
- Once completed, bring up your v.s code
- Open your Terminal or New Terminal and type "python" enter
- If it gives you a python version, know that your python 3.9.6 interpreter is ready.
- ***You must have installed gitbash***, if not, bring up your Command Prompt and type python --version to ensure that python has been installed successfully.
- Now, confirm in your File Explorer that you have cloud sdk.
- So, go to “Downloads”, and click there to ensure that "googlecloudSDKinstaller" is present there.
- Click on this "Googlecloudsdkinstaller" to populate the **Welcome to Google Cloud CLI Setup**.
- Now, click on “Next.”
- Click now to check the licence box on Agree.
- Click on “I Agree”
- Here check the box on “Single User.”
- Click now on “Next.”
- Check the box on “Beta command.”
- Click now on “install.”
  - **It will take some time to do some checks. If everything is ok, it will be installed successfully**.
- When the installation is complete.
  - Click on “Next”, “Next”, then click on “Finish”.
  - It will open your command prompt.
  - Then hit the "Y" bottom to confirm.
  - It will open a window for you to sign into your Gmail that you will use to set up your Google cloud environment.
  - lick now on “Continue.”
  - Click on “Allow”
- **Now, bring up your Terminal again to continue from there under**
  - Pick cloud project to use
  - 1.
  - 2.
  - 3.
  - Now, type “1” to select the first option.
- Now, you are good to go. You can now test it.
- So, In your Terminal, type "**gcloud –version**.

If you see this “**command new argument expected**”, know that everything is ok
- Whenever you want to take a new setup, maybe for a new project, just do gcloud init enter.
- It will take you through the whole flow again.

   - **For MacOs**
- As it defaults you to your OS under macOS, the 1st step wants you to confirm that you have python3 installed in your machine already. So, skip this 1st step and go to the 2nd step. We shall download the python later.
- Step 2: Here, it gives you three options to download any of them. Click to download the first option of macOS 64-bit (x86_64) if your mac is not Apple M1.
- So click on "**google-cloud-cli-462.0.1-darwin-x86_64.tar.gz**"
- Now, go to your Finder and confirm that you have "**google-cloud-sdk**" there.
- Now, bring up your v.s code.
- We need to install python at this time. So first bring up your terminal and check if python is currently installed in your OS.
- So do **python --version**.
- If it says, “command not found”, know python is not installed. So, it needs to be installed.
- You can use **brew**. (brew is the install manager for mac).
- So, do **brew** enter.
- If brew is installed, then use brew to install python3.
- So do "**brew install python3**".
- After the installation is completed, check to confirm it.
- So do "**python3 --version**"
  - If the result is not **python 3.11.7**, then know that you have to make python a global service in your OS.
  - To do this, go to your vs code and type there to check that python is not there in the system already.
  - Now proceed to make python as a global service in your mac. So vi to this
  - **vi ~/.bash_profile** enter.
 
 - change to insert mode.
 - Now paste this command inside this configuration file
 - **alias python='/usr/local/bin/python3'**
 - Now, save and quit **esc :wq!**

- Run this command to source or refresh your bash config.
- **source ~/.bash_profile** enter.
  - Now, do **python –version**. You will see that it displays "python 3.11.7"




















- 
