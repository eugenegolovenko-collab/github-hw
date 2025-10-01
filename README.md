# github-hw
#Домашнее задание к занятию «Git» - Евгений Головенко
---
## Задание 1

**Действия:**
1. Зарегистрирован аккаунт GitHub.
2. Создан новый публичный репозиторий с инициализацией `README`.
3. Клонирование репозитория:

`git clone https://github.com/eugenegolovenko-collab/github-hw.git`
   
4. Настройка git-конфига (имя и почта):

`git config --global user.name "Eugene Golovenko"`

`git config --global user.email "eugene.golovenko@gmail.com"`
   
5. Проверка статуса:

`git status`
  
   Вывод:
   
   `On branch main`
   
   `Your branch is up to date with 'origin/main'.`
   
   `nothing to commit, working tree clean`
   
6. Редактирование README.md - добавление названия задания и имени > файл перешёл в статус Modified.

7. Проверка статуса:
   
`git status`
   
8. Проверка изменений:

`git diff`
   
`git diff --staged`
   
9. Добавление в staged:

`git add README.md`
   
10. Создание коммита:

`git commit -m "First commit. Added work title and name."`
   
11. Отправка изменений:

`git push origin main`

[Ссылка на коммит](https://github.com/eugenegolovenko-collab/github-hw/commit/ef876615baf2a297ced47fa327104400da80b36e)

---
## Задание 2

**Действия:**
1. Создан файл `.gitignore`:

   `touch .gitignore`
   
   `git status`

2. Добавлены правила игнорирования:

   `cache/`

   `*.pyc`

3. Добавление в staged и коммит:

   `git add .gitignore`
   
   `git commit -m "Add .gitignore file"`

4. Отправка изменений:
   
   `git push origin main`
   
[Ссылка на коммит](https://github.com/eugenegolovenko-collab/github-hw/commit/48d9d52e5099f16d398b77427ae3de6a98239162)

---
## Задание 3

**Действия:**
1. Создана ветка `dev`:

   `git checkout -b dev`

2. В ветке dev создан файл `test.sh` с несколькими коммитами и пушами:

   `git add test.sh`

   `git commit -m "Add test.sh with content"`

   `echo "echo Another line" >> test.sh`
   
   `git add test.sh`
   
   `git commit -m "Update test.sh with new line"`
   
   `git push origin dev`

3. Переключение на основную ветку `main`:

   `git checkout main`

4. Создан файл `main.sh` и отправлен в репозиторий:

   `echo "echo Hello Main" >> main.sh`

   `git add main.sh`

   `git commit -m "Add main.sh in main branch"`

   `git push origin main`

5. Слияние ветки dev в main и пуш:

   `git merge dev`

   `git push origin main`

6. [Ссылка на граф коммитов](https://github.com/eugenegolovenko-collab/github-hw/network)


   
