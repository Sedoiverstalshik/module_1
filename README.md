# git-config

git config --global user.name “имя”
git config --global user.email “почта”

git config --list # посмотреть настройки

git config --global core.autocrlf true
git config --global core.quotepath off
git config --global core.safecrlf warn
git config --global init.defaultBranch main # Ветка по умолчанию

git init # инициализация репозитория
git add . # добавить все фаилы 
git commit -m "описание" # сделать коммит
git status # показывает текущий статус
git diff - # показывает текущие изменения
git diff --color-words # показывает изменения более развернуто
git checkout . # вернуться к последнему коммиту

git clone указываем путь к репозиторию # клонируем репозиторий