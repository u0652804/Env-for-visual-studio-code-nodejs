# Env-for-visual-studio-code-nodejs
 - download and install vscode : https://code.visualstudio.com/
 - download and install node js : https://nodejs.org/en/
 - create first app by vscode
 - run first app by node js use vscode terminal or terminal
 
## create first app by vscode
create your workspace. e.g. D:\VScode_workspace1

open terminal in dir. workspace.

create folder. e.g. hello
 
    mkdir hello
    
open project by vscode
 
    cd hello
    code .
    
 create first app.js in project    
     vscode : explorer -> hello -> new file -> app.js
 
 example code for first app e.g. app.js:
 
    var msg = "Hello World.";
    console.log(msg);
    
 
## run first app by node js use vscode terminal or terminal
execute app.js by node js :
    
    node app.js

## Create React App
Install create-react-app(an officially supported way to create React applications) by running this command in your terminal:
    
    npm install -g create-react-app
    
create a React application named myfirstreact:

    npx create-react-app myfirstreact
    
fix issue : install npm i
    
    npm i
    
move to the myfirstreact directory

    cd myfirstreact
    
execute the React application myfirstreact

    npm start
    
fix issue : npm start 
    
    npm install react-scripts@2.1.8
    npm start
    
## Reference
  https://www.w3schools.com/REACT/default.asp 
  https://stackoverflow.com/questions/57054403/problem-with-npm-start-error-spawn-cmd-enoent
