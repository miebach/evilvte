evilvte
=======

VTE based, highly customizable terminal emulator. Written by Wen-Yen Chuang <caleb AT calno DOT com>

It supports almost everything VTE provides. It also supports tabs, 
automatic hiding of the tab bar, and the ability to switch encoding at runtime. 
       
Configuration is done by editing the source code, especially src/config.h, and recompiling.

Some options can be changed via hotkeys or a menu, e.g. font size or encodings for each tab.

Requirements
------------

<pre>
sudo apt install pkg-config libvte-dev
</pre>

Compilation
-----------

<pre>
./configure
make
sudo make install
</pre>

To remove the compiled binaries and all internediate files, this will clean the source directory back to its original state:

<pre>
make distclean
</pre>
 
