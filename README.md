This bash script uses ffmpeg to merge/replace an audio file with a pre-exisiting video files for all files in a folder on Linux based OS and Windows with wsl or cygwin
# Merge /Replace Audio 

## 1) Purpose
Sometimes you have a video file which has 

Case a) no audio inside it and you want to merge an external audio file to the video file in batch 

Case b) video file contains audio but you are not happy with it and want to replace the internal video with an external audio in batch 

## 2) Condition 

This script is made assuming the video file is in .mp4 format and audio file is in .aac format and both files have same name that are to merged except the extension

## 3) Requirements 

ffmpeg is installed , and bash is used

## 4) Command 

Paste the file in folder which contains all the video and audo files and  
make the  replaceaudio.sh file executable using `chmod +x replaceaudio.sh`

then simply run the script with `./replaceaudio.sh`

### the output will be stored in output folder in same directory

## 5) Hint
You can use this in Windows too by using wsl and installing ffmpeg in windows

You can use any extension video or audio that is supported by ffmpeg , just you will have to change .mp4 with your video extension in line 5 of script

for using audio other than aac you will have to replace .aac in line 9 with your audio file extension .



#tags batch replace audio , add audio to video , replace audio in whole folder , add .aac file to .mp4 file
