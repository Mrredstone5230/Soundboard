# Soundboard

YOU NEED TO MANUALLY CREATE THE ./Sounds FOLDER !!!

(This is a temporary project, just to leave time for the original dev to fix it)

Basic, lightweight Java soundboard implementation.

Builds a visual Soundboard of all files listed in the subdirectory ./Sounds, which can be customized via the INI generated on launch.
Uses .wav format, which is required by Java for playback.

![Preview Image](https://github.com/shadowmoose/Soundboard/blob/master/Preview.png)

This Soundboard requires a Virtual Audio Cable interface, which you must install.
For Windows, I suggest this one: https://vb-audio.com/Cable/

Simply set the Virtual Cable as your default microphone, and when prompted by the App select the Virtual Speakers created (listed as "CABLE Input" with the above driver).

This program also makes use of the library [JNativeHook](https://github.com/kwhat/jnativehook). View their repository for further information, credits, and licensing.
