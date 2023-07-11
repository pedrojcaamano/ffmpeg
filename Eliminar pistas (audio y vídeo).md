`ffmpeg -i video.mp4 -map 0:0 -map 0:2 solo_canal2_audio.mp4`
Si video.mp4 tiene un canal de vídeo y varios de audio, de esta forma nos quedamos sólo con el canal 0 de vídeo y con el canal 2 de audio. Para ver los canales contenido en el archivo basta un simple:
`ffmpeg -i video4.mp4`
