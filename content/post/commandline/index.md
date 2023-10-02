---
title: Useful Linux Command Line Tools
subtitle: This page will be updated over time to include useful tips for working with Linux from a terminal.

# Summary for listings and search engines
summary: This page will be updated over time to include useful tips for working with Linux from a terminal.

# Link this post with a project
projects: []

# Date published
date: '2023-10-01T00:00:00Z'
# YYYY-DD-M
# Date updated
lastmod: '2023-10-02T00:00:00Z'

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - Isaiah Jones

tags:
  - Isaiah Jones

categories:
  - Demo
---

## List of Useful Commands

This page will serve as a living listicule of useful linux commands that I come across and want to remember over time.

`cat`: displays the contents of a file

`less`: displays the contents of a file in a searchable using `/` 

`scp ijones00@server:/home/usr/filepath/file .`: copies a remote file to the present working directory.

`command_1 | command_2 | ...`: the pipe command allows the stdout of a command to be connected to the stdin of another command

`ls -l`: lists the files located in the present working directory and gives permission and file size information

`lsof -i:22`: list open file - lists all of the processes using port 22

`kill -9 1212`: kills the process with PID 1212 with the signal number 9

`find *.jpg`: searches in the current directory all files that match the given regex expression

`rm -rf`: recursively remove all files at the given address

`netstat -an`: show a list of active TCP and UDP connections while preventing netstat from determining host names for foreign IP addresses

`grep -r "string" *`: searches for the string name recursively in the current directory

`ps -ef`: displays information about running processes and -ef displays information in a full format

`history > history.txt`: receives the history of the commandline and sends it into a new file named history.txt

``export PATH=`pwd`:$PATH``: adds the current directory to the PATH environment variable


`ssh ijones00@server.com`: starts a ssh connection
- `-X`: headless mode
- `-N`: tells ssh not to execute any commands on the remote host
- `-f`: run ssh in the background
- `-L 8892:localhost:8869`: forwards port 8892 of my local machine to port 8869 of the remote host

## VI quick tips
`vi file.txt`: start a vim instance with given file name

`i`: enables editing mode

`esc + wq`: saves and quits
