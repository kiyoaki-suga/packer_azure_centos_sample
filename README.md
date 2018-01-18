# packer_azure_centos_sample
Packer and Ansible will make Azure CentOS Golden Image (managed disk).

# How to make your image
1. cd builder
2. packer build -var-file=variables.json packer.json
