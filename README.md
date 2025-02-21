Directions on using Webstorm

First, install Git by downloading it from Git Download and following the installation instructions. Once installed, verify it by opening a terminal and running git --version. You can find a detailed installation guide in the Git Documentation.

Next, install WebStorm by downloading it from WebStorm Download and following the setup instructions.

Once WebStorm is installed, configure Git within the application. Open WebStorm, navigate to File > Settings (Preferences on macOS), then go to Version Control > Git. Ensure that the Path to Git executable is correctly set, then click Test to verify the configuration before clicking OK to save the settings.

To connect WebStorm to GitHub, go to File > Settings > Version Control > GitHub. Click the Add Account button (+), choose Log in via GitHub, and authenticate using your GitHub credentials in the browser. Once logged in, WebStorm will be linked to your GitHub account. For more details, refer to the JetBrains GitHub Integration Guide.

If you want to clone an existing GitHub repository, go to File > New > Project from Version Control in WebStorm. Enter the GitHub repository URL, click Clone, and WebStorm will download and open the project. Additional setup instructions can be found in the WebStorm Git Repository Setup Guide.

To create a new project and initialize Git, open WebStorm and go to File > New > Project. Choose a template and click Create. To enable Git, navigate to VCS > Enable Version Control Integration, select Git, and click OK. If you haven't already created a GitHub repository, follow the steps in the GitHub Quickstart Guide. After that, open the terminal in WebStorm and link your local repository to GitHub by running the following commands:

git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin master
To commit and push changes to GitHub, press Ctrl + K to open the Commit window. Select the files to commit, add a message, and click Commit. Once committed, push the changes by navigating to VCS > Git > Push or pressing Ctrl + Shift + K.

https://www.jetbrains.com/webstorm/download/#section=windows
https://git-scm.com/downloads
https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html
