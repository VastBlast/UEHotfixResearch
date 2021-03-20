## [ConsoleVariables]
| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | FortMatchmakingV2.EnableContentBeacon | |
| Boolean | FortMatchmakingV2.ContentBeaconFailureCancelsMatchmaking | |
| Boolean | Fort.ShutdownWhenContentBeaconFails | |
| Boolean | demo.WithTimeBurnIn | |
| Boolean | demo.EnableCheckpoints | |
| Boolean | demo.GotoTimeInSeconds | Skips to a certain time in seconds once a replay is loaded |
| Float | demo.TimeDilation | Sets universal default start time of replays to a certain time in seconds |

---
## [SystemSettings]
| Type | Key | Note |
| - | - | - |
| Boolean | demo.WithLevelStreamingFixes | |
| Boolean | demo.WithDeltaCheckpoints | |
| Boolean | demo.ReplayStreamerAutoDemoUseDateTimePostfix | used for labeling replays |
| String | demo.ReplayStreamerAutoDemoPrefix | default: `UnsavedReplay-` |


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
## [OnlineSubsystemMcp.Xmpp] - [OnlineSubsystemMcp.Xmpp Prod]
| Type | Key | Note |
| - | - | - |
| | | |
| String | ServerAddr | eg: `wss://example.com/xmpp` |
| String | ServerPort |  |
| Boolean | bUseSSL | |

---
## [OnlineSubsystemMcp.OnlinePartySystemMcpV2]
| Type | Key | Note |
| - | - | - |
| | | |
| Float | CreatePartyWaitForXmppConnectionTimeoutSeconds | |
| Float | JoinPartyWaitForXmppConnectionTimeoutSeconds |  |


---
## [OnlineSubsystemMcp.{service} {env}]
| Type | Key | Note |
| - | - | - |
| | | |
| String | Domain | eg: `sub.example.com`, `example.com:8080` |
| Array | AltDomains | |
| String | Protocol | eg: `http`, `https` |
| Boolean | bEnabled | |
| Float | HttpRetryLimit | |