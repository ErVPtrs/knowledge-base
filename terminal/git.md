# Git
1. Создать удаленный репозиторий (например на `GitHub`)
2. Клонировать репозиторий (создать локальную копию), используя URL
3. Внести изменения, сделать commit
4. Выгрузить коммит(ы) в удаленный репозиторий

_Пример:_
```bash
# 1. Клонировать репозиторий по его URL (URL репозитория получаем на GitHub (кнопка Code)

$ git clone https://github.com/ErVPtrs/knowledge-base.git
# В текущем каталоге будет создан каталог 
# с именем knowledge-base 
# Содержимое будет совпадать с удаленным репозиторием
# (с тем, который клонировали)


# 2. Открыть локальный репозиторий, например, 
# в Visual Studio Code
$ code knowledge-base

# Файлы проекта редактируются в Visual Studio Code

# 3. В терминале Visual Studio Code выполняем коммит и 
# отправляем коммит в удаленный репозиторий
$ git add python.md
# где python.md - это файл, изменения в котором 
# будут включены в следующий коммит
$ git commit -m "initial commit"
# где -m означает message (сообщения)
# "initial commit" - текст сообщения
# Первый коммит принято сопровождать текстом
# initial commit 
# 4. Выгрузить коммит или коммиты 
# (если было сделано несколько)
# в удаленный репозиторий
$ git push
```
