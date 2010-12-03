[license]: TMiTunes.tmbundle/blob/master/license.md "MIT-Style License"
# TMiTunes
An iTunes Manager for your Text Mate  

### Installation
Read [license.md][license] before proceeding. TMiTunes is released under the MIT License
use the following command to install into TextMate

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/Rixius/TMiTunes.tmbundle.git

### Current Features Supported
 - Play/Pause (⌘⇧↓)
 - Next Track (⌘⇧→)
 - Previous Track (⌘⇧ ←)
 - What am I listening to? (⌘⇧↑)
 - Raise Volume (⌘⇧+)
 - Lower Volume (⌘⇧-)
 - Toggle Shuffle (⌘⇧S)
 - Toggle Repeat (⌘⇧R)

### Configurable details
under Bundle Editor, there is a preference field called System Variables. Under this you will find the following text:

    {	shellVariables = (
    		{	name = 'TMiT_DELAY';
    			value = '2';
    		},
    		{	name = 'TMiT_SHORT_DELAY';
    			value = '1';
    		},
    		{	name = 'TMiT_DISPLAY';
    			value = 'show';
    		},
    	);
    }

 - TMiT\_DELAY is how long the song info stays on the screen (in seconds) 
 - TMiT\_SHORT\_DELAY is how long the setting info(repeat,volume,shuffle) stays on the screen (in seconds)
 - TMiT\_DISPLAY is whether song info is displayed on the play/pause,next,and previous track. leave at 'show' to show, anything else will not display.
 
### Planned features(if possible with AppleScript)
 - Sort By (artist/title/year/etc.)(ascending/descending)
 - Changing current Playlist
 - Searching for a track/artist/etc and playing it
 - equalizer settings

