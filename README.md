# Jenkins-Project-todo

## Create AWS EC2 instance

![create instance](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/ba38df30-c24d-40e6-8978-eb9f88be501b)


## Install Java
### Update your system
sudo apt update

![update linux](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/0c35af72-7bf7-4ab8-ada2-988e415864b5)


sudo apt install openjdk-11-jre

### Validate Installation
java -version

## Install Jenkins
curl -fsSL https://pkg.jenkins.io/debian/jenkins.io.key | sudo tee \   /usr/share/keyrings/jenkins-keyring.asc > /dev/null 

echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \   https://pkg.jenkins.io/debian binary/ | sudo tee \   /etc/apt/sources.list.d/jenkins.list > /dev/null

sudo apt-get update 

img![installing jenkins](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/d28a08c0-4462-4b1a-a909-35700ac8c355)


sudo apt-get install jenkins

## Start jenkins

sudo systemctl enable jenkins

sudo systemctl start jenkins

sudo systemctl status jenkins

## Open port 8080 from AWS Console

### Edit Inboud Rule

![edit inbound rule](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/3a82b48a-71f4-42c7-92e6-b7210d3d7be9)


### Open Login page

![login page](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/5b61b9e7-93b2-4d42-a8d5-da77ed7c6701)

![unlock jenkins](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/c2887b34-4e1d-4677-b307-c3c6cdfb831b)

![create admin user](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/1e6560b5-3d66-4b14-b023-8d8df9068632)


### Set SHH key on GitHub

![set ssh key on git](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/4f6e1223-9686-413f-b36b-c0a65b4fc15b)

### Set Keygens

![set keygen](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/1f341553-5cda-4425-bf9f-570edeea72da)


### Add Credentials in your Jenkins Project

![jenkins-credential](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/64299eb3-0eb2-4b19-99a7-ce830ce8bfbc)



### Edit Source code Management

![source code management](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/17c7c4c5-df87-424e-89f7-c5ff61f362b1)

### Click Build Now check console output

![jenkins console output](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/20f2d9ba-af80-42e5-9027-4b30ff2fd0fc)

### Open port 8000

![open on port 8000](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/d8922c9f-9ba4-4c53-aa2d-2ac2c61f18eb)

### Install Docker

![install docker](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/65f76914-04c3-4f2c-b096-9e876685326e)
  
### create DockerFile 

![create Docketfile ](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/c31d6e6c-372a-4a21-849c-e3ea8f44d83f)

### Edit build Trigger

![edit build trigger](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/283cf88f-129f-4f0f-bd32-8ad6c8568b7d)

### Pipeline running
![pipeline running](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/00a2de69-f2cd-4318-b65a-6fab99750c40)

### Result
![final output](https://github.com/Cloud-Xplorer08/Jenkins-Project-todo/assets/71820244/c1d9897a-8d3a-4c60-888a-ab8f9b4e7eb5)







