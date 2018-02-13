# Hustle: play movie files with sp33d

Hustle is a bash script used to search recursively in a directory for movie files and play them.

## Installation 

Simply put the bash script somewhere in $PATH and make it executable. Set the variable "path2dir" to the directory where you store your movie files. If you use another movie player program than vlc, change the variable "movieplayer" to the desired movie player. 

## Synopsis 

hustle [OPTIONS] SEARCHWORD

### Example 1 

`hustle mat`

will play the movie Matrix.(1999).720.YIFY...
if such a file exists in the directory specified by path2dir.

### Example 2  

`hustle -d /media/harddrive/movies/ -t 3 rob*1*9`

will play the movie Mr.Robot.S01E09.HDTV... if such a file exists in /media/harddrive/movies/
and was created less than 3 days ago.

