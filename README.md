# Hustle

Hustle is a bash script used to quickly search recursively in a directory and play movie files. 

## Synopsis 

hustle [OPTIONS] [SEARCHWORD]

### Example 1 

`hustle mat`

will play the movie Matrix.(1999).720.YIFY...
if such a file exists in the directory specified by path2dir.

### Example 2  

`hustle -d /media/harddrive/movies/ -t 3 rob*1*9`

will play the movie Mr.Robot.S01E09.HDTV... if such a file exists in /media/harddrive/movies/
and was created less than 3 days ago.

