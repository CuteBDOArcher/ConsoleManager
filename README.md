Консольный файловый менеджер с небольшим количеством команд для работы с данными. 

Команды:			
VIEW (V) -      Показывает выбранный каталог по странично с первой страницы.
                Примеры
                view C:\DirectoryName
                v C:\DirectoryName

PAGE (P) -      Переходит на указыную страницу каталога.
                Примеры:
                page 1
                p 4

FILEINFO (FI) - Показывает информацию о запрашиваемом файле.
                Примеры:
                fileInfo "C:\Directory Name\file.txt"
                fileinfo C:\DirectoryName\file.txt
                fi C:\Directory Name\file.txt


COPY (C) -      Копирование. Может копировать файлы и каталоги с файлами.
                Для копирования необходимо указать:
                путь до файла или каталога и путь каталога
			куда будет производится копирование.
                Примеры:
       		copy "C:\Directory Name\file.txt" "C:\New 				Directory Name"
                copy C:\DirectoryName "C:\New Directory Name"
               c C:\DirectoryName\file.txt C:\NewDirectoryName


DELETE (D) -    Удаление. Удаляет файл или каталог с файлами.
                Примеры:
                delete "C:\Directory Name\file.txt"
                delete C:\DirectoryName
                d "C:\Directory Name\file.txt"


QUIT (Q) -      Выход из программы.
                Примеры:
                quit
                exit
                q
