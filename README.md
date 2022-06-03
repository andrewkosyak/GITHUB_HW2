# GITHUB_HW2
@andy_kosyak

Precondition
- Repo -> New -> GitHub_HW2 -> create repo 
- git clone <url>

1) На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bag_Reports
git branch SQL
git branch Charles
git branch Mobile_testing

2) Запушить все ветки на внешний репозиторий
git push --all

3) В ветке Bag Reports сделать текстовый документ со структурой баг репорта
nano bugreport.txt

Bug ID -
Tester -
Date -
Title -

Bug Description
URL -
Summary -
Screenshot -
Platform -
Browser -

Administrative
Assigned to -
Assigned at -
Priority -
Severity -

Notes
Steps:
1)
2)
3)
...

AR
ER

CTRL + O
ENTER
CTRL +X

4) Запушить структуру багрепорта на внешний репозиторий
git add . 
git commit -m "bugreport structure"
git push origin Bag_Reports


5) Вмержить ветку Bag Reports в Main
git checkout main
git merge Bag_Reports -m "merge bugreport"

6) Запушить main на внешний репозиторий.
git push

7) В ветке CheckLists набросать структуру чек листа.
git checkout CheckLists
nano checklist.txt

Операции с файлами

     Проверка                  ER        AR      Комментарии
1) создать файл              passed    passed
2) открыть файл              passed    passed
3) ...                       ...


8) Запушить структуру на внешний репозиторий
git add .
git commit -m "add checklist"
git push origin CheckLists

9) На внешнем репозитории сделать Pull Request ветки CheckLists в main
Compare & Pull requests
Create Pull request
Merge Pull request
Confirm merge

10) Синхронизировать Внешнюю и Локальную ветки Main
git checkout main
git fetch
git pull









