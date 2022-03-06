# 22919-1
## Лабораторная работа GIT
### Общий удаленный репозиторий группы 22919/1 для лабораторной работы по Git

### Если уже создан Git репозиторий
1. Регистрируйтесь на GitHub, присылаете мне свое имя
3. Я приглашаю вас в проект репозитория, вы получаете доступ к редактированию общего репозитория
4. `git remote add origin https://github.com/Madixxx22/22919-1.git` (подключаетесь у себя на устройтсве)
5. `git pull` (получаете все данные с облачного репозитория)
6. создаете новую ветку со своей фамилией
7. `git push -u origin [введите свое название ветки по фамилии латиницей]` (отправляете свою ветку в удаленный репозиторий)

### Если не создан Git
1. `git clone https://github.com/Madixxx22/22919-1.git` он копирует удаленный репозиторий
2. Создаете свою ветку работаете с ней
3. `git remote add origin https://github.com/Madixxx22/22919-1.git` (подключаетесь у себя на устройтсве)
4. `git push -u origin [введите свое название ветки по фамилии латиницей]` (отправляете свою ветку в удаленный репозиторий)

Или проворачиваете все то же самое, что и в 1 варианте, но в самом начале создаете репозиторий `git init`

Также работаете с ним `git add .` добавляете все свои файлы на фиксацию

`git commit -m "Ваше сообщение коммита"` А дальше просто привязываетесь к моему репозиторию и пушите изменения как в 1 варианте

Примечание:

Если вы загружали свой репозиторий на GitHub вам сначала нужно отвязать его от удаленного репозитория и только потом присоединятся к моему. 

`git remote remove origin` (команда для отвязки)

Если будут какие-то ошибки пишите в лс помогу
