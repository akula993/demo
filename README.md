# Вытаскиваем все пакеты
* pip freeze
* pip freeze > requirements.txt 
 
Создаем локальный репозиторий
* git init

Проверяем статус репозитория и добовляем новые
* git status 
* git add . или git add -A
* git status 

Создаем комит
* git commit -m "django demo and settings"

Подключаем удаленный репозиторий и пушми
* git remote add origin git@github.com:akula993/demo.git
* git push -u origin master


* git checkout master
* git checkout main

На другом компе делаем
* git clone git@github.com:akula993/demo.git


* git push origin 
* git checkout main
* git checkout master
* git push origin master
* 
* cd ..
* git status 
* git push -u origin master

Применяем миграции
*  python manage.py migrate