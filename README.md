# How-To-Host
This repository will tell you have to host this password manager.

# Downloading Apps

There are 2 apps you need for this.

VS Code (https://code.visualstudio.com/download)

Node JS (https://nodejs.org/en/download) **Important!** You **Must** add Node JS To the system path for this to work. You can learn that here https://codeforgeek.com/adding-nodejs-to-system-path/

# Downloading Files

There is only one file you need to download here.

Project-root: this is the file with the server interface and the endpoints of the Password manager you can download it here. https://github.com/Self-hosted-Password-Manager/project-root/archive/refs/heads/main.zip
You should extract this and put the project-root file on your desktop. Also, you should make the passwords.json file hidden as the password manager **Will** lose all of its security and it will be the same as writing them down on a note book. (You can do this by right clicking the passwords.json clicking properties and making it hidden)


# Starting the web server

To start the password manager you should cd into the directory your project-root file is and then type "cd project-root". Now, you have to type in "node server.js"and go to "loclahost:3000/login.html" (Default login it 2265 but you can change it in the server.js file on line 9)

