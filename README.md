load-ladspa
===========

Simple desktop file and shell script to load and unload ladspa sound device on pulseaudio

LADSPA compresses the dynamic range, which keeps the loud and quiet closer together.

Installation steps:
 1. place the desktop file on the desktop
 2. place load-ladspa on your path (echo $PATH, I suggest $HOME/bin)
 3. install the compressor

References:
 * http://askubuntu.com/questions/95716/automatically-adjust-the-volume-based-on-content

Installing the compressor:
 1. apt-get install swh-plugins
