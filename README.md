# egotopsecret

Server Load Event

--  Check for banned user

--  If banned, display ban reason and length (maybe banning admin?)

Player Load (maybe server load?)
--  Make sure user has proper group (pub-Director) - may not be needed if we have function to check group in MAUL DB when running commands, etc
--  Check for specialty groups (EC, RC, AT, DS) - same as above

Important Functions
--  Hex to Dec Conversion to MAUL
--  Dec to Hex Conversion from MAUL

Needed features:
--  /report or /admin, /le, /ec
--  /kick [id] [reason], /ban [time] [reason] (0 is permanent, anything else is based off minutes) <-- Critical admin commands
--  --Bans must be able to be pushed into MAUL DB and be searched when a player tries connecting and all the usual MAUL fun stuff. 
--  --Add GTA internal DB of bans for IPs and Licenses? <-- is it worth it?
--  /freeze [id] (toggles), /goto [id], /bring [id], /spectate [id] <-- eG+ Commands
--  /setjob [id] [job] [level], /noclip <-- eGO+ Commands
--  /car [hash] <-- EC and Leadership command
--  /givemoney [id] [amount], /set commands, /slap, /slay,  <-- Leadership Commands
--  Whois / who / status command(s) - checks to see user's status in MAUL; kind of like current /admin command

Cool but not necessary
--  Ranks displayed in player list
--  Ranks displayed in OOC chat
--  Tags displayed automatically in player list (players will no longer need to have tags in name because it will show automatically. Must have PUB to show they aren't a member.)
--  Admin panel (like current home menu)