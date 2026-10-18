# LRC Seba

Aplicación para ver, crear y corregir letras sincronizadas en formato LRC.

Este es el repositorio de distribución gratuita de LRC Seba. Está destinado a instrucciones y versiones descargables; no contiene los proyectos personales del autor ni el código completo de la aplicación.

## Descargas

**La versión pública está en preparación. Todavía no hay una APK publicada para uso general.**

Las APK disponibles se publicarán en [Releases](https://github.com/SebaxoxMB/LRC-Seba/releases), junto con sus requisitos, novedades y suma SHA-256. Los archivos `Source code.zip` y `Source code.tar.gz` que genera GitHub no son la aplicación Android.

## Funciones

- Crear letras con tiempos por línea y corregir sincronizaciones existentes.
- Guardar proyectos, borradores y archivos LRC.
- Seguir la canción que se está reproduciendo en el teléfono.
- Cuenta individual y sincronización privada de proyectos entre equipos.

El proyecto incluye integración con Spotify y un prototipo para Android Auto. Su disponibilidad en una versión pública está pendiente de validación; no se promete compatibilidad con todos los usuarios, países o vehículos.

## Cuentas y Spotify

La experiencia prevista es descargar, instalar, entrar con Google y conectar la propia cuenta de Spotify. Ambas autorizaciones son independientes. Las contraseñas se introducen en los servicios correspondientes.

**La conexión completa con Spotify aún no es de acceso público.** La candidata 0.22.18 ya incorpora la configuración de LRC Seba: las instalaciones nuevas usan el botón **Vincular con Spotify**, sin introducir claves. El propietario todavía debe habilitar las cuentas participantes desde **User Management** de su aplicación en Spotify Developers. Instalar la APK o iniciar sesión no sustituye ese acceso a la beta.

La [documentación de Spotify Web API](https://developer.spotify.com/documentation/web-api/concepts/quota-modes) limita el modo de desarrollo a cinco usuarios autorizados. No se presenta esta beta como una integración ilimitada ni como un producto aprobado por Spotify.

## Requisitos y preparación

- La compilación actual requiere Android 8.0 o posterior.
- Se preparó una candidata 0.22.18 sin depuración, con Spotify preconfigurado y la misma firma de las versiones anteriores. Todavía permanece en borrador.
- Algunas funciones necesitan conexión a Internet y permisos que se explican en la app.
- Antes de abrir el servicio al público se completarán la prueba de actualización, el flujo de instalación, la política de privacidad, la eliminación de cuenta y las pruebas con nuevos usuarios.
- La sincronización en nube depende de la disponibilidad y cuotas del servicio. No se ofrece capacidad ilimitada.

Consulta la [guía de instalación y actualización](docs/INSTALACION.md).

## Informar un problema

Puedes abrir un [issue](https://github.com/SebaxoxMB/LRC-Seba/issues) indicando la versión de la app, versión de Android, modelo del equipo y pasos para reproducirlo. No publiques contraseñas, tokens, correos personales, respaldos privados ni letras completas de terceros.

## Avisos

Los componentes de terceros conservan sus propias licencias y avisos, incluidos en [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Este repositorio no concede derechos sobre letras o música de terceros. LRC Seba no está afiliada ni respaldada por Spotify, Google o GitHub.
