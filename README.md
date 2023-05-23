# mod-27-badbank-3-tiered

# Description
This exercise is part of the MITxPro Full Stack Development with MERN course (Module 27). It implements a simple three-tiered banking application

# Installation Guidelines
To run this application you must follow these steps:
1. Clone the repository on your machine (see below for instructions)

2. Install all modules
    $ cd <cloned_repository_directory>
    $ npm init
    $ npm install
3. Start MongoDB on Docker
    $ docker run -p 27017:27017 --name badbank -d mongo
5. Start the app
    $ node index.js
7. In your browser navigate to localuser:3000

# Cloning the repository
1. Open the GitHub repository page in your web browser.
2. Click on the green "Code" button located on the right side of the page.
3. In the dropdown menu that appears, make sure "HTTPS" is selected.
4. Copy the URL displayed: https://github.com/codefred77/mod-27-badbank-3-tiered.git
5. Open a terminal or command prompt on your local machine.Navigate to the directory where you want to clone the repository. 
6. You can use the cd command to change directories.
7. Once you are in the desired directory, use the git clone:
    $ git clone https://github.com/codefred77/mod-27-badbank-3-tiered.git
9. Git will start cloning the repository to your local machine. It will create a new directory with the same name as the repository.
10. Once the cloning process is complete, you will have a local copy of the GitHub repository in the specified directory.

# Technology used
Javascript, React, Node.js, Express, MongoDB, Docker

# Features:
Currently the app includes the following features:
1. Account creation (Name, email, password)
2. Login - with user authentication
3. Deposit - checks for valid amounts
4. Withdrawal - checks for valid amounts
5. List all users

Would like to add:
1. Google authentication
2. Transfers between customers

# MIT License
Copyright (c) 2022 codefred77

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
