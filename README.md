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
  * creates an aws vpc with a public and a private subnet
  * create
