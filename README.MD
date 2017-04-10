`mp3-split` is a command-line utility that splits a long MP3 file into smaller files and then tags them with the track name and track number.

It depends on Python 3, ffmpeg, eyeD3, and mp3info.

It was developed on Linux but may work on Windows if the dependencies are all in the PATH and if the script is called from the command line by `python` `mp3-split` `<arguments>` or `python3` `mp3-split` `<arguments>`

Also, you can try to use the WSL (Bash on Ubuntu on Windows)

Usage: `mp3-split` `MP3_FILE` `SPLIT_INFO`

Example `SPLIT_INFO` file:

01 Track Name 1 0:00<br>
02 The Second Track 3:26<br>
03 A Third Piece 26:01<br>
