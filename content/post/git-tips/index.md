---
title: Git 101
subtitle: All of the useful git commands I use!

# Summary for listings and search engines
summary: This page will be updated over time to include useful tips for working with Linux from a terminal.

# Link this post with a project
projects: []

# Date published
date: '2023-01-01T00:00:00Z'
# YYYY-DD-M
# Date updated
lastmod: '2023-30-08T00:00:00Z'

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

`git clone https://github.com/iljones00/personal-site.git`: clones repo to your current directory

`git status`: allows us to see which file we modified

`git add filename.txt`: add these changes to the stage

`git rm --cached hwk10.lisp`: removes file from the cache

`git commit -m "message"`: adds a commit with the given comment 

`git push`: updates the master repo to match your commits

`git pull`: get changes from remote

`git checkout -b newBranchName`: creates a new branch

`git checkout branchName`: puts you on that branch

`git merge branchName`: merges the branch to your current branch

`git pull origin branchName`: pulls from the given branchs

`git stash`: stores local changes into the stash

