# RIP [Pekora](https://pekora.zip) These FFlags most likely will/should work on normal roblox, and or on other revivals such as [ECS:R](https://ecsr.io/auth/home)
### Use [PekoStrap](https://github.com/WindowsMI/pekoStrap) to be able to apply these FFlags to your client.
### This is a repo with *most* pekora FFlags Found in different versions. Bonus at the bottom.
### ALSO there are files aswell, they're labeled as such: FFlags_<first 5 characters of the version>_<version, so like 2020L> Here's a bonus: [Studio FFlags](Studio%20FFlags.md)
### Here's another bonus: [Other Pekora Stuff](Other.md) Bro... so uh i got a list of a little over 4 THOUSAND Flags.. yea.. [insane right](InsanityFlags.md)
### Turns out im kinda stupid.. so every fflag needs FFlag infront of it to actually register. also DFFlag(s) mean 'Developer FastFlag'

## version-7e043f9d229d4b9a/2020L (first since this is the only ver which actually works for me) (Question: what's the L for? Answer: Large)
```json
{
  "FFlagAppBridgeStartupController": "False",
  "FFlagLuaUIBloxModalWindowAnchorPoint": "false",
  "FFlagLuaAppUseUIBloxToasts2": "false",
  "FFlagLuaPremiumCatalogTileFix": "false",
  "FIntPercentReportingNetworkProfileAfterStartup": "0",
  "FIntLuaAppNonFinalThumbnailMaxRetries": "0",
  "FIntLuaAppThumbnailsApiRetryTimeMultiplier": "0",
  "FIntEnableFriendFooterOnHomePageV369": "0",
  "FFlagLuaAppConvertUniverseIdToStringV364": "False",
  "FFlagLuaAppFixLightTheme": "false",
  "FIntAvatarEditorNewCatalogButton2": "0",
  "FFlagUseDateTimeType3": "False",
  "FFlagLuaFixEconomyCreatorStatsUrl": "false",
  "FFlagChinaLicensingApp": "False",
  "FIntLuaChatUseNewFriendsEndpointsV2": "0",
  "FFlagRestrictSales2": "False",
  "FFlagOrder66": "False",
  "FFlagUpsellDirectToPackage": "false",
  "FFlagAdultConfirmationEnabledNew": "false",
  "FFlagPromptRobloxPurchaseEnabled": "False",
  "FFlagIGPPPremiumPriceV2": "false",
  "FFlagAdultConfirmationEnabledV4": "false",
  "FFlagHideThirdPartyPurchaseFailure": "false",
  "FFlagLuaPremiumCatalogIGPP": "false",
  "FFlagLuaUseThirdPartyPermissions": "false",
  "FFlagDeveloperSubscriptionsEnabled": "False",
  "FFlagDisableRobuxUpsell": "false",
  "FFlagProductPercentLocFix": "false",
  "FFlagUseCursorOverrideManager": "False",
  "FFlagUGCValidateMeshBounds": "false",
  "FFlagUGCValidateHandleSize": "false",
  "FFlagUGCExtraBannedNames": "false"
}
```
## version-7e043f9d229d4b9a/2021M (I'm guessing the M stands for Mini)
```json
{
  "FFlagUIBloxAllowSystemBarToAcceptString": "false",
  "FFlagUIBloxTooltipWidthUsesHeaderToo": "false",
  "FFlagGamepadAnimatedCursor": "false",
  "FFlagUIBloxEnableAlertCustomTitleFooterConfig": "false",
  "FFlagAppBridgeStartupController": "False",
  "FFlagLuaBacktraceReportFromDetails": "false",
  "FFlagLuaAppUseNewUIBloxRoundedCorners": "false",
  "FFlagUIBloxHideHorizontalCarouselScrollButtonFix": "false",
  "FFlagUIBloxUseHeaderBarV2_1": "false",
  "FFlagUIBloxSlidersFilterOldTouchInputs": "false",
  "FFlagUIBloxEmptyStateControllerSupport": "false",
  "FFlagUIBloxUseTileThumbnailV2_0": "false",
  "FFlagUseUpdatedUIBloxCheckbox": "false",
  "FIntPercentReportingNetworkProfileAfterStartup": "0",
  "FFlagAddDisplayNameToUserModel": "false",
  "FIntLuaAppNonFinalThumbnailMaxRetries": "0",
  "FIntLuaAppThumbnailsApiRetryTimeMultiplier": "0",
  "FIntEnableFriendFooterOnHomePageV369": "0",
  "FFlagLuaAppConvertUniverseIdToStringV364": "False",
  "FFlagLuaAppNewDividerColor": "false",
  "FIntAvatarEditorNewCatalogButton2": "0",
  "FFlagUseDateTimeType3": "False",
  "FFlagLuaFixEconomyCreatorStatsUrl": "false",
  "FIntLuaChatUseNewFriendsEndpointsV2": "0",
  "FFlagLuaAppAddPresenceCounts": "false",
  "FFlagLuaAppUseRoduxV3": "false",
  "FFlagPolicyProviderFromMemStorageServiceFix": "false",
  "FFlagFixAppPolicyDefaultUserId": "false",
  "FFlagUseCursorOverrideManager3": "false",
  "FFlagLuaEnableScreenTime": "false",
  "FFlagLuaEnableScreenTimeSignalR": "false",
  "FFlagUGCValidateMeshBounds": "false",
  "FFlagUGCValidateHandleSize": "false",
  "FFlagUGCExtraBannedNames": "false",
  "FFlagUGCValidateContentIdStrict": "false",
  "FFlagUGCValidateAttributes": "false"
}
```

### FYI i didnt find any flags for 2018L or 2017L so.. maybe you can reuse some from the newer vers? but not recommended ofc.

### at ze bottom here i'll put random flags i find (this will include flags i *most* likely haven't listed anywhere else), this is in TOML format cause it doesn't become mad when i add comments. The values of the FFlags will be what i think is best.
```toml
[Studio FFlags]
# below fflags were found in pekora studio 2021 unless specified otherwise
# Prevents conflicts when multiple CoreScript subsystems are trying to override the mouse cursor at the same time.
FFlagUseCursorOverrideManager3 = true

# the next most scripts are in corescripts and core stuff, so should work on the client.
# so this is chinese console??? or idek but it says that if you're in china it's disabled so idk
FFlagDeveloperConsoleEnabledForLuobu = true

# OOO ADMIN STUFFS
FFlagDebugFreeCameraForAdmins = true

# Leaderstat server child-order tracker
FFlagAnOrderOfLeaderstats = false

# Loading screen stuffs idk
FFlagLoadTheLoadingScreenEvenFaster = true
FFlagLoadingScreenDontBlockOnPolicyService = false
FFlagBackButtonWhileLoadingGoesBackToApp = true
FFlagLoadingScreenShowBlankUntilPolicyServiceReturns = false

# idek
FFlagDebugEnableErrorStringTesting = false
FFlagShouldMuteUnlocalizedError = true

# by default set to 2 hours, disables reconnecting after the failure of first try
FFlagDisableReconnectAfterPotentialTimeout = true
FIntPotentialClientTimeoutSeconds = 7200
FFlagReconnectDisabled = false # when on, disables reconnecting on all errors
FStringReconnectDisabledReason = "We're sorry, Roblox is temporarily unavailable.  Please try again later." # or whatever u want to set it to

# Idk, for some/most the definition is the name/in the name
FFlagProximityPromptLocalization = true
FFlagProximityPromptNoButtonDrag = false
FFlagProximityPromptLiveChanges = true
FFlagProximityPromptMoreKeyCodes = true
FFlagProximityPromptMoreKeyCodes2 = true
FFlagProximityPromptsFadeIn = true
FFlagProximityPromptFixFade = true

# still dont know 😭
FFlagFixNotificationScriptError = true
FFlagLocalizeVideoRecordAndScreenshotText = false

# the name ig
FFlagGameplayPausePausesInteraction = false

# dialog fixes?
FFlagFixDialogScriptNilChecks = true
FFlagFixStuckDialogWhenUsingGamepad = true

#??? what's the diff between invites??
FFlagSafeGameInvite = true

# i have no idea
FFlagInspectMenuDeveloperMethodsPolicy = false

# ye bro wtf
FFlagEnableCoreScriptBacktraceReporting = true
# we will report the same message + stack combination 5 times per minute, and ignore subsequent occurrences
FFlagCoreScriptBacktraceRepeatedErrorRateLimiting = true
# yk what imma js stop saying "idk", if i dont know it wont have a comment
FFlagCoreScriptBacktraceReportUserAgent = false

FFlagCancelButtonTouchEventOnMouseDragOff = false
FFlagHandleChangeBoundActionNilValue = true

# Server core stuff (just 3)
FFlagRemoveInGameFollowingServer = false
# FFlagPackInGameJoinDataEnabledClient must be turned on first
FFlagPackInGameJoinDataEnabledServer = false
FFlagFallbackLeaderstatOrdering = false

FFlagPlayerListRoactInspector = true

# Changes your graphics slider to max out at 21 instead of 10
FFlagFixGraphicsQuality = true

# OO
FFlagNewEmotesInGame = true

FFlagBubbleChatUserSpecificSettings = false

FFlagShowInGameBlockingLuobu = false

FFlagEnableCaptureMode = true
FStringEnableCaptureModePlaceIds = "1234"


```

#### *Glitches*, NOT recommened to use, likely get you banned.
```json
{
  "DFIntNewRunningBaseGravityReductionFactorHundredth": 1500,
  "FFlagSimAdaptiveTimesteppingDefault2": true,
  "DFFlagSimHumanoidTimestepModelUpdate": true,
  "DFIntDebugSimPhysicsSteppingMethodOverride": 10000000,
  "DFFlagAssemblyExtentsExpansionStudHundredth": -50,
  "DFIntSimBroadPhasePairCountMax": 50,
  "FFlagDebugSimDefaultPrimalSolver": true,
  "DFIntDebugSimPrimalStiffness": 0,
  "DFIntMaxAltitudePDStickHipHeightPercent": -1000,
  "DFFlagDebugDisableTimeoutDisconnect": true,
  "FFlagTopBarUseNewBadge": true,
  "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
  "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```
