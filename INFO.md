# Trojan

Trojan (.tj) is a Lua based programming language for creating Roblox programs with AIDA.

## Installation

Click [here](https://www.roblox.com/groups/14847351/TrullzSec#!/about) for a template on creating your own program with Trojan.

Below is the loadstring for ADIA.

```bash
Loadstring here
```

## Compatibility

As of the executors tested, here are the working ones as of 6/22/22.
### Synapse


# Documentation

The official Trojan documentation (6/22/22)

# Section 1
## Part A - Introduction

Trojan is compact, easy to use and reliable coding language that takes simplicity to another level. Helping users create cool, interesting and creative tools and programs for others to install and fiddle with.

Trojan works by creating easy to use varibles that are linked to many different functions. This allows simple commands to run complex functions resulting in a cleaner workflow, and overall increase in productivity.

Trojan is coded in Roblox's frankenstien of language (a mixture of C++ and Lua), and works as the primary language in AIDA (CLI Terminal for Roblox). A lot of the main core functions that help Trojan stay reliable and on top in regards to its combatility with Synapse and other injection softwares. With that in mind, it helps us to push the limits everyday- and we hope other can be inspired enough to check out ADIA and maybe give coding with Trojan a try!

## Part B - Variables

A lot of Trojan, and how its used, is coded from Variables. They help a lot in keeping everything very tight and secure. As well as improving the simplicity of Trojan.

Program Variables

The program name is very important. It tells the script that runs Trojan, "Hey, this is the programs name". Trojan takes this information and uses it to keep track of whats what- as it's very important if you are trying to find your program that there is a program name.
```lua
local ProgramName = "e.g. Pineapple CMDS"
```

The program version is quite simple in itself. Simply it's the version of your program and comes in useful when keeping track on updates etc.
```lua
local ProgramVersion = "e.g. 0.0.1"
```

The program type is easily one of the most important questions you need to answer. A simply reponse can change the whole functionality of your program, so it's recommended to really plan things out prior to beginning your code.
A terminal based program is much like Metasploit, Wifite or really any other program that is based completely in the terminal (keep in mind, there isn't much of a difference between a terminal based program, and a UI based program. It's really only personaly preference and your care for UX design). Also, please make sure to spell it correctly. Small mistakes can lead to major problems when messing with the Program Variables.
```lua
local ProgramType = "Terminal/UI"
```

The UI loadstring is a primary tool if you've taken the UI route. This is the function ADIA will call to when your program is launched, so ensure that its all tight and secure.
```lua
local UILoadstring = "Loadstring Here"
```

Assets are a super cool tool within AIDA, and benefit people who have taken the 'Terminal' route. It also allows for a cross between a 'Terminal' and a 'UI' program.
```lua
local Assets = true/false
```

A prefix is super important when installing new assets. E.g. if I was installing a new asset and my prefix was "gu", then to download my asset, I would simply type the command "gu install Asset" after creating my local directory, more on that later.
```lua
local Prefix = "e.g. gu"
