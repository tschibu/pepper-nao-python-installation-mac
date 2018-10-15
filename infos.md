
Python 32bit oder 64bit version:
import struct;print( 8 * struct.calcsize("P"))




pynaoqi-python2.7-x.x-mac64.tar.gz
pynaoqi-python-2.7-naoqi-x.x-mac64.tar.gz
pynaoqi-python2.7-2.5.5.5-mac64.tar.gz


pynaoqi-python-2.7-naoqi-x.x-mac64.tar.gz

pynaoqi-python2.7-2.5.5.5-mac64.tar.gz
pynaoqi-python2.7-2.5.5.5-mac64.tar.gz
pynaoqi-python2.7-2.5.5.5-mac64_2.tar.gz


/Users/tluscre1/Documents/Studium.Local/ROBLAB/pynaoqi-sdk/lib/python2.7/site-packages
/Users/tluscre1/Documents/Studium.Local/ROBLAB/pynaoqi-sdk/lib

roblab:
/Users/tluscre1/Applications/anaconda3/envs/roblab/bin/python2.7

/Users/tluscre1/Applications/anaconda3/envs/roblab/bin/python2.7 -c 'import sys; print(sys.version)'
2.7.15 |Anaconda, Inc.| (default, May  1 2018, 18:37:05)
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)]


--> User definierte Python:
/usr/local/bin/python
    --> /Library/Frameworks/Python.framework/Versions/2.7/bin/python
    
/Library/Frameworks/Python.framework/Versions/2.7/bin/python
Python 2.7.15 (v2.7.15:ca079a3ea3, Apr 29 2018, 17:49:27)
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import sys; print(sys.version)
2.7.15 (v2.7.15:ca079a3ea3, Apr 29 2018, 17:49:27)
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)]
>>> import struct;print( 8 * struct.calcsize("P"))
64
>>> exit()

/Library/Frameworks/Python.framework/Versions/2.7/bin/python-32
Python 2.7.15 (v2.7.15:ca079a3ea3, Apr 29 2018, 17:49:27)
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import sys; print(sys.version)
2.7.15 (v2.7.15:ca079a3ea3, Apr 29 2018, 17:49:27)
[GCC 4.2.1 (Apple Inc. build 5666) (dot 3)]
>>> import struct;print( 8 * struct.calcsize("P"))
32
>>> exit()




--> MacOS Python:
/usr/bin/Python

/usr/bin/Python -c 'import sys; print(sys.version)'
2.7.10 (default, Oct  6 2017, 22:29:07)
[GCC 4.2.1 Compatible Apple LLVM 9.0.0 (clang-900.0.31)]























System:
import sys,platform; print platform.architecture()[0]