Run the following command in this directory:
```
youtube-dl -ciwx --audio-format wav --playlist-start 1  https://www.youtube.com/playlist\?list\=PLnkRJFUtBDzWOEnVOiWTVxGOWD70LDwtC --download-archive downloaded.txt --no-post-overwrites -o "%(id)s.%(ext)s"
```