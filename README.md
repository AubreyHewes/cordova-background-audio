#Background Audio for iOS

Support an iOS application playing audio in the background.

When included within a cordova/phonegap build then the application will support background audio for iOS
out of the box. No further action is necessary.

This negates having to use location/other solutions that may not be accepted by Apple.

##Installation

###Local cordova build

    cordova plugin add https://github.com/AubreyHewes/cordova-background-audio.git
    
###Local phonegap build

    phonegap local plugin add https://github.com/AubreyHewes/cordova-background-audio.git

###Remote phonegap build (build.phonegap.com)

**NOTE: The plugin has been submitted (2014-10-02). Currently it is not yet been accepted. Therefore the following will not work**

Add the following to your `config.xml`

	<gap:plugin name="nl.kingsquare.cordova.background-audio" />
	

