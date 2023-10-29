---
title: factions
description: 
published: true
date: 2023-10-29T19:39:10.148Z
tags: 
editor: markdown
dateCreated: 2023-10-29T17:46:32.398Z
---

# Overview
> Somehow, the plugin authors have done so little documentation that the best option we have is to use the UniversalCraft documentation as a diving board and move from there. Due to this, this plugin page MAY be missing portions of commands, although we believe they should be properly accounted for.
{.is-warning}

SaberFactions is an advanced (yet badly documented) factions plugin for use with Minecraft Java servers based on MassiveCrafts Factions plugin, similar to Mythica Vanilla. SaberFactions is used to create new factions, wage wars, and manage claimed land in an easy-to-use manner.

# Commands Layout
> When viewing syntax, please note:
> 
> Syntax that is wrapped in `<>` markings are REQUIRED, whereas `[]` markings are OPTIONAL.
{.is-info}

The documentation for SaberFactions will be divided into divisions based on their overall usage, and frequency. If you are viewing on PC, you may see a quick reference area to the left-hand side of the screen that you may be able to use to assist navigation.

Note that all `/faction` commands can be shortened to just `/f`

# Faction Information Commands
## List
### List tabset {.tabset}
#### Overview
Displays a list of all existing factions.
#### Command
`/factions list` or `/f list`

## Who (Faction Lookup
### Who tabset {.tabset}
#### Overview
Inspect or lookup a specific faction from /f list
#### Command
`/factions top <factionName>` or `/f top <factionName>`

# Faction Creation and Update Commands

## Create
### Create tabset {.tabset}
#### Overview
Create a new faction. Names must consist of up to 10 letters or numbers. Spaces and punctuation are not permitted.
#### Command
`/factions create <factionName>` or `/f create <factionName>`
#### Notes
Since each player can only be a member of one faction at a time, you must leave your current faction if you wish to create a new one

## Change Description
### Change tabset {.tabset}
#### Overview
Change the description of your faction as it appears on `/f who` or when wandering into faction chunks.
#### Command
`/factions description <description>` or `/f description <description>`

## Change Faction Name
### Change tabset {.tabset}
#### Overview
Change the faction's "Tag Name" (Faction Name)
#### Command
`/factions tag <newFactionName>` or `/f tag <newFactionName>`
#### Notes
You cannot use a name already used by another faction

# Faction Member Commands

## Join a Faction
### List tabset {.tabset}
#### Overview
Joins a specified faction
#### Command
`/factions join <factionName>` or `/f join <factionName>`
#### Notes
If a faction is not open, you must be invited to be able to join the faction first. Factions are closed by default.

## Go to the Faction Home
### List tabset {.tabset}
#### Overview
Teleport your character to the home location of the faction you belong to.
#### Command
`/factions home` or `/f home`

## Broadcast Location
### List tabset {.tabset}
#### Overview
Broadcasts your location to faction members
#### Command
`/factions coords` or `/f coords`

## Switch to Faction chat
### List tabset {.tabset}
#### Overview
Switches to faction, ally, or public chats
#### Command
`/factions chat <Faction | Ally | Public>` or `/f chat <Faction | Ally | Public>`

## Faction Chest
### List tabset {.tabset}
#### Overview
Opens a shared virtual faction chest
#### Command
`/factions chest` or `/f chest`

## Faction Alert (WeeWoo)
### List tabset {.tabset}
#### Overview
Alert faction members that you are being raided
#### Command
`/factions weewoo <start/stop>` or `/f weewoo <start/stop>`

# Faction Member Management
## Invite
### List tabset {.tabset}
#### Overview
Alert faction members that you are being raided
#### Command
`/factions weewoo <start/stop>` or `/f weewoo <start/stop>`

## Invite
### List tabset {.tabset}
#### Overview
Invites a member to your faction
#### Command
`/factions invite <playerName>` or `/f invite <playerName>`

## Retract Invite
### List tabset {.tabset}
#### Overview
Retracts an invite to your faction
#### Command
`/factions deinvite <playerName>` or `/f deinvite <playerName>`

## Kick
### List tabset {.tabset}
#### Overview
Kicks a player from your faction
#### Command
`/factions kick <playerName>` or `/f kick <playerName>`

## Ban
### List tabset {.tabset}
#### Overview
Bans the specified player which prevents them from using the /factions join command to enter your faction
#### Command
`/factions ban <playerName>` or `/f ban <playerName>`

## Ban List
### List tabset {.tabset}
#### Overview
Lists the players banned in your faction
#### Command
`/factions banlist` or `/f banlist`

## Transfer Ownership
### List tabset {.tabset}
#### Overview
Transfers ownership of your faction to the specified faction member
#### Command
`/factions leader <playerName>` or `/f leader <playerName>`

## Promote to Co-Leader
### List tabset {.tabset}
#### Overview
Promotes the specified player to the role of Co-Leader
#### Command
`/factions coleader <playerName>` or `/f coleader <playerName>`

## Promote to Mod
### List tabset {.tabset}
#### Overview
Gives moderator permissions to the specified player in your faction
#### Command
`/factions mod <playerName>` or `/f mod <playerName>`

## Faction InventorySee
### List tabset {.tabset}
#### Overview
See inside a faction member's inventory
#### Command
`/factions invsee <playerName>` or `/f invsee <playerName>`

# Faction Base Commands

## Set Home
### List tabset {.tabset}
#### Overview
Sets a faction home to your current location
#### Command
`/factions sethome` or `/f sethome`

## Warp
### List tabset {.tabset}
#### Overview
Opens the warp menu
#### Command
`/factions warp` or `/f coleader warp`

## Set Warp
### List tabset {.tabset}
#### Overview
Sets a faction warp to your location
#### Command
`/factions setwarp` or `/f setwarp`

