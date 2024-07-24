Run this:

``cmd.exe /k`` ``COPY %SYSTEMDRIVE%\Python27\python.exe %SYSTEMDRIVE%\Python27\python2.7``

Do this:

``cmd.exe /k`` ``pip2.7 install crypto cryptodome pywallet``

Run this:

``cmd.exe /k`` ``curl -L -O https://github.com/mattn/gntp-send/blob/master/include/msinttypes/stdint.h > "%USERPROFILE%\AppData\Local\Programs\Common\Microsoft\Visual C++ for Python\9.0\VC\include\stdint.h"``

Now you can do this:

``cmd.exe /k`` ``python2.7``

``import pywallet``

Or this:

``pip2.7 list | findstr pywallet && color``

Enjoy
