Cortar (extraer) 'X' segundos desde el principio de un audio:

`ffmpeg -i Audio.mp3 -t [duración_del_corte] AudioCortado.mp3`

Cortar (extraer) una parte intermedia de un audio:

`ffmpeg -i Audio.mp3 -ss [segundo _de_inicio] -t [duración_del_corte] AudioCortado.mp3`

Cortar (extraer) la parte final de un audio:

`ffmpeg -i Audio.mp3 -ss [segundo _de_inicio] AudioCortado.mp3`

Por defecto, si no pones el parámetro -t, ffmpeg entiende que es hasta el final del audio.
