This script was created to redirect access to the "Plex Transcoder" executable in /usr/lib/plexmediaserver by renaming the executable to "Plex Transcoder" to "Plex Transcoder.real" and creating a bash script called "Plex Transcoder".

Currently, the script only changes the color of burned-out subtitles via forced transcoding, which are originally white (because the Plex server doesn't respect the my choice for yellow subtitles setting in the web configuration interface!!!), to yellow, and checks if the input video stream is in AV1 format and change CPU for decoding but keeps the GPU for encoding (again, due to some bug in Plex or the script where the binary tries to decode AV1 via hardware).

It was initially created in a scenario with a native Plex server running Debian (currently version 13) and an Nvidia GTX 1660 Super (Turing) GPU.

## Disclaimer
This software is provided "as is", without any express or implied warranty. 

In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software. 

Use at your own risk!

