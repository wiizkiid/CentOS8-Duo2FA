# CentOS8-Duo2FA

www.networkwizkid.com

Thank you for downloading my script. Please read this document before using the script.

This script will configure Duo 2FA for SSH access to CentOS 8 servers.

Disclaimer: The script contained within this folder has been created and tested on CentOS 8 x64 architecture. However, I will not be held liable for any unforseen changes that the system encounters. By using this script you are accepting full responsibility for any system changes caused by this script.

Instructions:

Add the script named centos8_duo_2fa.sh to the root users /home folder with file name 'centos8_duo_2fa.sh' ii. You will also need to make sure that you can execute the script by issuing the following command: chmod +x centos8_duo_2fa.sh

Create the following directory: mkdir /etc/duo

Obtain your ikey, skey and API hostname from the Duo Admin Panel and create the following file before saving:

nano /etc/duo/duovars.txt

ikey= skey= host=

Run the script from /home. Command: ./centos8_duo_2fa.sh

Once complete, test Duo 2FA
