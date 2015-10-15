# Background Audio for iOS

Support an iOS application playing audio in the background.

When included within a cordova build then the application will support background audio for iOS
out of the box. No further action is necessary.

This negates having to use location/other solutions that may not be accepted by Apple.

## Installation

    cordova plugin add nl.kingsquare.cordova.background-audio

OR

    cordova plugin add https://github.com/AubreyHewes/cordova-background-audio.git

For the latest..

### Ionic 

    ionic plugin add nl.kingsquare.cordova.background-audio

### PhoneGap / PhoneGap Build (build.phonegap.com)

Add the following to your `config.xml`

	<gap:plugin name="nl.kingsquare.background-audio" />
	

