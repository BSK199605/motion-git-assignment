Open  azure.microsoft.com
Click on "Free Account" or "Start Free
Sign-up process and click start
Enter Personal details as requested
Identity Verification
payment info 
Account activation
Dashboard access

####### Azure VM Crreation######
Login into Azure Portal
Select Create NEW vm
bSIC cONFIG.
cHOOSE UNIQUE NAME.
Choose location
Choose OS

### Steps to deploy Python Script #####
Connect to Azure VM using "ssh username@your-vm-public-ip"
Install Python and Pip using "sudo apt install python3 python3-pip -y"
Transfer Python Script Using SCP (from local machine)
scp -i /path/to/your-key.pem your_script.py username@vm-ip:/home/username/
Run The python script using "python3 your_script.py"
