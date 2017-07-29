# AutoNetstatScanner

This bash script is supposed to constantly scan the connections on the computer and determine if there are any processes that are accessing the internet whose process name is different than the name of file that started the process (for example the process name bash being started from /bin/bash, which has a file name of bash). There is a file where exceptions can be placed (files that should not draw warnings).

I decided to write this for my own personal computer after CyberPatriots and seeing how malware can change its process name can be changed to hide it from notice from people managing he computer. 

NOTE: It's still under testing and being worked on.
