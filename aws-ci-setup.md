**process of setup aws ci**
1) Open instance in the platform
2) Connect to the Instances
3) Use the following commands for installing the Jenkins:
*sudo wget -O /etc/yum.repos.d/jenkins.repo \
*   https://pkg.jenkins.io/redhat-stable/jenkins.repo
*sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
*sudo yum upgrade
# Add required dependencies for the jenkins package
*sudo yum install fontconfig java-17-openjdk
*sudo yum install jenkins
*sudo systemctl daemon-reload.
4) run This Command in your Instances:

To start the Jenkkins use Following commands:

*sudo systemctl enable jenkins
*sudo systemctl start jenkins
*sudo systemctl status jenkins

5) Run The Command to start and check the instances
6) Change security Inbounds Allow the code 8080 for the accesing of jenkins
7) Use your ip adress with 8080 to open jenkins
8) create your own jenkin profile using your details.
 finally jenkins is setuped in your instances






