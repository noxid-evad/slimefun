---
description: Useful commands for understanding towny
---

# Town Commands

## Towny Commands

|    Commands   |                      Description                      |
| :-----------: | :---------------------------------------------------: |
|     /towny    |               Shows basic towny commands              |
|    /towny ?   |               Shows more towny commands               |
|   /towny map  |                  Shows the towny map                  |
| /towny prices |    Shows taxes/costs associated with running a town   |
|   /towny top  |                  Shows top residents                  |
|  /towny time  | hows time until next new-day (tax/upkeep collection.) |

## Town Commands

|              Commands             |                                                     Description                                                    |
| :-------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
|               /town               |                                       Shows a player their town's town screen                                      |
|              /town ?              |                                           Shows /town commands available                                           |
|           /town \<name>           |                                     Shows the information on the specified town                                    |
|             /town list            |                                         Shows town list display information                                        |
|            /town online           |                                     Shows players in your town which are online                                    |
|            /town leave            |                                                    Leaves a town                                                   |
|             /town here            |                              Shows you the town screen of the town in which you stand                              |
|            /town spawn            |                                         Teleports you to your town's spawn                                         |
|            /town claim            |                        Mayor command to claim the townblock in which you stand for your town                       |
|        /town claim outpost        | Claims an outpost for your town. {name} uses the plot name. {name:#} is used when a plot name begins with a number |
|           /town unclaim           |                              Mayor command to unclaim the townblock in which you stand                             |
|     /town buy bonus \<amount>     |                                           Buys available bonus townblocks                                          |
|      /town withdraw \<amount>     |                                            Removes money from town bank.                                           |
|      /town deposit \<amount>      |                                       Adds money from player to the town bank                                      |
|        /town create \<name>       |                                                 Creates a new town                                                 |
|            /town delete           |                                                   Deletes a town                                                   |
|        /town invite \<name>       |                            Show a list of players who've been sent invites to your town                            |
|  /town invite+ \<name1> \<name2>  |                            Show a list of players who've been sent invites to your town                            |
|         /town kick \<name>        |                                  Mayor command to remove residents from your town                                  |
|   /town kick+ \<name1> \<name2>   |                                  Mayor command to remove residents from your town.                                 |
|   /town rank add \<name> \<rank>  |                                       Grants a rank to a resident of the town                                      |
| /town rank remove \<name> \<rank> |                                      Removes a rank to a resident of the town                                      |
|      /town set mayor \<name>      |                               Mayor command to give mayor status to another resident                               |
|     /town set board \<message>    |                                               Shows board information                                              |
|        /town set homeblock        |                                      Sets the homeblock and spawn of your town                                     |
|          /town set spawn          |                               Sets the town spawn, must be done inside the homeblock                               |
|             /town set             |                                            Shows set display information                                           |
|     /town set taxes \<amount>     |           Sets taxes collected from each resident daily. Also sets percentage if taxpercent is toggled on          |
|    /town set plottax \<amount>    |                        Set taxes collected from each resident daily, per plot that they own                        |
|       /town set name \<name>      |                                               Change your town's name                                              |
|       /town toggle explosion      |                                           Turn on/off explosions in town                                           |
|         /town toggle fire         |                                           Turn on/off firespread in town                                           |
|         /town toggle mobs         |                                       Turn on/off hostile mobspawning in town                                      |
|        /town toggle public        |         Turn on/off public /town spawning and the co-ordinates of the town's homeblock in the /town screen         |
|          /town toggle pvp         |                                               Turn on/off pvp in town                                              |

## Plot Commands

|         Commands        |                           Description                          |
| :---------------------: | :------------------------------------------------------------: |
|         /plot ?         |                    Shows the /plot commands                    |
|        /plot set        |                  Shows set display information                 |
|        /plot perm       |   Shows the perm line of the plot in which the player stands   |
|       /plot toggle      |                Shows toggle display information                |
|       /plot claim       | Resident command to personally claims a plot that are for sale |
|      /plot unclaim      |       Resident command to unclaim personally owned plots       |
| /plot forsale \<amount> |                       Set a plot for sale                      |
|     /plot notforsale    |                  Set a plot to not be for sale                 |

## Resident Commands

|                  Commands                 |                       Description                      |
| :---------------------------------------: | :----------------------------------------------------: |
|                 /resident                 |          Shows a player their resident screen          |
|                /resident ?                |              Shows /res commands available             |
|             /resident \<name>             |            Brings up \<name> towny overview            |
|               /resident tax               |                Shows taxes a player pays               |
|        /resident friend add \<name>       |    Resident adds online player to their friends list   |
|      /resident friend remove \<name>      | Resident removes online player from their friends list |
|             /resident set perm            |           Shows set perm display information           |
| /resident set perm \<friend/ally/outside> |         Modify all perms for a particular group        |

## Extra Commands

{% hint style="warning" %}
/tc\
Toggles town chat\
\
/nc\
Toggles nation chat\
\
/g \
Toggles global chat
{% endhint %}
