# CSGO-CFG
CFG for CSGO

# A bit of Knowleadge
## What is this?
Is a CFG for CSGO to automatically set your settings to play. ( Execept Graphics Settings ) Mostly for MM Competitive but for other types of competitions is allowed to. - Report back if there is something illegal. ( I think Jumpthrow bind is illegal in some competitons, but I really don't know. )

## Do I need it?
Not exactly, but you can try it and decide for yourself it you want it or NEED it. :P

## Instructions:
1. Download the proyect by going [here](../../releases) or [from mega](https://mega.nz/#F!PggQCKSI!13NWNAGvXvwu_fzZAzBNhg).
2. Place the CFGs into your CSGO CFG folder ( ..\steamapps\common\Counter-Strike Global Offensive\csgo\cfg ).
3. Edit it by changing the Sensitivity, Personal Color, Hud Color... etc in other to adapt it to your liking.
4. Launch CSGO and press F10 to open the console. Type in "exec autoexec" or "Autoexec" ( CFG needs to be re-executed in order to properly work ).
5. You can either start playing or utilize the follow Launch options ( CSGO need to be restarted in other to make them work ):

-novid : Disables Intro Video - Most recomended

-tickrate 128 : Set Client Server to Tickrate 128 ( Default is 64 ) - Only recomended if you have a good PC. ( Only afects Client server - AKA Play with bots )

-maxplayers_override 40 : Allows 40 people to connect ( Default is 10 - 9 + You ) - Only recomended if you have a good PC. ( Only afects Client server - AKA Play with bots )

-nobrowser : Disable Browser inside CSGO. Like cl_disablehtmlmotd, but better. - Most Recomended.

-language : Change language of Counter-Strike to any other available. Ex: -language spanish - Recomended if you want Steam in one language and CS in another.

# Features:
Console enabled.
Music removed and 10 Sec bomb to min so you know it.
Matchmaking Ping search to 25.
Mouse Raw Input and No acceleration by default.
Small Net Graph.
Enable friends to follow you on your games.
Killcam disabled.
Competitive Rates.
Sounds won't be downloaded when entering a server.
FPS unlimited except on Menu.
3 Crosshair types.
Invitations to play will only be able if on Main menu.
Game Instructor Disabled.

## Keys                                                                  
                                                                          
F1         : Toogles Crosshair for better nades.
F2         : Change Crosshair.
F3         : Toogle Instructor.
F10        : Toogle Console.
PGUP       : Toogle IgnoreMsg.
             Status: Broadcast, Team/Broadcast, All chat, Accept all.
T          : Change to defuse Mode. Hold E and Swing your mouse to spin.
PGDN       : Toogle IgnoreRadar.
BlockMayus : Toogle Weapon Side.
F          : Jump Throw - Simply Select Nade, Charge to Throw and press F.
H          : Inspect Weapon.
L          : Enables X-Ray on Demo playback.
Z          : Radio Commands - Go, Fall Back, Stick Together Team, Hold This Position, Follow Me.
X          : Radio Commands - Enemy Spotted, Need Backup, You Take the Point, Sector Clear, I'm in Position.
C          : High Jump - Jump as High as CS is posible.
V          : Clean everything - Console, blood, bullet holes... everything.
N          : Mute voices.
KP_Enter   : Change Radar size.
Left ALT   : Radio Commands - Affirmative/Roger, Negative, Cheer!, Compliment, Thanks.
Mouse3     : Basic Radio Commands - Affirmative/Roger, Negative, Cheer!, Hold This Position, Follow Me, Thanks.


## Commands

Autoexec   : Runs Autoexec config.
Training   : Runs Training config.
HelpMe     : Displays this infobox. ( Requires HelpMe.cfg )
Clean      : Clean everything cleanable.
Moded      : Displays CFG last modification date and time on console
MM_MaxPing : Display Max Search ping for MM. Also shows original command to modify it.

### Remember
You can edit the keys by editing the CFG. Any changes through Console will be wipe out, so if you make any, just edit the Autoexec CFG and edit the values, or add it.
Don't forget to edit the HelpMe.cfg if you modify any Bind.
