# git-commands
Шпаргалка по командам гит

команды для создания нового репозитория:
touch README.md
git init
git checkout -b main
git add README.md
git commit -m "first commit"
git remote add origin http://163.120.70.2:3000/lepotin/qwerty.git
git push -u origin main

Пуш существующего репозитория:
git remote add origin http://163.120.70.2:3000/lepotin/qwerty.git
git push -u origin main

Изменить адрес репозитория:
git remote set-url origin https://github.com/career_karma_tutorials/git_tutorials
или
git remote rm origin
git remote add origin https://github.com/career_karma_tutorials/git_tutorials

Клонировать репозиторий:
git clone git://git.kernel.org/pub/scm/.../linux.git my-linux
