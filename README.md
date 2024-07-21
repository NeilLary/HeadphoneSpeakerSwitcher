# HeadphoneSpeakerSwitcher
An interactive Rainmeter skin for your desktop to switch audio

HeadphoneSpeakerSwitcher allows you to switch between the speaker and headphone audio by setting the default device and default communication device

Pre-requisites:
Installing Rainmeter: https://www.rainmeter.net/
Installing skins: https://docs.rainmeter.net/manual/installing-skins/

Set the Rainmeter to run on startup and load the skin to the Rainmeter and you are ready to go.
During the startup, the AudioSwitcher runs by default and sets the speaker as Default Device and Default Communication Device. During switching between headphones/speaker, the Default Device and Default Communication Device would be set for the selected device.

![image](https://github.com/user-attachments/assets/f43947b5-9691-4f8b-8cfa-785147bdf903)

As most windows applications like Discord, Whatsapp.. uses 'Default Device' as the VoIP passthrough, even after switching your audio through the windows settings, the Default Communication Device still remains the previously configured device.

![image](https://github.com/user-attachments/assets/c807b552-544f-47fa-949e-141245e7bb85)

Unless user manually swithces this through the Audio Playback settings in windows, the call audio through the windows applications won't be available through the newly selected device.

This skin fixes the issue in VOIP applications where even though the you've selected your preferred device through the windows, still the VoIP audio now pass through the Default Communication Device.
This is because windows only switches the Default Device through the Audio Playback settings as some users would like to have this configuration separately.

**This skin gives user the option to configure the Default Device and Default Communication Device to the selected device.**


This skin is an update based on the work: https://github.com/s4wny/rainmeter-headphones-speaker-switcher
