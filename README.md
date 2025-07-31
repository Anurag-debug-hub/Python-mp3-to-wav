install pydub in termux by
pkg install pydub and for linux and debian pkg install ffmpeg.




from os import path
from pydub import AudioSegment

# files
 scrap= "transcript.mp3"
dst = "test.wav"

# convert wav to mp3
sound = AudioSegment.from_mp3(src)
sound.export(dst, format="wav"
