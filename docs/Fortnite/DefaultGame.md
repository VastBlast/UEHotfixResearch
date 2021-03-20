## [/Script/FortniteGame.FortTextHotfixConfig]
| Type | Key | Note |
| - | - | - |
| | | |
| Array | TextReplacements | Model: `(Category=Game, bIsMinimalPatch=True, Namespace="", Key="SomeStringKey", NativeString="SomeStringBefore",LocalizedStrings=(("en","SomeStringAfter")))` |


---
## [/Script/FortniteGame.FortGameInstance]
| Type | Key | Note |
| - | - | - |
| | | |
| Integer | KairosMinSupportedAppVersion | |
| Boolean | bBattleRoyaleMatchmakingEnabled | Enables or disables the ability to matchmake into a Battle Royale playlist |
| Boolean | bCreativeModeProfileEnabled | |
| Array | FrontEndPlaylistData | Model: `(PlaylistName=Playlist_PlaylistId, PlaylistAccess=(bEnabled=false, bIsDefaultPlaylist=false, CategoryIndex=0, bDisplayAsLimitedTime=false, DisplayPriority=8), AccessOverrides=((Regions=(\"ALL\"), Platforms=(\"ALL\"), OverrideAccess=(bEnabled=false, bIsDefaultPlaylist=false, bDisplayAsLimitedTime=False, DisplayPriority=8)))` |


---
## [/Script/Account.OnlineAccountCommon]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bEnableWaitingRoom | |
| Boolean | bRequireLightswitchAtStartup | |


---
## [/Script/FortniteGame.FortGlobals]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bAthenaLeaderboardFrontEndEnabled | |
| Boolean | bAthenaStatsFrontendEnabled | |
| Boolean | bGlobalLeaderboardsFrontEndEnabled | |


---
## [/Script/FortniteGame.FortMatchmakingV2]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bCustomKeyEnabled | |
| Array | AltDomainRecords | Model: `(OriginalDomain="intial.matchmaking.domain", AltDomain="alternate.matchmaking.domain")`|
