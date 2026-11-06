<p align="center"><img src="images/logo.png" alt="" width="96"></p>

<h1 align="center">VeloxDM</h1>

<p align="center">Gestor de descargas con segmentación dinámica, colas, planificador, video, BitTorrent y extensión de navegador.</p>

<p align="center"><a href="https://sotomontes.com/#veloxdm"><b>Ver en sotomontes.com</b></a></p>

**Autor:** Sebastian Sotomontes · © 2026

> Esta página es solo una presentación del proyecto. El código y los instaladores son privados.

---

<p align="center"><img src="images/banner.png" alt="" width="100%"></p>

## Qué es

VeloxDM es un gestor de descargas para Windows pensado para bajar archivos grandes sin perder el progreso. Divide cada descarga en varias conexiones que trabajan en paralelo y, cuando una termina, ayuda a la más lenta. También baja vídeo, torrents y paquetes de enlaces, y se integra con tu navegador para capturar las descargas sin que tengas que copiar nada.

## Cómo se usa

1. Instala VeloxDM y añade la extensión a tu navegador. Desde ese momento las descargas se capturan solas, con su sesión, cookies y referer.
2. Para bajar algo a mano, pulsa **Añadir URL**, pega el enlace y elige carpeta y categoría. En los vídeos eliges también la calidad.
3. Sigue el avance en la ventana principal. Al abrir una descarga ves cómo progresa cada conexión y puedes pausarla o cambiar su velocidad.
4. Agrupa las descargas en **colas** y abre el **planificador** para decidir qué días y a qué horas corren, y qué hacer al terminar.
5. Para muchos enlaces, pega un texto o una página en el **capturador de enlaces**: revisa cuáles siguen vivos y los agrupa en paquetes con su carpeta y contraseña.
6. En **Opciones** configuras límites, cuota de datos, velocidad por horario, proxy, sonidos y control desde el móvil.

<p align="center"><img src="images/principal.png" alt="Ventana principal" width="100%"><br><sub>Ventana principal</sub></p>

<p align="center"><img src="images/segmentos.png" alt="Progreso por conexiones" width="100%"><br><sub>Progreso por conexiones</sub></p>

<p align="center"><img src="images/video.png" alt="Elegir calidad de un vídeo" width="100%"><br><sub>Elegir calidad de un vídeo</sub></p>

<p align="center"><img src="images/opciones.png" alt="Límites y horarios" width="100%"><br><sub>Límites y horarios</sub></p>

## Funciones

- **HTTP, HTTPS y FTP** con hasta 32 conexiones y segmentación dinámica.
- **Vídeo** de YouTube y más de 1000 sitios, con calidad a elegir, MP4 o solo audio, además de HLS y DASH.
- **BitTorrent**: enlaces magnet y archivos `.torrent`, con selección de archivos.
- **Extensión de navegador** para Chrome, Edge, Brave, Vivaldi y Opera.
- **Colas y planificador** con días, horas y acciones al terminar.
- **Capturador de enlaces** y paquetes con carpeta y contraseña.
- **Después de descargar**: verificación de sumas, descompresión y antivirus.
- **Control desde el móvil** en la red local con PIN.

## Detalles

- Reanuda tras cortes de internet, reinicios o apagones.
- Hasta 32 conexiones por archivo con segmentación dinámica.
- Los archivos por partes se descomprimen solos al terminar, probando tu lista de contraseñas.
- Si un sitio pide una verificación, VeloxDM abre la página para que la resuelvas tú; nada se salta.
- Línea de comandos para usarlo desde scripts.

## Tecnologías

C# · .NET 10 · WebView2

**Créditos:** usa yt-dlp, MonoTorrent y ffmpeg.

<sub>© 2026 Sebastian Sotomontes. Todos los derechos reservados.</sub>
