# wlan fallback option for your Raspbian

## What is it good for?
I thought it might be useful to have a wlan connection to my Pi if it 
goes up and no known Connection is here that the Pi knows of?

What does this do?
* Set your known WLAN ESSIDs
* Set your fallback WLAN
* Manage your Raspberry without external Connections

## I use it for
MPD on the RPi and use in the car. For MPD there are many GUIs to choose
from and for Android my primary choice is MpDroid(https://play.google.com/store/apps/details?id=com.namelessdev.mpdroid).
I power up the pi if the car goes on and if there is no wifi that the Pi knows of it creates a new AccessPoint. From here my Android Phone knows what to do (Tasker) when connected to it.
