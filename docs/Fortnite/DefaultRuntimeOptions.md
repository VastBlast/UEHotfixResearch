## [/Script/FortniteGame.FortRuntimeOptions]

| Type | Key | Note |
| -------- | -------- | -------- |
| Boolean | bAllowAllReplays | Allows client to play old replays |
| Boolean | bGetLiveSessionsFromLeaderboards | Get Live Sessions, where you can watch matches live i presume, I believe this was used so you can watch the world cup live.|
| Boolean | bEnableBattlePassWatchVideoActionOnCell | |
| Boolean | bEnableBadMatchPopup | Enables Bad Match as in like a ban message or if the client failed to register with the server because anti cheat disabled that would be considered a "bad match" this is default to false.|
| Boolean | bEnableInGameMatchmaking | Allows client to matchmake |
| Boolean | bShowMOTDNews | Shows in-game news |
| Boolean | bForceBRMode | |
| Boolean | bSkipSubgameSelect | Skips STW/BR/Creative game selection screen |
| Boolean | bMOTDSameNewsForCreative | |
| Boolean | bAllowInGameStore | |
| Boolean | bShowStoreBanner | |
| Boolean | bEnableBattlePassGiftingButton | |
| Boolean | bForceEverybodyToGoNightNight | Disables the game and shows a special screen (at end of chapter 2 season 8: countdown for season 9) |
| Boolean | bEnableExtendedUserSearchUI | |
| Boolean | bAllowReportingFeaturedIslands | |
| Boolean | bShowBPPreviewVideo | |
| String | CheckStatusURL | e.g.: `https://status.epicgames.com` |
| Float | BadMatchIncidentThreshold | Default value is 20|
| Float | BadConnectionUpdateTime |Default value is 5|
| Float | BadMatchPopupRecallInterval |Default value is 10|
| Boolean | bEnableSavedLoadouts | |
| Boolean | bEnableClientSettingsSaveToCloud | |
| Integer | PreloadRevision | |
| | PlaylistCuratedHub | e.g.: `PlaylistCuratedHub=(("Playlist_PlaygroundV2", "8042-9140-1956"),("Playlist_Creative_PlayOnly", "8042-9140-1956"))` |
| Enum Array | ItemShopDefaultLandingPriority | The item shop section to open to when selecting the Item Shop navigation tab. Enum example: `EFortItemShopSection::ShopSection` |
| Array | ExperimentalCohortPercent | Includes a percent value for how many users will get the experiment applied, and an int for the actual experiment. Model: `(CohortPercent=100,ExperimentNum=30)` |
| Array | CreativeBetaPermissions | Whitelists creative islands for certain Perms `(PrimaryAssetId="CreativePlot:AssetID",PermissionTagContainer=("CreatorHub","EarlyAccess","Developer"))` |
| Array | DisabledFrontendNavigationTabs | Disables a tab using this model: `(TabName="...",TabState=EFortRuntimeOptionTabState::Hidden)` |
| Array | DisabledTabsForOutOfSeason | e.g.: `+DisabledTabsForOutOfSeason=(TabName="AthenaDirectAcquisition",TabState=Hidden)` |
| Array | PlaylistCuratedContent | e.g.: `PlaylistCuratedContent=(("Playlist_Showdown_BlueFlatline_1v1",(CuratedLinkCodes=("8015-0342-4964"))))` |
| Array | CuratedLinkCodes | e.g.: `5279-2660-3689?v=22` |
| Array | AthenaStarterGameMode | e.g.: `+AthenaStarterGameMode="Playlist_DefaultSolo"` |
| Array | FrontEndPlaylistData | e.g.: `+FrontEndPlaylistData=(PlaylistName=Playlist_Rebirth_Duos, PlaylistAccess=(bEnabled=false, CategoryIndex=1, DisplayPriority=8))` |

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
