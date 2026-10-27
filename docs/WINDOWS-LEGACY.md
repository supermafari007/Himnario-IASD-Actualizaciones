# Windows Legacy 2.1.8

Edición nativa de 32 bits para Windows XP SP3 (x86), Vista SP2 y Windows 7 SP1/8/8.1.
Requiere procesador con SSE2. Incluye Solo letra, Instrumental y Cantado con letras
sincronizadas. El instalador incorpora el reproductor; no requiere .NET, WebView2
ni instalar VLC. No incluye video ni modos ocultos.

## Instalar o actualizar

1. Cierra el Himnario Legacy.
2. Ejecuta [Himnario_Adventista_Windows_Legacy_x86_Setup.exe](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/download/v2.1.8/Himnario_Adventista_Windows_Legacy_x86_Setup.exe).
3. La actualización conserva biblioteca, favoritos y preferencias.

## Letras y música por componentes

El asistente descarga Letras, Cantado e Instrumental desde GitHub y permite elegir
qué actualizar o reparar. Reconoce los recursos del paquete completo anterior.
**Letras 2.0** se descarga en dos ZIP que el programa verifica e integra como un
solo componente, conservando la música no seleccionada. Indica el tamaño y el
espacio necesario para la selección y permite continuar una descarga interrumpida.

El canal de esta edición es [media-manifest-windows-legacy.json](https://github.com/supermafari007/Himnario-IASD-Recursos/blob/main/media-manifest-windows-legacy.json).
Puedes seleccionar una biblioteca existente o importar desde USB el ZIP completo
oficial Legacy 1.0. Ese ZIP conserva las letras originales; después se ofrece
su actualización a 2.0. Reparar vuelve a instalar solo los componentes marcados
y puede sustituir archivos personalizados dentro de ellos.

## Temas, sugerencias y listas

El catálogo contiene **613 himnos**. El botón de temas conserva las categorías y
añade búsquedas por necesidad u ocasión, como «un himno para terminar el culto».
Incluye accesos a Diezmo y Ofrendas, Bautismo, Santa Cena, Presentación de un niño,
Matrimonio y Funerales. Las sugerencias explican su relación con la letra y permiten
seleccionar, guardar en favoritos o añadir a la lista con **+**.

Favoritos se conserva entre aperturas y admite respaldo JSON compatible con las
otras ediciones. Recientes registra solo esta sesión y se borra al cerrar.
La guía del botón **?** se adapta a los controles actuales.

## Segunda pantalla

Configura el escritorio extendido en Windows antes de abrir el Himnario. El menú
permanece en la principal y la secundaria muestra la portada de espera; recibe
las letras al reproducir. El icono de monitor cambia el destino, y los controles
de la principal permiten avanzar, retroceder y detener. Las letras se adaptan al
lienzo panorámico. Minimizar el Himnario minimiza ambas ventanas; al restaurar
vuelven juntas. Con una pantalla se mantiene la reproducción habitual.

## Controles habituales

Enter reproduce; Espacio pausa o continúa; las flechas cambian de diapositiva;
Esc regresa al menú; F11 alterna ventana y pantalla completa. Arrastra la ventana
desde su franja superior. El cursor se oculta tras tres segundos de inactividad
durante la reproducción. Se conservan las opciones de listas, mezcla y respaldo.

## Desinstalar

Usa el panel de programas o Desinstalar. Las bibliotecas existentes que solo hayas
seleccionado se conservan. Los recursos descargados y administrados por Legacy y
sus preferencias se retiran, incluidos archivos personalizados dentro de esas
carpetas. Los documentos exportados fuera se conservan.

## Verificación de esta entrega

Se comprobó en Windows anfitrión la interfaz, reproducción, componentes y ciclo
de instalación/reinstalación/desinstalación, además de auditar las importaciones
de los binarios frente a XP SP3. No se repitió la ejecución en cada Windows antiguo.
