# macouiscripts

Ouilookup will either:

Take a full or partial MAC as a sole argument and comb oui.txt for that MAC.  When found, it spits out the owner organization

or

Take --update as a sole argument and either download oui.txt from the IEEE if it does not exist, or download a temp (oui2.txt), compare the two, and keep the new one if it is different than the local file

Please note that this is still a work in progress and things may break 

This repo is still called "macouiscriptS" because I used to have the functionality in --update split off into a separate script
