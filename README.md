# AutoTrim
A bash script uses [ffmpeg](https://github.com/FFmpeg/FFmpeg) to trim a video into titled orderd parts.
### Usage
``` bash
autotrim <video> <timestamps-textfile>
```
### Timestamps Example
##### This script uses REGEX to identify timestamps:
```
04:28 Introduction to Big-O
17:00) Dynamic and Static Arrays
0:27:40) Dynamic Array Code
(0:35:03 Linked Lists Introduction
(0:49:16) Doubly Linked List Code
(0:58:26) Stack Introduction
(1:09:40) Stack Implementation
(1:12:49) Stack Code
(1:15:58) Queue Introduction
(1:22:03) Queue Implementation
(1:27:26) Queue Code
```
## Example
Using the same text file above
```
autotrim "Data Structures and algos" "timestamps.text"
```
### Output
First It will ask You to enter a title for the new folder.
```
Enter a title:
```
And that's it.
```
01 Introduction to Big-O.mp4
02 Dynamic and Static Arrays.mp4
03 Dynamic Array Code.mp4
04 Linked Lists Introduction.mp4
05 Doubly Linked List Code.mp4
06 Stack Introduction.mp4
07 Stack Implementation.mp4
08 Stack Code.mp4
09 Queue Introduction.mp4
10 Queue Implementation.mp4
11 Queue Code.mp4
```

### Install
Just clone the repo and add the script to your path.
