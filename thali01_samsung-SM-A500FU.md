#### Test 61248225a3bd1fe_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/SettingsProvider( 1015): name = vibrate_in_silent
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/CscReceiver( 1453): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1453): Recieve Sim State Changed : ABSENT
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
--------- beginning of system
W/ResourcesManager( 1453): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/splitIntent( 1015): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1015): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/BroadcastQueue( 1015): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1453, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TEST    ( 1175): run!!!
I/WifiApBroadcastReceiver( 1365): onReceive: action android.intent.action.SIM_STATE_CHANGED
E/Zygote  ( 2325): MountEmulatedStorage()
E/Zygote  ( 2325): v2
I/SELinux ( 2325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
I/libpersona( 2325): KNOX_SDCARD checking this for 1000
I/libpersona( 2325): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2325 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
I/SELinux ( 2325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/GeometricMosaic_Renderer( 1175): setBackgroundBitmap
E/Zygote  ( 2332): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2332): v2
I/libpersona( 2332): KNOX_SDCARD checking this for 1000
I/libpersona( 2332): KNOX_SDCARD not a persona
I/SELinux ( 2332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/BootupListener( 1453): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/TimaKeyStoreProvider( 2325): TimaSignature is unavailable
D/SettingsProvider( 1015): name = internet_call_settings_visibility
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1001
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/ActivityThread( 2325): Added TimaKeyStore provider
D/SettingsProvider( 1015): ret = -1
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2332): TimaSignature is unavailable
D/ActivityThread( 2332): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/PhoneUtilsCommon( 1453): isSupportVoLTE is false.
E/Zygote  ( 2355): MountEmulatedStorage()
I/libpersona( 2355): KNOX_SDCARD checking this for 10046
E/Zygote  ( 2355): v2
I/libpersona( 2355): KNOX_SDCARD not a persona
I/SELinux ( 2355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2355): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2355 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/StatusChecker( 2325): onReceive : android.intent.action.SIM_STATE_CHANGED
D/TimaKeyStoreProvider( 2355): TimaSignature is unavailable
D/ActivityThread( 2355): Added TimaKeyStore provider
I/StatusChecker( 2325): onReceive : net.mt.init : 
D/StatusChecker( 2325): onReceive : preference initializing
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2355): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2355): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2355): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2355): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2355): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2355): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 2373): MountEmulatedStorage()
I/libpersona( 2373): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2373): v2
I/libpersona( 2373): KNOX_SDCARD not a persona
I/SELinux ( 2373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2373): TimaSignature is unavailable
D/ActivityThread( 2373): Added TimaKeyStore provider
E/Zygote  ( 2388): MountEmulatedStorage()
E/Zygote  ( 2388): v2
I/libpersona( 2388): KNOX_SDCARD checking this for 1000
I/libpersona( 2388): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2388): TimaSignature is unavailable
D/ActivityThread( 2388): Added TimaKeyStore provider
I/Omc:Receiver( 2373): onReceive : android.intent.action.SIM_STATE_CHANGED
I/Omc:OmcData( 2373): omc.xml not exist
I/Omc:Receiver( 2373): OM Customize disabled
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2403): MountEmulatedStorage()
E/Zygote  ( 2403): v2
I/libpersona( 2403): KNOX_SDCARD checking this for 10131
I/libpersona( 2403): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2403 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/Mms/MmsApp( 2355): [start]    onCreate() consume time = 0.0
I/SELinux ( 2403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/art     (  315): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 22.574ms
E/USB_UICC(  303): Timeout! No signal received. Retry num = 21
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 943us total 21.081ms
D/TimaKeyStoreProvider( 2403): TimaSignature is unavailable
D/ActivityThread( 2403): Added TimaKeyStore provider
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 594us total 20.724ms
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/Zygote  ( 2418): MountEmulatedStorage()
E/Zygote  ( 2418): v2
I/libpersona( 2418): KNOX_SDCARD checking this for 1000
I/libpersona( 2418): KNOX_SDCARD not a persona
I/SELinux ( 2418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2418 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ResourcesManager( 2403): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2403): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2403): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2403): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2418): TimaSignature is unavailable
D/ActivityThread( 2418): Added TimaKeyStore provider
D/SBrowserFeatureFlag( 2403): initialized in static block : loadCscFeatureValue() succeed! 
W/art     ( 2355): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 107.276ms
D/ManifestProvider( 2403): onCreate()
E/OperatorBookmarksSIMReceiver( 2403): onReceive runs..android.intent.action.SIM_STATE_CHANGED
D/Mms/ArtClassLoader( 2355): init before art
D/Mms/TelephonyPermission( 2355): start operation mode monitor
W/ResourcesManager( 2355): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2355): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2355): isDefault true
D/Mms/MmsApp( 2355): onCreate() com.android.mms
D/Mms/MmsApp( 2355): [start]    initCountryIso consume time = 498.378542
D/CountryDetector( 1015): The first listener is added
D/Mms/MmsApp( 2355): [end]    initCountryIso consume time = 13.085365
D/Mms/MmsConfig( 2355): [start]    MmsConfig.init() consume time = 0.601822
D/Mms/MmsConfig( 2355): before partial update
D/Mms/MmsConfig( 2355): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2355): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2355): isAuth is false
D/Mms/MmsConfig( 2355): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1453): query,matched:2117, calling pid = 2355
D/TP/MmsSmsProvider( 1453): match 2117:Elapsed time : 3.439 ms
D/EasySignUpManager_1.0.1( 2355): isAuth is false
D/EasySignUpManager_1.0.1( 2355): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2355): mps_code.dat does not exist
E/CscParser( 2355): customer_path =/system/csc/customer.xml
E/CscParser( 2355): fileName + /system/csc/customer.xml
E/CscParser( 2355): mps_code.dat does not exist
E/CscParser( 2355): customer_path =/system/csc/customer.xml
E/CscParser( 2355): fileName + /system/csc/customer.xml
D/CscParser( 2355): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2355):  enable multiwindow = true
E/Mms/MessageUtils( 2355): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2355): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 2355): [end]    init() consume time = 126.837448
D/Mms/Contact( 2355): [start]    init() consume time = 1.537084
D/Mms/Contact( 2355): [end]    init consume time = 10.217916
D/TP/MmsSmsProvider( 1453): query,matched:13, calling pid = 2355
D/TP/MmsSmsProvider( 1453): match 13:Elapsed time : 1.916 ms
D/Mms/DraftCache( 2355): [start]    rebuildCache consume time = 8.221094
D/TP/MmsSmsProvider( 1453): query,matched:12, calling pid = 2355
D/TP/MmsSmsProvider( 1453): match 12:Elapsed time : 1.388 ms
D/Mms/DraftCache( 2355): [end]    rebuildCache consume time = 9.3575
D/Mms/MethodReflector( 2355): getSubId is called
D/Mms/TelephonyUtils( 2355): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2355): getTelephonyProperty is called
D/Mms/DownloadManager( 2355): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2355): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2355): auto download without roaming -> true
D/Mms/DownloadManager( 2355): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2355): getSubId is called
D/Mms/MethodReflector( 2355): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2355): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2355): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2355): getTelephonyProperty is called
D/Mms/DownloadManager( 2355): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2355): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2355): auto download without roaming -> true
D/Mms/DownloadManager( 2355): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2355): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2355): mAutoDownload ------> true
D/ComposerPerformance( 2355): 1456842781613 ms / [DONE] Composer constructor
D/Mms/Conversation( 2355): [start]    init() consume time = 80.846667
D/TP/MmsSmsDatabaseHelper( 1453): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1453): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1453): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1453): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1453): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1453): deleteConversation threadId: 9223372036854775807
E/CII     ( 2355): CommonIMSInterface: VoLTE CSC feature disabled.
D/TP/MmsSmsProvider( 1453): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
I/Mms/ReservationManager( 2355): ReservationManager()
I/Mms/ReservationManager( 2355): resetAfterConnected()
V/TP/MmsSmsDatabaseHelper( 1453): updateThread(), thread_id = 9223372036854775807
D/TP/MmsSmsProvider( 1453): query,matched:7, calling pid = 2355
V/TP/MmsSmsDatabaseHelper( 1453): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1453): match 7:Elapsed time : 8.064 ms
D/TP/MmsSmsProvider( 1453): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
D/Mms/Conversation( 2355): [end]    init consume time = 35.341041
I/Mms/ReservationManager( 2355): getReservedSendMessageCount(): retMessageCount=0
D/Mms/ArtClassLoader( 2355): init [DONE] art
D/Mms/MessagingNotification( 2355): [start]    init() consume time = 6.179532
D/Mms/MessagingNotification( 2355): [end]    init consume time = 1.785885
D/Mms/MmsApp( 2355): [end]    onCreate() consume time = 1.771302
D/Mms/SmsReceiver( 2355): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
D/Mms/SpamFilter( 2355): [start]    SpamFilter fill() begin consume time = 3.075104
D/TP/MmsSmsProvider( 1453): query,matched:0, calling pid = 2355
V/TP/MmsSmsProvider( 1453): getSimpleConversations entered.
D/Mms/Synchronizer( 2355): [start]    doSync consume time = 1.751615
D/TP/MmsSmsProvider( 1453): update, matched:300, calling pid = 2355
V/TP/MmsSmsProvider( 1453): syncDBData start
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
V/TP/MmsSmsProvider( 1453): syncDBData sms end
V/TP/MmsSmsProvider( 1453): syncDBData mms end
D/TP/MmsSmsProvider( 1453): match 0:Elapsed time : 5.420 ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/splitIntent( 1015): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
V/TP/MmsSmsProvider( 1453): syncDBData end
D/Mms/Synchronizer( 2355): [end]    doSync consume time = 7.100885
D/Mms/DownloadManager( 2355): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2355): roaming ------> false, mSimSlot = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TP/MmsSmsProvider( 1453): query,matched:400, calling pid = 2355
D/Mms/MethodReflector( 2355): getSubId is called
D/Mms/TelephonyUtils( 2355): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2355): getTelephonyProperty is called
D/Mms/DownloadManager( 2355): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2355): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2355): auto download without roaming -> true
D/Mms/DownloadManager( 2355): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/BootupListener( 1453): intent.getAction() = android.intent.action.SERVICE_STATE
D/Mms/SpamFilter( 2355): [end]    SpamFilter fill() finished consume time = 8.050313
D/Mms/DownloadManager( 2355): mAutoDownload ------> true
D/SettingsProvider( 1015): name = internet_call_settings_visibility
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1001
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/PhoneUtilsCommon( 1453): isSupportVoLTE is false.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2325): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2325): onReceive : net.mt.init : DONE
D/Mms/SmsReceiverService( 2355): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/Mms/TelephonyPermission( 2355): isDefault true
D/Mms/SmsReceiverService( 2355): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2355): handleSIMStatus()
D/Mms/SmsReceiverService( 2355): handleSIMStatus(): SIM_STATUS = ABSENT
D/StatusChecker( 2325): Service state changed : 3 mSub-1
D/Mms/MessagingNotification( 2355): checkBadgeCount unreadCount=0 badgeCount=0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/SmsProvider( 1453): query,matched:26, calling pid = 2355
D/TP/SmsProvider( 1453): match 26:Elapsed time : 1.317 ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1453): query,matched:6, calling pid = 2355
D/TP/MmsSmsProvider( 1453): match 6:Elapsed time : 1.153 ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 2443): 
D/AndroidRuntime( 2443): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2443): CheckJNI is OFF
D/AndroidRuntime( 2443): readGMSProperty: start
D/AndroidRuntime( 2443): readGMSProperty: already setted!!
D/AndroidRuntime( 2443): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2443): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2443): readGMSProperty: end
D/AndroidRuntime( 2443): addProductProperty: start
E/Zygote  ( 2450): MountEmulatedStorage()
E/Zygote  ( 2450): v2
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2450 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/libpersona( 2450): KNOX_SDCARD checking this for 10025
I/libpersona( 2450): KNOX_SDCARD not a persona
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/SELinux ( 2450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/SELinux ( 2450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.110/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TimaKeyStoreProvider( 2450): TimaSignature is unavailable
D/ActivityThread( 2450): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ResourcesManager( 2450): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2472): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2472 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/Zygote  ( 2472): v2
I/libpersona( 2472): KNOX_SDCARD checking this for 10020
I/libpersona( 2472): KNOX_SDCARD not a persona
I/SELinux ( 2472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2472): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2472): TimaSignature is unavailable
D/ActivityThread( 2472): Added TimaKeyStore provider
E/USB_UICC(  303): Timeout! No signal received. Retry num = 22
I/WifiNative-HAL( 1015): startHal
W/ResourcesManager( 2472): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
E/wifi    ( 1015): getStaticLongField sWifiHalHandle 0x9c8e68bc
W/ResourcesManager( 2472): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/WifiNative-HAL( 1015): Could not start hal
W/ResourcesManager( 2472): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/SMD     (  294): DCD OFF
E/AffinityControl( 2443): AffinityControl: registerfunction enter
D/AndroidRuntime( 2443): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1479): onPause
D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1479
D/AndroidRuntime( 2443): Shutting down VM
I/OMACP   ( 2450): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 2490): MountEmulatedStorage()
E/Zygote  ( 2490): v2
I/libpersona( 2490): KNOX_SDCARD checking this for 10174
I/libpersona( 2490): KNOX_SDCARD not a persona
I/SELinux ( 2490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/Omacp( 2355): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/SELinux ( 2490): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2490 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
V/ActivityThread( 1479): updateVisibility : ActivityRecord{3c5e40af token=android.os.BinderProxy@18e39c22 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
D/TimaKeyStoreProvider( 2490): TimaSignature is unavailable
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
D/ActivityThread( 2490): Added TimaKeyStore provider
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 2450): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/Launcher.HomeView( 1479): onStop
V/ActivityThread( 1479): updateVisibility : ActivityRecord{3c5e40af token=android.os.BinderProxy@18e39c22 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1015): isKioskContainerExistOnDevice
V/VibratorService( 1015): hasVibrator - useVibetonz: true
D/Launcher( 1479): onTrimMemory. Level: 20
D/EasySignUpManager_1.15.0305( 2472): serviceId : 0, features : -1
I/splitIntent( 1015): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
I/splitIntent( 1015): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2508): MountEmulatedStorage()
I/libpersona( 2508): KNOX_SDCARD checking this for 10044
E/Zygote  ( 2508): v2
I/libpersona( 2508): KNOX_SDCARD not a persona
I/WebViewFactory( 2490): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/SELinux ( 2508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2508 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 2508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1015): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1015): mCursor = null
D/SecContentProvider2( 1015): isCopyContactToSimAllowed = true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/LibraryLoader( 2490): Time to load native libraries: 2 ms (timestamps 9162-9164)
I/LibraryLoader( 2490): Expected native library version number "",actual native library version number ""
E/Zygote  ( 2521): MountEmulatedStorage()
I/libpersona( 2521): KNOX_SDCARD checking this for 10088
E/Zygote  ( 2521): v2
I/libpersona( 2521): KNOX_SDCARD not a persona
I/SELinux ( 2521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2521 uid=10088 gids={50088, 9997} abi=armeabi-v7a
I/SELinux ( 2521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2521): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2508): TimaSignature is unavailable
D/ActivityThread( 2508): Added TimaKeyStore provider
W/art     ( 2443): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/WebViewChromiumFactoryProvider( 2490): Binding Chromium to main looper Looper (main, tid 1) {2d98fbe7}
I/LibraryLoader( 2490): Expected native library version number "",actual native library version number ""
I/chromium( 2490): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2541 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 2541): MountEmulatedStorage()
I/libpersona( 2541): KNOX_SDCARD checking this for 10142
E/Zygote  ( 2541): v2
I/libpersona( 2541): KNOX_SDCARD not a persona
,I/SELinux ( 2541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2541): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/TimaKeyStoreProvider( 2521): TimaSignature is unavailable
,D/ActivityThread( 2521): Added TimaKeyStore provider
,I/BrowserStartupController( 2490): Initializing chromium process, singleProcess=true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1015): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/art     ( 2490): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2490): ApplicationContext is null in ApplicationStatus
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,W/ResourcesManager( 2508): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2508): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2508): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2508): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2508): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2508): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2508): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2508): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/Zygote  ( 2558): MountEmulatedStorage()
E/Zygote  ( 2558): v2
I/libpersona( 2558): KNOX_SDCARD checking this for 10054
I/libpersona( 2558): KNOX_SDCARD not a persona
,I/SELinux ( 2558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2558): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2558 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2541): TimaSignature is unavailable
,D/ActivityThread( 2541): Added TimaKeyStore provider
,W/chromium( 2490): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2490): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2490): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 2490): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2490): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2490): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2490): Local Branch: 
I/Adreno-EGL( 2490): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2490): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2490):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/TimaKeyStoreProvider( 2558): TimaSignature is unavailable
,D/ActivityThread( 2558): Added TimaKeyStore provider
,W/ResourcesManager( 2558): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 2541): TaskCloserActivity enter()
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/TaskCloserActivity( 2541): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
E/Zygote  ( 2576): MountEmulatedStorage()
E/Zygote  ( 2576): v2
I/libpersona( 2576): KNOX_SDCARD checking this for 10139
I/libpersona( 2576): KNOX_SDCARD not a persona
I/SELinux ( 2576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2576 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/SELinux ( 2576): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/Recents_RecreateReceiver( 2558): onReceive by home
,D/TimaKeyStoreProvider( 2576): TimaSignature is unavailable
,D/ActivityThread( 2576): Added TimaKeyStore provider
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/BluetoothAdapter( 2490): 957063481: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager( 2576): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2576): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2576): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2576): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2576): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,W/chromium( 2490): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup,
,W/art     ( 2490): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2490): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2490): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 2490): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2490): CordovaWebView is running on device made by: samsung
,W/art     ( 2490): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2490): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 46838(2MB) AllocSpace objects, 5(194KB) LOS objects, 33% free, 25MB/38MB, paused 1.973ms total 128.799ms
,D/OpenGLRenderer( 2490): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/PhoneWindow( 2490): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2490): *FMB* isFloatingMenuEnabled return false
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 23
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/NearbySource( 2508): Nearby Source Create!
,D/NearbyContext( 2508): Nearby Context Create!
,D/InputDispatcher( 1015): Focus entered window: 2490
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2490): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2490): Initialized EGL, version 1.4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {27a42505}
,D/OpenGLRenderer( 2490): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2490): Enabling debug mode 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AbsListView( 2472): Get MotionRecognitionManager
,I/ActivityManager( 1015): Displayed Component not be shown by security: +1s57ms
,W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{26f47dfd u0 com.example.hello/.MainActivity t7} time:30030
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2508): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2508): Samsung link source created
,D/MotionRecognitionService( 1015):  ssp status : false
,I/SamsungIME( 1784): getCurrentCandidateView
,I/Timeline( 2490): Timeline: Activity_idle id: android.os.BinderProxy@1d513fe2 time:30087
,W/BindingManager( 2490): Cannot call determinedVisibility() - never saw a connection for the pid: 2490
,D/ContactProvider( 2508): getAllContactInfoList Start
,D/SamsungIME( 1784): Dismiss ExpandCandiate
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2508): Receive : home resume
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 2355): ui event
,I/splitIntent( 1015): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,I/chromium( 2490): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteLog( 1228): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): start check captive portal 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ContactProvider( 2508): getAllContactInfoList End
,I/syncContacts( 2508): thread: 253, sync time = 151
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/JsMessageQueue( 2490): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,E/AndroidProtocolHandler( 2490): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/accuweather( 1736): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,I/SamsungIME( 1784): getDebugLevel  : 0x4f4c
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 11
,D/accuweather( 1736): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1736): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1736): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1736): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
D/accuweather( 1736): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1736): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1736): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1736): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1736): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 1736): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1736): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1736): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1736): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 33
,I/SamsungIME( 1784): getDebugLevel  : 0x4f4c
,E/accuweather( 1736): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1784): KeybaordView init() : load resources
,D/accuweather( 1736): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1736): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1736): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1736): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1736): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1736): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1736): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1736): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/dhcpcd  ( 2223): wlan0: sending IPv6 Router Solicitation
I/SamsungIME( 1784): getCurrentKeyboard
I/SamsungIME( 1784): getTextKeyboard
,D/accuweather( 1736): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/accuweather( 1736): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/SamsungIME( 1784): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1305): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1305): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/jxcore_app_log( 2490): JniHelper::setJavaVM(0xb817a450), pthread_self() = -1200789952
,D/JX-Cordova( 2490): jxcore cordova android initializing
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/jxcore-log( 2490): Initializing JXcore engine
W/jxcore-log( 2490): JXcore engine is ready
,W/jxcore-log( 2490): Starting JXcore engine
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/Mms/MmsApp( 2355):  start initViewCache mms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SIP     ( 1453): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/Mms/ComposeMessageFragment( 2355): [start]    fillCache consume time = 1987.525884
D/Mms/ComposeMessageFragment( 2355): fillCache, easy = false
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/File    ( 1453): fail readDirectory() errno=2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/audit   ( 1957): type=1400 msg=audit(1456842783.721:205): avc:  denied  { ioctl } for  pid=2490 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1957):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1957): type=1300 msg=audit(1456842783.721:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=bebb1d58 items=0 ppid=315 ppcomm=main pid=2490 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1957): type=1320 msg=audit(1456842783.721:205): 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1901): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/AbsListView( 2355): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 2355): [end]    fillCache consume time = 139.94698
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 2490): Platform android
W/jxcore-log( 2490): 
,W/jxcore-log( 2490): Process ARCH arm
W/jxcore-log( 2490): 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/art     ( 2355): Suspending all threads took: 10.235ms
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
E/USB_UICC(  303): Timeout! No signal received. Retry num = 24
,I/jxcore-log( 2490): JXcore Cordova bridge is ready!
I/jxcore-log( 2490): 
,W/jxcore-log( 2490): JXcore engine is started
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1305): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1305): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,E/jxcore-log( 2490): >> samsung-SM-A500FU
E/jxcore-log( 2490): 
,I/jxcore-log( 2490): Total memory 1983791104
I/jxcore-log( 2490): 
,I/jxcore-log( 2490): Free memory 399867904
I/jxcore-log( 2490): 
I/jxcore-log( 2490): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2490): 
I/jxcore-log( 2490): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2490): 
,I/jxcore-log( 2490): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2490): 
,I/jxcore-log( 2490): Size 720 1280
I/jxcore-log( 2490): 
,I/jxcore-log( 2490): Screen Brightness 60
I/jxcore-log( 2490): 
,E/jxcore-log( 2490): Dummy Error Log.
E/jxcore-log( 2490): 
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:750 [0:0] Cncl30MinRftAl
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1058 [0:0] chkNW: true
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:1056 [0:0] == cityListItem Size : 0
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:904 [0:0] MR pcknme : Manual systemui
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:257 [0:0] == rCL 1456842784028
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> RM:273 [0:0] EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
,D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
,D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:1895 [0:0] MCL getLLoc@
D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
,D/Mms/BubbleViewCache( 2355): fillCache bubble = 1
,D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr!!
,D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:1956 [0:0] PrvdrErr getPerformLoc:true
,D/daemonapp( 1305): [MSC_Daemon]>>> WMCL:1958 [0:0] MCL pfL set:f
,D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl,
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1456842784084
D/daemonapp( 1305): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1456864384072
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1305): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1456864380000
,D/daemonapp( 1305): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1456864380000
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1456864380000
,D/daemonapp( 1305): [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:1314 [0:0] CL@AtRfr = 3
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:1321 [0:0]  AR_lasttime: 1456864380000,
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1615 [0:0] util getnext by widget 1456864380000
D/daemonapp( 1305): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1456864380000
,E/Zygote  ( 2642): MountEmulatedStorage()
E/Zygote  ( 2642): v2
I/libpersona( 2642): KNOX_SDCARD checking this for 1000
I/libpersona( 2642): KNOX_SDCARD not a persona
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
D/daemonapp( 1305): [MSC_Daemon]>>> RM:1332 [0:0] NextTime       :1456864380000
D/daemonapp( 1305): [MSC_Daemon]>>> AWCLRH:242 [0:0] rLH /on rciclf
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:1480 [0:0]  retryCityIdCurrentlocationfail getRefreshType : 3
D/daemonapp( 1305): [MSC_Daemon]>>> RM:1491 [0:0] send broad cast error to clock
,I/SELinux ( 2642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2642 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2642): TimaSignature is unavailable
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityThread( 2642): Added TimaKeyStore provider
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SamsungIME( 1784): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,I/Scheduler( 1901): Use legacy PeriodicScheduler
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
D/daemonapp( 1305): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1305): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1305): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/AdaptiveEventManager( 1175): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/AdaptiveEventManager( 1175): currentCityId is null
D/AdaptiveEventManager( 1175): NetWork disabled : Don't refresh weather info : 201
D/AdaptiveEventManager( 1175): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1175): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1175): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1175): mWeatherInfo is not reliable
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,E/daemonapp( 1305): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1305): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 201
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2642):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2642):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,W/InstanceID/Rpc( 1901): Found 10012
,E/Zygote  ( 2658): MountEmulatedStorage()
E/Zygote  ( 2658): v2
I/libpersona( 2658): KNOX_SDCARD checking this for 10135
I/libpersona( 2658): KNOX_SDCARD not a persona
,I/SELinux ( 2658): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2658): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2658): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2658 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/daemonapp( 1305): [MSC_Daemon]>>> WDBH:4086 [0:0] ud SLS false
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:1344 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
D/daemonapp( 1305): [MSC_Daemon]>>> RM:1349 [0:0] =======RefreshType:1 End RetThd Current===========
D/daemonapp( 1305): [MSC_Daemon]>>> RM:1236 [0:0] resetRefreshThread : 0
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SecurityLogAgent( 2642):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2642): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1305): [MSC_Daemon]>>> RM:1441 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
D/daemonapp( 1305): [MSC_Daemon]>>> RM:1353 [0:0] send broad cast to clock Cur
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,I/art     (  315): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 24.383ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2642): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 2642): FileZippingService : file path =  /data/misc/audit/audit.old
,D/TimaKeyStoreProvider( 2658): TimaSignature is unavailable
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 759us total 20.037ms
D/ActivityThread( 2658): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 33.309ms
,E/Zygote  ( 2674): MountEmulatedStorage()
,E/Zygote  ( 2674): v2
I/libpersona( 2674): KNOX_SDCARD checking this for 1000
I/libpersona( 2674): KNOX_SDCARD not a persona
I/SELinux ( 2674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1015): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2674 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/SecurityLogAgent( 2642): FileZippingService : onPremise disabled. Zipping..  
,W/ResourcesManager( 2658): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2658): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2658): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2674): TimaSignature is unavailable
,D/ActivityThread( 2674): Added TimaKeyStore provider
,D/SecurityLogAgent( 2642): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2642): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2642): DenialLogFileZipCreator File existence : true audit.old file size 631
,D/SecurityLogAgent( 2642): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2642): FileZippingService : completed task. Returning wakelock . 
,W/ContextImpl( 2674): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2691): MountEmulatedStorage(),
E/Zygote  ( 2691): v2
I/libpersona( 2691): KNOX_SDCARD checking this for 1000
I/libpersona( 2691): KNOX_SDCARD not a persona
,I/SELinux ( 2691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2691 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2691): TimaSignature is unavailable
,D/ActivityThread( 2691): Added TimaKeyStore provider,
,W/ResourcesManager( 2691): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/jxcore-log( 2490): getBuffer is called!!!!
I/jxcore-log( 2490): 
,D/FactoryTestApp( 2691): [FactoryTestBroadcastReceiver$onReceive](2691) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2691): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2691): [XMLDataStorage$parseXML](2691) is Live Demo : false
,D/FactoryTestApp( 2691): [XMLDataStorage$parseXML](2691) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2691): [XMLDataStorage$parseXML](2691) deviceXML=a5ulte.dat
D/FactoryTestApp( 2691): [XMLDataStorage$parseXML](2691) nameXML=a5ultexx.dat
,D/FactoryTestApp( 2691): [XMLDataStorage$parseAsset](2691) parseAsset Is Started
,I/FactoryTestApp( 2691): [XMLDataStorage$parseAsset](2691) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2691): [XMLDataStorage$parseAsset](2691) Decode base file: factory.dat
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FACTORY_TEST_APP
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FAILHIST_VERSION
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=MODEL_NAME
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=MODEL_NUMBER
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=CHIPSET_NAME
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=DEVICE_TYPE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=BATT_TYPE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PANEL_TYPE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SPEAKER_COUNT
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=MIC_COUNT
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_LTE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_DUAL_STANBY_ONE_CP
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_RCV
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_EPEN
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HW_VER_EFS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_AP_EX_THERM_ADC
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_MULTI_SIM_FRAMEWORK
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_DSDS_MSIMM_CHECK
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FONT_SIZE
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=RAM_SIZE_IF
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=MULTI_TSK_THD
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=NEED_LPA_MODE_SET
D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_POWER
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_HOME
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_BACK
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_TEST_VIEW_TABLE,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SEMI_KEY_TEST_VOLUME_UP,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SEMI_KEY_TEST_VOLUME_DOWN,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SEMI_KEY_TEST_HOME,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_KEY_TEST_THRESHOLD,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_TSP_STANDARD_CHANNEL,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_SENSOR_TEST_ACC_REVERSE,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_GEOMAGNETIC_ALPS_CAL,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SENSOR_TEST_ACC_BIT,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=G_VECTOR_SUM_ACC_BIT,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_VIBETONZ_UNSUPPORTED,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=AT_GPSSTEST,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=AT_BATTEST_RESET_WHEN_READ,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SUPPORT_CHARGE_COUNT,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HALL_IC_TEST,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_NEW_TSP_SELFTEST_SYNAPTICS,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=READ_TARGET_GEOMAGNETIC,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_SELFTEST_MIN_MELFAS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_SELFTEST_MAX_MELFAS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=BOOTLOADER_VERSION
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=BATTERY_TEST_MODE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=BATTERY_VF_OCV
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=LPA_MODE_SET
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2691): [XMLDataStorage$redefinitionById](2691) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2691): [XMLDataStorage$parseAsset](2691) SemiFunctionMenu
,D/FactoryTestApp( 2691): [XMLDataStorage$parseAsset](2691) parseAsset Is Completed
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2691): [ModuleCommon$ModuleCommon](2691) Create ModuleCommon
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2691): [Support$Kernel.read](2691) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2691): [ModuleCommon$readFactoryMode](2691) mode: ON
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2691): [FactoryTestBroadcastReceiver$onReceive](2691) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2691): [Support$Values.getBoolean](2691) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 2691): [Support$Properties.get](2691) property=ro.factory.factory_binary
,D/FactoryTestApp( 2691): [FactoryTestBroadcastReceiver$onReceive](2691) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2691): [ModuleCommon$getFtClientEnableState](2691) result : false
I/FactoryTestApp( 2691): [ModuleCommon$connectedJIG](2691) ...
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2691): [ModuleCommon$connectedJIG](2691) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2691): [Support$Kernel.read](2691) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2691): [ModuleCommon$connectedJIG](2691) value = 1f, JIG_ON = 1C
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2691): [ModuleCommon$isConnectionModeNone](2691) mConnectionMode = gsm
I/FactoryTestApp( 2691): [ModuleCommon$isRunningFtClient](2691) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2691): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2691) start DummyFtClient service for APO
,W/ContextImpl( 2691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1015): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2691): User mode
,I/FactoryTestApp( 2691): [ModuleCommon$disableFtClient](2691) ...
,D/FactoryTestApp( 2691): [DummyFtClient$onCreate](2691) Create DummyFtClient service
I/FactoryTestApp( 2691): [XMLDataStorage$parsingXML](2691) FtClient => data parsing was completed.
D/FactoryTestApp( 2691): [DummyFtClient$onReceive](2691) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2691): [ModuleCommon$isConnectionModeNone](2691) mConnectionMode = gsm
,D/FactoryTestApp( 2691): [Support$Values.getBoolean](2691) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2691): [DummyFtClient$onStartCommand](2691) ...
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 25
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,I/WifiService( 1015): android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,E/SMD     (  294): DCD OFF
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2712): MountEmulatedStorage()
E/Zygote  ( 2712): v2
I/libpersona( 2712): KNOX_SDCARD checking this for 1002
I/libpersona( 2712): KNOX_SDCARD not a persona
I/SELinux ( 2712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2712 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 2712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/UsbDeviceManager( 1015): boot completed
D/UsbDeviceManager( 1015): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1015): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1015): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
D/UsbDeviceManager( 1015): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 2712): TimaSignature is unavailable
,D/ActivityThread( 2712): Added TimaKeyStore provider
,E/Zygote  ( 2730): MountEmulatedStorage()
,E/Zygote  ( 2730): v2
I/ActivityManager( 1015): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2730): KNOX_SDCARD checking this for 1000
I/KeyguardEffectViewUtil( 1175): set resource id
I/libpersona( 2730): KNOX_SDCARD not a persona
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SettingsProvider( 1015): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10054
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BOOT_COMPLETED
I/SELinux ( 2730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/KeyguardUpdateMonitor( 1175): handleBootCompleted()
D/KeyguardUpdateMonitor( 1175): handleBootCompleted()
,E/SELinux ( 2730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PalmMotion( 1015): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1015): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1015): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1015): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
,D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/SamsungIME( 1784): showDlgMsgBox : false true true
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 2730): TimaSignature is unavailable
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 2730): Added TimaKeyStore provider
,D/NfcService( 1439): call the applyRouting
,I/GAV4    ( 2224): Thread[GAThread,5,main]: No campaign data found.
,I/RecoverySystem( 1015): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1015): No recovery log file
,D/ActivityManager( 1015): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,E/RecoverySystem( 1015): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1015): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1015): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 2712): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 2712): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/GLSActivity( 1901): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/File    ( 2730): fail readDirectory() errno=2
,D/Reset_Reason( 1015): resetString = NPON
,V/OtaStartupReceiver( 1453): onOtaspChanged: mOtaspMode=1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 2754): MountEmulatedStorage()
E/Zygote  ( 2754): v2
I/libpersona( 2754): KNOX_SDCARD checking this for 1001
I/libpersona( 2754): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2754 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
I/SELinux ( 2754): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2754): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2754): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BluetoothA2dpSinkServiceJni( 2712): register_com_android_bluetooth_a2dp_sink
,I/BootReceiver( 1015): Copying audit failures to DropBox
I/BootReceiver( 1015): Checking for fsck errors
I/BootReceiver( 1015): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 2754): TimaSignature is unavailable
,D/ActivityThread( 2754): Added TimaKeyStore provider
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityThread( 2055): Failed to find provider info for com.android.contacts.metadata
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 24781, reason: UserStart, SyncResult: databaseError: true stats []
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SyncManager( 1015): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 64437, reason: UserStart
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ResourcesManager( 2754): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/BtSettings.ProfileConfig( 2712): Adding GattService
,D/BtSettings.ProfileConfig( 2712): Adding HeadsetService
,D/BtSettings.ProfileConfig( 2712): Adding A2dpService
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BtSettings.ProfileConfig( 2712): Adding HidService
,D/BtSettings.ProfileConfig( 2712): Adding HealthService
,D/BtSettings.ProfileConfig( 2712): Adding PanService
,D/BtSettings.ProfileConfig( 2712): Adding BluetoothMapService
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/BtSettings.ProfileConfig( 2712): Adding SapService
,D/BtSettings.ProfileConfig( 2712): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 2712): Adding A2dpSinkService
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/BtSettings.ProfileConfig( 2712): Adding SapClientService
,D/BtSettings.ProfileConfig( 2712): Adding HidDevService
,I/BtSettings.ProfileConfig( 2712): *********Initializing Bluetooth Profile Settings*******
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/GAv4-SVC( 2055): Google Analytics 8.4.89 is starting up.
,D/ActivityManager( 1015): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/FactoryTestApp( 2691): [ProtectedFactoryTestBroadcastReceiver$onReceive](2691) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2691): [ProtectedFactoryTestBroadcastReceiver$onReceive](2691) com.samsung.intent.action.SECPHONE_READY
D/FactoryTest( 2691): User mode
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/Mms/NotificationReceiver( 2355): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,D/Mms/NotificationReceiver( 2355): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2355): queue Uri = content://im/queue-messages?box=pending
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/BootReceiver( 1015): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/TP/ImProvider( 1453): im query match24
D/TP/ImProvider( 1453): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1453): ftSesstionId must be a long.
D/TP/ImProvider( 1453): getQueuedImMessages
,D/TP/ImProvider( 1453): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/Mms/NotificationReceiver( 2355):  getPendingMessageIds: no pending messages.
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/Mms/ActionsFactory( 2355): Call to GET_LAST_MESSAGES_SENT
,D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 31510, tid: 31510, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1015):     r0 b914bd48  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1015):     r4 0045b0a0  r5 be11f218  r6 b914bd48  r7 be11f228
D/CrashAnrDetector( 1015):     r8 be11ee60  r9 ba64e378  sl ba64e378  fp be11f1dc
D/CrashAnrDetector( 1015):     ip be11f228  sp be11ee58  lr a0b0030c  pc a0affd98  cpsr a00f0010
D/CrashAnrDetector( 1015):     d0  ffffff859ec62bb0  d1  0000000000000000
D/CrashAnrDetector( 1015):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1015):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1015):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1015):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1015):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1015):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1015):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1015):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1015):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1015):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1015):     scr 20000013
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1015):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1015):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1015):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          be11edd8  00000000  
D/CrashAnrDetector( 1015):          be11eddc  00000000  
D/CrashAnrDetector( 1015):          be11ede0  00000000  
D/CrashAnrDetector( 1015):          be11ede4  00000000  
D/CrashAnrDetector( 1015):          be11ede8  00000000  
D/CrashAnrDetector( 1015):          be11edec  00000000  
D/CrashAnrDetector( 1015):          be11edf0  00000000  
D/CrashAnrDetector( 1015):          be11edf4  00000000  
D/CrashAnrDetector( 1015):          be11edf8  00000000  
D/CrashAnrDetector( 1015):          be11edfc  00000000  
D/CrashAnrDetector( 1015):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1015):          be11ee04  00000000  
D/CrashAnrDetector( 1015):          be11ee08  00000000  
D/CrashAnrDetector( 1015):          be11ee0c  00000000  
D/CrashAnrDetector( 1015):          be11ee10  00000000  
D/CrashAnrDetector( 1015):          be11ee14  00000000  
D/CrashAnrDetector( 1015):          be11ee18  00000000  
D/CrashAnrDetector( 1015):          be11ee1c  00000000  
D/CrashAnrDetector( 1015):          be11ee20  00000000  
D/CrashAnrDetector( 1015):          be11ee24  00000000  
D/CrashAnrDetector( 1015):          be11ee28  00000000  
D/CrashAnrDetector( 1015):          be11ee2c  00000000  
D/CrashAnrDetector( 1015):          be11ee30  00000000  
D/CrashAnrDetector( 1015):          be11ee34  00000000  
D/CrashAnrDetector( 1015):          be11ee38  00000000  
D/CrashAnrDetector( 1015):          be11ee3c  00000000  
D/CrashAnrDetector( 1015):          be11ee40  00000000  
D/CrashAnrDetector( 1015):          be11ee44  00000000  
D/CrashAnrDetector( 1015):          be11ee48  00000000  
D/CrashAnrDetector( 1015):          be11ee4c  00000000  
D/CrashAnrDetector( 1015):          be11ee50  00000000  
D/CrashAnrDetector( 1015):          be11ee54  00000000  
D/CrashAnrDetector( 1015):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1015):          be11ee5c  00000000  
D/CrashAnrDetector( 1015):          be11ee60  00000000  
D/CrashAnrDetector( 1015):          be11ee64  00000000  
D/CrashAnrDetector( 1015):          be11ee68  00000000  
D/CrashAnrDetector( 1015):          be11ee6c  00000000  
D/CrashAnrDetector( 1015):          be11ee70  00000000  
D/CrashAnrDetector( 1015):          be11ee74  00000000  
D/CrashAnrDetector( 1015):          be11ee78  00000000  
D/CrashAnrDetector( 1015):          be11ee7c  00000000  
D/CrashAnrDetector( 1015):          be11ee80  00000000  
D/CrashAnrDetector( 1015):          be11ee84  00000000  
D/CrashAnrDetector( 1015):          be11ee88  00000000  
D/CrashAnrDetector( 1015):          be11ee8c  00000000  
D/CrashAnrDetector( 1015):          be11ee90  00000000  
D/CrashAnrDetector( 1015):          be11ee94  00000000  
D/CrashAnrDetector( 1015):          be11ee98  00000000  
D/CrashAnrDetector( 1015):          be11ee9c  00000000  
D/CrashAnrDetector( 1015):          be11eea0  00000000  
D/CrashAnrDetector( 1015):          be11eea4  00000000  
D/CrashAnrDetector( 1015):          be11eea8  00000000  
D/CrashAnrDetector( 1015):          be11eeac  00000000  
D/CrashAnrDetector( 1015):          be11eeb0  00000000  
D/CrashAnrDetector( 1015):          be11eeb4  00000000  
D/CrashAnrDetector( 1015):          be11eeb8  00000000  
D/CrashAnrDetector( 1015):          be11eebc  00000000  
D/CrashAnrDetector( 1015):       
D/CrashAnrDetector( 1015): processName:com.test.thalitest
D/CrashAnrDetector( 1015): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/SettingsProvider( 1015): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
I/BootReceiver( 1015): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 2016, tid: 2016, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1015):     r0 b926a1f0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1015):     r4 0045b0a0  r5 be11f218  r6 b926a1f0  r7 be11f228
D/CrashAnrDetector( 1015):     r8 be11ee60  r9 baf12548  sl baf12548  fp be11f1dc
D/CrashAnrDetector( 1015):     ip be11f228  sp be11ee58  lr a09c330c  pc a09c2d98  cpsr a00f0010
D/CrashAnrDetector( 1015):     d0  ffffff859e8579c0  d1  0000000000000000
D/CrashAnrDetector( 1015):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1015):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1015):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1015):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1015):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1015):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1015):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1015):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1015):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1015):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1015):     scr 20000013
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1015):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1015):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1015):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          be11edd8  00000000  
D/CrashAnrDetector( 1015):          be11eddc  00000000  
D/CrashAnrDetector( 1015):          be11ede0  00000000  
D/CrashAnrDetector( 1015):          be11ede4  00000000  
D/CrashAnrDetector( 1015):          be11ede8  00000000  
D/CrashAnrDetector( 1015):          be11edec  00000000  
D/CrashAnrDetector( 1015):          be11edf0  00000000  
D/CrashAnrDetector( 1015):          be11edf4  00000000  
D/CrashAnrDetector( 1015):          be11edf8  00000000  
D/CrashAnrDetector( 1015):          be11edfc  00000000  
D/CrashAnrDetector( 1015):     ,     be11ee00  00000000  
D/CrashAnrDetector( 1015):          be11ee04  00000000  
D/CrashAnrDetector( 1015):          be11ee08  00000000  
D/CrashAnrDetector( 1015):          be11ee0c  00000000  
D/CrashAnrDetector( 1015):          be11ee10  00000000  
D/CrashAnrDetector( 1015):          be11ee14  00000000  
D/CrashAnrDetector( 1015):          be11ee18  00000000  
D/CrashAnrDetector( 1015):          be11ee1c  00000000  
D/CrashAnrDetector( 1015):          be11ee20  00000000  
D/CrashAnrDetector( 1015):          be11ee24  00000000  
D/CrashAnrDetector( 1015):          be11ee28  00000000  
D/CrashAnrDetector( 1015):          be11ee2c  00000000  
D/CrashAnrDetector( 1015):          be11ee30  00000000  
D/CrashAnrDetector( 1015):          be11ee34  00000000  
D/CrashAnrDetector( 1015):          be11ee38  00000000  
D/CrashAnrDetector( 1015):          be11ee3c  00000000  
D/CrashAnrDetector( 1015):          be11ee40  00000000  
D/CrashAnrDetector( 1015):          be11ee44  00000000  
D/CrashAnrDetector( 1015):          be11ee48  00000000  
D/CrashAnrDetector( 1015):          be11ee4c  00000000  
D/CrashAnrDetector( 1015):          be11ee50  00000000  
D/CrashAnrDetector( 1015):          be11ee54  00000000  
D/CrashAnrDetector( 1015):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1015):          be11ee5c  00000000  
D/CrashAnrDetector( 1015):          be11ee60  00000000  
D/CrashAnrDetector( 1015):          be11ee64  00000000  
D/CrashAnrDetector( 1015):          be11ee68  00000000  
D/CrashAnrDetector( 1015):          be11ee6c  00000000  
D/CrashAnrDetector( 1015):          be11ee70  00000000  
D/CrashAnrDetector( 1015):          be11ee74  00000000  
D/CrashAnrDetector( 1015):          be11ee78  00000000  
D/CrashAnrDetector( 1015):          be11ee7c  00000000  
D/CrashAnrDetector( 1015):          be11ee80  00000000  
D/CrashAnrDetector( 1015):          be11ee84  00000000  
D/CrashAnrDetector( 1015):          be11ee88  00000000  
D/CrashAnrDetector( 1015):          be11ee8c  00000000  
D/CrashAnrDetector( 1015):          be11ee90  00000000  
D/CrashAnrDetector( 1015):          be11ee94  00000000  
D/CrashAnrDetector( 1015):          be11ee98  00000000  
D/CrashAnrDetector( 1015):          be11ee9c  00000000  
D/CrashAnrDetector( 1015):          be11eea0  00000000  
D/CrashAnrDetector( 1015):          be11eea4  00000000  
D/CrashAnrDetector( 1015):          be11eea8  00000000  
D/CrashAnrDetector( 1015):          be11eeac  00000000  
D/CrashAnrDetector( 1015):          be11eeb0  00000000  
D/CrashAnrDetector( 1015):          be11eeb4  00000000  
D/CrashAnrDetector( 1015):          be11eeb8  00000000  
D/CrashAnrDetector( 1015):          be11eebc  00000000  
D/CrashAnrDetector( 1015):         
,D/CrashAnrDetector( 1015): processName:com.test.thalitest
D/CrashAnrDetector( 1015): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/BootReceiver( 1015): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1015): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/SettingsProvider( 1015): name = db_smartlock_supported
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 8409, tid: 8409, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1015):     r0 b9145f50  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1015):     r4 0045b0a0  r5 be11f218  r6 b9145f50  r7 be11f228
D/CrashAnrDetector( 1015):     r8 be11ee60  r9 bab49fd0  sl bab49fd0  fp be11f1dc
D/CrashAnrDetector( 1015):     ip be11f228  sp be11ee58  lr 9fdfc30c  pc 9fdfbd98  cpsr a00f0010
D/CrashAnrDetector( 1015):     d0  ffffff859df5ebb0  d1  646f6d5f65646f6e
D/CrashAnrDetector( 1015):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1015):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1015):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1015):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1015):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1015):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1015):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1015):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1015):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1015):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1015):     scr 20000012
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1015):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1015):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1015):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          be11edd8  00000000  
D/CrashAnrDetector( 1015):          be11eddc  00000000  
D/CrashAnrDetector( 1015):          be11ede0  00000000  
D/CrashAnrDetector( 1015):          be11ede4  00000000  
D/CrashAnrDetector( 1015):          be11ede8  00000000  
D/CrashAnrDetector( 1015):          be11edec  00000000  
D/CrashAnrDetector( 1015):          be11edf0  00000000  
D/CrashAnrDetector( 1015):          be11edf4  00000000  
D/CrashAnrDetector( 1015):          be11edf8  00000000  
D/CrashAnrDetector( 1015):          be11edfc  00000000  
D/CrashAnrDetector( 1015):     ,     be11ee00  00000000  
D/CrashAnrDetector( 1015):          be11ee04  00000000  
D/CrashAnrDetector( 1015):          be11ee08  00000000  
D/CrashAnrDetector( 1015):          be11ee0c  00000000  
D/CrashAnrDetector( 1015):          be11ee10  00000000  
D/CrashAnrDetector( 1015):          be11ee14  00000000  
D/CrashAnrDetector( 1015):          be11ee18  00000000  
D/CrashAnrDetector( 1015):          be11ee1c  00000000  
D/CrashAnrDetector( 1015):          be11ee20  00000000  
D/CrashAnrDetector( 1015):          be11ee24  00000000  
D/CrashAnrDetector( 1015):          be11ee28  00000000  
D/CrashAnrDetector( 1015):          be11ee2c  00000000  
D/CrashAnrDetector( 1015):          be11ee30  00000000  
D/CrashAnrDetector( 1015):          be11ee34  00000000  
D/CrashAnrDetector( 1015):          be11ee38  00000000  
D/CrashAnrDetector( 1015):          be11ee3c  00000000  
D/CrashAnrDetector( 1015):          be11ee40  00000000  
D/CrashAnrDetector( 1015):          be11ee44  00000000  
D/CrashAnrDetector( 1015):          be11ee48  00000000  
D/CrashAnrDetector( 1015):          be11ee4c  00000000  
D/CrashAnrDetector( 1015):          be11ee50  00000000  
D/CrashAnrDetector( 1015):          be11ee54  00000000  
D/CrashAnrDetector( 1015):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1015):          be11ee5c  00000000  
D/CrashAnrDetector( 1015):          be11ee60  00000000  
D/CrashAnrDetector( 1015):          be11ee64  00000000  
D/CrashAnrDetector( 1015):          be11ee68  00000000  
D/CrashAnrDetector( 1015):          be11ee6c  00000000  
D/CrashAnrDetector( 1015):          be11ee70  00000000  
D/CrashAnrDetector( 1015):          be11ee74  00000000  
D/CrashAnrDetector( 1015):          be11ee78  00000000  
D/CrashAnrDetector( 1015):          be11ee7c  00000000  
D/CrashAnrDetector( 1015):          be11ee80  00000000  
D/CrashAnrDetector( 1015):          be11ee84  00000000  
D/CrashAnrDetector( 1015):          be11ee88  00000000  
D/CrashAnrDetector( 1015):          be11ee8c  00000000  
D/CrashAnrDetector( 1015):          be11ee90  00000000  
D/CrashAnrDetector( 1015):          be11ee94  00000000  
D/CrashAnrDetector( 1015):          be11ee98  00000000  
D/CrashAnrDetector( 1015):          be11ee9c  00000000  
D/CrashAnrDetector( 1015):          be11eea0  00000000  
D/CrashAnrDetector( 1015):          be11eea4  00000000  
D/CrashAnrDetector( 1015):          be11eea8  00000000  
D/CrashAnrDetector( 1015):          be11eeac  00000000  
D/CrashAnrDetector( 1015):          be11eeb0  00000000  
D/CrashAnrDetector( 1015):          be11eeb4  00000000  
D/CrashAnrDetector( 1015):          be11eeb8  00000000  
D/CrashAnrDetector( 1015):          be11eebc  00000000  
D/CrashAnrDetector( 1015):         
D/CrashAnrDetector( 1015): processName:com.test.thalitest
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1015): broadcastEvent : null SYSTEM_TOMBSTONE
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/BootReceiver( 1015): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/AccessibilityManagerService( 1015): setmDNIeNegative (false)
,D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 10813, tid: 10813, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1015):     r0 b92c7dd0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1015):     r4 0045b0a0  r5 be11f218  r6 b92c7dd0  r7 be11f228
D/CrashAnrDetector( 1015):     r8 be11ee60  r9 b9a6af30  sl b9a6af30  fp be11f1dc
D/CrashAnrDetector( 1015):     ip be11f228  sp be11ee58  lr a0d6430c  pc a0d63d98  cpsr a00f0010
D/CrashAnrDetector( 1015):     d0  ffffff859ec579c0  d1  0000000000000000
D/CrashAnrDetector( 1015):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1015):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1015):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1015):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1015):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1015):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1015):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1015):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1015):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1015):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1015):     scr 20000012
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1015):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1015):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1015):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          be11edd8  00000000  
D/CrashAnrDetector( 1015):          be11eddc  00000000  
D/CrashAnrDetector( 1015):          be11ede0  00000000  
D/CrashAnrDetector( 1015):          be11ede4  00000000  
D/CrashAnrDetector( 1015):          be11ede8  00000000  
D/CrashAnrDetector( 1015):          be11edec  00000000  
D/CrashAnrDetector( 1015):          be11edf0  00000000  
D/CrashAnrDetector( 1015):          be11edf4  00000000  
D/CrashAnrDetector( 1015):          be11edf8  00000000  
D/CrashAnrDetector( 1015):          be11edfc  00000000  
D/CrashAnrDetector( 1015):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1015):          be11ee04  00000000  
D/CrashAnrDetector( 1015):          be11ee08  00000000  
D/CrashAnrDetector( 1015):          be11ee0c  00000000  
D/CrashAnrDetector( 1015):          be11ee10  00000000  
D/CrashAnrDetector( 1015):          be11ee14  00000000  
D/CrashAnrDetector( 1015):          be11ee18  00000000  
D/CrashAnrDetector( 1015):          be11ee1c  00000000  
D/CrashAnrDetector( 1015):          be11ee20  00000000  
D/CrashAnrDetector( 1015):          be11ee24  00000000  
D/CrashAnrDetector( 1015):          be11ee28  00000000  
D/CrashAnrDetector( 1015):          be11ee2c  00000000  
D/CrashAnrDetector( 1015):          be11ee30  00000000  
D/CrashAnrDetector( 1015):          be11ee34  00000000  
D/CrashAnrDetector( 1015):          be11ee38  00000000  
D/CrashAnrDetector( 1015):          be11ee3c  00000000  
D/CrashAnrDetector( 1015):          be11ee40  00000000  
D/CrashAnrDetector( 1015):          be11ee44  00000000  
D/CrashAnrDetector( 1015):          be11ee48  00000000  
D/CrashAnrDetector( 1015):          be11ee4c  00000000  
D/CrashAnrDetector( 1015):          be11ee50  00000000  
D/CrashAnrDetector( 1015):          be11ee54  00000000  
D/CrashAnrDetector( 1015):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1015):          be11ee5c  00000000  
D/CrashAnrDetector( 1015):          be11ee60  00000000  
D/CrashAnrDetector( 1015):          be11ee64  00000000  
D/CrashAnrDetector( 1015):          be11ee68  00000000  
D/CrashAnrDetector( 1015):          be11ee6c  00000000  
D/CrashAnrDetector( 1015):          be11ee70  00000000  
D/CrashAnrDetector( 1015):          be11ee74  00000000  
D/CrashAnrDetector( 1015):          be11ee78  00000000  
D/CrashAnrDetector( 1015):          be11ee7c  00000000  
D/CrashAnrDetector( 1015):          be11ee80  00000000  
D/CrashAnrDetector( 1015):          be11ee84  00000000  
D/CrashAnrDetector( 1015):          be11ee88  00000000  
D/CrashAnrDetector( 1015):          be11ee8c  00000000  
D/CrashAnrDetector( 1015):          be11ee90  00000000  
D/CrashAnrDetector( 1015):          be11ee94  00000000  
D/CrashAnrDetector( 1015):          be11ee98  00000000  
D/CrashAnrDetector( 1015):          be11ee9c  00000000  
D/CrashAnrDetector( 1015):          be11eea0  00000000  
D/CrashAnrDetector( 1015):          be11eea4  00000000  
D/CrashAnrDetector( 1015):          be11eea8  00000000  
D/CrashAnrDetector( 1015):          be11eeac  00000000  
D/CrashAnrDetector( 1015):          be11eeb0  00000000  
D/CrashAnrDetector( 1015):          be11eeb4  00000000  
D/CrashAnrDetector( 1015):          be11eeb8  00000000  
D/CrashAnrDetector( 1015):          be11eebc  00000000  
D/CrashAnrDetector( 1015):       
D/CrashAnrDetector( 1015): processName:com.test.thalitest
D/CrashAnrDetector( 1015): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 46310(2MB) AllocSpace objects, 50(4MB) LOS objects, 33% free, 28MB/42MB, paused 2.582ms total 189.594ms
,D/BluetoothAdapterState( 2712): make
,W/art     ( 2055): Suspending all threads took: 11.078ms
I/bluedroid( 2712): init
,I/BluetoothAdapterState( 2712): Entering OffState
,I/BootReceiver( 1015): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,I/bte_conf( 2712): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/bte_conf( 2712): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2712): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2712): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 2712): btif_fetch_local_ble_random_bdaddr
I/bluedroid( 2712): get_profile_interface socket
I/bluedroid( 2712): get_profile_interface map_client
,D/BluetoothAdapterService( 2712): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 2712): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 2712): Address is:7C:F9:0E:37:96:AB
,E/BluetoothServiceJni( 2712): populateRssiValuesNative
I/bluedroid( 2712): getModelRssiValues
E/BluetoothServiceJni( 2712): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2712): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 2712): Name is: A5-1
,D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 6058, tid: 6772, name: Thread-1061  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9c909ff0
D/CrashAnrDetector( 1015):     r0 710804a8  r1 735927c8  r2 12dd4780  r3 13533ec0
D/CrashAnrDetector( 1015):     r4 000000c2  r5 710804a8  r6 735927c8  r7 13533ec0
D/CrashAnrDetector( 1015):     r8 73592770  r9 ba677458  sl 12dd4780  fp 9ca0b8a8
D/CrashAnrDetector( 1015):     ip 9c909ff0  sp 9c90bff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1015):     d0  12dd4780735927c0  d1  007300200065003e
D/CrashAnrDetector( 1015):     d2  c0c0c0c0c0c0c053  d3  0102020202020213
D/CrashAnrDetector( 1015):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1015):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1015):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1015):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1015):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1015):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1015):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1015):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1015):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1015):     scr 20000013
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1015):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          9c90bf70  00000000  
D/CrashAnrDetector( 1015):          9c90bf74  00000000  
D/CrashAnrDetector( 1015):          9c90bf78  00000000  
D/CrashAnrDetector( 1015):          9c90bf7c  00000000  
D/CrashAnrDetector( 1015):          9c90bf80  00000000  
D/CrashAnrDetector( 1015):          9c90bf84  00000000  
D/CrashAnrDetector( 1015):          9c90bf88  00000000  
D/CrashAnrDetector( 1015):          9c90bf8c  00000000  
D/CrashAnrDetector( 1015):          9c90bf90  00000000  
D/CrashAnrDetector( 1015):          9c90bf94  00000000  
D/CrashAnrDetector( 1015):          9c90bf98  00000000  
D/CrashAnrDetector( 1015):          9c90bf9c  00000000  
D/CrashAnrDetector( 1015):          9c90bfa0  00000000  
D/CrashAnrDetector( 1015):          9c90bfa4  00000000  
D/CrashAnrDetector( 1015):          9c90bfa8  00000000  
D/CrashAnrDetector( 1015):          9c90bfac  00000000  
D/CrashAnrDetector( 1015):          9c90bfb0  00000000  
D/CrashAnrDetector( 1015):          9c90bfb4  00000000  
D/CrashAnrDetector( 1015):          9c90bfb8  00000000  
D/CrashAnrDetector( 1015):          9c90bfbc  00000000  
D/CrashAnrDetector( 1015):          9c90bfc0  00000000  
D/CrashAnrDetector( 1015):          9c90bfc4 , 00000000  
D/CrashAnrDetector( 1015):          9c90bfc8  00000000  
D/CrashAnrDetector( 1015):          9c90bfcc  00000000  
D/CrashAnrDetector( 1015):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90bfd4  00000000  
D/CrashAnrDetector( 1015):          9c90bfd8  00000000  
D/CrashAnrDetector( 1015):          9c90bfdc  00000000  
D/CrashAnrDetector( 1015):          9c90bfe0  00000000  
D/CrashAnrDetector( 1015):          9c90bfe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90bfe8  e3a070ad  
D/CrashAnrDetector( 1015):          9c90bfec  ef9000ad  
D/CrashAnrDetector( 1015):     #00  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          ........  ........
D/CrashAnrDetector( 1015):     #01  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90bff4  00000000  
D/CrashAnrDetector( 1015):          9c90bff8  00000000  
D/CrashAnrDetector( 1015):          9c90bffc  00000000  
D/CrashAnrDetector( 1015):          9c90c000  00000000  
D/CrashAnrDetector( 1015):          9c90c004  00000000  
D/CrashAnrDetector( 1015):          9c90c008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c00c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c010  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1015):          9c90c014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c018  12dd4780  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1015):          9c90c01c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1015):          9c90c020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c024  00000000  
D/CrashAnrDetector( 1015):          9c90c028  00000000  
D/CrashAnrDetector( 1015):          9c90c02c  00000000  
D/CrashAnrDetector( 1015):          9c90c030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c034  00000000  
D/CrashAnrDetector( 1015):          9c90c038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c03c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          9c90c040  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1015):          9c90c044  73
D/CrashAnrDetector( 1015): processName:com.test.thalitest
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1015): broadcastEvent : null SYSTEM_TOMBSTONE
D/SettingsProvider( 1015): name = bluetooth_name
,I/BootReceiver( 1015): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1015): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/BluetoothA2dp( 2712): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1015): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 6080, tid: 6935, name: Thread-1071  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa37a6ff0
D/CrashAnrDetector( 1015):     r0 710804a8  r1 735927c8  r2 12e00890  r3 133c2fc0
D/CrashAnrDetector( 1015):     r4 000000c2  r5 710804a8  r6 735927c8  r7 133c2fc0
D/CrashAnrDetector( 1015):     r8 73592770  r9 b8284ec8  sl 12e00890  fp a38a88a8
D/CrashAnrDetector( 1015):     ip a37a6ff0  sp a37a8ff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1015):     d0  12e00890735927c0  d1  007300200065002f
D/CrashAnrDetector( 1015):     d2  c0c0c0c0c0c0c03c  d3  0102020202020213
D/CrashAnrDetector( 1015):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1015):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1015):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1015):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1015):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1015):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1015):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1015):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1015):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1015):     scr 20000013
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1015):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          a37a8f70  00000000  
D/CrashAnrDetector( 1015):          a37a8f74  00000000  
D/CrashAnrDetector( 1015):          a37a8f78  00000000  
D/CrashAnrDetector( 1015):          a37a8f7c  00000000  
D/CrashAnrDetector( 1015):          a37a8f80  00000000  
D/CrashAnrDetector( 1015):          a37a8f84  00000000  
D/CrashAnrDetector( 1015):          a37a8f88  00000000  
D/CrashAnrDetector( 1015):          a37a8f8c  00000000  
D/CrashAnrDetector( 1015):          a37a8f90  00000000  
D/CrashAnrDetector( 1015):          a37a8f94  00000000  
D/CrashAnrDetector( 1015):          a37a8f98  00000000  
D/CrashAnrDetector( 1015):          a37a8f9c  00000000  
D/CrashAnrDetector( 1015):          a37a8fa0  00000000  
D/CrashAnrDetector( 1015):          a37a8fa4  00000000  
D/CrashAnrDetector( 1015):          a37a8fa8  00000000  
D/CrashAnrDetector( 1015):          a37a8fac  00000000  
D/CrashAnrDetector( 1015):          a37a8fb0  00000000  
D/CrashAnrDetector( 1015):          a37a8fb4  00000000  
D/CrashAnrDetector( 1015):          a37a8fb8  00000000  
D/CrashAnrDetector( 1015):          a37a8fbc  00000000  
D/CrashAnrDetector( 1015):          a37a8fc0  000,00000  
D/CrashAnrDetector( 1015):          a37a8fc4  00000000  
D/CrashAnrDetector( 1015):          a37a8fc8  00000000  
D/CrashAnrDetector( 1015):          a37a8fcc  00000000  
D/CrashAnrDetector( 1015):          a37a8fd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a8fd4  00000000  
D/CrashAnrDetector( 1015):          a37a8fd8  00000000  
D/CrashAnrDetector( 1015):          a37a8fdc  00000000  
D/CrashAnrDetector( 1015):          a37a8fe0  00000000  
D/CrashAnrDetector( 1015):          a37a8fe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a8fe8  e3a070ad  
D/CrashAnrDetector( 1015):          a37a8fec  ef9000ad  
D/CrashAnrDetector( 1015):     #00  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          ........  ........
D/CrashAnrDetector( 1015):     #01  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a8ff4  00000000  
D/CrashAnrDetector( 1015):          a37a8ff8  00000000  
D/CrashAnrDetector( 1015):          a37a8ffc  00000000  
D/CrashAnrDetector( 1015):          a37a9000  00000000  
D/CrashAnrDetector( 1015):          a37a9004  00000000  
D/CrashAnrDetector( 1015):          a37a9008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a900c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a9010  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1015):          a37a9014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a9018  12e00890  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1015):          a37a901c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1015):          a37a9020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a9024  00000000  
D/CrashAnrDetector( 1015):          a37a9028  00000000  
D/CrashAnrDetector( 1015):          a37a902c  00000000  
D/CrashAnrDetector( 1015):          a37a9030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a9034  00000000  
D/CrashAnrDetector( 1015):          a37a9038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a903c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1015):          a37a9040  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1015):          a37a9044  73
D/CrashAnrDetector( 1015): processName:com.test.thalitest
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1015): broadcastEvent : null SYSTEM_TOMBSTONE
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 2712): config_hci_snoop_log
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothManagerService( 1015): Ble is always on enable gatt
,I/BluetoothManagerService( 1015): enableGattForLeMode, doBind called
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,I/BtGatt.JNI( 2712): classInitNative(L900): classInitNative: Success!
E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1015): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1015): uri = 3 selection = isBluetoothEnabled
,W/Settings( 1365): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapterState( 2712): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 2712): Setting state to 11
I/BluetoothAdapterState( 2712): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2712): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2712): updateAdapterState state is 11
,D/BluetoothAdapterService( 2712): Autoconnection is available 
,D/CrashAnrDetector( 1015): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1015): Hardware: MSM8916
D/CrashAnrDetector( 1015): Revision: 2
D/CrashAnrDetector( 1015): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1015): Radio: unknown
D/CrashAnrDetector( 1015): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1015): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1015): Revision: '2'
D/CrashAnrDetector( 1015): ABI: 'arm'
D/CrashAnrDetector( 1015): pid: 2458, tid: 2624, name: Thread-256  >>> com.example.hello <<<
D/CrashAnrDetector( 1015): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1015):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1015):     r4 9dddde78  r5 9dddde38  r6 b8adc500  r7 9dddde38
D/CrashAnrDetector( 1015):     r8 00000000  r9 9dddde74  sl 9dddf3d0  fp 9dddde1c
D/CrashAnrDetector( 1015):     ip 9d93cba0  sp 9dddde00  lr 9d643308  pc b6f2d468  cpsr 600d0030
D/CrashAnrDetector( 1015):     d0  513802003a373ed5  d1  0000b80c030000a1
D/CrashAnrDetector( 1015):     d2  88000000560a109d  d3  0000003502000060
D/CrashAnrDetector( 1015):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1015):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1015):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1015):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1015):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1015):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1015):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1015):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1015):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1015):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1015):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1015):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1015):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1015):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1015):     scr 20000012
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): backtrace:
D/CrashAnrDetector( 1015):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1015):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1015): 
D/CrashAnrDetector( 1015): stack:
D/CrashAnrDetector( 1015):          9ddddd80  00000000  
D/CrashAnrDetector( 1015):          9ddddd84  00000000  
D/CrashAnrDetector( 1015):          9ddddd88  9cd2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1015):          9ddddd8c  e8bc0f76  
D/CrashAnrDetector( 1015):          9ddddd90  9dddddbc  [stack:2624]
D/CrashAnrDetector( 1015):          9ddddd94  9dddde64  [stack:2624]
D/CrashAnrDetector( 1015):          9ddddd98  b8adc500  [heap]
D/CrashAnrDetector( 1015):          9ddddd9c  00000003  
D/CrashAnrDetector( 1015):          9ddddda0  9ddddddc  [stack:2624]
D/CrashAnrDetector( 1015):          9ddddda4  b8b162a8  [heap]
D/CrashAnrDetector( 1015):          9ddddda8  9cd53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1015):          9dddddac  9da11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1015):          9dddddb0  00000000  
D/CrashAnrDetector( 1015):          9dddddb4  ffffff82  
D/CrashAnrDetector( 1015):          9dddddb8  00000000  
D/CrashAnrDetector( 1015):          9dddddbc  ffffff82  
D/CrashAnrDetector( 1015):          9dddddc0  9cd2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1015):          9dddddc4  b8b132a8  [heap]
D/CrashAnrDetector( 1015):,          9dddddc8  b8bcbd18  [heap]
D/CrashAnrDetector( 1015):          9dddddcc  00000001  
D/CrashAnrDetector( 1015):          9dddddd0  9cd49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1015):          9dddddd4  b8adc500  [heap]
D/CrashAnrDetector( 1015):          9dddddd8  9cd4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1015):          9ddddddc  00000000  
D/CrashAnrDetector( 1015):          9ddddde0  00000000  
D/CrashAnrDetector( 1015):          9ddddde4  00000000  
D/CrashAnrDetector( 1015):          9ddddde8  00000003  
D/CrashAnrDetector( 1015):          9dddddec  000000aa  
D/CrashAnrDetector( 1015):          9dddddf0  0000006b  
D/CrashAnrDetector( 1015):          9dddddf4  0001416e  
D/CrashAnrDetector( 1015):          9dddddf8  00000000  
D/CrashAnrDetector( 1015):          9dddddfc  9dddde30  [stack:2624]
D/CrashAnrDetector( 1015):     #00  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1015):          ........  ........
D/CrashAnrDetector( 1015):     #01  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde04  00000000  
D/CrashAnrDetector( 1015):          9dddde08  9dddde78  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde0c  9dddde5c  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde10  9dddde48  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde14  00000000  
D/CrashAnrDetector( 1015):          9dddde18  9dddee94  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde1c  9d61a3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1015):          9dddde20  9dddde50  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde24  00000000  
D/CrashAnrDetector( 1015):          9dddde28  9dddde44  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde2c  9d44c184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1015):          9dddde30  00000000  
D/CrashAnrDetector( 1015):          9dddde34  00000000  
D/CrashAnrDetector( 1015):          9dddde38  b6f73de4  
D/CrashAnrDetector( 1015):          9dddde3c  00000000  
D/CrashAnrDetector( 1015):          9dddde40  9ddde1cc  [stack:2624]
D/CrashAnrDetector( 1015):          9dddde44  9d528b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1015):          9dddde48  b8adc500  [heap]
D/CrashAnrDetector( 1015):          9dddde4c  b8adc500  [heap]
D/CrashAnrDetector( 1015):          9dddde50  b8bcbd18  [heap]
D/CrashAnrDetector( 1015):          9dddde54  00000001  
D/CrashAnrDetector( 1015):          9dddde58  9
D/CrashAnrDetector( 1015): processName:com.example.hello
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1015): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
D/BluetoothAdapterService( 2712): updateAdapterState prevState = 10newState = 11
,D/SettingsProvider( 1015): name = block_emergency_message
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/SettingsProvider( 1015): name = safetycare_geolookout_registering,
,D/BluetoothSecureManager( 2712): getInstant: null,
D/BluetoothSecureManager( 2712): calling getMethod for getService
D/BluetoothSecureManager( 2712): calling getService
D/BluetoothSecureManager( 2712): getService return binder: android.os.BinderProxy@3a354bfb
D/BluetoothSecureManagerService( 1015): isSecureModeEnabled
,D/BluetoothSecureManagerService( 1015): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 2712): isSecureModeOn:false
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/SamsungIME( 1784): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1015): [BT Setting State] State =11
W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2712): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2712): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2712): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2712): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService,
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2712): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  getBluetoothState : 11
,D/BluetoothBondStateMachine( 2712): make
D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1175): onStateChanged: Bluetooth
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 2712): StableState(): Entering Off State
W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.gatt.GattService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2712): handleDebugAction() action=null
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,D/BtGatt.GattService( 2712): Received start request. Starting profile...
,D/BtGatt.GattService( 2712): start()
D/BtGatt.GattService( 2712): start()
I/bluedroid( 2712): get_profile_interface gatt
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/BtGatt.AdvertiseManager( 2712): advertise manager created
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/ConnectivityManager( 2055): CallingUid : 10012, CallingPid : 2055
,D/ConnectivityService( 1015): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1015): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1015): apparently satisfied.  currentScore=60
,D/ConnectivityService( 1015): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityManager.CallbackHandler( 2055): CM callback handler got msg 524290
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.hid.HidService
,D/BtGatt.GattService( 2712): mStartError = false
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,D/HeadsetService( 2712): Received start request. Starting profile...
,D/HeadsetService( 2712): start()
,I/BluetoothHeadsetServiceJni( 2712): classInitNative: succeeds
,D/HeadsetStateMachine( 2712): make
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.hdp.HealthService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/HeadsetStateMachine( 2712): # of Max HF connection is 2
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1015): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.map.BluetoothMapService
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2712): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,D/ActivityManager( 1015): bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2712): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
I/BluetoothAdapterState( 2712): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/bluedroid( 2712): get_profile_interface handsfree
,I/DualScoManager( 2712): Instantiating Dual Sco Manager
I/DualScoManager( 2712): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 2712): createCMTIContentObservers
,D/SettingsProvider( 1015): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 2712): Enter Disconnected: -2
,D/HeadsetService( 2712): mStartError = false
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/HeadsetStateMachine( 2712): Clear mHeadsetBrsf
D/HeadsetStateMachine( 2712): map size, before remove : 0
D/HeadsetStateMachine( 2712): map size, after remove: 0
,D/A2dpService( 2712): Received start request. Starting profile...
D/A2dpService( 2712): start()
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/BluetoothAvrcpServiceJni( 2712): classInitNative: succeeds
,I/bluedroid( 2712): get_profile_interface avrcp
,E/RemoteController( 2712): Cannot set synchronization mode on an unregistered RemoteController
,D/[LPC]   ( 1015): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,I/Avrcp   ( 2712):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 2712):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 2712): classInitNative: succeeds
,D/A2dpStateMachine( 2712): make
,I/bluedroid( 2712): get_profile_interface a2dp
,I/GKI_LINUX( 2712): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 2712): warning : media task started media_task_refcnt 1 
,D/BluetoothMediaBrowser( 2712): no now playing list
D/BluetoothMediaBrowser( 2712):  getNowPlayingId now playing id : -1
,D/A2dpService( 2712): mStartError = false
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothHidServiceJni( 2712): classInitNative: succeeds
,D/A2dpStateMachine( 2712): Enter Disconnected: -2
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,D/HidService( 2712): Received start request. Starting profile...,
D/HidService( 2712): start()
I/bluedroid( 2712): get_profile_interface hidhost
,D/HidService( 2712): setHidService(): set to: null
D/HidService( 2712): mStartError = false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/BluetoothHealthServiceJni( 2712): classInitNative: succeeds
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/HealthService( 2712): Received start request. Starting profile...
D/HealthService( 2712): start()
,I/bluedroid( 2712): get_profile_interface health
,W/CursorWrapperInner( 2355): Cursor finalized without prior close()
D/HealthService( 2712): mStartError = false
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,I/BluetoothPanServiceJni( 2712): classInitNative(L105): succeeds
,E/Zygote  ( 2803): MountEmulatedStorage()
E/Zygote  ( 2803): v2
I/libpersona( 2803): KNOX_SDCARD checking this for 1000
I/libpersona( 2803): KNOX_SDCARD not a persona
,I/SELinux ( 2803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2803 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/PanService( 2712): Received start request. Starting profile...
D/PanService( 2712): start()
D/BluetoothPanServiceJni( 2712): initializeNative(L110): pan
I/bluedroid( 2712): get_profile_interface pan
,D/PanService( 2712): mStartError = false
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/BluetoothMapService( 2712): Received start request. Starting profile...
D/BluetoothMapService( 2712): start()
,D/BluetoothMapService( 2712): mStartError = false
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,I/BluetoothSAPServiceJni( 2712): classInitNative(L204): succeeds
,D/SapService( 2712): Received start request. Starting profile...
D/SapService( 2712): start()
D/BluetoothSAPServiceJni( 2712): initializeNative(L209): sap
I/bluedroid( 2712): get_profile_interface sap
D/SapService( 2712): mStartError = false
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
D/HeadsetStateMachine( 2712): Proxy object connected
D/HeadsetStateMachine( 2712): Try to query the phonestate on bind
,I/Telecom ( 1424): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1424): BluetoothPhoneService: handleMessage(7) / param 0
I/Telecom ( 1424): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1424): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1424): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,D/TimaKeyStoreProvider( 2803): TimaSignature is unavailable
,D/ActivityThread( 2803): Added TimaKeyStore provider
,I/Telecom ( 1424): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 26
,W/BluetoothHeadset( 1424): Proxy not attached to service
,I/Telecom ( 1424): BluetoothPhoneService: Result of Message : true
,D/HeadsetPhoneState( 2712): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 2712): sendDeviceDataStateChanged
D/HeadsetStateMachine( 2712): Disconnected process message: 11
D/HeadsetPhoneState( 2712): Signal level : previous=0 curr=0
D/HeadsetStateMachine( 2712): Disconnected process message: 18
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 2712): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 2712): Proxy object connected
D/BluetoothAdapterService( 2712): Bluetooth A2dp source service connected
,D/HeadsetStateMachine( 2712): Disconnected process message: 10
D/HeadsetPhoneState( 2712): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2712): Disconnected process message: 11
,W/ResourcesManager( 2803): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2818): MountEmulatedStorage()
E/Zygote  ( 2818): v2
I/libpersona( 2818): KNOX_SDCARD checking this for 10145
I/libpersona( 2818): KNOX_SDCARD not a persona
,I/SELinux ( 2818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2818 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 2818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,D/TimaKeyStoreProvider( 2818): TimaSignature is unavailable
,D/ActivityThread( 2818): Added TimaKeyStore provider
,I/i       ( 1015): No model
,W/ResourcesManager( 2818): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 2818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2818): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2818): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/FactoryTest( 1015): Not factory mode
D/w       ( 1015): isUserBuild = true
D/FactoryTest( 1015): Not factory mode. isFactoryMode() returend false
,W/DriveInitializer( 2055): Awaiting to be initialized
,W/DriveInitializer( 2055): Background init thread started
,D/SSRM:aZ ( 1015): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1015): Updating Threshold Value.. isSystemReady: true
,E/SmartFaceService( 1015): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1015): no icon
,E/SmartFaceService( 1015): mActiveServiceType: 0
,E/SmartFaceService( 1015): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1015): updateClientsDone. def. do nothing.
,E/SmartFaceService( 1015): Service Type to Worker: 0
E/SmartFaceService( 1015): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1015): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/BluetoothA2dp( 1015): Proxy object connected
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1015): [SO] activate (ident=0xb879f1b8, enabled=0)
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,D/SensorManager( 1015): unregisterListener ::   
,I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1015): [SO] changed settle time [0]
D/SensorService( 1015): [SO] setDelay [200000000]
D/SensorService( 1015): [SO] activate (ident=0xb879f1b8, enabled=1)
D/SensorService( 1015): [SO] AR_init
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/AlarmManagerEXT( 1015): mGmsLocationBundling: false
D/BluetoothPan( 1015): BluetoothPAN Proxy object connected
,D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
,I/ActivityManager( 1015): Killing 1191:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1015): [SO] activate (ident=0xb879f1b8, enabled=0)
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1015): unregisterListener ::   
,I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1015): [SO] changed settle time [1]
,D/SensorService( 1015): [SO] setDelay [66000000]
D/SensorService( 1015): [SO] activate (ident=0xb879f1b8, enabled=1)
D/SensorService( 1015): [SO] AR_init
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/RCPManagerService( 1015): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1015):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/RCPManagerService( 1015): BootReceiver.onReceive(): Starting RCP Proxy for user = null
,E/RCPManagerService( 1015):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/,
W/ContextImpl( 2055): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files,
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/EnterpriseDeviceManagerService( 1015): android.intent.action.BOOT_COMPLETED
D/SensorService( 1015): [SO] 0.038 0.326 10.132
D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
D/EnterpriseDeviceManagerService( 1015): runAdminUpdate
D/EnterpriseUtils( 1015): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1015): nothing to selfUpdate
,V/ApplicationPolicy( 1015): boot completed - refreshWidgetStatus
,V/ApplicationPolicy( 1015): refresh widget status for user 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname flipboard.app
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget,
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_1191/cgroup.procs: No such file or directory
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.mms
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/PhoneRestrictionPolicy( 1015): Message received - msg { when=-3ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1015): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy( 1015): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1015):  >>>> deliveryBlockedMsgs
,D/WifiP2pService( 1015): InactiveState{ what=143415 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143415 }
,D/WifiP2pService( 1015): DefaultState{ what=143415 }
,D/ConnectivityService( 1015): Got NetworkFactory Messenger for WIFI_P2P
,D/WIFI_P2P( 1015): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/Tethering( 1015): Boot complete.
,D/ConnectivityService( 1015): Got NetworkFactory Messenger for WIFI
,E/WifiStateMachine( 1015): Blacklist file delete
,D/SensorService( 1015): [SO] 0.038 0.345 10.113
,D/SensorService( 1015): [SO] [100 -> 255]
,V/EnterpriseBillingEngine( 1015): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1015): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1015): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1015): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1015): handleAllprofiles - end
,W/PhoneRestrictionPolicy( 1015): cvList size 0
,W/PhoneRestrictionPolicy( 1015):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1015): cvList size 0
,W/DriveInitializer( 2055): Background init thread ended
,D/UsbHostNotification( 1015): boot completed
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/UsbHostRestrictor( 1015): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1015): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1015): SIM was never inserted
,D/UsbHostRestrictor( 1015): writableHostSysNode[false]
,D/UsbHostRestrictor( 1015): Can NOT Write Disable Sys Node to [ON]
,D/WIFI    ( 1015): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/PersonaManagerService( 1015): ACTION_BOOT_COMPLETED
D/BluetoothAdapterState( 2712): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2712): enable
,E/PersonaManagerServiceHandler( 1015):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/KnoxKeyguardUpdateMonitor( 1015): onBootComplete
,I/KnoxKeyguardUpdateMonitor( 1015): onTrustManagedChanged user 0, managed:false
,D/KeyguardViewMediator( 1175): onTrustChanged( Showing = false , userId = 0 )
,I/KnoxKeyguardUpdateMonitor( 1015): onTrustChanged user:0, enable:false
,D/UsbStorageNotification( 1015): boot completed
,I/bt_hci_bdroid( 2712): init
,I/GKI_LINUX( 2712): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 2712): bt-vendor : init
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1015): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1015): set_capabilities_callback: 55u
,I/bt_vendor( 2712): bt-vendor : get_bt_soc_type
,I/libmdmdetect( 1015): ESOC framework not supported
,E/bt_vendor( 2712): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 2712): init: Local BD Address : ab:96:37:0e:f9:7c
D/bt_userial_mct( 2712): userial_init
,I/bt_vendor( 2712): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2712): Starting hciattach daemon
I/bt_vendor( 2712): try to set false
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,D/qmi_secgps_clnt( 1015): qmi_secgps_client_init()
,I/libmdmdetect( 1015): Found internal modem: modem
E/PerMgrLib( 1015): Peripheral manager is not supported on this device
I/bt_vendor( 2712): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 2712): Starting hciattach daemon
I/bt_vendor( 2712): try to set true
,E/Geofence_Adapter( 1015): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1015): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1015): BOOT_COMPLETED native_cleanup 
,D/StorageNotification( 1175): boot completed
,I/ActivityManager( 1015): Killing 1395:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/qmi_secgps_clnt( 1015): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt( 1015): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,I/qcom-bluetooth( 2874): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,D/StatusBarManagerService( 1015): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/PhoneStatusBar( 1175): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1015): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
D/qmi_secgps_clnt( 1015): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 1566): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/Zygote  ( 2879): MountEmulatedStorage()
,I/libpersona( 2879): KNOX_SDCARD checking this for 10099
E/Zygote  ( 2879): v2
I/libpersona( 2879): KNOX_SDCARD not a persona
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
I/ActivityManager( 1015): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2879 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2879): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,D/BadgeProvider( 1566): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 1566): sendNotify, [notify] : null,
,D/BadgeProvider( 1566): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1566): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1566): update, [UpdateCount] : 1
D/Launcher.Model( 1479): reloadBadges entered.
,I/qcom-bluetooth( 2896): /system/etc/init.qcom.bt.sh: Transport : smd 
,D/TimaKeyStoreProvider( 2879): TimaSignature is unavailable
,I/qcom-bluetooth( 2897): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/ActivityThread( 2879): Added TimaKeyStore provider,
,I/qcom-bluetooth( 2900): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qcom-bluetooth( 2902): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,E/LocSvc_utils_cfg( 1015): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/qcom-bluetooth( 2903): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,I/qcom-bluetooth( 2905): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
W/libprocessgroup( 1015): failed to open /acct/uid_10096/pid_1395/cgroup.procs: No such file or directory
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1015): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
I/ActivityManager( 1015): Killing 1539:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt( 1015): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1015): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1015): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1015): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,E/ActivityThread( 2879): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2879): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1015): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1015): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/ActivityManager( 1015): Killing 1819:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/DrmEventReceiver( 1015): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1015): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1015): DrmEventReceiver : beginStartingService
,I/System.out( 1015): start Service
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1015): startService callerProcessName:android, calleePkgName: android
,D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1228): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2916): MountEmulatedStorage()
,I/libpersona( 2916): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2916): v2
I/libpersona( 2916): KNOX_SDCARD not a persona
I/SELinux ( 2916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2916 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_1539/cgroup.procs: No such file or directory
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/qcom-bluetooth( 2922): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,I/qcom-bluetooth( 2929): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2930 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,E/Zygote  ( 2930): MountEmulatedStorage()
I/libpersona( 2930): KNOX_SDCARD checking this for 10152
E/Zygote  ( 2930): v2
I/libpersona( 2930): KNOX_SDCARD not a persona
,I/SELinux ( 2930): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 2930): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/SELinux ( 2930): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 2916): TimaSignature is unavailable
,D/ActivityThread( 2916): Added TimaKeyStore provider
,D/WVMDrmPlugIn(  288): WVMDrmPlugin::onInitialize : 1483
D/WVMDrmPlugIn(  288): WVMDrmPlugin::onSetOnInfoListener : add 1483
,I/DrmEventService( 1015): action event :android.intent.action.BOOT_COMPLETED
,I/TimaServiceEventReceiver( 1015): TimaServiceEventReceiver : onReceive
,I/ANDROID_DRM_FRWORKS_DrmManager(  288): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/TimaKeyStoreProvider( 2930): TimaSignature is unavailable
D/ActivityThread( 2930): Added TimaKeyStore provider
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
,W/ResourcesManager( 2916): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MediaScannerReceiver( 1228): action: android.intent.action.BOOT_COMPLETED
,I/bt_vendor( 2712): bluetooth satus is on
D/bt_userial_mct( 2712): userial_open(port:0)
I/bt_vendor( 2712): bt-vendor : BT_VND_OP_USERIAL_OPEN
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,D/BluetoothBDAdrressReceiver( 2916): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 2916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,I/bt_vendor( 2712): Done intiailizing UART
,I/bt_vendor( 2712): Done intiailizing UART
I/bt_userial_mct( 2712): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2712): Bluetooth Firmware and transport layer are initialized
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/bt_userial_mct( 2712): Entering userial_read_thread()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
,I/        ( 2712): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 2712): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2712): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2712): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 2712): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2712): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2712): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2712): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2712): BTE_InitTraceLevels -- TRC_GAP,
I/        ( 2712): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2712): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2712): BTE_InitTraceLevels -- TRC_SDP,
,I/        ( 2712): BTE_InitTraceLevels -- TRC_GATT
W/libprocessgroup( 1015): failed to open /acct/uid_10138/pid_1819/cgroup.procs: No such file or directory
I/        ( 2712): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2712): BTE_InitTraceLevels -- TRC_BTAPP
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
I/        ( 2712): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2712): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,E/CscReceiver( 1453): onReceive android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/ActivityManager( 1015): Killing 1623:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 2930): (284) automatic index on shooting_modes(title_id)
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 27
,E/Zygote  ( 2955): MountEmulatedStorage()
,E/Zygote  ( 2955): v2
I/libpersona( 2955): KNOX_SDCARD checking this for 1000
I/libpersona( 2955): KNOX_SDCARD not a persona
,I/SELinux ( 2955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 2126:com.vlingo.midas/u0a31 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     (  315): Explicit concurrent mark sweep GC freed 8787(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.647ms total 34.659ms
,W/ResourcesManager( 1453): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1453): onCreate()
E/BluetoothBDTestService( 1453): onStart(), extra_type: BOOT_COMPLETED
,E/BluetoothBDTestService( 1453): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1453): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,D/TimaKeyStoreProvider( 2955): TimaSignature is unavailable
D/CscUpdateService( 1453): onStart
,E/CscUpdateService( 1453): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1453): set_CSC_version
E/CscParser( 1453): update(): xml file exist
,D/ActivityThread( 2955): Added TimaKeyStore provider
,W/bt-l2cap( 2712): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 2712): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fa76e9 
E/bt-btm  ( 2712): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fa76e9 
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 18.009ms
,D/MediaScannerService( 1228): !@start scanning volume internal: [/system/media, /oem/media]
,D/BluetoothAdapterProperties( 2712): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 2712): BTM_SEC_REG[3]: id 37, is_orig 1, psm 0x000019
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 16.676ms
,E/bt-btif ( 2712): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 2712): Address is:7C:F9:0E:37:96:AB
E/BluetoothServiceJni( 2712): populateRssiValuesNative
I/bluedroid( 2712): getModelRssiValues
E/BluetoothServiceJni( 2712): model_rssi_values_callback: low = -70, mid = -60, high = 127,
D/BluetoothAdapterProperties( 2712): modelRssiValuesCallback, low, mid, high = -70,-60,127
,E/Zygote  ( 2970): MountEmulatedStorage(),
E/Zygote  ( 2970): v2
I/libpersona( 2970): KNOX_SDCARD checking this for 10003
I/libpersona( 2970): KNOX_SDCARD not a persona
,I/SELinux ( 2970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2970 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/SELinux ( 2970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/BluetoothAdapterProperties( 2712): Name is: A5-1
I/CscUtil ( 1453): isWifiOnly = false
I/System.out( 1453): HandDataNode = null
I/CscUpdateService( 1453): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1453): This is normal boot : CSC not updated
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,E/CscParser( 1453): update(): xml file exist
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/BluetoothUtils( 2712): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2712): Scan Mode:20
D/BluetoothAdapterProperties( 2712): Discoverable Timeout:120
D/SettingsProvider( 1015): name = bluetooth_name
D/BluetoothAdapterProperties( 2712): LE Address is:FC:F3:1C:6E:2D:57
E/bt-btif ( 2712): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2712): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2712): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2712): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2712): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 2712): db_open: db_open : handle 3027808272l, read 13894 bytes onto local cache
D/ActivityManager( 1015): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
D/IOP_DB_BT( 2712): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2712): db_query: result 1
I/        ( 2712): iop_db_open: iop_db_open status 0
,E/bt_mct  ( 2712): hci lib postload completed
,D/CscGPS  ( 1453): CSCGPS.updateParameters
D/CscGPS  ( 1453): supl host : null
D/CscGPS  ( 1453): SUPL Host is null or invalid
D/CscGPS  ( 1453): supl_ver : null
D/CscGPS  ( 1453): SUPL Ver is null or invalid
D/CscGPS  ( 1453): supl port : null
D/CscGPS  ( 1453): SUPL PORT is null or invalid
D/CscGPS  ( 1453): LPP : null
D/CscGPS  ( 1453): LPP is null or invalid
D/CscGPS  ( 1453): CSC don't have any AGPS value.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/CscUpdateService( 1453): same CSC Version
D/CscUtil ( 1453): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,D/TimaKeyStoreProvider( 2970): TimaSignature is unavailable
,D/ActivityThread( 2970): Added TimaKeyStore provider
D/bte_conf( 2712): Device ID record 1 : primary
D/bte_conf( 2712):   vendorId            = 0075
D/bte_conf( 2712):   vendorIdSource      = 0001
D/bte_conf( 2712):   product             = 0100,
D/bte_conf( 2712):   version             = 0200
D/bte_conf( 2712):   clientExecutableURL = 
D/bte_conf( 2712):   serviceDescription  = 
D/bte_conf( 2712):   documentationURL    = 
,D/bte_conf( 2712): bte_load_did_conf no section named DID2.
,W/ResourcesManager( 2955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BluetoothPanServiceJni( 2712): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
E/Zygote  ( 2993): MountEmulatedStorage()
E/Zygote  ( 2993): v2
I/libpersona( 2993): KNOX_SDCARD checking this for 1101
I/libpersona( 2993): KNOX_SDCARD not a persona
,I/SELinux ( 2993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2993 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,E/SELinux ( 2993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10107/pid_1623/cgroup.procs: No such file or directory
,D/BluetoothAdapterState( 2712): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
W/libprocessgroup( 1015): failed to open /acct/uid_10031/pid_2126/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 2712): ScanMode =  20
D/BluetoothAdapterProperties( 2712): State =  11
D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 2712): Setting state to 12
I/BluetoothAdapterState( 2712): Bluetooth adapter state changed: 11-> 12
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/MtpService( 1228): updating state; isCurrentUser=true, mMtpLocked=false
,D/BluetoothUtils( 2712): getBtEnabledContainers(): btContainers = []
D/BluetoothAdapterProperties( 2712): Scan Mode:21
D/BluetoothAdapterProperties( 2712): Discoverable Timeout:120
,D/SettingsProvider( 1015): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1002
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/TimaKeyStoreProvider( 2993): TimaSignature is unavailable
D/ActivityThread( 2993): Added TimaKeyStore provider
,E/SQLiteLog( 1228): (283) recovered 25 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 2712): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 2712): updateAdapterState state is 12
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,D/TP/MmsProvider( 1453): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1453): update , handleReadChangedBroadcast
,D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
W/ResourcesManager( 2993): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2712): Autoconnection is available 
D/BluetoothAdapterService( 2712): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2712): starting service from this receiver
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/Mms:transaction( 2355): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2355): [start]    nonBlockingUpdateMessageIndicator() consume time = 3338.748384
D/BluetoothAdapter( 2490): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 2490): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 2712): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 2712): Entering On State from state = 11
,D/BluetoothAdapter( 2712): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1015): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1453): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1453): onBluetoothStateChange: Bluetooth is on
,I/Mms/ReservationManager( 2355): resetAfterConnected()
D/BluetoothAdapter( 1439): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1439): onBluetoothStateChange: Bluetooth is on
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,D/BluetoothA2dp( 2712): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1015): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1015): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1901): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1901): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1424): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1424): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1175): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1175): onBluetoothStateChange: Bluetooth is on
V/SmartcardService( 2993): main Received broadcast
V/SmartcardService( 2993): Starting smartcard service after boot completed
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
D/TP/MmsSmsProvider( 1453): query,matched:7, calling pid = 2355
,D/TP/MmsSmsProvider( 1453): match 7:Elapsed time : 2.005 ms
,I/KnoxUsageLogPro( 2955): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,D/Mms/MessagingNotification( 2355): sDisableVibrateForCamera = false
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =12
D/Mms/TelephonyPermission( 2355): isDefault true
I/InputMethodManagerService( 1015): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1175):  onBluetoothStateChange:,
,I/KnoxUsageLogPro( 2955): savePreference: key = previous_sys_time value = 1456842787193
,D/BluetoothHeadset( 1424): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19a3858c, true
,I/BluetoothPbapService( 2712): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/SamsungIME( 1784): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 1424): registerMessageListener
,D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1175):  getBluetoothState : 12
D/ActivityManager( 1015): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1015): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,I/KnoxUsageLogPro( 2955): premStatus:2
,D/TP/MmsProvider( 1453): Query uri=content://mms, match=0, calling pid = 2355
,D/HeadsetService( 2712): registerMessageListener
,D/HeadsetService( 2712): registerMessageListener
,D/HeadsetStateMachine( 2712): Disconnected process message: 70
D/HeadsetStateMachine( 2712): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@35e79490
,I/Telecom ( 1424): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1424): BluetoothPhoneService: updateHeadsetWithCallState
D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,I/KnoxUsageLogPro( 2955): isEulaShown : false
I/KnoxUsageLogPro( 2955): KnoxUsageReceiver onReceive : not Processible, just return
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/Telecom ( 1424): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1424): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1424): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,I/ActivityManager( 1015): Killing 1496:com.android.printspooler/u0a136 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3012): MountEmulatedStorage()
E/Zygote  ( 3012): v2
I/libpersona( 3012): KNOX_SDCARD checking this for 10085
I/libpersona( 3012): KNOX_SDCARD not a persona
,I/SELinux ( 3012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/KnoxUsageLogPro( 2955): savePreference: key = previous_elapsed_time value = 34165
,I/ActivityManager( 1015): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3012 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 2154:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
I/SELinux ( 3012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/HeadsetStateMachine( 2712): Disconnected process message: 9
,D/HeadsetStateMachine( 2712): mNumActive: 0 mNumHeld: 0 mCallState: 6
,I/Mms/ReservationManager( 2355): getReservedSendMessageCount(): retMessageCount=0
,D/audio_hw_primary(  289): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  289): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  289): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  289): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  289): platform_set_parameters: exit with code(-2)
,D/audio_hw_hfp(  289): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  289): adev_set_parameters: exit
E/HeadsetStateMachine( 2712): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/TimaKeyStoreProvider( 3012): TimaSignature is unavailable
,D/ActivityThread( 3012): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10136/pid_1496/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10050/pid_2154/cgroup.procs: No such file or directory
,I/dhcpcd  ( 2223): wlan0: sending IPv6 Router Solicitation
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 57847(3MB) AllocSpace objects, 82(5MB) LOS objects, 33% free, 26MB/39MB, paused 2.215ms total 244.787ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/MediaScanner( 1228): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/Zygote  ( 3028): MountEmulatedStorage()
I/libpersona( 3028): KNOX_SDCARD checking this for 10157
E/Zygote  ( 3028): v2
I/libpersona( 3028): KNOX_SDCARD not a persona
I/SELinux ( 3028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3028 uid=10157 gids={50157, 9997} abi=armeabi-v7a
E/SELinux ( 3028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/BluetoothPbapService( 2712): Handler(): got msg=1
,D/SecContentProvider( 1015): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1453): query,matched:200, calling pid = 2355
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/TP/MmsSmsProvider( 1453): match 200:Elapsed time : 2.143 ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/BluetoothPbapService( 2712): PBAP Service initSocket try: 0
,W/ResourcesManager( 3012): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3012): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3012): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/Zygote  ( 3044): MountEmulatedStorage(),
E/Zygote  ( 3044): v2,
I/libpersona( 3044): KNOX_SDCARD checking this for 10048
I/SELinux ( 3044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3044): KNOX_SDCARD not a persona
,I/SELinux ( 3044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothMapMasInstance( 2712): set MAP SDP message type : 1
,I/ActivityManager( 1015): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3044 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/BluetoothSocket( 2712): bindListen(): myUserId = 0
W/BluetoothAdapter( 2712): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 2712): bindListen(): myUserId = 0
,W/BluetoothAdapter( 2712): getBluetoothService() called with no BluetoothManagerCallback
,D/TimaKeyStoreProvider( 3028): TimaSignature is unavailable
,D/BluetoothSocket( 2712): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2712): bindListen(), new LocalSocket 
D/BluetoothSocket( 2712): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2712): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f29f1af
,D/BluetoothSocket( 2712): channel: 5
D/BluetoothSocket( 2712): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2712): bindListen(), new LocalSocket 
D/BluetoothSocket( 2712): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2712): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28d969bc
,D/ActivityThread( 3028): Added TimaKeyStore provider
,D/BluetoothSocket( 2712): channel: 19
D/BluetoothPbapService( 2712): PBAP Socket is BluetoothServerSocket
,D/TimaKeyStoreProvider( 3044): TimaSignature is unavailable
,D/ActivityThread( 3044): Added TimaKeyStore provider
,D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2355
,D/TP/SmsProvider( 1453): match 0:Elapsed time : 4.695 ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2970): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/MediaScanner( 1228): processDirectory :  /system/media
,W/ResourcesManager( 3028): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 3064): MountEmulatedStorage(),
I/libpersona( 3064): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3064): v2
I/libpersona( 3064): KNOX_SDCARD not a persona
I/SELinux ( 3064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ResourcesManager( 3044): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
,I/SELinux ( 3064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourcesManager( 3044): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3044): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3064 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3064): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/SmsReceiverService( 2355): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2355): isDefault true
D/Mms/SmsReceiverService( 2355): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2355): [start]    handleBootCompleted() consume time = 457.916302
,D/TP/SmsProvider( 1453): query,matched:51, calling pid = 2355
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
D/TP/SmsProvider( 1453): match 51:Elapsed time : 1.578 ms
,I/SecureStorage( 2970): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2970
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,I/SecureStorage( 2970): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2970): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2970
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,V/MediaScanner( 1228):  prescan time: 533ms (DB items: 141)
V/MediaScanner( 1228):     scan time: 48ms (Caching mode: true), (makeEntry time: 31ms ~64%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1228): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1228):    total time: 581ms
V/MediaScanner( 1228): checked files: 133  directories : 6  (I: 0, U: 0)
,D/TimaKeyStoreProvider( 3064): TimaSignature is unavailable
D/MediaScanner( 1228): checkDefaultSounds
D/MediaScanner( 1228): system alarm_alert  : Vwiurug_etwofi5wgg
D/ActivityThread( 3064): Added TimaKeyStore provider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1228): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1228): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1228): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1228): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1228): OK. ringtone is already exist in setting DB.,
,E/Zygote  ( 3080): MountEmulatedStorage()
E/Zygote  ( 3080): v2
I/libpersona( 3080): KNOX_SDCARD checking this for 10159
I/libpersona( 3080): KNOX_SDCARD not a persona,
I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3080 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1015): Killing 2224:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
I/SELinux ( 3080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3080): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/MediaScannerService( 1228): !@done scanning volume internal
D/MediaScannerService( 1228): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/FactoryTestApp( 2691): [DummyFtClient$mBroadcastReceiver](2691) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2691): [DummyFtClient$mBroadcastReceiver](2691) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2691): [DummyFtClient$mBroadcastReceiver](2691) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/TP/MmsSmsProvider( 1453): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1453): deleteConversation threadId: 9223372036854775806
,D/TimaKeyStoreProvider( 3080): TimaSignature is unavailable
,D/ActivityThread( 3080): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 2355): isBlockingModeEnabled() = false, Zen mode = 0
,D/SettingsProvider( 1015): name = block_emergency_message
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10048
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/ActivityManager( 1015): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/TP/MmsSmsProvider( 1453): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1453): updateThread(), thread_id = 9223372036854775806
,V/TP/MmsSmsDatabaseHelper( 1453): sUpgradeVersion = 0, db.getVersion() = 81
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1453): (284) automatic index on im_threads(normal_thread_id)
,D/BadgeProvider( 1566): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TP/MmsSmsProvider( 1453): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
,D/Mms/Conversation( 2355): deleteTempConversation(),deleted=0
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/SmsProvider( 1453): Update uri=content://sms/outbox, match=8
,D/BadgeProvider( 1566): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1566): sendNotify, [notify] : null
D/BadgeProvider( 1566): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1566): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1566): update, [UpdateCount] : 1
,D/Launcher.Model( 1479): reloadBadges entered.
,D/ActivityManager( 1015): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/Mms/MessagingNotification( 2355): setBadgeCount(), count=0
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started
,I/WifiCredService( 1365): onCreate
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/TP/MmsSmsProvider( 1453): need read changed broadcast:false
,D/MediaProvider( 1228): savePlaylistTableInBulkDeleter finished
,D/Mms/MessagingNotification( 2355): remove alarm
,I/Intent to TravelDirActivity( 3080): inside TravelBroadcastReceiver
,E/SQLiteLog( 3064): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,D/Mms/SmsReceiverService( 2355): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2355): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2355): [SIM-1]sendFirstQueuedMessage()
,D/Mms/MessagingNotification( 2355): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1453): query,matched:26, calling pid = 2355
,D/MediaScanner( 1228): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/libprocessgroup( 1015): failed to open /acct/uid_10113/pid_2224/cgroup.procs: No such file or directory
,D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2355
,D/TP/SmsProvider( 1453): match 0:Elapsed time : 1.438 ms
,D/WifiTimerReceiver( 1365): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1365): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1365): Action boot completed received
,D/Mms/MessagingNotification( 2355): [end]    nonBlockingUpdateMessageIndicator() consume time = 180.836145
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
D/WifiCredService( 1365): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/DSM     ( 3064): [Lines:107] Normal booted
D/DSM     ( 3064): [Lines:114] Boot completed
,D/TP/SmsProvider( 1453): match 26:Elapsed time : 10.188 ms
,E/WifiStateMachine( 1015): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/WifiNative-wlan0( 1015): callSECStringApiVoid - ID [215]
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/WifiNative-wlan0( 1015): invaild command id : 215
,E/Zygote  ( 3100): MountEmulatedStorage()
,E/Zygote  ( 3100): v2
I/libpersona( 3100): KNOX_SDCARD checking this for 1000
I/libpersona( 3100): KNOX_SDCARD not a persona
,I/SELinux ( 3100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
V/MediaScanner( 1228): processDirectory :  /storage/emulated/0
,I/SELinux ( 3100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3100 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/SELinux ( 3100): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 1646:com.google.android.partnersetup/u0a15 (adj 15): empty #31
D/MediaScanner( 1228): Skipping:
D/MediaScanner( 1228): 7klwibgf7fvntblfd7(75ebcf7
D/MediaScanner( 1228): Skipping:
D/MediaScanner( 1228): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/MediaScanner( 1228): processDirectory :  /storage/extSdCard
W/MediaScanner( 1228): Error opening directory, reason : Permission denied.
W/MediaScanner( 1228): 7klwibgf7fxlKdCbid7
D/NearbySettings( 1365): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1365): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1365): MountReceiver.onReceive - Create mPrefHandler
,V/MediaScanner( 1228):  prescan time: 51ms (DB items: 27)
V/MediaScanner( 1228):     scan time: 25ms (Caching mode: true), (makeEntry time: 18ms ~72%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1228): postscan time: 6ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1228):    total time: 82ms
V/MediaScanner( 1228): checked files: 10  directories : 17  (I: 0, U: 0)
D/TimaKeyStoreProvider( 3100): TimaSignature is unavailable
D/NearbySettings( 1365): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/ActivityThread( 3100): Added TimaKeyStore provider
V/NearbySettings( 1365): MountReceiver.mPrefHandler - 7002
D/SettingsProvider( 1015): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
E/Zygote  ( 3117): MountEmulatedStorage()
E/Zygote  ( 3117): v2
I/libpersona( 3117): KNOX_SDCARD checking this for 1000
I/libpersona( 3117): KNOX_SDCARD not a persona
I/SELinux ( 3117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3117): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
I/NearbySettings( 1365): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/ActivityManager( 1015): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/NearbySettings( 1365): MountReceiver.onReceive - Internal Path
I/ActivityManager( 1015): Killing 2332:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/Mms/SmsReceiver( 2355): unregisterForServiceStateChanges, already unregistered
,D/Mms/MessagingNotification( 2355): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2355): isDefault true
D/MediaScannerService( 1228): !@done scanning volume external
,D/SettingsProvider( 1015): name = next_alarm_formatted
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10085
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
D/SettingsProvider( 1015): name = personal_mode_enabled
,D/FactoryTestApp( 2691): [DummyFtClient$mBroadcastReceiver](2691) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2691): [DummyFtClient$mBroadcastReceiver](2691) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2691): [DummyFtClient$sendBootCompletedAndFinish](2691) ...
D/FactoryTestApp( 2691): [Support$Values.getString](2691) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2691): [ModuleCommon$isConnectionModeNone](2691) mConnectionMode = gsm
D/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$ResponseWriter](2691) Create IPCWriterToSecPhoneService
W/ContextImpl( 2691): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
I/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$connectToSecPhoneService](2691)  
,D/ActivityManager( 1015): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
,D/TimaKeyStoreProvider( 3117): TimaSignature is unavailable
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,D/ActivityThread( 3117): Added TimaKeyStore provider
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,D/TP/MmsProvider( 1453): Query uri=content://mms, match=0, calling pid = 2355
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 28
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/ResourcesManager( 3117): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 1453): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/SMD     (  294): DCD OFF
,W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1453): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1453): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_1646/cgroup.procs: No such file or directory
,W/ActivityThread( 3117): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/Zygote  ( 3134): MountEmulatedStorage(),
E/Zygote  ( 3134): v2
I/libpersona( 3134): KNOX_SDCARD checking this for 10160
I/libpersona( 3134): KNOX_SDCARD not a persona,
,I/SELinux ( 3134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3134 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 3134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3134): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,I/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$onServiceConnected](2691) connected done
,D/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$write](2691) Send Response Message to SecPhone
,D/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$write](2691) Response ��
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2332/cgroup.procs: No such file or directory
,I/SmartcardBootCompleteReceiver( 1365): SmartcardBootCompleteReceiver - onReceive() 
,I/SmartcardBootCompleteReceiver( 1365): Received intent with action - android.intent.action.BOOT_COMPLETED
,I/art     ( 1453): Background sticky concurrent mark sweep GC freed 40639(2MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 8MB/11MB, paused 1.157ms total 111.627ms
,D/AT_Distributor(  331): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,I/art     ( 1453): WaitForGcToComplete blocked for 25.081ms for cause Explicit
,W/ContextImpl( 1365): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SmartcardBootCompleteReceiver( 1365): Broadcast sent with current lockscreen type
,D/TimaKeyStoreProvider( 3134): TimaSignature is unavailable
,D/ActivityThread( 3134): Added TimaKeyStore provider
,D/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$handleMessage](2691) Send BOOTING COMPLETED done
,W/ResourcesManager( 3134): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/[SBeam] ( 1365): SBeamEnabler.initPreferenceForSbeam : 0
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
I/art     ( 1453): Explicit concurrent mark sweep GC freed 1939(101KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 2.011ms total 62.235ms
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/TP/MmsSmsProvider( 1453): query,matched:200, calling pid = 2355
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/TP/MmsSmsProvider( 1453): match 200:Elapsed time : 1.846 ms
,D/LcdtestApp( 3117): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/LcdtestApp( 3117): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3152): MountEmulatedStorage(),
E/Zygote  ( 3152): v2
I/libpersona( 3152): KNOX_SDCARD checking this for 1000
I/libpersona( 3152): KNOX_SDCARD not a persona
,I/SELinux ( 3152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3152 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 2373:com.sec.android.omc/1000 (adj 15): empty #31
,D/AT_Distributor(  331): SetAtdStatus(), 1_1_0,
D/AT_Distributor(  331): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,E/SELinux ( 3152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SettingSearch/SearchIntentReceiver( 1365): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1365): search setting db init!!
,W/ContextImpl( 1365): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2355
,I/SettingSearch/SearchIntentReceiver( 1365): BOOT_COMPLETED call InitSerachDBThread thread start!
,W/art     ( 3012): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 219.781ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 28.490ms
,D/TP/SmsProvider( 1453): match 0:Elapsed time : 14.421 ms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 19.509ms
,D/[0]UMC:UMCContentProvider( 3134): @onCreate
,D/TimaKeyStoreProvider( 3152): TimaSignature is unavailable
D/BluetoothMediaBrowser( 2712):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
D/ActivityThread( 3152): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 17.955ms
,E/Zygote  ( 3168): MountEmulatedStorage(),
,E/Zygote  ( 3168): v2
I/libpersona( 3168): KNOX_SDCARD checking this for 1000
I/libpersona( 3168): KNOX_SDCARD not a persona
,I/SELinux ( 3168): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3168 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,I/SELinux ( 3168): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3168): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3181): MountEmulatedStorage(),
E/Zygote  ( 3181): v2
I/libpersona( 3181): KNOX_SDCARD checking this for 10150
I/SELinux ( 3181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3181): KNOX_SDCARD not a persona
,I/SELinux ( 3181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3181): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3168): TimaSignature is unavailable
,D/ActivityThread( 3168): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3181 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2373/cgroup.procs: No such file or directory
,D/BluetoothMediaBrowser( 2712): no now playing list
D/BluetoothMediaBrowser( 2712):  getNowPlayingId now playing id : -1
,D/TimaKeyStoreProvider( 3181): TimaSignature is unavailable
,D/[0]UMC:Core( 3134): onCreate(): 
D/[0]UMC:Core( 3134): @isManagedProfileUser
D/[0]UMC:Core( 3134): userId: 0
,W/ResourcesManager( 3168): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityThread( 3181): Added TimaKeyStore provider
,D/[0]UMC:Core( 3134): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 3134): userInfo.isManagedProfile() : false
,D/TP/SmsProvider( 1453): query,matched:51, calling pid = 2355
,D/TP/SmsProvider( 1453): match 51:Elapsed time : 1.386 ms
,D/Mms/MessagingNotification( 2355): isBlockingModeEnabled() = false, Zen mode = 0
,D/BadgeProvider( 1566): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/[0]UMC:DeviceInfo( 3134): USA==US==
,I/SecureStorage(  404): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,I/FOTA    ( 3168): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/SecureStorage( 2970): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2970): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,I/DIAGMON_AGENT( 3152): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/Launcher.Model( 1479): reloadBadges entered.
,D/BadgeProvider( 1566): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1566): sendNotify, [notify] : null
D/BadgeProvider( 1566): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1566): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1566): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 2355): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2355): remove alarm
,D/Mms/MessagingNotification( 2355): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1453): query,matched:0, calling pid = 2355
,D/TP/SmsProvider( 1453): match 0:Elapsed time : 1.569 ms
,D/Mms/SmsReceiverService( 2355): [end]    handleBootCompleted() consume time = 677.371406
,I/ActivityManager( 1015): Killing 2403:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/USER_AGENT( 3134): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
D/[0]UMC:AdminManager( 3134): init - start
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3203): MountEmulatedStorage()
E/Zygote  ( 3203): v2
I/libpersona( 3203): KNOX_SDCARD checking this for 1000
I/libpersona( 3203): KNOX_SDCARD not a persona
,D/[0]UMC:AdminManager( 3134): loadAdmins
I/SELinux ( 3203): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3203): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3203): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 2418:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10131/pid_2403/cgroup.procs: No such file or directory
D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1175): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1175): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/[0]UMC:AdminManager( 3134): init - end
,D/GSLBManager( 3134): migrateStoredUrlFromOldPref
,V/HeadsetService( 2712): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/TimaKeyStoreProvider( 3203): TimaSignature is unavailable
,D/HeadsetStateMachine( 2712): Disconnected process message: 10
,D/ActivityThread( 3203): Added TimaKeyStore provider
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ResourcesManager( 3203): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/GSLBManager( 3134): migrateStoredUrlFromOldPref : Migration Not Needed
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2418/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3168): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3168): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1015): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/[0]UMC:UMCAdmin( 3134): deactivateUMCAdminIfNotRequired : -1
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,E/[0]UMC:Utils( 3134): Admin not found in package com.samsung.knoxpb.mdm
I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,E/[0]UMC:Utils( 3134): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3134): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3134): isContainer : 0
,I/DIAGMON_AGENT( 3152): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/OverheatReceiver( 1175): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1175): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1175): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1175): isSafeMode = false
,D/BootupListener( 1453): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1015): name = internet_call_settings_visibility
,I/DIAGMON_AGENT( 3152): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
,D/SettingsProvider( 1015): selectionArgs: 1001
,D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/DIAGMON_AGENT( 3152): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,D/PhoneUtilsCommon( 1453): isSupportVoLTE is false.
,I/DIAGMON_AGENT( 3152): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,I/DIAGMON_AGENT( 3152): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 3152): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/EnterpriseDeviceManagerService( 1015): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 3134): No active admin owned by uid 10160
,D/[0]UMC:UMCAdmin( 3134): isContainer : 0
,I/Telecom ( 1424): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1015): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,D/[0]UMC:UMCAdmin( 3134): deactivateUMCAdmin - UMC App Admin deactivated
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,D/ActivityManager( 1015): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,D/ActivityManager( 1015): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,D/[0]UMC:GuardService( 3134): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/[0]UMC:CoreReceiver( 3134): Intent : android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/[0]UMC:CoreReceiver( 3134):  check PreETag 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3168): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 3168): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 3168): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,E/Zygote  ( 3222): MountEmulatedStorage()
E/Zygote  ( 3222): v2
I/libpersona( 3222): KNOX_SDCARD checking this for 10057
I/libpersona( 3222): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3168): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/SELinux ( 3222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/DBG_DM  ( 3168): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
E/SELinux ( 3222): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3222 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/Telecom ( 1424): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3168): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 3168): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3168): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,D/TimaKeyStoreProvider( 3222): TimaSignature is unavailable
,D/ActivityThread( 3222): Added TimaKeyStore provider
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,E/Zygote  ( 3238): MountEmulatedStorage()
E/Zygote  ( 3238): v2
I/libpersona( 3238): KNOX_SDCARD checking this for 10086
I/libpersona( 3238): KNOX_SDCARD not a persona
,I/SELinux ( 3238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3238 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 3238): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 2325:com.sec.android.app.mt/1000 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:CoreReceiver( 3134): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 3134): Enter loadList
,D/[0]UMC:CoreReceiver( 3134): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 3134): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 3134): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 3134): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3134): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3134): isContainer : 0
,D/EnterpriseDeviceManagerService( 1015): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 3134): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 3134): isContainer : 0
D/TimaKeyStoreProvider( 3238): TimaSignature is unavailable
,D/ActivityThread( 3238): Added TimaKeyStore provider
E/Zygote  ( 3255): MountEmulatedStorage()
I/libpersona( 3255): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3255): v2
I/libpersona( 3255): KNOX_SDCARD not a persona
I/SELinux ( 3255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/[0]UMC:UMCAdmin( 3134): deactivateUMCAdmin - UMC App Admin deactivated
I/ActivityManager( 1015): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3255 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 1566:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/[0]UMC:ByodSetupStarter( 3134): Container ID : 0
,V/[0]UMC:Utils( 3134): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 3134): shutdown
,D/TimaKeyStoreProvider( 3255): TimaSignature is unavailable
D/ActivityThread( 3255): Added TimaKeyStore provider
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 29
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,V/audio_hw_primary(  289): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  289): audio_extn_get_parameters: returns 
V/msm8974_platform(  289): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  289): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  289): key: 'call_forwarding' value: ''
,V/InCall  ( 1972): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1972): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1972): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
D/[0]UMC:GuardService( 3134): @GuardService - stopService Result = true
,I/DBG_DM  ( 3168): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3168): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/ScoverManager( 1972): serviceVersion : 16908288
I/art     ( 3134): System.exit called, status: 0
I/AndroidRuntime( 3134): VM exiting with result code 0, cleanup skipped.
D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1972): InCallUtils - isCoverClosed false
,I/Telecom ( 1424): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1972): InCallUtils - isCoverClosed false
I/InCall  ( 1972): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1972): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1972): InCallPresenter -  - dismissCoverDialog()...
I/DBG_DM  ( 3168): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/InCall  ( 1972): CallSContextMotion - stopPutDownListening
D/InCall  ( 1972): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/PhoneStatusBarView( 1175): setCallBackground:0
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1972): InCallUtils - isCoverClosed false
,D/BluetoothAdapter( 2490): disable()
,D/SettingsProvider( 1015): name = bluetooth_on
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2325/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10072/pid_1566/cgroup.procs: No such file or directory
,D/BluetoothAdapterState( 2712): CURRENT_STATE=ON, MSG = USER_TURN_OFF,
D/BluetoothAdapterProperties( 2712): Setting state to 13
I/BluetoothAdapterState( 2712): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2712): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2712): updateAdapterState state is 13
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: false pid=2490, uid=10174
,D/SettingsProvider( 1015): name = wifi_on
,I/ActivityManager( 1015): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3134)(adj 0) has died(262,1007)
,E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 2027): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2027): wlan0: Setting scan request: 0 sec 0 usec
,I/jxcore-log( 2490): ****TEST TOOK:  5128  ms ****
I/jxcore-log( 2490): 
I/wpa_supplicant( 2027): P2P: Current p2p state = IDLE
I/jxcore-log( 2490): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 2490): 
I/wpa_supplicant( 2027): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,E/ConnectivityService( 1015): updateNetworkInfo()
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 3168): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED,
D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1015): InactiveState{ what=131204 },
D/WifiP2pService( 1015): P2pEnabledState{ what=131204 }
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
D/WifiP2pService( 1015): sending p2p connection changed broadcast: FAILED
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 15577(832KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.609ms total 206.749ms
D/VideoCallManager( 1972): Instantiating VideoCallManager
,E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,I/GFX construct_block_size_descriptor_2d second part( 1972): took 2.503125ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1972): took 5.210781ms for 0*0 texture 0
,I/GFX raster( 1972): took 12.162240ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb8544788 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb855c998 counterpartCT=4 counterpartW=176 counterparth=144
,D/WifiScanningService( 1015): SCAN_AVAILABLE : 1
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RttService( 1015): SCAN_AVAILABLE : 1
D/RttService( 1015): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1015): sending p2p connection changed broadcast: DISCONNECTED
D/WifiScanningService( 1015): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,E/Tethering( 1015): No numeric data
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
D/WifiP2pService( 1015): P2pDisablingState
D/WifiP2pService( 1015): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1015): p2p socket connection lost
,E/BluetoothHeadset( 2970): BTStateChangeCB is registed
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/WifiP2pService( 1015): P2pDisabledState
E/Tethering( 1015): No numeric data
D/WifiP2pService( 1015): P2pDisabledState{ what=143375 }
D/WifiP2pService( 1015): DefaultState{ what=143375 }
,D/BluetoothHeadset( 2970): doBind(): CallingUid(myUserHandle) = 0
E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1972): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1972): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1972): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1972): Local Branch: 
I/Adreno-EGL( 1972): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1972): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1972):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/Tethering( 1015): No numeric data
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/Tethering( 1015): No numeric data
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,I/BluetoothPbapService( 2712): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/comsamsunglog( 1305): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1305): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1305): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1305): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
I/GFX GPU raster( 1972): eglCreateImageKHR: EGL_SUCCESS
,D/BluetoothSocket( 2712): close() in, this: android.bluetooth.BluetoothSocket@26317d45, channel: 19, state: LISTENING
D/BluetoothSocket( 2712): close() this: android.bluetooth.BluetoothSocket@26317d45, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28d969bc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f9b8c9amSocket: android.net.LocalSocket@132df9cb impl:android.net.LocalSocketImpl@2ab165a8 fd:FileDescriptor[76]
D/BluetoothSocket( 2712): Closing mSocket: android.net.LocalSocket@132df9cb impl:android.net.LocalSocketImpl@2ab165a8 fd:FileDescriptor[76]
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
D/BluetoothAdapterService( 2712): Autoconnection is available 
D/BluetoothAdapterService( 2712): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2712): terminating service from this receiver
,I/glCompressedTexImage2D( 1972): took 0.259167ms for 320*61440 texture 37809
D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1015): onP2pDisconnected
D/IpRemoteDisplayController( 1015): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1015): WfdBridgeServer is already null
E/WifiStateMachine( 1015): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController( 1015): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1015): disconnect
D/WifiDisplayController( 1015): updateConnection
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  277): Clearing all IP addresses on wlan0
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ActivityManager( 1015): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ConnectivityManager.CallbackHandler( 2055): CM callback handler got msg 524292
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,E/Tethering( 1015): No numeric data
D/TelephonyNetworkFactory( 1453): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1453): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/draw setup( 1972): took 11.812292ms for 320*240 texture 37809
E/GFX GPU raster( 1972): drawn
E/BluetoothHeadset( 2970): BluetoothHeadset service is binded
,D/BluetoothAdapterProperties( 2712): onBluetoothDisable()
D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.110/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/BluetoothAdapterProperties( 2712): mDiscovering is false
I/GFX GPU raster ASTC( 1972): took 53.505313ms for 320*240 texture 12
I/GFX raster( 1972): took 53.555730ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb855c998 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb855ecd8 counterpartCT=4 counterpartW=320 counterparth=240
D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/BluetoothAdapterState( 2712): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothA2dp( 2970): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1015): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
I/wpa_supplicant( 2027): p2p0: State: DISCONNECTED -> DISCONNECTED
,E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
E/Tethering( 1015): No numeric data
,I/GFX GPU raster( 1972): eglCreateImageKHR: EGL_SUCCESS,
D/SettingsProvider( 1015): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10162
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
I/glCompressedTexImage2D( 1972): took 0.335104ms for 480*122880 texture 37813
I/draw setup( 1972): took 0.653593ms for 480*640 texture 37813
E/GFX GPU raster( 1972): drawn
D/BluetoothUtils( 2712): getBtEnabledContainers(): btContainers = []
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2712): Scan Mode:20
,I/GFX GPU raster ASTC( 1972): took 6.771355ms for 480*640 texture 12
I/GFX raster( 1972): took 6.856929ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb855ecd8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb878d168 counterpartCT=4 counterpartW=480 counterparth=640
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
I/InputMethodManagerService( 1015): [BT Setting State] State =13
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/BluetoothTile( 1175):  onBluetoothStateChange:
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,D/BluetoothTile( 1175):  handleUpdatestate:false name:null
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  getBluetoothState : 13
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
D/AllShareCastTile( 1175): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1175): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Bluetooth
,E/UpdateRequestReceiver( 3238): ignoring update request
I/SamsungIME( 1784): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
E/ConnectivityService( 1015): updateNetworkInfo()
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1972): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1972): took 0.319531ms for 440*116864 texture 37809
I/draw setup( 1972): took 0.650156ms for 440*330 texture 37809
E/GFX GPU raster( 1972): drawn
,I/DBG_DM  ( 3168): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/GFX GPU raster ASTC( 1972): took 4.253646ms for 440*330 texture 12
I/GFX raster( 1972): took 4.338177ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb878d168 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb87a1558 counterpartCT=4 counterpartW=440 counterparth=330
D/daemonapp( 1305): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1305): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1305): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
E/daemonapp( 1305): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,V/NetworkStats( 1015): updateIfacesLocked()
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/GFX GPU raster( 1972): eglCreateImageKHR: EGL_SUCCESS
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
I/glCompressedTexImage2D( 1972): took 0.417552ms for 480*163840 texture 37811
I/draw setup( 1972): took 0.800312ms for 480*640 texture 37811
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/GFX GPU raster( 1972): drawn
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,I/GFX GPU raster ASTC( 1972): took 5.977240ms for 480*640 texture 12
I/GFX raster( 1972): took 6.049167ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb8791368 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb87a1090 counterpartCT=4 counterpartW=480 counterparth=640
D/daemonapp( 1305): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1456842789366
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1456864380000
D/daemonapp( 1305): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1305): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,V/NetworkStats( 1015): performPollLocked() took 10ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/BluetoothAdapterState( 2712): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2712): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
,I/wpa_supplicant( 2027): Blacklist: Clear (all) 
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,E/bt-btif ( 2712): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/bt-btif ( 2712): cmd socket is not created
,E/bt-btm  ( 2712): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2712): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2712): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x001b not found for deregistration
D/btif_config_util( 2712): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/AndroidRuntime( 3279): 
D/AndroidRuntime( 3279): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,V/AlarmManager( 1015): waitForAlarm result :8
,D/AndroidRuntime( 3279): CheckJNI is OFF
,D/AndroidRuntime( 3279): readGMSProperty: start
D/AndroidRuntime( 3279): readGMSProperty: already setted!!
D/AndroidRuntime( 3279): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3279): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3279): readGMSProperty: end
D/AndroidRuntime( 3279): addProductProperty: start
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(0)
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
,D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1175): onReceive : 0, 0
,D/WifiCredService( 1365): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/wpa_supplicant( 2027): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1015): interfaceStatusChanged p2p0, false
,E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1972): took 2.311198ms for 0*0 texture 0
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/daemonapp( 1305): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1456864380000
,D/BluetoothSocket( 2712): close() in, this: android.bluetooth.BluetoothSocket@3215d866, channel: 5, state: LISTENING
,D/BluetoothSocket( 2712): close() this: android.bluetooth.BluetoothSocket@3215d866, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f29f1af, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2067a7mSocket: android.net.LocalSocket@3f8b3454 impl:android.net.LocalSocketImpl@52f0ffd fd:FileDescriptor[74]
,D/BluetoothSocket( 2712): Closing mSocket: android.net.LocalSocket@3f8b3454 impl:android.net.LocalSocketImpl@52f0ffd fd:FileDescriptor[74],
I/wpa_supplicant( 2027): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,I/wpa_supplicant( 2027): wlan0: State: COMPLETED -> DISCONNECTED
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 2027): Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
I/wpa_supplicant( 2027): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 2027): wlan0: State: DISCONNECTED -> DISCONNECTED
I/GFX generate_partition_tables( 1972): took 7.422343ms for 0*0 texture 0,
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/daemonapp( 1305): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
D/daemonapp( 1305): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1456864380000
,D/Tethering( 1015): InitialState.processMessage what=4
,I/GFX raster( 1972): took 11.795206ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb878aa28 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb878ab48 counterpartCT=4 counterpartW=176 counterparth=144
,E/Tethering( 1015): No numeric data,
,E/        ( 1972): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,I/GFX construct_block_size_descriptor_2d second part( 1972): took 2.157708ms for 0*0 texture 0,
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): clearTetheredNotification()
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit,
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 4ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/GFX generate_partition_tables( 1972): took 6.338125ms for 0*0 texture 0
D/HotspotTile( 1175): updateTetherState():false, false
,I/GFX raster( 1972): took 10.652344ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1972): Bitmap=0xb878ad68 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb878ad08 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1972): registerListener
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH,
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1015): registerListenerCallback : binder = android.os.BinderProxy@32a0b564, pid : 1972, uid : 1001, type : 1
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/UpdateRequestReceiver( 3238): ignoring update request
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0,
I/DBG_DM  ( 3168): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/comdaemonstockapp( 1305): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1305): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/Zygote  ( 3302): MountEmulatedStorage()
E/Zygote  ( 3302): v2
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3302 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 3302): KNOX_SDCARD checking this for 10009
I/libpersona( 3302): KNOX_SDCARD not a persona
I/SELinux ( 3302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3302): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/InCall  ( 1972): InCallPresenter -  - Finished InCallPresenter.setUp
,W/bt-l2cap( 2712): btif_mce_execute_se not found for deregistration
W/bt-l2cap( 2712): HC lib lpm enable=0 return 0
W/bt-l2cap( 2712): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2712): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2712): ag scb idx 1 not allocated
W/bt-btif ( 2712): ag scb idx 2 not allocated
E/bt-btif ( 2712): BTA AG is already disabled, ignoring ...
,I/bt_userial_mct( 2712): exiting userial_read_thread
D/bt_userial_mct( 2712): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2712): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2712): hw_epilog_process
D/bt_userial_mct( 2712): userial_close
I/bt_vendor( 2712): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/AffinityControl( 3279): AffinityControl: registerfunction enter
,E/UpdateRequestReceiver( 3238): ignoring update request
,I/wpa_supplicant( 2027): Blacklist: Clear (all) 
,I/ActivityManager( 1015): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3320 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 3320): MountEmulatedStorage()
I/libpersona( 3320): KNOX_SDCARD checking this for 10166
E/Zygote  ( 3320): v2
I/libpersona( 3320): KNOX_SDCARD not a persona
,I/SELinux ( 3320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3320): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 3279): Calling main entry com.android.commands.pm.Pm,
,D/TimaKeyStoreProvider( 3302): TimaSignature is unavailable
,D/ActivityThread( 3302): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 3238): ignoring update request
,D/PackageManager( 1015): START PACKAGE DELETE: observer{999932160}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
,D/TimaKeyStoreProvider( 3320): TimaSignature is unavailable
,D/ActivityThread( 3320): Added TimaKeyStore provider
,D/PackageManager( 1015): !@killApplicatoin: 10174, uninstall pkg
,I/DBG_POLICYDM( 3255): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/ActivityManager( 1015): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/DBG_POLICYDM( 3255): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
I/ActivityManager( 1015): Killing 2490:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,E/UpdateRequestReceiver( 3238): ignoring update request
,I/DBG_POLICYDM( 3255): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3255): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/wpa_supplicant( 2027): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/DBG_POLICYDM( 3255): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 3255): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3255): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/bt_vendor( 2712): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2712): bluetooth satus is on
I/bt_vendor( 2712): bt-vendor : resetting BT status
I/bt_vendor( 2712): Starting hciattach daemon
I/bt_vendor( 2712): try to set false
,I/bt_vendor( 2712): Starting hciattach daemon
I/bt_vendor( 2712): try to set false
,I/bt_vendor( 2712): cleanup
,I/GKI_LINUX( 2712): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2712): GKI_exit_task 0 done
I/GKI_LINUX( 2712): GKI_shutdown(): task [BTU] terminated
,I/WindowState( 1015): WIN DEATH: Window{34d2d87c u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,W/PackageSettings( 1015): Skipping PackageSetting{3016f90d com.test.thalitest/10155} due to missing metadata
,D/InputDispatcher( 1015): Focus left window: 2490
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/DBG_POLICYDM( 3255): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3255): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3255): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,W/ActivityManager( 1015): Force removing ActivityRecord{26f47dfd u0 com.example.hello/.MainActivity t7}: app died, no saved state
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/FocusedStackFrame( 1015): Set to : 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/[SBeam] ( 1365): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1365): SBeamEnabler.isSBeamSupported : EXIST
,V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
W/ActivityManager( 1015): Spurious death for ProcessRecord{1859ed2c 2490:com.example.hello/u0a174}, curProc for 2490: null
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [21]
,E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/BluetoothAdapterState( 2712): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2712): isSecureModeOn:false
D/BluetoothAdapterService( 2712): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.gatt.GattService
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10174 user=0: pkg removed
,E/Tethering( 1015): No numeric data
,E/UpdateRequestReceiver( 3238): ignoring update request
,D/Launcher( 1479): onRestart, Launcher: 957063481
,E/Tethering( 1015): No numeric data
,E/Tethering( 1015): No numeric data
,E/Tethering( 1015): No numeric data
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,E/USB_UICC(  303): Timeout! No signal received. Retry num = 30
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService( 1015): getProviders()=[passive]
,E/Zygote  ( 3356): MountEmulatedStorage()
,E/Zygote  ( 3356): v2
I/libpersona( 3356): KNOX_SDCARD checking this for 10015
I/libpersona( 3356): KNOX_SDCARD not a persona
I/SELinux ( 3356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3356 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3356): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BtGatt.DebugUtils( 2712): handleDebugAction() action=null
W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
D/BtGatt.GattService( 2712): Received stop request...Stopping profile...
D/BtGatt.GattService( 2712): stop()
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.AdvertiseManager( 2712): advertise clients cleared
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3372): MountEmulatedStorage()
E/Zygote  ( 3372): v2
,I/libpersona( 3372): KNOX_SDCARD checking this for 10092
I/libpersona( 3372): KNOX_SDCARD not a persona
,I/SELinux ( 3372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3372): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,I/ActivityManager( 1015): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3372 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/Launcher( 1479): onStart, Launcher: 957063481
D/Launcher.HomeView( 1479): onStart
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
D/Launcher( 1479): onResume, Launcher: 957063481
,E/USB_UICC(  303): Timeout! No signal received. Reach maximum retries!
,E/USB_UICC(  303): usb_uicc_init_qmi failed ! 
I/USB_UICC(  303): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  303): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/SettingsProvider( 1015): name = kids_home_mode
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10007
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/TimaKeyStoreProvider( 3356): TimaSignature is unavailable
,D/ActivityThread( 3356): Added TimaKeyStore provider
D/Launcher.HomeView( 1479): onResume
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/TimaKeyStoreProvider( 3372): TimaSignature is unavailable
D/ActivityThread( 3372): Added TimaKeyStore provider
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/NotificationAccessSettings( 1365): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.hid.HidService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/VibratorService( 1015): hasVibrator - useVibetonz: true
,D/HeadsetService( 2712): Received stop request...Stopping profile...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 1
,D/MenuAppsGridFragment( 1479): onResume
,D/ActivityManager( 1015): handle home activity for 0
I/WallpaperManagerService( 1015): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1015): post home show event for user 0
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1015):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1015): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.hdp.HealthService
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BluetoothA2dp( 2970): Proxy object connected
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.pan.PanService
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
I/ApplicationPolicy( 1015): updateDataUsageMap
,D/InputDispatcher( 1015): Focus entered window: 1479
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 1479): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ResourcesManager( 1365): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 2490 uid 10174
,I/DBG_DM  ( 3168): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1784): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/Timeline( 1479): Timeline: Activity_idle id: android.os.BinderProxy@18e39c22 time:37188
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,E/SamsungIME( 1784): mOCRHelper is null
,W/ResourcesManager( 3320): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3320): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1901): Ignoring removeGeofence because network location is disabled.
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiCredService( 1365): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1175): Wifi onReceive(1)
D/HotspotTile( 1175): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1175): onStateChanged: Wi-Fi
,D/HotspotTile( 1175): onReceive : 1, 0
,W/Settings( 1901): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2712): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/ActivityManager( 1015): Displayed Component not be shown by security: +460ms
,D/RegisteredComponentCache( 1439): Collect Tech packages for Knox
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2712): Not skipping com.broadcom.bt.service.sap.SapService
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,W/TRThreadPoolExecutor( 3222): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3222): Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3222): Task "NotifyOnDoneFutureTask[refresh_auth_tokens]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3222): Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/SearchServiceFactory( 3222): refreshing search history.
,D/ActivityManager( 1015): startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/ActivityManager( 1015): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/TRThreadPoolExecutor( 3222): Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2712): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2712): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,D/BluetoothAdapterState( 2712): Stopping profile services that were post enabled
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 2712): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2712): Exit Disconnected: -1
,D/Tethering( 1015): interfaceRemoved wlan0
E/Tethering( 1015): attempting to remove unknown iface (wlan0), ignoring
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,D/ScoverManager( 1365): serviceVersion : 16908288
W/TextServicesManagerService( 1015): no available spell checker services found
,D/PersonaManager( 1439): isKioskContainerExistOnDevice
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 39375(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 4.322ms total 499.248ms
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/BluetoothA2dp( 2970): Proxy object disconnected
,D/PackageManager( 1015): delete codoeFile: 
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
I/AASA_removePackage( 1015): UID=10174 Target=com.example.hello
,D/PackageManager( 1015): result of delete: 1{999932160}
,D/HidService( 2712): Received stop request...Stopping profile...
D/HidService( 2712): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2712): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2712): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2712): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,V/JNIHelp ( 3320): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/AndroidRuntime( 3279): Shutting down VM
,D/Tethering( 1015): interfaceRemoved p2p0
,E/Tethering( 1015): attempting to remove unknown iface (p2p0), ignoring
,D/RegisteredServicesCache( 1439): empty dynamic service
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/GLSActivity( 1901): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1901): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 3320): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3320): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26317d45: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3320): Installed default security provider GmsCore_OpenSSL
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2712): Profile still running: com.android.bluetooth.hid.HidService
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/BluetoothHeadsetServiceJni( 2712): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2712): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2712): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
I/ServiceManager(  335): Waiting for service AtCmdFwd...,
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PanService( 2712): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/BluetoothMapService( 2712): Received stop request...Stopping profile...
,W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1015): Killing 2450:com.wsomacp/u0a25 (adj 15): empty #31
,I/DBG_DM  ( 3168): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,D/SapService( 2712): Received stop request...Stopping profile...
,D/SapService( 2712): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2712): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5525e3d
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 2712): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2712): Proxy object disconnected
D/BluetoothAdapterService( 2712): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2712): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2712): GKI_exit_task 2 done
I/GKI_LINUX( 2712): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2712): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2712): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2712): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2712): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2712): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2712): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2712): Cleaning up Bluetooth PAN callback object
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2712): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2712): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(89284157)( 2712): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2712): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2712): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/BluetoothAdapterState( 2712): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2712): Setting state to 10
I/BluetoothAdapterState( 2712): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2712): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2712): updateAdapterState state is 10
,D/BluetoothAdapterService( 2712): Autoconnection is available 
D/BluetoothAdapterService( 2712): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2712): Entering OffState
D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 2712): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2712): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1453): onBluetoothStateChange: up=false
D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
D/BluetoothAdapter( 1453): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1439): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1439): Bluetooth is turned off, stop adv and scan
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothA2dp( 2712): onBluetoothStateChange: up=false
,W/art     ( 3279): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{67869c3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t6} time:37746
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,E/Zygote  ( 3436): MountEmulatedStorage()
E/Zygote  ( 3436): v2
I/libpersona( 3436): KNOX_SDCARD checking this for 1000
I/libpersona( 3436): KNOX_SDCARD not a persona
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/SELinux ( 3436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,I/ActivityManager( 1015): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3436 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Killing 2576:com.sec.android.app.camera/u0a139 (adj 15): empty #31,
I/ActivityManager( 1015): Killing 2541:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
I/ActivityManager( 1015): Killing 2521:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #33
,E/SELinux ( 3436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/BluetoothAdapter( 1015): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1015): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1901): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1901): Bluetooth is turned off, stop adv and scan
,I/ActivityManager( 1015): Killing 2642:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
D/BluetoothAdapter( 1424): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1424): Bluetooth is turned off, stop adv and scan
I/art     (  315): Explicit concurrent mark sweep GC freed 8725(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 25.249ms
,D/BluetoothA2dp( 2970): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2970): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2970): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1175): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1175): Bluetooth is turned off, stop adv and scan
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.131ms
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 8 receivers.
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 17.319ms
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/TimaKeyStoreProvider( 3436): TimaSignature is unavailable
,D/ActivityThread( 3436): Added TimaKeyStore provider
,D/BluetoothAdapter( 1175): 544148690: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1175):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1175): 544148690: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1175): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1175):  getBluetoothState : 10
,D/BluetoothAdapter( 1175): 544148690: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1175): 544148690: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/BluetoothAdapter( 1175): 544148690: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1175): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/TRThreadPoolExecutor( 3222): Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/SamsungIME( 1784): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/GKI_LINUX( 2712): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2712): GKI_exit_task 1 done
I/GKI_LINUX( 2712): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2712): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1901): 861571157: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1901): 861571157: getState() :  mService = null. Returning STATE_OFF
E/SMD     (  294): DCD OFF
,I/art     ( 2712): System.exit called, status: 0
,I/AndroidRuntime( 2712): VM exiting with result code 0, cleanup skipped.
,D/ActivityManager( 1015): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_FMMDM( 3436): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,E/Zygote  ( 3460): MountEmulatedStorage()
E/Zygote  ( 3460): v2
I/libpersona( 3460): KNOX_SDCARD checking this for 10092
I/libpersona( 3460): KNOX_SDCARD not a persona
,I/SELinux ( 3460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3460): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/ActivityManager( 1015): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3460 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_FMMDM( 3436): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3436): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
W/FileUtils( 2674): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/DBG_FMMDM( 3436): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
I/WebViewFactory( 3222): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
W/FileUtils( 3372): Failed to chmod(/data/data/com.dropbox.android/databases/prefs.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,I/ActivityManager( 1015): Process com.android.bluetooth (pid 2712)(adj 0) has died(296,1003)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 3372): (28) failed to open "/data/data/com.dropbox.android/databases/prefs.db" with flag (131138) and mode_t (0) due to error (30)
I/FactoryTestApp( 2691): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3147)  
,E/SQLiteDatabase( 3372): Failed to open database '/data/data/com.dropbox.android/databases/prefs.db'.
E/SQLiteDatabase( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.e(panda.py:270)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:97)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteDatabase( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 3372): Couldn't open prefs.db for writing (will try read-only):
E/SQLiteOpenHelper( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3372): 	at android.databa,se.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.e(panda.py:270)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:97)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteOpenHelper( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 3372): Opened prefs.db in read-only mode
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,D/TimaKeyStoreProvider( 3460): TimaSignature is unavailable
,D/ActivityThread( 3460): Added TimaKeyStore provider
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
,D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1015): PackageReceiver onReceive()
,D/PanelView( 1175): There is/are notification(s) 
,I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
,E/Zygote  ( 3477): MountEmulatedStorage()
,E/Zygote  ( 3477): v2
I/libpersona( 3477): KNOX_SDCARD checking this for 1000
I/libpersona( 3477): KNOX_SDCARD not a persona
,E/SQLiteLog( 3372): (28) failed to open "/data/data/com.dropbox.android/databases/prefs.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3372): Failed to open database '/data/data/com.dropbox.android/databases/prefs.db'.
E/SQLiteDatabase( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.b(panda.py:139)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:102)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteDatabase( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 3372): Couldn't open prefs.db for writing (will try read-only):
,E/SQLiteOpenHelper( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878),
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteOpenHelper( 3372): 	,at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.b(panda.py:139)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:102)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteOpenHelper( 3372): 	,at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteOpenHelper( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3372): ,	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 3372): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/ActivityManager( 1015): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/SQLiteOpenHelper( 3372): Opened prefs.db in read-only mode
,I/SELinux ( 3477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/SQLiteLog( 3372): (28) failed to open "/data/data/com.dropbox.android/databases/prefs.db" with flag (131138) and mode_t (0) due to error (30)
,I/SELinux ( 3477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SQLiteDatabase( 3372): Failed to open database '/data/data/com.dropbox.android/databases/prefs.db'.
E/SQLiteDatabase( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.c(panda.py:209)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:112)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteDatabase( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SELinux ( 3477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteOpenHelper( 3372): Couldn't open prefs.db for writing (will try read-only):
E/SQLiteOpenHelper( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.c(panda.py:209)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:112)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteOpenHelper( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 3372): Opened prefs.db in read-only mode
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/SQLiteLog( 3372): (28) failed to open "/data/data/com.dropbox.android/databases/prefs.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3372): Failed to open database '/data/data/com.dropbox.android/databases/prefs.db'.
E/SQLiteDatabase( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteDatabase( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.d(panda.py:238)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.util.l.a(panda.py:117)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteDatabase( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteDatabase( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteLog( 1015): (28) failed to open "/data/system/OtpDatabase.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteOpenHelper( 3372): Couldn't open prefs.db for writing (will try read-only):
E/SQLiteOpenHelper( 3372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 3372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 3372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 3372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.provider.a.a(panda.py:145)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
E/SQLiteOpenHelper( 3372): 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:290)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.d(panda.py:238)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.util.l.a(panda.py:117)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.c(panda.py:338)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.b.<init>(panda.py:275)
E/SQLiteOpenHelper( 3372): 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
E/SQLiteOpenHelper( 3372): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 3372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3372): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 3372): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 3372): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 3372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLi,teConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 3372): Opened prefs.db in read-only mode
E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.andro,id.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2674): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
W/FileUtils( 3372): Failed to chmod(/data/data/com.dropbox.android/app_bromo): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)
E/File    ( 3372): fail readDirectory() errno=2
E/SQLiteDatabase( 2674): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2674): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2674): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2674): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2674): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2674): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2674): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2674): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 1015): Failed to open database '/data/system/OtpDatabase.db'.
E/SQLiteDatabase( 1015): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 1015): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1015): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1015): 	at com.android.server.enterprise.otp.engine.handler.db.DBHandler.<init>(DBHandler.java:40)
E/SQLiteDatabase( 1015): 	at com.android.server.enterprise.otp.engine.handler.db.DBHandler.getInstance(DBHandler.java:47)
E/SQLiteDatabase( 1015): 	at com.android.server.enterprise.otp.PackageRemovalReceiver.onReceive(PackageRemovalReceiver.java:25)
E/SQLiteDatabase( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
E/SQLiteDatabase( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 1015): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 1015): 	at com.android.server.SystemServer.run(SystemServer.java:445)
E/SQLiteDatabase( 1015): 	at com.android.server.SystemServer.main(SystemServer.java:329)
E/SQLiteDatabase( 1015): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 1015): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 1015): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 1015): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 1015): Shutting down VM
E/AndroidRuntime( 1015): *** FATAL EXCEPTION IN SYSTEM PROCESS: main
E/AndroidRuntime( 1015): java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) } in com.android.server.enterprise.otp.PackageRemovalReceiver@6da1f05
E/AndroidRuntime( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:943)
E/AndroidRuntime( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 1015): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 1015): 	at com.android.server.SystemServer.run(SystemServer.java:445)
E/AndroidRuntime( 1015): 	at com.android.server.SystemServer.main(SystemServer.java:329)
E/AndroidRuntime( 1015): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1015): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1015): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 1015): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 1015): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 1015): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 1015): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 1015): 	at com.android.server.enterprise.otp.engine.handler.db.DBHandler.<init>(DBHandler.java:40)
E/AndroidRuntime( 1015): 	at com.android.server.enterprise.otp.engine.handler.db.DBHandler.getInstance(DBHandler.java:47)
E/AndroidRuntime( 1015): 	at com.android.server.enterprise.otp.PackageRemovalReceiver.onReceive(PackageRemovalReceiver.java:25)
E/AndroidRuntime( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
E/AndroidRuntime( 1015): 	... 9 more

```
