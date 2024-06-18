Operating System:
•	Download and Install Windows 11: Visit Microsoft's Windows 11 download page and follow the installation instructions.
 ![image](https://github.com/Mitchy001/se-assignment-1-setting-up-your-developer-environment-Mitchy001/assets/140062227/02e915e3-5170-46a6-b90a-bb37547c148e)

Window Installation process 2:
   Step 1 - Format the drive and set the primary partition as active.
Connect the USB flash drive to your technician PC.
Open Disk Management: Right-click on Start and choose Disk Management.
Format the partition: Right-click the USB drive partition and choose Format. Select the FAT32 file system to be able to boot either BIOS-based or UEFI-based PCs.
Set the partition as active: Right-click the USB drive partition and click Mark Partition as Active.


Step 2 - Copy Windows Setup to the USB flash drive.

Use File Explorer to copy and paste the entire contents of the Windows product DVD or ISO to the USB flash drive.
Optional: add an unattend file to automate the installation process. For more information, see Automate Windows Setup.




Step 3 - Install Windows to the new PC.

Connect the USB flash drive to a new PC.
Turn on the PC and press the key that opens the boot-device selection menu for the computer, such as the Esc/F10/F12 keys. Select the option that boots the PC from the USB flash drive.
Windows Setup starts. Follow the instructions to install Windows.
Remove the USB flash drive.
2. Text Editor or IDE:
•	 To install Visual Studio Code (VS Code), follow these steps: 
•	Download: Visit the official Visual Studio Code website (https://code.visualstudio.com/) using your web browser. 
•	Download Installer: Click on the "Download for Windows" button to download the installer file. 
•	Run Installer: Once the download is complete, locate the downloaded installer file (usually in your Downloads folder) and double-click on it to run it. 
•	Installation Wizard: Follow the prompts in the installation wizard. You can choose the installation location and whether to add VS Code to your PATH (environment variables) during the installation process. 
•	Complete Installation: After the installation is complete, you can launch Visual Studio Code by double-clicking its shortcut icon on the desktop or by searching for "Visual Studio Code" in the Start menu
  Main Components of the VS Code User Interface:
   1. Activity Bar:
Located on the far left of the interface.
Provides access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.
You can customize the Activity Bar by right-clicking and choosing which icons to show or hide.
2. Side Bar:
       Displays different panels depending on the Activity Bar selection.
For instance, selecting Explorer shows the file explorer where you can manage project files.
3. Editor Group:
The main area where you edit files.
Supports multiple editors side-by-side (split view).
Tabs at the top show open files, and you can switch between them easily.
4. Status Bar:
Located at the bottom of the window.
Shows information about the current workspace, such as branch name, encoding, line endings, and errors or warnings.
You can click on items for more details or to change settings.
Visual studio interface
 
       
3. Version Control System:
•	Install Git: Download Git from git-scm.com and follow the installation instructions. Configure Git with your name and email.
 
    Create a GitHub account: Sign up at GitHub to host your repositories.
•	Initialize a Git repository: Navigate to your project folder in the command line (git init) and make your first commit (git commit -m "Initial commit").
![image](https://github.com/Mitchy001/se-assignment-1-setting-up-your-developer-environment-Mitchy001/assets/140062227/df06e54d-36c0-4304-afc6-b90b83ef6f9e)

5. Programming Languages and Runtimes:
•	Python: Download Python from python.org and install it on your system. Ensure you select the option to add Python to your PATH during installation.
 ![image](https://github.com/Mitchy001/se-assignment-1-setting-up-your-developer-environment-Mitchy001/assets/140062227/88712717-712d-415c-ae26-c880e6f80bb1)


•	Install respective compilers, interpreters, or runtimes as per your project requirements.
 
5. Package Managers:
•	pip (Python): Python usually comes with pip. Verify its installation by running pip --version in the command line.
   ![image](https://github.com/Mitchy001/se-assignment-1-setting-up-your-developer-environment-Mitchy001/assets/140062227/96d3c6df-f9ba-43e4-8b17-4c39699f85d5)
    
6. Database (MySQL):
•	Download and Install MySQL: Get MySQL from MySQL Community Downloads and follow the installation instructions. Choose the appropriate installer for your system (e.g., MySQL Installer for Windows).
 ![image](https://github.com/Mitchy001/se-assignment-1-setting-up-your-developer-environment-Mitchy001/assets/140062227/a81a2cba-fbd6-4019-90cc-dc8978f201fe)

7. Development Environments and Virtualization (Optional):
•	Consider using  virtual machines (e.g., Hyper-V, VirtualBox) to isolate project dependencies and manage consistent environments.
 ![image](https://github.com/Mitchy001/se-assignment-1-setting-up-your-developer-environment-Mitchy001/assets/140062227/74cc5ead-539b-46d0-b305-42ebbe3c1e6e)

8. Extensions and Plugins:
•	Explore extensions for Visual Studio Code: Open Visual Studio Code, go to the Extensions view (Ctrl+Shift+X), and search for extensions related to your programming languages and workflow (e.g., Python, Git integration).
 
9. Document Your Setup:
•	Create a detailed document outlining:
o	Steps taken to set up each tool and environment.
o	Configurations made (e.g., Git configuration, Python installation).
o	Customizations (e.g., Visual Studio Code settings, Docker configurations).
o	Troubleshooting steps encountered and solutions applied.



#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
