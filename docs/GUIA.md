# Guía de instalación y uso

[← Volver a las descargas](../README.md#descargas) · [Preguntas frecuentes](AYUDA.md)

Elige primero el instalador desde la portada. Esta guía reúne los detalles de instalación, actualización, reparación y limpieza de cada sistema.

<a id="instalar-windows"></a>

## Instalación en Windows — x64

1. Descarga y ejecuta **Himnario_Adventista_Windows_Setup.exe**.
2. Abre el Himnario y descarga los recursos si faltan.
3. Puedes usar **Elegir carpeta** para guardarlos en otro disco.

El instalador es un único archivo y no necesita archivos `.bin` adicionales. Si falta WebView2, el instalador web oficial de Microsoft lo descarga. La aplicación incluye .NET. La instalación conserva los recursos existentes; la reparación manual puede reemplazar archivos multimedia personalizados.

En Windows, puedes mover la ventana desde el título o la franja superior entre los botones. F11 y el botón superior alternan la pantalla completa sin bordes y recuperan el tamaño y la posición anteriores. En **Buscar actualización**, la frase **Reparar Contenido Multimedia** abre el asistente del primer inicio: permite elegir carpeta, pausar, continuar o reintentar la descarga y volver al Himnario al terminar.

### Novedades de Windows 2.1.7

La edición para Windows 10/11 de 64 bits incorpora **Favoritos**, **Recientes** de la sesión y una guía visual renovada al pulsar **?**. El corazón guarda o retira favoritos; el signo **+** permite añadir himnos a la lista de reproducción. Puedes guardar y recuperar tus favoritos desde **Respaldar favoritos**. Recientes se borra al cerrar el programa.

Abre **Buscar actualización** para recibir la 2.1.7. La actualización conserva tus recursos multimedia y preferencias.

### Desinstalación en Windows

Instala **2.1.3 o posterior** para actualizar también el desinstalador. Al confirmar la desinstalación, se retiran el programa, sus recursos multimedia, las descargas temporales, las preferencias y las cachés. También se limpian las ubicaciones multimedia que el Himnario haya registrado en otros discos. Los archivos personalizados guardados dentro de las carpetas multimedia se eliminan.

Si el Himnario sigue abierto, un disco está desconectado o hay archivos bloqueados, se debe resolver antes de completar la desinstalación. Las actualizaciones normales conservan los recursos existentes.

<a id="instalar-windows-legacy"></a>

## Instalación en Windows Legacy — XP/Vista/7/8

Descarga **Himnario_Adventista_Windows_Legacy_x86_Setup.exe** desde la publicación
2.1.6. No requiere .NET, WebView2 ni instalar VLC. XP requiere SP3 de 32 bits;
Vista requiere SP2 y Windows 7, SP1. El procesador debe admitir SSE2.

Esta edición conserva Solo letra, Instrumental y Cantado; no reproduce videos.
Descarga un paquete propio de 3,87 GB y consulta un manifiesto exclusivo. Las
ediciones actuales mantienen sus recursos completos.

Consulta la [guía de Windows Legacy](WINDOWS-LEGACY.md) para importar desde USB,
reparar, actualizar o desinstalar. Actualizar conserva biblioteca y preferencias.

<a id="instalar-macos"></a>

## Instalación en macOS — Intel y Apple Silicon

Elige la edición que corresponda a tu Mac. Ambas ofrecen las mismas funciones del Himnario.

| Edición | Versiones compatibles de macOS |
| --- | --- |
| **Intel** | Ventura, Sonoma, Sequoia y Tahoe |
| **Apple Silicon · M1 o posterior** | Tahoe, Golden Gate y versiones posteriores compatibles con tu Mac |

1. Descarga el DMG de tu procesador.
2. Ábrelo y arrastra **Himnario Adventista** a **Aplicaciones**.
3. Abre el Himnario. Si faltan recursos, pulsa **Descargar ahora** o usa **Elegir carpeta** para guardarlos en otro disco.

Los recursos y preferencias existentes se conservan. La aplicación inicia en pantalla completa nativa, con controles de macOS. Usa el botón verde, F11 o Ctrl+Cmd+F para volver al modo ventana; allí puedes moverla desde la barra de título y redimensionarla desde los bordes. Ayuda, información y actualizaciones están a la derecha. El arrastre HTML de letras y fondos está desactivado para evitar imágenes flotantes.

La versión vigente de macOS es la **2.1.6**, disponible desde Buscar actualización. Abre el DMG descargado y arrastra la app al acceso Applications para reemplazar la copia de Aplicaciones; se conservan recursos y preferencias.

### Reparación y desinstalación en macOS

Desde **Buscar actualización > Reparar Contenido Multimedia** puedes volver a descargar el paquete oficial aunque no haya una nueva versión. El asistente pide confirmación, permite elegir carpeta, pausar, continuar y reintentar; al terminar, pulsa **Volver al Himnario**. La reparación detiene la reproducción y conserva los recursos anteriores si la instalación falla.

Para retirar la aplicación y sus datos, abre el menú del Himnario en la barra de macOS y selecciona **Desinstalar Himnario…**. Tras confirmar, se eliminan los recursos, las descargas temporales, los instaladores, las preferencias y los datos web de la aplicación; la app se envía a la Papelera. También se limpian las ubicaciones multimedia registradas en otros discos. Conecta esos discos antes de desinstalar. Los archivos personalizados guardados dentro de Letra, Musica o Video Cantado se eliminan; los documentos y listas exportados fuera de esas carpetas se conservan.

La limpieza completa requiere usar el menú del Himnario. Mover únicamente la app a la Papelera desde Finder conserva sus datos. Las actualizaciones normales conservan los recursos y preferencias.

### Primera apertura e instalador de macOS

La firma es ad hoc, sin notarización de Apple. Si macOS bloquea la apertura, consulta [qué hacer al abrir la aplicación por primera vez](AYUDA.md#macos-no-abre) y la [guía de Apple](https://support.apple.com/es-cl/guide/mac-help/mh40616/mac).


Los DMG incluyen fondo musical, acceso a Applications e instrucciones LEEME_MAC.txt. La unidad montada utiliza el icono del Himnario. Arrastra la aplicación a Applications, expulsa la unidad y abre la copia instalada en Aplicaciones.

<a id="instalar-linux"></a>

## Instalación en Linux — Intel/AMD64 y ARM64

Para **Ubuntu 24.04 o posterior, Linux Mint 22 o posterior y Debian 13**. Descarga AMD64 si tu procesador es Intel/AMD, o ARM64 si es ARM. Abre el archivo DEB con el instalador de software de tu distribución. También puedes instalarlo desde la carpeta de descarga con:

    sudo apt install ./Himnario_Adventista_Linux_AMD64.deb

Usa el nombre ARM64 si corresponde. El instalador del Himnario pesa aproximadamente **1,3 MB**; el gestor de paquetes descarga GTK, WebKitGTK y decodificadores nativos si faltan. La primera instalación necesita conexión.

Abre **Himnario Adventista** desde el menú. Al primer inicio, pulsa **Descargar ahora** para integrar la multimedia o **Elegir carpeta** para guardarla en otro disco. La ventana usa los botones propios del Himnario, como Windows; F11 alterna pantalla completa. En modo ventana se puede mover desde el título o la franja superior y redimensionar desde los bordes.

**Buscar actualización > Reparar Contenido Multimedia** abre el mismo asistente del primer inicio, con confirmación, carpeta, pausa, reanudación y reintento. Al terminar, pulsa **Volver al Himnario**. Cada procesador recibe únicamente su paquete Linux, verificado con SHA-256.

El paquete instala un perfil AppArmor exclusivo de `/usr/bin/himnario-adventista`, autorizado para permitir el aislamiento de WebKit en Ubuntu. No altera las restricciones generales del sistema. Se retira al desinstalar y se elimina al purgar el paquete.

### Desinstalación en Linux

Usa **Información > Desinstalar y eliminar datos…** y confirma. Se eliminan recursos, descargas, preferencias, cachés y las carpetas multimedia registradas; después se solicita la autorización nativa para retirar el paquete. Conecta los discos usados antes de desinstalar. También se eliminan archivos personalizados dentro de Letra, Musica y Video Cantado; las listas exportadas fuera de las carpetas del Himnario se conservan.

Eliminar solo el paquete desde el gestor de software conserva los datos del usuario. Para una limpieza completa usa primero la opción del Himnario. Las actualizaciones normales conservan recursos y preferencias.

## Recursos multimedia — letras, música y videos

Los instaladores no incluyen el paquete multimedia. La aplicación lo descarga del [dataset configurado en Hugging Face](https://huggingface.co/datasets/supermafari007/himnario-recursos) y consulta su versión en el [manifiesto multimedia](https://gist.github.com/supermafari007/bfa044dcec126d836bfea974e2a95cb3).

Las ediciones actuales usan el paquete 1.0 de **4,21 GB**. Reserva aproximadamente **8,6 GB libres** durante la descarga y extracción. Windows Legacy usa un paquete separado de **3,87 GB**, necesita unos **8,0 GB libres** y solo incluye letras y música. Una vez instalados los recursos, puedes reproducirlos sin conexión.

## Actualizaciones — programa y contenido multimedia

El Himnario comprueba las actualizaciones al iniciar y desde **Buscar actualización**. Consulta las publicaciones del programa y el manifiesto multimedia. Cada edición selecciona su instalador correspondiente y verifica su integridad. Actualizar el programa conserva la multimedia existente.

Si eliges **Más tarde**, al cerrar se prepara la actualización pendiente. En macOS se abre el DMG verificado para que arrastres la app a Aplicaciones; cada procesador recibe su propia edición. Si solo hay recursos multimedia pendientes, se instalan antes de cerrar.

Las notas usan un encabezado general y secciones por plataforma. Una publicación que solo contiene Windows se identifica como Windows; las publicaciones compartidas indican las plataformas y arquitecturas que realmente incluyen.

<a id="verificar-descargas"></a>

## Verificación de descargas — SHA-256

Cada publicación incluye las sumas de sus archivos: **SHA256SUMS.txt** para Windows, **SHA256SUMS-Windows-Legacy-x86.txt** para Windows Legacy, **SHA256SUMS-macOS-Intel.txt** para macOS Intel, **SHA256SUMS-macOS-AppleSilicon.txt** para macOS Apple Silicon, **SHA256SUMS-Linux-AMD64.txt** y **SHA256SUMS-Linux-ARM64.txt** para Linux, según las ediciones disponibles.

En Windows puedes comprobar un archivo con `Get-FileHash -Algorithm SHA256`. En macOS puedes usar `shasum -a 256` y en Linux `sha256sum`.
