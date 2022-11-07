1. git status
2. git add [files] // git add . (точка заменяет все файлы), добавляет файлы в stage
3. git commit -m "comment" // добавление комментариев
4. git log // показывает нашу запись
4.1 git log --oneline // показывает запись в укороченном виде
5. git push [rep_link] [branch_name] // отправить изменения на репозиторий
   // git push origin master

   Команды:
1. git remote -v // Узнать ссылку на репозиторий
2. git config user.name "" // добавить или узнать имя
3. git congig user.email ""
4. git branch name // узнать ветку, добавить ветку
4.1 git checkout name // переключиться на другую ветку
5. git reset //позволяет удалить файлы в промежуточной области
5.1 git reset --hard // вернёт изменения на нужные места
6. git diff // строки которые мы добавляли