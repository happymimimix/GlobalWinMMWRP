<p align="center">
  <img src="https://i.imgur.com/iFLDs6C.png">
  <br />
  A group of functions, that allows you to bypass the Windows Multimedia API, thus getting rid of the lag caused by its slow buffer system.
</p>

# What is this? 
This is a global winmm patch that can be used by ALL software once installed. 

# Why make this when you can patch individual apps instead? 
There are some apps that call the dll with absolute path and the individual app patch just doesn't work. 
In addition, the individual app patch that khangaroo has made needs you to patch every single midi app you want to use one by one, which is very annoying. 

# What if there's an app that can't use OmniMIDI, such as dosbox? 
Don't worry, my patch does not use KDMAPI. It works with all midi output devices. 
Buggy apps like dosbox can still use Microsoft GS Wavetable Synth as much as they like. 
Besides that, you can also have a try with Coolsoft Virtual MIDI Synth. 
That one has a lot better compatibility than OmniMIDI but is also slightly slower. 

# Install tutorial: 
1. Rename winmm.dll in your system to wmmog.dll
2. Download winmm.dll from releases
3. Copy the new winmm.dll to system32 & systemwow64
