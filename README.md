# ansible-dev-node

## Setting up local workstation 

python3.9 -m venv ~/.venv/ansible-dev
source ~/.venv/ansible-dev/bin/activate
pip install --upgrade pip
pip3 install ansible==7.1.0
pip3 install ansible-core==2.14.2
pip3 install ansible-lint

To use the vmware community collection install the SDK
pip install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python.git