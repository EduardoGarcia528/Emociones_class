# Emociones_class

El dataset de música usado por el paper de TAKASHIMA_2023 se llama DEAM (manual_DEAM)

El dataset de DEAM, de 1,802 audios de 45 segundos con una frecuencia de muestreo de 44100 Hz; en este dataset se encuentra música variada de varios generos, y también audios de ruido como tráfico de autos o gente hablando, en manual_DEAM se detalla el dataset. Contiene valores de valencia y arousal cada 500 ms, del segundo 15 al 45.

muestra.ipynb extrae muestras de algun archivo .wav, de ejemplo se le aplica la FFT
En class está el clasificador.ipynb de emociones, y hay archivos csv agrupados por emoción.
Decoder.ipynb covierte .mp3 a .wav
