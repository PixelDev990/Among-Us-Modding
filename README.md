<p align="center">Please Note that i've included peasapi as its easy for begginers and the creator "PeasPlayer" did not contribute to this repository and i have credited him because of his wonderfull api.</p>

# Getting Started...
## Chapter 1 \[Basic Modding]
Plugins:
<br>
[Docs & Builds](https://docs.reactor.gg) (API for modding) 
<br>
[Role Api](https://docs.peasplayer.tk/among-us-lessons/) (For making it easy) 
<br>
[For Custom Settings](https://github.com/DorCoMaNdO/Reactor-Essentials)
## Once you finish all installation steps do this:
Ill be showing you how to make a role now:
(put the file as role.cs in your exampleproject/modname directory)
<br>
[Role Src Here](https://github.com/PixelDev990/Among-Us-Modding/blob/main/AU-Modding%20Src/Roles/ExampleImposter.cs)
<br>
[Full Code Here](https://github.com/Peasplayer/ExampleAmongUsMod/blob/master/ExampleMod/)
<br>
Thanks to peasplayer 

## Got an error? No problem!
[Support](https://reactor.gg)
## To finish up build your mod and setup a server!

To make a server the best software i'd say is [Hindenburg](https://github.com/SkeldJS/Hindenburg)
<br>
Once you setup your hindenburg server you're free to play and test you're role with your friends!

## Chapter 2 \[SomeWhat Advanced]
Custom Rpc's and Settings
<br>
[Code Used](https://github.com/eDonnes124/Town-Of-Us-R/tree/master/source) (Town Of Us code is the best example)

## Custom Rpc's
What is a Custom Rpc?
<br>
Custom rpc is kind of a setting used to determine the roles in the mod for its custom settings or timers.
<br>
How to make an rpc?
<br>
Lets make a custom rpc for our example role shall we?
```cs
namespace ExampleMod
{
    public enum CustomRPC
    {
        SetExampleImposter = 100,    
            }
          } 
        }
      }
    }
  }
}
```
Welp Thats an rpc....
## Custom Settings
These are the things with which you set your cooldowns and buttons and have to be implemented in you `mod.cs` file
_Pending....
    
# Next Chapter - (Custom Cosmectics and Custom Colors)



@2022 Rezend Inc. [PixelKing]
<br>
*This repository is owned and maintained by Pixelking and if there are any mistakes please dm me on discord (socials on profile)*
