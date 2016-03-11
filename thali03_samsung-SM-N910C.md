#### Test 62509094a319d1d_thali03_samsung-SM-N910C Logs


```
--------- beginning of main
D/ResourcesManager( 9547): creating new AssetManager and set to /system/app/SmartcardManager/SmartcardManager.apk
D/TimaKeyStoreProvider( 9562): TimaSignature is unavailable
D/ActivityThread( 9562): Added TimaKeyStore provider
--------- beginning of system
W/ResourcesManager( 9547): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/ActivityManager( 3524): Killing 8830:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
D/ResourcesManager( 9562): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
D/BadgeProvider( 9562): onCreate
D/BadgeProvider( 9562): DatabaseHelper
E/SmartCardContentProvider( 9547): onCreate
I/SmartCardBroadcastReceiver( 9547): SmartCardBroadcastReceiver - onReceive() 
I/SmartCardBroadcastReceiver( 9547): Broadcast received for locktype changed 
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PopupuiReceiver( 9035): onReceive() getAction : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2( 3524): uri = -1 selection = getSealedState
D/SecContentProvider2( 3524): mCursor = null
I/PopupuiReceiver_KNOX( 9035): getSealedState : true
D/SecContentProvider2( 3524): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2( 3524): mCursor = null
I/PopupuiReceiver_KNOX( 9035): getSealedHideNotificationMessages : 1
D/SecContentProvider2( 3524): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2( 3524): mCursor = null
I/PopupuiReceiver_KNOX( 9035): getCheckCoverPopupState : true
D/PopupuiReceiver( 9035): Action cable connected ! on - 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9582): MountEmulatedStorage()
E/Zygote  ( 9582): v2
I/libpersona( 9582): KNOX_SDCARD checking this for 10149
I/libpersona( 9582): KNOX_SDCARD not a persona
I/SELinux ( 9582): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.samsung.android.app.powersharing for broadcast com.samsung.android.app.powersharing/.service.BatteryReceiver: pid=9582 uid=10149 gids={50149, 9997} abi=armeabi-v7a
I/SELinux ( 9582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Killing 8883:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
E/SELinux ( 9582): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification( 9518): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 3982): query,matched:26, calling pid = 9518
D/TP/SmsProvider( 3982): match 26:Elapsed time : 1.176 ms
D/TP/MmsSmsProvider( 3982): query,matched:6, calling pid = 9518
D/TP/MmsSmsProvider( 3982): match 6:Elapsed time : 1.537 ms
D/TimaKeyStoreProvider( 9582): TimaSignature is unavailable
D/ActivityThread( 9582): Added TimaKeyStore provider
I/Mms/ReservationManager( 9518): ReservationManager()
I/Mms/ReservationManager( 9518): resetAfterConnected()
D/TP/MmsSmsProvider( 3982): query,matched:7, calling pid = 9518
D/TP/MmsSmsProvider( 3982): match 7:Elapsed time : 1.562 ms
D/ResourcesManager( 9582): creating new AssetManager and set to /system/app/PowerSharing/PowerSharing.apk
I/Mms/ReservationManager( 9518): getReservedSendMessageCount(): retMessageCount=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/PowerSharing.BatteryReceiver( 9582): onReceive : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
E/Zygote  ( 9599): MountEmulatedStorage()
E/Zygote  ( 9599): v2
I/libpersona( 9599): KNOX_SDCARD checking this for 10028
I/libpersona( 9599): KNOX_SDCARD not a persona
I/SELinux ( 9599): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9599): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9599): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=9599 uid=10028 gids={50028, 9997} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 8897:com.samsung.android.provider.filterprovider/u0a116 (adj 13): bgCount ##31
D/TimaKeyStoreProvider( 9599): TimaSignature is unavailable
D/ActivityThread( 9599): Added TimaKeyStore provider
D/BootupListener( 3982): ACTION_DRIVELINK
D/SettingsProvider( 3524): name = drivelink_navigation
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3982): NAVI : com.here.app.maps
D/SettingsProvider( 3524): name = internet_call_settings_visibility
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3982): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
I/ActivityManager( 3524): Killing 8921:com.samsung.helphub/1000 (adj 13): bgCount ##31
D/LocationWidgetUtils( 9178): getUpcommingInstances() start: 1457706943267, end: 1458255599999
D/LocationWidgetUtils( 9178): getUpcommingInstances() DB begin time >= start:1457706943267, DB begin time <= end:1458255599999
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/art     ( 3524): Explicit concurrent mark sweep GC freed 53026(2MB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 49MB/65MB, paused 1.534ms total 116.169ms
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 9599): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
W/ResourcesManager( 9599): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/Zygote  ( 9615): MountEmulatedStorage()
E/Zygote  ( 9615): v2
I/libpersona( 9615): KNOX_SDCARD checking this for 10163
I/libpersona( 9615): KNOX_SDCARD not a persona
I/SELinux ( 9615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9615): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=9615 uid=10163 gids={50163, 9997} abi=armeabi-v7a
D/AndroidRuntime( 9597): 
D/AndroidRuntime( 9597): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 9597): CheckJNI is OFF
D/AndroidRuntime( 9597): readGMSProperty: start
D/AndroidRuntime( 9597): readGMSProperty: already setted!!
D/AndroidRuntime( 9597): readGMSProperty: end
D/AndroidRuntime( 9597): addProductProperty: start
D/TimaKeyStoreProvider( 9615): TimaSignature is unavailable
D/ActivityThread( 9615): Added TimaKeyStore provider
I/OMACP   ( 9599): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ResourcesManager( 9615): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
W/ResourcesManager( 9615): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9615): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/Mms/Omacp( 9518): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/Mms/ArtClassLoader( 9518): init before art
D/Mms/ArtClassLoader( 9518): init [DONE] art
D/Mms/PerformanceUtils( 9518): link cahcing start
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 9599): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Mms/PerformanceUtils( 9518): link cahcing done
E/Zygote  ( 9639): MountEmulatedStorage()
I/libpersona( 9639): KNOX_SDCARD checking this for 10164
E/Zygote  ( 9639): v2
I/libpersona( 9639): KNOX_SDCARD not a persona
I/SELinux ( 9639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=9639 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 9639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Killing 8761:com.android.vending/u0a31 (adj 13): bgCount ##31
E/SELinux ( 9639): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 9639): TimaSignature is unavailable
E/AffinityControl( 9597): AffinityControl: registerfunction enter
D/ActivityThread( 9639): Added TimaKeyStore provider
D/ResourcesManager( 9639): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 9639): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9639): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9639): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9639): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/AndroidRuntime( 9597): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3524): mDVFSHelper.acquire()
D/PermissionCache( 2849): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (123 us)
I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, uhalitest
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(394/onUserLeaveHint)] 
I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 26
I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/AndroidRuntime( 9597): Shutting down VM
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(399/onUserLeaveHint)] Home Key!!
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3524): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/SettingSearchManagerReceiver( 3982): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 3982): addSearchInfoDB
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
D/SecContentProvider2( 3524): mCursor = null
D/ApplicationPolicy( 3524): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager( 3524): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 6298): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
E/Zygote  ( 9662): MountEmulatedStorage()
E/Zygote  ( 9662): v2
I/libpersona( 9662): KNOX_SDCARD checking this for 10181
I/libpersona( 9662): KNOX_SDCARD not a persona
I/SELinux ( 9662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
I/SELinux ( 9662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/SELinux ( 9662): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=9662 uid=10181 gids={50181, 9997} abi=armeabi-v7a
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
I/ActivityManager( 3524): Killing 8778:com.samsung.android.sdk.samsunglink/u0a42 (adj 13): bgCount ##31
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PanelView( 3690): There is/are notification(s) 
I/DBG_DM  ( 6298): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9677): MountEmulatedStorage()
E/Zygote  ( 9677): v2
I/libpersona( 9677): KNOX_SDCARD checking this for 10692
I/libpersona( 9677): KNOX_SDCARD not a persona
I/SELinux ( 9677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=9677 uid=10692 gids={50692, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 9662): TimaSignature is unavailable
D/ActivityThread( 9662): Added TimaKeyStore provider
I/SELinux ( 9677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9677): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/KnoxNotification( 3690): ----- inflateViews : modified publicViewLocal -----
D/KnoxNotification( 3690): ----- inflateViews : modified KnoxViewLocal -----
D/ResourcesManager( 9662): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
D/PersonaManager( 3690): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 3690): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@11164b69
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PanelView( 3690): There is/are notification(s) 
D/TimaKeyStoreProvider( 9677): TimaSignature is unavailable
D/ActivityThread( 9677): Added TimaKeyStore provider
D/StatusBarManagerService( 3524): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager( 9677): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
D/hwcutils( 2849): MppFactory::MppFactory()
D/        ( 2849): virtual LibMpp* MppFactory::CreateMpp(int, int, int, int) dev(4) mode(0) drm(0), 
D/libexynosgscaler( 2849): LibMpp::LibMpp()
D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
I/SettingSearchManagerReceiver( 3982): endInsert
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 9692): MountEmulatedStorage()
I/libpersona( 9692): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9692): v2
I/libpersona( 9692): KNOX_SDCARD not a persona
I/SELinux ( 9692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WebViewFactory( 9677): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
I/ActivityManager( 3524): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=9692 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager( 9677): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/ActivityManager( 3524): Killing 8992:com.osp.app.signin/u0a45 (adj 13): bgCount ##31
,I/LibraryLoader( 9677): Loading: webviewchromium
,I/LibraryLoader( 9677): Time to load native libraries: 4 ms (timestamps 1482-1486)
I/LibraryLoader( 9677): Expected native library version number "",actual native library version number ""
,D/TimaKeyStoreProvider( 9692): TimaSignature is unavailable
,D/ActivityThread( 9692): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager( 9692): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,V/WebViewChromiumFactoryProvider( 9677): Binding Chromium to main looper Looper (main, tid 1) {1e481552}
,I/LibraryLoader( 9677): Expected native library version number "",actual native library version number ""
,I/chromium( 9677): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/AssistantMenuSettingSearch( 9692): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 9692): Make Setting DB
,D/PackageManager( 3524): [MSG] MCS_UNBIND
,I/BrowserStartupController( 9677): Initializing chromium process, renderers=0
,W/art     ( 9677): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 9677): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 9677): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 9677): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium( 9677): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 9677): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 9677): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 9677): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 9677): CordovaWebView is running on device made by: samsung
,W/art     ( 9677): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 9677): Attempt to remove local handle scope entry from IRT, ignoring
,W/ContextImpl( 9692): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,I/ActivityManager( 3524): Killing 8973:com.android.keychain/1000 (adj 13): bgCount ##31
,D/Activity( 9677): performCreate Call secproduct feature valuefalse
D/Activity( 9677): performCreate Call debug elastic valuetrue
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/OpenGLRenderer( 9677): Render dirty regions requested: true
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9749): MountEmulatedStorage()
E/Zygote  ( 9749): v2
I/libpersona( 9749): KNOX_SDCARD checking this for 10122
I/libpersona( 9749): KNOX_SDCARD not a persona
,I/SELinux ( 9749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=9749 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9749): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 8199:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9749): TimaSignature is unavailable
,D/ActivityThread( 9749): Added TimaKeyStore provider
,I/SurfaceFlinger( 2849): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/ResourcesManager( 9749): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/OpenGLRenderer( 9677): Initialized EGL, version 1.4
,I/OpenGLRenderer( 9677): HWUI protection enabled for context ,  &this =0xaf545060 ,&mEglDisplay = 1 , &mEglConfig = -1357967088 
,D/OpenGLRenderer( 9677): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer( 9677): Enabling debug mode 0
,D/mali_winsys( 9677): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 9749): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3524): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 3524): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 9749): getAccountsCursor
,I/Gmail   ( 9749): Observing account changes for notifications
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/GAV2    ( 9749): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libexynosgscaler( 2849): virtual CGscaler::~CGscaler()
D/libexynosgscaler( 2849): virtual LibMpp::~LibMpp()
D/        ( 2849): virtual MppFactory::~MppFactory()
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Gmail   ( 9749): getAccountsCursor
,E/Gmail   ( 9749): Error finding the version of the Email provider.....
E/Gmail   ( 9749): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 9749): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   ( 9749): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 9749): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 9749): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 9749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 9749): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 9749): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 9749): We do not support migrating this version of the Email provider.
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3524): Displayed com.test.thalitest/.MainActivity: +603ms
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3524): Killing 9057:com.android.documentsui/u0a100 (adj 13): bgCount ##31
,I/Timeline( 9677): Timeline: Activity_idle id: android.os.BinderProxy@3e704108 time:41938
,E/SQLiteLog( 9749): (283) recovered 76 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 9749): notifyAccountChanged
,I/Gmail   ( 9749): getAccountsCursor
I/Gmail   ( 9749): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 9749): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 9749): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 9749): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 4820): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/JsMessageQueue( 9677): Set native->JS mode to OnlineEventsBridgeMode
,W/GCoreFlp( 4667): No location to return for getLastLocation()
W/FusedLocationProvider( 4667): location=null
,I/chromium( 9677): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 9677): 
,I/Gmail   ( 9749): getAccountsCursor
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/GCM     ( 4667): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/jxcore_app_log( 9677): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1627847936
,D/JX-Cordova( 9677): jxcore cordova android initializing
,I/SurfaceFlinger( 2849): id=12 Removed uhalitest (8/9)
,I/SurfaceFlinger( 2849): id=12 Removed uhalitest (-2/9)
,I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (4/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3524): mDVFSHelper.release()
I/Timeline( 3524): Timeline: Activity_windows_visible id: ActivityRecord{165881fd u0 com.test.thalitest/.MainActivity t32} time:42133
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d7459fe added. We now have 1 listener(s)
,D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@6
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): setBluetoothMacAddress: E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 9677): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 9677): setIdentityString: {"name":"<no peer name>","address":"E0:DB:10:14:E2:C0"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 9677): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 9677): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Bluetooth MAC address: E0:DB:10:14:E2:C0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d645075 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 9677): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 9677): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 9677): setScanMode: 1 -> 2
,D/SSRM:n  ( 3524): SIOP:: AP = 380, PST = 363, CUR = -831
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 27761(1700KB) AllocSpace objects, 2(32KB) LOS objects, 22% free, 53MB/69MB, paused 1.411ms total 101.179ms
,D/WifiService( 3524): New client listening to asynchronous messages
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9814): MountEmulatedStorage()
E/Zygote  ( 9814): v2
I/libpersona( 9814): KNOX_SDCARD checking this for 10125
I/libpersona( 9814): KNOX_SDCARD not a persona
,I/SELinux ( 9814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9814): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=9814 uid=10125 gids={50125, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8715(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 303us total 10.271ms
,D/TimaKeyStoreProvider( 9814): TimaSignature is unavailable
,D/ActivityThread( 9814): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 594us total 8.568ms
,D/ResourcesManager( 9814): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 9814): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 253us total 8.070ms
,I/Babel   ( 9814): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 9814): MmsConfig.loadMmsSettings
I/Babel   ( 9814): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
I/Babel   ( 9814): MmsConfig.loadFromDatabase
,D/ResourcesManager( 9814): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Babel   ( 9814): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 9814): MmsConfig.loadFromResources
,E/Babel   ( 9814): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 9814): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
,W/AudioCapabilities( 9814): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 9814): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 9814): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 9814): Unsupported mime audio/x-ima
W/Settings( 9814): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/VideoCapabilities( 9814): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 9814): Unsupported mime video/wvc1
,W/VideoCapabilities( 9814): Unsupported mime video/x-ms-wmv
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@6
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/VideoCapabilities( 9814): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 9814): Unsupported mime video/wvc1
,W/VideoCapabilities( 9814): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 9814): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 9814): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 9814): Unsupported mime video/sorenson
,W/VideoCapabilities( 9814): Unsupported mime video/mp43
,W/AudioCapabilities( 9814): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 9814): Unsupported mime audio/mpeg-L2
,W/VideoCapabilities( 9814): Unrecognized profile/level 32768/2 for video/mp4v-es
,E/SQLiteLog( 9814): (284) automatic index on conversation_participants_view(conversation_id)
,I/VideoCapabilities( 9814): Unsupported profile 4 for video/mp4v-es
,E/SQLiteLog( 9814): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 9814): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 9814): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 9814): (284) automatic index on conversation_participants_view(conversation_id)
,I/Mms/MmsApp( 9518):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 9518): [start]    fillCache consume time = 1933.236959
,D/Mms/ComposeMessageFragment( 9518): fillCache, easy = false
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AbsListView( 9518): Get MotionRecognitionManager
,D/MotionRecognitionService( 3524):  ssp status : true
,D/Mms/ComposeMessageFragment( 9518): [end]    fillCache consume time = 85.654542
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/BubbleViewCache( 9518): fillCache bubble = 8
,D/Widget  ( 9253): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 9253): widgetUpdate 5
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,E/Watchdog( 3524): !@Sync 1
,D/Widget  ( 9253): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/SettingsProvider( 3524): name = audio_safe_volume_state
,I/ActivityManager( 3524): Killing 9095:com.android.externalstorage/u0a9 (adj 13): bgCount ##31
,E/CscReceiver( 3982): onReceive android.intent.action.SIM_STATE_CHANGED
,D/CscReceiver( 3982): Recieve Sim State Changed : ABSENT
,I/splitIntent( 3524): Split this intent : android.intent.action.SIM_STATE_CHANGED !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10 divideNum= 2 r.nextReceiver= 1 receivers.size=12
I/splitIntent( 3524): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=3982, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/WifiApBroadcastReceiver( 8657): onReceive: action android.intent.action.SIM_STATE_CHANGED
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  ( 9860): MountEmulatedStorage()
E/Zygote  ( 9860): v2
I/libpersona( 9860): KNOX_SDCARD checking this for 1000
I/libpersona( 9860): KNOX_SDCARD not a persona
,I/SELinux ( 9860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=9860 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 9860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,W/jxcore-log( 9677): Initializing JXcore engine
W/jxcore-log( 9677): JXcore engine is ready
,E/SELinux ( 9860): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 9677): Starting JXcore engine
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 3524): name = internet_call_settings_visibility
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
,D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
,D/BootupListener( 3982): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
,D/TimaKeyStoreProvider( 9860): TimaSignature is unavailable
,D/ActivityThread( 9860): Added TimaKeyStore provider
,E/Zygote  ( 9876): MountEmulatedStorage()
E/Zygote  ( 9876): v2
I/libpersona( 9876): KNOX_SDCARD checking this for 1000
I/libpersona( 9876): KNOX_SDCARD not a persona
,I/SELinux ( 9876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
E/auditd  ( 4603): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3524): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
I/SELinux ( 9876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=9876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9891): MountEmulatedStorage()
E/Zygote  ( 9891): v2
I/libpersona( 9891): KNOX_SDCARD checking this for 10017
I/libpersona( 9891): KNOX_SDCARD not a persona
,I/SELinux ( 9891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider( 9876): TimaSignature is unavailable
,D/ActivityThread( 9876): Added TimaKeyStore provider
,I/SELinux ( 9891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=9891 uid=10017 gids={50017, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 9891): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent:SEDenialService( 3524): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,D/TimaKeyStoreProvider( 9891): TimaSignature is unavailable
,D/ActivityThread( 9891): Added TimaKeyStore provider
,W/jxcore-log( 9677): Platform android
W/jxcore-log( 9677): 
W/jxcore-log( 9677): Process ARCH arm
W/jxcore-log( 9677): 
D/ResourcesManager( 9860): creating new AssetManager and set to /system/app/MobileTrackerEngineTwo/MobileTrackerEngineTwo.apk
,D/ResourcesManager( 9876): creating new AssetManager and set to /system/app/SilentLog/SilentLog.apk
,D/ResourcesManager( 9891): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/StatusChecker( 9860): onReceive : android.intent.action.SIM_STATE_CHANGED
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9908): MountEmulatedStorage()
I/libpersona( 9908): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9908): v2
I/libpersona( 9908): KNOX_SDCARD not a persona
,I/SELinux ( 9908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=9908 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 9111:com.facebook.system/u0a10 (adj 13): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9908): TimaSignature is unavailable
,E/Zygote  ( 9923): MountEmulatedStorage()
E/Zygote  ( 9923): v2
I/libpersona( 9923): KNOX_SDCARD checking this for 10156
I/libpersona( 9923): KNOX_SDCARD not a persona
,I/SELinux ( 9923): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ActivityThread( 9908): Added TimaKeyStore provider
,I/SELinux ( 9923): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=9923 uid=10156 gids={50156, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,E/SELinux ( 9923): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
I/ActivityManager( 3524): Killing 8958:com.facebook.appmanager/u0a110 (adj 13): bgCount ##31
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/SmsReceiver( 9518): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
,D/TimaKeyStoreProvider( 9923): TimaSignature is unavailable
,D/ActivityThread( 9923): Added TimaKeyStore provider
,D/ResourcesManager( 9908): creating new AssetManager and set to /system/app/TcpdumpService/TcpdumpService.apk
,D/Mms/SmsReceiverService( 9518): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
,D/Mms/TelephonyPermission( 9518): isDefault true
D/Mms/SmsReceiverService( 9518): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
,D/Mms/SmsReceiverService( 9518): handleSIMStatus()
D/Mms/SmsReceiverService( 9518): handleSIMStatus(): SIM_STATUS = ABSENT
,I/ActivityManager( 3524): Killing 9160:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##31
,D/ResourcesManager( 9923): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager( 3524): Killing 9220:com.sec.factory/1000 (adj 13): bgCount ##31
,W/ResourcesManager( 9923): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9923): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9923): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/VerificationLog( 9923): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/OperatorBookmarksSIMReceiver( 9923): onReceive runs..android.intent.action.SIM_STATE_CHANGED
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9944): MountEmulatedStorage()
E/Zygote  ( 9944): v2
I/libpersona( 9944): KNOX_SDCARD checking this for 1000
I/libpersona( 9944): KNOX_SDCARD not a persona
,I/SELinux ( 9944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=9944 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9237:com.samsung.klmsagent/u0a21 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9944): TimaSignature is unavailable
,D/ActivityThread( 9944): Added TimaKeyStore provider
,D/ResourcesManager( 9944): creating new AssetManager and set to /system/app/SecSetupWizard2013/SecSetupWizard2013.apk
,I/splitIntent( 3524): Queue : backgroundsplit_1 intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3524): Killing 9275:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9960): MountEmulatedStorage()
I/libpersona( 9960): KNOX_SDCARD checking this for 10036
E/Zygote  ( 9960): v2
I/libpersona( 9960): KNOX_SDCARD not a persona
I/SELinux ( 9960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9960): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.cignacoach.receiver.CignaCoachReceiver: pid=9960 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9960): TimaSignature is unavailable
,D/ActivityThread( 9960): Added TimaKeyStore provider
,D/ResourcesManager( 9960): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/jxcore-log( 9677): JXcore Cordova bridge is ready!
I/jxcore-log( 9677): 
W/jxcore-log( 9677): JXcore engine is started
,I/Choreographer( 9677): Skipped 75 frames!  The application may be doing too much work on its main thread.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): checkState()
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): checkState() : APP TYPE = Full
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isFitnessWithGearInstalled() : Fitness with Gear isn't Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService1xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService1xInstalled() : HEALTH SERVICE VERSION is NOT 1.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService0xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService0xInstalled() : HEALTH SERVICE VERSION is NOT 0.x !!!
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:2, health:2, present:true, voltage: 4207, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-933, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1402
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/org.thaliproject.p2p.ThaliPermissions( 9677): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/Zygote  ( 9988): MountEmulatedStorage()
I/libpersona( 9988): KNOX_SDCARD checking this for 10019
E/Zygote  ( 9988): v2
I/libpersona( 9988): KNOX_SDCARD not a persona
,I/SELinux ( 9988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.service.health for content provider com.sec.android.service.health/.cp.MigrationCpProvider: pid=9988 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/SELinux ( 9988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9988): TimaSignature is unavailable
,D/ActivityThread( 9988): Added TimaKeyStore provider
,I/chromium( 9677): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/ResourcesManager( 9988): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): checkState() : =========== UPGRADE_STATE_APP_UPGRADE_DONE ===========
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/com.sec.android.service.health.keyManager.KeyManager( 9960): Current encrypted state : -1
,I/SecSQLiteOpenHelper( 9960): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 9960): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 9960): Open platform.db in secure mode
D/SecSQLiteDatabase( 9960): Android Version: 5.0.1
D/SecSQLiteDatabase( 9960): Load library secsqlite.so for Android 5.0.1
,I/SecSQLiteDatabase( 9960): openSecureDatabase...
,I/SecSQLiteDatabase( 9960): private openSecureDatabase...
I/SecSQLiteConnectionPool( 9960): OpenSecure
I/SecSQLiteConnectionPool( 9960): OpenSecure with password
I/SecSQLiteConnectionPool( 9960): openSecureConnectionLocked
,I/SecSQLiteDatabase( 9960): ...private openSecureDatabase
I/SecSQLiteDatabase( 9960): ...openSecureDatabase
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SQLiteLog( 9960): (26) statement aborts at 0: [PRAGMA user_version;] file is encrypted or is not a database
,E/SecDefaultDatabaseErrorHandler( 9960): Corruption reported by sqlite on database: /data/data/com.sec.android.app.shealth/databases/platform.db
E/SecDefaultDatabaseErrorHandler( 9960): backup the database file: /data/data/com.sec.android.app.shealth/databases/platform.db
D/SecSQLiteOpenHelper( 9960): ...getDatabaseLocked(b,b,pwd)
,I/SecureStorage( 9988): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage( 2919): [INFO]: SPID(0x00000004)Credentials: uid 10019, gid 10019, pid 9988
I/SecureStorage( 2919): [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{162f9eb6 u0 com.sec.android.service.sm/.service.SecurityManagerService}
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SecureStorage( 2919): [INFO]: SPID(0x00000005)Secure Storage Daemon finished processing with result: 0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SecureStorage( 9988): [INFO]: SPID(0x00000005)Processing data has been completed
,I/SecureStorage( 9988): [INFO]: SPID(0x00000005)Skip using SecureStorageExceptionJNI
I/SecSQLiteOpenHelper( 9960): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 9960): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 9960): Open platform.db in secure mode
I/SecSQLiteDatabase( 9960): openSecureDatabase...
I/SecSQLiteDatabase( 9960): private openSecureDatabase...
I/SecSQLiteConnectionPool( 9960): OpenSecure
I/SecSQLiteConnectionPool( 9960): OpenSecure with password
I/SecSQLiteConnectionPool( 9960): openSecureConnectionLocked
I/SecSQLiteDatabase( 9960): ...private openSecureDatabase
I/SecSQLiteDatabase( 9960): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 9960): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 9960): ...getDatabaseLocked(b,b,pwd)
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/-----SIC-----( 9960): ------------------skip TGH
,I/SecSQLiteOpenHelper( 9960): getWritableDatabase(pwd)
I/SecSQLiteOpenHelper( 9960): getDatabaseLocked(b,b,pwd)...
I/SecSQLiteOpenHelper( 9960): Open platform.db in secure mode
I/SecSQLiteDatabase( 9960): openSecureDatabase...
I/SecSQLiteDatabase( 9960): private openSecureDatabase...
I/SecSQLiteConnectionPool( 9960): OpenSecure
I/SecSQLiteConnectionPool( 9960): OpenSecure with password
I/SecSQLiteConnectionPool( 9960): openSecureConnectionLocked
I/SecSQLiteDatabase( 9960): ...private openSecureDatabase
I/SecSQLiteDatabase( 9960): ...openSecureDatabase
,I/SecSQLiteOpenHelper( 9960): ...getDatabaseLocked(b,b,pwd)
D/SecSQLiteOpenHelper( 9960): ...getDatabaseLocked(b,b,pwd)
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9960): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.app.shealth/files/
W/ContextImpl( 9960): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.app.shealth/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,V/MediaPlayer( 9960): decode(36, 20909908, 4230)
,V/MediaPlayerService( 2855): decode(26, 20909908, 4230)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
I/ActivityManager( 3524): Killing 9293:com.sec.android.app.SPenKeeper/u0a161 (adj 13): bgCount ##31
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20909908, 4230)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=20770 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port,
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/MediaPlayerService( 2855): wait for playback complete
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x6c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
,I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(37, 20763080, 15440)
V/MediaPlayerService( 2855): decode(26, 20763080, 15440)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20763080, 15440)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
,V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
,I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=849387 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
,V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
,V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,D/AdaptiveEventManager( 3690): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3690): M updateContainers()
D/AdaptiveEventContainerSmall( 3690): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3690): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3690): pedoEvent == null
D/AdaptiveEventManager( 3690): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 3690): M updateContainers()
,D/AdaptiveEventContainerSmall( 3690): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 3690): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 3690): pedoEvent == null
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2855): wait for playback complete
,W/System.err( 9960): java.lang.NumberFormatException: Invalid int: "null"
,W/System.err( 9960): 	at java.lang.Integer.invalidInt(Integer.java:138)
W/System.err( 9960): 	at java.lang.Integer.parseInt(Integer.java:358)
W/System.err( 9960): 	at java.lang.Integer.parseInt(Integer.java:334)
W/System.err( 9960): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager.setProfileItems(LogManager.java:498)
W/System.err( 9960): 	at com.sec.android.app.shealth.common.utils.logging.service.LogManager$LogHandler.handleMessage(LogManager.java:1242)
W/System.err( 9960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9960): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 9960): RegionGroup for  is null
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x6d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(38, 20807608, 9226)
,V/MediaPlayerService( 2855): decode(26, 20807608, 9226)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20807608, 9226)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
E/DatabaseUtils( 3524): Writing exception to parcel
E/DatabaseUtils( 3524): java.lang.NullPointerException: key == null
E/DatabaseUtils( 3524): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils( 3524): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils( 3524): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils( 3524): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:376)
E/DatabaseUtils( 3524): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=404897 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
V/MediaPlayerService( 2855): wait for playback complete
,I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
,D/LocationWidgetUtils( 9178): getUpcommingInstances() start: 1457706946957, end: 1458255599999
D/LocationWidgetUtils( 9178): getUpcommingInstances() DB begin time >= start:1457706946957, DB begin time <= end:1458255599999
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x6e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(40, 20914220, 4890)
V/MediaPlayerService( 2855): decode(26, 20914220, 4890)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20914220, 4890)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=64058 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 6, 0, 0)
V/AudioCache( 2855): ignored
I/AudioPlayer( 2855): First fillBuffer call!!
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
,V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x6f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(42, 20840384, 17329)
V/MediaPlayerService( 2855): decode(26, 20840384, 17329)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20840384, 17329)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
,I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=857142 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x70, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(41, 20740576, 6644)
V/MediaPlayerService( 2855): decode(26, 20740576, 6644)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20740576, 6644)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=213446 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x71, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(43, 20816916, 23389)
V/MediaPlayerService( 2855): decode(26, 20816916, 23389)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20816916, 23389)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): wait for playback complete
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x72, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(36, 20706272, 8154)
V/MediaPlayerService( 2855): decode(26, 20706272, 8154)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20706272, 8154)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=405328 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
,I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
V/MediaPlayerService( 2855): wait for playback complete
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x73, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(46, 20679752, 4804)
I/libencoder( 3524): width= 768, height = 768, colot_type= 6, bit_depth= 8
V/MediaPlayerService( 2855): decode(26, 20679752, 4804)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20679752, 4804)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=110476 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 6, 0, 0)
I/AudioPlayer( 2855): First fillBuffer call!!
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x74, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(39, 20649204, 9400)
V/MediaPlayerService( 2855): decode(26, 20649204, 9400)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20649204, 9400)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=731360 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
,V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1371687361, value : -825995581
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1371687361, value : -825995581
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x75, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(44, 20857804, 52024)
V/MediaPlayerService( 2855): decode(26, 20857804, 52024)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20857804, 52024)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
,V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
,V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
V/MediaPlayer( 9960): decode(50, 20722624, 4112)
V/MediaPlayerService( 2855): decode(37, 20722624, 4112)
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/MediaPlayerService( 2855): player type = 3
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=2880000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
,V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(37, 20722624, 4112)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
,V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
,V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
,V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
,V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
,I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
,V/AudioCache( 2855): open(48000, 2, 0x0, 1, 0)
V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 6, 0, 0)
V/AudioCache( 2855): ignored
,V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
V/AudioCache( 2855): wait - success
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
,V/MediaPlayerService( 2855): wait for playback complete
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
,V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
D/TaskPersister( 3524): removeObsoleteFile: deleting file=31_task_thumbnail.png
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x77, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
,V/AwesomePlayer( 2855): addBatteryData
,V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x76, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
,I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(45, 20722624, 4112)
,V/MediaPlayerService( 2855): decode(26, 20722624, 4112)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
V/AwesomePlayer( 2855): setDefault
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20722624, 4112)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=4331 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 2855): open(44100, 1, 0x0, 1, 0)
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1287635273, value : -859651136
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1287635273, value : -859651136
V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/MediaPlayerService( 2855): wait for playback complete
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
,V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xae822380, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x78, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/MediaPlayer( 9960): decode(47, 20785700, 21825)
,V/MediaPlayerService( 2855): decode(26, 20785700, 21825)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20785700, 21825)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
,V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
,V/AudioCache( 2855): notify(0xb020d330, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb020d330, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x79, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
,V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
,V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(48, 20684636, 21552)
V/MediaPlayerService( 2855): decode(26, 20684636, 21552)
,V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20684636, 21552)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=1250000 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
,V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 6, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): addBatteryData
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1347078729, value : -934492341
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1347078729, value : -934492341
V/MediaPlayerService( 2855): wait for playback complete
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
,V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
,V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xb0009290, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
,V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2855): mAudioTrackVector clear
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2855): mSecCapture clear
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/MediaPlayer( 9960): decode(49, 20778600, 7017)
,V/MediaPlayerService( 2855): decode(26, 20778600, 7017)
V/MediaPlayerService( 2855): player type = 3
V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): constructor
,V/AwesomePlayer( 2855): setDefault
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): StagefrightPlayer
V/AwesomePlayer( 2855): setListener
V/StagefrightPlayer( 2855): initCheck
V/AwesomePlayer( 2855): setAudioSink
V/StagefrightPlayer( 2855): setDataSource(26, 20778600, 7017)
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,V/AwesomePlayer( 2855): track of type 'audio/vorbis' does not publish bitrate
,V/AwesomePlayer( 2855): mBitrate = -1 bits/sec
I/OggExtractor( 2855): OggSource::OggSource() mExtractor ref count = 4
V/AwesomePlayer( 2855): current audio track index (0) is added to vector
V/AwesomePlayer( 2855): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 2855): checkRightsStatus is not necessary - AwesomePlayer::setDataSource_l
V/MediaPlayerService( 2855): prepare
V/AwesomePlayer( 2855): prepareAsync
V/MediaPlayerService( 2855): wait for prepare
V/AwesomePlayer( 2855): onPrepareAsyncEvent
I/SecMediaClock( 2855): SecMediaClock constructor
I/SecMediaClock( 2855): reset
I/SecVideoCapture( 2855): SecVideoCapture constructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): initAudioDecoder
,V/AwesomePlayer( 2855): checkOffloadExceptions is true
V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/AwesomePlayer( 2855): Could not offload audio decode, try pcm offload
,V/AudioPolicyManager( 2855): isOffloadSupported: SR=44100, CM=0x1, Format=0x1, StreamType=-1, BitRate=4294967295, duration=173945 us, has_video=0
V/AudioPolicyManager( 2855): isOffloadSupported: stream_type != MUSIC, returning false
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 2855): finishAsyncPrepare_l
V/AwesomePlayer( 2855): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
,V/AudioCache( 2855): notify(0xaf2ebb00, 200, 973, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 5, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 1, 0, 0)
V/AudioCache( 2855): prepared
V/AudioCache( 2855): wait - success
V/MediaPlayerService( 2855): start
,V/StagefrightPlayer( 2855): start
V/AwesomePlayer( 2855): play
V/AwesomePlayer( 2855): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 2855): startAudioPlayer_l, sendErrorNotification (0)
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
,I/OMXCodec( 2855): >>>UHQA initOutputFormat 16
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat:2, 1, 0
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
I/AudioPlayer( 2855): Audioplayer kKeyAudioPCMFormat read fail(2, 1)
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
V/AudioCache( 2855): open(44100, 2, 0x0, 1, 0)
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10120): MountEmulatedStorage()
V/AwesomePlayer( 2855): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 6, 0, 0)
V/AudioCache( 2855): ignored
I/AudioPlayer( 2855): First fillBuffer call!!
I/AudioPlayer( 2855): >>> setAudioEffect Read mAudioFormat : 1, event : 1254313410, value : 1288195915
E/AudioPlayer( 2855): >>> setAudioEffect Error mAudioFormat : 1, event : 1254313410, value : 1288195915
V/AwesomePlayer( 2855): addBatteryData
E/Zygote  (10120): v2
,I/libpersona(10120): KNOX_SDCARD checking this for 10037
I/libpersona(10120): KNOX_SDCARD not a persona
V/MediaPlayerService( 2855): wait for playback complete
,I/SELinux (10120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] End Of Stream
E/SELinux (10120): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/AwesomePlayer( 2855): postAudioEOS delayUs (0)
V/AwesomePlayer( 2855): onCheckAudioStatus
V/AwesomePlayer( 2855): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 2855): onStreamDone
V/AwesomePlayer( 2855): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 2855): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 2, 0, 0)
V/AudioCache( 2855): playback complete - thread will wake up later
V/AwesomePlayer( 2855): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 7, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 2855): addBatteryData
V/AudioCache( 2855): wait - success
V/StagefrightPlayer( 2855): reset
,V/AwesomePlayer( 2855): reset_l()
I/ActivityManager( 3524): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=10120 uid=10037 gids={50037, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 2855): notify(0xaf2ebb00, 8, 0, 0)
V/AudioCache( 2855): ignored
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stop() sendCommand(0x7b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 2855): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,I/OMXCodec( 2855): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/OggExtractor( 2855): OggSource::stop() mExtractor ref count = 1
I/OggExtractor( 2855): OggSource::~OggSource() mExtractor !mStarted ref count = 1
I/OggExtractor( 2855): ~OggSource --
I/OggExtractor( 2855): ~OggExtractor ++
I/OggExtractor( 2855): ~MyVorbisExtractor ++ 
I/OggExtractor( 2855): ~MyVorbisExtractor --
I/OggExtractor( 2855): ~OggExtractor --
,I/ActivityManager( 3524): Killing 9319:com.sec.android.app.videoplayer/u0a56 (adj 13): bgCount ##31
,I/AudioPlayer( 2855): reset out
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
I/SecVideoCapture( 2855): SecVideoCapture destructor
I/SecVideoCapture( 2855): reset
V/AwesomePlayer( 2855): mSecCapture clear
I/SecMediaClock( 2855): SecMediaClock destructor
V/AwesomePlayer( 2855): mSecMediaClock clear
V/StagefrightPlayer( 2855): ~StagefrightPlayer
V/StagefrightPlayer( 2855): reset
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
V/AwesomePlayer( 2855): destructor
V/AwesomePlayer( 2855): reset_l()
V/AwesomePlayer( 2855): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 2855): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 2855): mAudioTrackVector clear
V/AwesomePlayer( 2855): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 2855): mSecCapture clear
V/AwesomePlayer( 2855): mSecMediaClock clear
,D/TimaKeyStoreProvider(10120): TimaSignature is unavailable
,D/ActivityThread(10120): Added TimaKeyStore provider
,D/ResourcesManager(10120): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(10120): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(10120): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(10120): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10120): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10120): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
,W/ResourcesManager(10120): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,D/ResourcesManager(10120): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(10120): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10120): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,I/FaceInterface( 9468): startFaceScan() : going on
D/FaceInterface( 9468): startFaceScan() is called.
,D/ContentApp( 5414): startScan() is called.
,D/FaceValue( 5414): mSleepTime: 800
D/FaceValue( 5414): mMaxThreadNum: 2
,D/ContentApp( 5414): startScan() is end.
,D/ContentApp( 5414): face_restore FINISHED_TYPE: 3
D/FaceScanner( 5414): isNeedToRestore : start
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10158): MountEmulatedStorage()
E/Zygote  (10158): v2
I/libpersona(10158): KNOX_SDCARD checking this for 10039
I/libpersona(10158): KNOX_SDCARD not a persona
,I/SELinux (10158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10158): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.ForceUpdateAlarmReceiver: pid=10158 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9397:com.samsung.dcm:DCMService/u0a4 (adj 13): bgCount ##31
,I/FaceInterface( 9468): startFaceScan() : going on
,D/FaceInterface( 9468): startFaceScan() is called.
,D/ContentApp( 5414): startScan() is called.
,D/ContentApp( 5414): startScan() is end.
,D/ContentApp( 5414): face_restore FINISHED_TYPE: 3
D/FaceScanner( 5414): isNeedToRestore : start
,D/TimaKeyStoreProvider(10158): TimaSignature is unavailable
,D/ActivityThread(10158): Added TimaKeyStore provider
,D/ResourcesManager(10158): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(10158): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(10158): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService(10158): PushLog.txt file is not deleted.
D/SPPClientService(10158): PushLog.txt file is not deleted.
D/SPPClientService(10158): ============PushLog. stop!
,E/SPPClientService(10158): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10178): MountEmulatedStorage()
I/libpersona(10178): KNOX_SDCARD checking this for 10039
E/Zygote  (10178): v2
I/libpersona(10178): KNOX_SDCARD not a persona
I/SELinux (10178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10178): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=10178 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 9449:com.sec.android.app.music:service/u0a44 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8758(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 504us total 11.420ms
,V/AlarmManager( 3524): waitForAlarm result :8
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 256us total 8.810ms
,D/TimaKeyStoreProvider(10178): TimaSignature is unavailable
,D/ActivityThread(10178): Added TimaKeyStore provider
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 296us total 9.391ms
,D/ResourcesManager(10178): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10064
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SPPClientService(10178): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(10178): [PushClientApplication] Push log off : This is Ship build version
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SPPClientService(10178): PushLog.txt file is not deleted.
D/SPPClientService(10178): PushLog.txt file is not deleted.
D/SPPClientService(10178): ============PushLog. stop!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10202): MountEmulatedStorage()
E/Zygote  (10202): v2
I/libpersona(10202): KNOX_SDCARD checking this for 10039
I/libpersona(10202): KNOX_SDCARD not a persona
,I/SELinux (10202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=10202 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (10202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10202): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9468:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10202): TimaSignature is unavailable
,D/ActivityThread(10202): Added TimaKeyStore provider
,D/ResourcesManager(10202): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService(10202): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(10202): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   (10202): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/SPPClientService(10202): PushLog.txt file is not deleted.
D/SPPClientService(10202): PushLog.txt file is not deleted.
D/SPPClientService(10202): ============PushLog. stop!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log( 9677): INFO testUtils Toggling radios to: true
I/jxcore-log( 9677): 
,D/BluetoothAdapter( 9677): enable()
,D/BluetoothAdapter( 9677): enable(): BT is already enabled..!
,I/jxcore-log( 9677): Unit Test app is loaded
I/jxcore-log( 9677): 
,I/Choreographer( 9677): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/WifiManager( 9677): packageName : com.test.thalitest
,D/SecContentProvider( 3524): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3524): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3524): mCursor = null
,D/WifiService( 3524): setWifiEnabled: true pid=9677, uid=10692
E/WifiService( 3524): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager( 3524): Permission Denial: getCurrentUser() from pid=9677, uid=10692 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 3524): Failed getting userId using ActivityManagerNative
W/WifiService( 3524): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=9677, uid=10692 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 3524): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23202)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2185)
W/WifiService( 3524): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2173)
W/WifiService( 3524): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider( 3524): name = wifi_on
,I/chromium( 9677): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 9677): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3524): getProviders()=[]
D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager( 9178): mPrivacy is null
,W/ContextImpl( 9178): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager( 9178): Service for PrivacyManager is connected
,D/BluetoothManager( 9960): getConnectedDevices
D/BluetoothManager( 9960): getConnectedDevices
,D/BluetoothManager( 9960): getConnectedDevices
,D/LWLocationManager( 9178): Privacy service : STATUS_PLACE
,D/LWLocationManager( 9178): updateLocationStatus()
,I/LocationWidgetFuctionData( 9178): readDB
,D/BluetoothManager( 9960): getConnectedDevices
,I/LocationWidgetFuctionData( 9178): selectedAppSize: 3
,I/LocationWidgetFuctionData( 9178): configPlaceList aroundMeItems
,D/BluetoothManager( 9960): getConnectedDevices
,D/BluetoothManager( 9960): getConnectedDevices
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10234): MountEmulatedStorage()
E/Zygote  (10234): v2
I/libpersona(10234): KNOX_SDCARD checking this for 10003
I/libpersona(10234): KNOX_SDCARD not a persona
I/SELinux (10234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10234 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10234): TimaSignature is unavailable
,D/ActivityThread(10234): Added TimaKeyStore provider
,E/Zygote  (10249): MountEmulatedStorage()
E/Zygote  (10249): v2
I/libpersona(10249): KNOX_SDCARD checking this for 1000
I/libpersona(10249): KNOX_SDCARD not a persona
,I/SELinux (10249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=10249 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9345:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3524): Killing 9547:com.sec.smartcard.manager/u0a187 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10249): TimaSignature is unavailable
,D/ActivityThread(10249): Added TimaKeyStore provider
,D/ResourcesManager(10234): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/ResourcesManager(10249): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/UserAnalysis.PlaceProvider(10234): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager(10234): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(10234): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10234): Create SecureDbHelper
,I/DIAGMON_AGENT(10249): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
D/IntelligenceServiceApplication(10234): onCreate()
,I/LocationWidgetFuctionData( 9178): selectedAppSize: 3
,I/LocationWidgetFuctionData( 9178): selectedAppSize: 3
,I/LocationWidgetFuctionData( 9178): selectedAppSize: 3
,I/LocationWidgetFuctionData( 9178): selectedAppSize: 3
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/DIAGMON_AGENT(10249): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT(10249): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT(10249): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 3524): Killing 9562:com.sec.android.provider.badge/u0a82 (adj 13): bgCount ##31
,I/DBG_DM  ( 6298): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,E/LWLocationManager( 9178): findLocationType() : cursor_location.moveToFirst() return false!!
,D/Widget  ( 9253): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 9253): widgetUpdate 5
D/LWLocationManager( 9178): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager( 9178): setShouldUpdateLocationId
D/LWLocationManager( 9178): setShouldUpdateLocationId return false
D/LWLocationManager( 9178): setShouldUpdateLocationId
D/LWLocationManager( 9178): setShouldUpdateLocationId return false
D/LWLocationManager( 9178): setShouldUpdateLocationId
D/LWLocationManager( 9178): setShouldUpdateLocationId return false
D/LWLocationManager( 9178): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/Widget  ( 9253): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10264): MountEmulatedStorage()
,E/Zygote  (10264): v2
I/libpersona(10264): KNOX_SDCARD checking this for 10173
I/libpersona(10264): KNOX_SDCARD not a persona
,I/SELinux (10264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10264 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux (10264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10264): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10264): TimaSignature is unavailable
,D/ActivityThread(10264): Added TimaKeyStore provider
,D/ResourcesManager(10264): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity(10264): TaskCloserActivity enter()
,V/TaskCloserActivity(10264): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/Widget  ( 9253): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  ( 9253): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 9253): widgetUpdate 5
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10280): MountEmulatedStorage()
,E/Zygote  (10280): v2
I/libpersona(10280): KNOX_SDCARD checking this for 1000
,I/libpersona(10280): KNOX_SDCARD not a persona
,I/SELinux (10280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=10280 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10280): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10280): TimaSignature is unavailable
,D/ActivityThread(10280): Added TimaKeyStore provider
,D/ResourcesManager(10280): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,E/MTPRx   (10280): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
D/SecContentProvider2( 3524): mCursor = null
,D/SecContentProvider2( 3524): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 3524): mCursor = null
,V/MTPRx   (10280): sealedState: false
V/MTPRx   (10280): sealedUsbMassStorageState: false
E/MTPRx   (10280): check value of boot_completed is1
E/MTPRx   (10280): check booting is completed_sys.boot_completed
,E/MTPRx   (10280): Sd-Card path/storage/extSdCard
,E/MTPRx   (10280): Status for mount/Unmount :removed
E/MTPRx   (10280): SDcard is not available
,W/MTPRx   (10280): value of connected istrue
W/MTPRx   (10280): value of configured istrue
W/MTPRx   (10280): value of mtpEnabled isfalse
W/MTPRx   (10280): value of ptpEnabled istrue
,E/MTPRx   (10280): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   (10280): mFirstTime: false
,D/        (10280): MTP: reading debug level property
,E/MTPJNIInterface(10280): Getting CryptionKey from JAVA
E/MTPRx   (10280): currentUserId is 0
,E/MTPRx   (10280): Start observing USB_STATE_MATCH 
,E/MTPRx   (10280): usbMode is 0200
E/MTPRx   (10280): is_Privatemode is NOT 1
,D/SettingsProvider( 3524): name = mtp_usb_conditions_met
,D/SecContentProvider( 3524): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   (10280): sending PTP_ICON_ENABLED to stack 
,D/SettingsProvider( 3524): name = mtp_running_status
,D/SettingsProvider( 3524): name = mtp_usb_conditions_met
,E/MTPRx   (10280): else part ... so first time!!!
,E/MTPPlaObsrvr(10280): inside setContext()
,E/MTPPlaObsrvr(10280):  inside createplafiles
,I/CheckinService( 4820): Done disabling old GoogleServicesFramework version
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 57850(5MB) AllocSpace objects, 12(2MB) LOS objects, 23% free, 53MB/69MB, paused 2.212ms total 156.511ms
,E/MTPPlaObsrvr(10280): playlist count is0
E/MTPPlaObsrvr(10280):  inside try branch createplafiles
,E/MTPPlaObsrvr(10280):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr(10280): Inside registerContentObserver
,E/MtpAdbObserver(10280): inside setContext()
,E/MtpAdbObserver(10280): Inside registerContentObserver
,W/Settings(10280): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/CalendarAlarmManager( 9196): sys current time:1457706948940
,D/CalendarAlarmManager( 9196): reminder amount:0
,D/SettingsProvider( 3524): name = mtp_running_status
,I/ActivityManager( 3524): Killing 9035:com.sec.android.app.popupuireceiver/1000 (adj 13): bgCount ##31
,D/SettingsProvider( 3524): name = mtp_usb_conditions_met
,E/MtpService(10280): onCreate.
,E/MtpService(10280): < MTP > Registering BroadCast receiver :::::
,E/MtpService(10280): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService(10280): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService(10280): onStartCommand.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/MTPRx   (10280): calling native method
,E/MTPJNIInterface(10280): < MTP > Registering BroadCast receiver :::::
,E/MtpService(10280): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/MtpService( 5414): updating state; isCurrentUser=true, mMtpLocked=false
,E/MTPJNIInterface(10280): < MTP > Registering BroadCast receiver :::::::
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10300): MountEmulatedStorage()
I/libpersona(10300): KNOX_SDCARD checking this for 1000
E/Zygote  (10300): v2
I/libpersona(10300): KNOX_SDCARD not a persona
,I/SELinux (10300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=10300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface(10280): noti = 11
,E/MtpService(10280): onStartCommand.
,E/MtpService(10280): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   (10280): calling native method
E/MTPRx   (10280): Checking the driver time out
,E/MTPJNIInterface(10280): noti = 2
D/        (10280): deleting sockets before message queue initialization
,D/        (10280): event handler thread is created, so set the flag
,E/        (10280): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPRx   (10280): called native method
E/MTPJNIInterface(10280): setting Media scanner status0
E/MTPJNIInterface(10280): Getting media scanner status0
E/MTPJNIInterface(10280): After setting Media scanner status0
W/MTPRx   (10280): notification from stack 1
,E/MTPJNIInterface(10280): DeviceName is Note4-1
,I/GAV2    ( 9749): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider(10300): TimaSignature is unavailable
,D/ActivityThread(10300): Added TimaKeyStore provider
,D/ResourcesManager(10300): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/TMNetworkReceiver(10300): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive() Exit 
,D/TMNetworkReceiver(10300): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
,D/TMSLogRemovalReceiver(10300): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver(10300): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver(10300): TMLogRemovalReceiver.onReceive() Exit
,I/ActivityManager( 3524): Killing 9582:com.samsung.android.app.powersharing/u0a149 (adj 13): bgCount ##31
,D/MediaScannerReceiver( 5414): action: android.intent.action.MTP_FILE_SCAN
,D/LocationWidgetUtils( 9178): getUpcommingInstances() start: 1457706949307, end: 1458255599999
D/LocationWidgetUtils( 9178): getUpcommingInstances() DB begin time >= start:1457706949307, DB begin time <= end:1458255599999
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LWLocationManager( 9178): getDeviceLocationId :  id = -100
D/LocationWidgetApplication( 9178): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10326): MountEmulatedStorage()
E/Zygote  (10326): v2
I/libpersona(10326): KNOX_SDCARD checking this for 10035
I/libpersona(10326): KNOX_SDCARD not a persona
,I/SELinux (10326): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10326): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=10326 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (10326): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/MediaScannerService( 5414): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,D/TimaKeyStoreProvider(10326): TimaSignature is unavailable
,D/ActivityThread(10326): Added TimaKeyStore provider
,I/Avrcp   ( 5599): Received the onChange database event
I/Avrcp   ( 5599): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 5599): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 5414): savePlaylistTableInBulkDeleter finished
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/MediaScanner( 5414): Prescan. DB items number : 62 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/MediaScanner( 5414): processDirectory :  /storage/emulated/0
,D/MediaScanner( 5414): Skipping:
D/MediaScanner( 5414): 7klwibgf7fvntblfd7(75ebcf7
,I/FeatureConfig(10326): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/MediaScanner( 5414): Skipping:
D/MediaScanner( 5414): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 5414): processDirectory :  /storage/extSdCard
W/MediaScanner( 5414): Error opening directory, reason : Permission denied.
W/MediaScanner( 5414): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 5414):  prescan time: 33ms (DB items: 62)
V/MediaScanner( 5414):     scan time: 32ms (Caching mode: true), (makeEntry time: 20ms ~62%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 5414): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 5414):    total time: 67ms
V/MediaScanner( 5414): checked files: 19  directories : 36  (I: 0, U: 0)
,I/iu.UploadsManager( 4820): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/MediaScannerService( 5414): !@done scanning volume external
,E/MTPJNIInterface(10280): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,W/ResourcesManager(10326): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(10326): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10326): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10326): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10326): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(10326): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(10326): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3524): Killing 9599:com.wsomacp/u0a28 (adj 13): bgCount ##31
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager(10326): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager(10326): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Zygote  (10345): MountEmulatedStorage()
E/Zygote  (10345): v2
I/libpersona(10345): KNOX_SDCARD checking this for 10050
I/libpersona(10345): KNOX_SDCARD not a persona
,I/SELinux (10345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(10326): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/SELinux (10345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourcesManager(10326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SELinux (10345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=10345 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(10326): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(10326): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(10326): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(10345): TimaSignature is unavailable
,D/ActivityThread(10345): Added TimaKeyStore provider
,D/ResourcesManager(10326): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager(10326): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(10326): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication(10326): system/finder_cp/cpdata.xml file not found
,D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/iu.UploadsManager( 4820): End new media; added: 0, uploading: 0, time: 135 ms
,W/ResourcesManager(10345): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10345): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10345): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(10345): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(10345): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
,D/NearbySource(10345): Nearby Source Create!
,D/NearbyContext(10345): Nearby Context Create!
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10345): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(10345): Samsung link source created
,E/MTPJNIInterface(10280): Status for mount/Unmount :removed
E/MTPJNIInterface(10280): SDcard is not available
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider(10345): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/        (10280): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface(10280): Status for mount/Unmount :removed
E/MTPJNIInterface(10280): SDcard is not available
E/SQLiteLog(10280): (21) API call with NULL database connection pointer
E/SQLiteLog(10280): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog(10280): (21) API call with NULL database connection pointer
E/SQLiteLog(10280): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog(10280): (21) API call with NULL database connection pointer
E/SQLiteLog(10280): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog(10280): (21) API call with NULL database connection pointer
E/SQLiteLog(10280): (21) misuse at line 105958 of [9491ba7d73]
,W/MTPRx   (10280): notification from stack 2
,D/        (10280): [mtp_init_device] Library open with 32 bits.
D/        (10280): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        (10280): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        (10280): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        (10280):  [sua_support_present:1277] returning false 
D/        (10280): *****Starting mtp_io()
W/MTPRx   (10280): notification from stack 3
D/        (10280): [mtp_start_io] source_thread Creation 
D/        (10280): [mtp_start_io] sink_thread Creation 
D/        (10280): [mtp_start_io:368] sink thread created so set th_sink
,I/UpdateIcingCorporaServi( 4057): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10371): MountEmulatedStorage()
I/libpersona(10371): KNOX_SDCARD checking this for 10079
E/Zygote  (10371): v2
I/libpersona(10371): KNOX_SDCARD not a persona
,I/SELinux (10371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=10371 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3524): Killing 7891:com.android.defcontainer/u0a5 (adj 13): bgCount ##31
,V/Avrcp   ( 5599): handleMessage, msg=207
,D/BluetoothMediaBrowser( 5599):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/TimaKeyStoreProvider(10371): TimaSignature is unavailable
,D/ActivityThread(10371): Added TimaKeyStore provider
,D/BluetoothMediaBrowser( 5599): no now playing list
,D/BluetoothMediaBrowser( 5599):  getNowPlayingId now playing id : -1
D/Avrcp   ( 5599):  checkNowPlayingList start
,D/ResourcesManager(10371): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ContactProvider(10345): getAllContactInfoList End
,I/syncContacts(10345): thread: 1368, sync time = 125
,D/FileShare-Server(10371): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10386): MountEmulatedStorage()
E/Zygote  (10386): v2
I/libpersona(10386): KNOX_SDCARD checking this for 1000
I/libpersona(10386): KNOX_SDCARD not a persona
,I/SELinux (10386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10386 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Killing 9662:com.sec.providers.settingsearch/u0a181 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10386): TimaSignature is unavailable
,D/ActivityThread(10386): Added TimaKeyStore provider
,D/ResourcesManager(10386): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(10386): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10402): MountEmulatedStorage()
E/Zygote  (10402): v2
I/libpersona(10402): KNOX_SDCARD checking this for 1000
I/libpersona(10402): KNOX_SDCARD not a persona
,I/SELinux (10402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=10402 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9749:com.google.android.gm/u0a122 (adj 13): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8782(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 870us total 22.028ms
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10402): TimaSignature is unavailable
,D/ActivityThread(10402): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 931us total 20.295ms
,D/ResourcesManager(10402): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 442us total 18.810ms
,D/ShortcutReceiver(10402):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10417): MountEmulatedStorage()
E/Zygote  (10417): v2
I/libpersona(10417): KNOX_SDCARD checking this for 10147
I/libpersona(10417): KNOX_SDCARD not a persona
,I/SELinux (10417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10417 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10417): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 4155:com.google.process.gapps/u0a14 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10417): TimaSignature is unavailable
,D/ActivityThread(10417): Added TimaKeyStore provider
,D/ResourcesManager(10417): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(10417): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 4057): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/UpdateIcingCorporaServi( 4057): UpdateCorporaTask done [took 457 ms] updated apps [took 457 ms] 
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,E/Zygote  (10441): MountEmulatedStorage()
E/Zygote  (10441): v2
I/libpersona(10441): KNOX_SDCARD checking this for 10014
I/libpersona(10441): KNOX_SDCARD not a persona
,I/SELinux (10441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=10441 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux (10441): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10441): TimaSignature is unavailable
,D/ActivityThread(10441): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10441): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GservicesProvider(10441): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient(10441): GMS http client unavailable, use old client
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/ResourcesManager(10441): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/GoogleHttpClient(10441): GMS http client unavailable, use old client
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/PkgBroadcastIntentOp( 4820): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 4820): Null package name or gms related package.  Ignoreing.
,E/Zygote  (10467): MountEmulatedStorage()
E/Zygote  (10467): v2
I/libpersona(10467): KNOX_SDCARD checking this for 10031
I/libpersona(10467): KNOX_SDCARD not a persona
,I/SELinux (10467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10467 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10467): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WearableController( 4820): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 4820): updateResources: need to parse f{com.google.android.gms}
,D/TimaKeyStoreProvider(10467): TimaSignature is unavailable
,D/ActivityThread(10467): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 23685(1519KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 2.904ms total 141.040ms
,I/ActivityManager( 3524): Killing 9860:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
,D/ResourcesManager(10467): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,I/art     ( 4667): Explicit concurrent mark sweep GC freed 34288(2MB) AllocSpace objects, 26(416KB) LOS objects, 35% free, 29MB/45MB, paused 2.506ms total 80.154ms
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  (10467): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     ( 4820): Explicit concurrent mark sweep GC freed 62664(4MB) AllocSpace objects, 32(512KB) LOS objects, 20% free, 31MB/39MB, paused 3.479ms total 76.017ms
,W/SQLiteConnectionPool( 4820): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/Finsky  (10467): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10467): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10467): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     ( 5414): Explicit concurrent mark sweep GC freed 10007(563KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 1.132ms total 26.444ms
,E/SQLiteLog(10441): (283) recovered 652 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,D/Ads     (10467): Skipping gmscore version check
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  (10467): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10467): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  (10467): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/Finsky  (10467): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Zygote  (10517): MountEmulatedStorage()
E/Zygote  (10517): v2
I/libpersona(10517): KNOX_SDCARD checking this for 10063
I/libpersona(10517): KNOX_SDCARD not a persona
,I/SELinux (10517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10517 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9876:com.sec.modem.settings/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10517): TimaSignature is unavailable
,D/ActivityThread(10517): Added TimaKeyStore provider
,D/ResourcesManager(10517): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/VRSetupWizardStub/PackageIntentReceiver(10517): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10517): ACTION_PACKAGE_ADDED
,I/ActivityManager( 3524): Killing 9891:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,I/HomeSyncInstallReceiver( 3966): This pkg do not need BT addr. Do nothing
,I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_ADDED !!   mSplitNum[0]=15, mSplitNum[1]=27, mSplitNum[2]=39 divideNum= 12 r.nextReceiver= 3 receivers.size=51
I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10533): MountEmulatedStorage()
E/Zygote  (10533): v2
I/libpersona(10533): KNOX_SDCARD checking this for 10101
I/libpersona(10533): KNOX_SDCARD not a persona
,I/SELinux (10533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=10533 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/SELinux (10533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10533): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/BroadcastQueue( 3524): Exception when sending broadcast to ComponentInfo{com.google.android.partnersetup/com.google.android.partnersetup.RlzPingBroadcastReceiver},
W/BroadcastQueue( 3524): android.os.DeadObjectException
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3524): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3524): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3524): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3524): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123),
W/BroadcastQueue( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10547): MountEmulatedStorage()
E/Zygote  (10547): v2
I/libpersona(10547): KNOX_SDCARD checking this for 10017
I/libpersona(10547): KNOX_SDCARD not a persona
,I/SELinux (10547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/TimaKeyStoreProvider(10533): TimaSignature is unavailable
,E/SELinux (10547): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityThread(10533): Added TimaKeyStore provider
,I/ActivityManager( 3524): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=10547 uid=10017 gids={50017, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 3524): Spurious death for ProcessRecord{253b0165 10547:com.google.android.partnersetup/u0a17}, curProc for 9891: null
,D/TimaKeyStoreProvider(10547): TimaSignature is unavailable
,D/ActivityThread(10547): Added TimaKeyStore provider
,D/PkgBroadcastIntentOp( 4820): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ResourcesManager(10547): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,D/ResourcesManager(10533): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 4820): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/WearableController( 4820): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/AsyncTaskServiceImpl( 4820): Submit a task: k
,D/Mms/FreeMessageStatusReceiver( 9518): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/k       ( 4820): Processing package: com.test.thalitest
,D/Mms/FreeMessageReceiverService( 9518): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 9518): onHandleIntent: ACTION_PACKAGE_ADDED
,D/GassUtils( 4820): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4820): Found info for package com.test.thalitest in db.
,D/DocsApplication(10533): Installing DEX configuration.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/DexInstaller(10533): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(10533): Provided clientMode=RELEASE, packageInfo=PackageInfo{2be76725 com.google.android.apps.docs}
,D/TAG     (10533): onCreate()
,D/CrossAppStateProvider(10533): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/Zygote  (10574): MountEmulatedStorage()
I/libpersona(10574): KNOX_SDCARD checking this for 10053
E/Zygote  (10574): v2
I/libpersona(10574): KNOX_SDCARD not a persona
,I/SELinux (10574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10574): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=10574 uid=10053 gids={50053, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 9988): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver( 9988): onReceive called  PACKAGE_ADDED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9988): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10574): TimaSignature is unavailable
,D/ActivityThread(10574): Added TimaKeyStore provider
,E/Zygote  (10590): MountEmulatedStorage()
I/libpersona(10590): KNOX_SDCARD checking this for 1000
E/Zygote  (10590): v2
I/libpersona(10590): KNOX_SDCARD not a persona
,I/SELinux (10590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9908:com.sec.tcpdumpservice/1000 (adj 15): bgCount ##31
,D/ResourcesManager(10574): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(10574): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10574): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10574): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10590): TimaSignature is unavailable
,D/ActivityThread(10590): Added TimaKeyStore provider
,E/Zygote  (10606): MountEmulatedStorage()
E/Zygote  (10606): v2
I/libpersona(10606): KNOX_SDCARD checking this for 10010
I/libpersona(10606): KNOX_SDCARD not a persona
,I/SELinux (10606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.facebook.system for broadcast com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver: pid=10606 uid=10010 gids={50010, 9997} abi=armeabi-v7a
,I/SELinux (10606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10606): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/MyFiles (10574): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ResourcesManager(10590): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/TimaKeyStoreProvider(10606): TimaSignature is unavailable
,D/ActivityThread(10606): Added TimaKeyStore provider
,I/TactileAssist( 3524): enable value -1
I/TactileAssist( 3524): internal enable value -1
I/TactileAssist( 3524): intensity value -1
I/TactileAssist( 3524): saveAppList value true
,I/TactileAssist( 3524): List of disabled apps :
,I/PCWCLIENTTRACE_LOG(10590): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10590): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10590): new DMDBOpenHelper instance
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10606): creating new AssetManager and set to /data/app/com.facebook.system-1/base.apk
,E/Zygote  (10621): MountEmulatedStorage()
I/libpersona(10621): KNOX_SDCARD checking this for 10005
E/Zygote  (10621): v2
I/libpersona(10621): KNOX_SDCARD not a persona
I/SELinux (10621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=10621 uid=10005 gids={50005, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/SELinux (10621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10621): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PCWCLIENTTRACE_PushUtil(10590): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(10590): sales region : global
I/PCWCLIENTTRACE_PushUtil(10590): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(10590): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/Zygote  (10636): MountEmulatedStorage()
E/Zygote  (10636): v2
I/libpersona(10636): KNOX_SDCARD checking this for 10059
I/libpersona(10636): KNOX_SDCARD not a persona
,I/SELinux (10636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10636 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux (10636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10636): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9923:com.sec.android.app.sbrowser/u0a156 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10621): TimaSignature is unavailable
,D/ActivityThread(10621): Added TimaKeyStore provider
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8745(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 864us total 30.360ms
,D/Finsky  (10467): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10636): TimaSignature is unavailable
,D/ActivityThread(10636): Added TimaKeyStore provider
,D/ResourcesManager(10621): creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 597us total 10.262ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 309us total 9.641ms
,E/Zygote  (10653): MountEmulatedStorage()
I/libpersona(10653): KNOX_SDCARD checking this for 10114
E/Zygote  (10653): v2
I/libpersona(10653): KNOX_SDCARD not a persona
,I/SELinux (10653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.feed.platformads.AppInstallReceiver: pid=10653 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux (10653): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10653): TimaSignature is unavailable
,D/ActivityThread(10653): Added TimaKeyStore provider
,E/installd( 2860): system dir 0 : /system/app/
E/installd( 2860): system dir 1 : /system/priv-app/
E/installd( 2860): system dir 2 : /vendor/app/
E/installd( 2860): system dir 3 : /oem/app/
,I/GAV3    ( 9960): Thread[GAThread,5,main]: No campaign data found.
,D/ResourcesManager(10636): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(10636): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 3524): Killing 9944:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##31
D/ResourcesManager(10653): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3524): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/Zygote  (10670): MountEmulatedStorage()
E/Zygote  (10670): v2
I/libpersona(10670): KNOX_SDCARD checking this for 1000
I/libpersona(10670): KNOX_SDCARD not a persona
,I/SELinux (10670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=10670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10120:com.sec.android.app.sns3/u0a37 (adj 15): bgCount ##31
,D/Compatibility(10636): onReceive() it will make start service
,D/Compatibility(10636): onHandleIntent()
,D/TimaKeyStoreProvider(10670): TimaSignature is unavailable
,D/ActivityThread(10670): Added TimaKeyStore provider
,D/Compatibility(10636): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10692, android.intent.extra.user_handle=0}]
,D/Compatibility(10636): found: 2
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Compatibility(10636): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10636): skipping ResolveInfo{1e9260fa com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10636): considering ResolveInfo{193ba6ab com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10636): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10636): enabling receiver ResolveInfo{3e704108 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility(10636): enabling receiver ResolveInfo{1dcc50a1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/UpdateIcingCorporaServi( 4057): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/ResourcesManager(10670): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/Compatibility(10636): enabling receiver ResolveInfo{2e1592c6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ResourcesManager(10653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Compatibility(10636): enabling receiver ResolveInfo{3d0c0287 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility(10636): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/ContextImpl( 9692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
,I/ActivityManager( 3524): Killing 10158:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 10120
,I/ActivityManager( 3524): Killing 10178:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): bgCount ##31
,E/JavaBinder( 3524): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3524): Exception when sending broadcast to ComponentInfo{com.sec.spp.push/com.sec.spp.push.receiver.PackageInfoChangeReceiver}
W/BroadcastQueue( 3524): android.os.TransactionTooLargeException
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3524): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3524): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3524): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3524): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:19427)
W/BroadcastQueue( 3524): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:470)
W/BroadcastQueue( 3524): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/BroadcastQueue( 3524): 	at android.os.Binder.execTransact(Binder.java:446)
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/AppStateLoggerExceptionHandler(10653): Installed uncaught exception handler for app state logging
,D/AppStateLogger(10653): Attempting to open app state logging file
,E/Zygote  (10698): MountEmulatedStorage()
E/Zygote  (10698): v2
I/libpersona(10698): KNOX_SDCARD checking this for 10039
I/libpersona(10698): KNOX_SDCARD not a persona
,I/SELinux (10698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=10698 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10698): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/AppStateLogger(10653): Successfully opened app state logging file: /data/data/com.facebook.katana/app_state_logs/c018186c-4b61-ccc4-5f03-e956ffde915a.txt
D/ACRA    (10653): ACRA is enabled for com.facebook.katana, intializing...
,D/ResourcesManager( 4057): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,V/fb-UnpackingSoSource(10653): locked dso store /data/data/com.facebook.katana/lib-main
I/fb-UnpackingSoSource(10653): dso store is up-to-date: /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource(10653): releasing dso store lock for /data/data/com.facebook.katana/lib-main
,V/fb-UnpackingSoSource(10653): locked dso store /data/data/com.facebook.katana/lib-assets
I/fb-UnpackingSoSource(10653): dso store is up-to-date: /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource(10653): releasing dso store lock for /data/data/com.facebook.katana/lib-assets
,V/fb-UnpackingSoSource(10653): locked dso store /data/data/com.facebook.katana/lib-xzs
,I/fb-UnpackingSoSource(10653): dso store is up-to-date: /data/data/com.facebook.katana/lib-xzs
V/fb-UnpackingSoSource(10653): releasing dso store lock for /data/data/com.facebook.katana/lib-xzs
,I/Icing   ( 4820): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/art     (10653): Thread[1,tid=10653,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
,D/TimaKeyStoreProvider(10698): TimaSignature is unavailable
V/appstatelogger(10653): Registered App State Logger stream with Breakpad
,V/MemoryEnlargementHack(10653): largeHeap already enabled in manifest
V/DexLibLoader(10653): DLL.loadAll betaBuild:false flags:0x00000004
D/ActivityThread(10698): Added TimaKeyStore provider
,E/Zygote  (10719): MountEmulatedStorage()
E/Zygote  (10719): v2
I/libpersona(10719): KNOX_SDCARD checking this for 10102
I/libpersona(10719): KNOX_SDCARD not a persona
,V/dalvik-internals(10653): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
I/SELinux (10719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
V/dalvik-internals(10653): hooked signal using trap ()
V/dalvik-internals(10653): hooked sysv_signal using trap ()
V/dalvik-internals(10653): hooked bsd_signal using trap ()
V/dalvik-internals(10653): hooked sigaction using jump ()
V/dalvik-internals(10653): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals(10653): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals(10653): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader(10653): patched ART 5.0.x miranda bug
,V/DexLibLoader(10653): opening dex store /data/data/com.facebook.katana/dex
,V/DexLibLoader(10653): Secondary program dex metadata: [.root_relative]
V/DexLibLoader(10653): Secondary program dex metadata: [.locators]
V/DexLibLoader(10653): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
I/SELinux (10719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/DexLibLoader(10653): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader(10653): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
,I/ActivityManager( 3524): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=10719 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,E/SELinux (10719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    (10533): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ResourcesManager(10698): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/TimaKeyStoreProvider(10719): TimaSignature is unavailable
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/ActivityThread(10719): Added TimaKeyStore provider
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/DexLibLoader(10653): read status:9 check:faceb007faceb00e
,V/DexLibLoader(10653): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader(10653): verified deps file
I/DexLibLoader(10653): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader(10653): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader(10653): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10653): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader(10653): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader(10653): Setup multi dex took 0 ms.
V/DexLibLoader(10653): optimization needed: no
,D/MemoryReductionHack(10653): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager(10719): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager(10719): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SPPClientService(10698): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService(10698): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/SPPClientService(10698): PushLog.txt file is not deleted.
D/SPPClientService(10698): PushLog.txt file is not deleted.
D/SPPClientService(10698): ============PushLog. stop!
,E/Zygote  (10740): MountEmulatedStorage()
E/Zygote  (10740): v2
I/libpersona(10740): KNOX_SDCARD checking this for 10042
I/libpersona(10740): KNOX_SDCARD not a persona
,I/SELinux (10740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=10740 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,E/SELinux (10740): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 10202:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): bgCount ##31
,E/[CarMode](10719): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager(10719): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager(10719): mContext is not null
,I/VlingoAndroidCore(10719): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,I/GMPM    (10653): App measurement is starting up
,D/TimaKeyStoreProvider(10740): TimaSignature is unavailable
,D/ActivityThread(10740): Added TimaKeyStore provider
,E/GMPM    (10653): getGoogleAppId failed with status: 10
,E/GMPM    (10653): Uploading is not possible. App measurement disabled
,D/ResourcesManager(10740): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,D/ResourcesManager( 4820): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,W/ResourcesManager(10740): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10740): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/Icing   ( 4820): Loaded CLD2 Version V2.0 - 20141016
,E/Zygote  (10761): MountEmulatedStorage()
,E/Zygote  (10761): v2
I/libpersona(10761): KNOX_SDCARD checking this for 10034
I/libpersona(10761): KNOX_SDCARD not a persona
,I/SELinux (10761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=10761 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux (10761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10761): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/UpdateIcingCorporaServi( 4057): UpdateCorporaTask done [took 354 ms] updated apps [took 354 ms] 
,I/Icing   ( 4820): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,D/TimaKeyStoreProvider(10761): TimaSignature is unavailable
,D/ActivityThread(10761): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10761): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/StaticBindingVerifier(10653): Verify
,I/SL_DEBUG(10740): isLoggable:: isProductShip = 1
,I/SL_DEBUG(10740): isLoggable:: SL_DEBUG_EXIST = false
,I/System.out(10761): Inside WakeupProvider
,W/GAV2    (10533): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,E/DatabaseUtils(10761): Writing exception to parcel
E/DatabaseUtils(10761): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(10761): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(10761): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(10761): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(10761): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(10761): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(10761): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(10761): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(10761): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(10761): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(10761): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager( 3524): Killing 10234:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##31
,W/System.err(10719): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(10719): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10719): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err(10719): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10719): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10719): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10719): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10719): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10719): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10719): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
,W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
,W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
,W/System.err(10719): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err(10719): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
,W/System.err(10719): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err(10719): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err(10719): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err(10719): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10719): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
I/VlingoApplication(10761): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
W/System.err(10719): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10719): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10719): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10719): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10719): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10719): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10719): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10719): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10719): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils(10761): Writing exception to parcel
E/DatabaseUtils(10761): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils(10761): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils(10761): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils(10761): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils(10761): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils(10761): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils(10761): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils(10761): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils(10761): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils(10761): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils(10761): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err(10719): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err(10719): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err(10719): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
,W/System.err(10719): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err(10719): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err(10719): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err(10719): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err(10719): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err(10719): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err(10719): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err(10719): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err(10719): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err(10719): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err(10719): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err(10719): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err(10719): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err(10719): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err(10719): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err(10719): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10719): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10719): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err(10719): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err(10719): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err(10719): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err(10719): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode](10719): [DLApplication]-Init Called!:false
,W/[CarMode](10719): [CommonUtil]-=========================================
W/[CarMode](10719): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode](10719): [CommonUtil]-=========================================
E/[CarMode](10719): [DLApplication]-Init Started!:true
,I/[CarModeFW](10719): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW](10719): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW](10719): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW](10719): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW](10719): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW](10719): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW](10719): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW](10719): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW](10719): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW](10719): ### android.os.Looper::loop(145)
I/[CarModeFW](10719): ### android.app.ActivityThread::main(5944)
I/[CarModeFW](10719): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW](10719): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW](10719): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoAndroidCore(10761): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
,I/MessageDataHandler(10719): initialize
W/LightSharedPreferencesImpl(10653): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl(10653): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10653): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl(10653): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl(10653): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl(10653): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl(10653): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl(10653): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl(10653): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl(10653): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl(10653): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl(10653): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl(10653): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl(10653): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl(10653): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl(10653): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl(10653): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl(10653): 	... 10 more
,D/[CarModeFW](10719): CDH-initiazlieCaches : before sync
D/[CarModeFW](10719): CDH-initiazlieCaches : after sync
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10740): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/[CarModeFW](10719): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW](10719): CDH-ContactDataHandler initiazlieCaches time : 30
D/[CarModeFW](10719): CDH-initiazlieCaches : end sync
,D/[CarModeFW](10719): DrivingManager-initialize...
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SensorService( 3524): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
W/ContextImpl(10740): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/SensorService( 3524): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3524): Skipped sensor MAX86902 because it requires permission 
D/VlingoApplication(10761): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
I/SensorService( 3524): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3524): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,D/VlingoApplication(10761): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow(10761): initQueue()
,V/Transcoder(10740): Transcoder(0xaf0eb560)::constructor
V/Transcoder(10740): addObitRecipient
V/TMI-JNI (10740): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,I/Icing   ( 4820): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/Icing   ( 4820): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10812): MountEmulatedStorage()
E/Zygote  (10812): v2
I/libpersona(10812): KNOX_SDCARD checking this for 10045
I/libpersona(10812): KNOX_SDCARD not a persona
,I/SELinux (10812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=10812 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10812): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10812): TimaSignature is unavailable
,D/ActivityThread(10812): Added TimaKeyStore provider
,I/ActivityManager( 3524): Killing 10249:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,I/MediaPlayer(10719): Need to enable context aware info
V/MediaPlayer-JNI(10719): native_setup
V/MediaPlayer(10719): constructor
,V/MediaPlayer(10719): setListener
,V/AlarmManager( 3524): waitForAlarm result :4
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 23078(1471KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 1.434ms total 114.786ms
,D/WifiService( 3524): New client listening to asynchronous messages
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/[CarModeFW](10719): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW](10719): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode](10719): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457706952753
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457706952754
,D/ResourcesManager(10812): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457706952754
,D/[CarMode](10719): [DLServiceManager]-updateLocationList
D/[CarMode](10719): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457706952755
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457706952756
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457706952757
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457706952758
,D/[CarModeFW](10719): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,D/TP/SmsProvider( 3982): query,matched:2, calling pid = 10719
,D/TP/SmsProvider( 3982): match 2:Elapsed time : 1.223 ms
,F/DLApplication(10719): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
,I/[CarMode](10719): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW](10719): ContactDataHandler-getFavoriteContactList : cur len = 0
,E/[CarMode](10719): [DLApplication]-Init End!:true
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/TP/SmsProvider( 3982): query,matched:2, calling pid = 10719
,D/MessageDataHandler(10719):  getInboxList smsCursor : 25
,D/TP/SmsProvider( 3982): match 2:Elapsed time : 3.558 ms
,D/[CarModeFW](10719): CalllogDataHandler-getCalllogList : cur len = 0
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 35
D/[CarModeFW](10719): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarMode](10719): [TAG]-phone sound mode is: 0
V/[CarMode](10719): [DLApplication]-savePreviousGpsState
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 35
,D/TP/MmsProvider( 3982): Query uri=content://mms/inbox, match=2, calling pid = 10719
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 42
,D/[CarModeFW](10719): LocationDataHandler-No schedules found.
,D/TP/MmsProvider( 3982): Query uri=content://mms, match=0, calling pid = 10719
D/MessageDataHandler(10719):  getInboxList mmsCursor : 19
,D/[CarModeFW](10719): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/SA      (10812): [SSP] onCreated
,D/[CarModeFW](10719): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 48
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,E/Zygote  (10841): MountEmulatedStorage()
E/Zygote  (10841): v2
I/libpersona(10841): KNOX_SDCARD checking this for 10003
I/libpersona(10841): KNOX_SDCARD not a persona
,I/SELinux (10841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10841 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
E/SELinux (10841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/[CarMode](10719): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/MessageDataHandler(10719):  getInboxList mms,sms cursor join : 24
,I/SA      (10812): [TPM] There is no property file
,D/TP/MmsSmsProvider( 3982): query,matched:0, calling pid = 10719
V/TP/MmsSmsProvider( 3982): getSimpleConversations entered.
,I/SA      (10812): [SCU] isHaveSA() - false
,D/TP/MmsSmsProvider( 3982): match 0:Elapsed time : 2.006 ms
,I/SA      (10812): [TPM] getModelProperty : null
I/SA      (10812): [TPM] getCSCProperty : null
I/MessageDataHandler(10719): getUnreadMessageCount :0
D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 73
,I/SA      (10812): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,D/TP/MmsSmsProvider( 3982): query,matched:13, calling pid = 10719
,D/TP/MmsSmsProvider( 3982): match 13:Elapsed time : 1.328 ms
,I/SA      (10812): [DM] init START
,I/SA      (10812): [DM] This device is not a Vodafone
,V/xAnalytics(10653): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics(10653): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics(10653): JNI_OnLoad XAnalyticsNative complete
,V/xAnalytics(10653): tigon: 0x0 - xanalytics: 0xffffffff9400e340
,I/SA      (10812): checkReactivationActive for LOLLIPOP
D/MessageDataHandler(10719):  getInboxList address cursor : 13
I/SA      (10812): checkReactivationActive for reactiveActive
I/SA      (10812): setSupportRL : true
,D/TimaKeyStoreProvider(10841): TimaSignature is unavailable
,I/SA      (10812): [SCU] isHaveSA() - false
I/SA      (10812): support phone number id : false
I/SA      (10812): [DM] init END
,I/SA      (10812): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
D/ActivityThread(10841): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3982): query,matched:0, calling pid = 10719
V/TP/MmsSmsProvider( 3982): getSimpleConversations entered.
I/SA      (10812): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10692 extra.user_handle.:0 ]
,V/xAnalytics(10653): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
V/xAnalytics(10653): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     (10653): Attempt to remove local handle scope entry from IRT, ignoring
D/TP/MmsSmsProvider( 3982): match 0:Elapsed time : 1.409 ms
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/[CarMode](10719): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode](10719): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,E/Zygote  (10864): MountEmulatedStorage()
E/Zygote  (10864): v2
I/libpersona(10864): KNOX_SDCARD checking this for 10046
I/libpersona(10864): KNOX_SDCARD not a persona
,I/SELinux (10864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=10864 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux (10864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10864): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarMode](10719): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
,E/[CarMode](10719): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/MessageDataHandler(10719):  getInboxList thread cursor : 34
,I/UpdateManagerReceiver(10719): Intent : android.intent.action.PACKAGE_ADDEDFri Mar 11 15:35:52 GMT+01:00 2016
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/DialogFlow(10719): initQueue()
,D/TimaKeyStoreProvider(10864): TimaSignature is unavailable
I/System.out(10761): INFO:Resource not found:/Common.properties Using default values
,D/ActivityThread(10864): Added TimaKeyStore provider
,E/Zygote  (10882): MountEmulatedStorage()
E/Zygote  (10882): v2
I/libpersona(10882): KNOX_SDCARD checking this for 1000
I/libpersona(10882): KNOX_SDCARD not a persona
,I/SELinux (10882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=10882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 9615:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
D/ResourcesManager(10841): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,I/ActivityManager( 3524): Killing 10300:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##32
,I/ActivityManager( 3524): Killing 9253:com.samsung.android.snote/u0a160 (adj 15): bgCount ##33
,I/ActivityManager( 3524): Killing 10264:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): bgCount ##34
,D/MessageDataHandler(10719):  thread, addr result: 42
,I/[CarModeFW](10719): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 167
,I/[CarModeFW](10719): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
,D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 170
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10882): TimaSignature is unavailable
,D/ActivityThread(10882): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider(10841): PlaceProvider onCreate()
,D/ResourcesManager(10864): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(10864): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10864): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(10864): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/UserAnalysis.SecureDbManager(10841): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(10841): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10841): Create SecureDbHelper
,D/ResourcesManager(10882): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/IntelligenceServiceApplication(10841): onCreate()
,W/ContextImpl(10882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10882): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Minikin (10864): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,E/FilterInstaller(10882): installFilters
,E/FilterInstaller(10882): There is no requred permission
,I/RelayReceiver_PinBoard(10864): onReceive... android.intent.action.PACKAGE_ADDED
,E/Zygote  (10899): MountEmulatedStorage()
E/Zygote  (10899): v2
I/libpersona(10899): KNOX_SDCARD checking this for 10121
I/libpersona(10899): KNOX_SDCARD not a persona
I/SELinux (10899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=10899 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/RelayService_PinBoard(10864): RelayService Started!! : android.intent.action.PACKAGE_ADDED
I/art     ( 2880): Explicit concurrent mark sweep GC freed 8767(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 882us total 21.355ms
,I/ActivityManager( 3524): Killing 9639:com.android.calendar/u0a164 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10899): TimaSignature is unavailable
,D/ActivityThread(10899): Added TimaKeyStore provider
,D/[CarModeFW](10719): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW](10719): MyPlaceProvider-=============
,D/[CarModeFW](10719): MyPlaceProvider-=============
D/[CarModeFW](10719): MyPlaceProvider-=============
D/[CarModeFW](10719): MyPlaceProvider-=============
D/[CarModeFW](10719): MyPlaceProvider-=============
D/[CarModeFW](10719): MyPlaceProvider-=============
D/[CarModeFW](10719): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW](10719): MyPlaceProvider-==============
D/[CarModeFW](10719): MyPlaceProvider-==============
D/[CarModeFW](10719): MyPlaceProvider-==============
D/[CarModeFW](10719): MyPlaceProvider-==============
D/[CarModeFW](10719): MyPlaceProvider-==============
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 257us total 10.638ms
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 247us total 8.026ms
,E/Zygote  (10916): MountEmulatedStorage()
E/Zygote  (10916): v2
I/libpersona(10916): KNOX_SDCARD checking this for 10110
I/libpersona(10916): KNOX_SDCARD not a persona
,I/SELinux (10916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10916): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=10916 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppStateLogger(10653): Successfully dumped app state to log file
,D/[CarModeFW](10719): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457706953084 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
,E/[CarModeFW](10719): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList(10719): loadLocationDestinationList is null
D/[CarModeFW](10719): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 329
I/ActivityManager( 3524): Killing 9814:com.google.android.talk/u0a125 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10916): TimaSignature is unavailable
,D/ActivityThread(10916): Added TimaKeyStore provider
,D/ResourcesManager(10899): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/ResourcesManager(10916): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,D/PackageIntentReceiver(10899): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver(10899): Not GearManger package! 
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10931): MountEmulatedStorage()
E/Zygote  (10931): v2
I/libpersona(10931): KNOX_SDCARD checking this for 1000
I/libpersona(10931): KNOX_SDCARD not a persona
,I/SELinux (10931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=10931 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (10931): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 9178:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/9178/oom_score_adj; errno=22
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10931): TimaSignature is unavailable
,D/ActivityThread(10931): Added TimaKeyStore provider
,D/ResourcesManager(10931): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10946): MountEmulatedStorage()
I/libpersona(10946): KNOX_SDCARD checking this for 1000
E/Zygote  (10946): v2
I/libpersona(10946): KNOX_SDCARD not a persona
,I/SELinux (10946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3524): Killing 10371:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10946): TimaSignature is unavailable
,D/ActivityThread(10946): Added TimaKeyStore provider
,D/ResourcesManager(10946): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/ActivityManager( 3524): Killing 10386:com.sec.knox.bridge/1000 (adj 15): bgCount ##31
,D/AcmsPackageEventListener(10946): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl(10946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService(10946): Enter Oncreate
D/AcmsServiceMonitor(10946): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10946): creating AcmsCore
D/AcmsCore(10946): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10946): AcmsCore
,V/fb-UnpackingSoSource(10916): locked dso store /data/data/com.facebook.appmanager/lib-main
I/fb-UnpackingSoSource(10916): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource(10916): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
,V/fb-UnpackingSoSource(10916): locked dso store /data/data/com.facebook.appmanager/lib-assets
D/AcmsCore(10946): init
D/AcmsCore(10946): Looper handler is not null
D/AcmsCore(10946): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10946): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
I/fb-UnpackingSoSource(10916): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource(10916): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
D/AcmsServiceMonitor(10946): Incrementing - Counter value: 1
D/AcmsCore(10946): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10946): onStartCommand
D/AcmsService(10946): Action: android.intent.action.PACKAGE_ADDED
D/AcmsCertificateMngr(10946): AcmsCertificateMngr
D/AcmsServiceMonitor(10946): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10946): Incrementing - Counter value: 2
D/AcmsService(10946): Incremented Counter Value : onStartCommand
V/fb-UnpackingSoSource(10916): locked dso store /data/data/com.facebook.appmanager/lib-xzs
D/AcmsRevocationMngr(10946): AcmsRevocationMngr
I/fb-UnpackingSoSource(10916): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource(10916): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ActivityThread(10946): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ACRA    (10916): ACRA is enabled for com.facebook.appmanager, intializing...
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{5cce831 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
V/DexLibLoader(10916): DLL.loadAll betaBuild:true flags:0x00000001
,V/dalvik-internals(10916): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals(10916): hooked signal using trap ()
V/dalvik-internals(10916): hooked sysv_signal using trap ()
V/dalvik-internals(10916): hooked bsd_signal using trap ()
,V/dalvik-internals(10916): hooked sigaction using jump ()
V/DexLibLoader(10916): opening dex store /data/data/com.facebook.appmanager/dex
,V/DexLibLoader(10916): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
V/DexLibLoader(10916): read status:9 check:faceb007faceb00e
,V/DexLibLoader(10916): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader(10916): verified deps file
I/DexLibLoader(10916): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader(10916): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader(10916): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader(10916): Setup multi dex took 1 ms.
V/DexLibLoader(10916): optimization needed: no
,D/AcmsService(10946): Inside handle Intent
D/AcmsService(10946): App added - package name: com.test.thalitest
D/AcmsCore(10946): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10946): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10946): Incrementing - Counter value: 3
D/AcmsCore(10946): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10946): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10946): Decrementing - Counter value: 2
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10966): MountEmulatedStorage()
E/Zygote  (10966): v2
I/libpersona(10966): KNOX_SDCARD checking this for 10160
I/libpersona(10966): KNOX_SDCARD not a persona
,I/SELinux (10966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=10966 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/GMPM    (10916): App measurement is starting up
,W/cn      (10916): Verify
,D/TimaKeyStoreProvider(10966): TimaSignature is unavailable
,D/ActivityThread(10966): Added TimaKeyStore provider
,E/GMPM    (10916): getGoogleAppId failed with status: 10
,E/GMPM    (10916): Uploading is not possible. App measurement disabled
,D/ResourcesManager(10966): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(10966): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10966): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10989): MountEmulatedStorage()
E/Zygote  (10989): v2
I/libpersona(10989): KNOX_SDCARD checking this for 10013
I/libpersona(10989): KNOX_SDCARD not a persona
,I/SELinux (10989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10989): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3524): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=10989 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/appmanager(:<default>):LightSharedPreferencesImpl(10916): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl(10916): 	... 10 more
,W/appmanager(:<default>):b(10916): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/TimaKeyStoreProvider(10989): TimaSignature is unavailable
,D/ActivityThread(10989): Added TimaKeyStore provider
,V/io.jxcore.node.JXcoreExtension( 9677): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 9677): INFO testUtils BLE multiple advertisement supported
I/jxcore-log( 9677): 
,W/appmanager(:<default>):b(10916): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/jxcore-log( 9677): My device name is: samsung-SM-N910C
I/jxcore-log( 9677): 
,D/ResourcesManager(10989): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,V/Common  (10966): getScreenSize 1440 2560
,I/Icing   ( 4820): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,I/JAM     (10966): Load The ApaService JNI
,I/JAM     (10966): version: ProfessionalAudio_v1.0.b5
I/JAM     (10966): Try v1.0.b3 ...
D/Spen    (10966): SpenSdk version level = 55
D/Spen    (10966): SpenSdk jar version = 3.0.243
,D/Spen    (10966): SpenSdk apk version = 3.0.235
D/Spen    (10966): Server UPDATE Check
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/linker  (10966): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SPenError(10966): JNI_OnLoad
,D/JNI_Bitmap(10966): Init .. Done
D/SPenSpiDecoder(10966): JNI_OnLoad .. Done
D/SPenError(10966): JNI_OnLoad Success
,D/PluginManager(10966): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
,D/PluginManager(10966): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(10966): JNI_OnLoad
,D/Init_SPenSdk_Jni(10966): AndroidSDK: 21
D/Init_SPenSdk_Jni(10966): JNI_OnLoad .. Done
,E/Zygote  (11018): MountEmulatedStorage()
E/Zygote  (11018): v2
I/libpersona(11018): KNOX_SDCARD checking this for 10160
D/Model_ObjectBase_Jni(10966): JNI_OnLoad .. Done
I/libpersona(11018): KNOX_SDCARD not a persona
,D/Model_ObjectStroke_Jni(10966): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(10966): JNI_OnLoad .. Done
,I/SELinux (11018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/Model_ObjectText_Jni(10966): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(10966): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(10966): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni(10966): check build type eng[0]
,I/ActivityManager( 3524): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=11018 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/SELinux (11018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/Model_NoteDoc_Jni(10966): JNI_OnLoad .. Done
,E/SELinux (11018): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Model_NoteFile_Jni(10966): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(10966): JNI_OnLoad .. Done
D/Model   (10966): OnLoad class Done
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/TimaKeyStoreProvider(11018): TimaSignature is unavailable
,D/ActivityThread(11018): Added TimaKeyStore provider
,D/spe_log (10966): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(10966): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(10966): Canvas JNI_OnLoad enter!!
,D/SPen_Library(10966): Canvas JNI_OnLoad Success
D/SPen_Library(10966): TextView JNI_OnLoad enter!!
,D/SPen_Library(10966): TextView JNI_OnLoad Success
D/SPen_Library(10966): Text JNI_OnLoad enter!!
D/SPen_Library(10966): Text JNI_OnLoad Success
D/SPen_Library(10966): FontManager JNI_OnLoad enter!!
D/SPen_Library(10966): FontManager JNI_OnLoad Success
D/SPen_Library(10966): CapturePage JNI_OnLoad enter!!
D/SPen_Library(10966): CapturePage JNI_OnLoad Success
D/SPen_Library(10966): Multi JNI_OnLoad enter!!
D/SPen_Library(10966): Multi JNI_OnLoad Success
D/SPen_Library(10966): Draw Engine JNI_OnLoad Success
,D/SPen_Library(10966): Brush JNI_OnLoad enter!!
,W/appmanager(:<default>):QuickExperimentControllerImpl(10916): Exposure of experiment com.facebook.http.g.c@15ac3aed occurred when no user was logged in
,D/ResourcesManager(11018): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(11018): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(11018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11018): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/SPen_Library(10966): Brush JNI_OnLoad Success
,I/Icing   ( 4820): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,I/art     (10916): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
I/art     (10916): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,D/SPen_Library(10966): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(10966): ChineseBrush JNI_OnLoad Success
,I/System.out(10916): Thread-1516(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10916): Thread-1516(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10916): Thread-1516(ApacheHTTPLog):isShipBuild true
I/System.out(10916): Thread-1516(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SPen_Library(10966): InkPen JNI_OnLoad enter!!
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
D/SPen_Library(10966): InkPen JNI_OnLoad Success
,D/SPen_Library(10966): Marker JNI_OnLoad enter!!
,D/SPen_Library(10966): Marker JNI_OnLoad Success
,D/SPen_Library(10966): Pencil JNI_OnLoad enter!!
,D/SPen_Library(10966): Pencil JNI_OnLoad Success
,D/SPen_Library(10966): NativePen JNI_OnLoad enter!!
,D/SPen_Library(10966): NativePen JNI_OnLoad Success
,D/SPen_Library(10966): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(10966): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(10966): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(10966): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(10966): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(10966): MagicPen JNI_OnLoad Success
,D/SPen_Library(10966): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(10966): ObliquePen JNI_OnLoad Success
,D/SPen_Library(10966): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(10966): FountainPen JNI_OnLoad Success
D/Spen    (10966): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(10966): SPenSdk_init2
D/Init_SPenSdk(10966): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(10966): Total S Pen SDK Directory Size = 0
D/Spen    (10966): initialize complete
,W/linker  (10966): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/SNoteProvider(11018): onCreate enableSnoteSync = true
,D/SNoteProvider(11018): ===query=== 
,D/ResourcesManager(10966): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,V/Common  (11018): getScreenSize 1440 2560
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (11046): MountEmulatedStorage()
E/Zygote  (11046): v2
I/libpersona(11046): KNOX_SDCARD checking this for 10183
I/libpersona(11046): KNOX_SDCARD not a persona
,I/SELinux (11046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11046): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=11046 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10441:com.google.process.gapps/u0a14 (adj 15): bgCount ##31
,I/ActivityManager( 3524): Killing 10402:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##32
,E/lowmemorykiller( 2827): Error writing /proc/10441/oom_score_adj; errno=22
E/lowmemorykiller( 2827): Error writing /proc/10402/oom_score_adj; errno=22
,D/TimaKeyStoreProvider(11046): TimaSignature is unavailable
D/SNoteProvider(11018): ===query=== 
,D/ActivityThread(11046): Added TimaKeyStore provider
,D/ResourcesManager(11046): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog(11046): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11061): MountEmulatedStorage()
I/libpersona(11061): KNOX_SDCARD checking this for 10190
E/Zygote  (11061): v2
I/libpersona(11061): KNOX_SDCARD not a persona
,I/SELinux (11061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=11061 uid=10190 gids={50190, 9997} abi=armeabi-v7a
E/SELinux (11061): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 10517:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(11061): TimaSignature is unavailable
,D/ActivityThread(11061): Added TimaKeyStore provider
,D/ResourcesManager(11061): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11061): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11061): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(11061): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11061): Widget is not attached.
,I/splitIntent( 3524): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/ActivityManager( 3524): Killing 10345:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11079): MountEmulatedStorage()
I/libpersona(11079): KNOX_SDCARD checking this for 10022
E/Zygote  (11079): v2
I/libpersona(11079): KNOX_SDCARD not a persona
,I/SELinux (11079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11079 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/AcmsKeyStoreHelper(10946):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper(10946): Key Store exist
I/AcmsKeyStoreHelper(10946): Hence loading the keystore file
,D/TimaKeyStoreProvider(11079): TimaSignature is unavailable
,D/ActivityThread(11079): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11079): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/AcmsKeyStoreHelper(10946):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(10946): getKeyStoreForApplication success 
D/AcmsCore(10946): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(10946): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10946): Decrementing - Counter value: 1
D/AcmsCore(10946): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(10946): This is NOT a valid MirrorLink app
D/AcmsCore(10946): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(10946): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10946): Decrementing - Counter value: 0
D/AcmsServiceMonitor(10946): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor(10946): getSvcCounter - Counter value: 0
D/AcmsService(10946): Enter onDestroy
I/AcmsService(10946): cleanUp(): inside service clean up
D/AcmsCore(10946): AcmsCore: inside DeInit
D/AcmsCore(10946): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(10946): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(10946): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(10946): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(10946): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(10946): getSvcCounter - Counter value: 0
D/AcmsService(10946): killing acms process
I/Process (10946): Sending signal. PID: 10946 SIG: 9
I/LocationWidgetApplication(11079): onCreate() : start
,D/LocationWidgetApplication(11079): countryCode = POLAND
,D/LocationManagerService( 3524): getProviders()=[]
D/LocationManagerService( 3524): getProviders()=[passive]
D/LocationManagerService( 3524): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(11079): mPrivacy is null
,W/ContextImpl(11079): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/PackageManager( 3524): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ContextFramework:PrivacyManager(11079): Service for PrivacyManager is connected
I/SettingSearch/SearchIntentReceiver( 8657): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 8657): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/LWLocationManager(11079): Privacy service : STATUS_PLACE
D/LWLocationManager(11079): updateLocationStatus()
,I/LocationWidgetFuctionData(11079): readDB
,I/LocationWidgetFuctionData(11079): selectedAppSize: 3
I/LocationWidgetFuctionData(11079): configPlaceList aroundMeItems
,I/SettingSearch/SearchIntentReceiver( 8657): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 8657): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 8657): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11100): MountEmulatedStorage()
I/libpersona(11100): KNOX_SDCARD checking this for 10181
E/Zygote  (11100): v2
I/libpersona(11100): KNOX_SDCARD not a persona
,I/SELinux (11100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11100): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=11100 uid=10181 gids={50181, 9997} abi=armeabi-v7a
,I/ActivityManager( 3524): Process ACMS.Process (pid 10946)(adj 0) has died(85,1125)
,I/ActivityManager( 3524): Killing 9518:com.android.mms/u0a52 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/9518/oom_score_adj; errno=22
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11114): MountEmulatedStorage()
I/libpersona(11114): KNOX_SDCARD checking this for 10122
E/Zygote  (11114): v2
I/libpersona(11114): KNOX_SDCARD not a persona
,I/SELinux (11114): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(11100): TimaSignature is unavailable
,I/ActivityManager( 3524): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=11114 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11114): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ActivityThread(11100): Added TimaKeyStore provider
,E/SELinux (11114): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 10547:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,I/LocationWidgetFuctionData(11079): selectedAppSize: 3
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 629us total 10.414ms
,I/LocationWidgetFuctionData(11079): selectedAppSize: 3
,I/LocationWidgetFuctionData(11079): selectedAppSize: 3
,I/LocationWidgetFuctionData(11079): selectedAppSize: 3
,D/ResourcesManager(11100): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 718us total 10.258ms
,D/TimaKeyStoreProvider(11114): TimaSignature is unavailable
,D/ActivityThread(11114): Added TimaKeyStore provider
,D/CountryDetector( 3524): No listener is left
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 390us total 10.441ms
,D/ResourcesManager(11114): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ActivityThread(10916): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/LWLocationManager(11079): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(11079): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(11079): setShouldUpdateLocationId
D/LWLocationManager(11079): setShouldUpdateLocationId return false
D/LWLocationManager(11079): setShouldUpdateLocationId
D/LWLocationManager(11079): setShouldUpdateLocationId return false
D/LWLocationManager(11079): setShouldUpdateLocationId
D/LWLocationManager(11079): setShouldUpdateLocationId return false
D/LWLocationManager(11079): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,I/SettingSearch/SettingsSearchManager( 8657): Infomation -> numtitleinfo : 0 numSearchinfo : 367
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread(11114): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   (11114): getAccountsCursor
,I/SettingSearch/SettingsSearchManager( 8657):  Infomation -> getItem size : 367
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3524): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 3524): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    (11114): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   (11114): Observing account changes for notifications
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11150): MountEmulatedStorage()
E/Zygote  (11150): v2
I/libpersona(11150): KNOX_SDCARD checking this for 10014
I/libpersona(11150): KNOX_SDCARD not a persona
,I/SELinux (11150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11150): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=11150 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ResourcesManager( 8657): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 8657): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,W/ResourcesManager( 8657): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8657): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8657): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8657): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(11150): TimaSignature is unavailable
,D/ActivityThread(11150): Added TimaKeyStore provider
,D/ResourcesManager(11150): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 8657): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,I/System.out(10916): P[5]_NetworkDispatch1 calls detatch()
,I/GservicesProvider(11150): Gservices pushing to system: true; secure/global: true
I/ActivityManager( 3524): Killing 9988:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
,I/GoogleHttpClient(11150): GMS http client unavailable, use old client
,D/ResourcesManager(11150): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,I/GoogleHttpClient(11150): GMS http client unavailable, use old client
,W/ActivityManager( 3524): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 3524): Killing 10574:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,E/Gmail   (11114): Error finding the version of the Email provider.....
E/Gmail   (11114): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (11114): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (11114): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (11114): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (11114): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (11114): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (11114): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (11114): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(11114): We do not support migrating this version of the Email provider.
,I/Gmail   (11114): getAccountsCursor
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog(11114): (283) recovered 77 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager( 3524): Killing 10590:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 18512(1201KB) AllocSpace objects, 2(32KB) LOS objects, 23% free, 53MB/69MB, paused 8.034ms total 105.039ms
I/art     ( 3524): WaitForGcToComplete blocked for 104.980ms for cause Explicit
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{10b4a840 u0 ReceiverList{70c7c3 10916 com.facebook.appmanager/10110/u0 remote:16417772}}
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{10b4a840 u0 ReceiverList{70c7c3 10916 com.facebook.appmanager/10110/u0 remote:16417772}}
,I/Gmail   (11114): notifyAccountChanged
,I/Gmail   (11114): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (11114): getAccountsCursor
,I/Gmail   (11114): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (11114): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (11114): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 4820): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{8909117 u0 ReceiverList{e500196 10916 com.facebook.appmanager/10110/u0 remote:2ce2f8b1}}
,I/Gmail   (11114): getAccountsCursor
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 3773(217KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 1.874ms total 82.985ms
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11198): MountEmulatedStorage()
I/libpersona(11198): KNOX_SDCARD checking this for 10135
E/Zygote  (11198): v2
I/libpersona(11198): KNOX_SDCARD not a persona
,I/SELinux (11198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11198): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=11198 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11198): TimaSignature is unavailable
,D/ActivityThread(11198): Added TimaKeyStore provider
,D/ResourcesManager(11198): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(11198): Database version: 104
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(11198): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(11198): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11198): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (11198): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11198): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (11198): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@125235c8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11198): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(11198): GMSCore installation verified
,I/ConfigStore(11198): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10916): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10916): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,I/SettingSearch/SearchIntentReceiver( 8657): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 8657): LOCALE_CHANGED call search setting db finish!!
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11198): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/appmanager(:<default>):QuickExperimentControllerImpl(10916): Exposure of experiment com.facebook.imagepipeline.m.d@181a758d occurred when no user was logged in
,W/appmanager(:<default>):aa(10916): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,W/appmanager(:<default>):aa(10916): Requested time interval of 300000 ms should be increased to at least 900000 ms for a
,V/analytics4a(10916): JNI_OnLoad called
V/analytics4a(10916): JNI_OnLoad complete
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11198): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11198): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3524): getStreamVolume 3 index 0
,I/MediaRouter(11198): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/art     (10916): Explicit concurrent mark sweep GC freed 58195(3MB) AllocSpace objects, 6(119KB) LOS objects, 22% free, 28MB/36MB, paused 756us total 29.336ms
,I/SettingSearch/SearchIntentReceiver( 8657): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/NetworkMonitor(11198): type=WIFI subType= reason=null isConnected=true
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/appmanager(:<default>):m(10916): No feature status reporters found; is this dead code?
,I/SettingSearch/SearchIntentReceiver( 8657): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 8657): LOCALE_CHANGED call search setting db finish!!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WearableService( 4667): callingUid 10014, callindPid: 4667
,I/NetworkMonitor(11198): type=WIFI subType= reason=null isConnected=true
,D/BluetoothManager( 9960): getConnectedDevices
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 9960): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/BluetoothManager( 9960): getConnectedDevices
,W/ContextImpl(10916): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/cache
,D/BluetoothManager( 9960): getConnectedDevices
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/Download/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10916): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files/Download
,D/BluetoothManager( 9960): getConnectedDevices
,D/BluetoothManager( 9960): getConnectedDevices
,D/BluetoothManager( 9960): getConnectedDevices
,I/MusicLeanback(11198): Conditions not met for autocaching.
I/MusicLeanback(11198): Stop autocaching.
,I/MusicLeanback(11198): Stop autocaching.
I/MusicLeanback(11198): Stop autocaching.
,D/BluetoothManager( 9960): getConnectedDevices
,D/SSRM:n  ( 3524): SIOP:: AP = 380, PST = 367, CUR = -933
,I/MusicLeanback(11198): Stop autocaching.
,I/MusicLeanback(11198): Stop autocaching.
,W/GoogleHttpClient(11198): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient(11198): Falling back to old SSLCertificateSocketFactory
,I/GHttpClientFactory(11198): Using the GMSCore's GoogleHttpClient
,D/BluetoothManager( 9960): getConnectedDevices
,D/BluetoothManager( 9960): getConnectedDevices
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,E/CscFactoryReceiver( 3982): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 3982): Media DB Scanner finished.
D/CscFactoryReceiver( 3982): start service to Set Ringtone
,D/CscFactoryReceiver( 3982): start service to Set Notification
,E/GmsUtils(11198): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/CscFactoryReceiver( 3982): start service to Set Alarmtone
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CscUpdateService( 3982): onStart
E/CscUpdateService( 3982): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3982): only ringtone update
,D/CscUpdateService( 3982): onStart
E/CscUpdateService( 3982): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3982): only notification update
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/CscParser( 3982): update(): xml file exist
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 3982): onStart
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/GmsUtils(11198): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/CscUpdateService( 3982): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3982): only alarmtone update
,E/CscParser( 3982): update(): xml file exist
,E/CscParser( 3982): update(): xml file exist
,W/CSCSettings( 3982): Setting Ringtones (type) : 1
D/CscParser( 3982): RingTone: null
W/CSCSettings( 3982): 1. Tag_Str: null
,W/CSCSettings( 3982): Setting Ringtones (type) : 4
D/CscParser( 3982): AlarmTone: null
W/CSCSettings( 3982): 1. Tag_Str: null
,W/CSCSettings( 3982): Setting Ringtones (type) : 2
,D/CscParser( 3982): MessageTone: null
W/CSCSettings( 3982): 1. Tag_Str: null
,E/Zygote  (11257): MountEmulatedStorage()
I/libpersona(11257): KNOX_SDCARD checking this for 10004
E/Zygote  (11257): v2
I/libpersona(11257): KNOX_SDCARD not a persona
,I/SELinux (11257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=11257 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10606:com.facebook.system/u0a10 (adj 13): bgCount ##31
,E/ActivityThread(11198): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3e7d72d2 that was originally bound here
E/ActivityThread(11198): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@3e7d72d2 that was originally bound here
E/ActivityThread(11198): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11198): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11198): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11198): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11198): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11198): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(11198): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11198): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11198): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(11198): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(11198): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(11198): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(11198): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(11198): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(11198): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(11198): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11198): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11198): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11198): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11198): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11198): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11198): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11198): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11198): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11198): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/TimaKeyStoreProvider(11257): TimaSignature is unavailable
D/ActivityThread(11257): Added TimaKeyStore provider
D/ResourcesManager(11257): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,I/DCMProvider(11257): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@2be76725 Provider Ref Count:1
,I/DCMConfig(11257): [#DCM#] initializeTransport.SystemBroadcastReceiver  1 ms
,I/StorageController(11257): [#DCM#]  state through storage volume =  mounted
,I/StorageController(11257): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(11257): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(11257): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
I/StorageController(11257): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
I/StorageController(11257): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager(11257): [#DCM#] setCriticalStateFromSystem screenOn =  true high siop = false camera running = false
,I/DCMPolicyManager(11257): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig(11257): [#DCM#] initializeTransport.DCMPolicyManager  17 ms
,I/DCMConfig(11257): [#DCM#] initializeTransport.MediaManager  18 ms
,I/DCMConfig(11257): [#DCM#] initializeTransport.DCMNRTManager  23 ms
,I/DCMConfig(11257): [#DCM#] No of CPU Core 8
I/DCMConfig(11257): [#DCM#] initializeTransport took  24 ms
I/DCMProvider(11257): [#DCM#] onCreate end 
,I/DCMNRTManager(11257): [#DCM#] intialize 
,I/SystemBroadcastReceiver(11257): [#DCM#] [DCM_Performance] onReceive completed in time  13 microsec. 
I/SystemBroadcastReceiver(11257): [#DCM#] [DCM_Performance] onReceive completed in time  8 microsec. 
,I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
,I/StorageController(11257): [#DCM#]  state through storage volume =  mounted
I/StorageController(11257): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/StorageController(11257): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/StorageController(11257): [#DCM#]  state through storage volume =  unmounted
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/StorageController(11257): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
I/StorageController(11257): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(11257): [#DCM#]  state through storage volume =  removed
,I/StorageController(11257): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController(11257): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController(11257): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/WriterFactory(11257): [#DCM#] verifyLuceneDB ++ 
I/DCMUtilities(11257): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,I/SystemUtils(11257): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils(11257): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities(11257): [#DCM#] OSUpgrade not required 
I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(11257): [#DCM#] onReceive action = EVENT_SIOP
I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
I/SystemBroadcastReceiver(11257): [#DCM#] No one is registered with Event Id EVENT_NETWORK_CHANGED
,E/Zygote  (11277): MountEmulatedStorage()
I/libpersona(11277): KNOX_SDCARD checking this for 10007
E/Zygote  (11277): v2
I/libpersona(11277): KNOX_SDCARD not a persona
I/WriterFactory(11257): [#DCM#] verifyLuceneDB OK breaking 
I/WriterFactory(11257): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory(11257): [#DCM#] TAXO in mode CREATE_OR_APPEND
I/SELinux (11277): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11277): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11277): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=11277 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10467:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/WriterFactory(11257): [#DCM#] Before facet 
,I/WriterFactory(11257): [#DCM#] After facet=!null ? true
,I/DCMUtilities(11257): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController(11257): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
I/DCMConfig(11257): [#DCM#] setSuccessState =  true
,D/TimaKeyStoreProvider(11277): TimaSignature is unavailable
,D/ActivityThread(11277): Added TimaKeyStore provider
,D/ResourcesManager(11277): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ThumbnailProvider(11277): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver(11277): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService(11277): [START] processBroadcastIntent ...
,I/BroadcastProcessorService(11277): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11296): MountEmulatedStorage()
E/Zygote  (11296): v2
I/libpersona(11296): KNOX_SDCARD checking this for 10044
I/libpersona(11296): KNOX_SDCARD not a persona
,I/SELinux (11296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11296): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=11296 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/SystemInfo(11277): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService(11277): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService(11277): [START] DocumentService startDocumentService
,I/DocumentService(11277): DocumentService onCreate ... service
,D/TimaKeyStoreProvider(11296): TimaSignature is unavailable
,D/ActivityThread(11296): Added TimaKeyStore provider
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/ResourcesManager(11296): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(11296): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(11296): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(11296): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11296): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(11296): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11296): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SystemInfo(11277): [SIOP LEVEL] : -2
,I/DocumentService(11277): [BEGIN SYNC] DocumentService beginIndexing :17
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11321): MountEmulatedStorage()
I/libpersona(11321): KNOX_SDCARD checking this for 10050
E/Zygote  (11321): v2
I/libpersona(11321): KNOX_SDCARD not a persona
,I/SELinux (11321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=11321 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3524): Killing 10326:com.samsung.android.app.galaxyfinder/u0a35 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(11321): TimaSignature is unavailable
,D/ActivityThread(11321): Added TimaKeyStore provider
,I/DocumentServiceUtils(11277):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo(11277): DocumentService [SIOP LEVEL] changed to -2
E/SystemInfo(11277): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,I/SystemInfo(11277): [SYSTEM STATUS] Battery and Storage levels are OK:
,D/ResourcesManager(11321): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/DocumentService(11277): [VERIFY] verifyThumbnailImages
,W/ResourcesManager(11321): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ResourcesManager(11321): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11321): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11321): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(11321): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11321): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11321): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl(11277): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/DocumentService(11277): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService(11277): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :80
E/DocumentService(11277): [THUMBNAIL] Total Time taken for each file :0
E/        (11277): [INDEX] Total time taken for each file :0
,I/DocumentService(11277): DocumentService onDestroy start
,I/DocumentService(11277): DocumentService onDestroy end
,I/DocumentService(11277): DocumentService cleanupEverything start
,I/IndexParserThreadsManager(11277): InterruptedException: null
,I/ActivityManager( 3524): Killing 10636:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,I/SystemInfo(11277): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(11277): DocumentService cleanupEverything end
I/Process (11277): Sending signal. PID: 11277 SIG: 9
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3524): Process com.samsung.indexservice (pid 11277)(adj 9) has died(76,1093)
,D/PackageManager( 3524): findPreferredActivity: No PreferredActivities set
,D/NearbySource(11321): Nearby Source Create!
D/NearbyContext(11321): Nearby Context Create!
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11321): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(11321): Samsung link source created
,D/ContactProvider(11321): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayAdapter( 3524): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/GalleryCacheReady(11321): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady(11321): handleMeidaScanFinish()
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11321): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11321): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11321): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl(11321): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/FaceInterface(11321): requestFaceScan() is called.
,I/FaceInterface(11321): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData(11321): query fail: 
W/LocalSuggestAlbumData(11321): query fail: 
,D/ContactProvider(11321): getAllContactInfoList End
I/syncContacts(11321): thread: 1578, sync time = 33
,D/BootupListener( 3982): ACTION_DRIVELINK
,D/SettingsProvider( 3524): name = drivelink_navigation
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
D/BootupListener( 3982): NAVI : com.here.app.maps
,D/SettingsProvider( 3524): name = internet_call_settings_visibility
D/SettingsProvider( 3524): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3524): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3524): selectionArgs: false
D/SettingsProvider( 3524): selectionArgs: 1001
D/SecContentProvider( 3524): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3524): ret = -1
,D/BootupListener( 3982): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/Widget  (10966): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  (10966): widgetUpdate 5
E/ActivityThread( 4820): Failed to find provider info for com.android.contacts.metadata
,D/RCPManagerService( 3524): exchangeData() failure , invalid userId
,D/SyncManager( 3524): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 51810, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3524): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 115615, reason: UserStart
,W/ResourceType( 5166): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5166): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/Widget  (10966): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,I/MediaStoreImporter(11198): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/GAV2    (10417): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log( 9677): 
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 9677): 
,I/io.jxcore.node.ConnectivityInfo( 9677): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 9677):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 9677):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 9677):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 9677):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 9677):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 9677):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 9677):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 9677):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 9677): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 9677): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 9677): 
I/jxcore-log( 9677): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 9677): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3524): Killing 10670:com.policydm/1000 (adj 13): bgCount ##31
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:2, health:2, present:true, voltage: 4308, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-817, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-602
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    (10533): Thread[GAThread,5,main]: No campaign data found.
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/art     (10653): Thread[1,tid=10653,WaitingForJniOnLoad,Thread*=0xb4d08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/art     (10653): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImp,l(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3bb6b9ec u0 ReceiverList{bc6a49f 10653 com.facebook.katana/10114/u0 remote:3db8e3e}}
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3bb6b9ec u0 ReceiverList{bc6a49f 10653 com.facebook.katana/10114/u0 remote:3db8e3e}}
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/GcOptimizer(10653): Configure for next cold start: disable
,W/BroadcastQueue( 3524): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{10fef26d u0 ReceiverList{5c5a84 10653 com.facebook.katana/10114/u0 remote:9628897}}
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl(10653): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@238e1fe8 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl(10653): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@6ac7601 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl(10653): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@1cf7b248 occurred when no user was logged in
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):QeInternalImpl(10653): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11406): MountEmulatedStorage()
E/Zygote  (11406): v2
I/libpersona(11406): KNOX_SDCARD checking this for 10082
I/libpersona(11406): KNOX_SDCARD not a persona
,I/SELinux (11406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11406): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3524): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=11406 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11406): TimaSignature is unavailable
,D/ActivityThread(11406): Added TimaKeyStore provider
,D/ResourcesManager(11406): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BadgeProvider(11406): onCreate
D/BadgeProvider(11406): DatabaseHelper
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10653): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10653): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,D/BadgeProvider(11406): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(11406): sendNotify, [notify] : null
D/BadgeProvider(11406): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(11406): update, [BadgeCount] : badgecount=0
D/BadgeProvider(11406): update, [UpdateCount] : 1
D/Launcher.Model( 4002): reloadBadges entered.
,W/fb4a(:<default>):UserScope(10653): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope(10653): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 29217(1856KB) AllocSpace objects, 18(4MB) LOS objects, 23% free, 53MB/69MB, paused 1.361ms total 100.081ms
,I/System.out(10916): P[5]_NetworkDispatch2 calls detatch()
,I/ActivityManager( 3524): Killing 9692:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 9677): 
,I/System.out(10916): P[5]_NetworkDispatch3 calls detatch()
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 9677): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
I/jxcore-log( 9677): 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    (11114): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3524): waitForAlarm result :4
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(11198): Conditions not met for autocaching.
I/MusicLeanback(11198): Stop autocaching.
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11198): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient(11198): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(11198): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/iu.UploadsManager( 4820): End new media; added: 0, uploading: 0, time: 64 ms
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3524): waitForAlarm result :4
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11457): MountEmulatedStorage()
E/Zygote  (11457): v2
I/libpersona(11457): KNOX_SDCARD checking this for 10031
I/libpersona(11457): KNOX_SDCARD not a persona
,I/SELinux (11457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=11457 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SELinux (11457): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11457): TimaSignature is unavailable
,D/ActivityThread(11457): Added TimaKeyStore provider
,D/ResourcesManager(11457): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/AlarmManager( 3524): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 5236): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 5236): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 15 36
,D/Finsky  (11457): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/FaceInterface(11321): startFaceScan() : going on
D/FaceInterface(11321): startFaceScan() is called.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ContentApp( 5414): startScan() is called.
,D/ContentApp( 5414): startScan() is end.
,D/ContentApp( 5414): face_restore FINISHED_TYPE: 3
D/FaceScanner( 5414): isNeedToRestore : start
,D/Finsky  (11457): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(11457): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(11457): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SQLiteLog(11150): (283) recovered 652 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,D/Finsky  (11457): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Ads     (11457): Skipping gmscore version check
,D/Finsky  (11457): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (11457): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (11457): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (11457): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(11457): Thread-1592(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11457): Thread-1592(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(11457): Thread-1592(ApacheHTTPLog):isShipBuild true
I/System.out(11457): Thread-1592(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10031
,I/qtaguid (11457): Tagging socket 44 with tag e8d195d100000000{3906049489,0} uid -1, pid: 11457, getuid(): 10031
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 3524): lcd : 1 +
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 1 -,
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (11457): Tagging socket 48 with tag e8d195d100000000{3906049489,0} uid -1, pid: 11457, getuid(): 10031
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (11457): Untagging socket 44
,I/System.out(11457): Thread-1592 calls detatch()
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (11457): Untagging socket 44
,I/qtaguid (11457): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (11457): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(11457): untagSocket(44) failed with errno -22
I/System.out(11457): Thread-1593 calls detatch()
,D/Finsky  (11457): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (11501): MountEmulatedStorage()
E/Zygote  (11501): v2
I/libpersona(11501): KNOX_SDCARD checking this for 10014
I/libpersona(11501): KNOX_SDCARD not a persona
,I/SELinux (11501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=11501 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux (11501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11501): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(11501): TimaSignature is unavailable
,D/ActivityThread(11501): Added TimaKeyStore provider
,D/ResourcesManager(11501): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(11501): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(11501): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MultiDex(11501): VM with version 2.1.0 has multidex support
I/MultiDex(11501): install
I/MultiDex(11501): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (11501): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(11501): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (11501): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18451b29: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(11501): Installed default security provider GmsCore_OpenSSL
,I/splitIntent( 3524): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3524): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,I/qtaguid (11457): Untagging socket 44
,I/qtaguid (11457): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (11457): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(11457): untagSocket(44) failed with errno -22
I/System.out(11457): Thread-1592 calls detatch()
,D/AuthorizationBluetoothService( 4667): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr(11501): Reading stored module config
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationInitializer( 4820): Restart initialization of location
,E/MDM     ( 4667): [317] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 4667): No location to return for getLastLocation()
,W/FusedLocationProvider( 4667): location=null
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/splitIntent( 3524): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/NativeLibraryUtils(11501): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE(11501): Connecting to CarCallService...
,I/art     (11501): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (11501): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE(11501): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service(11501): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter(11501): Creating a new PhoneAdapter instance
,W/ActivityManager( 3524): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/PackageManager( 3524): [MSG] MCS_UNBIND
D/CAR.TEL.PhoneAdapter(11501): setListener: com.google.android.gms.car.dn@c56900c
,W/ActivityManager( 3524): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(11501): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service(11501): Starting CarCallService with initial phone null
,I/ActivityManager( 3524): Killing 10533:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAR.SERVICE(11501): Package validated; name: com.android.vending
,V/Finsky  (11457): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (11457): Untagging socket 44
,I/qtaguid (11457): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (11457): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(11457): untagSocket(44) failed with errno -22
I/System.out(11457): Thread-1593 calls detatch()
,D/ResourcesManager(11457): creating new AssetManager and set to /system/framework/framework-res.apk
,D/ResourcesManager(11457): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(11457): creating new AssetManager and set to /system/app/ANTRadioService/ANTRadioService.apk
,D/ResourcesManager(11457): creating new AssetManager and set to /system/app/AntHalService/AntHalService.apk
,W/ResourcesManager(11457): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(11457): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(11457): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(11457): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10110
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(11457): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(11457): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(11457): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  (11457): [1] DailyHygiene.access$600: Logging device features
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3524): waitForAlarm result :4
,D/DeviceConnectionService( 4667): client connected with version: 8296000
,D/Finsky  (11457): [1614] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (11457): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  (11457): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11457): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(11457): (HTTPLog)-Static: isShipBuild true
I/System.out(11457): (HTTPLog)-Thread-1603-986242416: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(11457): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10031
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{71f61b1 u0 com.samsung.android.MtpApplication/.MtpService}
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(10916): P[5]_NetworkDispatch4 calls detatch()
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(10916): P[5]_NetworkDispatch5 calls detatch()
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3524): SIOP:: AP = 360, PST = 366, CUR = -817
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:2, health:2, present:true, voltage: 4384, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:-422, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:105
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/PowerManagerService( 3524): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3524): !@[ps] Screen__Off - 0 : timeout (0x4) (2)
I/PowerManagerService( 3524): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI( 3524): setDeviceInteractive: 0
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3524): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3524): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService( 3524): handleSandman : startDream()
E/PowerManagerService( 3524): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 3524): Sleeping (uid 1000)...
D/PowerManagerService( 3524): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3524): [input device light] setInputDeviceLightOn is called : 0,
D/PowerManagerService( 3524): [input device light] handleInputDeviceLightOff
,D/SContextService( 3524): 	.unregisterCallback : 1, client=
,D/SContextService( 3524): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@36238e67, Service = Auto Rotation, used = 1
I/SurfaceFlinger( 2849): id=14 createSurf (1440x2560),2 flag=404, DolorFade
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3524): stop(ContextProvider.java:149)
,V/CAE     ( 3524): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3524): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2867): sendContextData: -78, 7, 0, 0
,D/PowerManagerService( 3524): Excessive delay in ColorFade : createSurface: 13ms
,D/CAE     ( 3524): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3524): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3524): Excessive delay in ColorFade : createEglContext: 19ms
,D/mali_winsys( 3524): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PowerManagerService( 3524): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 28ms
,D/CAE     ( 3524): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3524): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3524): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3524): removeSContextService() : service = Auto Rotation
D/SContextService( 3524): ===== SContext Service List =====
D/SContextManager( 3524):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@26e36050, service=Auto Rotation
,D/KeyguardViewMediator( 3690): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3690): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3690): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 3690): notifyScreenOffLocked
,V/ActivityThread( 9677): updateVisibility : ActivityRecord{2d5af4e5 token=android.os.BinderProxy@3e704108 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/KeyguardViewMediator( 3690): timeout : 5000
,D/KeyguardViewMediator( 3690): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 3690): handleNotifyScreenOff
,D/PowerManagerService( 3524): Excessive delay in ColorFade : initGLShaders: 51ms
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs( 2867): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService( 3524): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 18ms
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_ON
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 14ms
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/MotionRecognitionService( 3524):  handler : SCREEN_ON end
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 13ms
D/PowerManagerService( 3524): Excessive delay in ColorFade prepare: 169ms
D/DisplayPowerController( 3524): ColorFade: onAnimationStart
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: true
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/NotificationService( 3524): ACTION_SCREEN_ON
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3524): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2855): setParameters(screen_state=on)
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3524): do suspend false
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/wpa_supplicant( 3833): reset timer : RESET_TIMER 1
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
,D/lights  ( 3524): lcd : 0 +
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 0 -
,I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_ON called
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,I/NfcService( 3966): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3966): call the applyRouting
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SamsungIME( 4436): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 5236): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:281 [0:0] update clock event, is not screen on!!
,D/SSRM:n  ( 3524): SIOP:: AP = 350, PST = 363, CUR = -422
,I/SystemBroadcastReceiver(11257): [#DCM#] [DCM_Performance] onReceive completed in time  2111 microsec. 
,I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(11257): [#DCM#] onReceive action = EVENT_SCREEN_ON
,I/DCMController(11257): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3778): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,D/comsamsunglog( 3778): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LightsService( 3524): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 3524) 
D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457728500000
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457706966889
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3524): turn on LED for charging
,D/SensorManager( 3524): unregisterListener ::   
D/lights  ( 3524): led_pattern : 1 +
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/lights  ( 3524): led_pattern : 1 -
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs( 2867): sendContextData: -76, 13, -46, 0
E/daemonapp( 3778): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 36, 6,
D/SensorHubManager( 3524): SendSensorHubData: send data = -63, 14, 14, 36, 6
,D/Sensorhubs( 2867): sendContextData: -63, 14, 14, 36, 6
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3524):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/NotificationService( 3524): ACTION_SCREEN_OFF
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: false
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerState( 3524): !@ ColorFade entry
D/DisplayPowerController( 3524): ColorFade: onAnimationEnd
D/SensorManager( 3524): unregisterListener ::   
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3524): do suspend true
,I/AudioHardwareTinyALSA( 2855): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/Sensors ( 3524): Light old sensor_state 513, new sensor_state : 1 en : 0
,I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SensorManager( 3524): unregisterListener ::   
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
I/Sensors ( 3524): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Display
,I/DisplayManagerService( 3524): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger( 2849): Set power mode=0, type=0 flinger=0xb6a62000
I/hwcomposer( 2849): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
D/SensorManager( 3524): unregisterListener ::   
,V/ActivityManager( 3524): Display changed displayId=0
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/VolumePanel( 3690): registerReceiver: onReceive start 
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3690): registerReceiver: onReceive end 
,D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3690): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3966): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3690):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3690): onReceive : Intent.ACTION_SCREEN_OFF
,D/CAR.SERVICE(11501): mConnectedToCar = false, abort
,E/ActivityThread(11501): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3529a79d that was originally bound here
E/ActivityThread(11501): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3529a79d that was originally bound here
E/ActivityThread(11501): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11501): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11501): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11501): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11501): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11501): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11501): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11501): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread(11501): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread(11501): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread(11501): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread(11501): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread(11501): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread(11501): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(11501): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(11501): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(11501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11501): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11501): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11501): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11501): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11501): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11501): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/accuweather( 5236): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,E/ActivityThread(11501): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11857f3f that was originally bound here
E/ActivityThread(11501): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@11857f3f that was originally bound here
E/ActivityThread(11501): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(11501): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(11501): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(11501): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(11501): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(11501): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread(11501): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread(11501): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread(11501): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread(11501): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread(11501): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread(11501): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread(11501): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread(11501): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread(11501): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread(11501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(11501): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(11501): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(11501): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(11501): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(11501): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(11501): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 3524): Unbind failed: could not find connection for android.os.BinderProxy@7fe5cb8
,D/accuweather( 5236): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3524): SIOP:: AP = 350, PST = 361, CUR = -422
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5236): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5236): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5236): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SystemBroadcastReceiver(11257): [#DCM#] [DCM_Performance] onReceive completed in time  98 microsec. 
,I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(11257): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController(11257): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5236): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/SurfaceControl( 3524): Excessive delay in setPowerMode(): 200ms
D/PowerManagerService( 3524): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3524): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3524): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/PowerManagerService( 3524): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 201ms
,D/accuweather( 5236): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,I/PowerManagerService( 3524): [PWL] Off : 0s ago
I/PowerManagerService( 3524): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 3524): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 3524): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService' (uid=10031, pid=11457, ws=null) (elapsedTime=3419)
,D/accuweather( 5236): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 39815(2MB) AllocSpace objects, 7(112KB) LOS objects, 23% free, 53MB/69MB, paused 2.193ms total 142.397ms
,W/IcingInternalCorpora( 4820): getNumBytesRead when not calculated.
,D/SSRM:a  ( 3524): DeviceInfo:: 000000100000
,D/SSRM:a  ( 3524): SettingsAirViewInfo:: 000000000
,I/ActivityManager( 3524): Waited long enough for: ServiceRecord{14bac8b2 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,W/IdleConnectionHandler(10916): Removing a connection that never existed!
,W/IdleConnectionHandler(10916): Removing a connection that never existed!
,W/ProcessCpuTracker( 3524): Skipping unknown process pid 11577
,I/System.out(11457): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Killing 10698:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,I/wpa_supplicant( 3833): nl80211: Received scan results (20 BSSes)
,E/WifiStateMachine( 3524): [1,457,706,970,473 ms] noteScanEnd no scan source
,D/WifiP2pService( 3524): InactiveState{ what=147461 }
,D/WifiP2pService( 3524): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 3524): DefaultState{ what=147461 }
,E/WifiStateMachine( 3524): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@30f8a49d sup_state=COMPLETED debouncing=false
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardViewMediator( 3690): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 3690): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 3524): [PWL] Off : 5s ago
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3524): waitForAlarm result :8
,E/Watchdog( 3524): !@Sync 2
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:2, health:2, present:true, voltage: 4395, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:-106, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:188
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for charging
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/AlarmManager( 3524): waitForAlarm result :4
,D/SSRM:n  ( 3524): SIOP:: AP = 320, PST = 356, CUR = -106
,V/AlarmManager( 3524): waitForAlarm result :4
,D/Finsky  (11457): [1605] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (11457): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3524): [PWL] Off : 15s ago
,V/xAnalytics(10653): xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3524): waitForAlarm result :4
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:2, health:2, present:true, voltage: 4396, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:44, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:151
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for charging
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 310, PST = 351, CUR = 44
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3524): Killing 10761:com.vlingo.midas/u0a34 (adj 13): bgCount ##31
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:96, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:106
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/LightsService( 3524): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3524) 
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,D/SecContentProvider2( 3524): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3524): mCursor = null
,I/Sensors ( 3524): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3524): turn on LED for fully charged
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/ApplicationPolicy( 3524): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager( 3524): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 3524): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3690
I/PowerManagerService( 3524): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService( 3524): Waking up from sleep (uid 10060)...
,D/PowerManagerService( 3524): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3524): [s] UserActivityState : 0 -> 1
V/KeyguardServiceDelegate( 3524): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@7661613)
D/PowerManagerService( 3524): [PWL] sb acquire: PowerManagerService.Display
,D/KeyguardViewMediator( 3690): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 3690): notifyScreenOnLocked
,I/DisplayPowerController( 3524): Blocking screen on until initial contents have been drawn.
,D/SContextService( 3524): 	.registerCallback : 1, client=
W/CAE     ( 3524): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerManagerService( 3524): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL( 3524): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 3524): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/SurfaceFlinger( 2849): Set power mode=2, type=0 flinger=0xb6a62000
I/hwcomposer( 2849): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(0)
D/AutomaticBrightnessController( 3524): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/AutomaticBrightnessController( 3524): [DAB] updateAutoBrightnessSEC : 11(11.0)    0.0 < 0.0 < 15.0 (0.6)
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PowerManagerService( 3524): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 2ms
,I/Sensors ( 3524): Acc old sensor_state 512, new sensor_state : 513 en : 1
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/CAE     ( 3524): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/SensorManager( 3524): registerListener :: 0, ICM20610 Acceleration Sensor, 200000, 0,  
D/PowerManagerService( 3524): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 4ms
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/CAE     ( 3524): setCAProperty(ContextAwareService.java:469) - result : true
,W/CAE     ( 3524): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3524): sendAttribute() : service = Auto Rotation
W/CAE     ( 3524): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3524): start(ContextProvider.java:126)
,V/CAE     ( 3524): clear(AutoRotationRunner.java:182)
V/CAE     ( 3524): enable(AutoRotationRunner.java:158)
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs( 2867): sendContextData: -79, 7, 0, 0
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAE     ( 3524): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3524): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     ( 3524): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3524): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     ( 3524): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     ( 3524): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@15272ae7, Service : AUTO_ROTATION(1)
,W/CAE     ( 3524): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3524): addSContextService() : service = Auto Rotation
D/SContextService( 3524): ===== SContext Service List =====
,D/SContextService( 3524): Listener : android.hardware.scontext.SContextService$Listener@669d694, Service : Auto Rotation
D/SContextManager( 3524):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@26e36050, service=Auto Rotation
,I/DisplayManagerService( 3524): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 3524): Display changed displayId=0
,V/ActivityManager( 3524): Display changed displayId=0
,I/Sensors ( 3524): #>LightSensor r=1 g=1 b=2 c=4 atime=238 again=64 lux=0.000000
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 3524): unregisterListener ::   
D/lights  ( 3524): led_pattern : 5 +
,D/KeyguardViewMediator( 3690): handleNotifyScreenOn
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/StatusBarKeyguardViewManager( 3690): onScreenTurnedOn()
,D/PalmMotion( 3524): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/lights  ( 3524): led_pattern : 5 -
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PalmMotion( 3524): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SSRM:a  ( 3524): DeviceInfo:: 000000100000
D/SSRM:a  ( 3524): SettingsAirViewInfo:: 000000000
,D/ActivityManager( 3524): post active user change for 0
,D/SurfaceControl( 3524): Excessive delay in setPowerMode(): 208ms
D/PowerManagerService( 3524): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 209ms
,D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,D/InputManager-JNI( 3524): setDeviceInteractive: 1
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3524): unregisterListener ::   
,D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/KnoxNotification( 3690): ----- inflateViews : modified publicViewLocal -----
,D/SamsungIME( 4436): showDlgMsgBox : false true true
,D/KnoxNotification( 3690): ----- inflateViews : modified KnoxViewLocal -----
,D/NfcService( 3966): call the applyRouting
,D/PersonaManager( 3690): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3690): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@11164b69
,I/Timeline( 9677): Timeline: Activity_idle id: android.os.BinderProxy@3e704108 time:94377
,V/UserPresentBroadcastReceiver( 4667): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3690): Icon Only
,I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
,I/Sensors ( 3524): #>LightSensor r=1 g=1 b=2 c=4 atime=238 again=64 lux=0.000000
,V/KeyguardServiceDelegate( 3524): **** SHOWN CALLED ****
D/StatusBarKeyguardViewManager( 3690): callback.onShown()
D/DisplayPowerController( 3524): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 3524): Unblocked screen on after 367 ms
D/DisplayPowerState( 3524): !@ ColorFade exit
,I/SurfaceFlinger( 2849): id=14 Removed DolorFade (8/8)
,D/BatteryMeterView( 3690): onDraw batteryColor : -1
,I/SurfaceFlinger( 2849): id=14 Removed DolorFade (-2/8)
,E/libEGL  ( 3524): call to OpenGL ES API with no current context (logged once per thread)
,D/PowerManagerService( 3524): Excessive delay in ColorFade : dismiss: 12ms
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 11 +
,D/lights  ( 3524): lcd : 11 -
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3524): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService( 3524): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService( 3524): [input device light] handleInputDeviceLightOn
D/lights  ( 3524): button : 1 +
D/lights  ( 3524): button : 1 -
,D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/lights  ( 3524): led_pattern : 0 +
D/BatteryService( 3524): turn off LED
D/LightsService( 3524): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 3524): led_pattern : 0 -
,D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs( 2867): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService( 3524): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,E/MotionRecognitionService( 3524):  handler : SCREEN_ON end
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NotificationService( 3524): ACTION_SCREEN_ON
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: true
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/StatusBar.NetworkController( 3690): applyOpen
,D/LightsService( 3524): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event2/device/enabled: 1
I/AudioHardwareTinyALSA( 2855): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3524): do suspend false
,I/wpa_supplicant( 3833): reset timer : RESET_TIMER 1
I/wpa_supplicant( 3833): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3833): P2P: Current p2p state = IDLE
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,I/wpa_supplicant( 3833): Scan requested (ret=0) - scan timeout 30 seconds
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_ON
E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_ON called
,I/NfcService( 3966): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3966): call the applyRouting
,I/SamsungIME( 4436): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 5236): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,I/Sensors ( 3524): #>LightSensor r=1 g=2 b=2 c=5 atime=238 again=64 lux=0.000000
,E/accuweather( 5236): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 15 36
,I/SystemBroadcastReceiver(11257): [#DCM#] [DCM_Performance] onReceive completed in time  323 microsec. 
,I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(11257): [#DCM#] onReceive action = EVENT_SCREEN_ON
D/SSRM:n  ( 3524): SIOP:: AP = 300, PST = 346, CUR = 96
I/DCMController(11257): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3778): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,D/comsamsunglog( 3778): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3778): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457728500000
D/daemonapp( 3778): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457706997024
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3778): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3778): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3778): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SSRM:a  ( 3524): DeviceInfo:: 000000100000
D/SSRM:a  ( 3524): SettingsAirViewInfo:: 000000000
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/PowerManagerService( 3524): [input device light] handleInputDeviceLightOff
D/lights  ( 3524): button : 0 +
,D/lights  ( 3524): button : 0 -
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02055d/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/wpa_supplicant( 3833): nl80211: Received scan results (18 BSSes)
,D/WifiP2pService( 3524): InactiveState{ what=147461 }
,E/WifiStateMachine( 3524): [1,457,707,000,663 ms] noteScanEnd no scan source
,D/WifiP2pService( 3524): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 3524): DefaultState{ what=147461 }
,E/WifiStateMachine( 3524): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@30f8a49d sup_state=COMPLETED debouncing=false
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3524): waitForAlarm result :4
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 4667): Vacuum at: now=1457707004735 tag=VacuumService
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PhenotypeConfigurator( 4667): Scheduling Phenotype for one-off execution 9113 seconds from now (1457707005147)
,I/PhenotypeFlagCommitter( 4667): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4667): Using platform SSLCertificateSocketFactory
,E/Watchdog( 3524): !@Sync 3
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3524): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 4667): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2845): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2845): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4667): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 4667): Tagging socket 80 with tag 3000120100000000{805310977,0} uid -1, pid: 4667, getuid(): 10014
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid ( 4667): Tagging socket 83 with tag 3000120100000000{805310977,0} uid -1, pid: 4667, getuid(): 10014
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3524): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 4667): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4667): Tagging socket 80 with tag 3000120100000000{805310977,0} uid -1, pid: 4667, getuid(): 10014
,D/LocationManagerService( 3524): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4667): Tagging socket 80 with tag 3000120100000000{805310977,0} uid -1, pid: 4667, getuid(): 10014
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-151
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
,D/LocationManagerService( 3524): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4667): Tagging socket 80 with tag 3000120100000000{805310977,0} uid -1, pid: 4667, getuid(): 10014
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3524): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4667): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4667): Tagging socket 80 with tag 3000120100000000{805310977,0} uid -1, pid: 4667, getuid(): 10014
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3524): SIOP:: AP = 300, PST = 341, CUR = 38
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/FactoryTest(10280): Not factory mode
D/FactoryTest(10280): Not factory mode. isFactoryMode() returend false
,D/MTPRx   (10280): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   (10280): still no open session command from host, so toast
W/ContextImpl(10280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl(10280): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
I/Timeline(10280): Timeline: Activity_launch_request id:com.android.settings time:106972
,E/PersonaManagerService( 3524): inState():  stateMachine is null !!
I/PersonaManagerService( 3524): PersonaId don't exist
I/ActivityManager( 3524): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3524): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3524): mDVFSHelper.acquire()
,E/MTPRx   (10280): started activity for popup
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,V/ActivityManager( 3524): Display changed displayId=0
,D/ResourcesManager(10280): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10280): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10280): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10280): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10280): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10280): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10280): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10280): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity(10280): PREF_DONT_ASK_AGAIN : true
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
E/ActivityManager( 3524): Invalid thumbnail dimensions: 768x768
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService( 3524): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 3524): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@8ca6719 attribute=android.view.inputmethod.EditorInfo@3fedb3de, token = android.os.BinderProxy@16248111
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SettingsReceiverActivity(10280): dev.kiessupport is : TRUE
,D/Activity(10280): performCreate Call secproduct feature valuefalse
D/Activity(10280): performCreate Call debug elastic valuetrue
,D/ActivityManager( 3524): post active user change for 0
D/KnoxTimeoutHandler( 3524): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3524): handleActiveUserChange for user 0
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 9677): Timeline: Activity_idle id: android.os.BinderProxy@3e704108 time:107137
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@2
W/ActivityManager( 3524): mDVFSHelper.release()
D/CustomFrequencyManagerService( 3524): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  pkgName : ACTIVITY_RESUME_BOOSTER@6
,I/libencoder( 3524): width= 768, height = 768, colot_type= 6, bit_depth= 8
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CustomFrequencyManagerService( 3524): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3524  tag : ACTIVITY_RESUME_BOOSTER@6
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3690 (0x0)
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:122
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3524): SIOP:: AP = 290, PST = 337, CUR = 31
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,V/AlarmManager( 3524): waitForAlarm result :8
,V/AlarmManager( 3524): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3524): <AppSync3 Whitelist>
V/AlarmManager( 3524): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 5236): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 5236): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 15 37
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3524): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 3524): lcd : 3 +
,D/lights  ( 3524): lcd : 3 -
,D/lights  ( 3524): lcd : 1 +
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 1 -
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3524): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3524): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3524): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3524): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
D/InputManager-JNI( 3524): setDeviceInteractive: 0
I/PowerManagerService( 3524): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 3524): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3524): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService( 3524): handleSandman : startDream()
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/InputManager-JNI( 3524): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService( 3524): handleSandman : startDreaming, but isDreaming false
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event3/device/enabled: 0
I/PowerManagerService( 3524): Sleeping (uid 1000)...
D/PowerManagerService( 3524): [s] UserActivityState : 4 -> 0
,D/PowerManagerService( 3524): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService( 3524): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger( 2849): id=15 createSurf (1440x2560),2 flag=404, DolorFade
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3524): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService( 3524): 	.unregisterCallback : 1, client=
D/SContextService( 3524): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@669d694, Service = Auto Rotation, used = 1
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3524): stop(ContextProvider.java:149)
,V/CAE     ( 3524): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3524): disable(AutoRotationRunner.java:171)
I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs( 2867): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3524): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,D/PowerManagerService( 3524): Excessive delay in ColorFade : createSurface: 20ms
I/CAE     ( 3524): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/mali_winsys( 3524): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PowerManagerService( 3524): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 30ms
,D/CAE     ( 3524): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3524): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3524): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3524): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3524): removeSContextService() : service = Auto Rotation
D/SContextService( 3524): ===== SContext Service List =====
D/SContextManager( 3524):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@26e36050, service=Auto Rotation
,D/KeyguardViewMediator( 3690): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3690): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3690): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 3690): notifyScreenOffLocked
,D/KeyguardViewMediator( 3690): timeout : 5000
,D/PowerManagerService( 3524): Excessive delay in ColorFade : initGLShaders: 34ms
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 13ms
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 10ms
,V/ActivityThread( 9677): updateVisibility : ActivityRecord{2d5af4e5 token=android.os.BinderProxy@3e704108 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PowerManagerService( 3524): Excessive delay in ColorFade : draw: 16ms
D/PowerManagerService( 3524): Excessive delay in ColorFade prepare: 129ms
D/DisplayPowerController( 3524): ColorFade: onAnimationStart
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/KeyguardViewMediator( 3690): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 3690): handleNotifyScreenOff
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/lights  ( 3524): lcd : 0 +
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3524): lcd : 0 -
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:62, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:89
,D/LightsService( 3524): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3524) 
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3524): turn on LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/SensorManager( 3524): unregisterListener ::   
D/lights  ( 3524): led_pattern : 5 +
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/lights  ( 3524): led_pattern : 5 -
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,I/CAE     ( 3524): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3524): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3524): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs( 2867): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3524): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 14, 37, 6,
D/SensorHubManager( 3524): SendSensorHubData: send data = -63, 14, 14, 37, 6
D/Sensorhubs( 2867): sendContextData: -63, 14, 14, 37, 6
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/MotionRecognitionService( 3524):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3524):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3524): evaluateTrafficStatsPolling
,D/NotificationService( 3524): ACTION_SCREEN_OFF
D/WifiStateMachine( 3524): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/LightsService( 3524): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3524) 
E/WifiStateMachine( 3524): handleScreenStateChanged Exit: false
D/LightsService( 3524): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 3524): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
D/SensorManager( 3524): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/WifiStateMachine( 3524): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3524): do suspend true
,D/SensorManager( 3524): unregisterListener ::   
D/LightsService( 3524): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2855): setParameters(screen_state=off),
,D/AutomaticBrightnessController( 3524): mCallbacks.updateBrightness()
,I/SecExternalDisplayIntents_Java( 3524): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 3524): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3524): Bridge Server is not available
,D/VolumePanel( 3690): registerReceiver: onReceive start 
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3690): registerReceiver: onReceive end 
,D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3690): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF end
,D/DisplayPowerController( 3524): getFinalBrightness : 11 -> 0
D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/DisplayPowerController( 3524): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/GpsLocationProvider( 3524): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3524): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3524): sExerciseIterface is not available
,D/PersonaManagerService( 3524): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 3524): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3966): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3690):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3690): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5236): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5236): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3524): SIOP:: AP = 290, PST = 333, CUR = 62
,D/DisplayPowerState( 3524): !@ ColorFade entry
D/DisplayPowerController( 3524): ColorFade: onAnimationEnd
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 5236): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5236): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
,D/accuweather( 5236): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5236): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/AutomaticBrightnessController( 3524): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3524): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3524): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3524): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Display
D/AutomaticBrightnessController( 3524): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/DisplayManagerService( 3524): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/Sensors ( 3524): Light old sensor_state 513, new sensor_state : 1 en : 0
,V/ActivityManager( 3524): Display changed displayId=0
D/SurfaceFlinger( 2849): Set power mode=0, type=0 flinger=0xb6a62000
,I/hwcomposer( 2849): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
,D/SensorManager( 3524): unregisterListener ::   
,I/Sensors ( 3524): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/SensorManager( 3524): unregisterListener ::   
,I/SystemBroadcastReceiver(11257): [#DCM#] [DCM_Performance] onReceive completed in time  338 microsec. 
,I/SystemBroadcastReceiver(11257): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager(11257): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController(11257): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService( 3524): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3778): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5236): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5236): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5236): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5236): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5236): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3524): Excessive delay in setPowerMode(): 209ms
D/PowerManagerService( 3524): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3524): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3524): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/PowerManagerService( 3524): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 210ms
I/PowerManagerService( 3524): [PWL] Off : 0s ago
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3524): waitForAlarm result :4
,D/KeyguardViewMediator( 3690): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 3690): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 3524): [PWL] Off : 5s ago
,E/Watchdog( 3524): !@Sync 4
,V/AlarmManager( 3524): waitForAlarm result :4
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:71, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3524): SIOP:: AP = 290, PST = 326, CUR = 71
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3524): [PWL] Off : 15s ago
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:79, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:80
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/BatteryService( 3524): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 318, CUR = 79
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ClearcutLoggerApiImpl( 4820): disconnect managed GoogleApiClient
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 3524): waitForAlarm result :4
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 310, CUR = 76
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:76, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:57
D/BatteryService( 3524): stay LED for fully charged
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3524): [PWL] Off : 30s ago
,E/Watchdog( 3524): !@Sync 5
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 303, CUR = 76
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:71, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:85
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 295, CUR = 71,
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:65, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:55
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,I/PowerManagerService( 3524): [PWL] Off : 50s ago
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3524): waitForAlarm result :4
,V/AlarmManager( 3524): waitForAlarm result :4
,V/AlarmManager( 3524): waitForAlarm result :8
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 290, CUR = 65
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:87
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3524): !@Sync 6
,D/SSRM:n  ( 3524): SIOP:: AP = 280, PST = 287, CUR = 63
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
,D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2872): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,I/PowerManagerService( 3524): [PWL] Off : 75s ago
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 284, CUR = 59
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3524): waitForAlarm result :4
,I/ClearcutLoggerApiImpl( 4667): disconnect managed GoogleApiClient
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 280, CUR = 57
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3524): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:60
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3524): !@Sync 7
,D/SSRM:n  ( 3524): SIOP:: AP = 270, PST = 278, CUR = 55
,D/BatteryService( 3524): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3524): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3524): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:70
D/BatteryService( 3524): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3524): stay LED for fully charged
,I/MotionRecognitionService( 3524): Plugged
,I/MotionRecognitionService( 3524): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5599): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5599): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3524): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 9677): Reconnected to the test server
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): --= Surplus to requirements =--
I/jxcore-log( 9677): 
,I/jxcore-log( 9677): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 9677): 
,D/AndroidRuntime(11905): 
D/AndroidRuntime(11905): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(11905): CheckJNI is OFF
,D/AndroidRuntime(11905): readGMSProperty: start
D/AndroidRuntime(11905): readGMSProperty: already setted!!
,D/AndroidRuntime(11905): readGMSProperty: end
D/AndroidRuntime(11905): addProductProperty: start
,E/AffinityControl(11905): AffinityControl: registerfunction enter
,D/AndroidRuntime(11905): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3524): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3524): START PACKAGE DELETE: observer{430494291}
D/PackageManager( 3524): pkg{<packageName>}
D/PackageManager( 3524): user{0}
D/PackageManager( 3524): caller{2000}
D/PackageManager( 3524): flags{3}
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3524): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3524): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3524): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3524): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3524): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3524): !@killApplicatoin: 10692, uninstall pkg
I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10692 user=-1: uninstall pkg
,I/ActivityManager( 3524): Killing 9677:com.test.thalitest/u0a692 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3524):   Force finishing activity ActivityRecord{165881fd u0 com.test.thalitest/.MainActivity t32}
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 3524): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3524): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3524): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3524): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3524): Skipping PackageSetting{1fd7a8e4 com.example.hello/10691} due to missing metadata
,I/ActivityManager( 3524): Force stopping com.test.thalitest appid=10692 user=0: pkg removed
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 8693): Explicit concurrent mark sweep GC freed 30515(1689KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.634ms total 37.677ms
,D/WifiService( 3524): Client connection lost with reason: 4
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,W/GeofencerStateMachine( 4667): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4820): Explicit concurrent mark sweep GC freed 5700(302KB) AllocSpace objects, 1(16KB) LOS objects, 20% free, 31MB/39MB, paused 2.123ms total 62.697ms
,I/InputReader( 3524): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4436): mOCRHelper is null
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/art     ( 4057): Explicit concurrent mark sweep GC freed 30521(1893KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.022ms total 75.724ms
,E/libprocessgroup( 3524): failed to kill 1 processes for processgroup 9677
,D/LWLocationManager(11079): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11079): getLastUiLocationId() : mLastUiLocationId = -100
,D/EnterpriseDeviceManagerService( 3524): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3524): Admin package name: com.google.android.gms
,E/Zygote  (11927): MountEmulatedStorage()
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/libpersona(11927): KNOX_SDCARD checking this for 10063
E/Zygote  (11927): v2
I/libpersona(11927): KNOX_SDCARD not a persona
,I/SELinux (11927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourceType( 5166): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5166): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/ActivityManager( 3524): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11927 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider(11927): TimaSignature is unavailable
,D/ActivityThread(11927): Added TimaKeyStore provider
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 88476(5MB) AllocSpace objects, 56(5MB) LOS objects, 23% free, 53MB/69MB, paused 2.497ms total 193.435ms
D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(11927): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/art     ( 3524): WaitForGcToComplete blocked for 65.690ms for cause Explicit
,D/SecContentProvider2( 3524): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3524): mCursor = null
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/VRSetupWizardStub/PackageIntentReceiver(11927): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(11927): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(11927): packagename:com.test.thalitest
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11944): MountEmulatedStorage()
I/libpersona(11944): KNOX_SDCARD checking this for 10021
E/Zygote  (11944): v2
I/libpersona(11944): KNOX_SDCARD not a persona
I/SELinux (11944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/ActivityManager( 3524): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11944 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,W/ResourceType( 3524): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager( 3524): Killing 10719:com.sec.android.automotive.drivelink/u0a102 (adj 13): bgCount ##31
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 902us total 21.959ms
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 470us total 18.589ms
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/TimaKeyStoreProvider(11944): TimaSignature is unavailable
,D/ActivityThread(11944): Added TimaKeyStore provider
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.165ms total 14.409ms
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 3524): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(11944): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/KLMS-2.4.521: (11944): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 11 15:38:50 GMT+01:00 2016
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/KLMS-2.4.521: (11944): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (11944): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11944): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/splitIntent( 3524): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3524): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,I/KLMS-2.4.521: (11944): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11944): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/art     ( 3524): Explicit concurrent mark sweep GC freed 8307(372KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 53MB/69MB, paused 3.643ms total 176.901ms
,I/KLMS-2.4.521: (11944): KLMSIntentService(): PACKAGE_REMOVED
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/KLMS-2.4.521: (11944): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11944): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
W/ResourcesManager(11079): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  (11961): MountEmulatedStorage()
E/Zygote  (11961): v2
I/libpersona(11961): KNOX_SDCARD checking this for 10106
I/libpersona(11961): KNOX_SDCARD not a persona
,I/SELinux (11961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11961 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (11961): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,E/Zygote  (11976): MountEmulatedStorage()
E/Zygote  (11976): v2
I/libpersona(11976): KNOX_SDCARD checking this for 1000
I/libpersona(11976): KNOX_SDCARD not a persona
,I/SELinux (11976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/SELinux (11976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider(11961): TimaSignature is unavailable
E/SELinux (11976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityThread(11961): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(11079): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(11079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11079): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/KLMS-2.4.521: (11944): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(11976): TimaSignature is unavailable
,I/KLMS-2.4.521: (11944): KLMSIntentService(): onDestroy()
,D/ActivityThread(11976): Added TimaKeyStore provider
,D/ResourcesManager(11961): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/elm:14491(11961): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(11961): ELMEngine.ELMEngine( context ).
,D/elm:14491(11961): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/Zygote  (11992): MountEmulatedStorage()
E/Zygote  (11992): v2
I/libpersona(11992): KNOX_SDCARD checking this for 10052
I/libpersona(11992): KNOX_SDCARD not a persona
,I/SELinux (11992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3524): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=11992 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,E/SELinux (11992): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/elm:14491(11961): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(11961): ElmAgentService : onCreate()
D/elm:14491(11961): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11961): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11961): MDMBridge.getInstance()
D/elm:14491(11961): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11961): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(11079): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/elm:14491(11961): ElmAgentService : onDestroy().
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11061): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11061): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11061): Clear T&P info.
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11061): Widget is not attached.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11976): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/TimaKeyStoreProvider(11992): TimaSignature is unavailable
,W/ResourcesManager(11976): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityThread(11992): Added TimaKeyStore provider
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  (12010): MountEmulatedStorage()
I/libpersona(12010): KNOX_SDCARD checking this for 10019
E/Zygote  (12010): v2
I/libpersona(12010): KNOX_SDCARD not a persona
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,I/SELinux (12010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=12010 uid=10019 gids={50019, 9997} abi=armeabi-v7a
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Books/Books.apk
D/RCPManager(11976):  in createShortcut() for packageName: com.test.thalitest userId0
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/SELinux (12010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/RCPManagerService( 3524):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3524): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
E/SELinux (12010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/Resources( 3524): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/TimaKeyStoreProvider(12010): TimaSignature is unavailable
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ActivityThread(12010): Added TimaKeyStore provider
D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/UsbSettingsManager( 3524): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3524): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/PackageManager( 3524): delete codoeFile: 
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/AASAUninstall( 3524):  com.test.thalitest not target!
,D/PackageManager( 3524): result of delete: 1{430494291}
,I/ActivityManager( 3524): Killing 10740:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/AndroidRuntime(11905): Shutting down VM
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(11992): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ActivityManager( 3524): Killing 9196:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager(11992): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(11992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
W/ResourcesManager(11992): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11992): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,W/ResourcesManager(11992): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/Videos/Videos.apk
W/ResourcesManager(11992): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/Zygote  (12026): MountEmulatedStorage()
E/Zygote  (12026): v2
I/libpersona(12026): KNOX_SDCARD checking this for 10101
I/libpersona(12026): KNOX_SDCARD not a persona
,I/SELinux (12026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (12026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3524): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=12026 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (12026): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 10812:com.osp.app.signin/u0a45 (adj 13): bgCount ##31
,D/ResourcesManager(11079): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3524): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Books/Books.apk
,D/RCPManagerService( 3524): PackageReceiver onReceive()
I/HarmonyEASService( 3524): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3524): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3524): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3524): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3524): uID is 10692
V/EnterpriseBillingPolicy( 3524): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3524): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3524): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3524): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(12010): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=32_task.xml
D/TimaKeyStoreProvider(12026): TimaSignature is unavailable
,D/TaskPersister( 3524): removeObsoleteFile: deleting file=32_task_thumbnail.png
,D/ActivityThread(12026): Added TimaKeyStore provider
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 4820): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/Mms/MmsApp(11992): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(11992): init before art
,D/Mms/ArtClassLoader(11992): init [DONE] art
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PkgBroadcastIntentOp( 4820): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4820): Clearing selected account for com.test.thalitest
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/LocationSettingsChecker( 4820): Removing dialog suppression flag for package com.test.thalitest
,D/com.sec.android.service.health.upgrade.UninstallReceiver(12010): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(12010): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(12010): onReceive() : package name is not s health. Return !!!
,D/Mms/TelephonyPermission(11992): start operation mode monitor
,D/ResourcesManager(11992): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(11992): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/LocationWidgetApplication(11079): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(12026): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/NetworkScheduler.SchedulerReceiver( 4667): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4667): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/Mms/TelephonyPermission(11992): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(11992): isDefault true
,D/Mms/MmsApp(11992): onCreate() com.android.mms
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  (12049): MountEmulatedStorage()
I/libpersona(12049): KNOX_SDCARD checking this for 1000
E/Zygote  (12049): v2
I/libpersona(12049): KNOX_SDCARD not a persona
I/SELinux (12049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=12049 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (12049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12049): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Killing 10841:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/Mms/MmsApp(11992): [start]    initCountryIso consume time = 122.909333
,D/DocsApplication(12026): Installing DEX configuration.
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/CountryDetector( 3524): The first listener is added
,D/TimaKeyStoreProvider(12049): TimaSignature is unavailable
,D/ActivityThread(12049): Added TimaKeyStore provider
,D/DexInstaller(12026): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper(12026): Provided clientMode=RELEASE, packageInfo=PackageInfo{2be76725 com.google.android.apps.docs}
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
D/Mms/MmsApp(11992): [end]    initCountryIso consume time = 27.602584
D/Mms/MmsConfig(11992): [start]    MmsConfig.init() consume time = 0.164458
,D/TAG     (12026): onCreate()
,D/CrossAppStateProvider(12026): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/Mms/MmsConfig(11992): before partial update
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/Icing   ( 4820): doRemovePackageData com.test.thalitest
,D/Mms/MmsConfig(11992): Load Resize quality : 80
,D/Mms/MmsConfig(11992):  enable multiwindow = true
,D/ResourcesManager(12049): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/WearableController( 4820): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ResourcesManager(11079): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/PCWCLIENTTRACE_LOG(12049): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(12049): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(12049): new DMDBOpenHelper instance
,E/Mms/MessageUtils(11992): setCountryDetector : update country detector info 
,E/SQLiteLog( 4820): (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
E/Mms/MessageUtils(11992): updateCountryIso : update country iso info 
,E/SQLiteLog(12049): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4820): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4820): 	at com.google.android.gms.googlehelp.metrics.c.a(:com.google.android.gms:99)
E/SQLiteDatabase( 4820): 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
E/SQLiteDatabase( 4820): 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:277)
E/SQLiteDatabase( 4820): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
E/SQLiteDatabase( 4820): 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
E/SQLiteDatabase( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4820): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase(12049): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12049): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(12049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(12049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(12049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(12049): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(12049): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(12049): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(12049): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(12049): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(12049): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(12049): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(12049): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(12049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12049): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(12049): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(12049): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(12049): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(12049): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(12049): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(12049): Shutting down VM
E/SQLiteOpenHelper( 4820): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4820): 	at com.google.android.gms.googlehelp.metrics.c.a(:com.google.android.gms:99)
E/SQLiteOpenHelper( 4820): 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
E/SQLiteOpenHelper( 4820): 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:277)
E/SQLiteOpenHelper( 4820): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
E/SQLiteOpenHelper( 4820): 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
E/SQLiteOpenHelper( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4820): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 4820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime(12049): FATAL EXCEPTION: main
E/AndroidRuntime(12049): Process: com.sec.pcw.device, PID: 12049
E/AndroidRuntime(12049): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12049): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(12049): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(12049): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(12049): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(12049): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(12049): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12049): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12049): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(12049): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(12049): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(12049): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(12049): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(12049): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(12049): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(12049): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(12049): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(12049): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(12049): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(12049): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(12049): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(12049): 	... 11 more
W/SQLiteOpenHelper( 4820): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 4820): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4820): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 4820): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
D/gH_CompatibleDatabase( 4820): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/Mms/PackageInfo(11992): com.sec.imsservice is not installed
D/Mms/MmsConfig(11992): [end]    init() consume time = 109.109208
D/Mms/Contact(11992): [start]    init() consume time = 1.117167
D/ResourcesManager(11079): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop191.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,D/TP/MmsSmsProvider( 3982): query,matched:13, calling pid = 11992
D/TP/MmsSmsProvider( 3982): match 13:Elapsed time : 1.549 ms
D/Mms/Contact(11992): [end]    init consume time = 18.864292
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/Mms/DraftCache(11992): [start]    rebuildCache consume time = 2.042375
D/TP/MmsSmsProvider( 3982): query,matched:12, calling pid = 11992
D/TP/MmsSmsProvider( 3982): match 12:Elapsed time : 1.615 ms
D/ResourcesManager(11079): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
E/Zygote  (12079): MountEmulatedStorage()
E/Zygote  (12079): v2
I/libpersona(12079): KNOX_SDCARD checking this for 10035
I/libpersona(12079): KNOX_SDCARD not a persona
I/SELinux (12079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3524): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=12079 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux (12079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (12079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
I/Process (12049): Sending signal. PID: 12049 SIG: 9
D/UsbHostManager( 3524): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3524): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3524): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3524): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3524): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3524): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3524): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/Mms/TelephonyUtils(11992): getSubId from simSlot 0, return Value = -1
,I/GCore-Chimera-Crash( 4820): Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
,D/Mms/DownloadManager(11992): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11992): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11992): auto download without roaming -> true
D/Mms/DownloadManager(11992): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(11992): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(11992): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(11992): roaming -> false (slotId = 1)
D/Mms/DownloadManager(11992): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(11992): auto download without roaming -> true
D/Mms/DownloadManager(11992): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(11992): auto download during roaming secondary -> false
D/Mms/DownloadManager(11992): mAutoDownload ------> true
,I/ActivityManager( 3524): Killing 10882:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/Mms/DraftCache(11992): [end]    rebuildCache consume time = 49.106083
,D/TimaKeyStoreProvider(12079): TimaSignature is unavailable
,D/ActivityThread(12079): Added TimaKeyStore provider
,D/MtpClient(11321): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(11321): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/Mms/MmsApp(11992): [end]    onCreate() consume time = 7.289958
,D/Mms/FreeMessageStatusReceiver(11992): onReceive, action : android.intent.action.PACKAGE_REMOVED
,I/GCore-Chimera-Crash( 4820): 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDMwKRjO36UR
I/GCore-Chimera-Crash( 4820): IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
I/GCore-Chimera-Crash( 4820): ==
I/GCore-Chimera-Crash( 4820): GCore-Chimera-Crash
,E/AndroidRuntime( 4820): FATAL EXCEPTION: IntentService[ClearHelpHistoryChimeraIntentService]
E/AndroidRuntime( 4820): Process: com.google.android.gms, PID: 4820
E/AndroidRuntime( 4820): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4820): 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:280)
E/AndroidRuntime( 4820): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
E/AndroidRuntime( 4820): 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
E/AndroidRuntime( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4820): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Mms/DownloadManager(11992): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(11992): roaming ------> false, mSimSlot = 0
,D/Mms/Conversation(11992): [start]    init() consume time = 10.221584
,D/Mms/TelephonyUtils(11992): getSubId from simSlot 0, return Value = -1
,D/UsbHostManager( 3524): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3524): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/Mms/DownloadManager(11992): roaming -> false (slotId = 0)
D/Mms/DownloadManager(11992): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(11992): auto download without roaming -> true
D/Mms/DownloadManager(11992): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(11992): mAutoDownload ------> true
,I/TactileAssist( 3524): enable value -1
I/TactileAssist( 3524): internal enable value -1
I/TactileAssist( 3524): intensity value -1
I/TactileAssist( 3524): saveAppList value true
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk,
,D/Mms/FreeMessageReceiverService(11992): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(11992): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/EventHub( 3524): Removing device '/dev/input/event10' due to inotify event
,I/TactileAssist( 3524): List of disabled apps :
,I/ActivityManager( 3524): Process com.sec.pcw.device (pid 12049)(adj 9) has died(301,986)
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
,I/art     ( 4667): Explicit concurrent mark sweep GC freed 86814(4MB) AllocSpace objects, 35(1447KB) LOS objects, 34% free, 30MB/46MB, paused 2.994ms total 97.459ms
,D/TP/MmsSmsProvider( 3982): deleteConversation threadId: 9223372036854775807
,I/EventHub( 3524): Removing device '/dev/input/event7' due to inotify event
,I/Process ( 4820): Sending signal. PID: 4820 SIG: 9
,I/FeatureConfig(12079): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/EventHub( 3524): Removing device '/dev/input/event8' due to inotify event
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(11079): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/EventHub( 3524): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (12107): MountEmulatedStorage()
,E/Zygote  (12107): v2
I/libpersona(12107): KNOX_SDCARD checking this for 10059
I/libpersona(12107): KNOX_SDCARD not a persona
,I/SELinux (12107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/PowerManagerService( 3524): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10014, pid=4820, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=327)
,D/ConnectivityService( 3524): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@24ac7f04)
,I/SELinux (12107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12107): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3524): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=12107 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
D/ConnectivityService( 3524): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3524): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager( 3524): Process com.google.android.gms (pid 4820)(adj 5) has died(351,987)
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10997ms
,I/EventHub( 3524): Removing device '/dev/input/event11' due to inotify event
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.chimera.GmsIntentOperationService in 10996ms
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10995ms
,W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10994ms
W/ActivityManager( 3524): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20994ms
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TimaKeyStoreProvider(12107): TimaSignature is unavailable
,D/ActivityThread(12107): Added TimaKeyStore provider
,W/ResourcesManager(12079): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager(12079): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/EventHub( 3524): Removing device '/dev/input/event12' due to inotify event
,W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(12079): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12107): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(12107): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(12079): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/EventHub( 3524): Removing device '/dev/input/event13' due to inotify event
,D/ResourcesManager(12079): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(12079): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/SQLiteLog( 9960): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 9960): (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,D/Compatibility(12107): onReceive() it will make start service
E/Zygote  (12127): MountEmulatedStorage()
E/Zygote  (12127): v2
I/libpersona(12127): KNOX_SDCARD checking this for 10039
I/libpersona(12127): KNOX_SDCARD not a persona
,I/PowerManagerService( 3524): [PWL] Off : 105s ago
E/SQLiteQuery( 9960): exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
I/SELinux (12127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3524): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=12127 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/EventHub( 3524): Removing device '/dev/input/event14' due to inotify event
,I/SELinux (12127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (12127): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12079): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/AndroidRuntime( 9960): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 9960): Process: com.sec.android.app.shealth, PID: 9960
E/AndroidRuntime( 9960): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 9960): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
E/AndroidRuntime( 9960): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
E/AndroidRuntime( 9960): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
E/AndroidRuntime( 9960): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
E/AndroidRuntime( 9960): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:147)
E/AndroidRuntime( 9960): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:136)
E/AndroidRuntime( 9960): 	at android.content.ContentResolver.query(ContentResolver.java:503)
E/AndroidRuntime( 9960): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime( 9960): 	at com.sec.android.app.shealth.framework.ui.data.AppRegistryDbManagerWithProvider.deleteAppRegistryData(Unknown Source)
E/AndroidRuntime( 9960): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:66)
E/AndroidRuntime( 9960): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 9960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 9960): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 9960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Compatibility(12107): onHandleIntent()
,D/Compatibility(12107): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10692, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,V/ApplicationPolicy( 3524): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
,D/Compatibility(12107): found: 2
,D/TimaKeyStoreProvider(12127): TimaSignature is unavailable
,E/DropBoxManagerService( 3524): Can't write: system_app_crash
E/DropBoxManagerService( 3524): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3524): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3524): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3524): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3524): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3524): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3524): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3524): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3524): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3524): 	... 5 more
D/ActivityThread(12127): Added TimaKeyStore provider
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12079): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4057): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility(12107): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(12107): skipping ResolveInfo{1e9260fa com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(12107): considering ResolveInfo{193ba6ab com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(12107): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(12107): enabling receiver ResolveInfo{3e704108 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility(12107): enabling receiver ResolveInfo{1dcc50a1 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/Process ( 9960): Sending signal. PID: 9960 SIG: 9
,D/ResourcesManager(12079): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(12127): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3524): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager(12079): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12079): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
