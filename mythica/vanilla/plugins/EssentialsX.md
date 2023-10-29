---
title: EssentialsX
description: The Essentials plugin, in brief
published: true
date: 2023-10-29T20:10:13.898Z
tags: 
editor: markdown
dateCreated: 2023-10-29T20:10:13.898Z
---

# EssentialsX Overview
[EssentialsX](https://www.spigotmc.org/resources/essentialsx.9089/) (Referred to as Essentials) is a continuation of the original Essentials 2 plugin for Bukkit servers, adding support for the latest Minecraft versions. EssentialsX also includes several performance enhancements and fixes on top of the original Essentials, as well as plenty of new useful features for servers.

> Vanilla Mythica Uses Essentials for only a few commands, however more extensive documentation on the Essentials plugin can be found [here](https://essinfo.xeya.me/commands.html)
{.is-info}

# EssentialsX in Vanilla Mythica
Essentials is used to control a number of core functions in the server, from person-to-person teleports, teleports to spawn and home, and similar functions. Essentials also changes the syntax of many moderation commands as well, and gives various features to simplify tasks.

# Common Commands
> When viewing syntax, please note:
> 
> Syntax that is wrapped in `<>` markings are REQUIRED, whereas `[]` markings are OPTIONAL
{.is-info}

## TPA (TP Ask)
### Create tabset {.tabset}
#### Overview
Request that you teleport to another player
#### Command
`/tpa <player>`
#### Aliases
tpask

## TPAHere
### Change tabset {.tabset}
#### Overview
Request that another player teleport to you
#### Command
`/tpahere <player>`
#### Aliases
etpahere

## TPO (TP Override)
### Change tabset {.tabset}
#### Overview
Teleport override for tptoggle (Force Teleport)
> This is a staff only command!
{.is-warning}
#### Command
`/tpo <player>`

## TPOHere
### Change tabset {.tabset}
#### Overview
Teleport here override for tptoggle
> This is a staff only command!
{.is-warning}
#### Command
`/tpohere <player>`

## TP Request Accept
### Change tabset {.tabset}
#### Overview
Accepts teleport requests.
#### Command
`/tpaccept [player|*]`
#### Aliases
etpaccept,tpyes,etpyes

## TP Request Deny
### Change tabset {.tabset}
#### Overview
Rejects teleport requests.
#### Command
`/tpdeny [player|*]`
#### Aliases
etpdeny, tpno, etpno

## TP Positional
### Change tabset {.tabset}
#### Overview
Teleport to coordinates
> This is a staff only command!
{.is-warning}
#### Command
`/tppos <x> <y> <z> [yaw] [pitch] [world]`
#### Aliases
etppos

## TP Random
### Change tabset {.tabset}
#### Overview
Teleport to a random location
#### Command
`/tpr`
#### Aliases
etpr, tprandom, etprandom

## TP Auto Accept
### Change tabset {.tabset}
#### Overview
Automatically accept teleportation requests.
#### Command
`/tpauto [player]`
#### Aliases
etpauto

## Spawn Teleport
### Change tabset {.tabset}
#### Overview
Teleports player to the spawnpoint
#### Command
`/spawn [player]`
> Please note that only staff can use the player parameter
{.is-warning}
#### Aliases
espawn

## Warp
### Change tabset {.tabset}
#### Overview
List all warps or warp to the specified location.
#### Command
`/warp <pagenumber|warpName> [player]`
> Please note that only staff can use the player parameter
{.is-warning}
#### Aliases
ewarp, warps, ewarps

## Warp Information
### Change tabset {.tabset}
#### Overview
Finds location information for a specified warp.
#### Command
`/warpinfo <warp>`
#### Aliases
ewarpinfo

## Set Homes
### Change tabset {.tabset}
#### Overview
Set home to your current location.
#### Command
`/sethome [player:]<name>`
> Please note that only staff can use the player parameter
{.is-warning}
#### Aliases
esethome, createhome, ecreatehome

## TP Home
### Change tabset {.tabset}
#### Overview
Teleport to your home.
#### Command
`/sethome [player:]<name>`
> **Please Note:** If you have only ONE home, you are not required to list the home name.
{.is-info}

> Please note that only staff can use the player parameter
{.is-warning}
#### Aliases
ehome,homes,ehomes

## Delete Home
### Change tabset {.tabset}
#### Overview
Removes a home
#### Command
`/delhome [player:]<homeName>`
> Please note that only staff can use the player parameter
{.is-warning}
#### Aliases
edelhome, remhome, eremhome, rmhome, ermhome

# General Commands

> When viewing syntax, please note:
> 
> Syntax that is wrapped in `<>` markings are REQUIRED, whereas `[]` markings are OPTIONAL
{.is-info}

## Private Message Toggle
### Change tabset {.tabset}
#### Overview
Blocks receiving all private messages.
#### Command
`/msgtoggle [player] [on|off]`
#### Aliases
emsgtoggle

## Gamemode
### Change tabset {.tabset}
#### Overview
Changes the player gamemode
> This is a staff only command!
{.is-warning}

#### Command
`/gamemode <survival|creative|adventure|spectator> [player]`

#### Short Commands
Creative: `/gmc [player]`

Survival: `/gms [player]`

Adventure: `/gma [player]`

Spectator: `/gmsp [player]`
#### Aliases
adventure, eadventure, adventuremode, eadventuremode, creative, eecreative, creativemode, ecreativemode, egamemode, gm, egm, gma, egma, gmc, egmc, gms, egms, gmt, egmt, survival, esurvival, survivalmode, esurvivalmode, gmsp, sp, egmsp, spec, spectator

## Hat
### Change tabset {.tabset}
#### Overview
Get a some cool new headgear
#### Command
`/hat [remove]`
#### Aliases
ehat, head, ehead

## Worth
### Change tabset {.tabset}
#### Overview
Calculates the worth of items in hand or as specified.
#### Command
`/worth <<itemname>|<id>|hand|inventory|blocks> [-][amount]`
#### Aliases
eprice, price, eworth

# Essentials Economy Commands
The SMP uses the Essentials plugin to manage anything based around the economy. Essentials gives the power to sell certain items to the server for a set cost. There are also a variety of commands that can be used to help inform you and perform transactions.

## Sell
### Change tabset {.tabset}
#### Overview
Sells the item currently in your hand.
#### Command
`/sell <<itemname>|<id>|hand|inventory|blocks> [amount]`
#### Aliases
esell

## Pay
### Change tabset {.tabset}
#### Overview
Pays another player from your balance.
#### Command
`/pay <player> <amount>`
#### Aliases
epay

## Pay Toggle
### Change tabset {.tabset}
#### Overview
Toggles whether you are accepting payments.
#### Command
`/paytoggle [player]`
#### Aliases
payon

## Pay Confirmation Toggle
### Change tabset {.tabset}
#### Overview
Toggles whether you are prompted to confirm payments.
#### Command
`/payconfirmtoggle`
#### Aliases
epayconfirmtoggle, payconfirmoff, epayconfirmoff, payconfirmon, epayconfirmon, payconfirm, epayconfirm

## Top Balance List
### Change tabset {.tabset}
#### Overview
Lists players by top balances.
#### Command
`/baltop [page]`
#### Aliases
ebalancetop, baltop, ebaltop

## Balance
### Change tabset {.tabset}
#### Overview
States the current balance of a player.
#### Command
`/balance [player]`
#### Aliases
bal, ebal, ebalance, money, emoney
