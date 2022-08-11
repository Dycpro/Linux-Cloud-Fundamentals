# Lab 3: Manage Packages and Services on a Linux VM (Azure or AWS)


1. Create a Linux VM
2. Install the Apache Web Server
3. Start the service status via command line
4. Investigate the service status via command line
5. Stop the service


Challenge: Create a boostrapping script that will install and start this service on new EC2 VMs

Notes:

Install and Configure Apache (Ubuntu)

https://ubuntu.com/tutorials/install-and-configure-apache#1-overview
How to install Apache on RHEL 8 / CentOS 8 Linux

https://linuxconfig.org/installing-apache-on-linux-redhat-8
How to use cloud-init to customize a Linux virtual machine in Azure on first boot

https://docs.microsoft.com/en-us/azure/virtual-machines/linux/tutorial-automate-vm-deployment
Create bootstrap actions to install additional software

https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-bootstrap.html

I created and started my Instance with the CLI using the images of Amazon Linux and choosed the one under my present free subscription,also choosed an Instance type of t2.micro,one of the smallest and also on my current free subscription then i went ahead to intsall an Apache Web server,aftrer connecting to the instance and upadating new packages on it.I was able to start the service status via command line,Investigate the service status via command line it gave me inforamtions about what is going on in the system activities that has taken place in that last few minutes,i was able to stop the service successfully via the command line.I created a bootsrap script to serve this service with the heading tag of "hello world"with time i will get better with this