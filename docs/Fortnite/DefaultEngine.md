## [ConsoleVariables]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | FortMatchmakingV2.EnableContentBeacon | |
| Boolean | FortMatchmakingV2.ContentBeaconFailureCancelsMatchmaking | |
| Boolean | Fort.ShutdownWhenContentBeaconFails | |
| Boolean | demo.WithTimeBurnIn | |
| Boolean | demo.EnableCheckpoints | |
| Float | demo.GotoTimeInSeconds | Skips to a certain time in seconds once a replay is loaded |
| Float | demo.TimeDilation | Sets universal default start time of replays to a certain time in seconds |

#### More "undocumented" ones [here](https://pastebin.com/8yMBGDJM).

---
## [SystemSettings]
| Type | Key | Note |
| - | - | - |
| Boolean | demo.WithLevelStreamingFixes | |
| Boolean | demo.WithDeltaCheckpoints | |
| Boolean | demo.ReplayStreamerAutoDemoUseDateTimePostfix | used for labeling replays |
| String | demo.ReplayStreamerAutoDemoPrefix | default: `UnsavedReplay-` |

---
## [Core.Log]

- **ELogVerbosity::Type**: Enum that defines the verbosity levels of the logging system.
        ```        
        NoLogging,
        Fatal,
        Error,
        Warning,
        Display,
        Log,
        Verbose,
        VeryVerbose,
        All              = VeryVerbose
        ```
- Take a look at Fortnite logs to understand more about the logging system.  

| Type | Key | Note |
| - | - | - |
| ELogVerbosity::Type | LogHttp | e.g: `error` |
| ELogVerbosity::Type | LogXmpp | |
| ELogVerbosity::Type | LogBeacon | |
| ELogVerbosity::Type | LogQos | |
| ELogVerbosity::Type | LogOnline | |
| ELogVerbosity::Type | LogOnlineCloud | |
| ELogVerbosity::Type | LogOnlineGame | |
| ELogVerbosity::Type | LogSourceControl | |
| ELogVerbosity::Type | LogUAC | |
| ELogVerbosity::Type | LogBattlEye | |
| ELogVerbosity::Type | LogEasyAntiCheatServer | |
| ELogVerbosity::Type | LogEasyAntiCheatClient | |
| ELogVerbosity::Type | LogFortAnalytics | |
| ELogVerbosity::Type | LogEpicCMS | |
| ELogVerbosity::Type | LogNetPlayerMovement | |
| ELogVerbosity::Type | LogDerivedDataCache | |
| ELogVerbosity::Type | LogOnlineDataAssetDirectory | |
| ELogVerbosity::Type | LogContentBeacon | |
| ELogVerbosity::Type | LogBPSInstallerConfig | |




---
## [/Script/Engine.UserInterfaceSettings]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | ApplicationScale | Scales client ui |


---
## [LwsWebSocket]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bDisableCertValidation | |


---
## [XMPP]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bEnableWebsockets | |

---
## [PatchCheck]
| Type | Key | Note |
| - | - | - |
| | | |
| String | ModuleName | e.g: `FortnitePatchCheck`|
| Boolean | bCheckPlatformOSSForUpdate | |
| Boolean | bCheckOSSForUpdate | |

---
## [/Script/Qos.QosRegionManager]
| Type | Key | Note |
| - | - | - |
| | | |
| Array | RegionDefinitions | e.g: `+RegionDefinitions=(DisplayName=NSLOCTEXT("MMRegion", "EU", "EU"), RegionId="EU", bEnabled=true, bVisible=true, bAutoAssignable=true)`|


---
## [OnlineSubsystemMcp.Xmpp]
- Prod: **[OnlineSubsystemMcp.Xmpp Prod]**

| Type | Key | Note |
| - | - | - |
| | | |
| String | ServerAddr | e.g: `wss://example.com/xmpp` |
| String | ServerPort |  |
| Boolean | bUseSSL | |

---
## [OnlineSubsystemMcp.OnlinePartySystemMcpV2]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | CreatePartyWaitForXmppConnectionTimeoutSeconds | |
| Float | JoinPartyWaitForXmppConnectionTimeoutSeconds |  |
| Boolean | bRequiresMatchingBuildId | Bypass joining older client party if set to false |


---
## [OnlineSubsystemMcp.{service} {env}]
- BaseService: **[OnlineSubsystemMcp.BaseServiceMcp]**

| Type | Key | Note |
| - | - | - |
| | | |
| String | Domain | eg: `sub.example.com`, `example.com:8080` |
| Array | AltDomains | |
| String | Protocol | eg: `http`, `https` |
| String | AccountCreationUrl | `/tos?client_id=clientid&response_type=code&embedded=true`|
| String | LoginPortalUrl | `/login/logintype?client_id=clientid&response_type=code` |
| Float | HttpRetryLimit | |
| Boolean | bEnabled | |
| Boolean | bUpdatesConnectionStatus | True = any failed HTTP request will cause an immediate logout |
