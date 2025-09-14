# audio-fft-webapp
🎵 Analizador de Audio

Aplicación web 100 % cliente (sin backend) que permite subir un archivo de audio y obtener:

📊 Metadatos (nombre, duración, canales, frecuencia de muestreo, bitrate, bit depth si es WAV).

🌊 Forma de onda (con downsampling y rejilla).

📈 Espectro promedio (FFT/Welch en escala lineal o dB).

🎨 Espectrograma dinámico (STFT con ventana Hann y solape configurable, distintos mapas de color).

💾 Exportaciones:

CSV del espectro.

PNG del espectrograma.

Todo se procesa localmente en tu navegador usando Web Audio API y Canvas — no se sube ningún dato a servidores externos.

🚀 Demo

La aplicación funciona como GitHub Pages:
👉 [enlace a la demo](https://SalvaGaR.github.io/audio-fft-webapp/)

⚙️ Uso

Abre la página.

Sube un archivo de audio (MP3, WAV, FLAC, OGG, etc.).

Ajusta parámetros (FFT, solape, canal, mapa de color, rango dinámico).

Pulsa Analizar y explora los gráficos.

Opcional: descarga CSV o PNG.

🛠️ Tecnologías

HTML5 + CSS3 + JavaScript

Web Audio API para decodificar audio.

Canvas API para visualización.

Sin dependencias externas.

📄 Licencia

Puedes usar, modificar y compartir libremente este proyecto bajo la licencia que prefieras (MIT recomendada).
Sin dependencias externas.
