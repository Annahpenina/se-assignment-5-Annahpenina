[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15276477&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Download the vs code on the vs code website, click on the "download visual studio code" option.
   Follow the on screen instructions to download the installer.
   Run the download installer.
   Choose "visual studio" workload during istallation.
   Install : click the " install" button  to start the installation process.
   Launch visual studio  once installation is complete.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.


Theme: Choose a theme of your choice (e.g dark or light, e.t.c)
Font: Set font which is best for you coding ( e.g Code, Consolas, e.t.c)
Indentation: Configure the tab size and whether to use spaces or tabs for indentation.

Extensions: choose and download extention of you choise and according to yor coding (e.g python, java e.tc)
Code Spell Checker: Highlights spelling errors in your comments and strings.
Integrated Terminal: Customize the terminal to your liking (e.g git bash, power shell)
Workspace settings: Adjust settings specific to your current workspace if needed.
Version Control Integration: Familiarize yourself with the Git integration provided by VS Code. You can stage changes, commit, pull, push, and resolve merge conflicts directly from the editor.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

Activity Bar: It provides quick access to different views and features of VS Code, such as Explorer (file explorer), Search, Source Control (Git integration), and more.

Side Bar: It provides more detailed navigation and information related to your project files and workspace.

Editor Group:
Purpose: Editor Groups are they are central workspace areas where you can view and edit files, thus you can to work on different files at the same time.

Status Bar: It provides various status indicators, information, and quick actions related to your workspace and the current file.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   command palette  is a powerful tool that allows users to access and execute various commands and actions within the editor. It provides a quick and efficient way to perform tasks without having to navigate through menus or remember keyboard shortcuts.

To access the Command Palette, you can use one of the following methods:

Keyboard Shortcut: Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac).
Menu: Click on the "View" menu in the top toolbar, then select "Command Palette."
Right-click Context Menu: Right-click anywhere in the editor or sidebar, then select "Command Palette" from the context menu.
Examples of Common Tasks Using the Command Palette:
File Operations:

Open File: File: Open File or simply start typing the filename.
Create New File: File: New File.
Save All: File: Save All.
Close Editor: Workbench: Close Editor.
Editing:

Find: Find.
Replace: Replace.
Change Language Mode: Change Language Mode.
Navigation:

Go to Symbol: Go to Symbol in File.
Go to Line: Go to Line.
Open Symbol by Name: Go to Symbol....
Source Control:

Commit Changes: Git: Commit.
Pull from Remote: Git: Pull.
Push to Remote: Git: Push.
Extensions:

Install Extension: Extensions: Install Extensions.
Update All Extensions: Extensions: Show Outdated Extensions.
Settings:

Open User Settings: Preferences: Open User Settings.
Open Workspace Settings: Preferences: Open Workspace Settings.
Debugging:

Start Debugging: Debug: Start Debugging.
Stop Debugging: Debug: Stop Debugging.
Terminal:

Open Terminal: Terminal: Create New Integrated Terminal.
Run Selected Text in Terminal: Terminal: Run Selected Text in Active Terminal.
Tasks:

Run Task: Tasks: Run Task.
Window Management:

New Window: Workbench: New Window.
                                                             source: chatGPT


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extensions play a crucial role in enhancing the functionality and customization options available in Visual Studio Code (VS Code). They allow users to add new features, integrate with external tools and services, and tailor the editor to their specific needs and workflows. Extensions can range from language support and syntax highlighting to debugging tools, version control integrations, and productivity enhancements.

Finding and Installing Extensions:
Extension Marketplace: The primary way to discover and install extensions is through the Visual Studio Code Marketplace, accessible from within the editor or via the web. Users can search for extensions by name, category, or tag, read reviews, and see popularity ratings.
Command Palette: Users can also access the extension management commands via the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) by searching for commands like "Extensions: Install Extensions" or "Extensions: Show Recommended Extensions".
VS Code Marketplace Website: Users can visit the VS Code Marketplace website (https://marketplace.visualstudio.com/) to explore and install extensions directly from their web browser. They can then sync their installed extensions with their VS Code installation.
Managing Extensions:
Once installed, extensions can be managed easily within Visual Studio Code:

Enable/Disable: Users can enable or disable installed extensions from the Extensions view (Ctrl + Shift + X or Cmd + Shift + X).
Update: VS Code automatically checks for updates to installed extensions, but users can also manually update extensions from the Extensions view.
Uninstall: Users can uninstall extensions they no longer need directly from the Extensions view.
Essential Extensions for Web Development:
ESLint/Prettier: For JavaScript/TypeScript linting and code formatting.
Debugger for Chrome/Firefox: Enables debugging JavaScript code in Chrome or Firefox directly from VS Code.
Live Server: Quick development server with live browser reloading.
HTML CSS Support: Provides autocompletion and syntax highlighting for HTML and CSS.
Auto Close Tag/Auto Rename Tag: Helps with HTML/XML tag closing and renaming.
Path Intellisense: Autocompletes filenames in your code.
GitLens: Enhances Git integration, providing inline Git blame annotations, code lens, etc.
Color Highlight: Highlights colors found in CSS files.
Bracket Pair Colorizer: Helps visually match brackets with corresponding colors.
Lorem Ipsum: Generates Lorem Ipsum placeholder text.
                                                             source: chatGPT

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

Using the Menu: Click on the "Terminal" menu in the top toolbar, then select "New Terminal."
Keyboard Shortcut: press control + j

advantages:
Switch between coding and terminal tasks without switching between different windows and back.

You can interact with VS Code features directly from the terminal, such as running Git commands, debugging, and opening files.

The integrated terminal  allows you to stay within the same window while coding and executing commands.

The integrated terminal automatically opens at the root of your workspace, providing easy access to project files and resources.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Using the File Explorer:
   Click on the Explorer icon in the Activity Bar.
   Select New File,New Folder if creating new and for existing files and folders, you navigate to the exact files or folders you want on the explora.

   Managing Files and Folders:
   click on the file or folder in the explora to rename or delete.
   click on the file or fold in the explora that you want to copy or move to your new destination and past.

   Navigate between files and directories.
   select files to open click and open those files. use the navigation bar at the top to navigate through your repositories and switch between tabs.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Go to the file menu, select the preferences optiona, you will find all the settings and customize your setting up to your liking.

   Theme:
   go to the file  menu, select preferences option.
   select theme from that menu then choose how you like to customize your theme from colour, file icon and product icon theme.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?


Install Required Extensions:

Ensure that the appropriate debugger extension is installed for your programming language. For example, if you're debugging JavaScript or TypeScript, you'll need the Debugger for Chrome extension.
Configure Launch Configuration:

Open your project folder in VS Code.
Navigate to the debug view by clicking on the debug icon in the Activity Bar (or pressing Ctrl + Shift + D).
Click on the gear icon to open the launch.json file.
If you don't have a launch configuration already, you can create one using the "Add Configuration" button and selecting the appropriate debug configuration for your project type. This file specifies how to launch and debug your program.
Set Breakpoints:

Open the file you want to debug.
Click in the gutter next to the line number where you want to set a breakpoint. Alternatively, you can use the keyboard shortcut F9 to toggle breakpoints.
Start Debugging:

Press F5 or click on the green play button in the debug view to start debugging. This will launch your program in debug mode and halt execution at the breakpoints you've set.
Interact with Debugging Controls:

Once the debugger is running, you can use the debugging controls in the debug toolbar to step through your code, pause execution, resume execution, and inspect variables.
Inspect Variables and Expressions:

While debugging, you can hover over variables to see their current values or add them to the watch window for monitoring.
You can also use the debug console to execute expressions and commands in the context of your program.
Continue Debugging:

Continue stepping through your code, inspecting variables, and identifying issues until you've resolved the problem or completed your debugging session.
Key Debugging Features Available in VS Code:
Breakpoints:

Set breakpoints in your code to pause execution and inspect the state of your program.
Stepping Controls:

Step through your code line by line using controls like "Step Over", "Step Into", and "Step Out".
Watch Window:

Monitor the values of variables and expressions in real-time as you debug your program.
Call Stack:

View the call stack to understand the sequence of function calls leading up to the current point of execution.
Conditional Breakpoints:

Set breakpoints that only trigger when certain conditions are met, such as when a variable reaches a specific value.
Debug Console:

Interact with your program by executing commands and expressions directly in the debug console.
Exception Handling:

Handle exceptions and errors gracefully by configuring how VS Code responds to uncaught exceptions.
                                                            source: chatGPT

10. Using Source Control:
   
  
Open Your Project Folder:

Open VS Code and navigate to the folder containing your project or create a new folder for your project.
Initialize Git Repository:

Open the integrated terminal in VS Code (Ctrl + `` or Cmd + ``) and run the following command to initialize a Git repository:
csharp
Copy code
git init
Making Commits:
Stage Changes:

Use the Source Control view in the Side Bar (Ctrl + Shift + G or Cmd + Shift + G) to view and stage changes.
Click on the "+" icon next to the file(s) you want to stage, or use the "Stage All Changes" button to stage all changes.
Commit Changes:

Enter a commit message in the text box provided in the Source Control view.
Press Ctrl + Enter (Windows/Linux) or Cmd + Enter (Mac) to commit the changes.
Pushing Changes to GitHub:
Linking to GitHub:

Make sure you have a GitHub account and a repository created for your project on GitHub.
Open the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) and run the command:
makefile
Copy code
Git: Clone
Enter the URL of your GitHub repository and choose the local directory where you want to clone the repository.
Pushing Changes:

After making commits to your local repository, push the changes to your GitHub repository.
Use the Source Control view to ensure all changes are committed and staged.
Open the integrated terminal and run the following command to push changes to GitHub:
perl
Copy code
git push origin master
Replace origin with the name of your remote repository if you've named it differently, and master with the name of the branch you're pushing.
Authenticate with GitHub:

If prompted, provide your GitHub username and password or access token to authenticate and push changes to the remote repository. 

                                                             source: chatGPT

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

