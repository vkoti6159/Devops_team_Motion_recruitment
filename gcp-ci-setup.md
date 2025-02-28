**create  a Jenkins in the gcp
Open Virtual Machine(VM) in the platform
Connect to the Virtual Machine(VM)
Use the following commands for installing the Jenkins:
sudo wget -O /etc/yum.repos.d/jenkins.repo \
https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
sudo yum upgrade
Add required dependencies for the jenkins package
sudo yum install fontconfig java-17-openjdk
sudo yum install jenkins
sudo systemctl daemon-reload.
run This Command in your Instances:
To start the Jenkkins use Following commands:

sudo systemctl enable jenkins
sudo systemctl start jenkins
sudo systemctl status jenkins
Run The Command to start and check the Virtual Machine(VM)
Change Firewalls Rules Allow the  code 8080 for the accesing of jenkins
Use your  External ip adress with 8080 to open jenkins
create your own jenkin profile using your details. 
finally jenkins is setuped in your Virtual Machine(VM)
