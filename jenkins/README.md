# Jenkins Installations

1. Clone the repository
```
git clone https://github.com/princebirring/DevOps.git
```
2. Change the directory
```
cd DevOps/jenkins
```
3. Change the Permission of the jenkins.sh shell script.
```
chmod u+x jenkins.sh
```
4. Run the jenkins-docker shell script
```
./jenkins.sh
```
5. Jenkins will be running on private-ip:8080(Cloud) or localhost:8080(Local Machine). You require a password to access and create the jenkins admin account. You can get the password by running the following command. 
```
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
```
6. Jenkins Status, Restart, Stop and Start. 
```
sudo service jenkins status
sudo service jenkins restart
sudo service jenkins stop
sudo service jenkins start
```