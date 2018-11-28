# pigrow_windows_remote

This is the executable version of pigrow_remote.py, there are versions for running on windows or linux machines - just download, unzip and run the executable.

-------

New features in this version -

    - Overlay Log's onto Timelapse videos, new button in the timelapse tab that opens a dialogue box which allows you to select exactly which parts of the log you want to display, the size, position and colour of the text. It creates a new image set in a folder called edited_caps which you can overlay more logs onto or make into a timelapse. 

    - User Logs, now you can record notes or log your own variables directly from the remote gui. This useful little feature makes it easy to record notes like 'photoperiod changed', 'seed type = bob's tomatos' and to log watering times, plant heights, etc which can be either overlaid onto the timelapse using the new overlay log feature or graphed as soon as the local graphing tab is completed... (coming in a future version) 

-------

 Install Notes; 
 -------------

 To connect to your pi you will need it linked to your wifi with SSH enabled, the easiest way to do this is to connect it to a screen using HDMI and use a mouse and keyboard to connect to wife and run raspi-conf to turn SSH on. 

 Once connected to you raspbery pi you can use the 'install pigrow' button in the system tab of the gui to insstall the pigrow software onto the pi, the first step you should take is to change the box name to something of your choice (making sure to click the button after inputting your new name) - once you have your sensors and relay board working it's a good idea to use the local files tab to download your settings files so you can keep a backup.   


 To make and play timelapse video you'll need MPV insalled, on linux simply run the command 'apt install mpv' on windows visit https://mpv.io/installation/ and follow the instructions, install it into the same folder as the pigrow_remote.exe or set path variables so that running the command mpv in the pigrow_remote.exe folder opens mpv.


--

This is still a rapidly evolving work-in-progress so not all features are complete, it'd be really helpful if you could tell me about any bugs or errors you experience.   


  More info and guides at www.reddit.com/r/Pigrow 
  
  
