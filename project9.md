#TOOLING WEBSITE DEPLOYMENT WITH JENKINS

*Create an AWS EC2 server based on Ubuntu Server 20.04 LTS and name it "Jenkins"

![instance](./images/instance.PNG)

96-`sudo apt update`

`sudo apt install default-jdk-headless`

`wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`

`sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
    /etc/apt/sources.list.d/jenkins.list'`


`sudo apt update`

`sudo apt-get install jenkins`

`sudo systemctl status jenkins`

![JENKINS](./IMAGES/jenkins.PNG)

http://<Jenkins-Server-Public-IP-Address-or-Public-DNS-Name>:8080

`sudo cat /var/lib/jenkins/secrets/initialAdminPassword`


![jen](./images/jenkins%20log%20in.PNG)

![ready](./images/ready.PNG)

![log](./images/log%20in.PNG)

![build2](./images/build2.PNG)

![build](./images/buildimage.PNG)


`ls /var/lib/jenkins/jobs/tooling_github/builds/<build_number>/archive/`

![ARCHIVE](./images/artifacts.PNG)

![success](./images/success.PNG)

![build](./images/build.PNG)

![end](./images/project9%20end.PNG)


























