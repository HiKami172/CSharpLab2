# CSharp lab 2
## Windows-служба прослущивает папку "sourceDirectory" проекта. 
## При добавлении файла программа:
- создает его зашифрованную копию
- архивирует
- разархивирует
- дешифрует в папку "targetDirectory" проекта
# targetDirectory хранит файлы в поддиректориях формата "dd.mm.yyyy/hh.mm.ss" (дата и время приема файлов sourceDirectory

## Требования:
- добавить папки "sourceDirectory" и "targetDirectory"

## Обзор:
- Archive.cs - содержит класс с методами архивации и распаковки
- Cryptograpgy.cs - содержит класс с методами шифрования и дешифарования
- Service1.cs - функционал службы
- Installer1.cs - установщик службы