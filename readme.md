# Network Ad Blocking Data/Scripts

## Ex. File Usage

| File | Purpose |
| ---- | ------- |
| block_service.json | List of all the services that need ad blocking, and their respective AD domains to be blocked |

## Installation

Note: It is recommended you use a python virtual environment to run the software.

### Installing & Using Python Virtual Environments

```bash
# Install python virtaul environment wrapper
pip install virtualenv 

# Enter the directory where you want to create the virtual environment
# Create a virtual environment
virtualenv ad_blocking
cd ad_blocking/bin
sudo chmod +x activate
source ./activate