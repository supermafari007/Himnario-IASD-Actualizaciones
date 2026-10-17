# Himnario Adventista para Windows y macOS

Descarga el instalador desde [la última versión estable](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/latest).

Este repositorio público distribuye los instaladores y sus sumas SHA-256. El código del programa se mantiene en un repositorio privado.

## Instalar en Windows

1. Descarga `Himnario_Adventista_WebView2_Setup.exe` desde Releases y ejecútalo en Windows x64.
2. Abre el Himnario y pulsa **Descargar ahora** para instalar los recursos multimedia.
3. Puedes usar **Elegir carpeta** para guardarlos en otro disco. Necesitas aproximadamente **8,6 GB libres** durante la descarga y extracción del paquete 1.0 de 4,21 GB.

El instalador es un único archivo; no necesita archivos `.bin` adicionales. Si falta WebView2, el instalador web oficial de Microsoft lo descarga. La aplicación incluye .NET y, una vez descargados los recursos, funciona sin conexión.

## Actualizaciones

**Buscar actualización** consulta las nuevas versiones estables de este repositorio y el manifiesto de recursos multimedia. El programa verifica el SHA-256 del instalador descargado antes de permitir su ejecución y conserva los recursos existentes.

Los recursos se descargan del [dataset oficial configurado en Hugging Face](https://huggingface.co/datasets/supermafari007/himnario-recursos). La versión multimedia se consulta en [este manifiesto](https://gist.github.com/supermafari007/bfa044dcec126d836bfea974e2a95cb3).

El archivo `SHA256SUMS.txt` de cada publicación permite verificar también el instalador manualmente con `Get-FileHash -Algorithm SHA256`.

## macOS Intel y Apple Silicon

Las dos ediciones comparten la misma interfaz y funciones, con ejecutables Swift nativos separados. Requieren macOS 26 Tahoe o posterior; Apple Silicon también se comprueba en macOS 27 Golden Gate.

| Tu Mac | Instalador 2.0.2 |
| --- | --- |
| Intel | [Descargar DMG Intel](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.0.2/Himnario_Adventista_macOS_Intel.dmg) |
| Apple Silicon, M1 o posterior | [Descargar DMG Apple Silicon](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.0.2/Himnario_Adventista_macOS_AppleSilicon.dmg) |

Abre el DMG y arrastra Himnario Adventista a Aplicaciones. Los recursos ya descargados se conservan. En una instalación nueva, la aplicación descarga la multimedia y permite elegir otro disco; reserva unos 8,6 GB libres temporalmente.

La aplicación inicia en modo ventana con los controles nativos de macOS. Puedes moverla desde la barra de título, redimensionarla desde los bordes y usar el botón verde o F11 para pantalla completa. Ayuda, información y actualizaciones están a la derecha. Se ha desactivado el arrastre HTML que producía imágenes flotantes.

Cada edición descarga únicamente su instalador oficial y verifica el SHA-256 de GitHub. No requiere iniciar sesión. La firma es ad hoc, sin notarización de Apple; macOS puede pedir autorizar su apertura en Ajustes del Sistema > Privacidad y seguridad.

La versión Intel supera las pruebas de ventana y reproducción en Tahoe. La animación de Spaces no se completa en el runner Intel y requiere comprobación adicional en un Mac físico. Apple Silicon supera también la entrada y salida de pantalla completa en Tahoe y Golden Gate.
