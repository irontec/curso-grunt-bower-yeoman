## Installing nodejs

```bash
# Install nvm - Node Version Manager
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.7.0/install.sh | sh

# Load nvm 
source ~/.nvm/nvm.sh

# Install nodejs vr 0.10
nvm install 0.10

# Load nodejs vr 0.10
nvm use 0.10

# Set version 0.10 as default
nvm alias default 0.10

# Install packages as global
npm -g install yo bower grunt-cli generator-webapp generator-angular
```
