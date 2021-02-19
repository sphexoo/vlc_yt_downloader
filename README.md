# vlc_youtube_downloader
Download audio from any youtube video using a python script. 
The app uses VLC media players functionality for downloading audio from youtube.

1) prerequisites:  
- VLC Media Player
- Python 3
- Path to vlc.exe is added as Environment Variable named VLC_HOME (e.g. name = VLC_HOME; value = "C:\Program Files\VideoLAN\VLC\vlc.exe")
2) usage
- cmd: python downloader.py [-h] [--out <FILENAME>] [-verbose] url

|**positional argument**|**description**|  
|---|---|
|url|Specify youtube url to download audio from.|

|**argument**|**description**|  
|---|---|
|-h, -help|show this help message and exit|
|--out <FILENAME>|Specify name of output file.|
|-verbose|Show VLC media player GUI when downloading audio.|
|-no_url_check|Disable URL regex check. This may lead to unexpected behavior or corrupted downloads.|
