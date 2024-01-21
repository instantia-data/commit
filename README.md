# simple-git - Git Automation Scripts

## Description
These scripts simplifies Git commit processes like commit or reset by fetch-all.

## Prerequisites
- Bash
- Git

## Installation for commit
Clone the repository and give execution permissions to the script:
```
git clone [URL of your repository]
chmod +x commit
```
For global usage you can install it 
### Ubuntu, CentOS, macOS
in /usr/local/bin/commit
### Usage
```
commit "Your commit message here"
```
The script will prompt if you want to push the changes to repository
### Features
Adds a timestamp to the commit message.

Simplifies the commit process with a single command:

git pull

git add .

git commit -m "the changes"

and prompt for push

## Installation for reset-git
Get the git status and ask for a hard reset:
```
git clone [URL of your repository]
chmod +x reset-git
```
For global usage you can install it 
### Ubuntu, CentOS, macOS
in /usr/local/bin/reset-git
### Usage
```
reset-git <branch-name>
```
The script will prompt if you want to reset the repository to the last commit

### Features
git status

git fetch --all

git reset --hard origin/<branch-name>

## Contributions
Contributions are welcome. 
To contribute, fork the project, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Author
Luís Pinto
luis.pinto@instantia.pt
