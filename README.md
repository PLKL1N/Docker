# Docker
---
## Install docker

### Amazon Linux 2

```
yum install -y docker
systemctl enable --now docker
usermod -aG docker ec2-user
usermod -aG docker root
chmod 666 /var/run/docker.sock  '\'''
