## emilys-aptitude (MAC Instructions)

### Pre-reqs - software
iterm: https://iterm2.com/

vscode: https://code.visualstudio.com/Download

Homebrew: this is installed using iterm. Homebrew is the defauly package manager for MAC.
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
Node & NPM (NPM is part of the node library)
```
brew install node
```

### Pre-reqs - git
Create a git account, otherwise you won't be able to make commits to this code base. 

Basic git commands
> git clone (this takes a git repo and mirrors it to your local computer)

> git commit (this is used to save your local changes and prepare to push to the server)

> git push (this pushes your local changes to the git site )

### Download Project 

* Open Iterm
* cd ~/Documents (~ is a shortcut for your home directory)
* mkdir git
* cd git
* clone repo

```
git clone https://github.com/rachau87/emilys-aptitude.git
```

* cd emilys-aptitude
* npm install (this installs any libraries that your computer doesn't have)

### Open Project in vscode 
* Open vscode
* File --> Open
* Go to Documents/git/ and click the folder emilys-aptitude
* Open the src folder
* Click on pitter-patter.ts file

### Test your work 
Open Iterm, make sure you are in the emilys-aptitude folder

Run:
```
npx ts-node src/pitter-patter.ts
```

Results should be in Iterm

