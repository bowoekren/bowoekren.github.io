---
layout: default
title: upgrade libc6 2.19 pada crunchbang waldorf!
---
coba2 pake distro yang katanya ubuntu based paling '__ringan__'.  
jajalin install android emu di crunchbang, install vbox, install, download genymotion.
lanjut running si geny, nah pas running. libc6 ga support. katanya musi pake yg v >= 2.15
googling sana sini akhirnya nemu juga di stackoverflow.  


 * musti exit display manager, ctrl + alt + f1
 * add ke sources.list


```
deb http://ftp.debian.org/debian sid main
```


 * update package, lalu install libc6 


```
$ apt-get update
$ apt-get -t sid install libc6
```
 * profit
