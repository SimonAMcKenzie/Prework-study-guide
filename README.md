# Prework Study Guide Webpage
## A study guide for course prework

To understand on a basic level how to configure and setup, develop, and deploy a web page from scratch
I learned and implemented a web app development process including:
- VS code basics
- Using GitBash
- Using GitHub
- web app coding principles and fundemantals
- debugging Visual Studio Code
- web app development project management basics

Creating this web app means there is a place to record what has been learned on the Front End Web App Developer bootcamp. During the pre-work I learned:
- How to cultivate a developer mindset to see failure as an opportunity to learn something new and grow as a developer
- How to apply agile methodology to web development to keep track of project work
- How to setup a repository for a webapp so I have a place to keep a track of what is being built
- The importance of an SSH key to ensure secure, encrypted communication and authentication between servers, services, and developers, facilitating safe code deployment and remote server access.
- How to use gitbash to execute Git commands, manage source code, and use version control
- How to setup and use GitHub to host, share, and collaborate on code repositories, and use version control.
- How to setup and use the coding environment Visual Studio Code to develop a web apapp, including adding an extention to view my project in my web browser
- How to write and check code for a single page web app including HTML, CSS, and Javascript
- Where to go to find useful information about web dev including Mozila.org


## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Follow these steps to set up your development environment:

Prerequisites
Install Git & Git Bash:
Download and install from Git's official website.

Install Visual Studio Code (VS Code):
Download and install from VS Code's official website.

Git Setup
Configure Git:

a. Open Git Bash.

b. Set your Git username:

bash
Copy code
git config --global user.name "YourUsername"
c. Set your Git email:

bash
Copy code
git config --global user.email "youremail@example.com"
Set Up SSH for GitHub (Recommended):

a. In Git Bash, check for existing SSH keys:

bash
Copy code
ls -al ~/.ssh
b. If there are no SSH key files, generate a new one:

bash
Copy code
ssh-keygen -t ed25519 -C "youremail@example.com"
Press Enter to accept default locations.

c. Start the ssh-agent:

bash
Copy code
eval "$(ssh-agent -s)"
d. Add the SSH key:

bash
Copy code
ssh-add ~/.ssh/id_ed25519
e. Display and copy the SSH key:

bash
Copy code
cat ~/.ssh/id_ed25519.pub
f. On GitHub, go to Settings > SSH and GPG keys > New SSH key. Paste your key and save.

Visual Studio Code Setup
Open VS Code.

Install Recommended Extensions:

a. Search for and install "Live Server" for live reloading of HTML/CSS changes.

b. Install "Prettier" for code formatting.

c. Depending on your project's needs, consider other extensions like "ESLint" for linting JavaScript code.

Starting a Project
Clone an Existing Repository:

If you have a GitHub project:

a. Open Git Bash.

b. Navigate to your desired directory.

c. Clone the repository:

bash
Copy code
git clone git@github.com:YourUsername/YourRepositoryName.git
Or, Start a New Project:

a. In VS Code, go to "File" > "Open Folder" and choose a directory for your project.

b. In the terminal (Terminal > New Terminal), initialize a Git repository:

bash
Copy code
git init
c. Start adding your HTML, CSS, and JavaScript files and build your project.

## Usage

The web app has been designed to give students doing their prework study a place to summarise and showcase what they have learned at each milestone. See my screenshot below:

![Screenshot of web app project](prework-study-guide/assets/images/my_webapp_screenshot_24092023.png)

## Credits

Developed by Simon McKenzie

Image bowtie-cat.jpg was provided by edX Bootcamp 

Training material including links to resources provided by edX Bootcamp


## License

MIT License

Copyright (c) 2023 Simon Mckenzie

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---
