# mod-27-badbank-3-tiered

# Description
This exercise is part of the MITxPro Full Stack Development with MERN course (Module 27). It implements a simple three-tiered banking application

# Installation Guidelines
To run this application you must follow these steps:
1. Clone the repository on your machine
    o Open the GitHub repository page in your web browser.
    o Click on the green "Code" button located on the right side of the page.
    o In the dropdown menu that appears, make sure "HTTPS" is selected.
    o Copy the URL displayed, which should be something like https://github.com/username/repository.git.
    o Open a terminal or command prompt on your local machine.
    o Navigate to the directory where you want to clone the repository. You can use the cd command to change directories.
    o Once you are in the desired directory, use the git clone
2. Install all modules
    $ cd <cloned_repository_directory>
    $ npm init
    $ npm install
3. Start MongoDB on Docker
    $ docker run -p 27017:27017 --name badbank -d mongo
4. Start the app
    $ node index.js
5. In your browser navigate to localuser:3000


with the following features:
1. Account creation (Name, email, password)
2. Login
3. Deposit
4. Withdrawal
5. List all users

