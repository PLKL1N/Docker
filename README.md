# Docker
---
## Install docker
### Amazon Linux 2
```shell
yum install -y docker
systemctl enable --now docker
usermod -aG docker ec2-user
usermod -aG docker root
chmod 666 /var/run/docker.sock
```

### Amazon Linux Linux 2023
'''shell
dnf install -y docker
systemctl enable --now docker
usermod -aG docker ec2-user
usermod -aG docker root
chmod 666 /var/run/docker.sock
'''
