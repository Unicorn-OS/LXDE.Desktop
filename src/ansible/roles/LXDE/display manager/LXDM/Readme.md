# fix: Failed to Start Session error

https://forum.lxde.org/viewtopic.php?p=54629&sid=be7a9e3c44c1e19faafb0c3c67d2b840#p54629

>you need to install the lxdm display manager in order to >boot correctly lxde (at least for first time), and setting >it up by default.
>```
># apt-get install task-lxde-desktop
># apt-get install lxdm
>```
>
>OR
>manually configure a ~/.xinitrc file.