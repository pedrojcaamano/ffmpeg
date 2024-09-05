# Transformar un video FullHD (1920x1080) de 16500k de bitrate a un vídeo HD (1280x720) con 2000k de bitrate.
ffmpeg -i video_fullhd_16500k.mkv -vf scale=1280:720 -b:v 2000k video_HD_2000k.mkv
