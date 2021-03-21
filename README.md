# aws_focus

Setup code commit 

Create EC2 instance 
	1) Get the instance key eg: demo.pem
	2) Connect to EC2 instance with SSH client 
	3) SSH -I "demo.pem" ec2-user@ec2-22-2123-67-84.compute-1.amazonaws.com

Sudo yum update 
Sudo yum install git 

Create IAM
	1) Create IAM user for codecommit or add user to group 
	2) Give programming and console access, user pwd
	3) Attach Commit policy  (user creds: Access key   
	Secret_key)

CLI commands:
git config --global credential.helper '!aws --profile codecommit credential-helper $@'
git config --global credentials.UserHttpPath true
git config --global --edit
	
	Configuring users to access EC2 instance via ssh: 
mohinim@WIN10PC0QT500 MINGW64 ~/Desktop
$ ssh-keygen -y -f new.pem


To SSH are User in EC2 instance


