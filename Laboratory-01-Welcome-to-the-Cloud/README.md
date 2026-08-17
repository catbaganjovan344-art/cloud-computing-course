# Laboratory 01 – Welcome to the Cloud

## Mission Overview

This mission introduces the fundamentals of cloud computing through hands-on practice in a cloud-based Linux environment using KillerCoda. The activity focuses on accessing a Linux playground, creating a user account, gathering system information, organizing files and directories, and documenting the work using GitHub.

## Objectives

- Access and use a cloud-based Linux environment through KillerCoda.
- Create and manage a Linux user account.
- Navigate the Linux file system using terminal commands.
- Gather basic system information.
- Create and organize directories and Markdown files.
- Build and maintain a GitHub portfolio repository.
- Document laboratory activities and evidence using Markdown.

## Activities Performed

1. Accessed the Ubuntu Linux environment through KillerCoda.
2. Created the Linux user `jcutebagan` and provided sudo access.
3. Verified the username, working directory, and hostname.
4. Gathered information about the operating system, kernel, CPU, memory, and disk space.
5. Created the required laboratory directory structure.
6. Created the `about-me.md` file.
7. Created the GitHub repository `CCM101-jcutebagan`.
8. Added the required laboratory documentation files to the repository.
9. Prepared screenshots as evidence of the completed activities.

## Linux Commands Used

```bash
sudo adduser jcutebagan
sudo usermod -aG sudo jcutebagan
su - jcutebagan
whoami
pwd
hostname
cat /etc/os-release
uname -r
lscpu
free -h
df -h
mkdir -p
find
cat
