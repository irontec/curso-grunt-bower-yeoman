## Installing Ruby

```bash
# Install rvm - Ruby Version Manager
curl -L https://get.rvm.io | bash -s stable

# Load rvm
source ~/.rvm/scripts/rvm

# List available ruby versions
rvm list

# Install a ruby version and set it as default
rvm install 2.0.0-p353

# Load ruby version 2.0.0-p353 and set as default
rvm use 2.0.0-p353 --default

# Install packages
gem install --pre sass compass

```