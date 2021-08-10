# Create AMI with packer
In this repo you will find packer template to build an AWS image witn Nginx installed. 

## AMI details:
* OS: Ubuntu-xenial-16.04-amd64
* Nginx installed as a service which is enabled


## Instructions:
* Install [Packer](https://learn.hashicorp.com/tutorials/packer/get-started-install-cli) 
* Create new directory: ```mkdir packer_nginx```
* Navigate to it: ```cd packer_nginx```
* Clone the repo here: ```git clone https://github.com/InnaHristova/packer_nginx.git```
* Build the image with the following command: ```packer build nginx.pkr.hcl```

*For more information, you may visit https://learn.hashicorp.com/packer*
