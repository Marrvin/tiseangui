#Instructions to make TiseanGUI work on MS Windows.

# Introduction #

This are a collection of tips to allow users of tiseanGUI to work under Windows. This instructions apply to Windows XP, the os in which it has been tested.

# Installation of Python #

The installation on Windows of python is quite simple, you only have to use the Windows Installer provided in the python website:

http://www.python.org/download/

# Installation of GTK, Glade and PyGTK #

This instructions are for Windows XP workstations who hasn't have any previous installation of GTK+.

The best way to install pygtk, is to follow its original guide on http://www.pygtk.org/downloads.html

The main problem with this guide is the recommendation of use of the GTK+ Bundle, which doesn't have libglade and Glade3 support, which is needed for tiseangui.

Luckily, the Glade Project has installers for windows that include all the binaries also with a GTK+.
http://glade.gnome.org/download.html

We are currently testing it with the following package:
http://ftp.gnome.org/pub/GNOME/binaries/win32/glade3/3.6/glade3-3.6.7-with-GTK+.exe

After installing GTK+ with Glade Support, you have to install the following pyCairo, pyGObjext, pyGTK from the pygtk downloads: http://www.pygtk.org/downloads.html

For any other doubts about setting up your pygtk environment you should read the following entry of the pygtk faq:
http://faq.pygtk.org/index.py?req=show&file=faq21.001.htp

# Installation of TiseanGUI #

## Development Version ##

You can download our latest version from our svn http://code.google.com/p/tiseangui/source/checkout

After downloading the latest svn copy you have to copy all the binaries from the latest Tisean Package inside de bin directory on the tiseangui project directory.

You have to consider that as it is the development version, it could contain code that its unstable.

## Beta Version ##

you can download the latest package from our downloads section:

http://code.google.com/p/tiseangui/downloads/list

If you download the version without windows binaries, you will have to copy the Tisean binaries to de bin directory inside the tiseangui directory.

If you download the version with the binaries, you would have tiseanGUI ready for execution.

## tiseanGUI execution ##

> After you have setup your installation you can launch tiseangui from the command line using the following command on the tiseangui project directory.

For example if we had performed a setup on the C:\tiseangui directory, we could execute the gui from command line in this way.

<pre>
C:\tiseangui\python tiseangui.py<br>
</pre>