# Trouble shooting

### This file contains all the problems I ecountered.
I give brief descriptions of  the problem ecountered,
and my solution/opinion of each.

## Hardware

### Raspberri Pi 3b

Due to a limited budget I used a raspberry pi 3b, in all examples
of similar projects a raspberry pi 4 was used instead. I believe
this to be something to consider but not significant enough to
halt the entire project or cause any hugely substantial errors
beside having to use a 32-bit os instead of 64-bit. 

### Iphone SE

I used my old iphone SE for this project but all the examples of
projects similar to mine used an ipad pro. I believe this could
have caused a slight error for margin but if it did it's quite
infinitesimal. 

## Software

When prompted for a password to access the SSH key I entered the
password to the raspberry pi. After 10 failed attempts I reset the
password on the raspberry pi, but this did not result in progress. So
I removed the password prompt from the ssh key(despite the lowered
security). I was still unable to connect to the ssh key. I believe I
may need to reflash the raspberry pi to make a new ssh; this may not
be the case but this is the quickest route I see working. I tried
accessing the ssh key from another device to no avail.

### Linux Mint

I originally wanted to use linux mint for this project as it is my
preferred version of linux. This was not a possibility as it's a
64-bit os, and the raspberry pi can only operate 32-bit. I didn't
discover this until I attempted to boot the raspberry pi and was
met with a blank screen. This was not a large issue, but for anyone
who may attempt to build off of this project please keep in mind
what os' can work with your hardware. 

### Raspian

Raspian was my second attempt of an os, I had used it when I was
younger and got my first raspberry pi. It works, however it is
defientely catered towards a younger audience. When I say it works
I mean it's a valid choice of OS in the correct context. This was
not the correct context; when trying to resolve the SSH issue the
simplistic interface became frustrating to work around.

### Linux Cinnamon

Linux Mint couldn't be used as it was 64-bit instead of 32-bit, so I
figured I would take a shot at Linux cinnamon. (Check if its 32-bit)
I believe that Linux Cinnamon could work for some people but I found
it to be quite frustraiting. In order to get the os to be lightweight
the interface seems to have taken some hits. This os was personally
not my cup of tea, but may work for others. Definetely a valid choice. 
### LMDE 6 "Faye"


## 3D modeling 

For all information detailing 3D models please navigate to my website
www.patrickquintana.com