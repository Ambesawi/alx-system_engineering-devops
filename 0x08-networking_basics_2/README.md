# 0x08. Networking basics #1

## Resources

Read or watch:
- [What is localhost](link-to-localhost)
- [What is 0.0.0.0](link-to-0.0.0.0)
- [What is the hosts file](link-to-hosts-file)
- [Netcat examples](link-to-netcat-examples)
- `man` or `help`:
  - [ifconfig](link-to-ifconfig)
  - [telnet](link-to-telnet)
  - [nc](link-to-nc)
  - [cut](link-to-cut)

## Learning Objectives

At the end of this project, you are expected to be able to explain the following topics without the help of Google:

### General

- What is localhost/127.0.0.1
- What is 0.0.0.0
- What is /etc/hosts
- How to display your machine’s active network interfaces

## Copyright - Plagiarism

You are responsible for creating your solutions to the tasks to meet the learning objectives. Avoid plagiarism, and refrain from publishing any content related to this project.

## Requirements

- Allowed editors: vi, vim, emacs
- All files will be interpreted on Ubuntu 20.04 LTS
- All files should end with a new line
- `README.md` file at the root is mandatory
- All Bash script files must be executable
- Bash scripts must pass Shellcheck (version 0.7.0 via apt-get) without any errors
- The first line of all Bash scripts should be `#!/usr/bin/env bash`
- The second line of all Bash scripts should be a comment explaining what is the script doing

## Tasks

### 0. Change your home IP

Write a Bash script that configures an Ubuntu server with the below requirements:

Requirements:
- localhost resolves to 127.0.0.2
- facebook.com resolves to 8.8.8.8.

Example:

```bash
sylvain@ubuntu$ ping localhost
PING localhost (127.0.0.1) 56(84) bytes of data.
# Output truncated for brevity
sylvain@ubuntu$
sylvain@ubuntu$ ping facebook.com
PING facebook.com (157.240.11.35) 56(84) bytes of data.
# Output truncated for brevity
sylvain@ubuntu$
sylvain@ubuntu$ sudo ./0-change_your_home_IP
sylvain@ubuntu$
sylvain@ubuntu$ ping localhost
PING localhost (127.0.0.2) 56(84) bytes of data.
# Output truncated for brevity
sylvain@ubuntu$
sylvain@ubuntu$ ping facebook.com
PING facebook.com (8.8.8.8) 56(84) bytes of data.
# Output truncated for brevity
