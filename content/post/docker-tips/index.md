---
title: What is Docker and how do I use it?
subtitle: Introduction to the docker ecosystem

# Summary for listings and search engines
summary: Introduction to docker, containers, and a walkthrough of the ecosystem

# Link this post with a project
projects: []

# Date published
date: '2023-01-01T00:00:00Z'
# YYYY-DD-M
# Date updated
lastmod: '2023-01-10T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

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

# List of Useful Commands

This page will serve as a living listicule of useful linux commands that I come across and want to remember over time.

`cat`: displays the contents of a file

`less`: displays the contents of a file in a searchable using `/` 

`scp ijones00@server:/home/usr/filepath/file .`: copies a remote file to the present working directory.

`command_1 | command_2 | ...`: the pipe command allows the stdout of a command to be connected to the stdin of another command

`ls -l`: lists the files located in the present working directory and gives permission and file size information

`ssh ijones00@server.com -X`: starts a ssh connection in headless mode

# VI quick tips
`vi file.txt`: start a vim instance with given file name

`i`: enables editing mode

`esc + wq`: saves and quits
