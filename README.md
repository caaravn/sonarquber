-> **Download and install sonar on Ubuntu**

**java install**
sudo apt update
sudo apt install openjdk-11-jre -y


sudo adduser sonarqube   ---------> adding user
apt install unzip
sudo su - sonarqube      ----------> swiching to sonar user
wget https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-9.4.0.54424.zip
unzip *
ls
chmod -R 755 /home/sonarqube/sonarqube-9.4.0.54424
chown -R sonarqube:sonarqube /home/sonarqube/sonarqube-9.4.0.54424
cd sonarqube-9.4.0.54424/bin/linux-x86-64/
./sonar.sh start
```
