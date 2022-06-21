## GIT commands

#### Начало работы
git clone [address] - клонировать репозиторий
git init - инициализировать локальный репозиторий
git remote add [branch_name] [address] - установить подключение с репозиторием
git pull [address] [branch_name] - вытянуть изменения из репозитория

#### Информация
git status - проверить есть ли изменения
git remote -v - показать ссылку на репозиторий
git diff / git diff [file_name]- показать какие изменения произошли
git log / git log --oneline - подробная/краткая информация o commits

#### Фиксируем изменения
git add [file_name] / git add . - добавить выбранные/все файлы в stage
git commit -m 'comments' - зафиксировать изменения локально
git push [address] [branch_name] - отправить изменения в репозиторий

#### Работа с ветками
git branch - показать имя ветки
git checkout [branch_name] - переключить ветку
git branch [branch_name] - создать новую ветку
git merge [branch_name] - объединить ветки
git branch -d [branch_name] - удалить ветку локально

#### Остальное
git reset [file_name] - убрать файл из stage
git reset --hard - убрать все произведенные изменения