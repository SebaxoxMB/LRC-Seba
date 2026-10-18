# Instalar y actualizar LRC Seba

Estado: documentación preparada para futuras versiones públicas. Actualmente no hay una release pública para uso general.

## Cuando se publique una APK

1. Abre [Releases](https://github.com/SebaxoxMB/LRC-Seba/releases) y lee los requisitos y limitaciones de la versión.
2. Descarga el archivo terminado en `.apk`. Los ZIP de código de GitHub no se instalan en Android.
3. Si Android lo solicita, permite instalar aplicaciones desde el navegador o gestor de archivos que usas para abrir la APK. Puedes retirar ese permiso después.
4. Abre LRC Seba y concede únicamente los permisos necesarios para las funciones que quieras utilizar.
5. El registro de LRC Seba y la autorización de Spotify son pasos distintos. Sigue las condiciones de acceso de la versión descargada.

La instalación externa puede requerir pasos adicionales según el dispositivo, versión de Android y país. No se garantiza compatibilidad universal. Android Auto necesita validación específica y no se habilita automáticamente por instalar una APK.

## Antes de actualizar

- Exporta una copia de tus proyectos importantes.
- Instala la actualización sobre la versión anterior solo cuando las notas indiquen que es compatible.
- Si aparece un error de firma o de paquete, no desinstales para forzar la actualización: podrías perder proyectos locales y borradores. Informa del error sin publicar datos privados.

La candidata 0.22.17 se compiló sin depuración y conserva el certificado de las versiones anteriores, con una copia local protegida de la firma. No se ha cambiado la identidad de la aplicación. La actualización sobre una instalación existente todavía requiere una prueba en dispositivo físico antes de anunciarla como verificada.

## Comprobar la descarga

Cada APK pública tendrá un archivo de suma SHA-256. En Windows se puede comprobar con PowerShell:

```powershell
Get-FileHash -LiteralPath 'C:\ruta\LRC-Seba.apk' -Algorithm SHA256
```

El resultado debe coincidir con la suma publicada para ese mismo archivo y versión.
