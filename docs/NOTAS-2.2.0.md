# Himnario Adventista 2.2.0 · Windows y macOS

Esta versión está disponible para Windows moderno de 64 bits, Windows Legacy x86 y macOS Intel y Apple Silicon. Linux mantiene su entrega 2.1.9.

## Encontrar el himno que recuerdas

El buscador principal admite títulos y fragmentos de las letras de los 613 himnos. Puedes escribir una parte del himno aunque no recuerdes su nombre; las coincidencias muestran contexto. No exige las mismas tildes o puntuación. La casilla numérica acepta los himnos del 1 al 613 y formatos como 001 o 045; los valores fuera del catálogo se descartan.

Al comenzar una reproducción, el buscador se limpia para preparar el siguiente himno. Los favoritos, su orden y las listas existentes se conservan al actualizar. La apertura de archivos JSON valida su formato, tamaño, números y modos; los archivos importados no pueden establecer rutas de reproducción ni ejecutar órdenes.

## Himnos adicionales

Se incorporan los himnos nacionales de Argentina, Bolivia, Chile, Colombia, Ecuador, Paraguay, Perú y Uruguay, además de Aventureros, Conquistadores y Guías Mayores. En Windows moderno y macOS se encuentran en Temas y también por nombre, país o fragmento de letra. En Legacy se eligen desde Temas → Adicionales o buscando su nombre. Son un catálogo adicional a los 613 himnos, sin asignarles números nuevos ni incorporarlos a las listas numéricas.

El paquete **Himnos adicionales 1.0** se descarga o repara por separado: 50 láminas panorámicas, 11 pistas MP3 e iconos, aproximadamente 403 MB. Se ofrece cuando falta y no obliga a descargar otra vez las letras o la música ya instaladas. Cantado avanza las láminas según cada grabación; Solo letra permite avance manual. Al terminar regresa al menú o a la espera de la secundaria.

## Presentación y continuidad

Se mantienen los controles fijos, la ocultación por sesión, la minimización independiente y la detección de pantallas de la 2.1.9. Los himnos adicionales utilizan también la secundaria; los controles y el estado del operador se sincronizan con la reproducción. La ayuda visual se actualiza para explicar los elementos y las descargas actuales.

En Windows moderno, el instalador sigue siendo uno solo: **Himnario_Adventista_Windows_Setup.exe**. Conserva el perfil y la carpeta de instalación. Los recursos se verifican mediante SHA-256 y se instalan por componentes, con recuperación ante reemplazos incompletos. La firma de editor de Windows continúa pendiente; esta entrega no desactiva las protecciones del sistema.


## Windows Legacy 2.2.0

Instalador propio: **Himnario_Adventista_Windows_Legacy_x86_Setup.exe**, aproximadamente 9,2 MB, para XP SP3 x86 (SSE2), Vista SP2 y Windows 7 SP1/8/8.1. Incluye el motor de audio y no requiere .NET ni WebView2. Conserva los modos Solo letra, Instrumental y Cantado, la biblioteca y los favoritos anteriores.

Incorpora la búsqueda por fragmentos de los 613 himnos, la validación numérica y de archivos JSON, una guía actualizada y los once adicionales con sus láminas y MP3 sincronizados. El paquete adicional se ofrece cuando falta y se puede reparar sin descargar de nuevo la música. Los clientes anteriores conservan su canal de recursos.

La entrega se verificó en Windows actual, con instalación/reinstalación/desinstalación y auditoría de importaciones frente a XP SP3. No se repitió su ejecución en cada Windows antiguo. [Guía de Legacy](WINDOWS-LEGACY.md).


## macOS Intel y Apple Silicon 2.2.0

Las dos ediciones incorporan búsqueda por fragmentos de las letras, validación de la casilla 1–613/001–613, archivos JSON limitados a listas y favoritos, y el catálogo de ocho países y tres clubes. El paquete Himnos adicionales 1.0 se ofrece cuando falta y se puede reparar sin descargar de nuevo los otros recursos. Se conservan favoritos, listas y biblioteca.

- **Intel:** macOS Ventura, Sonoma, Sequoia y Tahoe.
- **Apple Silicon:** ejecutable nativo arm64 para M1 o posterior, desde Tahoe, Golden Gate y versiones posteriores compatibles.

Se mantienen los controles nativos, la pantalla completa al abrir, Cmd+O/Cmd+S, el panel fijo y la minimización independiente de las ventanas. Los adicionales funcionan tanto en la pantalla habitual como en la secundaria, con avance sincronizado en Cantado y manual en Solo letra. La guía refleja los elementos actuales del Mac.

Descarga el **DMG de tu procesador** y arrastra el Himnario a **Aplicaciones**. Los discos conservan el fondo musical, el icono de la unidad y las posiciones de la aplicación, Applications y LEEME. Cada edición dispone también de ZIP alternativo y archivo SHA-256.


### Revisión de mantenimiento de macOS

Se ha corregido la continuidad de las descargas del actualizador: las copias de distintas versiones se mantienen separadas y una descarga incompatible se renueva automáticamente, conservando siempre la verificación SHA-256. Se mantiene la versión **2.2.0** y sus funciones.

Si ya instalaste la primera entrega de macOS 2.2.0, descarga el DMG actual y reemplaza la aplicación en **Aplicaciones** para recibir esta corrección. Se conservan tus favoritos y recursos. El actualizador de una versión anterior conserva su comportamiento hasta instalar la revisión; si muestra un fallo de verificación, pulsa **Reintentar** o descarga el DMG directamente.
