load-ladspa
===========

Simple desktop file and shell script to load and unload ladspa sound device on pulseaudio

LADSPA compresses the dynamic range, which keeps the loud and quiet closer together.

Installation steps:
 1. place the desktop file (desktop/give-me-quiet.desktop) on the desktop ($HOME/Desktop)
 2. place load-ladspa (bin/load-ladspa) on your path (echo $PATH, I suggest $HOME/bin)
 3. install the compressor (see below)

References:
 * http://askubuntu.com/questions/95716/automatically-adjust-the-volume-based-on-content
 * http://askubuntu.com/questions/43950/how-can-i-apply-a-ladspa-plugin-to-a-pulseaudio-stream

Installing the compressor:
 1. apt-get install swh-plugins
