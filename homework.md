# Команды Git

Инициализация нового репозитория
git init 

Клонирование существующего репозитория
git clone <repository_url>
git clone --branch <branch_name> <repository_url>  # Клонирование конкретной ветки

Добавление изменений
git add <file>
git add .  # Добавить все изменения
git add -p  # Интерактивное добавление изменений


Сохранение изменений в локальный репозиторий
git commit -m "Commit message"
git commit -a -m "Commit message"  # Добавить все измененные файлы и закоммитить


Отправка изменений в удаленный репозиторий
git push origin <branch>
git push -u origin <branch>  # Установить ветку как отслеживаемую


Получение изменений из удаленного репозитория
git pull origin <branch>
git pull --rebase origin <branch>  # Получить изменения и перебазировать


Проверка состояния репозитория
git status
git status -s  # Краткий статус


Проверка состояния репозитория
git status
git status -s  # Краткий статус


Просмотр истории коммитов
git log
git log --oneline  # Краткий лог
git log --graph  # Графический лог
git log -p  # Показать изменения в каждом коммите


Работа с ветками.
git branch  # Список всех веток
git branch <new_branch>  # Создать новую ветку
git branch -d <branch>  # Удалить ветку
git branch -r  # Список удаленных веток


Переключение между ветками или восстановление файлов
git checkout <branch>
git checkout -b <new_branch>  # Создать и переключиться на новую ветку
git checkout -- <file>  # Отменить изменения в файле


Слияние веток
git merge <branch>
git merge --no-ff <branch>  # Слияние без fast-forward


Просмотр различий между коммитами, ветками или файлами
git diff
git diff <branch1> <branch2>
git diff --staged  # Различия между индексом и последним коммитом


Управление удаленными репозиториями
git remote -v  # Список всех удаленных репозиториев
git remote add <name> <url>  # Добавить новый удаленный репозиторий
git remote rm <name>  # Удалить удаленный репозиторий


Получение изменений из удаленного репозитория без слияния
git fetch origin
git fetch --all  # Получить изменения из всех удаленных репозиториев


Удаление файлов
git rm <file>
git rm --cached <file>  # Удалить файл из индекса, но оставить его в рабочей директории


