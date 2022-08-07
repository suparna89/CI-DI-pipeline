# Building-CI-CD-pipeline-to-deploy-a-new-version-of-Application-Jenkins-

# install Java 
sudo apt update 
sudo apt install default-jdk 

# install the Jenkins stable version. 
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add - 
sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list' 
sudo apt-get update 
sudo apt-get install jenkins 

# Check whether Jenkins is now active or not, run the below command. It will show status Active if the Jenkins is appropriately installed. 
sudo systemctl status jenkins 

# Find the password from the command  
sudo cat /var/lib/jenkins/secrets/initialAdminPassword 

# Press Install Suggested Plugins - >Create First admin user 

# Create 3 Instance in EC2 in AWS

# Install Maven & Git 
sudo apt-get install -y git maven

# Install TOMCAT In Production Server 
sudo apt-get update 

# Install tomcat8 
sudo apt-get install -y tomcat8 

# Install one more package 
sudo apt-get install -y tomcat8-admin 

# connection
java -jar jenkins.war 

