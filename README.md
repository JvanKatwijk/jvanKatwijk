## Hi there 👋

My name is Jan van Katwijk.
"When I was young" (the Animals 1967) I built  REAL radios, devices with glowing tubes, large components that you could decipher without wearing glasses.
Later I built a few with transistors (I skipped the period where more complex chips were available) but that was less fun.
After retirement I got interested in SDR and started programming some SDR programs, the result is shown here.

Qt-DAB and dab-cmdline deal with - as their name suggests - decoding of DAB signals.
Qt-DAB is GUI based and contains lots of features, dab-cmdline is a simple command line based version, just for
selecting a single service in a selected channel.
Both can be configured with common SDR devices as DABsticks, SDRplay and AIRspy devices etc.

The second line below is for DRM (Digital Radio Mondiale) type decoders. The drm-receiver tries to decode DRM30 transmissions (on shortwave),but there are 
not much DRM transmissions left in this region.
The drm+ decoder is combined drm+ and fm. DRM+ cannot be received here, so it is only tested with some files as input.
DRM+ is transmitted in the FM band, so the program handles both DRM+ and FM.

Both programs (ie. the DRM receiver and the DRM+/FM receiver) take samples from either an SDRplay device, a Hackrf device or a DABstick,
the DRM decoder (which I actually use to listen to DRM transmissions) is
now equipped with a client for a spyserver, a file reader (96000 S.s) and a reader for the audiocard.

The third line shows two programs for weak signal detection are Qt-WSPR and Qt-FT8, decoders with a Qt-based front end,
Input devices here are -again - SDRplay devices, Hackrf devices, (limited) DAB sticks and spyServer input.

The repository contains some other programs as well, e.g. an Algol to C translator, some plugins for SDRuno, etc.
