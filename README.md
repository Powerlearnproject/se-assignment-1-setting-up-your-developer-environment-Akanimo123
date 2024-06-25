[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15285912&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   Step-by-step procedure to download and install Windows 11 Operating system:
1. Visit the Microsoft Windows 11 download page by clicking on https://www.microsoft.com/software-download/windows11
2. Click the Download Now button under Create Windows 11 Installation Media.
3. Select either Upgrade this PC now if you’re updating that computer to Windows 11 
4. When installing Windows 11 on a different machine, pick Create installation media for another PC and save the ISO file.
5.  Finish following the prompts to either upgrade your PC or download the ISO file by choosing options like your language, and the edition of Windows you want.
6. On the Windows 11 download page, click Download Now under Download Windows 11 Disk Image (ISO) for x64 devices. 
7. Click the 64-bit Download button under Download - Windows 11. 
8. Once the ISO finishes downloading, you should be able to locate it in the folder where it is saved (most likely your Downloads folder).


3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Step-by-step procedure to download and install Visual Studio Code on Windows:
Step 1: Visit the Official Website of the Visual Studio Code using any web browser like Google Chrome, Microsoft Edge, etc. Click on https://code.visualstudio.com/Download
Step 2: Press the “Download for Windows” button on the website to start the download of the Visual Studio Code Application.
Step 3: When the download finishes, then the Visual Studio Code Icon appears in the downloads folder.
Step 4: Click on the Installer icon to start the installation process of the Visual Studio Code.
Step 5: After the Installer opens, it will ask you to accept the terms and conditions of the Visual Studio Code. Click on I accept the agreement and then click the Next button.
Step 6: Choose the location data for running the Visual Studio Code. It will then ask you to browse the location. Then click on the Next button.
Step 7: Then it will ask to begin the installation setup. Click on the Install button.
Step 8: After clicking on Install, it will take about 1 minute to install the Visual Studio Code on your device.
Step 9: After the Installation setup for Visual Studio Code is finished, it will show a window like this below. Tick the “Launch Visual Studio Code” checkbox and then click Next.
Step 10: After the previous step, the Visual Studio Code window opens successfully. Now you can create a new file in the Visual Studio Code window and choose a language of yours.


5. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
Step-by-step procedure to download and install Git on Windows:
1. Go to git-scm.com/download/win.
2. Click on the Git - Downloading Package site.
3. Click on the 'Click here to download' link at the top of the page to download the latest version of Git for Windows (Git 2.45.2).
4. After the setup has been downloaded on your browser, open it.
5. On the 'Select Components' page, click on the 'Additional icons' option. 
6. Click Next.
7. Click Next again on the choosing default editor setup page. Do not make any changes.
8. On the follow-up page, choose Notepad++ as Git's default editor.
9. Click Next.
10. On the next setup page requesting for the name of the initial branch after git init, click the 'Let Git decide' option. By Git deciding, it can use its default branch name (master) for the initial branch in newly created repositories.
11. Click Next.
12. The next setup page requests choosing the SSH executable. Choose the 'Use bundled OpenSSH' option. This option uses the ssh.exe extension that comes with Git.
13. Click Next.
14. On the 'Choosing HTTPS transport backend', click the 'Use the OpenSSL library' option.
15. Click Next.
16. To configure the line ending conversions in Git on the next setup page, choose the 'Checkout Windows-style, commit Unix-style line endings'. This would allow Git to convert between LF and CRLF when checking out and committing text files.
17. Click Next.
18. The next setup page will require a default behaviour of the 'git pull' command. To this, click the 'Fast-forward or merge' option. 
19. Click Next.
20. To complete the installation, click the 'Launch Git Bash' option.
21. Click Finish.
22. To check the version of the installed Git, after the Git Bash has been launched, enter the command git  --version. The installed version will appear within seconds on the next line.
Step-by-step procedure to creating a Github account:
1. Log into github.com
2. Follow the instructions and create an email address and a username.
Step-by-step tp initialize a Git repository:
1. Right-click on Git Bash and open in 'Administrator' mode.
2. Create a new directory by entering cd /
3. Then nagivate to a Local Drive in your computer sytem by entering cd /c/
4. To make the directory, enter mkdir foldername.
5. Then create a directory inside that drive by entering cd foldername/ (for example $ cd PlpProgramming/).
6. To link your Git to your GitHub repository, type git config  --global list on your Git Bash. This would display both the username and email address you entered while creating your GitHub account.
8. Press the Enter key.
7. Next, type  git config  --global user.name "pass in your GitHub username"
8. Press the Enter key.
8. Type git config  --global user.email "pass in your GitHub email"
9. Press the Enter key.
10. To create a python file on Git Bash, type vi hello.py. 
11. Press the Enter key. This would automatically open an editor. Once there, you can make changes to the created file.
12. Press i to edit. This will display a cursor symbol. 
12. Navigate to the top of the page. Press the Enter key to make a new line.
13. Type #!/usr/bin/python3.
14. Press the Enter key.
15. To save and quit the editor, navigate to the bottom line of the editor and enter wq. This would save the file and exit the editor interface.
16. To initialize the repository, type git init.
17. Press the Enter key.
18. Then type git add .
19. Press the Enter key.
20. To write the commit message, type git commit -m "enter a messsage" (e.g. "created a python file").
21. Press the Enter key.
22. Then type git remote add "GitHub repository link".
23. Press the Enter key.
24. Then enter git push .
25. Press the Enter key.

6. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Step-by-step procedure to download and install Python on Windows:
1. Open a web browser of your choice (e.g. Chrome, Microsoft Edge) etc and enter https://www.python.org/downloads/windows/
2. Navigate to the desired Python version you want to download. 
3. Under the 'Stable Releases', click the link to download Windows Installer (64-bit). The download is approximately 25MB.
4. Once done, open the Python Installer setup.
5. Click the two option boxes for both the admin privileges and the option to add Python to PATH. By allowing admin privileges, the installation folder for Python can be changed. By adding Python to PATH, the executable is placed in the PATH variable after installation.
6. After, select the Install Now for the installation.
7. Click Next on the 'Optional Features' page.
8. On the 'Advanced Options' page, tick the necessary boxes. 
9. Choose a customized install location folder.
10. Click Install.
11. After setup has been displayed to be successful, click Close.
12. To verify successful installation of Python, open the Git Bash in Administrator mode.
13. Type python  --version.
14. Press Enter. Within seconds, the installed Python version will appear below on the next line.

7. Install Package Managers:
   If applicable, install package managers like pip (Python).
1. To verify if pip was also installed, type pip  --version on the Git Bash terminal.
2. Press Enter. Within seconds, the installed pip version will appear on the next line below.
When Python software is installed, a virtual environment package is also installed along. To install the virtual environment (virtualenv), open the Git Bash in Administrator mode.
3. To install virtualenv, type the command pip install virtualenv or pip install venv.
4. Press Enter and wait for the installation to complete. Once done, it is installed on your system for use.

8. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step-by-step procedure to download and install MySQL database on Windows:
1. Open a web browser of your choice (e.g. Chrome, Microsoft Edge) etc and enter dev.mysql.com/downloads/installer/
2. Click the Download button for the Windows (x86, 32-bit) 296.1M version. This is the community version.
3. On the pop-up page, click the 'No thanks, just start my download' link. The MySQL Installer 1.6 window will begin loading.
4.  To select a setup type, click on the Server only option. This installs only MySQL Server product.
5. Click Next.
6. Click Next on the Path Conflicts page. Make no changes here.
7. Click Execute on the next page to install the product. Once done, a green checkmark will appear beside the product icon and the status will change from 'Ready to install' to 'Complete'.
8. Click Next.
9. Click Next on the Product Configuration page.
10. On the Type and Networking page, choose Development Computer on the Config Type drop-down list. All boxes can be left checked or unchecked. The default pipe and memory name is MYSQL. The default port is 3306. In case of an error message here, change the port number to 3307. 
11. Click Next.
12. On the Named Pipe setup page, select the Minimum access to all users option. This is the recommended option for Windows clients.
13. Click Next.
14. On the Authentication Method page, select the 'Use Strong Password Encryption for Authentication' option. It is recommended for all new MySQL Server installations.
15. Click Next.
16. On the Accounts and Roles page, a current root password of your choice will be required. A green check mark will indicate that the root password entered is strong. If not, an x mark will be displayed. 
17. Click Next.
18. On the Windows Service page, click Next as no changes are required.
19. On the Logging Options page, click Next as no changes here are required.
20. On the Advanced Options setup, click Next as no changes are required.
21. On the Apply Configuration page, click the Execute button. All options wil be automatically checked one after the other. 
22. Once all have been checked, click Finish to complete configuration.
23. To start the MySQL Server, open the Command Prompt on your Windows machine.
24. Enter the command C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld  --console

Step-by-step procedure to install MySQL Workbench:
1. . Open a web browser of your choice (e.g. Chrome, Microsoft Edge) etc and enter dev.mysql.com/downloads/workbench/.
2. Click Download on the Windows (x86, 64-bit), MSI Installer which is the community version.
3. On the pop-up page, click the 'No thanks, just start my download' link. The MySQL Workbench 8.0 CE window will begin loading.
4. Once it is done, the setup wizard will open.
5. Click Next to install the folder.
6. Click Install on the next setup page.
7. The installation will take a few minutes. Once the setup is completed, click the 'Lauch MySQL Workbench now' option.
8. Click Finish.
9. Once the MySQL Workbench 8.0 window opens, click on the 'Local Instance MySQL80 option. This is for the root user.
10. The pop-up window will request for a password. This is the same password that would have been entered in during the MySQL Server installation process. Once the password has been entered in correctly, click OK. The user interface for MySQL will then autmatically appear. 

9. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

10. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

11. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.
  There were no challenges encountered during the installation processes of any of the aforementioned software packages. 

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
