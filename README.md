biobankActivityMonitor
======================

A tool to extract meaningful health information from large accelerometer datasets e.g. how much time individuals spend in sleep, sedentary behaviour, and physical activity.

This software will allow non-specialists worldwide to benefit from the information currently locked within the accelerometer data of large health studies e.g. UK Biobank will have 100,000 people wear wrist-worn accelerometers for 1 week each, and then monitor their health for the rest of their lives.


<h2>Installation</h2>
Details of installation (e.g. via pip).


<h2>Usage</h2>
To extract a summary of movement (average sample sumVectorMagnitude) and (non)wear time from raw GENEActiv/Axivity .bin/.CWA accelerometer files:


    python biobankActivityMonitor.py [input_file.CWA] [options]<br>
    python biobankActivityMonitor.py p001.cwa<br>
    python biobankActivityMonitor.py p001.cwa<br>

  
Options include:
 - Folder to write epoch summaries
 - Folder to write nonWear summaries
 - Filtering on/off
 - Autocalibration on/off + parameter settings
 - Diurnal adjustment on/off
 - Days to remove from analysis


<h2>Licence</h2>
This project is released under an BSD Licence (see LICENCE)
