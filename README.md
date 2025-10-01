# github-hw
Домашнее задание к занятию «Git»
Фамилия Имя: Евгений Головенко
---
## Задание 1

**Действия:**
1. Зарегистрирован аккаунт GitHub.
2. Создан новый публичный репозиторий с инициализацией `README`.
3. Клонирование репозитория:
   ```bach
   git clone https://github.com/eugenegolovenko-collab/github-hw.git ```
4. Настройка git-конфига (имя и почта):
   ```bach
   git config --global user.name "Eugene Golovenko"
   git config --global user.email "eugene.golovenko@gmail.com" ```
5. Проверка статуса:
   ```bach
   git status ```
   Вывод:
   On branch main
   Your branch is up to date with 'origin/main'.
   nothing to commit, working tree clean
6. Редактирование README.md > файл перешёл в статус Modified.
7. Проверка статуса:
   ```bach
   git status ```
8. Проверка изменений:
   ```bash
   git diff
   git diff --staged ```
9. Добавление в staged:
   ```bash
   git add README.md ```
10. Создание коммита:
   ```bash
   git commit -m "First commit. Added work title and name." ```
11. Отправка изменений:
   ```bash
   git push origin main ```
Ссылка на коммит:
https://github.com/eugenegolovenko-collab/github-hw/commit/ef876615baf2a297ced47fa327104400da80b36e

