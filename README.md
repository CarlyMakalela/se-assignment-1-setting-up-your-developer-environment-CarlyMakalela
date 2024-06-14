[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15268043&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.


# INDEX

1. Installing Windows 11 Operating System
2. Installing a Text Editor or Integrated Development Environment (IDE)
3. Setting up a Version Control System
4. Installing Programming Languages and Runtimes
5. Installing Package Managers
6. Configure a Database (MySQL)
7. Set Up Development Environments and Virtualization (optional)
8. Installing Extensions in Visual Studio Code
9. My Relection On The Challenges I Faced and The Solutions

# My Developer Environment Setup Guide

### Introduction
This guide outlines the process I followed to set up my development environment on my computer. It covers the installation of essential software, configuration of tools, and preparation for coding and project work.

## Step 1: Choose and Install your preferred Operating System (OS)

NB Choose an operating system that suits your own preferences

### Download and Install Windows 11
1. Visite the [Windows 11 download] (https://www.microsoft.com/software-download/windows11).
2. Click "Download Now" to get the installer.
3. After the download completed, run the installer and follow the on-screen instructions to install Windows 11.
4. Restart your computer when prompted.

## Step 2: Install a Text Editor or Integrated Development Environment (IDE)

### Download and Install Visual Studio Code
1. I navigated to the [Visual Studio Code download] (https://code.visualstudio.com/Download).
2. I chose the appropriate version for Windows.
3. I downloaded the installer and ran it.
4. I followed the installation steps and launched Visual Studio Code from the Start menu.

## Step 3: Set Up a Version Control System

### Install Git
1. I went to the [Git download] (https://git-scm.com/downloads).
2. I ran the installer and used the default settings.
3. I opened Command Prompt and typed:
   
   git --version
   
  In order to verify the installation.

###   In order to Configure Git
1. I opened Command Prompt and entered:

   git config --global user.name "Your Name"

   git config --global user.email "your.email@example.com"
   

## Create a GitHub Account
1. I visited [GitHub] (https://github.com) and signed up for an account.
2. Followed the prompts until my account was successfully set up.

## Initialize a Git Repository
1. I created a new project folder by opening Command Prompt and typing:

   ## NB Enter these steps one at a time and press  "Enter" after each command.
   mkdir myplp_project
   cd my_project
   
2. I initialized a Git repository:
   
   git init
   
3. I created a README file and made my first commit:
   
   echo "# My Project" > README.md

   git add README.md

   git commit -m "initial commit"

   git remote add origin [your-repo-URL]

   git push -u origin main/master

4.. I added a .gitignore file:
   - I created a file named `.gitignore` in the project folder.
   - I added common files and directories to ignore (e.g., `__pycache__/`, `*.pyc`, `.vscode/`).



## Step 4: Install Necessary Programming Languages and Runtimes

### Install Python
1. I went to the [Python download ] (https://www.python.org/downloads/).
2. I clicked "Download Python" to get the installer.
3. I ran the installer, ensured that check the "Add Python to PATH" instruction, and clicked "Install Now".

## Step 5: Install Package Managers

### Verify pip Installation
1. I checked if pip was installed by opening Command Prompt and typing:
   pip --version
2. Alternatively:
python -m pip --version

## Step 6: Configure a Database (MySQL)

### Download and Install MySQL
1. I visited the [MySQL download] (https://dev.mysql.com/downloads/windows/installer/5.7.html).
2. I downloaded the appropriate installer for Windows.
3. I ran the installer and followed the default settings.

## Step 7: (Optional) Set Up Development Environments and Virtualization

Depending on what you need as an individual, you can install Docker. I chose  to install it. Below are the steps to take in order to successfully install Docker: 

### Install Docker (Optional)

1. Go to the [Docker download] (https://www.docker.com/products/docker-desktop).
2. Click on the "Download for Windows" option.
3. Run the installer and follow the instructions/prompts.
4. Click on finish or done option.

   

## Step 8: Explore Extensions and Plugins

### Install Extensions in Visual Studio Code
1. I opened Visual Studio Code.
2. I clicked on the Extensions view icon on the Sidebar 
3. I searched for and installed the following extensions:
   - Python: Provides support for Python programming.
   - GitLens: Enhances Git capabilities within Visual Studio Code.
   - Prettier - Code formatter: Ensures consistent code formatting.
   - ESLint: Helps identify and fix problems in JavaScript code.
   - Pylance: Enhances Python editing features like type checking and autocomplete.
   - Path Intellisense: Autocompletes filenames in the project.

 
   
## Reflection on my Challenges

### My Experience

Setting up my development environment came with some challenges. The most notable issue was with MySQL I could not even get the databases to show. I had trouble displaying the database and I am still working on solving this problem. This has been a valuable learning experience, and I am determined to overcome this obstacle soon.

Visual studio Code was a breeze to use, it is straight forward and you can also download any extentension easily without a hassle. It is indeed User friendly, even for the beginners. Navigation is a bliss.

My other challenge was navigating Flutter. I found that the solution is to  reboot your machine. Once I rebooted my machine, I was able to work on it properly without receiving error messages even for the extentions I had already installed. I also used AI to help with some of the issues I had faced.  

Following these steps, I was able to set up a fully functional development environment, ready for coding and project work. If I encounter any specific issues or need further assistance, I know I can seek help and continue learning.