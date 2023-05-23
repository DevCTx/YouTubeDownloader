# YouTube Downloader 
#### developed in Python during my online class with [www.CodeAvecJonathan.com](https://codeavecjonathan.com/)

#### Needs the ffmpeg audio/video codecs installed on your system : https://ffmpeg.org/download.html
FFmpeg is the leading multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created.
https://ffmpeg.org/

#### and the useful ffmpeg-python module from https://github.com/kkroening/ffmpeg-python
FFmpeg is extremely powerful, but its command-line interface gets really complicated rather quickly.
If you're like me and find Python to be powerful and readable, it's easier with ffmpeg-python.

## Sample 
'''commandline
python .\YouTubeDownloader.py
Video to download : https://www.youtube.com/watch?v=FARAVxy0Z8c
Title : MISSION: IMPOSSIBLE | Behind the Scenes ( 181223 views )

What kind of stream would you like to download ?
1 - standard audio-video stream
2 - video stream only
3 - audio stream only
4 - personalized audio-video stream
Enter your choice : 4
audio = True / video = True / personalized
                                          
Select a video resolution ...             
1 - 1080p video/mp4 (itag:137)
2 - 720p video/mp4 (itag:136) 
3 - 480p video/mp4 (itag:135) 
4 - 360p video/mp4 (itag:134) 
5 - 240p video/mp4 (itag:133) 
6 - 144p video/mp4 (itag:160) 
Enter your choice : 1         

Downloading 1080p video/mp4 (itag:137)... 100 % done !
                                                      
.. then an audio rate ...                             
1 - 128kbps audio/mp4 (itag:140)
2 - 48kbps audio/mp4 (itag:139) 
Enter your choice : 1

Downloading 128kbps audio/mp4 (itag:140)... 100 % done !

... and the magic appears ...

Here it is :  .\YouTubeDownloader\MISSION IMPOSSIBLE  Behind the Scenes.mp4
'''
