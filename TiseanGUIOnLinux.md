#Instructions to make TiseanGUI work on Linux (or any Unix Flavour).

# Introduction #

This are a collection of tips to allow users of tiseanGUI to work on Unix.

# Installation of Python, GTK, Glade and PyGTK #

The recommended way of installing them is to use the package manager of distribution.

# Installation of TiseanGUI #

## Development Version ##

You can download our latest version from our svn http://code.google.com/p/tiseangui/source/checkout

After downloading the latest svn copy you will have to compile and copy the Tisean 3.0.1 binaries to the bin directory inside the tiseangui project directory.

You have to consider that as it is the development version, it could contain code that its unstable.

## Beta Version ##

you can download the latest package from our downloads section:

http://code.google.com/p/tiseangui/downloads/list

After you unpack the package you will have to compile and copy the Tisean 3.0.1 binaries to bin directory inside the tiseangui project directory.

## tiseanGUI execution ##

> After you have setup your installation you can launch tiseangui from the command line using the following command on the tiseangui project directory.

For example if we had performed a setup on the \home\user\ directory, we could execute the gui from command line in this way.

<pre>
\home\user\python tiseangui.py<br>
</pre>