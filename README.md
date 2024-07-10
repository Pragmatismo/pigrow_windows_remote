# pigrow_windows_remote

This is the windows executable version of pigrow_remote.py - just download, unzip and run the executable test_gui.exe

'test_gui_008' now has all the features of the old gui 'pigrow_remote_4_9b' except for the Graphing and User Log tabs. The features are upgraded in many ways so use the new gui for everything except for these - they'll be added in future versions. 

To use the newest Raspberry Pi OS version 'Bookworm' requires the use of a virtual environment for python, to be able to install python modules such as those used to read sensors or watchdog which is used for monitoring logs the venv must be installed and enabled via the system panel, install pigrow dialogue - do this first before running the install wizard. 

-------

 Install Notes; 
 -------------

 To connect to your pi you will need it linked to your wifi with SSH enabled, the easiest way to do this is to set up ssh when creating the SD card in Raspberry Pi Imager. Alternatively connect it to a screen using HDMI and use a mouse and keyboard to connect to wife and run raspi-conf to turn SSH on. 

 Once connected to you raspbery pi you can use the 'install pigrow' button in the system tab of the gui and use the Install Wizard, if using Raspberry Pi OS version Bookworm or others that require use of a venv then first use the config venv dialog box to install a virtual environment.

 - once you have your sensors and relay board working it's a good idea to use the local files tab to download your settings files so you can keep a backup.   

 To make and play timelapse video you'll need MPV insalled, on linux simply run the command 'apt install mpv' on windows visit https://mpv.io/installation/ and follow the instructions, there's an install script which will take care of everything for you. If using another method to install it set path variables so that running the command mpv in the pigrow_remote.exe folder opens mpv.

--

This is still a rapidly evolving work-in-progress so not all features are complete, it'd be really helpful if you could tell me about any bugs or errors you experience.   


  More info and guides at www.reddit.com/r/Pigrow 
  Or robogromo on youtube  
  
