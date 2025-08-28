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

### at ze bottom here i'll put random flags i find (this will only include flags i haven't listed here or in the studio flags), this is in TOML format cause it doesn't become mad when i add comments. Also this will have comments.. i forgot what i wanted to say lmao
```toml
[Studio FFlags]
# Prevents conflicts when multiple CoreScript subsystems are trying to override the mouse cursor at the same time.
UseCursorOverrideManager3 = true

# so this is chinese console??? or idek but it says that if you're in china it's disabled so idk
DeveloperConsoleEnabledForLuobu = true

# OOO ADMIN STUFFS
DebugFreeCameraForAdmins = true
```
