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

```shell
dnf install -y docker
systemctl enable --now docker
usermod -aG docker ec2-user
usermod -aG docker root
chmod 666 /var/run/docker.sock
```

https://limgyeol.notion.site/Diary-268537305262804cb89ad857a3619b31?source=copy_link