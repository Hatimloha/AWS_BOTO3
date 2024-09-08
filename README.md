# Boto3 installation in ubuntu
## Prerequest

### command to install AWS CLI on Ubuntu is:
```shell
sudo apt-get update
sudo apt-get install awscli -y
```
### Install AWS CLI v2:
```shell
# Download the AWS CLI v2 package:
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

# Unzip the package:
Unzip the package:

# Run the installer:
sudo ./aws/install

# Verify the installation:
aws --version
```

## Install Python on Ubuntu

```shell
# Update the package index:
sudo apt-get update

# Install Python:
sudo apt-get install python3 -y

# Verify the installation:
python3 --version

```

## Install pip for Python 3:
```shell
# Python3
sudo apt-get install python3-pip -y

# Verify the installation:
python3 --version
```

```shell
# Install python3-venv if you don't have it
sudo apt-get install python3-venv -y

# Create a new virtual environment
python3 -m venv myenv

# Activate the virtual environment
source myenv/bin/activate

# Install Boto3 within the virtual environment
pip install boto3

```
python ec2.py
```shell

```

```shell
deactivate
```




