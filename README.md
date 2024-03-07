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

## Installation for gitdir
Clone the repository and give execution permissions to the script:
```
git clone [URL of your repository]
chmod +x gitdir
```
For global usage you can install it 
### Ubuntu, CentOS, macOS
in /usr/local/bin/gitdir
### Usage
Inside a folder to iterate all direct child folders
```
gitdir
```
### Features
Iterate all direct child folders, check if is a git repository and perform:

- git pull
- git status
- prompt for commit if necessary
- prompt for push


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

## Installation for laraclear
Performs clear operations in Laravel projects local installed
```
git clone [URL of your repository]
chmod +x laraclear
```
For global usage you can install it 
### Ubuntu, CentOS, macOS
in /usr/local/bin/laraclear
### Usage
```
laraclear
```
### Features
Performs clear operations in Laravel projects:
php artisan view:clear
sudo php artisan cache:clear
php artisan config:clear
php artisan route:clear
php artisan queue:clear
php artisan event:clear
php artisan debugbar:clear
php artisan optimize:clear

## Contributions
Contributions are welcome. 
To contribute, fork the project, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Author
Luís Pinto
luis.pinto@instantia.pt
