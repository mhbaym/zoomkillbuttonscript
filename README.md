# zoomkillbuttonscript
The Karabiner-Elements file required to activate the zoom killer. Note: only works with a mac, and only works with a button that acts as a USB keyboard.

Steps required to activate zoom kill button:
1) Acquire USB button.
2) Install Karabiner-Elements (https://karabiner-elements.pqrs.org/)
3) Download `zoomkillrules.json` and put it in `~/.config/karabiner/assets/complex_modifications/`
3) In Preferences -> Complex Modifications click **+Add Rule** and select "F18 to open and quit zoom, Enter".
3) Use Karabiner's Event Viewer to figure out what key the USB button triggers.
3) Use Simple Modifications to remap the button to F18. I reccomend remapping only for the specific Target Device so you can still use that key on, say, your keyboard.
4) Try it out. You might need to give permissions to things in your Security and Privacy preferences the first time or two. But then it should work cleanly.
5) Optional: if you want a sound you can specify the path in the .json file where it currently reads `~/Downloads/Ahooga.mp3`
