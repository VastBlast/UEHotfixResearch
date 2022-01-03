## [/Script/Account.OnlineAccountCommon]
| Type | Key | Note |
| -------- | -------- | -------- |
| String | EulaKey | As far as i know atm FortniteMobileIOS, is the only one ik, I'll add more later if i find more.


---
## [/Script/FortniteGame.FortOnlineAccount]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bShouldRequestGeneralChatRooms | |
| Boolean | bShouldJoinGlobalChat | |
| Boolean | bShouldJoinFounderChat | |


---
## [/Script/FortniteGame.FortGlobals]
| Type | Key | Note |
| -------- | -------- | -------- |
| Float | MinCullObjectSize | default is 64.0 |
| Float | MinCullDistance | default is 3000 |
| Float | MaxCullObjectSize | default is 1000 |
| Float | MaxCullDistance | default is 28500 |
| Boolean | bAccountLinkingEnabled | |
| Boolean | bTwitchEnabled | |
| Boolean | bTwitchHeartbeatEnabled | |
| Boolean | bTwitchAllowDisplayViewernames | |
| Boolean | bHasWorldMap | |
| Boolean | bAllowLogout | |
| Boolean | bAllowQuit | |
| Array | SubGameAccess |(SubGame=(Athena,Campain,Creative),AccessStatus=(OpenAccess, Disabled),MatchmakingStatus=(Enabled,Disabled) | For IOS only Athena is enabled
| Float | MemoryRequirementForMediaStreamingMB |default is 3500 |
| Float | MaxResolutionForMediaStreaming |It's set to 720p on ios, even if you upscale the res of the game |




---
## [/Script/FortniteGame.FortPlayerControllerAthena]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bSupportNextPieceAssist | |
| Float | PerPlatformEnemyRenderCustomDepthScalar | Default is 0|


---
## [/Script/FortniteGame.FortPlayerControllerAthena]
| Type | Key | Note |
| -------- | -------- | -------- |
| Script | DefaultWorldTimeOfDayManager | /Script/FortniteGame.FortTimeOfDayManager| Sets the TODM for mobile


---
## [AppStore]
| Type | Key | Note |
| -------- | -------- | -------- |
|  | AppStoreId | IOSAppStore| Makes the default store the App store

---
## [VoiceChatManager]
| Type | Key | Note |
| -------- | -------- | -------- |
| Float | NetworkTypePollingDelay | Default is 4|
| Boolean | bEnableBluetoothMicrophone ||


---

## [/Script/FortniteGame.FortHoagieVehicleConfigs]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bEnableCVarScaling ||

---
## [PartyHub]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean| bExampleForTesting | |
| Int32 | ExampleInt32ForTesting ||
| Double | ExampleDoubleForTesting ||
| String | ExampleStringForTesting ||
| String | electraPlayerContent ||
| Boolean | bIsChatEnabled ||
| Boolean | bIsTextChatEnabled ||
| Boolean | bUseExtendedSearch ||
| Boolean | bDisplayAutoLaunch ||
| Int32 | autoLaunchDelay ||
| Boolean | bDefaultValueAutoLaunch ||
| Boolean | bEnableDisambiguateLoading ||

---
## [Staging]
| Type | Key | Note |
| -------- | -------- | -------- |
| Array | RemapDirectories |(From="Engine/Plugins/Lumin", To="Engine/Plugins/MagicLeap")|


---
## [PersistentStatsTracker]
| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bEnablePersistentStatTracking ||
---
## [EpicPurchaseFlow]
| Type | Key | Note |
| -------- | -------- | -------- |
| String | UEPlatform |`example "IOS" ` |
---
