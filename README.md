Шпора по гиту

pwd - текущая директория 
cd ~ - перейти в домашнюю директорию
cd c:/ - переместились в корневую директорию 
ls - содержимое директории
ls -a - покажет абсолютно все файлы даже скрытые
ls ~
ls ..
cd .. - возврат к предыдущей директории
cd git - переход к следующей директории
cd git/git2 - перемещение через несколько директорий
touch my-new-file.txt - создали файл my-new-file.txt 
mkdir new-dir - создали директорию new-dir 
mkdir -p dir1/dir-inside/dir-deeper-inside - создали папку dir-deeper-inside в папке dir-inside, которая находится в папке dir1 
mkdir ~/my-git-projects 
touch ../../file.txt
cp index.html src/ - скопировали index.html в папку src 
cp index.html style.css script.js src/ - скопировали три файла (index.html, style.css и script.js) в папку src 
mv table.csv ./very-important-files - переместить файл
cat myfile.txt - показать содержимое файла (только текст)
rm example.txt - удалили файл example.txt из текущей папки 
rmdir images - команда удалит папку images из текущей директории, если папка images пуста 
rm -r images - удалили папку images со всем её содержимым из текущей директории 
&& - можно объединять команды в 1 строку
2 таба выведут все команды, 1 таб допишет название файла или папки

git config --list - показать заданное имя юзера и email для гита (cat ~/.gitconfig - аналогичная команда)
git init -создать репозиторий в папке
rm -rf .git - прекратить инициализацию репозитория 
git status - состояние репозитория

git add --all - добавить все файлы в папке к выбранным
git add readme.txt - добавить по одному
git add . - добавить всю текущую папку

git commit -m "Мой первый коммит!" - сохранение
git log - выводит информацию о коммитах

git push -u origin main - пушим первый раз в удаленный репозиторий
git push - все остальные пуши