# Starting React.JS project on VS Code with Git
The purpose of this repository is to keep a living document on how to start a React.js project on VS Code 
with Git to help with version control.

## Steps:
1.  Ensure that VS Code, Git and Node.JS are installed on computer. Also ensure that React Developer 
Tools extension is added to and activated in your browser.
2.  In VS Code Extensions, check that ES7 React/Redux/GraphGL/React-Native is installed. Also check that 
Live Server, ESLint, JavaScript (ES6) Code snippets extensions are installed.
3.  In VS Code terminal, go to a directory (where you want to keep your project folders). 
4.  Type `npx create-react-app {your project name}` to create a boilerplate react.js project.
5.  After the above command has completed execution, use VS Code to open the newly created project folder. 
6.  In VS Code terminal, go into the new project folder, type `npm start` and you should see your 
computer's default browser opening a new tab to display the boilerplate React.JS web page.
7.  You can delete the unnecessary boilerplate files within the src sub-folder and start coding for your 
project. I have included the barebone program files in [src sub-folder](./src).

## Working with Git
1.  Check that .git is auto-created in the project folder by VS Code. If .git is not found then type in terminal 
(within the project folder) "git init" to initialize git for the project. Alternatively, ensure that git 
is activated within VS Code.
