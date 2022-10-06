                    Solomon Hykes Lauched Docker in 2013. At That time he said "The Entire OS will be 
Launced in less than 2 second ". Wonderful! Docker is too much Powerful.


Docker is a tool on which we can run multiple OS at a time with tremendous speed.

--> Docker is a software 
--> To run this Docker we need OS 
--> That OS should be LINUX
--> Then we have to run linux on AWS Cloud 

1.After launching instance on AWS in ec2 type
2.we have log in root user by running command "sudo su - root"
3.to check user run command "whoami"
4.to check software intalled or not "rpm -q docker-ce"
5.In most of the OS we have to setup the command "yum"  for installing but in cloud OS they have 
  In-Built "yum" command.
6.then we have to install docker by "yum install docker" command
7.to check status of any software. is it active or inactive Run "systemctl status docker"
8.To start the software if it is inactive "systemctl start docker"
9.if you want to see how many OS running on the software there is a command "docker ps"
10.To install any OS we need OS setup or OS Image. So, in container world 
                   OS Image == Container Image
11.There is a registry where we cna check that the soecific OS is available or not
             "hub.docker.com"
12.we have to desired OS on the website if is there click on the logo and there is command to install 
   that OS image . just copy it and paste it on docker.
13.To add version put a semicolon between OS name and Version name
          eg. "docker pull ubuntu:14.04"
	  it will install ubuntu 14.04 version 
14.To Run OS the last command is
        "docker run -t -i ubuntu:14.04"
15.To check running OS. log into another terminal of base system that is amazon linux instance 
    and then run the command "docker ps".
16.To shutdown the OS command "exit"




That's All for the Day Lets catup up in the next .md
