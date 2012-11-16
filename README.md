cute-gps
========

An open HW/SW cute device with GPS.  

Version:	1.0  
Author:		[Mauro Scomparin](http://scompoprojects.wordpress.com)  

Details
-------
  
The cute-gps project contains all the things you'll need to build a device that
can be used as a GPS logger, compass, and navigator.  
The hardware it's developed with a open source program suite called gEDA,and
there's also a file to open it with the gsch2pcb program wich I use to manage
the process of creating a board easier.  
The software, running on the microcontroller it's developed with the a series
of open source tools called GNU. I'm lazy and can't be bothered to build a
toolchain from source code (althoug possible), so I used an already built
cross toolchain from CodeSourcery, that targets arm-none-eabi.
  
  
License
-------

All the source code, the schematics and the layouts are open, wich means you
can view, modify, use them as you want for your own needs, the details can be
found in the `/LICENSE` folder.
  

Links
-----
  
My project blog:  
[http://scompoprojects.wordpress.com](http://scompoprojects.wordpress.com)  
  
Codesourcery g++ lite toolchain:
[http://www.mentor.com/embedded-software/sourcery-tools/sourcery-codebench/editions/lite-edition/](http://www.mentor.com/embedded-software/sourcery-tools/sourcery-codebench/editions/lite-edition/)  
  
GNU site:  
[http://www.gnu.org/](http://www.gnu.org/)  