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
* Navigate to packer_nginx: ```cd packer_nginx```
* Authenticate to AWS:
  ```export AWS_ACCESS_KEY_ID=YOUR_ACCESS_KEY```
  ```export AWS_SECRET_ACCESS_KEY=YOUR_SECRET_KEY```
  ```export AWS_SESSION_TOKEN=YOUR_ACCESS_KEY```
* Initialize packer configuration: ```packer init .```
* Build packer image: ```packer build nginx.pkr.hcl```

*For more information, you may visit https://learn.hashicorp.com/packer*
