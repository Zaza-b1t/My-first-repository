# Всё о Git

## Основные команды

1. Инициализация репозитория:
   ```bash
   git init

Добавление файлов:
git add <имя_файла>     
git add .    
Коммит изменений:

bash
Копировать
git commit -m "Сообщение о коммите"
Просмотр статуса репозитория:

bash
Копировать
git status
Просмотр истории коммитов:

bash
Копировать
git log
Работы с удалённым репозиторием:

bash
Копировать
git remote add origin <URL-репозитория>    
git push -u origin master                  
git pull                                   
Работа с ветками:

bash
Копировать
git branch <имя_ветки>                     
git checkout <имя_ветки>                   
git checkout -b <имя_ветки>                