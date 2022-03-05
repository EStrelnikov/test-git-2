1. git status
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment"
4. git log / git log --oneline //просмотр подробной\ короткой информации о коммите
5. git push [rep_link] [branch_name] // отправить файлы на удаленный репозиторий
6. git reset - удаление из файла промежудочные изменения
7. git diff - просмотр промежуточных изменений в файлах
8. git reset --hard - удаление всех изменений

9. git branch - просмотр веток
10. git branch name* - создание новой ветки с названием - name
11. git checkout develop* - переключение на ветку с названием - develop
12. git pull [rep_link] [branch_name] - получение ветки - [branch_name] репозитория [rep_link] на наш ПК
13. git branch -d [branch_name] - удаление ветки с названием - [branch_name]
<!-- слияние веток --> 
    <!-- переключаемся на ветку в которую хотим перенести все изменения с другой ветки с помощью - git checkout  -->
14. git merge futere/main-page - слияние ветки с веткой(имя ветки) futere/main-page ( изменения локально на нашем ПК) 