# LGG2_DTSX
Why doesn't the LG G2 passthrough DTS:X? 

I am investigating why Jellyfin can play a DTS:X audio track, yet between JF and the AVR, it is either transcoded or plays no audio at all.

Ultimately I will consider success when DTS:X audio is played on Jellyfin, with the AVR reporting DTS:X


Q. Can the Jellyfin App on the LG deliver DTS:X to the TV?<br>
Jellyfin reported Direct Play for a diagnostic clip containing only DTS:X audio. 

Q. Is there proof that Jellyfin passes DTS:X audio to the TV?<br>
No

Q. How dooes the G2 Kernal audio bypass and eARC control works?<br>
Unknown

Q. Can the G5 forwarder be adapted to the G2?<br>
Unknown


Previous Work & Research
This repo has successfully implimented DTS:X over eARC on the G5

Glasshouse documents native-app DTS:X over eARC on a G5
https://github.com/rorygallagher2024/glasshouse/blob/2af052d9c1dd36a856145b8ba38b3df76815db82/native/dts-forwarding/README.md

- Uses a custom forwarder and kernal audio routing changes 


These two repo's completed work to impliment DTS but no DTS:X

A Git Repo containing libraries and scripts needed to restore DTS playback as well as add Matroska DV support on LG Smart TVs, such as OLED CX models.
https://github.com/lgstreamer/dts_restore

A fork of the original dts_restore - add webOS 25 support 
https://github.com/josippapez/dts_restore_plus


