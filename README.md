# Container in EC2 via Amazon Linux 2

### update machine
```bash
sudo yum update -y
```
### Install Docker toolkits
```bash
sudo yum install docker -y
```
```bash
sudo service docker start
```
```bash
sudo service docker status
```
```bash
sudo usermod -aG docker $USER
exit
ssh . . .
```

### Install Docker Compose
```bash
sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
```
```bash
sudo chmod +x /usr/local/bin/docker-compose
```

### Install Git
```bash
sudo yum install git -y
```
