# d70-buddy
Arduino project to provide a display and choose tone maps on a Roland D70. The main functionality is to listen for the D70 SYSEX commands, and resend the most recent program change commands if a new map is selected. This essentially allows you to change maps on the fly without restarting whatever is sending MIDI.

The D70 includes maps for the Roland SC-55 and within that, an MT-32 map, but as with the original SC-55, this means the default instruments only, no custom programming. The Secret of Monkey Island only uses default instruments so it's a good one to test with.
