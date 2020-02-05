## OTUS-Linux-Lesson 1
# Задание 1 - Обновляем ядро из репозитория, загружаем Vagrantfile на Github    
Собственно, все по методичке.    
Для тестового запуска устанавливаем Vagrant и Virtualbox и вводим команды.  
```
vagrant init -m zerkalo7/centos-7-5
vagrant up
```

Загружаем Vagrantfile и readme.md на Github  
```
git init .
git add Vagrantfile
git add readme.md
git commit -m "Initial commit"
git remote add origin https://github.com/zerkalo7/lesson1.git
git push -u origin master
```
