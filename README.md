﻿## Что такое Git.

Git - это система контроля версий (англ. Version Control System или VCS). В том числе она хранит историю проектов разработчиков.

Одно изменение называется ревизия или версия.
Каждая ревизия содержит информацию о том, что изменилось, кто и когда внес изменения и комментарии, если они есть.

Основные функции VCS: 
* хранит историю изменений в виде отдельных ревизий
* позволяет манипулировать историей: менять порядок ревизий, полностью удалять версии, возвращаться назад в истории и т.д.
* помогает анализировать изменения: например, кто и когда вносит изменения, кто чаще всего вносит изменения в определенный файл и т.д.

Ключевая особенность современных VCS - поддержка параллельной работы нескольких пользователей, в т.ч. над одним файлом. 

VCS - это общее название ряда продуктов, таких как Git, Mercurial, Subversion и др.

Git - программа, которая в т.ч. может работать из командной строки.


## Основные команды в командной строке:

* pwd (print working directory) - показать рабочую папку.
* cd (change directory) - переход в указанную в качестве параметра директорию
* ~ - обозначение для домашней директории
* .. – обозначение родительской директории
* . – обозначение текущей директории
* ls (list directory contents) – вывести содержимое директории
* touch – команда для создания файла в текущей или указанной директории, имя файла рекомендовано указывать с расширением
* mkdir (make directory) – команда для создания папки 
* cp (copy) – команда для копирования файлов (два параметра: что копируем и куда копируем)
* mv (move) – команда для перемещения файлов (два параметра: что перемещаем и куда)
* cat (concatenate and print) – команда для чтения текстовых файлов
* rm (remove) – команда для необратимого удаления файла
* rmdir (remove directory) – необратимо удаляет папку (директорию), если папка пуста
* rm -r (remove recursive) – команда для необратимого удаления директории со всем ее содержимым (в случае, когда мы 100% уверены, что мы точно хотим удалить все файлы внутри директории)


## Советы по эффективной работе в командной строке:

1. Выполняйте сразу несколько команд. Можно записать несколько команд сразу все списком через символ &&. 
2. Вызывайте команды из буфера. У терминала (консоли/командной строки) есть собственная память, в ней хранятся все команды, которые вызывались до этого, по их списку можно перемещаться с помощью стрелочек вверх и вниз.
3. Используйте автозаполнение. 
* Можно набрать в терминале первые буквы команды и дважды нажать на Tab – появится список команд, которые начинаются с этих же символов.
* Tab автоматически дописывает не только команды, но и пути.
* Используйте Tab при навигации в другую директорию. Если вводим команду cd и название папки, а после этого нажимаем Tab, то консоль покажет все возможные пути.


 
## Работа с Git.

Основные команды:

* git init – сделать папку репозиторием
* rm -rf .git – разгитить папку
* git status – проверить состояние репозитория
* git add – подготовить файл к сохранению 
* git commit – выполняем коммит (непосредственно сохранение)
* git log – посмотреть историю коммитов 

