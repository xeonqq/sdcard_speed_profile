# sdcard_speed_profile
speed profile for different sd card

## The command used to test speed:
  - sudo hdparm -t /dev/mmcblk0 #test read speed
  - dd count=1k bs=1M if=/dev/zero of=/media/qq/WIMIUS/test.img #test write speed

## video recording requirement
    [While a single minute 1080p footage at the standard 30 frames per second requires only 130 MB, a 4K video at the same framerate will require a whopping 375 MB.] (https://9to5mac.com/2015/09/10/iphone-6s-4k-video-size/)
  - for 1080p write speed require: 2.16 MB/s
  - for 4k write speed require: 6.2 MB/s

## SD card brand
  - SanDisk Ultra 10 32 GB HC I
    * read: 66.79 MB/sec, write:  20,6 MB/s
  
  - APME Pro 128 GB HC I
    * read: 17.07 MB/sec, write: 15,1 MB/s
