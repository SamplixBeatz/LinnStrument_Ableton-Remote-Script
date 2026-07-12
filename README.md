# Ableton Remote Scripts for LinnStrument 128 / 200 - V2

These scripts allow you to control Ableton using the LinnStrument's pads. Separate remote scripts are available for each LinnStrument model (128/200) for working in Session View and Arrangement View.

They are focused on live looping in session view and arranging in arrangement view (incl. keystrokes).

Each remote script also includes a “Note Mode,” in which (with the exception of the first pad column) the LinnStrument can be used in normal operating mode.

Study the included PDF's for all mapped functions of the remote scripts.
There is a second PDF for labelling the LinnStrument with the session_view functions (stickers).

Requirements:
- Session View scripts: Ableton Live 12 (not tested with earlier versions), Mac and Windows (only tested on Mac silicon)
- Arrangement View scripts: Ableton Live 12 Suite (requires Max for Live; not tested with earlier versions), Max-External 11strokes (https://github.com/11ols/11strokes), Mac only

Regarding colors: The LinnStrument can display only 10 different colors. The Remote Script therefore attempts to render each track's color as accurately as possible. Clips are generally displayed in the track's color (no individual clip coloring).

--------

Installieren eines Session_View Scripts:
- Unzip Remote Script
- Copy Folder "LinnStrument_XXX_Session_View" to your Ableton User Libary / Remote Scripts. If this folder does not exist, create it.
- On LinnStrument, Per-Split Settings, Left Split, turn on CC FADERS (CC1-CC8, see PDF). Also, set the left split to a width of 1 column by HOLDing the SPLIT button while pressing any pad in column 1 (leftmost column). 
- Open Ableton
- In Ableton Preferences, select “TEMPO & MIDI” at left. Then in the MIDI section at right, under “Control Surface”, set the first unused row to “LinnStrument_XXX_Session_View”. Then in the INPUT and OUTPUT columns for the same row, set both to LINNSTRUMENT MIDI”. 
- To switch between SESSION MODE and NOTE MODE, on LinnStrument press pad 1 (nearest to front) in column 1 (leftmost column).
- Enjoy your LinnStrument with a lot of APC 40 mk2 & Push functionality!

--------

Installieren eines Arrangement_View Scripts:
- Unzip Remote Script
- Copy Folder "LinnStrument_XXX_Arrangement_View" to your Ableton User Libary / Remote Scripts. If this folder does not exist, create it.
- Copy the Max External “11strokes.mxo” to “/documents/Max 9/Packages/11strokes/externals”. For more information: https://github.com/11ols/11strokes
- On LinnStrument, Per-Split Settings, Left Split, turn on CC FADERS (CC1-CC8, see PDF). Also, set the left split to a width of 1 column by HOLDing the SPLIT button while pressing any pad in column 1 (leftmost column). 
- Open Ableton
- In Ableton Preferences, select “TEMPO & MIDI” at left. Then in the MIDI section at right, under “Control Surface”, set the first unused row to “LinnStrument_XXX_Arrangement_View”. Then in the INPUT and OUTPUT columns for the same row, set both to LINNSTRUMENT MIDI”.
- Copy the M4L device “LinnStrument_Companion.amxd” to your Ableton User Library. Insert the device on the Master channel. The “Arrament_View” remote script will not work without this device.
- To switch between ARRANGEMENT MODE and NOTE MODE, on LinnStrument press pad 1 (nearest to front) in column 1 (leftmost column).
- Have fun using the LinnStrument to trigger frequently used commands while working in Arrangement View.
--------

### Session Mode
![Session Mode](https://github.com/SamplixBeatz/LinnStrument_Ableton-Remote-Script/blob/main/pictures/01_Session%20Mode.JPG)

### Mixer Mode
![Mixer Mode](https://github.com/SamplixBeatz/LinnStrument_Ableton-Remote-Script/blob/main/pictures/02_Mixer%20Mode.jpg)

### Note Mode
![Note Mode](https://github.com/SamplixBeatz/LinnStrument_Ableton-Remote-Script/blob/main/pictures/03_Note%20Mode.JPG)

### Arrangement Mode
![Arrangement Mode](https://github.com/SamplixBeatz/LinnStrument_Ableton-Remote-Script/blob/main/pictures/04_Arrangement%20Mode.jpg)
