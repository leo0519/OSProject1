# OSProject1
Sample code for FIFO scheduling.

```
env: linux ubuntu 16.04
cmd: cd sample && gcc sample.c -o sample && sudo ./sample < sample.in
You need to have root priviledge to use SCHE_FIFO.
```
Show on debug message.
```
The message will show on stdout,
use printk(KERN_DEBUG "AAAAA\n") to print on dmsg.
(Remember to include linux/kernel.h)
```
