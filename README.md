# Time Zone Fixer

This small app fixes the timezone problems in the countries that the government changes the policy of daylight saving time (DST).

## Usage
In order to make it work, just run in your terminal:
```bash
$ sh ./generator
```
This script will automatically download the latest timezone data, decompress it and will compile the files that you need upload to your Android-based device.
This script will generate three files:
- zoneinfo.dat
- zoneinfo.idx
- zoneinfo.version

Copy/Replace these three files into your device (in the /system/usr/share/zoneinfo folder). To do it, you should use a file viewer application like ES File Explorer, enable the root mode and mount / in mode writable.

Reboot your device.


## Uso

Esta aplicación corrige el problema de la zona horaria en los países que los gobiernos modifican el cambio de hora.

Para ejecutarlo, escribe lo siguiente en tu consola:
```bash
$ sh ./generator
```
Este script descarga la última versión del timezone data, lo descomprime y compila automáticamente para generar los binarios necesarios para la actualización de tu android.

Este script crea tres archivos:
- zoneinfo.dat
- zoneinfo.idx
- zoneinfo.version

Copia/Reemplaza esos archivos en tu android en la carpeta /system/usr/share/zoneinfo. Para realizarlo, debes usar un programa que te permita explorar tus archivos, como por ejemplo el ES File Explorer en modo root y montando la partición / en modo escritura.

Reinicia tu Android.



-- mcornejo
