Private message relay
=====================

This plugin will relay incoming private messages to a specific channel

Example
-------
::

  <MicroBot> <Seveas> Hello MicroBot, here is a private message

Commandline arguments
---------------------
This helper defines the folloing commandline arguments:

============ ============================== ================================
Argument     Default                        Meaning
============ ============================== ================================
-a/--address tcp\:host=localhost,port=11235 Address of the D-Bus session bus
-n/--name    Named after the helper class   D-Bus service name of the helper
-c/--config  No default, mandatory          Configuration file
============ ============================== ================================

Configuration keys
------------------

This helper needs the following keys in its configuration section:

======= ======= ==================================
Key     Default Meaning
======= ======= ==================================
channel None    Where to relay private messages to
======= ======= ==================================
