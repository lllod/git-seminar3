# Инструкция по работе с программой Git

Git - это программа для ...

## Создание репозитория

Для создания(**инициализации**) нового репозитория в текущей папке используется команда:

    git init

## Проверка состояния репозитория

Для проверки состояния репозитория нужно выполнить команду:

    git status

## Добавление изменений к отслеживанию

Для добавления изменений к отслеживанию (в "индекс") нужно выполнить команду:

    git add <filename>

## Добавление коммитов

text

    git commit

text    

    git commit -m 'message'

text

    git commit -a

text

    git commit -am 'message'

## Логгирование

text

    git log

text

    git log --oneline

text

    git log --all

text

    git log --oneline --all

## Переключение между коммитами

text

    git checkout <hash>

## Сравнение коммитов

text

    git diff

text

    git diff <hash1> <hash2>