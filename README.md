# esx_jewelrobbery

This script adds the abality to rob the Vangelico Jewelry  Store for a server.



Features:
 # Config.AllowedWeapons:
 	list for Weapon break chance.  Each weapon can have unique break chance.  If set to 100 will break first try.
 # Config.ItemDrops: 
 	list for Items allows for unique drop chance for each item, as well as max amount player can receive per box.
 # Config.UnAuthJobs:
 	list for server jobs that are not allowed to rob the jewelry store.
 # Config.Closed
 	This setting will close the store if the number of police on the server is lower then the Config.MinPolice.
	
	
  
 	Will receive random amount from Config.MinMoney to  Config.MaxMoney -  default is 5 - 100
	Can set Police Notify Percentage - default is set to 40%
	Can set Always Notify on death -  This will always notify Police of Murder if NPC is killed during mugging.  Once they start running the script will not notify if you kill them.
	Must have Weapon that is not from melee/explosive catagory to start a mugging.
	If you aim at a vehicle that is moving at all (even being pushed) the NPC will ignore the mugging script and act as the game dictates.
	If you aim at a driver of a stopped vehicle the driver will exit the vehicle and put hands up you can then start the mugging.
	Player can stop same NPC but if that npc is last one mugged will not be able to mug again.
	Police Notification gives Alert as well as Circle that will slowly vanish over time (default is 250 seconds - not in Config.lua with this version)
  


This is my first Scrpt for FiveM using Lua. I am sure someone with more experience can trim down the code to make it more streamlined.
I have tested this on a local hosted ESX server as well as a server that I play on. 

I have updated to add config.lua for easier management on a server.  Tried to include the giveableItems list in the config but kept getting a error on trying to pull random item from list in config.  Will look into adding items list in config next update.  For now you will have to change the list at the very top of  main_c.lua to items that are on your server.  

If anyone has any questions feel free to send me message

SpikE
