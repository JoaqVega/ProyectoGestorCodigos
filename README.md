# ProyectoGestorCodigos
Proyecto del curso DAWI

Dentro de dawi crea una carpeta llamada angular

Extrae mi-proyecto2.zip dentro de angular/


Importar:
Abre CMD

Navega hasta la carpeta del proyecto: cd C:\Users\TuUsuario\Documents\mi-proyecto-angular

O en el explorador de archivos ve a la carpeta y en la URL ejecutas cmd.

Instalas dependencias: npm install
Ejecutas code .
En la termina del VS code ejecutas ng serve

Si hay error de: ng : No se puede cargar el archivo C:\Users\rodri\AppData\Roaming\npm\ng.ps1 porque la ejecución de scripts está deshabilitada en este sistema. Para obtener más información, consulta el tema about_Execution_Policies en https:/go.microsoft.com/fwlink/?LinkID=135170. En línea: 1 Carácter: 1 + ng serve + ~~ + CategoryInfo : SecurityError: (:) [], PSSecurityException + FullyQualifiedErrorId : UnauthorizedAccess


En ejecutar como admin en PowerShell, ejecutamos: Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

