## Install Jenkins on Ubuntu 20.04

- Install Java on Ubuntu 20.04

```
sudo apt install openjdk-11-jre openjdk-11-jdk
```

- Install Jenkins on Ubuntu 20.04

```
sudo apt install apt-transport-https
```

```
wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
```

```
sudo apt-add-repository "deb https://pkg.jenkins.io/debian-stable binary"
```

```
sudo apt update
```

```
sudo apt install jenkins
```

