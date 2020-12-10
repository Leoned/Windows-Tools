# Tricks for Windows
## Index
1. [Create txt file](#id1)
2. [Use Powershell for folder rename](#id2)

# 1. Create txt file <a named="id1"></a>
LISTAR ARCHIVOS CON CMD

Ejecutar CMD como administardor, luego teclear "cd" para ingresar a la ruta donde se desea enlistar archivos
Solo que muestre el nombre de los archivos en el bloc de notas
D:\SDRAG_GIS\GLOF\WP2\L4-5_2010>dir /b >lista.txt


LISTAR ARCHIVOS CREANDO UN ARCHIVO .BAT
Personalizar la ruta para enlistar archivos

dir /a /b /-p /o:gen >C:\Users\DELL\Desktop\lisatdo.txt
start notepad C:\Users\DELL\Desktop\listado.txt

# 1. Use Powershell for folder rename <a named="id2"></a>
```cmd
PS C:\FolderPath> REN 'OldName.pdf' 'NewName.pdf' --- hit enter for name change
```
You can automatize with an excel table for many files
