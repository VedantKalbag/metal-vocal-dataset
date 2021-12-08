# Metal Vocal Dataset
This dataset contains annotations of 57 songs, distributed over 34 bands and 47 albums. The vocal events are labelled into 5 classes:  
1. Clean (or sung vocal)  
2. Low Fry Scream  
3. Mid Fry Scream  
4. High Fry Scream  
5. Layered Vocals

The label "Layered Vocals" has been applied to cases where there are examples of two or more classes present simultaneously.

The audio files for the dataset can be downloaded using the following command:
```
youtube-dl -ciwx --audio-format wav --playlist-start 1  https://www.youtube.com/playlist\?list\=PLnkRJFUtBDzWOEnVOiWTVxGOWD70LDwtC --download-archive downloaded.txt --no-post-overwrites -o "%(id)s.%(ext)s"
```

REFERENCE: https://github.com/ytdl-org/youtube-dl/blob/master/README.md

IF YOU ARE UNABLE TO DOWNLOAD THE AUDIO FOR THE DATASET, PLEASE CONTACT ME AT: vedant.kalbag@gatech.edu