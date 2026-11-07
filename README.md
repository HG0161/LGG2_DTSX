# LGG2_DTSX
Why doesn't the LG G2 have DTSX available as passthrough

I'm looking into why Jellyfin can play a DTS:X audio track, but between this and the AVR, it's transcoded or plays no audio at all.
Ultimately i will consider success if when audible playback from LG Jellyfin, with the AVR reporting DTS:X


This repo has successfully implimented DTS:X over eARC on the G5

Glasshouse documents native-app DTS:X over eARC on a G5
https://github.com/rorygallagher2024/glasshouse/blob/2af052d9c1dd36a856145b8ba38b3df76815db82/native/dts-forwarding/README.md

  - Uses a custom forwarder and kernal audio routing changes 


These two repo's completed work to impliment DTS but no DTS:X

A Git Repo containing libraries and scripts needed to restore DTS playback as well as add Matroska DV support on LG Smart TVs, such as OLED CX models.
https://github.com/lgstreamer/dts_restore

A fork of the original dts_restore - add webOS 25 support 
https://github.com/josippapez/dts_restore_plus


