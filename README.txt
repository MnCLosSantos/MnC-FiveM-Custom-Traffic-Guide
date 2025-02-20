

     -------------- how to create custom traffic for your server (new qb-core) --------------


  1  -  download the resource 

  2  -  extract and put into resources, and remove "FiveM-" and "-main" from the downloaded resources name
      (i recomend that you create a file called "[trafficaddon]" in resources and put "custom_traffic" in there.)
 
  3  -  open openiv "https://openiv.com/"
 
  4  -  go here in file directory in openiv "Grand Theft Auto V\update\update.rpf\x64\levels\gta5"
 
  5  -  find popgroups.ymt and right click and export as an xml too remove the encription
 
  6  -  use visual studio code "https://code.visualstudio.com/" to open the xml/txt file
 
  7  -  change the spawn codes starting at line "6212"
 
  8  -  save the file as "all files" not a xml or txt, Make sure to call it "popgroups.ymt". 
        Save it in the "custom_traffic" folder or put it in there. should now be a "ymt" file

  9  -  delete this file "this where you want too save the ymt file.txt"
 
 10  -  go too this file path "resources\[qb]\qb-smallresources and delete the "popgroups.ymt" from within qb-smallresources.
 
 11  -  open the fxmanifest within qb-smallresources and delete these lines completely "24" and "28" and save
 
 12  -  go to your server.cfg file and ensure the folder "[trafficaddon]" and "custom_traffic" example ready to copy below
 
## traffic addon
ensure [trafficaddon]
ensure custom_traffic
 
 13  -  change ped density in "resouces/qb/qb-smallresources/config.lua" on line "74" to "79"
 
 14  -  restart your server
 
 
