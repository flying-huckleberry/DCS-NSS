DCS NO SCRIPT SANITIZATION

This is a DCS Server PROGRAM mod, not Saved Games.

Comments out the parts of the DCS code that force script sanitization.

You will need to edit MissionScripting.lua in DCS World/Scripts/MissionScripting.lua and remove the sanitisation. To do this remove all the code below the comment - the line starts "local function sanitizeModule(name)"

The purpose of this mod is to make disabling, updating dcs, and re enabling this mod as efficient as possible for the purpose of using Ciribob's Text To Speech mod:
> https://github.com/ciribob/DCS-SimpleTextToSpeech

This mod however is just for the purpose of using in OvGME and has no direct effect on the Text To Speech mod itself.

Maintained by Huckleberry (A/229)
flyinghuckleberry@gmail.com
