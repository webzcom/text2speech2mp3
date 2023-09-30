# TextToSpeech
This is simpleHTA application for reading text to speech using Microsoft's voice synth dll

Should run on any recent Windows installation.

Save .HTA file to your computer and double click to use. 

For conversion of the wave file to mp3, you'll need to download the ffmpeg.exe from github here:

Download the ffmpeg-master-latest-win64-gpl.zip file from https://github.com/BtbN/FFmpeg-Builds/releases

Copy the ffmpg.exe file into the text2speech2mp3 root folder.

Configure the variable, ffmpegPath = "ffmpeg.exe"

Just update the text-to-speech script with your ffmpeg installation path and you're good to go!

PS: There is one small issue I'm still working on. The two checkboxe options should be radio buttons as it is one or the other, not both. 

I will have to think about the options , U/I and user experience a little more before making the next update. 
