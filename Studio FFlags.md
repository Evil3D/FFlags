#  Below is a list of all FFlags i've found for Roblox Studio.

```toml
[studio.fflags]
# Enables forked chat analytics
EnableForkedChatAnalytics = true

# Fetch block list from the server
FetchBlockListFromServer = true

# In-experience user profile settings
InExperienceUserProfileSettingsEnabled = true

# Move UGC validation function feature
MoveUGCValidationFunctionFeature = true

# Wave emote on avatar context menu with expanded chat
WaveEmoteOnAvatarContextMenuWithExpChat = true

# Whisper emote on avatar context menu with expanded chat
WhisperEmoteOnAvatarContextMenuWithExpChat = true

# Comma-separated list of user IDs for in-experience name settings
RccInExperienceNameSettingsEnabledAllowList = "3119089537"

# Enables contact list in client
ContactListClientEnabled = true

# Enables contact list feature 2
ContactListEnabled2 = true

# Enables in-game menu duration logger
EnableInGameMenuDurationLogger = true

# Enables in-game IXP features
EnableIXPInGame = true

# Enables voice default server script
EnableVoiceDefaultServerScript = true

# Enables player view remote
PlayerViewRemoteEnabled = true

# Enables player view validate requestee version 2
PlayerViewValidateRequesteeEnabled2 = true

# Refactor for IXP service wrapper wait
IXPServiceWrapperWaitRefactor = true

# Verified badge clientsided
FStringWhitelistVerifiedUserId = "3119089537"
FFlagOverridePlayerVerifiedBadge = true

# Debugging tools (safe for anti-crash/logging)
FFlagDebugHumanoidRendering = false
FFlagDebugDisplayFPS = true
FFlagDebugTextBoxServiceShowOverlay = false
DFIntTextBoxServiceHistorySize = 1
FStringDebugLuaLogLevel = "" # "debug"
FStringDebugLuaLogPattern = "" # "ExpChat/mountClientApp"
DFFlagDebugAudioLogging = false
DFFlagDebugAudioLogging2 = false
DFFlagDebugPrintDataPingBreakDown = false
FFlagTrackerLodControllerDebugUI = false

# Anti-crash / stability tweaks
DFIntMaxActiveAnimationTracks = 60          # limits animations to prevent performance spikes
DFIntConnectionMTUSize = 900                # networking tweaks for stability
FIntRakNetResendBufferArrayLength = 128
FFlagOptimizeNetwork = true
FFlagOptimizeNetworkRouting = true
FFlagOptimizeNetworkTransport = true
FFlagOptimizeServerTickRate = true
DFIntServerPhysicsUpdateRate = 60
DFIntServerTickRate = 60
DFIntRakNetResendRttMultiple = 1
DFIntRaknetBandwidthPingSendEveryXSeconds = 1
DFIntOptimizePingThreshold = 50
DFIntPlayerNetworkUpdateQueueSize = 20
DFIntPlayerNetworkUpdateRate = 60
DFIntNetworkPrediction = 120
DFIntNetworkLatencyTolerance = 1
DFIntMinimalNetworkPrediction = 0.1

# Graphics / performance flags
# Commented out: disabling these can break graphics or visual quality
#DFIntCSGLevelOfDetailSwitchingDistance = 0
#DFIntCSGLevelOfDetailSwitchingDistanceL12 = 0
#DFIntCSGLevelOfDetailSwitchingDistanceL23 = 0
#DFIntCSGLevelOfDetailSwitchingDistanceL34 = 0
#DFIntTextureQualityOverride = 1
#FFlagDisablePostFx = true
#FIntDebugTextureManagerSkipMips = -1
#DFIntTextureCompositorActiveJobs = 0
#DFIntDebugFRMQualityLevelOverride = 1
#DFFlagDebugPauseVoxelizer = true
#DFFlagDebugRenderForceTechnologyVoxel = true
#FFlagGlobalWindRendering = false
#FIntRenderShadowIntensity = 0
#FIntRenderShadowmapBias = 1
#FIntDebugForceMSAASamples = -1
#FIntFRMMinGrassDistance = 0

# -------------------------
# UGC validation flags
# -------------------------

# Head, torso, limbs animation movement validation
# WARNING: enabling some of these may trigger crashes if assets are bad
#UGCValidateMaxAnimationMovementHead = ""
#UGCValidateMaxAnimationMovementUpperTorso = ""
#UGCValidateMaxAnimationMovementLeftUpperLeg = ""
#UGCValidateMaxAnimationMovementLeftLowerLeg = ""
#UGCValidateMaxAnimationMovementLeftHand = ""
#UGCValidateMaxAnimationMovementRightUpperArm = ""
#UGCValidateMaxAnimationMovementRightLowerArm = ""
#UGCValidateMaxAnimationMovementRightHand = ""
#UGCValidateMaxAnimationMovementLeftUpperArm = ""
#UGCValidateMaxAnimationMovementLeftLowerArm = ""
#UGCValidateMaxAnimationMovementLeftFoot = ""
#UGCValidateMaxAnimationMovementRightUpperLeg = ""
#UGCValidateMaxAnimationMovementRightLowerLeg = ""
#UGCValidateMaxAnimationMovementRightFoot = ""

# Asset type restrictions
#UGCLCAllowedAssetTypeIds = ""

# Emotes & animation checks
#UGCValidateEmoteAnimation = false
#UGCValidateDynamicHeadMoodRCC = false
#UGCValidateDynamicHeadMoodClient = false
#UGCValidateDynamicHeadMoodClientVpfSnapshot = false

# Bounds, BBox & mesh validation
#UGCValidateMaxAnimationFPS = 70
#UGCValidateMaxTotalInstances = 600
#UGCValidateMeshDivision = 9
#UGCValidateMeshDivisionFull = 159
#UGCValidateMeshDivisionMedium = 9
#UGCValidateMeshDivisionNarrow = 45
#UGCValidateAllowFlexibleTriangleLimit = false
#UGCValidateTriangleLimitTolerance = 10
#UGCValidatePartMass = false
#UGCValidateIndividualPartBBoxes2 = false
#UGCValidateCalculateScaleToValidateBounds = false
#UGCValidateMinBoundsVisibility2 = false
#UGCValidateNoScriptsInCurveAnim = false
#UGCValidateNoExtraInstsInCurveAnim = false
#UGCValidateRestrictAnimationMovement = false
#UGCValidateRestrictAnimationMovementPerPart = false
#UGCValidateRestrictAttachmentPositions = false
#UGCValidateUseMeshSizeProperty = false
#UGCValidateMeshVertColors = false
#UGCValidateAccurateCurveFrames = false
#UGCValidateBBoxOrderingsInLegs = false
#UGCValidateBBoxOrderingsInTorso = false
#UGCValidateBBoxOrderingsInArms = false
#UGCValidatePartSizeWithinRenderSizeLimits = false
#UGCValidateCageMeshDistanceThreshold = 60
#UGCValidateMaxTotalSurfaceArea = 70
#UGCValidateMaxCoplanarIntersectionsPercentage = 15
#UGCValidateNoTagsInCurveAnimations = false
#UGCValidateFixTransparencyReporting2 = false
#UGCValidateBindOffset = false
#UGCValidatePreciseAttachmentErrorMessage = false
#UGCValidateWrapLayersEnabled = false
#UGCValidateUseDataCache = false
#UGCValidateFixDeprecatedTransparency = false
#UGCValidateThumbnailConfiguration = false
#UGCValidateAnimationRequiredFieldsFix = false
#UGCValidateEmoteAnimationExtendedTests = false

# Name, visibility & other validation
#UGCValidationHeadThreshold = 30
#UGCValidationLeftArmThresholdBack = 33
#UGCValidationLeftArmThresholdFront = 35
#UGCValidationLeftArmThresholdSide = 50
#UGCValidationLeftLegThresholdBack = 50
#UGCValidationLeftLegThresholdFront = 50
#UGCValidationLeftLegThresholdSide = 46
#UGCValidationTorsoThresholdFront = 50
#UGCValidationTorsoThresholdSide = 46
#UGCValidationTorsoThresholdBack = 48
#UGCValidationTorsoThresholdTopBottom = 10
#UGCValidationLegThresholdTop = 10
#UGCValidationMaxAnimationBounds = "25"
#UGCValidationMaxAnimationDeltas = "1.5"
#UGCValidationMaxAnimationLength = "10"
#UGCValidationMaxCageDistance = "0.3"
#UGCValidationVisibilityDistributionAspect = "2.0"
#UGCValidationVisibilityDistributionWeight = 50
#UGCValidationVisibilityDistributionSliceMax = 50
#UGCValidationAcceptableBodyFacsExpansion = 150
#UGCValidationRefactorMeshScale = false
#UGCValidationFixConstantsTypoLeg = false
#LCCageQualityDocumentationLink = ""

# -------------------------
# Core / Voice / UX flags
# -------------------------

# Voice & microphone features
# Enable default voice chat behavior
EnableVoiceDefaultChannel = false
EnableVoiceMuteAnalytics = false
EnableVoicePromptReasonText = false
VoiceUserAgencyEnableIXP = false
VoiceJoinM3ToastDurationSeconds = 5
VoiceToxicityToastDurationSeconds = 5
VoiceChatTooltipDelay = 5
VoiceChatUILogging = false
VoiceExposureIXPLayerName = "Voice.Exposure"
VoiceUserAgency3 = false
VoiceUserAgencyIXPLayerName = ""
VoiceARRemoveOffsiteLinksForVoice = false
VoiceARUnblockingUnmutingEnabled = false
EnableSeamlessVoiceUX2 = false
EnableSeamlessVoiceConnectDisconnectButton2 = false

# Chat & experience UI
#UXForCameraPerformanceIXPEnabled = false
#UXForCameraPerformanceIXPLayerName = ""
EnableClientToastNotificationsRedirectExperiment = false
ClientToastNotificationsRedirect4 = false
ClientToastNotificationsRedirectLayerName = "Notification.Toast"
ClientToastNotificationsRedirectLayerValue = "NotificationRedirect"
EnableConnectDisconnectAnalytics = false
EnableConnectDisconnectButtonAnalytics = false
EnableNewInviteSendEndpoint = false
EnableNewInviteSendEndpointIXP = false
EnableExperienceMenuSessionTracking = false
EnableInExpVoiceUpsell8 = false
EnableInExpVoiceConsentAnalytics = false

# In-game UI fixes & camera
EnableAlwaysAvailableCamera = false
VRBottomBarPositionOffsetVerticalNumber = -170
VRBottomBarPositionOffsetDepthNumber = -20
VRBottomBarDebugPositionConfig = false
VRBottomBarHighlightedLeaveGameIconV2 = false
EnableAvatarChatToggleUIUpgradeForLegacyChatService = true
DoNotPromptCameraPermissionsOnMount = false
UseCameraDevicesListener = false
EnableAnalyticsForCameraDevicePermissions = false
VRScaleGuiDistance = 100

# Abuse / Reporting Flags

TranslatorUseInAbuseMethods = true
AbuseReportMenuOpenCloseSignal = true
AbuseReportShouldUseCanDisplayPeoplesUsernamesAppPolicy = true
AbuseReportTabRenderPerformanceFixEnabled = true
LuaAppAbuseReportAnalyticsHasLaunchData = false
ReportAbuseMenuEntrypointAnalytics = false
EnableNewVoiceReportFlows = false
EnableOptionalScreenshotButton2 = false
EnableReportAbuseMenuLayerOnV3 = false
ReportAbuseMenuLayerOnV3Layer = "Social.VoiceAbuseReport.ReportAbuseMenu.V1"
RAMaxAnnotationCount = 25
RAScreenshotOncePerMenuOpenEnabled = true
ReportAnythingDebugCanvas = true
ReportAnythingScreenshot = true
ReportAnythingLocalizationEnabled = true
ReportAnythingMultistepScreenshot = false
ReportAbuseMenuAutosizeYEnabled = true
ShrinkReportMenuForVisibility = false

# In-Game Menu / UX Flags

GetHumanoidDescriptionUpdates = true
HideShortcutsOnReportDropdown = false
ModalSelectorCloseButton = true
UnibarMenuOpenHamburger = false
RespawnChromeShortcutTelemetry = false
MusicTooltipLocalStorageKey_v2 = "HasSeenMusicTooltipFTUX_Dec11_2024"
LeaveChromeShortcutTelemetry = false
ConnectTooltipLocalStorageKey = "HasSeenRobloxConnectUnibarIconFTUX"
ShouldShowMusicFtuxTooltip3 = false
IntegrationsChromeShortcutTelemetry = false
MusicFtuxShowDelayMs = 3000
LeaveActionChromeShortcutTelemetry = false
HideShortcutsWhileIemDropdownActive = false
ShouldShowSimpleMusicFtuxTooltip2 = false
TweakedMicPinning2 = false
ChromeTrackWindowPosition = false
ChromeTrackWindowStatus = false
MusicTooltipLocalStorageKey = "HasSeenMusicTooltipFTUX_v2"
MusicFtuxDismissDelayMs = 5000
ShouldShowMusicFtuxTooltipXTimes3 = false
ChromeSelfViewIgnoreCoreGui = false
AppChatInExpConnectIconEnableSquadIndicator2 = false
UnibarMenuOpenSubmenu = false
UnpinUnavailable = false
RespawnActionChromeShortcutTelemetry = false
EnableUnibarTooltipQueue = false
RobloxConnectFtuxDismissDelayMs = 5000
AppChatDisableInExpU13 = false
RobloxConnectFtuxShowDelayMs = 3000
EnableNewBlockingModal_v2 = true
EnableToastForBlockingModal = true
NavigateToBlockingModal_1 = false
EnableNewBlockingModalDevApiPrompt = false
DebugEnableVRFTUXExperienceInStudio = false
EnableVRFTUXExperienceV2 = false
CleanUpFullscreenTitleBarPromiseOnUnmount = false
FixFullscreenTitleBarPromiseCancel = false
SideNavControllerBar = false
FixExitDialogBlockVRView = false
FullscreenTitleBarTriggerDelayMillis = 500
FixSafetyBubbleWidth = false
LuaMenuPerfImprovements = false
FullscreenTitleBarInjectGameServices = true
AlwaysShowDisplayNameInExpMenu = false
TruncateDeviceSelection = false
EnableFavoriteButtonForUgc = true

# Collectibles / UGC Flags

IBEnableLimitedBundle = true
IBGateUGC4ACollectibleAssetsBundles1 = true
DisplayCollectiblesIcon = true
AXEnableSaleLocationTypeParsing = true
IBEnableCollectiblesSystemSupport = true
ParseItemRestrictionsFromCatalog = false

# NextUp / Exit Modal UX

AddNextUpContainer3 = true
EnableNextUpImageLatencyTelemetry = false
InGameExitModalFixModalPadding = true
EnableInGameExitModalNextUpUiRequestCache = false

# Player List / IGM Fixes

PlayerListFixMobileScrolling = false
PlayerListClosedNoRender = false
FixDropDownVisibility = false
PlayerListReduceRerenders = false
PlayerListClosedNoRenderWithTenFoot = false
LeaderstatsWithASideOfClient = false
SelfieViewEnabled = true
SelfieViewFixMigration = true
IGMv1ARFlowExpandedAnalyticsEnabled = false
DefaultFriendingLabelTextNonEmpty = false
EnableExplicitSettingsChangeAnalytics = false
RefactorMenuConfirmationButtons3 = true
InExperienceMenuReorderFirstVariant2 = false
SettingsPageScaleTextSize = false
RelocateMobileMenuButtonsVariant = 0
FixIGMBottomBarVisibility = false
IGMv1ARFlowCSWaitFrames = 10
RemovePermissionsButtons = false
GameSettingsUsePreferredInputMovement = true
FixCyclicFullscreenIndexEvent = false
SingleUserInvitePageKeybind = false
DisableMuteAllCheckForIsMuted = false
InExperienceMenuIXPVar = "inExpSettingMenuVariantV1"
SettingsHubButtonCanBeDisabled = false
EnableLeaveGameUpsellEntrypoint = true
FixPermissionsButtonsEvents = true
UseFriendsPropsInMuteToggles2 = false
FixIGMTabTransitions = false
RelocateMobileMenuButtons2 = true
ShareGameSearchBoxFocusAnalytics = false
DestroyPlayerCardOnLeave = false
OverrideInExperienceMenuReorderFirstVariant2 = false
MenuButtonsThrottleHundredthsPercent = 0
RefactorPeoplePage4 = false
InExperienceMenuIXPLayer = "AppUserLayers.ExperienceMenuSettingsExposureLayer"
DebugRefactorInExpGameSettings = true
FilteredScrollingListAdditionalCustomizationsEnabled = true
GamepadMenuActionTelemetry = false
EnableTopBarAnalytics = false
EnableChromeBackwardsSignalAPI = false
LocalizeMenuNavigationToggleDialog = false
LoggingGamepadOpenExpControlsMenu = false
RemoveTopBarInputTypeRodux = false
AlwaysSelectButtonDismissesGamepadNavigationDialog = false
UnibarMenuIconLayoutFix = false
GamepadNavigationDialogABTestLayerName = "PlatformExcellence.QualityImprovement.Consoles"
GamepadNavigationDialogABTest2 = false
AlwaysShowGamepadNavigationDialog = false
GamepadNavigationDialogShowCount = 1
TopBarSignalizeHealthBar = false
EnableARFlowSession = false
OnlyEnableJoinVoiceInVoiceEnabledUniversesV2 = false

```
