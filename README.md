## Hi there 👋

My name is Jan van Katwijk
In my teener years I built (physical) radios, devices with tubes and
later with transistors (I skipped the period where more complex chips were available).
After retirement I started with programming SDR, my interests are DAB, DRM and amateur radio

Qt-DAB and dab-cmdline deal with - as the name suggests - decoding of DAB signals.
Qt-DAB is typically large and GUI based, dab-cmdline is command line based, just for
selecting a single service on a given channel.
Some more DAB related programs are in other repositories

fm-receiver is - again as the name suggests - an FM decoder, using Qt for the GUI.

drm-receiver tries to decode DRM (Digital Radio Mondiale) on shortwaves (a separate version exists for DRM+ on the FM band).
The program takes samples from either an SDRplay device, a Hackrf device or a DABstick,
and is now equipped with a client for a spyserver, a file reader (96000 S.s) and a reader for the audiocard.

It is derived from the sw receiver, that one is more general and has more decoders

Two programs for weak signal detection are Qt-WSPR and Qt-FT8, decoders with a Qt-based front end,
Input devices here are -again - SDRplay devices, Hackrf devices, (limited) DAB sticks and spyServer input.

The repository contains some other programs as well, e.g. an Algol to C translato, some plugins for SDRuno, etc.
