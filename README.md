[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15296417&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   a)Visit the visual studio website https://code.visualstudio.com/download
   b)Click on download visual studio code for windows 
   c)Follow the on-screen instructions to download the installer 
   d)Run the download installer as administrator after right clicking on the downloaded vs code folder.
   e)Agree with the liscence terms,click next,if you don't like the default location of visual studio you can change click next then next again. 
   f) check all boxes on the setting up of additional tasks 
   g)Click next and install then check the launch box after installation and finish
   h)After installation launch Visual Studio ,the app will open on the screen or you can see its icon on the desktop click on it.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   If one wants to change the appearance of the page go to file select preference then theme
   Next install extensions you require by clicking ctrl + shift + X all at once or the icon on the left edge with a broken box(extensions)
   If you want to use python you can search for python extension choose the first one with a tick indicating its verified install.
   Install a page will come up with the python icon you can also disable it from there
    Choose and install other extensions according to the programming language of interest
    It you want to make your code pretty install 'prettier' through the extension
    Install also code runner to help in running code and debugging where necessary    

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Acticity Bar
   -Located on ieft side allows you to switch between different views and provides access to;
   Explorer which displays your project files,Search,Source Control which provides git integration and version control features,Run and Debug accsesses debugging features and configurations and Extensions which manages VS code extensions
   Side Bar
   -Displays the contents searched from the activity bar e.g. if you select the explorer view the side bar will show the file and folder structure of your project.
   Editor Group
   -The central area of the user interface.You can open multiple files in tabs and split the editor into multiple groups to view and edit more than one file simoultaneously.
   Status Bar
   -Located at the bottom of the window and displays various status information such as current git branch ,indicates the programming language of the current active file,line and column number of the cursors position, shows the file encoding and line-ending type and finally displays notifications from extenstions or VS code itself.
   Panels
   -Located at the bottom of the window above the status bar.They include;Integrated terminal for running shell commands ,Output shows output from various VS code processes and extensions,Debug Console which displays debugging output and allows for interaction during debugging sessions and Problems-lists errors and warnings in your code based on linting and diagnostics.
   Menu Bar
   -Found at the top left of the window .Has the following menus File,View,Go for navigating different parts of the project,Run for managing debugging and run configurations,Terminal for opening and managing intergrated terminals and Help for accessing other resources.Also Edit for editing commands like undo,redo and find.
   Minimap
   -Found at the top right.A small overview of the whole file structure.
   Tabs
   -Located at the top of the editor area.Show the currently open files and can easily navigate to them by clicking the respective tabs.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
-A command palette is a feature that provides quick access to various commands and settings without needing to navigate through menus like a search bar where you type relevant keywords and opens the files or execute commands.
-One can access the command palette by going to View at the top and select Command Palette or press Ctrl+ Shift + P.
-It is used for running commands,changing settings,opening files without going to menu,finding tasks and running configured tasks and also managing extensions.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Extensions enhance functionality and customization of the developed environment by;
   -Providing support for a wide variety of programming languages such as python,JavaScript or C++
   -They enhance debugging capabilities of vs code allowing you to set breakpoints,inspect variables and step through code.e.g. Python extension for python debugging.
   -Moreover,they improve integration with version control systems such as Git which is enhanced by Gitlens extension.Has features like viewing detailed commit information and comparing revisions and branches.
   -Extensions help maintain code quality by providing linting and formatting tools such as Prettier for consistent code formatting across various languages.
   -They also boost productivity by providing features such as Live share,Bracket pair colorizerand Code snippets.
   -Extensions allow for customizing the look and feel of VS Code such as themes for the editor and icon pack for file explorer.
   -They provide specific support for frameworks and libraries offering tools for development,debugging and deployment.

   Extensions can e installed from the extension view (Ctrl + Shift + X) by searching for the desired extension and clicking inslall.If the extension has a tick it means its appproved if it doesnt then not approved.
   -As for management extensions can be enabled,disenabled or uninstalled from the Extensions view.

Extensions essential for Web development include;
-Prettier-Code Formatter
-ESLint
-HTML CSS Support
-Live server
-Debugger for chrome or Firefox
-Jest
-Editorconfig
-Markdown all in one

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   -Go to menu and click the 3dots at the top left.
   -Click terminal then select New terminal and Voila you have your terminal
   For usage;You can run any command-line tool or script such as git e.g.type git status to check your status of your git repository
   -You can open multiple terminal instances.To create a new terminal instance,click the +icon in the terminal panel or use shortcut Ctrl + Shift + Windows
   -You can switch between multiple terminals by clicking on the terminal tabs at the top of the terminal panel orby using the dropdown menu
   -You can split terminal to view multiple terminals side by side by clicking the split terminal icon or use shortcut Ctrl + Shift + 5 Windows
   -You can customize the integrated terminal by changing its settings by pressing Ctrl + Windows then search terminal to see available customization options.
   -You can define and run tasks from the terminal.
   
   Advantages of using the integrated terminal compared to an external terminal are;
   -Seamless workflow
   -Quick access:easily open and switch between the terminal and your code editor without needing to switch windows or applications.
   -Automatic path setting of environment and configurations relevant to your VS Code workspace reducing need for manual configuration.
   -Git integration you can use git commands within the integrated terminal.
   -Quickly navigate to errors and warnings in your code by following terminal output and leveraging VS Code's problem matcher.
   -Start debugging sessions and view realtime output in the terminal,making it easier to diagnose and fix issues. 

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   How to create a new file;
   a)Open the Explorer view by clicking the explorer icon in the Activity Bar on the left or press Ctrl + Shift + E on the keyboard.
   b)Right-click on the folder where you want to create the new file.
   c)Select New File from the context menu.
   d)Enter the name for the new file and press Enter
   How to create a new folder
   a)Open the explorer view.
   b)Right-Click on the parent folder or in the blank area of the Explorer
   c)Select New Folder from the context menu
   d)Enter the name ofthe new folder and press Enter
   Opening a File
   a)Open the Command Palette or(Ctrl + Shift + P) then type the name of the file
   b)Type >Open File and select it
   c)Navigate to the file you want and select it
   Opening a Folder
   a)Open the Command Palette or (Ctrl + Shift + P) then type the name of the folder.
   b)Type >Open Folder and select it
   c)Navigate to the folder you want to open and select it.
   Managing Files and Folders
   -Renaming a File or Folder(Using Explorer)
   a)Right-click on the file or folder you want to rename
   b)Select Rename from the context menu
   c)Enter the new name and press Enter
   -Move a file or folder 
   Drag and drop the file or folder to the desired location within the Explorer view
   -Delete a File or Folder
   a)Right-click on the file or folder you want to delete
   b)Select Delete from the context menu.
   c)Confirm deletion when prompted.
   -Copy and Paste a File or Folder
   a)Right-click on the file or folder you want to copy and select Copy
   b)Right-click on the destination folder and select Paste.
   You can use the integrated terminal to create,move or delete files and folders using command-line tools.

   Users can efficiently navigate to files or folders by
   opening the command palette-type go to file or folder then select the commmand and type the name of the file or folder you want to open.
   Open Editors View (Ctrl + K Ctrl+ E)
   shows a list of all open editors in the side bar
   Other Keyboard shortcuts
8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   Users can customize settings in VS Code through the Settings UI,the settings .json file,and the Keyindings UI.
   Settings UI is accessed by clicking on the gear icon on the lower left corner and select settings or using the shortcut Ctrl + Windows
   Customizing the theme
   -Open the Command Palette
   -Type Preferences:Color Theme and select it
   -Browse and Select the theme you want
   Changing the Font Size
   -Open the Settings UI.
   -In the search bar,type font size
   -Under Editor:Font size,adjust the font size as needed
   Customizing Keybindings
   -Open the Keybindings UI by clicking on the gear icon in the lower left corner and selecting Keyboard Shortcuts
   -In the Keybindings UI search for the command you want to customize
   -Click the pencil icon next to the command
   -Press the keys you want to assign to this command and press Enter
   For example;Changing the keybinding for the opening terminal
   -Open the Keybinding UI
   -Search for workbench.action.terminal.toggleTerminal
   -Click the pencil icon next to it.
   -Press your desired key combination(e.g.Ctrl + T) then press Enter

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   Key debugging features in VS Code include;
   -Integrated Debugger
   -Debug Console
   -Debugging Extensions for various programming languages
   -Breakpoints
   -Variable Inspection
   -Watch Expressions
   -Call Stack
   Steps to set up and start debugging a simple program
   -install VS Code
   -install the necessary extensions
   -open or create your project by creating or opening a folder and a file
   -create or write a siple program
   -set up Debug Configuration by clicking the debug icon in the activity bar on the left side of the window
   -set breaking points by clicking in the gutter next to the line numbers where you want to set breakpoints.Break points are marked using a red dot.
   -start debugging by pressing F5 or click the green play button
   -debug your program
   -stop debugging by pressing Shift + F5 or clicking the red square stop button in the debugging tool toolbar
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    -Install Git
    -Open your project on VS Code
    -Initialize a Git repository in the integrated terminal in vs code by selecting terminal>New terminal from the menu,run "git init"
    -Open the source control view by clicking the source control icon in the Activity Bar on the left side it shows the current status of your repository
    -Stage and Commit changes;staging-in the source control view,you will see a list of changed files,click the +icon next to each fileto stage it or click the one at the top to stage all.
    Commit changes by typing a commit message in the input box at the top of the source control view and click the checkmark icon to commit the changes.
    -Configure git user information if you haven't
    -Connect to a remote repository by typing "git remote add origin link of the repository" then push your commited changes by typing "git push -u origin master".

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

