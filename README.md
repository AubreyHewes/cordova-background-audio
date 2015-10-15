# Background Audio for iOS

Support an iOS application playing audio in the background.

When included within a cordova build then the application will support background audio for iOS
out of the box. No further action is necessary.

This negates having to use location/other solutions that may not be accepted by Apple.

## Installation

    cordova plugin add nl.kingsquare.cordova.background-audio
    # OR
    cordova plugin add https://github.com/AubreyHewes/cordova-background-audio.git # latest

### Ionic 

    ionic plugin add nl.kingsquare.cordova.background-audio
    # OR
    ionic plugin add https://github.com/AubreyHewes/cordova-background-audio.git # latest

### PhoneGap

    phonegap local plugin add nl.kingsquare.cordova.background-audio
    # or 
    phonegap local plugin add https://github.com/AubreyHewes/cordova-background-audio.git # latest

#### PhoneGap Build (build.phonegap.com)

Add the following to your `config.xml`

    <gap:plugin name="nl.kingsquare.background-audio" />
	

