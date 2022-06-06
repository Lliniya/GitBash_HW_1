# GitBush_HW_1
1. Посмотреть где я 

  `pwd`

2. Создать папку 

  `mkdir folder_1`

3. Зайти в папку 

  `cd folder_1`

4. Создать 3 папки mkdir folder1 folder2 folder3

  `mkdir folder_1 folder_2 folder_3`

5. Зайти в любую папку cd folder1

  `cd folder_1`

6. Создать 5 файлов (3 txt, 2 json) 

  `touch test1.txt test2.txt test3.txt test4.json test5.json`

7. Создать 3 папки

  `mkdir folder_1 folder_2 folder_3`

8. Вывести список содержимого папки

  `ls -la`

9. Открыть любой txt файл 

  `vim test1.txt`

10. Написать туда что-нибудь, любой текст. 

   `i "hello world"`

11. Сохранить и выйти. 

   `Esc -> :wq`

12. Выйти из папки на уровень выше 

   `cd ..`

13. Переместить любые 2 файла, которые вы создали, в любую другую папку. 

   `mv folder_1/test1.txt folder_2/test1.txt`
   `mv folder_1/test2.txt folder_2/test2.txt`
   
14. Скопировать любые 2 файла, которые вы создали, в любую другую папку. 

   `cp folder_2/test1.txt folder_1/test1.txt`
   `cp folder_2/test2.txt folder_1/test2.txt`

15. Найти файл по имени

   `find -name test1.txt`

16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает. 

   `grep '' file1.txt`

17. Вывести несколько первых строк из текстового файла 

   `head -n3 test1.txt`

18. Вывести несколько последних строк из текстового файла

   `tail -n3 test1.txt`

19. Просмотреть содержимое длинного файла (команда less) изучите как она работает.

   `less test1.txt`

20. Вывести дату и время

   `date`
  
==========================================

ЗАДАНИЕ*
1. Отправить http запрос на сервер. http://162.55.220.72:5005/terminal-hw-request  
```
   Шаг 1 - curl http://162.55.220.72:5005/terminal-hw-request  
   Шаг 2 - curl "http://162.55.220.72:5005/get_method?name=Slava&age=37"
```
2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13  
```
   Файл myscript.sh находится в ветке main данного репозитория.
```
