# mod-27-badbank-3-tiered

# Description
This exercise is part of the MITxPro Full Stack Development with MERN course (Module 27). It implements a simple three-tiered banking application

# Installation Guidelines
To run this application you must follow these steps:
1. Clone the repository on your machine
    a. Open the GitHub repository page in your web browser.
    b. Click on the green "Code" button located on the right side of the page.
    c. In the dropdown menu that appears, make sure "HTTPS" is selected.
    d. Copy the URL displayed: https://github.com/codefred77/mod-27-badbank-3-tiered.git
    e. Open a terminal or command prompt on your local machine.
    f. Navigate to the directory where you want to clone the repository. You can use the cd command to change directories.
    g. Once you are in the desired directory, use the git clone: $ git clone https://github.com/codefred77/mod-27-badbank-3-tiered.git
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

