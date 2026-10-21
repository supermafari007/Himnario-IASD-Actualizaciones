# Windows Legacy 2.1.3

Edición nativa de 32 bits para Windows XP SP3 (x86), Vista SP2 y Windows 7 SP1/8/8.1.
Requiere procesador con SSE2. Ofrece Solo letra, Instrumental y Cantado con letras
sincronizadas. No incluye reproducción de video ni activaciones ocultas.

## Instalar o actualizar

1. Cierra el Himnario Legacy.
2. Descarga y ejecuta [Himnario_Adventista_Windows_Legacy_x86_Setup.exe](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.1.3/Himnario_Adventista_Windows_Legacy_x86_Setup.exe).
3. La actualización conserva las preferencias y la biblioteca.

El instalador incluye el reproductor. No necesita .NET, WebView2 ni instalar VLC.
Windows actual conserva su instalador propio; ambas ediciones usan datos separados.

## Letras y música

Desde el primer inicio pulsa Descargar ahora, elige una biblioteca ya disponible
o importa desde USB el ZIP oficial para Windows Legacy.

Legacy consulta exclusivamente [version-windows-legacy.json](https://gist.githubusercontent.com/supermafari007/bfa044dcec126d836bfea974e2a95cb3/raw/version-windows-legacy.json).
El archivo version.json del mismo Gist sigue atendiendo a las ediciones actuales.
El paquete Legacy pesa 3.865.943.190 bytes (3,87 GB), con 3.950.762.430 bytes al extraer.
Reserva aproximadamente 8,0 GB libres durante la descarga e instalación.

[Descargar el ZIP Legacy para importar sin conexión](https://huggingface.co/datasets/supermafari007/himnario-recursos/resolve/main/Recursos_Multimedia_Himnario_1.0%20-%20Windows%20Legacy.zip?download=true).

Puedes pausar y continuar la descarga. Reparar Contenido Multimedia, dentro de
Buscar actualización, reinstala Letra y Musica y puede sustituir archivos
personalizados dentro de esas carpetas. Las otras carpetas no se modifican.

## Usar el himnario

Busca por número o título. Enter reproduce; Espacio pausa o continúa; las flechas
cambian de diapositiva; Esc regresa al menú; F11 alterna ventana y pantalla completa.
La ventana se arrastra desde su franja superior. El cursor se oculta durante la
reproducción después de tres segundos de inactividad. Se mantiene la lista de
reproducción y sus opciones de orden, mezcla, importación y exportación.

Las listas antiguas con modo 3 pasan a Cantado normal, conservando los himnos.

## Desinstalar

Usa el panel de programas o el acceso Desinstalar. Las bibliotecas existentes que
solo hayas seleccionado se conservan. Los recursos descargados y administrados
por Legacy y sus preferencias se retiran; también los archivos personalizados
dentro de sus carpetas de recursos. Los archivos exportados fuera se conservan.

## Verificación

Esta entrega se verifica en Windows anfitrión, con autopruebas y auditoría de las
importaciones frente a XP SP3. Esa auditoría no sustituye la ejecución y escucha
en cada sistema antiguo o máquina virtual.
