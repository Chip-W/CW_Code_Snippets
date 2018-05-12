# CW_Code_Snippets
**NOTE**
<br>
These snippets are what work for my community server.  They may need to be tweaked a little to work for yours.
<br>
I only supply these snippets to help others.  I do not guarantee they will work for you as they do for me.
<br><br>
# ESX_ADVANCEDFUEL EMERGENCY FUEL SNIPPET
THIS SCRIPT ADD FUEL POINTS AT ALL POLICE STATIONS THAT CAN ONLY BE USED BY ANY VEHICLE WITH THE "FLAG_LAW_ENFORCEMENT"
IN THE VEHICLES.META FILE. <BR><BR>

THESE VEHICLES CAN STILL FUEL AT REGULAR STATIONS.<BR><bR>

I'VE INCLUDED A YMAP FILE THAT PUTS PUMPS AT ALL THE POLICE/FIRE FUEL LOCATIONS<BR><BR>

ISSUES:<BR>
FIRE, AMBULANCE, AND RIOT VEHICLES CAN NOT USE THESE FUEL POINTS UNLESS YOU EDIT THE VEHICLES.META AND ADD THE
"FLAG_LAW_ENFORCEMENT" FLAG.  THIS IS BECAUSE I HAVEN'T BEEN ABLE TO FIND A COMMON NATIVE.<BR><BR>

POLICE PUMPS STILL CHARGE YOU (I HAVEN'T FIGURED THIS OUT YET).<BR><bR>

NAMES ABOVE THE PUMPS DON'T WORK AS THERE APPEARS TO BE A HARD LIMIT TO HOW MANY CAN IN AN ARRAY
<br><br>
# CUSTOM ESX_MENU CSS FILE
See [image](https://media.discordapp.net/attachments/349481476481482752/429406436926423060/20180330173809_1.jpg?width=890&height=501)

# esx_truckshop policejob support
This snippet is for the policejob to recognize the "owned_trucks" table and provide a result when using the vehicle interaction menu as an officer.
One little bug is that it will quickly display the owner's name and then switch to "Unknown".  Just use your controller's back button or backspace one time to view the owner name.
