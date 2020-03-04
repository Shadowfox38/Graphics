# Graphics
config to compile c++ X11 files

Add these header files in your c++ program

#include<X11/Xlib.h>

#include"gfx.h"

put the gfx.c and gfx.h files in the directory of you program

put the script_graphic.sh in home directory

edit the .bash_aliases file in your home directory (create one if you don't have it),put this in it

alias g+='~/.script_mysql.sh'

now run

chmod u+x .script_mysql.sh

source .bash_aliases


now you can compile your c++ with the command g+ filename.cpp

Enjoy!!
