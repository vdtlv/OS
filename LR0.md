# Отчет по Лабораторной Работе #0
Cкрипты для установки дистрибутивов следующего ПО:
#### 7-zip
``` 
C:\Users\VD\Downloads>msiexec /i 7z1900-x64.msi /norestart /le 7-zip-log.txt TARGETDIR=”C:\Program Files\7-Zip” /passive
```
#### Paint.Net
```
C:\Users\VD\Downloads>paintnet_4.2.12.exe /auto DESKTOPSHORTCUT=1 TARGETDIR=C:\Program Files\Graphics\Paint 
```
#### Inkscape
```
C:\Users\VD\Downloads>msiexec /i inkscape-1.0-x64.msi /qr /norestart TARGETDIR=”C:\Program Files\Graphics\Incscape” /lw inkscape-log.txt
```
#### LibreOffice
```
C:\Users\VD\Downloads>msiexec /i LibreOffice_6.4.4_Win_x86.msi /passive /le libreoffice-install-log.txt /norestart
```
##### Русскоязычное расширение
```
C:\Users\VD\Downloads>msiexec /i LibreOffice_6.4.4_Win_x86_helppac_ru.msi /passive /le libreoffice-install-log.txt /forcerestart
```
#### Notepad++
```
C:\Users\VD\Downloads>msiexec /i Norepad++7.6.6.msi /passive
```
