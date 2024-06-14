# How to install nodejs and npm
```
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

# download and install Node.js (you may need to restart the terminal)
nvm install 20

# verifies the right Node.js version is in the environment
node -v # should print `v20.14.0`

# verifies the right NPM version is in the environment
npm -v # should print `10.7.0`
```



### Install & Update Script

To install or update nvm, you should run the install script. To do that, you may either download and run the script manually, or use the following cURL or Wget command:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
or
```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
To verify
```
command -v nvm
```





Usage

To download, compile, and install the latest release of node, do this:
```
nvm install node # "node" is an alias for the latest version
```
To install a specific version of node:
```
nvm install 14.7.0 # or 16.3.0, 12.22.1, etc
```
To install npm
```
nvm install-latest-npm
```
Reference:
1. <https://github.com/nvm-sh/nvm?tab=readme-ov-file#usage>

