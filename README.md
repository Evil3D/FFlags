# Use [PekoStrap](https://github.com/WindowsMI/pekoStrap) to be able to apply these FFlags to your client.
### This is a repo with *most* pekora FFlags Found in different versions. Bonus at the bottom.
### ALSO there are files aswell, they're labeled as such: FFlags_<first 5 characters of the version>_<version, so like 2020L> Here's a bonus: [Studio FFlags](Studio%20FFlags.md)
### Here's another bonus: [Other Pekora Stuff](Other.md)

## version-7e043f9d229d4b9a/2020L (first since this is the only ver which actually works for me) (Question: what's the L for? Answer: Large)
```json
{
  "AppBridgeStartupController": "False",
  "LuaUIBloxModalWindowAnchorPoint": "false",
  "LuaAppUseUIBloxToasts2": "false",
  "LuaPremiumCatalogTileFix": "false",
  "PercentReportingNetworkProfileAfterStartup": "0",
  "LuaAppNonFinalThumbnailMaxRetries": "0",
  "LuaAppThumbnailsApiRetryTimeMultiplier": "0",
  "EnableFriendFooterOnHomePageV369": "0",
  "LuaAppConvertUniverseIdToStringV364": "False",
  "LuaAppFixLightTheme": "false",
  "AvatarEditorNewCatalogButton2": "0",
  "UseDateTimeType3": "False",
  "LuaFixEconomyCreatorStatsUrl": "false",
  "ChinaLicensingApp": "False",
  "LuaChatUseNewFriendsEndpointsV2": "0",
  "RestrictSales2": "False",
  "Order66": "False", // internal??
  "UpsellDirectToPackage": "false",
  "AdultConfirmationEnabledNew": "false",
  "PromptRobloxPurchaseEnabled": "False",
  "IGPPPremiumPriceV2": "false",
  "AdultConfirmationEnabledV4": "false",
  "HideThirdPartyPurchaseFailure": "false",
  "LuaPremiumCatalogIGPP": "false",
  "LuaUseThirdPartyPermissions": "false",
  "DeveloperSubscriptionsEnabled": "False",
  "DisableRobuxUpsell": "false",
  "ProductPercentLocFix": "false",
  "UseCursorOverrideManager": "False",
  "UGCValidateMeshBounds": "false",
  "UGCValidateHandleSize": "false",
  "UGCExtraBannedNames": "false"
}
```
## version-7e043f9d229d4b9a/2021M (I'm guessing the M stands for Mini)
```json
{
  "UIBloxAllowSystemBarToAcceptString": "false",
  "UIBloxTooltipWidthUsesHeaderToo": "false",
  "GamepadAnimatedCursor": "false",
  "UIBloxEnableAlertCustomTitleFooterConfig": "false",
  "AppBridgeStartupController": "False",
  "LuaBacktraceReportFromDetails": "false",
  "LuaAppUseNewUIBloxRoundedCorners": "false",
  "UIBloxHideHorizontalCarouselScrollButtonFix": "false",
  "UIBloxUseHeaderBarV2_1": "false",
  "UIBloxSlidersFilterOldTouchInputs": "false",
  "UIBloxEmptyStateControllerSupport": "false",
  "UIBloxUseTileThumbnailV2_0": "false",
  "UseUpdatedUIBloxCheckbox": "false",
  "PercentReportingNetworkProfileAfterStartup": "0",
  "AddDisplayNameToUserModel": "false",
  "LuaAppNonFinalThumbnailMaxRetries": "0",
  "LuaAppThumbnailsApiRetryTimeMultiplier": "0",
  "EnableFriendFooterOnHomePageV369": "0",
  "LuaAppConvertUniverseIdToStringV364": "False",
  "LuaAppNewDividerColor": "false",
  "AvatarEditorNewCatalogButton2": "0",
  "UseDateTimeType3": "False",
  "LuaFixEconomyCreatorStatsUrl": "false",
  "LuaChatUseNewFriendsEndpointsV2": "0",
  "LuaAppAddPresenceCounts": "false",
  "LuaAppUseRoduxV3": "false",
  "PolicyProviderFromMemStorageServiceFix": "false",
  "FixAppPolicyDefaultUserId": "false",
  "UseCursorOverrideManager3": "false",
  "LuaEnableScreenTime": "false",
  "LuaEnableScreenTimeSignalR": "false",
  "UGCValidateMeshBounds": "false",
  "UGCValidateHandleSize": "false",
  "UGCExtraBannedNames": "false",
  "UGCValidateContentIdStrict": "false",
  "UGCValidateAttributes": "false"
}
```

### FYI i didnt find any flags for 2018L or 2017L so.. maybe you can reuse some from the newer vers? but not recommended ofc.

### at ze bottom here i'll put random flags i find (this will include flags i *most* likely haven't listed anywhere else), this is in TOML format cause it doesn't become mad when i add comments. The values of the FFlags will be what i think is best.
```toml
[Studio FFlags]
# below fflags were found in pekora studio 2021 unless specified otherwise
# Prevents conflicts when multiple CoreScript subsystems are trying to override the mouse cursor at the same time.
UseCursorOverrideManager3 = true

# the next most scripts are in corescripts and core stuff, so should work on the client.
# so this is chinese console??? or idek but it says that if you're in china it's disabled so idk
DeveloperConsoleEnabledForLuobu = true

# OOO ADMIN STUFFS
DebugFreeCameraForAdmins = true

# Leaderstat server child-order tracker
AnOrderOfLeaderstats = false

# Loading screen stuffs idk
LoadTheLoadingScreenEvenFaster = true
LoadingScreenDontBlockOnPolicyService = false
BackButtonWhileLoadingGoesBackToApp = true
LoadingScreenShowBlankUntilPolicyServiceReturns = false

# idek
DebugEnableErrorStringTesting = false
ShouldMuteUnlocalizedError = true

# by default set to 2 hours, disables reconnecting after the failure of first try
DisableReconnectAfterPotentialTimeout = true

# Idk, for some/most the definition is the name/in the name
ProximityPromptLocalization = true
ProximityPromptNoButtonDrag = false
ProximityPromptLiveChanges = true
ProximityPromptMoreKeyCodes = true
ProximityPromptMoreKeyCodes2 = true
ProximityPromptsFadeIn = true
ProximityPromptFixFade = true

# still dont know 😭
FixNotificationScriptError = true
LocalizeVideoRecordAndScreenshotText = false

# the name ig
GameplayPausePausesInteraction = false

# dialog fixes?
FixDialogScriptNilChecks = true
FixStuckDialogWhenUsingGamepad = true

#??? what's the diff between invites??
SafeGameInvite = true

# i have no idea
InspectMenuDeveloperMethodsPolicy = false

# ye bro wtf
EnableCoreScriptBacktraceReporting = true
# we will report the same message + stack combination 5 times per minute, and ignore subsequent occurrences
CoreScriptBacktraceRepeatedErrorRateLimiting = true
# yk what imma js stop saying "idk", if i dont know it wont have a comment
CoreScriptBacktraceReportUserAgent = false

CancelButtonTouchEventOnMouseDragOff = false
HandleChangeBoundActionNilValue = true

# Server core stuff (just 3)
RemoveInGameFollowingServer = false
# FFlagPackInGameJoinDataEnabledClient must be turned on first
PackInGameJoinDataEnabledServer = false
FallbackLeaderstatOrdering = false

PlayerListRoactInspector = true

FixGraphicsQuality = true

# OO
NewEmotesInGame = true

BubbleChatUserSpecificSettings = false

ShowInGameBlockingLuobu = false
```
