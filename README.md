[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15286634&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

Prerequisites:

Ensure you have administrative privileges on your Windows 11 machine.
Make sure your system meets the minimum requirements for running VS Code.
Have a stable internet connection for the process to be successful.
Steps to Download and Install:

Download VS Code:

Open your web browser and go to the Visual Studio Code website.
Click on the "Download for Windows" button which will download the VS code installer for windows.

Run the Installer:

Once the download is complete, open the downloaded file (VSCodeSetup.exe).Double-click the installer file to run it.

Setup Wizard:

The VS Code Setup Wizard will open and a welcome screen will be displayed. Click NEXT to continue.
Read and accept the license agreement, then click NEXT.
Choose the destination folder for installation, then click NEXT.
Select additional tasks, such as creating a desktop icon or adding VS Code to the PATH, then click NEXT.
Click INSTALL to begin the installation process.

Complete Installation:

Wait for the installation to complete. Once the installation is complete, click finish to launch Visual Studio Code.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

First setups
Open the vs code from the start up menu.A welcome window will be displayed where a documentation is provided.
The vs code will require you to istall necessary extensions like python, lifesaver, pylance, prettier, debuggers and other extensions .
To navigate through the settings, open the setting menu where setting can be adjusted like the theme and font size.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

Main Components of the VS Code User Interface:

Activity Bar:
Located on the left side. Contains icons for Explorer, Search, Source Control, Run and Debug, and Extensions.

Side Bar:
Displays different views based on the selected activity like file explorer, search views, source control details, run and debug information and extension details.

Editor Group:
This is where you edit your code. It multiple tabs for different files where one works from.

Status Bar:
Located at the bottom of the window. Provides information about the current file like line number, encoding, language being used and Git branch. It also has notification icon where errors and other status notification are displayed.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

Command Palatte ia a powerful feature that privides quick access to various commands and functionalities without having to navigate through menus and allows one to perform a wide range of tasks efficiently by typing what you want to do.

How it can be accessed:
By using keyboard shortcuts; press ctrl+shift+p or F1.
Navigating through the menu where you click on the settings icon then select Command Palatte,

Taks that it can perform:
Opening files and folders, running and debugging code, version control for committing changes, managing extensions, formatting a document, searching, using settings and customazing, use of snippets and terminal operations.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions in vs code enhances its functionality by adding features that support various programming languages, frameworks, tools and workflows thus the developers environment is conducive.

   Acessing extensions, installing the and managing them: 

   Click the extension icon in the activity bar or access it using a combination of keyboard keys - ctrl+shift+x.

   To install the extensions, open the extension view an search an extension by typing the name. Click the install button on the desired extension.
   They can also be accessed using the Command Palette and type extension and select the the desired one to install.

   To manage them: Enable or disable them in the extension view area when you open the desired extension to be enabled or disabled.
   Unistalling the extensions- This helps the user remove extensions that they do not require.
   Updating extensions- Extension that need to be updated will be shown on the extension itself.

   Essential extensions of web development:
   Live Server: For live web development.
   Prettier: To keep your code tidy.
   ESLint: To catch JavaScript errors.
   Debugger for Chrome: For debugging in Chrome.
   Path Intellisense: For easier file navigation.HTML CSS Support:Enhances HTML and CSS IntelliSense in VS Code.
   npm Intellisense:Autocompletes npm modules in import statements.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   Using the menu:Go to the top menu and select Terminal then New Terminal
   Using the command Palatte:Press Ctrl+Shift+P to open the Command Palette.Type Terminal and Create New Terminal and press Enter.

Uses of the Intergrated Terminal

   Performs basic operations like switch between terminals, open multiple teminals and closing the terminals.

   Splitting of terminals that allows you run differnt commands side by side.

   Intergrated terminal support based on the default shell configured thus run the commands smoothly.

Advantages of using the Intergrated Terminal
   Convenience and efficiency since it does not require one to switch between different applications.
   Provides a consistent environment asit has paths and environment variables thus ensures consitency.
   Easy to navigate through the current project as it identifies the root of the project thus noadditionalnavigation is required.
   Allows customization where the terminal can be customized to match the development workflow like using the git terminal.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

Create New Files/Folders:
Right-click in the file explorer on the left and select New File or New Folder.

Open Existing Ones:
   Using the activity bar the menu button an click on file and open folder from the explore of the PC.

Managing Files and Folders:

Renaming Files and Folders:Right-click on the file or folder in the Explorer view then select Rename from the context menu.
Enter the new name and press Enter.

Deleting Files and Folders: Right-click on the file or folder then select Delete from the context menu.
Confirm the deletion.

Moving or Copying Files and Folders:
Drag and drop the file or folder to the desired location within the Explorer view.
Alternatively, you can right-click on the file or folder, select Cut or Copy, navigate to the destination folder, and then right-click and select Paste.

Navigate Easily:
   Click files in the explorer to open them.
   Use Ctrl+P to quickly find and open files.
   Use Ctrl+Tab to switch between open files.
   
8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Users can fing and customize settings through the user interface or by editing the settings JSON file.

Acessing:
   Settings UI.

Open the Command Palette with Ctrl+Shift+P.
Type "Preferences: Open Settings (UI)" and select it.

   Settings JSON.

Open the Command Palette with Ctrl+Shift+P.
Type "Preferences: Open Settings (JSON)" and select it.

Changing the theme:
   Using settings UI: Go to file - Preference - color theme or use command palette (ctrl+K  ctrl+T). Select a theme from the list.

   Using setting JSON: Open the settings JSON file. Add or modify the setting "workbench.colorTheme": "Dark+ (default dark)"  and replace it with your preferred theme.

Changing the Font Size:Using Settings UI.

Open the Settings UI.
In the search bar, type "font size".
Adjust the "Editor: Font Size" setting to your preferred size.

Using Settings JSON:

Open the settings JSON file.
Add or modify the following setting:
json
Copy code
"editor.fontSize": 14
Replace 14 with your desired font size.

Changing Keybindings:Using Keybindings UI.

Open the Command Palette with Ctrl+Shift+P .
Type "Preferences: Open Keyboard Shortcuts" and select it.
Search for the command you want to change, double-click on it, and press the new key combination.

Using Keybindings JSON:

Open the Command Palette with Ctrl+Shift+P.
Type "Preferences: Open Keyboard Shortcuts (JSON)" and select it.
Add or modify the keybinding in the JSON file. Example
    "key": "ctrl+s",
    "command": "workbench.action.files.save"
  
Replace "ctrl+s" with your desired key combination and "workbench.action.files.save" with the command you want to bind it to.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Steps to set up and start Debugging:
First have the necessary extensions require dependig on the programming languages.
Open or create a project folder and wtite a simple program.
Go to run and debug button on the activity bar or by pressing ctrl+shift+D to configure the debugger.
To run the code click on the button for running and debugging and it will start debugging.
The program will start running and will stop at any breakpoints.

Key debugging features in vs code

Breakpoints: Set by clicking in the gutter next to line number.

Watch: Add variables to the watch panel to monitor their values during execution.

Variable inspection: They hover over variables to see their current values.

Step controls: Step over(F10)- Execute the next line of code.
   Step into(F11)-Step into functions to debug inside them.
   Step out(shift+F11)-Step out of the current function.
   Continue(F5)- Continue execution untill the next breakpoint.     

Debug console: Evaluate expressions and execute code in the context of the pause pf the program.


10. Using Source Control:
   How can users integrate Git with VS Code for version control? Describe the process of initializing a repository
   making commits, and pushing changes to GitHub.

   Integrating Git with VS Code:

Ensure Git is installed on your system. You can download it from the git web.
Verify the installation by running git --version in your terminal.

Open Your Project in VS Code:

Open your project folder in VS Code by going to File then Open folder.

   Initializing a repository:

 Open the source control  view by clicking the source control icon on the activity bar or using ctrl+shift+G and then intialize repository.  

   Committing:
Using the source control view, go to file in the change section and click on the + sign  to stage all changes.
After staging enter a commit message on the box at the source control view then click on the checkmark icon or press ctrl+Enter.

   Pushing changes to GITHUB:
First create a GitHub repository, use the VS Code terminal and add the GitHub repository as a remote.
Push your local commits to GitHub by executing (git push -u origin master or main).

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

