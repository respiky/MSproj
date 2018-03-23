# MSproj
Project for the MS course

# Team Members
ILIENESCU Anca
JEBEREAN Remus

# Description
The aim of this project is to create a personal assisstant using Raspberry PI

# Similar ideas
The most well known personal assisstant is probably Amazon's Alexa. Other similar apps can be found on phones (Siri, Cortana, Google Assisstant etc.)

# Components to be used
Raspberry PI   - Provides all of the functionality required, will be used to emulate Alexa
MicroSD Card   - Used for storage
USB Microphone - Used as an input device for voice commands
USB Speakers   - Used as an output device for feedback to the given commands
LED/Switches   - Used to showcase some of the things we learned during laboratory lessons

# How it works
Using Amazon's Developer Service and Tools, we will emulate Alexa on a Raspberry PI. The Raspberry will act as a control/management app and system. It will receive data from the USB mic, feed it to the emulated Alexa software, which will in turn send it over the cloud to Amazon's Servers for processing. The received response will be relayed to the connected USB speakers for output in the same manner. We will add some extra bits of functionality, such as a switch to enable/disable the mic listening, a LED to show when the system is turned on, another LED showing when the system is actively listening to a command, or while providing the received output message and so on. This part is subject to change.
