# Emociones_class

Hay dos datasets de música, usados por el paper de TAKASHIMA_2023. DEAM (manual_DEAM) y PMEmo (sobre PMEmo: https://doi.org/10.1145/3206025.3206037)

El dataset de DEAM, de 1,802 audios de 45 segundos con una frecuencia de muestreo de 44100 Hz; en este dataset se encuentra música variada de varios generos, y también audios de ruido como tráfico de autos o gente hablando, en manual_DEAM se detalla el dataset. Contiene valores de valencia y arousal cada 500 ms, del segundo 15 al 45.

muestra.ipynb extrae muestras de algun archivo .wav, de ejemplo se le aplica la FFT
En class está el clasificador.ipynb de emociones, y hay archivos csv agrupados por emoción. \n
decoder.ipynb covierte .mp3 a .wav
