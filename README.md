## Requirements
- Have your rsa key generated in ~/.ssh
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```
## To access shell
```bash
ssh -i "~/.ssh/id_rsa" ubuntu@{public_ip}
```
