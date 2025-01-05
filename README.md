# Installing Homebrew
1. $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. $ brew install wget

# Setting up AWS CLI
1. $ curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
2. $ sudo installer -pkg AWSCLIV2.pkg -target /

# Verifying AWS CLI Installation:
3. $ which aws
4. $ aws --version


# Setting up Terraform
1. $ brew tap hashicorp/tap
2. $ brew install hashicorp/tap/terraform
