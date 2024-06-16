[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15272849&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Step 1: Before downloading Windows 11, I have to ensure that my  device meets the minimum system requirements, i,e, processor: 1 GHz or faster with 2 or more cores on a compatible 64-bit processor, RAM: 4 GB or more, Storage: 64 GB or larger, System firmware: UEFI, Secure Boot capable, TPM: Trusted Platform Module (TPM) version 2.0, Graphics card: DirectX 12 compatible graphics / WDDM 2.x, Display: >9” with HD Resolution (720p), Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.
   Step 2: Visit the Microsoft website: I go to the Windows 11 download page. Download the Installation Assistant: I click on "Download now" under the "Windows 11 Installation Assistant" section.
   Step 3: I find the Windows11InstallationAssistant.exe file in my Downloads folder and double-click it to run. The assistant will check my PC for compatibility and guide me through the download and installation process.
   Step 4:  From the same download page, I click on "Download now" under the "Create Windows 11 Installation Media" section. I open the MediaCreationTool.exe file and follow the instructions to create a bootable USB drive or DVD.
   Step 5: The Installation Assistant will automatically guide me through the installation process. If I'm using a bootable USB or DVD, I insert it and restart my PC. I select my language, time, and keyboard preferences, and click "Next." Then click "Install now." I select "Custom: Install Windows only (advanced)" to perform a clean installation or "Upgrade: Install Windows and keep files, settings, and applications" to upgrade my existing Windows installation.
   Step 6: I complete the setup process by following the prompts to configure my preferences, sign in with my Microsoft account, and customize my settings. Windows 11 will finalize the installation and boot to the desktop.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Step 1: I launch my preferred web browser. I navigate to the official Visual Studio Code website at https://code.visualstudio.com/.
   Step 2: On the VS Code homepage, I see the download button that automatically detects my operating system. I click on the button that says "Download for Windows". The download will begin automatically. I wait for the VSCodeSetup.exe file to finish downloading.
   Step 3: Once the download is complete, I locate the VSCodeSetup.exe file in my Downloads folder and double-click it to run the installer. If prompted by User Account Control (UAC), I click "Yes" to allow the installer to make changes to my device. 
   Step 4: In the installer window, I read and accept the license agreement, then click "Next.". I select the destination folder where I want to install VS Code, or I leave it as the default location, and then click "Next.".  I choose additional tasks such as creating a desktop icon, adding VS Code to the PATH (important for using VS Code from the command line), and other options, then click "Next.". I click "Install" to start the installation process. I wait for the installation to complete. Once the installation is finished, I ensure the "Launch Visual Studio Code" option is checked, then click "Finish."
   Step 5: I find the Visual Studio Code icon on my desktop or in the Start menu and open it. Install a few extensions like Prittier. Now, I have Visual Studio Code installed and set up on my computer, ready for coding!

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Step 1: I go to GitHub and sign up for a free account. 
   Step 2: I launch my Git Bash on Windows to configure. I type the following command to set my GitHub username: git config --global user.name "ItumelengMphuti". I type the following command to set my GitHub email: git config --global user.email "itumeleng1mphuti@gmail.com". 
   Step 3: I use the cd command to navigate to the folder where my project is located, or create a new directory if I don't have one yet: cd onedrive/desktop/myproject. I type the following command to initialize a new Git repository: git init. I add the files I want to include in my first commit by using the git add command. To add all files, I use: git add . 
   Step 4: I type the following command to commit the staged files, adding a commit message to describe the changes: git commit -m "Initial commit". 
   Step 5: I go to GitHub and click on the "+" icon in the top right corner, then select "New repository.". I enter a name for my repository, add a description (optional), choose to make it public or private, and decide whether to initialize it with a README (since I've already committed locally, I do not initialize with a README). I click on the "Create repository" button.
   Step 6: On the new repository page on GitHub, I find the URL for the repository. It should look something like https://github.com/MyUsername/myproject.git. I go back to my terminal and add the remote URL to my local repository: git remote add origin https://github.com/MyUsername/MyRepository.git . I push my local commits to the remote repository on GitHub: git push -u origin master. I go back to GitHub and navigate to my repository page. I should see my initial commit and files listed there. 


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Step 1: I go to the official Python website at python.org and download the latest version of Python.  I run the downloaded installer. During installation, I make sure to check the box that says "Add Python to PATH," then click "Install Now."
  Step 2:  I open my command prompt on Windows. I type the following command to verify that Python is installed correctly: python --version, this prompt should bring back a message that says version 3.12.4.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Step 1: I open my command prompt on Windows. Navigate to my python folder using cd. I type the following command to run the script and install pip: python get-pip.py 
   Step 2: I type the following command to verify that pip is installed and to see the version number: pip --version. this should give a result similar to when I run puthon --version


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Step 1: I go to the official MySQL website at https://dev.mysql.com/downloads/installer/. I click on the "Download" button for the MySQL Installer for my operating system. I choose the Windows (x86, 64-bit). 
   Step 2: After the download is complete, I locate the installer file in my Downloads folder. I double-click the installer file to run it.
   Step 3:  I see the MySQL Installer welcome screen. I click "Next" to proceed. I choose the setup type that suits my needs. For a typical installation, I select "Developer Default" and click "Next."  The installer checks for any missing requirements. If any are missing, I follow the instructions to install them, then click "Next." I click "Execute" to begin the installation process. This might take a few minutes.
   Step 4: Once the installation is complete, the installer will guide me through the configuration process. I choose the configuration type. For most users, "Standalone MySQL Server" is the best option. I click "Next." I choose the default options for network connectivity, ensuring that the port 3306 is selected. I click "Next."  I set the root password for the MySQL server. I choose a strong password and make a note of it. I can also add additional user accounts if needed. I click "Next." I configure MySQL to run as a Windows service (if on Windows) and choose the default settings. I click "Next." I click "Execute" to apply the configuration settings. Once complete, I click "Finish."


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   Step 1: I use the cd command to navigate to my project directory, cd myproject. 
   Step 2: Create the virtual environment using this command: python -m venv venv
   Step 3: I thne activate the vertual environmemt: .\venv\Scripts\activate. I should see the virtual environment's name in my terminal prompt, indicating that it is activated.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
