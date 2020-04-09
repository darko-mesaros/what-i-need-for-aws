# Workstation Stuff

### Non CLI stuff:
- Visual Studio Code
- AWS Toolkit
- Docker (to an extent) 

### AWS CLI stuff
**aws cli v1**

```
pip3 install awscli --user
```

**aws cli v2**

```
# mac os x
curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
sudo installer -pkg AWSCLIV2.pkg -target /

# linux
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install

# windows (powershell)
wget https://awscli.amazonaws.com/AWSCLIV2.msi
* AWSCLIV2.msi 
```

**aws-shell**

```
# https://github.com/awslabs/aws-shell
pip3 install aws-shell --user
```

**saws**

```
# https://github.com/donnemartin/saws
pip3 install saws --user
```

**AWS Elastic Beanstalk CLI**

```
# mac os x requirements:
# Xcode openssl zlib readline
git clone https://github.com/aws/aws-elastic-beanstalk-cli-setup.git
./aws-elastic-beanstalk-cli-setup/scripts/bundled_installer
```

**ecs CLI**

```
sudo curl -o /usr/local/bin/ecs-cli https://amazon-ecs-cli.s3.amazonaws.com/ecs-cli-darwin-amd64-latest
```


### CloudFormation
**cfn-nag**

```
gem install cfn_nag --user
```

**cfn-lint**

```
pip3 install cfn-lint --user
```

### IaC
**AWS CDK**

```
npm install -g aws-cdk
```

**Terraform**

```
# https://www.terraform.io/downloads.html
brew install terraform
```

### Serverless
**SAM CLI**

```
brew tap aws/tap
brew install aws-sam-cli
```

**serverless**

```
# mac os x
curl -o- -L https://slss.io/install | bash

# windows 
choco install serverless

# npm
npm install -g serverless
```

**sls-dev-tools**

```
npm install -g sls-dev-tools
```


### Misc
**brew**

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

**jq**

```
# brew
brew install jq
# apt
apt install jq
# pacman
pacman -S jq
# choco
chocolatey install jq
```

**ohmyzsh**

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

