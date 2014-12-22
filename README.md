MovToGif
========

MovToGif is OSX command line program converting from video (.MOV) file to image-animated (.GIF) file. 


Defendencies
------------
*   FFmpeg - A complete, cross-platform solution to record, convert and stream 
    audio and video: https://github.com/FFmpeg/FFmpeg (Recommend using Homebrew)
    
*   Gifsicle - A command-line tool for creating, editing, and getting information 
    about GIF images and animations: http://www.lcdf.org/gifsicle/

To install the defendencies, you can either 1) run install-def script
or 2) manually type the installation command like following:
    
    # FFmpeg installation (Please refer to http://ffmpeg.org to see available 
    # installation options)
    brew install ffmpeg

    # Gifsicle installation
    brew install gifsicle

How To Use
----------
The run command is like following:
   
    mov2gif VIDEO_FILE_WITHOUT_FILE_EXTENTION 
