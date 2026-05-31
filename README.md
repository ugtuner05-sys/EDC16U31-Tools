Tools are written 100% in Python. The flasher only uses J2534 devices; serial cables are not supported. A full write takes about 15 minutes with an Openport 2.0. I've tested the flasher using several J2534 cables
(Topdon R-Link X3, genuine Tactrix 2.0, Mongoose JLR, and SM2) and it should support any J2534 device that has KWP2000 support. Write/read chunk size is selectable depending on the quality of the device. 
The logger has basic, selectable measuring blocks. The checksum tool is a simple file-in, file-out process. I have over 80 hours invested in sniffing data communications, logging, bench testing, and debugging. 
I have only tested on my own computers so far, and everything works fine. I'm sure it still has bugs, but as of right now I'm comfortable releasing the tools in their alpha state.
If you have any problems or questions, you can message me at admin@undergroundteam.xyz.
