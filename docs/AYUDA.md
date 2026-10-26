# Ayuda y preguntas frecuentes

[← Volver a las descargas](../README.md#descargas) · [Guía de instalación](GUIA.md)

## ¿Cuál es la versión para mi equipo?

La [tabla de descargas](../README.md#descargas) indica el sistema, el procesador y la versión disponible de cada edición.

- **Windows:** la edición es para Intel/AMD de 64 bits. Compruébalo en **Configuración > Sistema > Acerca de > Tipo de sistema**. Para XP/Vista/7/8 está disponible Windows Legacy de 32 bits. No hay instalador nativo de Windows ARM.
- **Mac:** en **Apple > Acerca de esta Mac**, revisa tu procesador. Elige **Mac Intel** para macOS Ventura, Sonoma, Sequoia o Tahoe. Si tienes un **chip M1 o posterior**, elige **Apple Silicon**, compatible desde macOS Tahoe, incluido Golden Gate y versiones posteriores compatibles con tu Mac.
- **Linux:** AMD64 es para Intel/AMD de 64 bits y ARM64 es para ARM de 64 bits. El comando `uname -m` permite distinguir `x86_64` de `aarch64`.

## ¿Necesito una cuenta de GitHub?

Puedes descargar e instalar el Himnario sin iniciar sesión. Para abrir una consulta o informar un problema en este repositorio, GitHub sí solicita una cuenta.

## Windows muestra una alerta de SmartScreen

El instalador actual de Windows no está firmado con un certificado de editor confiable. SmartScreen puede advertir que la aplicación es desconocida porque aún no tiene suficiente reputación; ese aviso no equivale a una detección de malware. Comprueba que la descarga viene de este repositorio y verifica su SHA-256. No desactives las protecciones del sistema para instalarla.

Una firma válida identifica al editor, pero tampoco garantiza eliminar inmediatamente la alerta de un archivo nuevo. Consulta la [explicación de Microsoft](https://learn.microsoft.com/windows/apps/package-and-deploy/smartscreen-reputation).

## ¿Por qué el instalador es pequeño?

El programa y los recursos multimedia se distribuyen por separado. Primero instalas la aplicación y después ella descarga e integra las letras, la música y los videos. El tamaño vigente de cada instalador aparece en la tabla de descargas. Cada sistema puede descargar componentes adicionales si hacen falta.

## ¿Cuánto espacio y conexión necesito?

**Windows 2.1.9 y macOS 2.1.8** muestran el tamaño según los componentes seleccionados y comprueba el espacio para descargar e instalar. Letras 2.0 se ofrece en dos partes, gestionadas automáticamente; no necesitas renovar la música que ya tienes.

**Linux 2.1.7:** el paquete multimedia pesa **4,21 GB**. Reserva aproximadamente **8,6 GB libres** durante la descarga y extracción. Haz esta descarga antes de necesitar el Himnario en una reunión; su duración depende de tu conexión. Puedes pausarla y continuarla desde el asistente.

## ¿Funciona sin Internet?

Sí. Una vez integrados los recursos, puedes mostrar las letras y reproducir la música y los videos descargados sin conexión. Internet se necesita para descargar recursos, repararlos o buscar nuevas versiones.

## ¿Puedo guardar los recursos en otro disco?

Sí. Pulsa **Elegir carpeta** en el asistente. Usa un disco con espacio suficiente y mantenlo conectado cuando utilices el Himnario. La aplicación recuerda la ubicación elegida.

## La descarga se interrumpió

Vuelve al asistente y utiliza **Continuar descarga** o **Reintentar descarga**, según el mensaje que aparezca. El programa reutiliza el avance guardado cuando el servidor lo permite. Comprueba también la conexión y el espacio disponible en el disco elegido.

## Faltan letras, música o videos

Abre **Buscar actualización > Reparar Contenido Multimedia**. Confirma la reparación, elige la carpeta si lo necesitas y espera a que se integre el paquete. Al finalizar, pulsa **Volver al Himnario**.

En Windows 2.1.9 y macOS 2.1.8 marca solo los componentes que deseas reparar. Los no seleccionados se conservan. La biblioteca instalada desde el paquete anterior se reconoce sin descargarla nuevamente.

La reparación reinstala el contenido oficial y puede reemplazar archivos personalizados guardados dentro de las carpetas multimedia. Guarda una copia de esos archivos si deseas conservarlos.

## ¿Cómo proyecto sin mostrar el menú al público?

En **Windows 2.1.9 y macOS 2.1.8**, conecta otra pantalla y configúrala como escritorio extendido desde los ajustes de pantallas de tu sistema. Al abrir, la principal definida por el sistema conserva el menú y la secundaria muestra la portada de espera. Pulsa el icono de monitor para cambiar el destino. Al lanzar un himno, la secundaria recibe la reproducción; al detenerlo vuelve a la portada. Con una sola pantalla funciona la vista habitual.

### Control de la segunda pantalla en Windows 2.1.9

El panel fijo muestra el estado y el himno que se está reproduciendo. Puedes avanzar, retroceder, detener, ocultar la letra o minimizar la secundaria. **Ocultar letra** deja la portada de espera y mantiene el audio; sigue activado aunque selecciones otros himnos, hasta que lo pulses otra vez. Al cerrar y volver a abrir, la letra empieza visible. Cada ventana se minimiza por separado.

Puedes conectar o desconectar una pantalla con el programa abierto. Si Windows está en Duplicar con dos salidas activas, el Himnario intenta extenderlas temporalmente. Al salir recupera la configuración inicial si las pantallas siguen conectadas y no has cambiado tú la distribución. Si el controlador no lo permite, configura **Extender estas pantallas** en Windows. macOS 2.1.8 mantiene su comportamiento anterior.

## ¿Cómo busco un himno para una ocasión?

En **Windows 2.1.9 y macOS 2.1.8**, abre el botón de temas y elige **Buscar un himno**. Escribe una necesidad, un título o frases como «término del culto»; también puedes usar los accesos de ceremonias y servicios. Las sugerencias explican su relación con la letra y permiten guardar favoritos o preparar la lista. La X limpia la consulta. Al reproducir, el panel vuelve al inicio.

<a id="macos-no-abre"></a>

## macOS bloquea la primera apertura

Las ediciones actuales tienen firma ad hoc y **no están notarizadas por Apple**. Después de intentar abrir la aplicación descargada desde este repositorio, revisa el aviso de **Configuración del Sistema / Ajustes del Sistema > Privacidad y seguridad**. Si decides autorizar esta aplicación, macOS ofrece **Abrir de todos modos** o **Abrir igualmente**, según su versión e idioma.

Sigue la [guía de Apple para abrir una app de un desarrollador desconocido](https://support.apple.com/es-cl/guide/mac-help/mh40616/mac). Esta autorización corresponde a la aplicación concreta.

Comprueba además que elegiste el DMG de tu procesador y que utilizas una versión compatible de macOS.

## ¿Cómo instalo el archivo DEB en Linux?

Ábrelo con el instalador de software de tu distribución. Si necesitas usar la terminal, abre una en la carpeta donde descargaste el archivo:

```sh
# Para Intel / AMD de 64 bits:
sudo apt install ./Himnario_Adventista_Linux_AMD64.deb

# Para ARM de 64 bits:
sudo apt install ./Himnario_Adventista_Linux_ARM64.deb
```

Ejecuta solo la línea de tu procesador. El gestor de paquetes obtiene las dependencias que falten. Consulta la [compatibilidad y los detalles de Linux](GUIA.md#instalar-linux).

## Linux suena bajo o sube de golpe al salir con Esc

Los paquetes actuales de **Linux 2.1.3** incluyen una corrección de sonido: mantienen el nivel original del archivo, respetan el volumen y la amplificación elegidos en Linux y evitan el salto de volumen al interrumpir un himno con Esc. También corrigen el cambio rápido entre himnos.

Si descargaste un instalador anterior, cierra el Himnario y vuelve a descargar el [DEB de tu procesador](../README.md#descargas). Reinstálalo con una de estas líneas desde la carpeta de descarga:

```sh
# Intel / AMD de 64 bits:
sudo apt install --reinstall ./Himnario_Adventista_Linux_AMD64.deb

# ARM de 64 bits:
sudo apt install --reinstall ./Himnario_Adventista_Linux_ARM64.deb
```

Ejecuta solo la línea de tu procesador. **La versión sigue siendo 2.1.3 y se conservan los recursos y preferencias.** No necesitas reparar ni volver a descargar el contenido multimedia para aplicar esta corrección.

## Linux 2.1.3 muestra un error al comprobar actualizaciones

La descarga actual de **Linux 2.1.3** incluye la corrección del comprobador de versiones. Si instalaste el paquete anterior y aparece el mensaje `select_release is not defined`, cierra el Himnario y descarga de nuevo el DEB de tu procesador desde la [portada](../README.md#descargas).

Reinstala el paquete corregido. Por ejemplo, desde la carpeta de descarga:

```sh
# Para Intel / AMD de 64 bits:
sudo apt install --reinstall ./Himnario_Adventista_Linux_AMD64.deb

# Para ARM de 64 bits:
sudo apt install --reinstall ./Himnario_Adventista_Linux_ARM64.deb
```

Ejecuta solo la línea de tu procesador. El programa conserva la versión **2.1.3**, tus recursos y tus preferencias. Después de reinstalar, vuelve a abrirlo y pulsa **Buscar actualización**.

## ¿Qué pasa con mis recursos al actualizar?

Una actualización normal conserva tus recursos y preferencias. Usa **Buscar actualización** desde el propio Himnario para obtener la edición de tu sistema y procesador. En macOS, la actualización abre el DMG verificado para que sustituyas la app en Aplicaciones.

## ¿Cómo cambio entre ventana y pantalla completa?

Usa **F11**; en algunos teclados puede requerir **Fn + F11**. Windows y Linux también tienen un botón de pantalla completa en la parte superior. En macOS puedes usar el botón verde de la ventana. En modo ventana puedes moverla y cambiar su tamaño desde los bordes.

<a id="desinstalar"></a>

## ¿Cómo desinstalo el programa y sus recursos?

| Sistema | Opción de limpieza completa |
| --- | --- |
| Windows | Usa el desinstalador de Himnario Adventista, versión 2.1.3 o posterior, desde las aplicaciones instaladas de Windows. |
| macOS | En la barra de menús, abre el menú del Himnario y elige **Desinstalar Himnario…**. |
| Linux | Abre **Información > Desinstalar y eliminar datos…** dentro del Himnario. |

Conecta los discos donde hayas guardado recursos antes de desinstalar. Se eliminan las carpetas multimedia registradas, incluidos los archivos personalizados guardados dentro de ellas; las listas exportadas fuera de las carpetas del Himnario se conservan.

En macOS, mover solo la app a la Papelera conserva sus datos. En Linux, retirar solo el paquete con el gestor de software también conserva los datos del usuario. Consulta los [detalles de limpieza por sistema](GUIA.md).

## ¿Qué archivo elijo en la página de versiones?

Utiliza los enlaces de la [portada de descargas](../README.md#descargas): llevan directamente al **EXE de Windows**, al **DMG del Mac correspondiente** o al **DEB de Linux correspondiente**. Las publicaciones incluyen también archivos de verificación y otros formatos para distribución y actualización.

## ¿Cómo compruebo que una descarga está íntegra?

Cada versión publica archivos **SHA256SUMS** para sus instaladores. La aplicación también verifica sus propias descargas. Si deseas comprobar un archivo manualmente, consulta [Verificación de descargas — SHA-256](GUIA.md#verificar-descargas).

## ¿Dónde pido ayuda?

[Abre una consulta o informa un problema](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/issues/new/choose). Indica la edición, la versión del Himnario, el sistema operativo y qué ocurre. Los formularios te ayudarán a reunir esos datos.
