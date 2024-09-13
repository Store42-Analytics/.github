# Генерация SSH ключа
```bash
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

# Основные команды Git

## Настройка и конфигурация

```bash
git config --global user.name "Ваше Имя"
git config --global user.email "your_email@example.com"
```

## Работа с репозиториями

```bash
git init
git clone [url]
```

## Основные операции с файлами

```bash
git add [file]
git status
git commit -m "Сообщение коммита"
git rm [file]
git mv [old_filename] [new_filename]
```

## Работа с ветками

```bash
git branch [branch-name]
git checkout [branch-name]
git merge [branch-name]
```

## Просмотр истории и изменений

```bash
git log
git diff
```

## Синхронизация изменений

```bash
git pull
git push origin [branch-name]
```

## Вспомогательные команды

```bash
git stash
git tag [tag-name]
```
