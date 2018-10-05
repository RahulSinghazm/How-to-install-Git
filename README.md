# How-to-install-Git
Installing Git on Windows, Mac OS X and Linux 


# Installing Git – the easy way

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

– The Git website
* Instructions for Windows
* Instructions for Mac
* Instructions for Linux

# Installing Git on Linux
Determine on which Linux distribution your system is based on. See List of Linux distributions – Wikipedia for a list. Most Linux systems – including Ubuntu – are Debian-based.

## Debian-based linux systems
Open a terminal window. Copy & paste the following into the terminal window and hit Return. You may be prompted to enter your password.

sudo apt-get update
sudo apt-get upgrade
sudo apt-get install git
You can use Git now.




## Red Hat-based linux systems
Open a terminal. Copy & paste the following into the terminal window and hit Return. You may be prompted to enter your password.

sudo yum upgrade
sudo yum install git
You can use Git now.



# Installing Git on a Mac
Open a terminal window.

## Step 1 – Install Homebrew
Homebrew […] simplifies the installation of software on the Mac OS X operating system.

– Homebrew – Wikipedia

Copy & paste the following into the terminal window and hit Return.

ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew doctor
You will be offered to install the Command Line Developer Tools from Apple. Confirm by clicking Install. After the installation finished, continue installing Homebrew by hitting Return again.

# Step 2 – Install Git
Copy & paste the following into the terminal window and hit Return.

brew install git
You can use Git now.



# Installing Git on Windows
Download Git from : Git for Windows and install it.
