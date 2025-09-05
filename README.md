## Hi there 👋

My name is Jan van Katwijk.
"When I was young" I built  REAL radios, devices with glowing tubes compoenents that you could decipher without glasses.
Later I built a few with transistors (I skipped the period where more complex chips were available) but that was less fun.
After retirement I got interested in SDR and started programming some SDR programs.

Qt-DAB and dab-cmdline deal with - as their name suggests - decoding of DAB signals.
Qt-DAB is typically large and GUI based, dab-cmdline is a simple command line based version, just for
selecting a single service in aselected channel.
Birh can be confured with comon SDR devices as DABsticks, SDRplay and AIRspy devices etc.

The second line is for drm (Digital Radio Mondiale) type decoders, The drm-receuver tries to decode DRM30 transmissions (on shortwave(.
The drm+ decoder is combined drm+ and fm, since both are
(supposed to be) transmitted in the FM band (Here we do not receive drm+, so the decoder is tested with a very few recordings)

Both programs take samples from either an SDRplay device, a Hackrf device or a DABstick,
the DRM30 decoder (which I actually use to listen to DRM transmissions) is
 now equipped with a client for a spyserver, a file reader (96000 S.s) and a reader for the audiocard.

The third line shows two programs for weak signal detection are Qt-WSPR and Qt-FT8, decoders with a Qt-based front end,
Input devices here are -again - SDRplay devices, Hackrf devices, (limited) DAB sticks and spyServer input.

The repository contains some other programs as well, e.g. an Algol to C translator, some plugins for SDRuno, etc.
