## OTUS-Linux-Lesson 1
# Задание 1 - Обновляем ядро из репозитория, загружаем Vagrantfile на Github  
Собственно все по методичке, поэтому смысла расписывать здесь последовательности действий особенно нет.  
Для запуска тестового запуска устанавливаем Vagrant и Virtualbox и вводим команды.   
```
vagrant init -m zerkalo7/centos-7-5
vagrant up
```

А вот так создаем репозиторий на Github и загружаем туда Vagrantfile и readme.md из терминала  
```
git init .
git add Vagrantfile
git add readme.md
git commit -m "Initial commit"
git remote add origin https://github.com/zerkalo7/lesson1.git
git push -u origin master
```
