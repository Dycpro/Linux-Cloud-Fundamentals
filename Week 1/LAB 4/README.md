# Lab 4: Create and use an SSH public-private key pair for Linux VMs in Azure

Task:
1. Supported SSH key formats
2. Create an SSH key pair
3. Provide an SSH public key when deploying a VM
4. SSH into your VM


Notes:
Quickstart: SSH for Linux VMs

https://docs.microsoft.com/en-us/azure/virtual-machines/linux/mac-create-ssh-keys
Quickstart for Bash in Azure Cloud Shell

https://docs.microsoft.com/en-us/azure/cloud-shell/quickstart
I understood that Azure currently supports SSH protocol 2 (SSH-2) RSA public-private key pairs with a minimum length of 2048 bits. Other key formats such as ED25519 and ECDSA are not supported,i was able to generate an ssh key pair but encounter difficulties with providing key when deploying VM and ssh into VM.i am stil working on this and asking my collegues but time constraints.i will finish up and update my read.me as soon as possible thank you