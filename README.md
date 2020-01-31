# esx_jewelrobbery

This script adds the abality to rob the Vangelico Jewelry  Store for a server.



# Features:

  	<b>AllowedWeapons</b>:
 	list for Weapon break chance.  Each weapon can have unique break chance.  If set to 100 will break first try.
	
	ItemDrops: 
 	list for Items allows for unique drop chance for each item, as well as max amount player can receive per box.
	
	UnAuthJobs:
 	list for server jobs that are not allowed to rob the jewelry store.
	
	Config.Closed:
 	This setting will close the store if the number of police on the server is lower then the Config.MinPolice.
	


This is my first Scrpt for FiveM using Lua. I am sure someone with more experience can trim down the code to make it more streamlined.
I have tested this on a local hosted ESX server as well as a server that I play on. 

I have updated to add config.lua for easier management on a server.  Tried to include the giveableItems list in the config but kept getting a error on trying to pull random item from list in config.  Will look into adding items list in config next update.  For now you will have to change the list at the very top of  main_c.lua to items that are on your server.  

If anyone has any questions feel free to send me message

SpikE
