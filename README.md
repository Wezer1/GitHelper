# Помощник по командам git

## Базовые команды терминала


1. *cd* - перейти в след директорию


2. *pwd* - вывести директорию в которой находишься


3. *ls* - содержимое директории 


4. *touch* - создание файла


5. *mkdir* - создание директории 


6. *rm(dir)* - удаление файла или директории


## Базовые команды git


1. *git config* - команды igt


2. *git status* - вывести состояния git


3. *git add* - добавление файла в git


4. *git commit* - сохранение commit


5. *git log* - вывести журнал записей


6. *git remote (-v)* - добавление commit на GitHub


## Хеш, лог, HEAD


1. *Хеширование* (от англ. hash, «рубить», «крошить», «мешанина») — это способ преобразовать набор данных и получить их «отпечаток» (англ. fingerprint).


2. Получить сокращённый лог можно с помощью команды ~~git log~~ с флагом ~~--oneline~~ (англ. «одной строкой»).


3. В числе прочих файлов в папке .git есть служебный файл **HEAD**. Он указывает на самый свежий коммит.
Вместо хеша последнего коммита можно написать слово ~~HEAD~~ — Git вас поймёт.


## Виды статуса файлов

**untracked** (англ. «неотслеживаемый»)


**staged** (англ. «подготовленный»)(after git add)


**tracked** (англ. «отслеживаемый»)(в него попадают файлы, которые уже были зафиксированы с помощью git commit, а также файлы, которые были добавлены в staging area командой git add)


**modified** (англ. «изменённый»)