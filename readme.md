# Tricks for Windows
## Index
1. [Create txt file](#id1)
2. [Use Powershell for folder rename](#id2)
3. [Saber la capacidad maxima de memoria admitida por la PC](#id3)

# 1. Create txt file <a named="id1"></a>
LISTAR ARCHIVOS CON CMD

Ejecutar CMD como administardor, luego teclear "cd" para ingresar a la ruta donde se desea enlistar archivos
Solo que muestre el nombre de los archivos en el bloc de notas
```dos
D:\SDRAG_GIS\GLOF\WP2\L4-5_2010>dir /b >lista.txt
```

LISTAR ARCHIVOS CREANDO UN ARCHIVO .BAT
Personalizar la ruta para enlistar archivos

dir /a /b /-p /o:gen >C:\Users\DELL\Desktop\lisatdo.txt
start notepad C:\Users\DELL\Desktop\listado.txt

# 2. Use Powershell for folder rename <a named="id2"></a>
```dos
PS C:\FolderPath> REN 'OldName.pdf' 'NewName.pdf'
```
Hit enter for name change

You can automatize with an excel table for many files


# 3. Use Powershell for folder rename <a named="id3"></a>
```dos
# Windows
wmic memphysical get MaxCapacity, MemoryDevices

# Linux
ubuntu/debian: sudo apt install dmidecode
arch: sudo pacman -S dmidecode
Fedora: sudo dnf install dmidecode
openSUSE: sudo zypper in dmidecode
```
