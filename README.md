# How-To-Host
This repository will tell you have to host this password manager.

# Downloading Apps

There are 2 apps you need for this.

VS Code (https://code.visualstudio.com/download)

Node JS (https://nodejs.org/en/download) **Important!** You **Must** add Node JS To the system path for this to work. You can learn that here https://codeforgeek.com/adding-nodejs-to-system-path/

# Downloading Files

There is only one file you need to download here.

Project-root: this is the file with the server interface and the endpoints of the Password manager you can download it here. https://github.com/Self-hosted-Password-Manager/project-root/archive/refs/heads/main.zip
You should extract this and put the project-root file anywhere you can remember


# Starting the web server

To start the password manager you should cd into the directory your project-root file is and then type "cd project-root". Now, you have to type in "node server.js"and go to "loclahost:3000/login.html" (Default login it 2265 but you can change it in the server.js file on line 9)


# Making It More Secure

You can make the password manager secure by hiding the project-root file this is how.

1. Find the project-root file

2. Right click it and press properties

3. Press hidden and apply

4. There will be a pop-up and you should click "Apply changes to this folder only"

5. Done!
