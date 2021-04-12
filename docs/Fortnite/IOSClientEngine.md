## [Audio]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | UseAudioMixer | Default is set to false |
---

## [/Script/Engine.Engine]
| Type | Key | Note |
| - | - | - |
| Script | LocalPlayerClassName |/Script/FortniteGame.FortMobileLocalPlayer |

---
## [/Script/Engine.GarbageCollectionSettings]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | gc.MaxObjectsInGame | default is 786432.0 |
---
## [OnlineSubsystemIOS.Store]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean |bSupportsInAppPurchasing | default is true | Supports In app purchases for vbucks and such using the platforms Payment Method
| Boolean |bUseStoreV2 | default is true | Apple didn't really like this one, From what I remember this was Apple's plot against Apple with a simple hotfix they could enable support for their own Payment Wall.
---
## [SystemSettings]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | rhi.Metal.HeapBufferBytesToCompact |Default is 2097152 |
| Float | rhi.Metal.CommandBufferCommitThreshold | Default is 100|
---
## [InstallBundleManager]
| Type | Key | Note |
| - | - | - |
| | | |
|  | ModuleName | FortInstallBundleManager|
---
## [VoiceChatManager]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | NetworkTypePollingDelay | Default is 4|
| Boolean | bEnableBluetoothMicrophone ||
---
## [/Script/FortniteGame.FortHoagieVehicleConfigs]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bEnableCVarScaling ||

---
## [TextureStreaming]
| Type | Key | Note |
| - | - | - |
| Float| PoolSizeVRAMPercentage |Default is 0 |
---
## [LogFiles]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | MaxLogFilesOnDisk |Default is set to 10 Log files| Epic is aware that log files can take loads of storage if you surpass 10 it will start deleting the backups.
---
## [/Script/IOSRuntimeSettings.IOSRuntimeSettings]
| Type | Key | Note |
| - | - | - |
| | | |
| String | AdditionalPlistData |`"<key>NSCameraUsageDescription</key>\n<string>Nothing to see here.</string><key>NSMicrophoneUsageDescription</key>\n<string>Fortnite needs microphone access for voice chat.</string>\n<key>Fabric</key>\n<dict>\n<key>APIKey</key>\n<string>7a4cebd0324af21696e5e321802c5e26ba541cad</string>\n<key>Kits</key>\n<array>\n<dict>\n<key>KitInfo</key>\n<dict/>\n<key>KitName</key>\n<string>Crashlytics</string>\n</dict>\n</array>\n</dict>\n"`| Prompts the user to give microphone privileges.
| |BundleIdentifier|Example Builds:`com.chairentertainment.Fortnite` `com.epic.fortnite-internal-prod`  `com.epic.fortnite-internal`  `com.epic.fortnite-development` `com.chairentertainment.fortnitetest`|
| |BundleDisplayName|Fortnite|
| Boolean | bDevForArm64 ||
| Boolean | bDevForArmV7 ||
| Boolean | bShipForArmV7 ||
| Boolean | bDisableForceInline ||
| Boolean | bGeneratedSYMFile ||
| Boolean | bGeneratedSYMBundle ||
| Boolean | bGenerateXCArchive ||
| Boolean | bEnableFacebookSupport | Allows the user to Login with Facebook in kairos iirc|
| Boolean | bEnableAutomaticLogging ||
| Boolean | bEnableAdvertisingId ||
| Float | FacebookAppID |`1132078350149238`|
| Boolean | bEnableGoogleSupport ||
| String | GoogleReversedClientId |`"com.googleusercontent.apps.81931294547-rafm4jbl1skg8pfsms0gmb504o48g5ug"`|
| Float | IdleTimerEnablePeriod |Default is set to `1.0`|
| Boolean | bShipForBitcode ||
| Boolean | bEnableRemoteNotificationsSupport ||
| Boolean | bEnableBackgroundFetch ||
---
## [OnlineSubsystem]
| Type | Key | Note |
| - | - | - |
| | | |
| | DefaultPlatformService |`example "MCP" ` |
---
## [OnlineSubsystemMcp EMBEDDED]
| Type | Key | Note |
| - | - | - |
| | | |
|Boolean | bEnabled ||
---
## [/Script/Engine.StreamingSettings]
| Type | Key | Note |
| - | - | - |
| | | |
|Boolean | s.AsyncLoadingThreadEnabled ||

---
## [Analytics]
| Type | Key | Note |
| - | - | - |
| |AppsFlyerModuleName | |
|Boolean | s.AsyncLoadingThreadEnabled |On IOS it's set to `IOSAppsFlyer`|
---
## [PatchCheck]
| Type | Key | Note |
| - | - | - |
| |AppsFlyerModuleName | |
|Boolean | bCheckPlatformOSSForUpdate ||

---
