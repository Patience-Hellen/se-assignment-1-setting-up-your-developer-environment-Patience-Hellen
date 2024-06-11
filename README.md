[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15250057&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

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

My laptop was bought already installed with windows 10. It does not meet all minimum requirements for installation of windows 11.

Installation of an IDE and Extension and plugins
To download Visual Studio Code you got to the Official Visual Studio Code website: https://code.visualstudio.com/
Click on the "Download for Your Operating System" button. Visual Studio Code is available for Windows, macOS, and Linux.
Once the download is complete, locate the downloaded installer file usually in your Downloads folder named something like `VSCodeSetup.exe`.
Double-click on the installer file to start the installation process.
Follow the on-screen instructions in the installation wizard. You can choose the destination folder for installation, create shortcuts, and choose whether to add VS Code to the PATH.
Once the installation is complete, you can launch Visual Studio Code from your applications menu 
Upon first launch, Visual Studio Code will prompt you to install recommended extensions for popular programming languages and frameworks. You can choose to install these extensions based on your needs.
Customize your settings by navigating to File > Preferences > Settings. Here, you can modify various settings according to your preferences, such as theme, font size, keybindings, etc.
Exploration of extensions:
Open Visual Studio Code on your computer.
There are multiple ways to open the Extensions view:
Press `Ctrl+Shift+X`
Click on the square icon in the activity bar on the side panel (the icon with four squares, labeled "Extensions").
Go to the "View" menu and select "Extensions".
In the Extensions view, you'll see a search bar at the top.
Use the search bar to search for extensions by name, functionality, or category.
For example, you can search for "Python" to find extensions related to Python development.
VS Code features a selection of "Featured Extensions" that are highlighted on the Extensions view home page.
Scroll through the list of featured extensions to discover popular and highly recommended extensions.
On the left side of the Extensions view, you'll see various categories such as "Popular," "Recommended," "Installed," and more.
Click on a category to filter extensions based on that category.
For example, you can click on "Linting" to find extensions that provide linting functionality.
You can sort extensions by relevance, installs, ratings, or name using the dropdown menu at the top right of the Extensions view.
Once you've found an extension you want to install, click on the "Install" button next to the extension name.
Alternatively, you can click on the extension card to view more details and then click the "Install" button.
VS Code will download and install the extension automatically.
After installing extensions, you can manage them from the Extensions view.
Enable or disable extensions by toggling the switch next to the extension name.
Uninstall an extension by clicking on the gear icon next to the extension name and selecting "Uninstall".
VS Code may recommend extensions based on your usage patterns and the programming languages you work with.
Check the "Recommended" category in the Extensions view to find extensions that are tailored to your needs.
The "Popular" category in the Extensions view lists extensions that have a high number of installs and positive ratings.
Browse through the popular extensions to see if there are any that match your requirements.

Setting up the Version Control System
Visit the official Git website: https://git-scm.com/
Click on the download link for your operating system (Windows, macOS, Linux).
Follow the instructions to download the installer.
Double-click on the downloaded installer file (`Git-x.x.x-x64.exe`) and follow the installation wizard instructions. You can choose the installation directory and select components to install.
After installation, open a terminal (Command Prompt on Windows) and type `git --version`. You should see the installed Git version. This confirms that Git has been successfully installed.
Open a terminal and run the following commands, replacing `"Your Name"` and `"your_email@example.com"` with your actual name and email:
     git config --global user.name "Your Name"
     git config --global user.email "your_email@example.com"
You can verify your configuration by running:
     git config --global --list
This will display your configured name and email.
Visit the GitHub website: https://github.com/
Click on "Sign up" and follow the instructions to create your GitHub account.
Create a new directory for your project on your local machine using a file explorer or terminal:
     mkdir my_project
     cd my_project
Inside your project directory, run the following command to initialize a new Git repository:
     git init
Add your project files to the directory. You can create files manually or using a code editor.
Use the following command to add your files to the staging area:
      git add.
This command adds all files in the current directory to the staging area. You can also specify individual files or directories.
Commit your changes to the local repository using the following command:
      git commit -m "Initial commit"
Replace `"Initial commit"` with a meaningful commit message describing the changes you made.
On GitHub, create a new repository by clicking on the "+" icon in the top-right corner of the page and selecting "New repository".
Follow the instructions to create a new repository, giving it a name and optional description.
After creating the repository, GitHub will provide you with a URL. Use this URL to link your local repository to the remote GitHub repository:
      git remote add origin <repository_URL>
Replace `<repository_URL>` with the URL provided by GitHub.
Finally, push your committed changes to the remote GitHub repository using the following command:
      git push -u origin master
This command pushes your changes from the local `master` branch to the remote `master` branch on GitHub.

Installing Programming Languages and Runtimes
To install Python from [Python.org](https://www.python.org) 
Visit the official Python website: https://www.python.org
Click on the "Downloads" tab.
Choose the version of Python you want to download. It's recommended to download the latest stable version.
Select the appropriate installer for your operating system (Windows, macOS, or Linux).
For Windows:
Double-click on the downloaded installer (`python-x.x.x.exe`) to start the installation.
Check the box that says "Add Python x.x to PATH" during installation to make Python accessible from the command line.
Click "Install Now" and follow the installation wizard instructions.
After installation, open a terminal or command prompt and type `python --version`. You should see the installed Python version. This confirms that Python has been successfully installed.
Python doesn't require separate compilers or runtimes, as it's an interpreted language. However, if you're working with libraries or frameworks that have C extensions, you may need compilers like GCC (for C) or Visual C++ (for Windows).
Install necessary compilers and runtimes based on the requirements of your project. For example, if you're using libraries that require compilation, install the appropriate development tools for your operating system.
Create a simple Python script (e.g., `hello.py`) using your text editor or IDE. For example:
     print("Hello, Python!")
Open a terminal or command prompt.
Navigate to the directory containing your Python script.
Run the script by typing `python hello.py` and pressing Enter.
You should see the output `Hello, Python!`, indicating that Python is correctly installed and configured.

Install package managers
Pip is a package manager for Python that allows you to install and manage additional libraries and dependencies.
Check if Pip is already installed by running `pip --version` in the terminal/command prompt. If not, you can install it using the following command:
     python -m ensurepip
Upgrade Pip to the latest version using:
     python -m pip install --upgrade pip
Virtualenv is a tool used to create isolated Python environments for projects, preventing conflicts between dependencies.
Install Virtualenv using Pip:
     pip install virtualenv

Configure a Database
To download MySQL
Go to the official MySQL website: https://dev.mysql.com/downloads/.
Scroll down to find the MySQL Community (GPL) Downloads section.
Under MySQL Community (GPL) Downloads, locate the "MySQL Installer for Windows" section.
Click on the "Download" button for the MySQL Installer appropriate for your Windows system. For example, if you have a 64-bit system, choose the 64-bit version.
Once the installer is downloaded, locate the downloaded file (e.g., `mysql-installer-community-x.x.xx.xx.msi`) in your Downloads folder or the location where you saved it.
Double-click on the installer file to run it.
After running the installer, the MySQL Installer setup wizard will appear.
Select the setup type. For most users, the "Developer Default" setup type is recommended as it includes commonly used MySQL products and features.
Click on the "Next" button to proceed.
The installer will connect to the MySQL servers to fetch the latest products and updates. This may take a moment depending on your internet connection.
Once the product list is loaded, select the MySQL products you want to install. Typically, this includes MySQL Server, MySQL Workbench (a graphical tool for database design and administration), and other optional components.
Click on the "Next" button to proceed.
Review the products and features you selected for installation.
Click on the "Execute" button to begin the installation process.
The installer will download and install the selected MySQL products and components. This may take some time depending on your system's performance and internet speed.
During the installation process, you'll be prompted to configure MySQL Server.
Configure the MySQL Server by setting a root password and other necessary parameters as per your requirements.
Optionally, you can choose to configure MySQL as a Windows service for automatic startup.
Once the installation and configuration are completed successfully, you'll see a confirmation message.
Click on the "Finish" button to exit the installer.
To verify that MySQL Server is installed and running correctly, open the MySQL Command Line Client or MySQL Workbench from the Start menu.
Log in using the root username and the password you set during the installation process.
If you can successfully connect to the MySQL server, it means the installation was successful.


Set Up development Environments and Virtualization
To download Docker
Visit the Docker website: https://www.docker.com/products/docker-desktop
Click on the "Download Docker Desktop" button.
Docker Desktop is available for both Windows and macOS. Choose the appropriate version for your operating system.
You may need to create a Docker Hub account to proceed with the download.
 Once the Docker Desktop installer is downloaded, locate the file (e.g., `Docker Desktop Installer.exe` for Windows).
Double-click on the installer file to start the installation process.
Follow the on-screen instructions provided by the installer to complete the installation.
During the installation, Docker Desktop may require enabling virtualization in your system BIOS. Follow the prompts to enable it if necessary.
After installation is complete, Docker Desktop should start automatically.
Docker Desktop will initialize and start the Docker daemon, which allows you to run Docker containers on your system.
There are several virtualization platforms available, such as VirtualBox, VMware, and Hyper-V.VirtualBox is a free and open-source virtualization platform.
Visit the VirtualBox website: https://www.virtualbox.org/
Click on the "Download" link to go to the downloads page.
Download the appropriate installer for your operating system (Windows, macOS, Linux).
Double-click on the downloaded installer file and follow the on-screen instructions to install VirtualBox.
Considerations:
Docker containers and virtual machines provide isolation for project dependencies, ensuring that each project runs in its own isolated environment without interference from other projects.
By packaging project dependencies in Docker containers or virtual machines, you can ensure consistent environments across different machines, making it easier to share and collaborate on projects.
Docker containers and virtual machines can be easily transferred between different machines, allowing you to deploy projects on different platforms without worrying about compatibility issues.
Lightweight: Docker containers are lightweight compared to virtual machines, making them faster to start and consume fewer resources.
Easy Deployment: Docker containers are easy to deploy and manage, with built-in support for container orchestration tools like Kubernetes.
Ideal for Microservices: Docker is well-suited for microservices architectures, where each component runs in its own container.
Strong Isolation: Virtual machines provide stronger isolation compared to Docker containers, making them suitable for running legacy applications or environments with strict security requirements.
Hardware-Level Virtualization: Virtual machines emulate hardware, allowing you to run different operating systems on the same physical machine.
Compatibility: Virtual machines are compatible with a wide range of operating systems, making them suitable for running Windows, Linux, and macOS environments.

Challenges faced and strategies to overcome them
Firewall settings or network restrictions may prevent downloads or installations from completing successfully.
 I Temporarily disabled firewall settings to allow access to the required resources. 
Limited disk space may prevent installation or cause issues during the setup process.
  I Freed up disk space by deleting unnecessary files or applications and considered installing software on an external drive with sufficient space if internal storage is limited.
Some software installations may require additional dependencies or prerequisites to be installed beforehand. Like Flutter needing Vs code or Android.i reviewed the installation documentation carefully to identify any required dependencies or prerequisites and installed missing dependencies manually and used package managers to automate the process.
Insufficient permissions may prevent certain installation steps from completing, especially on shared or restricted systems.
   I run installation processes with administrator privileges where necessary. To ensure proper permissions are set for installation directories and files.
Using outdated software versions may lead to compatibility issues or missing features.
   I regularly check for updates and install the latest versions of the software an enable automatic updates where possible to ensure you're always using the latest stable releases.
Incorrect configuration settings or parameters during installation may result in errors or unexpected behavior.
   i double-check configuration settings and parameters before proceeding with installation and refer to installation guides or documentation for recommended configurations and troubleshooting tips.
Downloads or installations may get interrupted due to network issues, system crashes, or power outages.
   I ensure a stable internet connection during downloads and installations. 
Inadequate documentation or lack of support resources may make it difficult to troubleshoot issues during setup.
    I search online forums, community websites, or official documentation for solutions to common installation problems. Reach out to the software's support team or community for assistance if needed. I keep detailed notes of any encountered issues and their resolutions for future reference.
