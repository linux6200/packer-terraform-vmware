# Creating VMware templates with Packer and VMs with Terraform
First create a VMware template with Packer then use Terraform to provision VMs from that template

## Packer templates
Great medium post by [Guillermo Musumeci](https://medium.com/@gmusumeci/how-to-use-packer-to-build-a-windows-server-template-for-vmware-vsphere-3bc0dc9852ed)

### Windows Packer Templates
Here is his [github repo](https://github.com/guillermo-musumeci/packer-vsphere-iso-windows)

### Linux Packer Templates
[Linux Packer templates](https://github.com/guillermo-musumeci/packer-vsphere-iso-linux)

## More instructions
You can find more instructions in /packer-vsphere-iso-windows/README.md

## How to install packer
export PACKER_RELEASE="1.7.2"
wget https://releases.hashicorp.com/packer/${PACKER_RELEASE}/packer_${PACKER_RELEASE}_linux_amd64.zip
unzip packer_${PACKER_RELEASE}_linux_amd64.zip
mv packer /usr/local/bin

