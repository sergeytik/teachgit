# teachgit

# это по-моему не работает:

git pull https://github.com/sergeytik/teachgit.git

#полностью перезалить проект с нуля в текущий каталог:
#1. удаляем все:

rm -rf .git
rm -rf *

#2. Пересоздаем начисто:

git init
git remote add origin https://github.com/sergeytik/teachgit.git
git pull origin master

#3 после того как сделаны изменения, коммитим все сразу без add и отправляем на депозитарий

git commit -a -m "comment"
git pull -u origin master
