# **DevOps Homework**

## **1. Coding**

Please write a small tool which lists all S3 buckets in an AWS account. It is enough that the tool returns the Name and the Creation Time of the buckets. 

*Rules:*

* You are free to use the programming language and the SDK of your choice.
* Installation should not require us to install external tools.
* It’s enough that your program runs only on Linux

## **2. Configuration Management**

* Write an Ansible Playbook which:
  * Creates a user called **Jamie** on a server with only ssh public key authentication enabled
  * Creates */opt/folder1* & */opt/folder2* with only R+W permissions belonging to user **Jamie**
  * Updates the kernel parameter which enables TCP Forwarding
  * Installs *nginx* and updates the configuration. Create a systemd configuration which starts up nginx on failure and system startup/reboot.

* Write a Terraform Resource which:
  * Creates an aws vpc with a public and a private subnet
  * Attaches an internet gateway to the public subnet
  * Creates and attaches a NAT GW to the private subnet
  * Creates and configures the route tables. 
  * Creates a S3 bucket called **devops** which includes a directory called **homeworks** and creates and object in that directory called **test_objcet.txt**. At the end it should look similar to ```s3://devops/homeworks/test_obejct.txt```

## **3. Application Management and Deployment**

* Using the demo project in this repository: 
  * 
