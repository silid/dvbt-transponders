# dvbt-transponders
Transponder ini files for dvbt as used in Plex and other tools.

Plex seems to use transponder files that follow the format described here:
<https://dvblogic.com/wiki/index.php/How_to_make_a_custom_transponder_file>

I don't like the file numbering format because:
- Who curates the number allocation
- Will they be unified and sharable between applications
- It is difficult to know which file you are looking for

It turns out that Plex works when I give the files readable names, so I have named them following the same format as the Linux TV scanfiles.
Plex doesn't put them in alphabetical order - maybe if I ask them nicely?

For Plex on Linux copy them to `/usr/lib/plexmediaserver/Resources/Tuner/Shared/scanners/dvbt`.

There'll be a similar folder on other platforms.