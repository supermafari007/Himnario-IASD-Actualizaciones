# Himnario Adventista — descargas y actualizaciones

Instaladores ligeros para **macOS Intel**, **macOS Apple Silicon** y **Windows x64**. Cada plataforma puede tener una versión distinta; elige la descarga que corresponda a tu equipo.

Este repositorio público distribuye instaladores y sumas SHA-256. El código fuente se mantiene en repositorios privados.

## Descargas por plataforma

| Plataforma | Versión disponible | Instalador |
| --- | --- | --- |
| macOS Intel (x86_64) | [2.0.2](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/tag/v2.0.2) | [Descargar DMG Intel](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.0.2/Himnario_Adventista_macOS_Intel.dmg) |
| macOS Apple Silicon (arm64; M1 o posterior) | [2.0.2](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/tag/v2.0.2) | [Descargar DMG Apple Silicon](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.0.2/Himnario_Adventista_macOS_AppleSilicon.dmg) |
| Windows x64 | [2.1.3](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/tag/v2.1.3) | [Descargar instalador Windows](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.1.3/Himnario_Adventista_Windows_Setup.exe) |

También puedes consultar el [historial de publicaciones](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases). Los títulos indican las plataformas incluidas en cada versión.

## Instalación en macOS — Intel y Apple Silicon

Las dos ediciones comparten la interfaz y las funciones, con ejecutables Swift nativos separados. Requieren macOS 26 Tahoe o posterior compatible con el equipo; Apple Silicon también se comprueba en macOS 27 Golden Gate.

1. Descarga el DMG de tu procesador.
2. Ábrelo y arrastra **Himnario Adventista** a **Aplicaciones**.
3. Abre el Himnario. Si faltan recursos, pulsa **Descargar ahora** o usa **Elegir carpeta** para guardarlos en otro disco.

Los recursos y preferencias existentes se conservan. La aplicación inicia en modo ventana, con controles nativos de macOS. Puedes moverla desde la barra de título, redimensionarla desde los bordes y solicitar pantalla completa con el botón verde o F11. Ayuda, información y actualizaciones están a la derecha. El arrastre HTML de letras y fondos está desactivado para evitar imágenes flotantes.

### Firma y comprobaciones de macOS

La firma es ad hoc, sin notarización de Apple. macOS puede pedir autorizar la apertura en **Ajustes del Sistema > Privacidad y seguridad**.

Intel supera las pruebas de ventana y reproducción en Tahoe. La máquina virtual Intel no completa la animación de Spaces; esa transición requiere comprobación adicional en un Mac físico. Apple Silicon supera también la entrada y salida de pantalla completa en Tahoe y Golden Gate.

## Instalación en Windows — x64

1. Descarga y ejecuta **Himnario_Adventista_Windows_Setup.exe**.
2. Abre el Himnario y descarga los recursos si faltan.
3. Puedes usar **Elegir carpeta** para guardarlos en otro disco.

El instalador es un único archivo y no necesita archivos `.bin` adicionales. Si falta WebView2, el instalador web oficial de Microsoft lo descarga. La aplicación incluye .NET. La instalación conserva los recursos existentes; la reparación manual puede reemplazar archivos multimedia personalizados.

En Windows, puedes mover la ventana desde el título o la franja superior entre los botones. F11 y el botón superior alternan la pantalla completa sin bordes y recuperan el tamaño y la posición anteriores. En **Buscar actualización**, la frase **Reparar Contenido Multimedia** abre el asistente del primer inicio: permite elegir carpeta, pausar, continuar o reintentar la descarga y volver al Himnario al terminar.

### Desinstalación en Windows

Instala **2.1.3 o posterior** para actualizar también el desinstalador. Al confirmar la desinstalación, se retiran el programa, sus recursos multimedia, las descargas temporales, las preferencias y las cachés. También se limpian las ubicaciones multimedia que el Himnario haya registrado en otros discos. Los archivos personalizados guardados dentro de las carpetas multimedia se eliminan.

Si el Himnario sigue abierto, un disco está desconectado o hay archivos bloqueados, se debe resolver antes de completar la desinstalación. Las actualizaciones normales conservan los recursos existentes.

## Recursos multimedia — letras, música y videos

Los instaladores no incluyen el paquete multimedia. La aplicación lo descarga del [dataset configurado en Hugging Face](https://huggingface.co/datasets/supermafari007/himnario-recursos) y consulta su versión en el [manifiesto multimedia](https://gist.github.com/supermafari007/bfa044dcec126d836bfea974e2a95cb3).

El paquete 1.0 pesa **4,21 GB**. Reserva aproximadamente **8,6 GB libres** durante la descarga y extracción. Una vez instalados los recursos, puedes reproducirlos sin conexión.

## Actualizaciones — programa y contenido multimedia

**Buscar actualización** consulta las publicaciones del programa y el manifiesto multimedia. Cada edición selecciona su instalador correspondiente y verifica su integridad. Actualizar el programa conserva la multimedia existente.

Las notas usan un encabezado general y secciones por plataforma. Una publicación que solo contiene Windows se identifica como Windows; las publicaciones compartidas indican las arquitecturas de macOS que realmente incluyen.

## Verificación de descargas — SHA-256

Cada publicación incluye las sumas de sus archivos: **SHA256SUMS.txt** para Windows, **SHA256SUMS-macOS-Intel.txt** para Intel y **SHA256SUMS-macOS-AppleSilicon.txt** para Apple Silicon, según las ediciones disponibles.

En Windows puedes comprobar un archivo con `Get-FileHash -Algorithm SHA256`. En macOS puedes usar `shasum -a 256`.