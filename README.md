# Ability-Framework
Tool-Based Ability Framework

Hello! This is a tool-based ability framework developed by VALENTINE. The point of this framwork is to : 
- Allow for the use of tools without dedicated local scripts to listen for equipping for every tool 
- Allow for the use of client-based modules without the overhead of constantly requiring the module to run the ability locally
- Prevent the use of two serverside scripts to run the same ability, which would lead to two serverside events running at once
- This is a one-way communication (mostly) as opposed to a tool's normal client to server to client.

This framework allows for you to drop in a name in a dictionary which corresponds to a tool's name, and to the name of the script 
you want to run with the ability in question. It checks to make sure the player is supposed to have the ability before executing it, 
so it's safe against bugs and exploits. 

