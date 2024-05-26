# Shell Command Repository

Welcome to the Shell Command Repository! This repository contains a collection of useful shell commands and scripts for various purposes.


### Add the Key to SSH Agent

```bash
ssh-add /path/to/Test_Server_keyreset_16th_April23.pem
```
### Verify Key Addition

```bash
ssh-add -l
```

### ssh access server

```bash
ssh -t demo_user@example.com -p 22 -i ~/.ssh/demo_private_key.pem -o StrictHostKeyChecking=no
```

### scp download file from remote

```bash
scp -i ~/.ssh/demo_private_key.pem -P 22 demo_user@example.com:/home/demo_user/source_file.tar.gz /home/local_user/destination_directory
```
