Observing Guide
===============

This page describes how to make observations at the Challis Observatory. 

How to Observe
--------------

Be aware that the internet connection is a bit slow, so your mouse clicks will
not register immediately. Go slow as you click on things.

1. Make sure your IP address is on the Observatory whitelist.
2. Remote-desktop into the observatory - use vnc client like `TightVNC <https://www.tightvnc.com/>`_.
3. Check the weather report periodically throughout the observing session.
4. Open Observatory HCA panel - It should already be open on the menu bar, but if it's not, double-click the HCA icon on the desktop.
5. Right-click on "Turn on instruments" icon and select "Start". A message
   window should then appear saying the instruments are starting up.
6. Open MaximDL program and inspect the "Camera Control" box.
7. Open the "Setup" tab. 
8. Visit the "Observatory" window and click the connect button below the "Focuser 1" box.
9. Open the Alt-Focus-Table.txt file on the desktop. This file gives you the
   focuser position desired for a given temperature.
10. Adjust filter wheel.
11. Turn on south light in HCA and web cam.
12. Run "HCA Open Roof" - Do this step before turning on the telescope so the
    telescope can acquire a GPS signal.
13. Turn on telescope in the HCA panel.
14. Open TheSky program. Connect to telescope from TheSky.
15. Click on the object in the TheSky map and choose the slew button in the
    left panel to move the scope to the choosen object.

Other Notes
-----------
- Close roof in HCA panel.
- MaximDL to set exposures and collect images.
- Warm up CCD before turning off to avoid formation of ice crystals.
- Check image to make sure target is on the chip where you want it. Use Jog function (set to 1 arcminute) to move the image - East and West are reversed!
- Turn on south light and webcam to monitor shut down process.
- Park telescope (in TheSky) and go back to the telescope tab.
- In TheSky, "Shutdown" tab - Disconnect telescope.
- Do NOT turn off the telescope without parking it first - If you do, Jay will have to visit the observatory and re-align the telescope.
- Turn off telescope.
- Once the camera has reached ambient temperature, turn off the cooler. Disconnect from the camera in MaximDL.
- There is also an automated observing mode.
