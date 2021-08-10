# Create AMI with packer
In this repo you will find packer template to build an AWS image witn Nginx installed. 

## AMI details:
* OS: Ubuntu-xenial-16.04-amd64
* Nginx installed as a service which is enaled


## Instructions:
* Install [Packer](https://learn.hashicorp.com/tutorials/packer/get-started-install-cli) 
* Build the image with the following command: __packer build nginx.pkr.hcl__

*For more information, you may visit https://learn.hashicorp.com/packer*
