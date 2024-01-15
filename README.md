# FLASHFORGE-5M-PRO-CURA-START-END-GCODE

STABLE BETA FLASHFORGE 5M PRO CURA START/END GCODE 

(Still working on fine tuning the gcode to remove any unnecessary code/movements. You will need to change the M140 S50, M104 T0 S210 to whatever bed temp and nozzle temp you have on the cura settings. For some reason leaving this at the S0 default temp doesnt grab onto the slicer's default temp settings like it should. I have my bed at 50 and my nozzle at 210. The reason for this was to add the purge line that I get with the flashprint slicer. I dont like the FF slicer other than the camera setting)

I have tried using FlashPrint and Orca and they both dont get me quality prints. I know I still need to experiment on Orca more but for some reason using Cura makes my prints look perfect. I did try using the setting from Cura on the FF and Orca but to no avail. 


PLEASE USE THIS GCODE AT YOUR OWN RISK. THE NOZZLE SLIGHTLY TOUCHES THE RIGHT BACK PLASTIC RIM THAT SECURES THE FLEXI BED. I DONT MIND THAT IT DOES THIS AS IT ONLY MELTS A TINY FRACTION OF A MM ON THE PLASTIC AND I AM CURRENTY IN THE PROCESS OF ADJUSTING THE Y MOVEMENT TO PREVENT THIS IN FUTURE ITERATIONS. NOTHING ELSE ADVERSELY HAPPENS TO MY FF 5M PRO AND MY PRINTS COME OUT SUPER CLEAN. I WILL UPLOAD MY CURRENTLY USED CURA PROFILE AS WELL.

For the Cura Printer file (3mf) you can simply drag and drop this file over the open CURA platform and it will recognize it (This will have the cura profile I added separately, so you wont need to use the cura profile unless you want to save it for later use). Select that you want to open it as a project and create a new profile. This way it wont mess with anything else you have set up in CURA. It will load up the FLASHFORGE 5M PRO printer and settings (build volume, nozzle type, default PLA, etc.). You can adjust the slicer settings as needed. I print between 200mm/s & 300mm/s. I don't like the defaults at 400mm/s. You can change any values as you see fit.

V2 of the GCODE I just added no longer requires you to mess with the Temp gcode like in V1. I also adjusted the nozzle so it isnt as close to the rear plastic tab holding the flexi bed on the right side. I will continue to test to ensure that it 100% doesn't come close to it. 
