Current firmware:
v400_01_051_N

Патч из Zalman в Iodd (с версией 79(N) на борту):
Прошивки для iodd: http://iodd.kr

Для прошивки другой версии необходимо:
Скачать новую версию прошивки
Открыть EXE прошивку и извлечь mic и bin файл. Поместить их в папку с патчем
Открыть iODD2541-fw-updater-04.ini и внести изменения в строчки 4 - Firmware и 58 - Micom:
Указать там ваши файлы из прошлого пункта

Запустить iODD2541-fw-updater-04.exe

iODDs Пример дерева папок
создайте папку с именем "_ISO" в корневой папке.
Это дерево папок является примером.
Любое имя файла и имя папки под "_ISO" является приемлемым.

J:
├─ _ISO
│  │  Hiren’s BootCD 15.2.iso
│  │  ubuntu-14.04.4-desktop-amd64.iso
│  │  Windows 10.iso
│  │  Windows XP sp3.iso
│  │  (не более 32 файлов или вложенных папок в папке)
│  │  
│  ├─IMA for Floppy
│  │      Bios updater.ima
│  │      MS-DOS 6.0.ima
│  │      Symantec Ghost.ima
│  │      
│  ├─RMD for Setup
│  │      Win 7Ent_x86_x64+8.1Pro+10Pro vol2.RMD
│  │      Win7_Ult_SP1_Russian_x64.RMD
│  │      Windows 10.RMD
│  │      
│  └─VHD for Booting
│      │  linuxmint-17.3-cinnamon-32bit.vhd
│      │  Windows 10 Win2Go.vhd
│      │  Windows 7 OS Booting.vhd
│      │  
│      └─Вложенные Подпапки допускается
├─Your Folder 01
├─Your Folder 02
├─Your Folder 99
│  Your files 01.txt
│  Your files 02.txt
│  Your files 99.txt
