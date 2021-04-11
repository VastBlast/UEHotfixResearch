## Unreal Engine Hotfix System: 
##### (Mostly focused on Fortnite)

#### - Overview:

- Unreal Engine Hotfix is an engine plugin,
In simple terms: this plugin aims to provide the game devs to have a *quick* but efficient access to adjust classes \ edit it's default values, without the need to push a build to address the changes, mostly used for emergency proposes.
<br>

- Focusing on Fortnite more. Fortnite's Hotfix system is pretty much the same as the default engine one, as well as some changes; Fortnite provides it's hotfixes using it's api "CloudStorage" Service.
<br>

- UE4 Games has Configuration Files `DefaultXXXXX.ini`s, these files are Text files containing property settings for configuring gameplay or engine behavior. Basically some default values for some classes\plugins, They are usually stored in `.pak` files, For more info refer to the official documentation [here](https://docs.unrealengine.com/en-US/ProductionPipelines/ConfigurationFiles/index.html).
<br>


- The Hotfix System can adjust\change values in those files which can be really usefull in so much situations, for example: "Disabling\Nerfing some overpowered weapon by adjusting it's datatable values". 
<br>

- Default UE4 configuration categories are `Compat, DeviceProfiles, Editor, EditorGameAgnostic, EditorKeyBindings, EditorUserSettings, Engine, Game, Input, Lightmass, Scalability`. Some of them are Editor only as you can tell, Fortnite has the main ones `Engine, Game, Input, etc..` as well as some custom ones `e.g: DefaultRuntimeOptions`, However, in this documentation we'll be focusing only on the ones used by fortnite.
<br>

---

#### - UE4 Configuration Files and Hotfixing:

- **Engine**: This files are used for object and variable default values for Engine Classes, As you should've gussed, This file inherits **Engine** UClasses and UProperties, Looking for the class you want in the engine source should be enough.
<br>

- **Game, Input (And more)**:
Those are the same as Engine except that these files inherit **Game** UClasses and UProperties, to acknowledge all the possibilities you have to look directly at the game source code which we don't have access to; However, We can look at Unofficial SDKs and track the ones at pak files and hotfixes the game pushes to document them. Fortnite hotfixes are tracked here: [NiteStats](https://discord.gg/wJp9ZEp) | [Epic Server Version Status](https://discord.gg/z9TPuevz6s), SDKs are widely spread all over the internet (Just google it) and it can be really useful for hotfixing, here's an example: 

```cpp
// SDK

// Class FortniteGame.FortGlobals
class UFortGlobals : public UObject
{
public:
    struct FString LobbyMap;       
    //...
};
```

```ini
; DefaultGame Hotfix

[/Script/FortniteGame.FortGlobals]
; LobbyMap is "Frontend" by default
LobbyMap=Apollo_Terrain
```
###### *Pretty Cool, Huh? ;)*
<br>

- **Runtime Options**:
As the name sounds it's for "Runtime Options", as stated [here](https://docs.unrealengine.com/en-US/API/Runtime/Engine/Engine/URuntimeOptionsBase/index.html) `Supports checking at runtime whether features are enabled/disabled, and changing configuration parameters via console cheats or startup commands.`. However, Fortnite has it's own implementation `UFortRuntimeOptions` which inherits `URuntimeOptionsBase`, In a sense `DefaultRuntimeOptions.ini` has access to both classes; Again, Both classes can be found in SDKs and hotfixed the exact same way as the example shown above.
<br>

- **Hotfixes Documentation**:
Unofficially tracked and documented **fortnite** hotfixes for a wide variety of configuration files can be found [here](/docs/Fortnite).
<br>

###### Written with ♥ by [kemo](https://github.com/kem0o)
