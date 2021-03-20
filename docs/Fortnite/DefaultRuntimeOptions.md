## [/Script/FortniteGame.FortRuntimeOptions]

| Type | Key | Note |
| - | - | - |
| | | |
| Boolean | bAllowAllReplays | Allows client to play old replays |
| Boolean | bEnableInGameMatchmaking | Allows client to matchmake |
| Boolean | bShowMOTDNews | Shows in-game news |
| Boolean | bForceBRMode | |
| Boolean | bSkipSubgameSelect | Skips STW/BR/Creative game selection screen |
| Boolean | bMOTDSameNewsForCreative | |
| Boolean | bAllowInGameStore | |
| Boolean | bShowStoreBanner | |
| Boolean | bEnableSavedLoadouts | |
| Boolean | bEnableClientSettingsSaveToCloud | |
| Integer | PreloadRevision | |
| Enum Array | ItemShopDefaultLandingPriority | The item shop section to open to when selecting the Item Shop navigation tab. Enum example: `EFortItemShopSection::ShopSection` |
| Array | ExperimentalCohortPercent | Includes a percent value for how many users will get the experiment applied, and an int for the actual experiment. Model: `(CohortPercent=100,ExperimentNum=30)` |
| Array | DisabledFrontendNavigationTabs | Disables a tab using this model: `(TabName="...",TabState=EFortRuntimeOptionTabState::Hidden)` |


### Fortnite Client Tabs 
- BattlePass
- AthenaStore
- AthenaDirectAcquisition
- AthenaProfile
- AthenaLeaderboards
- AthenaProfileStats
- AthenaChallenges
- AthenaCareer
- Showdown
- Store
- Vault
- SpecialEvent
- Cosmetics
- AthenaShowdown
- Inventory

### Fortnite Item Shop Landing Priority
- RMTItemOffer
- Featured
- Daily
- SpecialFeatured
- SpecialDaily
- Standalone
- CommunityChoice
- MegaBundle
- BattlePass
