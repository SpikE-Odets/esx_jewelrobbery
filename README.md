# esx_jewelrobbery

This script adds the abality to rob the Vangelico Jewelry  Store for a server.



# Features:
	
	Store can be robbed by multiple players at same time.  No need to shoot to start robbery.
	Store can be closed by police after robbery attempt - to keep smash and grab happening over and over.
	Store can auto close if not enough police on for a robbery.
	If store closes while you are inside, Employee's will help you outside after explaining the store is closed.
	
	Each weapon that is allow to break glass can have a different break chance percent.
	Each Item that can drop from a glass box - can have different drop percent(rare) as well as max amount.
	
	Server is able to set UnAuthJobs that will not be able to rob the Jewerly Store.
	Server can set multiple Police Job by name that will receive robbery notification / be able to close store.
	
	Sounds for breaking/failing glass case.  Breaking sound can not be turned off / fail sound can be turned off.
	
	Security feature to keep one box paying out multiple times.


# Settings:

  	AllowedWeapons:  List for Weapon break chance.  Each weapon can have unique break chance.  If set to 100 will break first try.
	
	ItemDrops:  List for Items allows for unique drop chance for each item, as well as max amount player can receive per box.
	
	UnAuthJobs:  List for server jobs that are not allowed to rob the jewelry store.
	
	Config.Closed:  This setting will close the store if the number of police on the server is lower then the Config.MinPolice.
	
	Config.AllowPoliceStoreClose:  Allows police to close the store after a robbery until next Store Reset.
	



SpikE
