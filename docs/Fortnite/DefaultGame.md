## [/Script/FortniteGame.FortTextHotfixConfig]
| Type | Key | Note |
| -------- | -------- | -------- |
| Array | TextReplacements | Model: `(Category=Game, bIsMinimalPatch=True, Namespace="", Key="SomeStringKey", NativeString="SomeStringBefore",LocalizedStrings=(("en","SomeStringAfter")))` |


---
## [/Script/FortniteGame.FortGameInstance]
| Type | Key | Note |
| -------- | -------- | -------- |
| Integer | KairosMinSupportedAppVersion | |
| Boolean | bBattleRoyaleMatchmakingEnabled | Enables or disables the ability to matchmake into a Battle Royale playlist |
| Boolean | bCreativeModeProfileEnabled | |
| Array | FrontEndPlaylistData | Model: `(PlaylistName=Playlist_PlaylistId, PlaylistAccess=(bEnabled=false, bIsDefaultPlaylist=false, CategoryIndex=0, bDisplayAsLimitedTime=false, DisplayPriority=8), AccessOverrides=((Regions=(\"ALL\"), Platforms=(\"ALL\"), OverrideAccess=(bEnabled=false, bIsDefaultPlaylist=false, bDisplayAsLimitedTime=False, DisplayPriority=8)))` |


---
## [/Script/Account.OnlineAccountCommon]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bEnableWaitingRoom | |
| Boolean | bRequireLightswitchAtStartup | |


---
## [/Script/FortniteGame.FortGlobals]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bAthenaLeaderboardFrontEndEnabled | |
| Boolean | bAthenaStatsFrontendEnabled | |
| Boolean | bGlobalLeaderboardsFrontEndEnabled | |
| Boolean | bEnableFrontendCrafting | |
| Boolean | bEnableFrontendStorage | |
| Boolean | bUploadAthenaStats | |
| Integer | TimeBetweenLeaderboardRequestsMinutes | |


---
## [/Script/FortniteGame.FortMatchmakingV2]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bCustomKeyEnabled | |
| Array | AltDomainRecords | Model: `(OriginalDomain="intial.matchmaking.domain", AltDomain="alternate.matchmaking.domain")`|
---
## [AssetHotfix]
| Type | Key | Note |
| -------- | -------- | -------- |
| Array | CurveTable | A Curve Table is a curve where you can evaluate a value by its key here's an example `+CurveTable=Path;RowUpdate;ROW_NAME;CURVE_NUMBER (example 0, 1, 21);VALUE`|
| Array | DataTable | A Datatable is a similar concept as the CurveTable exept the value is static `+DataTable=Path;RowUpdate;ITEM_NAME;ROW_NAME;VALUE`|
