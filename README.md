# gopro-max-video-tools

The script is not polished for general use. It takes $1 as the source file, but you will need to edit the script for destination directory and naming convention. 

If there is interest I can update the script to accept params so it is a bit more 'polished' :)

## Multiple files

If you need to process multiple files in a directory, here's how I do it:

```
$ for FILE in GS*.360; do ./ffmpeg-convert.sh -i $FILE -o tmp; done
```
