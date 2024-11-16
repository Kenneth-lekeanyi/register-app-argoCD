** **PROCEDURE TO INSTALL GIT BASH ON A WINDOWS OS**
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

**(1)** **SETTING UP CLOUDSDK IN YOUR LOCAL**

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
  - Now, in your v.s code Terminal, check your current working directory.
  - So do **pwd** enter.
 - Since the google cloud that we downloaded is seated in Downloads, get inside the Download Directory.
 - So do **cd Downloads** enter. {This is because the gcloud config that we downloaded is currently sitting in Downloads}.
 - Now, do **ls**.
 - You will see "google-cloud-sdk" here in your downloads Directory.
 - So, get into the google cloud sdk.
 - So do **cd google-cloud-sdk**.
 - Now do **ls** enter.
 - You will see that there is a file in here titled as **install.sh.** We need to execute this file. So let's use bash to execute it.    - So do **bash install.sh** enter.
 - You should see “**Welcome to Google Cloud CLI……**.”
  - "Gcloud config set disable-usage-reporting false. Do you want to help improve the google cloud CLI (y/N)
  - Type **"N"** here.
  - Here, it says “**Modify profile to update your $PATH and enable shell command completion. Do you want to continue?**” (Y/N)
  - Type **Y** here.
  - Here it says “**Enter the path to an rc file to update or leave blank to use…**”
  - Hit "enter" or Hit the return button.
  - Here it says “**Google cloud CLI works best with python 3.11 and certain modules. Download and run python 3.11 installer**”. (Y/N)
  - Type **Y** here for yes.
  - It will prompt you here to enter your computer password.
  - Now, run this command **source ~/.bash_profile** enter.
  - It will prompt you to open a new Terminal. So, go to a new terminal and start by checking the version.
  - So, on a New Terminal, check the version by doing **gcloud –version** enter.
  - It will show you this.
   - **lekeanyi@Kenneths-MBP ~ % gcloud --version**
   - **Google Cloud SDK 462.0.1**
   - **bq 2.0.101**
   - **core 2024.01.31**
   - **gcloud-crc32c 1.0.0**
   - **gsutil 5.2**
- Now do **gcloud init** enter.  It says.
 - **lekeanyi@Kenneths-MBP ~ % gcloud init**
 - **Welcome! This command will take you through the configuration of gcloud**.
 - **Your current configuration has been set to: [default]**
 - You can skip diagnostics next time by using the following flag:
 - **gcloud init --skip-diagnostics**
 
 **Network diagnostic detects and fixes local network connection issues**.
 **Checking network connection...done**.                                                                                                 **Reachability Check passed.**
 **Network diagnostic passed (1/1 checks passed).**
 - You must log in to continue. Would you like to log in (Y/n)?  Type **y** enter
 - It now says: “Your browser has been opened to visit: https://accounts.google.com/o/oauth2/auth?response_type=code&client_id=32555940559.apps.googleusercontent.com&redirect_uri=http%3A%2F%2Flocalhost%3A8085%2F&scope=openid+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fuserinfo.email+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcloud-platform+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fappengine.admin+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fsqlservice.login+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fcompute+https%3A%2F%2Fwww.googleapis.com%2Fauth%2Faccounts.reauth&state=3y51vjaL68A7r6AzUfpDYg6QxW8C8q&access_type=offline&code_challenge=1e7ZFHlpDYWUvYFhxj8hpwz62_Vaj3EnHSGJTeoNOrw&code_challenge_method=S256

- It will populate a Google sign in portal (Choose an Account to continue to Google Cloud SDK) on a new tap, where you will be prompted to type your email address that was used to create you Google Cloud account (for it to authenticate into your Account)
 - **My own email: klekeanyi84@gmail.com**
 - **Enter Password:**
- It will authenticate again on your phone as 2 Factor authentication.
- Then click on “**Continue**”
- It says, “**Google Cloud SDK wants to access your Google Account**”.
- Click on “**Allow**”
 
**Success!!**
- Back in the V.S Code, it says;
 - **You are logged in as: [klekeanyi84@gmail.com]**.
 
- Pick cloud project to use:
  - [1] hardy-position-404322
  - [2] Enter a project ID
  - [3] Create a new project
- Please enter numeric choice or text value (must exactly match list item): 
- Enter **1** to log into “your project".

- To test and ensure that everything is working properly, 
- Type "**gloud –version**" enter
 - It should give you an output like this
 - ![Screenshot 2024-11-16 at 9 30 28 AM](https://github.com/user-attachments/assets/e378d37a-18cf-4da8-8c60-00a9896470b4)
 - So your Cloud SDK is all setup


**(2)** **LOGGING INTO THE CLUSTER**






















- 
