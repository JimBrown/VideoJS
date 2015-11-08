#VideoJS
```
Enable VideoJS to handle multimedia files.
Author: Jim Brown
```
IMPORTANT: Only one multimedia extension plugin can be enabled at the time and the class-video plugin must be enabled, too.

Please see VideoJS.com for more info about the player and its license.

Support for the Video.JS video player (videojs.com). It will play video natively via HTML5 in capable browsers if the appropiate multimedia formats are provided. It will fall back to flash in older browsers. The player size is responsive to the browser size.
```
Audio: This plugin does not play audio files.
Video: .m4v/.mp4 - Counterpart formats .ogv and .webm supported (see note below!)
```
IMPORTANT NOTE ON OGG AND WEBM COUNTERPART FORMATS:

The counterpart formats are not valid formats for Zenphoto itself as that would confuse the management. Therefore these formats can be uploaded via ftp only. The files needed to have the same file name except extension (beware the character case!).

IMPORTANT NOTE ON HD and SD FORMATS:

This player is capable of switching between HD and SD video files. To enable this feature the HD files should be uploaded as described above. The SD files should be uploaded to a companion albums folder that has the same path and starts in the same folder as the albums folder, but the root folder must be the same name as the normal albums folder with '.SD' appended to it. For example:
```
HD video files go here: /albums/videos/myvideo.mp4
SD video files go here: /albums.SD/videos/myvideo.mp4
```
(The counterpart videos must follow the same paths.)
```
NOTE: This plugin does not support external albums!
NOTE: This plugin does not support playlists!
```
Options:
```
Autoplay
Poster (Videothumb)
```
