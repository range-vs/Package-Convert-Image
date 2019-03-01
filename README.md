# Package-Convert-Image

## Русское описание
Программа для пакетной конвертации изображений.
Конвертировать можно из любых форматов(в том числе и нескольких(папка .*tga, еще одна папка .dds) в любой из форматов.
За основу конвертера использует программу XnView. Соответственно, для корректной работы требуется установка данной программы.

### Использование:
* Создайте любой *.bat - файл, и в него запишите команду запуска.
* Запустите *.bat - файл и дождитесь окончания операции

### Описание команд:
* -f "format" - формат выходных файлов. Поддерживаются любые форматы, которые поддерживает XnView. Для подробностей см. документацию XnView. Задаются в том же формате, что и у XnView.
* -in "in_path" - каталог, который содержит дерево каталогов/набор файлов для преобразования
* -out "out_path" - каталог, который будет содержать набор преобразованных файлов. Структура папок созраняется.
* -n_in "path_to_xnview" - каталог, который содержит исполняемый файл программы XnView.

### Пример:
```
-f tga -in "E:\X-Ray CoP SDK\editors\gamedata\textures" -out "D:\textures_tga" -n_in "C:\Program Files (x86)\XnView"
```

P.S.: если путь до любого каталога содержит пробелы, следует экранировать его кавычками:
```
"..path.."
```

## English Description
Program for batch conversion of images.
You can convert from any formats (including several (folder. * Tga, another folder. Dds) to any of the formats.
The converter is based on the XnView program. Accordingly, for correct operation requires the installation of this program.

### Use:
* Create any * .bat file, and write the startup command in it.
* Run * .bat file and wait for the operation to finish

### Description of commands:
* -f "format" - format of output files. Any format supported by XnView is supported. See the XnView documentation for details. They are set in the same format as XnView.
* -in "in_path" is the directory that contains the directory tree / file set for conversion
* -out "out_path" is the directory that will contain the set of converted files. The folder structure is created.
* -n_in "path_to_xnview" is the directory that contains the XnView executable file.

### Example:
```
-f tga -in "E:\X-Ray CoP SDK\editors\gamedata\textures" -out "D:\textures_tga" -n_in "C:\Program Files (x86)\XnView"
```

P.S .: if the path to any directory contains spaces, you should escape it with quotes:
```
"..path .."
```
