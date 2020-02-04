## OTUS-Linux-Lesson 1
#1. Vagrantfile
After installing Vagrant and Virtualbox virtual machine can be started with:
```
vagrant init -m zerkalo7/centos-7-5
vagrant up
```

Uploading Vagrantfile and readme.md to Git:
```
git init .
git add Vagrantfile
git add readme.md
git commit -m "Initial commit"
git remote add origin https://github.com/zerkalo7/lesson1.git
git push -u origin master
```
