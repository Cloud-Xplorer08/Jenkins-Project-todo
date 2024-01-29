# Jenkins-Project-todo

## Create AWS EC2 instance

![create instance](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/ba38df30-c24d-40e6-8978-eb9f88be501b)


## Install Java
### Update your system
sudo apt update

img

sudo apt install openjdk-11-jre

### Validate Installation
java -version

## Install Jenkins
curl -fsSL https://pkg.jenkins.io/debian/jenkins.io.key | sudo tee \   /usr/share/keyrings/jenkins-keyring.asc > /dev/null 

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \   https://pkg.jenkins.io/debian binary/ | sudo tee \   /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt-get update 

img

sudo apt-get install jenkins

## Start jenkins

sudo systemctl enable jenkins

sudo systemctl start jenkins

sudo systemctl status jenkins

## Open port 8080 from AWS Console

### Edit Inboud Rule

img

### Open Login page

img

img










