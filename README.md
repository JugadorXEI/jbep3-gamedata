# jbep3-gamedata
Gamedata for JBEP3 (SDK 2013 MP Mod) taken 19 July, 2018.

Since SourceMod doesn't have offsets and signatures for Jabroni Brawl: Episode 3, it ends up using the default ones and as result, its capabilities become greatly limited, so I bothered to get them so SourceMod works properly. This is meant for server owners that host a JBEP3 dedicated server and wish to get/update their gamedata to have access to commands such as `sm_slay`, for example, and for developers allowing them to develop plugins for this mod.

If something is broken/outdated, please let me know through a Github issue, or Discord (JugadorXEI#8724).

Tested on both Windows and Linux servers.

## Installation instructions:
This assumes you have SourceMod installed on your dedicated server. If not, go here: https://wiki.alliedmods.net/Installing_SourceMod

1. Go to sourcemod/configs, open core.cfg, search for the "DisableAutoUpdate" key and set it to "yes". This will prevent SourceMod to update its own gamedata (something that JBEP3 doesn't receive in any official capacity).
2. Drag and drop the gamedata folder from this Github to your sourcemod folder. It will replace a few files (specifically the `master.games.txt`ones).
3. Done!
It should be noted that if you don't do the first step, SourceMod will replace the `master.games.txt` files, thinking that they are outdated and preventing you from using this gamedata.

### What does this gamedata give:
If you are a server owner, then here's pics instead:

- Menu using HudRadioMenuMsg like CSS and TF2 has, which is vastly superior than the alternative:

![Doesn't it make you nostalgic?](https://files.catbox.moe/vli3we.png)

- sm_drug in action (previously it didn't work before):

![Trippin', indeed](https://files.catbox.moe/m2frrn.png)

...And basically compatibility with everything else that didn't work before.


## Credits:
Shoutouts/special thanks to Zero (iamthezero#7483 on Discord) for allowing me to get a hold of the mod's Linux binaries with symbols.

[Donate to AlliedModders](https://www.sourcemod.net/donate.php) because they are who they keep SourceMod alive, and they're really helpful.

<a href='https://ko-fi.com/jugadorxei' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Donate if you think JBEP3 deserves a better EU server.' /></a>