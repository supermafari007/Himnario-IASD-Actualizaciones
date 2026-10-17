# Himnario Adventista para Windows

Descarga el instalador desde [la última versión estable](https://github.com/supermafari007/Himnario-IASD-Actualizaciones/releases/latest).

Este repositorio público distribuye los instaladores y sus sumas SHA-256. El código del programa se mantiene en un repositorio privado.

## Instalar

1. Descarga `Himnario_Adventista_WebView2_Setup.exe` desde Releases y ejecútalo en Windows x64.
2. Abre el Himnario y pulsa **Descargar ahora** para instalar los recursos multimedia.
3. Puedes usar **Elegir carpeta** para guardarlos en otro disco. Necesitas aproximadamente **8,6 GB libres** durante la descarga y extracción del paquete 1.0 de 4,21 GB.

El instalador es un único archivo; no necesita archivos `.bin` adicionales. Si falta WebView2, el instalador web oficial de Microsoft lo descarga. La aplicación incluye .NET y, una vez descargados los recursos, funciona sin conexión.

## Actualizaciones

**Buscar actualización** consulta las nuevas versiones estables de este repositorio y el manifiesto de recursos multimedia. El programa verifica el SHA-256 del instalador descargado antes de permitir su ejecución y conserva los recursos existentes.

Los recursos se descargan del [dataset oficial configurado en Hugging Face](https://huggingface.co/datasets/supermafari007/himnario-recursos). La versión multimedia se consulta en [este manifiesto](https://gist.github.com/supermafari007/bfa044dcec126d836bfea974e2a95cb3).

El archivo `SHA256SUMS.txt` de cada publicación permite verificar también el instalador manualmente con `Get-FileHash -Algorithm SHA256`.