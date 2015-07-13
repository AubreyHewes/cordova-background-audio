#Background Audio for iOS

Support an iOS application playing audio in the background.

When included within a cordova/phonegap build then the application will support background audio for iOS
out of the box. No further action is necessary.

This negates having to use location/other solutions that may not be accepted by Apple.

##Installation

    cordova plugin add nl.kingsquare.cordova.background-audio

OR (TEMP cordova v5 npm) for latest npm version; due to cordova-repo not being updated; though always first repo:

    cordova plugin add nl.kingsquare.cordova.background-audio@1.0.1

OR

    cordova plugin add https://github.com/AubreyHewes/cordova-background-audio.git

For the latest..

###Phonegap build (build.phonegap.com)

TODO: update phonegap with latest version

Add the following to your `config.xml`

	<gap:plugin name="nl.kingsquare.background-audio" />
	

