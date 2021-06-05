# Starting a React.JS project on VS Code with Git

The purpose of this repository is to keep a living document on how to start a React.js project on VS Code
with Git to help with version control.

## Steps:

1.  Ensure that VS Code, Git and Node.JS are installed on computer. Also ensure that React Developer
    Tools extension is added to and activated in your browser.
2.  (Optional) In VS Code Extensions, check that ES7 React/Redux/GraphGL/React-Native is installed. Also check that
    Live Server, ESLint, JavaScript (ES6) Code snippets extensions are installed.
3.  In VS Code terminal, go to a directory (where you want to keep your project folders).
4.  Type `npx create-react-app {your project name}` to create a boilerplate react.js project.
5.  After the above command has completed execution, use VS Code to open the newly created project folder.
6.  In VS Code terminal, go into the new project folder, type `npm start` and you should see your
    computer's default browser opening a new tab to display the boilerplate React.JS web page.
7.  You can delete the unnecessary boilerplate files within the src sub-folder and start coding for your
    project. I have included the barebone program files in [src sub-folder](./src).

## Working with Git

1.  Check that .git is auto-created in the project folder by VS Code (view in File Explorer).
    If .git is not found, you can initialize git for the project in 2 ways:
    a. To get VS Code to automatically initialize Git in all projects, enable Git in VS Code settings. For VS Code 2019 and above, this should already be done (unless the user changed it). To enable Git in VS Code: Go to File > Preferences > Settings. Type "Git: Enabled" in the search bar. Make sure that the box is ticked.
    b. If you don't want to automatically initialize Git in all projects, and only for one project, do the following: Type in terminal (within the project folder) `git --version` to check if Git is installed. If there is an output "git version ...", it's already installed. If not, [download Git](https://git-scm.com/downloads/).
    Next, update Git config with name and email (if not done before) by typing `git config --global user.name "Your Name"`.
