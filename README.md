[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15270537&assignment_repo_type=AssignmentRepo)
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

 structured documentation template for setting up a development environment on Windows:

# Development Environment Setup Documentation

## Operating System Installation
- **Objective**: Install Windows 11 on your machine.
- **Steps**:
  1. Visit [Microsoft's Windows 11 download page](https://www.microsoft.com/software-download/windows11) and download the installation media.
  2. Follow on-screen instructions to install Windows 11 on your computer.
  Before starting the installation process, ensure you have:

Back up important data from your current operating system (if applicable).
Verified that your computer meets the minimum system requirements for Windows 11.
Prepared a bootable USB drive with the Windows 11 installation media.
Step-by-Step Windows 11 Installation Procedure
Download Windows 11 Installation Media:

Visit the Microsoft Windows 11 download page.
Click on "Download now" to download the Windows 11 Installation Assistant.
Create a Bootable USB Drive:

Insert a USB drive (at least 8 GB) into your computer.
Run the Windows 11 Installation Assistant that you downloaded.
Follow the prompts to create a bootable USB drive. This process will download Windows 11 and prepare the USB drive as the installation media.
Prepare Your Computer:

Restart your computer with the bootable USB drive inserted.
Enter the BIOS/UEFI settings by pressing a specific key (like F2, F12, Delete) during the boot process. The key depends on your computer's manufacturer (check your computer's manual).
In the BIOS/UEFI settings, set the USB drive as the primary boot device.
Install Windows 11:

Save the BIOS/UEFI settings and restart your computer.
Windows 11 setup will start automatically from the USB drive.
Select language, time, and keyboard preferences, then click "Next".
Click on "Install now".
Enter Product Key:

If prompted, enter your Windows 11 product key. You can also choose "I don't have a product key" to proceed without entering a key (you can activate Windows later).
Select Edition:

Choose the edition of Windows 11 you want to install. Select the one appropriate for your use (e.g., Windows 11 Home, Windows 11 Pro).
Accept License Terms:

Read and accept the Microsoft Software License Terms.
Choose Installation Type:

Select "Custom: Install Windows only (advanced)" if you're performing a clean installation and want to erase everything on the disk. Alternatively, choose "Upgrade" if you're upgrading from a previous version of Windows.
Partition Selection:

Select the partition where you want to install Windows 11 (if performing a clean installation). If you're upgrading, you might not see this step.

## Text Editor or IDE Installation
- **Objective**: Install Visual Studio Code for coding.
- **Steps**:
  1. Download Visual Studio Code from [Visual Studio Code website](https://code.visualstudio.com/Download).
  2. Run the installer and follow the installation prompts.

## Version Control System Setup
- **Objective**: Set up Git and GitHub for version control.
- **Steps**:
  1. Download Git from [Git official website](https://git-scm.com/download/win).
  2. Install Git with default settings.
  3. Configure Git with your username and email using `git config --global user.name "Your Name"` and `git config --global user.email "your.email@example.com"`.
  4. Create a GitHub account at [GitHub](https://github.com).
  5. Initialize a Git repository for your project:
     ```
     mkdir YourProject
     cd YourProject
     git init
     git remote add origin https://github.com/yourusername/your-repository.git
     ```
  6. Make your first commit:
     ```
     git add .
     git commit -m "Initial commit"
     git push -u origin main
     ```

## Programming Language and Runtime Installation
- **Objective**: Install Python for development.
- **Steps**:
  1. Download Python from [Python.org](https://www.python.org/downloads/).
  2. Run the installer, making sure to check the box "Add Python to PATH".
  3. Verify installation by opening a command prompt and typing `python --version`.

## Package Manager Installation
- **Objective**: Install pip for Python package management.
- **Steps**:
  1. Pip usually comes bundled with Python installation. Verify its installation by typing `pip --version` in the command prompt.

## Database Setup
- **Objective**: Install MySQL database.
- **Steps**:
  1. Download MySQL from [MySQL official website](https://dev.mysql.com/downloads/windows/installer/5.7.html).
  2. Run the installer and follow the installation prompts.
  3. Set a root password during the installation process.

## Optional: Development Environments and Virtualization
- **Objective**: Set up Docker for virtualization (if needed).
- **Steps**:
  1. Download Docker Desktop for Windows from [Docker Hub](https://hub.docker.com/editions/community/docker-ce-desktop-windows).
  2. Run the installer and follow the installation prompts.

## Extensions and Plugins
- **Objective**: Enhance Visual Studio Code with useful extensions.
- **Steps**:
  1. Open Visual Studio Code.
  2. Navigate to Extensions (Ctrl+Shift+X).
  3. Search and install extensions based on your programming needs (e.g., Python, GitLens, Docker).

## Documentation Completion
- **Contents**:
  - Overview
  - Installation Steps
  - Configuration Details
  - Troubleshooting Tips
  - Screenshots (where applicable)

## Project Repository
- **Objective**: Create a GitHub repository for your project.
- **Contents**:
  - Initialize repository with README.md and .gitignore files.
  - Push your initial code and configurations to GitHub.

## Reflection
- **Objective**: challenges faced and strategies used during setup.
- **Contents**:
  Challenges Encountered:
Compatibility Issues with Hardware:

Challenge: Some older hardware components may not be compatible with Windows 11, causing installation errors or issues during use.
Solution:
Before installation, check Microsoft's official compatibility list for Windows 11.
Update firmware and drivers to the latest versions compatible with Windows 11.
Consider upgrading hardware if compatibility issues persist.
Bootable USB Drive Creation Errors:

Challenge: Errors during the creation of a bootable USB drive using the Windows 11 Installation Assistant.
Solution:
Ensure the USB drive meets the minimum size requirement (typically 8 GB).
Use a reliable USB drive and try creating the bootable media on a different computer if errors persist.
Use alternative tools like Rufus to create the bootable USB drive if the Windows 11 Installation Assistant fails.
BIOS/UEFI Settings Configuration:

Challenge: Difficulty accessing or configuring BIOS/UEFI settings to boot from the USB drive.
Solution:
Consult your computer's manual or manufacturer's website to determine the correct key to access BIOS/UEFI settings during boot.
Disable Secure Boot temporarily if it interferes with booting from the USB drive.
Ensure the USB drive is properly recognized and set as the primary boot device in BIOS/UEFI settings.
Partitioning and Disk Management Issues:

Challenge: Confusion or errors during partition selection or disk formatting during Windows 11 installation.
Solution:
Back up important data before proceeding with disk management and partitioning.
Use the "Custom: Install Windows only (advanced)" option for clean installations to manage partitions manually.
Ensure to select the correct partition for installation to avoid accidental data loss.
Product Key Activation Problems:

Challenge: Issues with entering or activating the Windows 11 product key during installation.
Solution:
Verify the correctness of the product key entered.
Choose the option "I don't have a product key" to proceed without entering a key and activate Windows later.
Ensure your internet connection is stable during activation.
Driver and Software Compatibility Issues:

Challenge: Some devices or software may not have compatible drivers or may not function properly after Windows 11 installation.
Solution:
Check with the manufacturers for updated drivers compatible with Windows 11.
Use compatibility mode or troubleshoot compatibility for older software if needed.
Consider alternative software or hardware solutions if compatibility issues persist.
Reflection and Solutions Implemented:
Documentation and Preparation: Creating a detailed setup document with step-by-step instructions and screenshots helped mitigate confusion and errors during installation.
Troubleshooting Approach: Utilizing online resources, community forums, and manufacturer support helped resolve compatibility issues and driver problems effectively.
Adaptability: Being flexible with hardware upgrades or software alternatives ensured a smoother transition to Windows 11 without compromising productivity.


  
