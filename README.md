Simple dmenu frontend for MPD.

# Arguments

```
mpdmenu
dmenu frontend to mpd

USAGE:
	mpdmenu [FLAGS]
FLAGS:
	-h, --help         Prints help information
	-a, --artist       Artist mode
	-A, --albumartist  Album artist mode
	-b, --album        Album mode
	-p, --playlist     Playlist mode
	-P, --playlists    Playlists mode
	-c, --control      Control mode

DMENU ARGS:
	Every argument after :: will be passed to dmenu.
	
	For example:

	mpdmenu -p :: -sb '#000000'

```
