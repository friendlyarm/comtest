## **comtest**

Serial port communication in C.  

How to build
------------
```
# git clone https://github.com/friendlyarm/comtest.git
# cd comtest
# gcc -o comtest comtest.c
```

Usage
------------
```
./comtest -d /dev/ttyS4 -s 115200
```

Parameters
------------
```
# ./comtest --help
comtest - interactive program of comm port
press [ESC] 3 times to quit

Usage: comtest [-d device] [-t tty] [-s speed] [-7] [-c] [-x] [-o] [-h]
         -7 7 bit
         -x hex mode
         -o output to stdout too
         -c stdout output use color
         -h print this help
```

