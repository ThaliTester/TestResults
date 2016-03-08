#### Test 6170335145aca32_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/AudioManagerAndroid( 2190): Requires BLUETOOTH permission
I/NSApplication( 2190): Starting up...
D/SettingsProvider( 1014): name = vibrate_in_silent
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
--------- beginning of system
W/ResourcesManager( 1452): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/CscReceiver( 1452): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1452): Recieve Sim State Changed : ABSENT
I/splitIntent( 1014): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1014): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1452, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2254): MountEmulatedStorage()
I/libpersona( 2254): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2254): v2
I/libpersona( 2254): KNOX_SDCARD not a persona
I/SELinux ( 2254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2254 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
E/SELinux ( 2254): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/WifiApBroadcastReceiver( 1282): onReceive: action android.intent.action.SIM_STATE_CHANGED
E/Zygote  ( 2263): MountEmulatedStorage()
E/Zygote  ( 2263): v2
I/libpersona( 2263): KNOX_SDCARD checking this for 1000
I/libpersona( 2263): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2263 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2254): TimaSignature is unavailable
I/SELinux ( 2263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityThread( 2254): Added TimaKeyStore provider
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SELinux ( 2263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
D/BootupListener( 1452): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider( 1014): name = internet_call_settings_visibility
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
D/PhoneUtilsCommon( 1452): isSupportVoLTE is false.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 2263): TimaSignature is unavailable
D/ActivityThread( 2263): Added TimaKeyStore provider
E/Zygote  ( 2284): MountEmulatedStorage()
E/Zygote  ( 2284): v2
I/libpersona( 2284): KNOX_SDCARD checking this for 10046
I/libpersona( 2284): KNOX_SDCARD not a persona
I/SELinux ( 2284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2284 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 2284): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/StatusChecker( 2254): onReceive : android.intent.action.SIM_STATE_CHANGED
D/TimaKeyStoreProvider( 2284): TimaSignature is unavailable
D/ActivityThread( 2284): Added TimaKeyStore provider
I/StatusChecker( 2254): onReceive : net.mt.init : 
D/StatusChecker( 2254): onReceive : preference initializing
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2284): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2284): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2284): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2284): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2284): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 2301): MountEmulatedStorage()
I/libpersona( 2301): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2301): v2
I/libpersona( 2301): KNOX_SDCARD not a persona
I/SELinux ( 2301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2301): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2301): TimaSignature is unavailable
E/Zygote  ( 2314): MountEmulatedStorage()
E/Zygote  ( 2314): v2
I/libpersona( 2314): KNOX_SDCARD checking this for 1000
I/libpersona( 2314): KNOX_SDCARD not a persona
I/SELinux ( 2314): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2314): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2314 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2314): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 2301): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 2314): TimaSignature is unavailable
D/ActivityThread( 2314): Added TimaKeyStore provider
I/Omc:Receiver( 2301): onReceive : android.intent.action.SIM_STATE_CHANGED
I/Omc:OmcData( 2301): omc.xml not exist
I/Omc:Receiver( 2301): OM Customize disabled
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2332): MountEmulatedStorage()
E/Zygote  ( 2332): v2
I/libpersona( 2332): KNOX_SDCARD checking this for 10131
I/libpersona( 2332): KNOX_SDCARD not a persona
I/SELinux ( 2332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2332 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
E/SELinux ( 2332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2332): TimaSignature is unavailable
D/ActivityThread( 2332): Added TimaKeyStore provider
I/art     (  317): Explicit concurrent mark sweep GC freed 8755(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 23.564ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 591us total 16.782ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 16.321ms
E/Zygote  ( 2347): MountEmulatedStorage()
E/Zygote  ( 2347): v2
I/libpersona( 2347): KNOX_SDCARD checking this for 1000
I/libpersona( 2347): KNOX_SDCARD not a persona
I/SELinux ( 2347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2347 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2347): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 2284): [start]    onCreate() consume time = 0.0
D/TimaKeyStoreProvider( 2347): TimaSignature is unavailable
D/ActivityThread( 2347): Added TimaKeyStore provider
W/ResourcesManager( 2332): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2332): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2332): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2332): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/SBrowserFeatureFlag( 2332): initialized in static block : loadCscFeatureValue() succeed! 
W/art     ( 2284): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 101.273ms
D/ManifestProvider( 2332): onCreate()
E/OperatorBookmarksSIMReceiver( 2332): onReceive runs..android.intent.action.SIM_STATE_CHANGED
D/Mms/ArtClassLoader( 2284): init before art
D/Mms/TelephonyPermission( 2284): start operation mode monitor
W/ResourcesManager( 2284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2284): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2284): isDefault true
E/USB_UICC(  308): Timeout! No signal received. Retry num = 21
D/Mms/MmsApp( 2284): onCreate() com.android.mms
,D/Mms/MmsApp( 2284): [start]    initCountryIso consume time = 375.032916
D/CountryDetector( 1014): The first listener is added
D/Mms/MmsApp( 2284): [end]    initCountryIso consume time = 101.640729
D/Mms/MmsConfig( 2284): [start]    MmsConfig.init() consume time = 2.088438
D/Mms/MmsConfig( 2284): before partial update
D/Mms/MmsConfig( 2284): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2284): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2284): isAuth is false
D/Mms/MmsConfig( 2284): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/TP/MmsSmsProvider( 1452): query,matched:2117, calling pid = 2284
D/TP/MmsSmsProvider( 1452): match 2117:Elapsed time : 7.358 ms
D/EasySignUpManager_1.0.1( 2284): isAuth is false
D/EasySignUpManager_1.0.1( 2284): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2284): mps_code.dat does not exist
E/CscParser( 2284): customer_path =/system/csc/customer.xml
E/CscParser( 2284): fileName + /system/csc/customer.xml
E/CscParser( 2284): mps_code.dat does not exist
E/CscParser( 2284): customer_path =/system/csc/customer.xml
E/CscParser( 2284): fileName + /system/csc/customer.xml
D/CscParser( 2284): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2284):  enable multiwindow = true
E/Mms/MessageUtils( 2284): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2284): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2284): [end]    init() consume time = 103.726718
D/Mms/Contact( 2284): [start]    init() consume time = 5.431198
D/TP/MmsSmsProvider( 1452): query,matched:13, calling pid = 2284
D/Mms/Contact( 2284): [end]    init consume time = 13.074792
D/TP/MmsSmsProvider( 1452): match 13:Elapsed time : 2.228 ms
D/Mms/DraftCache( 2284): [start]    rebuildCache consume time = 20.543437
D/TP/MmsSmsProvider( 1452): query,matched:12, calling pid = 2284
D/TP/MmsSmsProvider( 1452): match 12:Elapsed time : 1.618 ms
D/Mms/DraftCache( 2284): [end]    rebuildCache consume time = 13.109115
D/Mms/MethodReflector( 2284): getSubId is called
D/Mms/TelephonyUtils( 2284): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2284): getTelephonyProperty is called
D/Mms/DownloadManager( 2284): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2284): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2284): auto download without roaming -> true
D/Mms/DownloadManager( 2284): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2284): getSubId is called
D/Mms/MethodReflector( 2284): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2284): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2284): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2284): getTelephonyProperty is called
D/Mms/DownloadManager( 2284): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2284): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2284): auto download without roaming -> true
D/Mms/DownloadManager( 2284): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2284): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2284): mAutoDownload ------> true
D/Mms/ArtClassLoader( 2284): init [DONE] art
D/AndroidRuntime( 2366): 
D/AndroidRuntime( 2366): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2366): CheckJNI is OFF
D/AndroidRuntime( 2366): readGMSProperty: start
D/AndroidRuntime( 2366): readGMSProperty: already setted!!
D/AndroidRuntime( 2366): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2366): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2366): readGMSProperty: end
D/AndroidRuntime( 2366): addProductProperty: start
D/ComposerPerformance( 2284): 1457427804831 ms / [DONE] Composer constructor
E/CII     ( 2284): CommonIMSInterface: VoLTE CSC feature disabled.
D/Mms/Conversation( 2284): [start]    init() consume time = 75.859688
I/Mms/ReservationManager( 2284): ReservationManager()
I/Mms/ReservationManager( 2284): resetAfterConnected()
D/TP/MmsSmsDatabaseHelper( 1452): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1452): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1452): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1452): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1452): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1452): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1452): query,matched:7, calling pid = 2284
D/TP/MmsSmsProvider( 1452): match 7:Elapsed time : 3.196 ms
I/Mms/ReservationManager( 2284): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1452): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1452): updateThread(), thread_id = 9223372036854775807
D/Mms/MmsApp( 2284): [end]    onCreate() consume time = 18.803437
D/Mms/SmsReceiver( 2284): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsDatabaseHelper( 1452): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
D/TP/MmsSmsProvider( 1452): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/Conversation( 2284): [end]    init consume time = 14.436562
D/Mms/DownloadManager( 2284): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2284): roaming ------> false, mSimSlot = 0
I/splitIntent( 1014): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/Mms/MethodReflector( 2284): getSubId is called
D/Mms/TelephonyUtils( 2284): getLongSubId from simSlot 0, return Value = -1
D/BootupListener( 1452): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1014): name = internet_call_settings_visibility
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/PhoneUtilsCommon( 1452): isSupportVoLTE is false.
D/Mms/MethodReflector( 2284): getTelephonyProperty is called
D/Mms/DownloadManager( 2284): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2284): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2284): auto download without roaming -> true
D/Mms/DownloadManager( 2284): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MessagingNotification( 2284): [start]    init() consume time = 9.491355
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/Mms/DownloadManager( 2284): mAutoDownload ------> true
D/StatusChecker( 2254): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2254): onReceive : net.mt.init : DONE
D/Mms/MessagingNotification( 2284): [end]    init consume time = 6.530677
D/StatusChecker( 2254): Service state changed : 3 mSub-1
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/SpamFilter( 2284): [start]    SpamFilter fill() begin consume time = 13.437812
D/TP/MmsSmsProvider( 1452): query,matched:400, calling pid = 2284
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1452): query,matched:0, calling pid = 2284
V/TP/MmsSmsProvider( 1452): getSimpleConversations entered.
D/Mms/Synchronizer( 2284): [start]    doSync consume time = 6.856459
D/TP/MmsSmsProvider( 1452): match 0:Elapsed time : 1.638 ms
D/Mms/SpamFilter( 2284): [end]    SpamFilter fill() finished consume time = 1.859166
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1452): update, matched:300, calling pid = 2284
V/TP/MmsSmsProvider( 1452): syncDBData start
V/TP/MmsSmsProvider( 1452): syncDBData sms end
V/TP/MmsSmsProvider( 1452): syncDBData mms end
V/TP/MmsSmsProvider( 1452): syncDBData end
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/Synchronizer( 2284): [end]    doSync consume time = 15.451667
D/Mms/SmsReceiverService( 2284): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/Mms/TelephonyPermission( 2284): isDefault true
D/Mms/SmsReceiverService( 2284): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2284): handleSIMStatus()
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/Mms/SmsReceiverService( 2284): handleSIMStatus(): SIM_STATUS = ABSENT
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/MessagingNotification( 2284): checkBadgeCount unreadCount=0 badgeCount=0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/AffinityControl( 2366): AffinityControl: registerfunction enter
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/SmsProvider( 1452): query,matched:26, calling pid = 2284
D/TP/SmsProvider( 1452): match 26:Elapsed time : 1.604 ms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1452): query,matched:6, calling pid = 2284
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1452): match 6:Elapsed time : 2.571 ms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/AndroidRuntime( 2366): Calling main entry com.android.commands.am.Am
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1014): mDVFSHelper.acquire()
D/FocusedStackFrame( 1014): Set to : 0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1472): onPause
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/Launcher( 1472): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1472
D/AndroidRuntime( 2366): Shutting down VM
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2388): MountEmulatedStorage()
E/Zygote  ( 2388): v2
I/libpersona( 2388): KNOX_SDCARD checking this for 10020
I/libpersona( 2388): KNOX_SDCARD not a persona
I/SELinux ( 2388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2388): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1014): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2388 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2388): TimaSignature is unavailable
D/ActivityThread( 2388): Added TimaKeyStore provider
E/Zygote  ( 2403): MountEmulatedStorage()
E/Zygote  ( 2403): v2
I/libpersona( 2403): KNOX_SDCARD checking this for 10025
I/libpersona( 2403): KNOX_SDCARD not a persona
I/SELinux ( 2403): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2403): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2403 uid=10025 gids={50025, 9997} abi=armeabi-v7a
E/SELinux ( 2403): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2415): MountEmulatedStorage()
E/Zygote  ( 2415): v2
I/libpersona( 2415): KNOX_SDCARD checking this for 10174
I/libpersona( 2415): KNOX_SDCARD not a persona
I/SELinux ( 2415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2415 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2415): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2403): TimaSignature is unavailable
D/ActivityThread( 2403): Added TimaKeyStore provider
W/ResourcesManager( 2388): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2388): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2388): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
V/ActivityThread( 1472): updateVisibility : ActivityRecord{22e908d6 token=android.os.BinderProxy@180444b6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 2415): TimaSignature is unavailable
D/ActivityThread( 2415): Added TimaKeyStore provider
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1472): onStop
W/ResourcesManager( 2403): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/ActivityThread( 1472): updateVisibility : ActivityRecord{22e908d6 token=android.os.BinderProxy@180444b6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/Launcher( 1472): onTrimMemory. Level: 20
W/art     ( 2366): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/WebViewFactory( 2415): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/LibraryLoader( 2415): Time to load native libraries: 2 ms (timestamps 8514-8516)
I/LibraryLoader( 2415): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2415): Binding Chromium to main looper Looper (main, tid 1) {2ca2878f}
,I/LibraryLoader( 2415): Expected native library version number "",actual native library version number ""
,I/chromium( 2415): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,E/SMD     (  292): DCD OFF
,I/BrowserStartupController( 2415): Initializing chromium process, singleProcess=true
,W/art     ( 2415): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2415): ApplicationContext is null in ApplicationStatus
,I/OMACP   ( 2403): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,W/chromium( 2415): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,D/Mms/Omacp( 2284): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/chromium( 2415): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2415): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2415): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 2415): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2415): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2415): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2415): Local Branch: 
I/Adreno-EGL( 2415): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2415): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2415):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
E/USB_UICC(  308): Timeout! No signal received. Retry num = 22
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 2403): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/EasySignUpManager_1.15.0305( 2388): serviceId : 0, features : -1
,I/splitIntent( 1014): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1014): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,D/BluetoothAdapter( 2415): 745806856: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/SecContentProvider2( 1014): uri = 18 selection = isCopyContactToSimAllowed
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): isCopyContactToSimAllowed = true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2452): MountEmulatedStorage(),
I/libpersona( 2452): KNOX_SDCARD checking this for 10044
E/Zygote  ( 2452): v2
I/libpersona( 2452): KNOX_SDCARD not a persona
I/SELinux ( 2452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2452 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2452): TimaSignature is unavailable
,D/ActivityThread( 2452): Added TimaKeyStore provider
,E/Zygote  ( 2467): MountEmulatedStorage(),
E/Zygote  ( 2467): v2
I/libpersona( 2467): KNOX_SDCARD checking this for 10088
I/libpersona( 2467): KNOX_SDCARD not a persona
,I/SELinux ( 2467): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2467 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,I/SELinux ( 2467): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 2467): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2467): TimaSignature is unavailable
D/ActivityThread( 2467): Added TimaKeyStore provider
E/Zygote  ( 2480): MountEmulatedStorage()
E/Zygote  ( 2480): v2
I/libpersona( 2480): KNOX_SDCARD checking this for 10142
I/libpersona( 2480): KNOX_SDCARD not a persona
I/SELinux ( 2480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2480 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 2480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ResourcesManager( 2452): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1472, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ResourcesManager( 2452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 2452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 2452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2480): TimaSignature is unavailable
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,D/ActivityThread( 2480): Added TimaKeyStore provider
,W/ResourcesManager( 2467): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2499): MountEmulatedStorage()
,E/Zygote  ( 2499): v2
I/libpersona( 2499): KNOX_SDCARD checking this for 10054
I/libpersona( 2499): KNOX_SDCARD not a persona
,I/SELinux ( 2499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2499 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
I/SELinux ( 2499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2499): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=8 Removed Mauncher (-2/8)
,E/Zygote  ( 2512): MountEmulatedStorage()
E/Zygote  ( 2512): v2
I/libpersona( 2512): KNOX_SDCARD checking this for 10139
I/libpersona( 2512): KNOX_SDCARD not a persona
,I/SELinux ( 2512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2512 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,E/SELinux ( 2512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2499): TimaSignature is unavailable
,D/ActivityThread( 2499): Added TimaKeyStore provider
,W/chromium( 2415): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/TimaKeyStoreProvider( 2512): TimaSignature is unavailable
,D/ActivityThread( 2512): Added TimaKeyStore provider
,W/ResourcesManager( 2499): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 2512): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2512): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2512): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2512): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2512): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/TaskCloserActivity( 2480): TaskCloserActivity enter()
,V/TaskCloserActivity( 2480): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/Recents_RecreateReceiver( 2499): onReceive by home
,W/art     ( 2415): Attempt to remove local handle scope entry from IRT, ignoring
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,W/AwContents( 2415): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2415): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2415): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2415): CordovaWebView is running on device made by: samsung
,W/art     ( 2415): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2415): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2415): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 2415): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2415): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/art     ( 2388): Verification of void com.android.contacts.common.list.l.P() took 101.686ms
,D/InputDispatcher( 1014): Focus entered window: 2415
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 2415): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2415): Initialized EGL, version 1.4
D/OpenGLRenderer( 2415): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2415): Enabling debug mode 0
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1176): Icon Only
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1176): There is/are notification(s) 
,I/ActivityManager( 1014): Displayed Component not be shown by security: +945ms
,W/ActivityManager( 1014): mDVFSHelper.release()
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{1b169d9e u0 com.example.hello/.MainActivity t10} time:29273
,I/SamsungIME( 1790): getCurrentCandidateView
,I/Timeline( 2415): Timeline: Activity_idle id: android.os.BinderProxy@2c2f5faa time:29277
,W/BindingManager( 2415): Cannot call determinedVisibility() - never saw a connection for the pid: 2415
,D/SamsungIME( 1790): Dismiss ExpandCandiate
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 33456(1829KB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 24MB/37MB, paused 2.113ms total 141.950ms
,I/chromium( 2415): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,D/NearbySource( 2452): Nearby Source Create!
,D/NearbyContext( 2452): Nearby Context Create!
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2452): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2452): Samsung link source created
,D/AbsListView( 2388): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,I/SamsungIME( 1790): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 2415): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2415): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/ContactProvider( 2452): getAllContactInfoList Start
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 23
,I/SamsungIME( 1790): getDebugLevel  : 0x4f4c
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SamsungIME( 1790): KeybaordView init() : load resources
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2452): Receive : home resume
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 2284): ui event
,I/splitIntent( 1014): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SamsungIME( 1790): getCurrentKeyboard
I/SamsungIME( 1790): getTextKeyboard
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SQLiteLog( 1226): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SamsungIME( 1790): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1719): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/ContactProvider( 2452): getAllContactInfoList End
,I/syncContacts( 2452): thread: 253, sync time = 179
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/jxcore_app_log( 2415): JniHelper::setJavaVM(0xb8ae2450), pthread_self() = -1191170976
,D/accuweather( 1719): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1719): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1719): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1719): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
D/accuweather( 1719): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1719): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1719): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/art     ( 1790): Suspending all threads took: 8.280ms
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1719): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1719): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 1719): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1719): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1719): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1719): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 10 03
,E/accuweather( 1719): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1719): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,W/jxcore-log( 2415): Initializing JXcore engine
W/jxcore-log( 2415): JXcore engine is ready
,D/accuweather( 1719): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1719): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1719): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1719): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1719): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1719): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1719): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1719): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1719): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,E/audit   ( 1944): type=1400 msg=audit(1457427806.699:203): avc:  denied  { ioctl } for  pid=2551 comm="Thread-265" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1944):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1944): type=1300 msg=audit(1457427806.699:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=5 a3=9de348f8 items=0 ppid=317 ppcomm=main pid=2551 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-265" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1944): type=1320 msg=audit(1457427806.699:203): 
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/jxcore-log( 2415): Starting JXcore engine
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1309): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1309): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/jxcore-log( 2415): Platform android
W/jxcore-log( 2415): 
,W/jxcore-log( 2415): Process ARCH arm
W/jxcore-log( 2415): 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/Mms/MmsApp( 2284):  start initViewCache mms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/ComposeMessageFragment( 2284): [start]    fillCache consume time = 1936.740416
D/Mms/ComposeMessageFragment( 2284): fillCache, easy = false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/jxcore-log( 2415): JXcore Cordova bridge is ready!
I/jxcore-log( 2415): 
,W/jxcore-log( 2415): JXcore engine is started
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/jxcore  ( 2415): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2415): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneWindow( 2415): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 2415): *FMB* installDecor flags : 8388610
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SIP     ( 1452): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1452): fail readDirectory() errno=2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/InputDispatcher( 1014): Focus left window: 2415
,D/InputDispatcher( 1014): Focus entered window: 2415
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PhoneWindow( 2415): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2415): *FMB* isFloatingMenuEnabled return false
,V/UserPresentBroadcastReceiver( 1802): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=4, NainActivit
,D/AbsListView( 2284): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 2284): [end]    fillCache consume time = 152.613698
,D/SRIB_DCS( 2415): log_dcs ThreadedRenderer::initialize entered! 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1790): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/Mms/BubbleViewCache( 2284): fillCache bubble = 1
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1309): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1309): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/USB_UICC(  308): Timeout! No signal received. Retry num = 24
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1309): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/AdaptiveEventManager( 1176): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,D/AdaptiveEventManager( 1176): currentCityId is null
D/AdaptiveEventManager( 1176): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1176): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1176): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1176): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1176): mWeatherInfo is not reliable
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,E/daemonapp( 1309): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2566): MountEmulatedStorage(),
I/libpersona( 2566): KNOX_SDCARD checking this for 10135
E/Zygote  ( 2566): v2
I/libpersona( 2566): KNOX_SDCARD not a persona
,I/SELinux ( 2566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2566): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2566 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
D/daemonapp( 1309): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
D/daemonapp( 1309): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1457427807463
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1457449407459
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1309): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1457449380000
,D/daemonapp( 1309): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457449380000
,D/TimaKeyStoreProvider( 2566): TimaSignature is unavailable
D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1457449380000
,D/ActivityThread( 2566): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 2566): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 2566): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1802): callingUid 10012, callindPid: 1802,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsWearableNodeHelper( 1802): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1802): [202] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationInitializer( 2023): Restart initialization of location
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Scheduler( 1802): Use legacy PeriodicScheduler
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 1802): Found 10012
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1452): query,matched:0, calling pid = 2023
,D/TP/SmsProvider( 1452): match 0:Elapsed time : 1.725 ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1452): Query uri=content://mms, match=0, calling pid = 2023
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1802): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1802): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1452): query,matched:0, calling pid = 2023
,D/TP/SmsProvider( 1452): match 0:Elapsed time : 1.793 ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1452): Query uri=content://mms, match=0, calling pid = 2023
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2023): getNumBytesRead when not calculated.
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2611): MountEmulatedStorage()
,E/Zygote  ( 2611): v2
I/libpersona( 2611): KNOX_SDCARD checking this for 1000,
,I/SELinux ( 2611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2611): KNOX_SDCARD not a persona
I/SELinux ( 2611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2611 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GCoreFlp( 1802): No location to return for getLastLocation(),
W/FusedLocationProvider( 1802): location=null
,I/art     (  317): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 26.951ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.679ms
,D/TimaKeyStoreProvider( 2611): TimaSignature is unavailable
,D/ActivityThread( 2611): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.538ms,
,D/SecurityLogAgent( 2611):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2611):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2611):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2611): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2611): FileZippingService : onHandleIntent 
,D/SecurityLogAgent( 2611): FileZippingService : file path =  /data/misc/audit/audit.old
,E/Zygote  ( 2629): MountEmulatedStorage()
,E/Zygote  ( 2629): v2
I/libpersona( 2629): KNOX_SDCARD checking this for 1000
I/libpersona( 2629): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2629 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2629): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/SecurityLogAgent( 2611): FileZippingService : onPremise disabled. Zipping..  ,
,I/SELinux ( 2629): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2629): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/SecurityLogAgent( 2611): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2611): DenialLogFileZipCreator : Not empty 
D/SecurityLogAgent( 2611): DenialLogFileZipCreator : Files exceeded the max limit 
,D/TimaKeyStoreProvider( 2629): TimaSignature is unavailable
,D/ActivityThread( 2629): Added TimaKeyStore provider
,D/SecurityLogAgent( 2611): DenialLogFileZipCreator File existence : true audit.old file size 1347
,D/SecurityLogAgent( 2611): DenialLogFileZipCreator : denied strings found . Starts zipping . 
,D/SecurityLogAgent( 2611): ProcessFileZipCreator : File name = denialLog
,D/SecurityLogAgent( 2611): ProcessFileZipCreator : Created temp file 
,D/SecurityLogAgent( 2611): ProcessFileZipCreator br.readline() has read  13 lines. 
,D/SecurityLogAgent( 2611): ProcessFileZipCreator denialxxx.txt file file existence : true size after copying : 0
,D/SecurityLogAgent( 2611): ProcessFileZipCreator : Source = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog-1481041258.txt
D/SecurityLogAgent( 2611): ProcessFileZipCreator : Destination = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog-1481041258.txt.zip
,D/SecurityLogAgent( 2611): ProcessFileZipCreator : File compressed.
D/SecurityLogAgent( 2611): ProcessFileZipCreatordenialLog-1481041258.txt has been deleted after compression. 
,D/SecurityLogAgent( 2611): FileCipher : getKey Called 
,I/SecureStorage( 2611): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,W/ContextImpl( 2629): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2611): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  404): [INFO]: SPID(0x00000000)Credentials: uid 1000, gid 1000, pid 2611
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2611): [INFO]: SPID(0x00000000)SS Daemon is running
D/SecurityLogAgent( 2611): FileCipher : Secure Storage Supported 
I/SecureStorage( 2611): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Credentials: uid 1000, gid 1000, pid 2611
I/SecureStorage(  404): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,E/Zygote  ( 2648): MountEmulatedStorage()
,E/Zygote  ( 2648): v2
I/libpersona( 2648): KNOX_SDCARD checking this for 1000
I/libpersona( 2648): KNOX_SDCARD not a persona
,I/SELinux ( 2648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2648 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2648): TimaSignature is unavailable,
,D/ActivityThread( 2648): Added TimaKeyStore provider
,W/ResourcesManager( 2648): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2648): [FactoryTestBroadcastReceiver$onReceive](2648) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2648): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2648): [XMLDataStorage$parseXML](2648) is Live Demo : false
,D/FactoryTestApp( 2648): [XMLDataStorage$parseXML](2648) modelXML=sm-a500fu.dat
D/FactoryTestApp( 2648): [XMLDataStorage$parseXML](2648) deviceXML=a5ulte.dat
D/FactoryTestApp( 2648): [XMLDataStorage$parseXML](2648) nameXML=a5ultexx.dat
D/FactoryTestApp( 2648): [XMLDataStorage$parseAsset](2648) parseAsset Is Started
,I/FactoryTestApp( 2648): [XMLDataStorage$parseAsset](2648) Convert dat file: sm-a500fu.dat
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 2190): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTestApp( 2648): [XMLDataStorage$parseAsset](2648) Decode base file: factory.dat
,I/GAv4-SVC( 2023): Google Analytics 8.4.89 is starting up.
,E/SMD     (  292): DCD OFF
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FACTORY_TEST_APP
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FAILHIST_VERSION
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=MODEL_NAME
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=MODEL_NUMBER
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=CHIPSET_NAME
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=DEVICE_TYPE
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=BATT_TYPE
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PANEL_TYPE
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FRONT_CAMERA_TYPE
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 25
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SPEAKER_COUNT
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=MIC_COUNT
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_LTE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_FRONT_CAMERA
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_RCV
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FACTORY_TEST_APO
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_EPEN
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_SENSORHUB
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=NEED_CAMDRIVER_OPEN
D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HW_VER_EFS
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FONT_SIZE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=RAM_SIZE_IF
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=MULTI_TSK_THD
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_POWER
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_HOME
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_BACK
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SENSOR_TEST_ACC_BIT,
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 16787(935KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 1.897ms total 133.894ms
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=AT_GPSSTEST
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PA0_TEMP_ADC
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HALL_IC_TEST
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=READ_TARGET_GEOMAGNETIC
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=BATTERY_VOLT_AVER,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=BATTERY_VF_OCV,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=SEC_EXT_THERMISTER_TEMP,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PA0_THERMISTER_ADC,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_COMMAND_CMD,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_COMMAND_STATUS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=TSP_COMMAND_RESULT,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=PATH_HALLIC_STATE,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=KEY_PRESSED_POWER,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=APCHIP_TEMP_ADC,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HUMITEMP_THERMISTER_PAM,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HUMITEMP_THERMISTER_BATT,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HUMITEMP_THERMISTER_BATT_CELCIUS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HUMITEMP_THERMISTER_S_HUB_BATT,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=LPA_MODE_SET,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=GEOMAGNETIC_SENSOR_ADC,
,D/FactoryTestApp( 2648): [XMLDataStorage$redefinitionById](2648) id=GEOMAGNETIC_SENSOR_POWER,
,D/FactoryTestApp( 2648): [XMLDataStorage$parseAsset](2648) SemiFunctionMenu
,D/FactoryTestApp( 2648): [XMLDataStorage$parseAsset](2648) parseAsset Is Completed
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2648): [ModuleCommon$ModuleCommon](2648) Create ModuleCommon
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2648): [Support$Kernel.read](2648) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2648): [ModuleCommon$readFactoryMode](2648) mode: ON
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2648): [FactoryTestBroadcastReceiver$onReceive](2648) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2648): [Support$Values.getBoolean](2648) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 2648): [Support$Properties.get](2648) property=ro.factory.factory_binary
D/FactoryTestApp( 2648): [FactoryTestBroadcastReceiver$onReceive](2648) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2648): [ModuleCommon$getFtClientEnableState](2648) result : false
,I/FactoryTestApp( 2648): [ModuleCommon$connectedJIG](2648) ...
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
,I/FactoryTestApp( 2648): [ModuleCommon$connectedJIG](2648) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2648): [Support$Kernel.read](2648) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 2648): [ModuleCommon$connectedJIG](2648) value = 1f, JIG_ON = 1C
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2648): [ModuleCommon$isConnectionModeNone](2648) mConnectionMode = gsm
I/FactoryTestApp( 2648): [ModuleCommon$isRunningFtClient](2648) RUNNING_FTCLIENT : false
,I/FactoryTestApp( 2648): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2648) start DummyFtClient service for APO
,W/ContextImpl( 2648): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
D/FactoryTest( 2648): User mode
,I/FactoryTestApp( 2648): [ModuleCommon$disableFtClient](2648) ...
,D/FactoryTestApp( 2648): [DummyFtClient$onCreate](2648) Create DummyFtClient service
,I/FactoryTestApp( 2648): [XMLDataStorage$parsingXML](2648) FtClient => data parsing was completed.
,D/FactoryTestApp( 2648): [DummyFtClient$onReceive](2648) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2648): [ModuleCommon$isConnectionModeNone](2648) mConnectionMode = gsm
,D/FactoryTestApp( 2648): [Support$Values.getBoolean](2648) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2648): [DummyFtClient$onStartCommand](2648) ...
,I/WifiService( 1014): android.intent.action.BOOT_COMPLETED,
,D/UsbDeviceManager( 1014): boot completed
,D/UsbDeviceManager( 1014): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1014): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1014): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1014): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,I/KeyguardEffectViewUtil( 1176): set resource id
,D/SettingsProvider( 1014): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BOOT_COMPLETED
,D/KeyguardUpdateMonitor( 1176): handleBootCompleted()
,D/KeyguardUpdateMonitor( 1176): handleBootCompleted()
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1014): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1014): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1014): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1014): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
,D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SecureStorage(  404): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0,
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SamsungIME( 1790): showDlgMsgBox : false true true
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,I/RecoverySystem( 1014): !@RecoverySystem handleAftermath
D/NfcService( 1439): call the applyRouting
I/RecoverySystem( 1014): No recovery log file
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2677): MountEmulatedStorage()
I/libpersona( 2677): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2677): v2
I/libpersona( 2677): KNOX_SDCARD not a persona
,I/SELinux ( 2677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/SecureStorage( 2611): [INFO]: SPID(0x00000001)Processing data has been completed
I/SecureStorage( 2611): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 2611): FileCipher : Got the key bytes 
D/SecurityLogAgent( 2611): FileCipher : Saving Key to SecureStorage.  
I/SecureStorage( 2611): [INFO]: SPID(0x00000001)Processing data
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 2611
I/SecureStorage(  404): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000104
,I/ActivityManager( 1014): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2677 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Reset_Reason( 1014): resetString = NPON
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,V/OtaStartupReceiver( 1452): onOtaspChanged: mOtaspMode=1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,D/TimaKeyStoreProvider( 2677): TimaSignature is unavailable
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 2677): Added TimaKeyStore provider
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2695): MountEmulatedStorage(),
E/Zygote  ( 2695): v2,
I/libpersona( 2695): KNOX_SDCARD checking this for 1001
,I/libpersona( 2695): KNOX_SDCARD not a persona
,I/SELinux ( 2695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/BootReceiver( 1014): Copying audit failures to DropBox
,I/SELinux ( 2695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/BootReceiver( 1014): Checking for fsck errors
,E/SELinux ( 2695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2695 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/TimaKeyStoreProvider( 2695): TimaSignature is unavailable
,D/ActivityThread( 2695): Added TimaKeyStore provider
,W/art     ( 2263): Suspending all threads took: 5.559ms
,W/ResourcesManager( 2695): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/File    ( 2677): fail readDirectory() errno=2
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FactoryTestApp( 2648): [ProtectedFactoryTestBroadcastReceiver$onReceive](2648) onReceive action=com.samsung.intent.action.SECPHONE_READY
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/FactoryTestApp( 2648): [ProtectedFactoryTestBroadcastReceiver$onReceive](2648) com.samsung.intent.action.SECPHONE_READY
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
D/FactoryTest( 2648): User mode
,D/Mms/NotificationReceiver( 2284): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
D/Mms/NotificationReceiver( 2284): handleBootCompleted()
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/RcsOwnCapsManager( 2284): queue Uri = content://im/queue-messages?box=pending
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TP/ImProvider( 1452): im query match24
D/TP/ImProvider( 1452): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1452): ftSesstionId must be a long.
D/TP/ImProvider( 1452): getQueuedImMessages
D/TP/ImProvider( 1452): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/NotificationReceiver( 2284):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2284): Call to GET_LAST_MESSAGES_SENT
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 31510, tid: 31510, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1014):     r0 b914bd48  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1014):     r4 0045b0a0  r5 be11f218  r6 b914bd48  r7 be11f228
D/CrashAnrDetector( 1014):     r8 be11ee60  r9 ba64e378  sl ba64e378  fp be11f1dc
D/CrashAnrDetector( 1014):     ip be11f228  sp be11ee58  lr a0b0030c  pc a0affd98  cpsr a00f0010
D/CrashAnrDetector( 1014):     d0  ffffff859ec62bb0  d1  0000000000000000
D/CrashAnrDetector( 1014):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1014):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1014):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1014):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1014):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1014):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1014):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1014):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1014):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1014):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1014):     scr 20000013
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1014):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1014):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1014):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          be11edd8  00000000  
D/CrashAnrDetector( 1014):          be11eddc  00000000  
D/CrashAnrDetector( 1014):          be11ede0  00000000  
D/CrashAnrDetector( 1014):          be11ede4  00000000  
D/CrashAnrDetector( 1014):          be11ede8  00000000  
D/CrashAnrDetector( 1014):          be11edec  00000000  
D/CrashAnrDetector( 1014):          be11edf0  00000000  
D/CrashAnrDetector( 1014):          be11edf4  00000000  
D/CrashAnrDetector( 1014):          be11edf8  00000000  
D/CrashAnrDetector( 1014):          be11edfc  00000000  
D/CrashAnrDetector( 1014):          be11ee00  00000000  
D/CrashAnrDetector( 1014):          be11ee04  00000000  
D/CrashAnrDetector( 1014):          be11ee08  00000000  
D/CrashAnrDetector( 1014):          be11ee0c  00000000  
D/CrashAnrDetector( 1014):          be11ee10  00000000  
D/CrashAnrDetector( 1014):          be11ee14  00000000  
D/CrashAnrDetector( 1014):          be11ee18  00000000  
D/CrashAnrDetector( 1014):          be11ee1c  00000000  
D/CrashAnrDetector( 1014):          be11ee20  00000000  
D/CrashAnrDetector( 1014):          be11ee24  00000000  
D/CrashAnrDetector( 1014):          be11ee28  00000000  
D/CrashAnrDetector( 1014):          be11ee2c  00000000  
D/CrashAnrDetector( 1014):          be11ee30  00000000  
D/CrashAnrDetector( 1014):          be11ee34  00000000  
D/CrashAnrDetector( 1014):          be11ee38  00000000  
D/CrashAnrDetector( 1014):          be11ee3c  00000000  
D/CrashAnrDetector( 1014):          be11ee40  00000000  
D/CrashAnrDetector( 1014):          be11ee44  00000000  
D/CrashAnrDetector( 1014):          be11ee48  00000000  
D/CrashAnrDetector( 1014):          be11ee4c  00000000  
D/CrashAnrDetector( 1014):          be11ee50  00000000  
D/CrashAnrDetector( 1014):          be11ee54  00000000  
D/CrashAnrDetector( 1014):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1014):          be11ee5c  00000000  
D/CrashAnrDetector( 1014):          be11ee60  00000000  
D/CrashAnrDetector( 1014):          be11ee64  00000000  
D/CrashAnrDetector( 1014):          be11ee68  00000000  
D/CrashAnrDetector( 1014):          be11ee6c  00000000  
D/CrashAnrDetector( 1014):          be11ee70  00000000  
D/CrashAnrDetector( 1014):          be11ee74  00000000  
D/CrashAnrDetector( 1014):          be11ee78  00000000  
D/CrashAnrDetector( 1014):          be11ee7c  00000000  
D/CrashAnrDetector( 1014):          be11ee80  00000000  
D/CrashAnrDetector( 1014):          be11ee84  00000000  
D/CrashAnrDetector( 1014):          be11ee88  00000000  
D/CrashAnrDetector( 1014):          be11ee8c  00000000  
D/CrashAnrDetector( 1014):          be11ee90  00000000  
D/CrashAnrDetector( 1014):          be11ee94  00000000  
D/CrashAnrDetector( 1014):          be11ee98  00000000  
D/CrashAnrDetector( 1014):          be11ee9c  00000000  
D/CrashAnrDetector( 1014):          be11eea0  00000000  
D/CrashAnrDetector( 1014):          be11eea4  00000000  
D/CrashAnrDetector( 1014):          be11eea8  00000000  
D/CrashAnrDetector( 1014):          be11eeac  00000000  
D/CrashAnrDetector( 1014):          be11eeb0  00000000  
D/CrashAnrDetector( 1014):          be11eeb4  00000000  
D/CrashAnrDetector( 1014):          be11eeb8  00000000  
D/CrashAnrDetector( 1014):          be11eebc  00000000  
D/CrashAnrDetector( 1014):       
D/CrashAnrDetector( 1014): processName:com.test.thalitest
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 2016, tid: 2016, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1014):     r0 b926a1f0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1014):     r4 0045b0a0  r5 be11f218  r6 b926a1f0  r7 be11f228
D/CrashAnrDetector( 1014):     r8 be11ee60  r9 baf12548  sl baf12548  fp be11f1dc
D/CrashAnrDetector( 1014):     ip be11f228  sp be11ee58  lr a09c330c  pc a09c2d98  cpsr a00f0010
D/CrashAnrDetector( 1014):     d0  ffffff859e8579c0  d1  0000000000000000
D/CrashAnrDetector( 1014):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1014):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1014):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1014):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1014):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1014):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1014):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1014):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1014):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1014):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1014):     scr 20000013
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1014):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1014):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1014):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          be11edd8  00000000  
D/CrashAnrDetector( 1014):          be11eddc  00000000  
D/CrashAnrDetector( 1014):          be11ede0  00000000  
D/CrashAnrDetector( 1014):          be11ede4  00000000  
D/CrashAnrDetector( 1014):          be11ede8  00000000  
D/CrashAnrDetector( 1014):          be11edec  00000000  
D/CrashAnrDetector( 1014):          be11edf0  00000000  
D/CrashAnrDetector( 1014):          be11edf4  00000000  
D/CrashAnrDetector( 1014):          be11edf8  00000000  
D/CrashAnrDetector( 1014):          be11edfc  00000000  
D/CrashAnrDetector( 1014):          be11ee00  00000000  
D/CrashAnrDetector( 1014):          be11ee04  00000000  
D/CrashAnrDetector( 1014):          be11ee08  00000000  
D/CrashAnrDetector( 1014):          be11ee0c  00000000  
D/CrashAnrDetector( 1014):          be11ee10  00000000  
D/CrashAnrDetector( 1014):          be11ee14  00000000  
D/CrashAnrDetector( 1014):          be11ee18  00000000  
D/CrashAnrDetector( 1014):          be11ee1c  00000000  
D/CrashAnrDetector( 1014):          be11ee20  00000000  
D/CrashAnrDetector( 1014):          be11ee24  00000000  
D/CrashAnrDetector( 1014):          be11ee28  00000000  
D/CrashAnrDetector( 1014):          be11ee2c  00000000  
D/CrashAnrDetector( 1014):          be11ee30  00000000  
D/CrashAnrDetector( 1014):          be11ee34  00000000  
D/CrashAnrDetector( 1014):          be11ee38  00000000  
D/CrashAnrDetector( 1014):          be11ee3c  00000000  
D/CrashAnrDetector( 1014):          be11ee40  00000000  
D/CrashAnrDetector( 1014):          be11ee44  00000000  
D/CrashAnrDetector( 1014):          be11ee48  00000000  
D/CrashAnrDetector( 1014):          be11ee4c  00000000  
D/CrashAnrDetector( 1014):          be11ee50  00000000  
D/CrashAnrDetector( 1014):          be11ee54  00000000  
D/CrashAnrDetector( 1014):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1014):          be11ee5c  00000000  
D/CrashAnrDetector( 1014):          be11ee60  00000000  
D/CrashAnrDetector( 1014):          be11ee64  00000000  
D/CrashAnrDetector( 1014):          be11ee68  00000000  
D/CrashAnrDetector( 1014):          be11ee6c  00000000  
D/CrashAnrDetector( 1014):          be11ee70  00000000  
D/CrashAnrDetector( 1014):          be11ee74  00000000  
D/CrashAnrDetector( 1014):          be11ee78  00000000  
D/CrashAnrDetector( 1014):          be11ee7c  00000000  
D/CrashAnrDetector( 1014):          be11ee80  00000000  
D/CrashAnrDetector( 1014):          be11ee84  00000000  
D/CrashAnrDetector( 1014):          be11ee88  00000000  
D/CrashAnrDetector( 1014):          be11ee8c  00000000  
D/CrashAnrDetector( 1014):          be11ee90  00000000  
D/CrashAnrDetector( 1014):          be11ee94  00000000  
D/CrashAnrDetector( 1014):          be11ee98  00000000  
D/CrashAnrDetector( 1014):          be11ee9c  00000000  
D/CrashAnrDetector( 1014):          be11eea0  00000000  
D/CrashAnrDetector( 1014):          be11eea4  00000000  
D/CrashAnrDetector( 1014):          be11eea8  00000000  
D/CrashAnrDetector( 1014):          be11eeac  00000000  
D/CrashAnrDetector( 1014):          be11eeb0  00000000  
D/CrashAnrDetector( 1014):          be11eeb4  00000000  
D/CrashAnrDetector( 1014):          be11eeb8  00000000  
D/CrashAnrDetector( 1014):          be11eebc  00000000  
D/CrashAnrDetector( 1014):         
D/CrashAnrDetector( 1014): processName:com.test.thalitest
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SettingsProvider( 1014): name = db_smartlock_supported
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 8409, tid: 8409, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1014):     r0 b9145f50  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1014):     r4 0045b0a0  r5 be11f218  r6 b9145f50  r7 be11f228
D/CrashAnrDetector( 1014):     r8 be11ee60  r9 bab49fd0  sl bab49fd0  fp be11f1dc
D/CrashAnrDetector( 1014):     ip be11f228  sp be11ee58  lr 9fdfc30c  pc 9fdfbd98  cpsr a00f0010
D/CrashAnrDetector( 1014):     d0  ffffff859df5ebb0  d1  646f6d5f65646f6e
D/CrashAnrDetector( 1014):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1014):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1014):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1014):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1014):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1014):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1014):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1014):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1014):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1014):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1014):     scr 20000012
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1014):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1014):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1014):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          be11edd8  00000000  
D/CrashAnrDetector( 1014):          be11eddc  00000000  
D/CrashAnrDetector( 1014):          be11ede0  00000000  
D/CrashAnrDetector( 1014):          be11ede4  00000000  
D/CrashAnrDetector( 1014):          be11ede8  00000000  
D/CrashAnrDetector( 1014):          be11edec  00000000  
D/CrashAnrDetector( 1014):          be11edf0  00000000  
D/CrashAnrDetector( 1014):          be11edf4  00000000  
D/CrashAnrDetector( 1014):          be11edf8  00000000  
D/CrashAnrDetector( 1014):          be11edfc  00000000  
D/CrashAnrDetector( 1014):     ,     be11ee00  00000000  
D/CrashAnrDetector( 1014):          be11ee04  00000000  
D/CrashAnrDetector( 1014):          be11ee08  00000000  
D/CrashAnrDetector( 1014):          be11ee0c  00000000  
D/CrashAnrDetector( 1014):          be11ee10  00000000  
D/CrashAnrDetector( 1014):          be11ee14  00000000  
D/CrashAnrDetector( 1014):          be11ee18  00000000  
D/CrashAnrDetector( 1014):          be11ee1c  00000000  
D/CrashAnrDetector( 1014):          be11ee20  00000000  
D/CrashAnrDetector( 1014):          be11ee24  00000000  
D/CrashAnrDetector( 1014):          be11ee28  00000000  
D/CrashAnrDetector( 1014):          be11ee2c  00000000  
D/CrashAnrDetector( 1014):          be11ee30  00000000  
D/CrashAnrDetector( 1014):          be11ee34  00000000  
D/CrashAnrDetector( 1014):          be11ee38  00000000  
D/CrashAnrDetector( 1014):          be11ee3c  00000000  
D/CrashAnrDetector( 1014):          be11ee40  00000000  
D/CrashAnrDetector( 1014):          be11ee44  00000000  
D/CrashAnrDetector( 1014):          be11ee48  00000000  
D/CrashAnrDetector( 1014):          be11ee4c  00000000  
D/CrashAnrDetector( 1014):          be11ee50  00000000  
D/CrashAnrDetector( 1014):          be11ee54  00000000  
D/CrashAnrDetector( 1014):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1014):          be11ee5c  00000000  
D/CrashAnrDetector( 1014):          be11ee60  00000000  
D/CrashAnrDetector( 1014):          be11ee64  00000000  
D/CrashAnrDetector( 1014):          be11ee68  00000000  
D/CrashAnrDetector( 1014):          be11ee6c  00000000  
D/CrashAnrDetector( 1014):          be11ee70  00000000  
D/CrashAnrDetector( 1014):          be11ee74  00000000  
D/CrashAnrDetector( 1014):          be11ee78  00000000  
D/CrashAnrDetector( 1014):          be11ee7c  00000000  
D/CrashAnrDetector( 1014):          be11ee80  00000000  
D/CrashAnrDetector( 1014):          be11ee84  00000000  
D/CrashAnrDetector( 1014):          be11ee88  00000000  
D/CrashAnrDetector( 1014):          be11ee8c  00000000  
D/CrashAnrDetector( 1014):          be11ee90  00000000  
D/CrashAnrDetector( 1014):          be11ee94  00000000  
D/CrashAnrDetector( 1014):          be11ee98  00000000  
D/CrashAnrDetector( 1014):          be11ee9c  00000000  
D/CrashAnrDetector( 1014):          be11eea0  00000000  
D/CrashAnrDetector( 1014):          be11eea4  00000000  
D/CrashAnrDetector( 1014):          be11eea8  00000000  
D/CrashAnrDetector( 1014):          be11eeac  00000000  
D/CrashAnrDetector( 1014):          be11eeb0  00000000  
D/CrashAnrDetector( 1014):          be11eeb4  00000000  
D/CrashAnrDetector( 1014):          be11eeb8  00000000  
D/CrashAnrDetector( 1014):          be11eebc  00000000  
D/CrashAnrDetector( 1014):         
D/CrashAnrDetector( 1014): processName:com.test.thalitest
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
I/AccessibilityManagerService( 1014): setmDNIeNegative (false)
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 10813, tid: 10813, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1014):     r0 b92c7dd0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1014):     r4 0045b0a0  r5 be11f218  r6 b92c7dd0  r7 be11f228
D/CrashAnrDetector( 1014):     r8 be11ee60  r9 b9a6af30  sl b9a6af30  fp be11f1dc
D/CrashAnrDetector( 1014):     ip be11f228  sp be11ee58  lr a0d6430c  pc a0d63d98  cpsr a00f0010
D/CrashAnrDetector( 1014):     d0  ffffff859ec579c0  d1  0000000000000000
D/CrashAnrDetector( 1014):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1014):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1014):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1014):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1014):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1014):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1014):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1014):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1014):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1014):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1014):     scr 20000012
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1014):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1014):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1014):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          be11edd8  00000000  
D/CrashAnrDetector( 1014):          be11eddc  00000000  
D/CrashAnrDetector( 1014):          be11ede0  00000000  
D/CrashAnrDetector( 1014):          be11ede4  00000000  
D/CrashAnrDetector( 1014):          be11ede8  00000000  
D/CrashAnrDetector( 1014):          be11edec  00000000  
D/CrashAnrDetector( 1014):          be11edf0  00000000  
D/CrashAnrDetector( 1014):          be11edf4  00000000  
D/CrashAnrDetector( 1014):          be11edf8  00000000  
D/CrashAnrDetector( 1014):          be11edfc  00000000  
D/CrashAnrDetector( 1014):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1014):          be11ee04  00000000  
D/CrashAnrDetector( 1014):          be11ee08  00000000  
D/CrashAnrDetector( 1014):          be11ee0c  00000000  
D/CrashAnrDetector( 1014):          be11ee10  00000000  
D/CrashAnrDetector( 1014):          be11ee14  00000000  
D/CrashAnrDetector( 1014):          be11ee18  00000000  
D/CrashAnrDetector( 1014):          be11ee1c  00000000  
D/CrashAnrDetector( 1014):          be11ee20  00000000  
D/CrashAnrDetector( 1014):          be11ee24  00000000  
D/CrashAnrDetector( 1014):          be11ee28  00000000  
D/CrashAnrDetector( 1014):          be11ee2c  00000000  
D/CrashAnrDetector( 1014):          be11ee30  00000000  
D/CrashAnrDetector( 1014):          be11ee34  00000000  
D/CrashAnrDetector( 1014):          be11ee38  00000000  
D/CrashAnrDetector( 1014):          be11ee3c  00000000  
D/CrashAnrDetector( 1014):          be11ee40  00000000  
D/CrashAnrDetector( 1014):          be11ee44  00000000  
D/CrashAnrDetector( 1014):          be11ee48  00000000  
D/CrashAnrDetector( 1014):          be11ee4c  00000000  
D/CrashAnrDetector( 1014):          be11ee50  00000000  
D/CrashAnrDetector( 1014):          be11ee54  00000000  
D/CrashAnrDetector( 1014):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1014):          be11ee5c  00000000  
D/CrashAnrDetector( 1014):          be11ee60  00000000  
D/CrashAnrDetector( 1014):          be11ee64  00000000  
D/CrashAnrDetector( 1014):          be11ee68  00000000  
D/CrashAnrDetector( 1014):          be11ee6c  00000000  
D/CrashAnrDetector( 1014):          be11ee70  00000000  
D/CrashAnrDetector( 1014):          be11ee74  00000000  
D/CrashAnrDetector( 1014):          be11ee78  00000000  
D/CrashAnrDetector( 1014):          be11ee7c  00000000  
D/CrashAnrDetector( 1014):          be11ee80  00000000  
D/CrashAnrDetector( 1014):          be11ee84  00000000  
D/CrashAnrDetector( 1014):          be11ee88  00000000  
D/CrashAnrDetector( 1014):          be11ee8c  00000000  
D/CrashAnrDetector( 1014):          be11ee90  00000000  
D/CrashAnrDetector( 1014):          be11ee94  00000000  
D/CrashAnrDetector( 1014):          be11ee98  00000000  
D/CrashAnrDetector( 1014):          be11ee9c  00000000  
D/CrashAnrDetector( 1014):          be11eea0  00000000  
D/CrashAnrDetector( 1014):          be11eea4  00000000  
D/CrashAnrDetector( 1014):          be11eea8  00000000  
D/CrashAnrDetector( 1014):          be11eeac  00000000  
D/CrashAnrDetector( 1014):          be11eeb0  00000000  
D/CrashAnrDetector( 1014):          be11eeb4  00000000  
D/CrashAnrDetector( 1014):          be11eeb8  00000000  
D/CrashAnrDetector( 1014):          be11eebc  00000000  
D/CrashAnrDetector( 1014):       
D/CrashAnrDetector( 1014): processName:com.test.thalitest
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 6058, tid: 6772, name: Thread-1061  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9c909ff0
D/CrashAnrDetector( 1014):     r0 710804a8  r1 735927c8  r2 12dd4780  r3 13533ec0
D/CrashAnrDetector( 1014):     r4 000000c2  r5 710804a8  r6 735927c8  r7 13533ec0
D/CrashAnrDetector( 1014):     r8 73592770  r9 ba677458  sl 12dd4780  fp 9ca0b8a8
D/CrashAnrDetector( 1014):     ip 9c909ff0  sp 9c90bff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1014):     d0  12dd4780735927c0  d1  007300200065003e
D/CrashAnrDetector( 1014):     d2  c0c0c0c0c0c0c053  d3  0102020202020213
D/CrashAnrDetector( 1014):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1014):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1014):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1014):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1014):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1014):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1014):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1014):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1014):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1014):     scr 20000013
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1014):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          9c90bf70  00000000  
D/CrashAnrDetector( 1014):          9c90bf74  00000000  
D/CrashAnrDetector( 1014):          9c90bf78  00000000  
D/CrashAnrDetector( 1014):          9c90bf7c  00000000  
D/CrashAnrDetector( 1014):          9c90bf80  00000000  
D/CrashAnrDetector( 1014):          9c90bf84  00000000  
D/CrashAnrDetector( 1014):          9c90bf88  00000000  
D/CrashAnrDetector( 1014):          9c90bf8c  00000000  
D/CrashAnrDetector( 1014):          9c90bf90  00000000  
D/CrashAnrDetector( 1014):          9c90bf94  00000000  
D/CrashAnrDetector( 1014):          9c90bf98  00000000  
D/CrashAnrDetector( 1014):          9c90bf9c  00000000  
D/CrashAnrDetector( 1014):          9c90bfa0  00000000  
D/CrashAnrDetector( 1014):          9c90bfa4  00000000  
D/CrashAnrDetector( 1014):          9c90bfa8  00000000  
D/CrashAnrDetector( 1014):          9c90bfac  00000000  
D/CrashAnrDetector( 1014):          9c90bfb0  00000000  
D/CrashAnrDetector( 1014):          9c90bfb4  00000000  
D/CrashAnrDetector( 1014):          9c90bfb8  00000000  
D/CrashAnrDetector( 1014):          9c90bfbc  00000000  
D/CrashAnrDetector( 1014):          9c90bfc0  00000000  
D/CrashAnrDetector( 1014):          9c90bfc4 , 00000000  
D/CrashAnrDetector( 1014):          9c90bfc8  00000000  
D/CrashAnrDetector( 1014):          9c90bfcc  00000000  
D/CrashAnrDetector( 1014):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90bfd4  00000000  
D/CrashAnrDetector( 1014):          9c90bfd8  00000000  
D/CrashAnrDetector( 1014):          9c90bfdc  00000000  
D/CrashAnrDetector( 1014):          9c90bfe0  00000000  
D/CrashAnrDetector( 1014):          9c90bfe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90bfe8  e3a070ad  
D/CrashAnrDetector( 1014):          9c90bfec  ef9000ad  
D/CrashAnrDetector( 1014):     #00  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          ........  ........
D/CrashAnrDetector( 1014):     #01  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90bff4  00000000  
D/CrashAnrDetector( 1014):          9c90bff8  00000000  
D/CrashAnrDetector( 1014):          9c90bffc  00000000  
D/CrashAnrDetector( 1014):          9c90c000  00000000  
D/CrashAnrDetector( 1014):          9c90c004  00000000  
D/CrashAnrDetector( 1014):          9c90c008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c00c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c010  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1014):          9c90c014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c018  12dd4780  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1014):          9c90c01c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1014):          9c90c020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c024  00000000  
D/CrashAnrDetector( 1014):          9c90c028  00000000  
D/CrashAnrDetector( 1014):          9c90c02c  00000000  
D/CrashAnrDetector( 1014):          9c90c030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c034  00000000  
D/CrashAnrDetector( 1014):          9c90c038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c03c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90c040  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1014):          9c90c044  73
D/CrashAnrDetector( 1014): processName:com.test.thalitest
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 6080, tid: 6935, name: Thread-1071  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa37a6ff0
D/CrashAnrDetector( 1014):     r0 710804a8  r1 735927c8  r2 12e00890  r3 133c2fc0
D/CrashAnrDetector( 1014):     r4 000000c2  r5 710804a8  r6 735927c8  r7 133c2fc0
D/CrashAnrDetector( 1014):     r8 73592770  r9 b8284ec8  sl 12e00890  fp a38a88a8
D/CrashAnrDetector( 1014):     ip a37a6ff0  sp a37a8ff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1014):     d0  12e00890735927c0  d1  007300200065002f
D/CrashAnrDetector( 1014):     d2  c0c0c0c0c0c0c03c  d3  0102020202020213
D/CrashAnrDetector( 1014):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1014):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1014):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1014):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1014):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1014):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1014):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1014):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1014):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1014):     scr 20000013
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1014):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          a37a8f70  00000000  
D/CrashAnrDetector( 1014):          a37a8f74  00000000  
D/CrashAnrDetector( 1014):          a37a8f78  00000000  
D/CrashAnrDetector( 1014):          a37a8f7c  00000000  
D/CrashAnrDetector( 1014):          a37a8f80  00000000  
D/CrashAnrDetector( 1014):          a37a8f84  00000000  
D/CrashAnrDetector( 1014):          a37a8f88  00000000  
D/CrashAnrDetector( 1014):          a37a8f8c  00000000  
D/CrashAnrDetector( 1014):          a37a8f90  00000000  
D/CrashAnrDetector( 1014):          a37a8f94  00000000  
D/CrashAnrDetector( 1014):          a37a8f98  00000000  
D/CrashAnrDetector( 1014):          a37a8f9c  00000000  
D/CrashAnrDetector( 1014):          a37a8fa0  00000000  
D/CrashAnrDetector( 1014):          a37a8fa4  00000000  
D/CrashAnrDetector( 1014):          a37a8fa8  00000000  
D/CrashAnrDetector( 1014):          a37a8fac  00000000  
D/CrashAnrDetector( 1014):          a37a8fb0  00000000  
D/CrashAnrDetector( 1014):          a37a8fb4  00000000  
D/CrashAnrDetector( 1014):          a37a8fb8  00000000  
D/CrashAnrDetector( 1014):          a37a8fbc  00000000  
D/CrashAnrDetector( 1014):          a37a8fc0  00000000  
D/CrashAnrDetector( 1014):          a37a8fc4 , 00000000  
D/CrashAnrDetector( 1014):          a37a8fc8  00000000  
D/CrashAnrDetector( 1014):          a37a8fcc  00000000  
D/CrashAnrDetector( 1014):          a37a8fd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a8fd4  00000000  
D/CrashAnrDetector( 1014):          a37a8fd8  00000000  
D/CrashAnrDetector( 1014):          a37a8fdc  00000000  
D/CrashAnrDetector( 1014):          a37a8fe0  00000000  
D/CrashAnrDetector( 1014):          a37a8fe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a8fe8  e3a070ad  
D/CrashAnrDetector( 1014):          a37a8fec  ef9000ad  
D/CrashAnrDetector( 1014):     #00  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          ........  ........
D/CrashAnrDetector( 1014):     #01  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a8ff4  00000000  
D/CrashAnrDetector( 1014):          a37a8ff8  00000000  
D/CrashAnrDetector( 1014):          a37a8ffc  00000000  
D/CrashAnrDetector( 1014):          a37a9000  00000000  
D/CrashAnrDetector( 1014):          a37a9004  00000000  
D/CrashAnrDetector( 1014):          a37a9008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a900c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a9010  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1014):          a37a9014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a9018  12e00890  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1014):          a37a901c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1014):          a37a9020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a9024  00000000  
D/CrashAnrDetector( 1014):          a37a9028  00000000  
D/CrashAnrDetector( 1014):          a37a902c  00000000  
D/CrashAnrDetector( 1014):          a37a9030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a9034  00000000  
D/CrashAnrDetector( 1014):          a37a9038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a903c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          a37a9040  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1014):          a37a9044  73
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): processName:com.test.thalitest
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
,W/Settings( 1282): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1014): name = block_emergency_message
,D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1014): Hardware: MSM8916
D/CrashAnrDetector( 1014): Revision: 2
D/CrashAnrDetector( 1014): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1014): Radio: unknown
D/CrashAnrDetector( 1014): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1014): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1014): Revision: '2'
D/CrashAnrDetector( 1014): ABI: 'arm'
D/CrashAnrDetector( 1014): pid: 2458, tid: 2624, name: Thread-256  >>> com.example.hello <<<
D/CrashAnrDetector( 1014): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1014):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1014):     r4 9dddde78  r5 9dddde38  r6 b8adc500  r7 9dddde38
D/CrashAnrDetector( 1014):     r8 00000000  r9 9dddde74  sl 9dddf3d0  fp 9dddde1c
D/CrashAnrDetector( 1014):     ip 9d93cba0  sp 9dddde00  lr 9d643308  pc b6f2d468  cpsr 600d0030
D/CrashAnrDetector( 1014):     d0  513802003a373ed5  d1  0000b80c030000a1
D/CrashAnrDetector( 1014):     d2  88000000560a109d  d3  0000003502000060
D/CrashAnrDetector( 1014):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1014):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1014):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1014):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1014):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1014):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1014):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1014):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1014):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1014):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1014):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1014):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1014):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1014):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1014):     scr 20000012
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): backtrace:
D/CrashAnrDetector( 1014):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1014):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1014): 
D/CrashAnrDetector( 1014): stack:
D/CrashAnrDetector( 1014):          9ddddd80  00000000  
D/CrashAnrDetector( 1014):          9ddddd84  00000000  
D/CrashAnrDetector( 1014):          9ddddd88  9cd2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1014):          9ddddd8c  e8bc0f76  
D/CrashAnrDetector( 1014):          9ddddd90  9dddddbc  [stack:2624]
D/CrashAnrDetector( 1014):          9ddddd94  9dddde64  [stack:2624]
D/CrashAnrDetector( 1014):          9ddddd98  b8adc500  [heap]
D/CrashAnrDetector( 1014):          9ddddd9c  00000003  
D/CrashAnrDetector( 1014):          9ddddda0  9ddddddc  [stack:2624]
D/CrashAnrDetector( 1014):          9ddddda4  b8b162a8  [heap]
D/CrashAnrDetector( 1014):          9ddddda8  9cd53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1014):          9dddddac  9da11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1014):          9dddddb0  00000000  
D/CrashAnrDetector( 1014):          9dddddb4  ffffff82  
D/CrashAnrDetector( 1014):          9dddddb8  00000000  
D/CrashAnrDetector( 1014):          9dddddbc  ffffff82  
D/CrashAnrDetector( 1014):          9dddddc0  9cd2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1014):          9dddddc4  b8b132a8  [heap]
D/CrashAnrDetector( 1014):,          9dddddc8  b8bcbd18  [heap]
D/CrashAnrDetector( 1014):          9dddddcc  00000001  
D/CrashAnrDetector( 1014):          9dddddd0  9cd49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1014):          9dddddd4  b8adc500  [heap]
D/CrashAnrDetector( 1014):          9dddddd8  9cd4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1014):          9ddddddc  00000000  
D/CrashAnrDetector( 1014):          9ddddde0  00000000  
D/CrashAnrDetector( 1014):          9ddddde4  00000000  
D/CrashAnrDetector( 1014):          9ddddde8  00000003  
D/CrashAnrDetector( 1014):          9dddddec  000000aa  
D/CrashAnrDetector( 1014):          9dddddf0  0000006b  
D/CrashAnrDetector( 1014):          9dddddf4  0001416e  
D/CrashAnrDetector( 1014):          9dddddf8  00000000  
D/CrashAnrDetector( 1014):          9dddddfc  9dddde30  [stack:2624]
D/CrashAnrDetector( 1014):     #00  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1014):          ........  ........
D/CrashAnrDetector( 1014):     #01  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde04  00000000  
D/CrashAnrDetector( 1014):          9dddde08  9dddde78  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde0c  9dddde5c  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde10  9dddde48  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde14  00000000  
D/CrashAnrDetector( 1014):          9dddde18  9dddee94  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde1c  9d61a3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1014):          9dddde20  9dddde50  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde24  00000000  
D/CrashAnrDetector( 1014):          9dddde28  9dddde44  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde2c  9d44c184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1014):          9dddde30  00000000  
D/CrashAnrDetector( 1014):          9dddde34  00000000  
D/CrashAnrDetector( 1014):          9dddde38  b6f73de4  
D/CrashAnrDetector( 1014):          9dddde3c  00000000  
D/CrashAnrDetector( 1014):          9dddde40  9ddde1cc  [stack:2624]
D/CrashAnrDetector( 1014):          9dddde44  9d528b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1014):          9dddde48  b8adc500  [heap]
D/CrashAnrDetector( 1014):          9dddde4c  b8adc500  [heap]
D/CrashAnrDetector( 1014):          9dddde50  b8bcbd18  [heap]
D/CrashAnrDetector( 1014):          9dddde54  00000001  
D/CrashAnrDetector( 1014):          9dddde58  9
D/CrashAnrDetector( 1014): processName:com.example.hello
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
,D/SettingsProvider( 1014): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 26,
,D/[LPC]   ( 1014): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2715): MountEmulatedStorage(),
E/Zygote  ( 2715): v2
I/libpersona( 2715): KNOX_SDCARD checking this for 1000,
I/libpersona( 2715): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2715 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 2715): TimaSignature is unavailable
,D/ActivityThread( 2715): Added TimaKeyStore provider
,W/ResourcesManager( 2715): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/SecureStorage(  404): [WARN]: SPID(0x00000002)Trying update data block to DB,
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,I/SecureStorage(  404): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 ,
,I/i       ( 1014): No model
,E/SmartFaceService( 1014): onReceive: android.intent.action.BOOT_COMPLETED,
D/SmartFaceIndicator( 1014): no icon
E/SmartFaceService( 1014): mActiveServiceType: 0
E/SmartFaceService( 1014): mLightIntensityEnough: true mLux: 0.0,
D/Stay/Rotation Worker( 1014): updateClientsDone. def. do nothing.
D/SensorService( 1014): [SO] activate (ident=0xb92e4bd0, enabled=0),
E/SmartFaceService( 1014): Service Type to Worker: 0
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/SmartFaceService( 1014): Last Active clients:0 Current Active clients: 0
D/FactoryTest( 1014): Not factory mode
E/SmartFaceService( 1014): Last Smart Pause clients: 0 Current Smart Pause clients: 0
D/FactoryTest( 1014): Not factory mode. isFactoryMode() returend false
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/w       ( 1014): isUserBuild = true
,I/SecureStorage( 2611): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2611): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 2611): FileCipher : Key loaded. 
,D/SecurityLogAgent( 2611): ProcessFileZipCreator : source file  :  file existence : true size after compression : 164
D/SecurityLogAgent( 2611): FileCipher : File ciphering 
D/SecurityLogAgent( 2611): FileCipher : Source file name = denialLog-1481041258.txt.zip source file size 164
,D/SSRM:aZ ( 1014): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1014): Updating Threshold Value.. isSystemReady: true
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1014): [SO] changed settle time [0]
,D/SensorService( 1014): [SO] setDelay [200000000]
D/SecurityLogAgent( 2611): FileCipher : Destination file name = denialLog-1086837759.zip dest file Size 176
D/SensorService( 1014): [SO] activate (ident=0xb9113ac8, enabled=1)
D/SecurityLogAgent( 2611): FileCipher : File ciphered successful 
D/SecurityLogAgent( 2611): ProcessFileZipCreator : source after encryption :  file existence : true file size:176
D/SecurityLogAgent( 2611): ProcessFileZipCreator : File ciphered 
D/SecurityLogAgent( 2611): ProcessFileZipCreatordenialLog-1481041258.txt.zip has been deleted after encryption. 
,D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SecurityLogAgent( 2611): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 2611): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 2611): StateMachine : Current State = 1
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,D/SecurityLogAgent( 2611): FileZippingService : completed task. Returning wakelock . 
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,V/AlarmManagerEXT( 1014): mGmsLocationBundling: false
,I/ActivityManager( 1014): Killing 1191:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 1394:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/RCPManagerService( 1014): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1014):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/RCPManagerService( 1014): BootReceiver.onReceive(): Starting RCP Proxy for user = null
,E/RCPManagerService( 1014):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/SSRM:n  ( 1014): SIOP:: AP = 380
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1014): [SO] activate (ident=0xb9113ac8, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1014): [SO] changed settle time [1]
,D/SensorService( 1014): [SO] setDelay [66000000]
,D/SensorService( 1014): [SO] activate (ident=0xb9113ac8, enabled=1)
D/SensorService( 1014): [SO] AR_init
,I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/EnterpriseDeviceManagerService( 1014): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1014): runAdminUpdate
,D/EnterpriseUtils( 1014): File Not Found : /data/system/selfUpdateAdmin.conf
,D/EnterpriseDeviceManagerService( 1014): nothing to selfUpdate
V/ApplicationPolicy( 1014): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1014): refresh widget status for user 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,W/PhoneRestrictionPolicy( 1014): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1014): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy( 1014): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1014):  >>>> deliveryBlockedMsgs
D/WifiP2pService( 1014): P2pDisabledState{ what=143415 }
,D/WifiP2pService( 1014): DefaultState{ what=143415 }
,E/WifiStateMachine( 1014): Blacklist file delete
W/PhoneRestrictionPolicy( 1014): cvList size 0
W/PhoneRestrictionPolicy( 1014):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1014): cvList size 0
,D/ConnectivityService( 1014): Got NetworkFactory Messenger for WIFI_P2P
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_1191/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10096/pid_1394/cgroup.procs: No such file or directory
D/ConnectivityService( 1014): Got NetworkFactory Messenger for WIFI
,D/WIFI_P2P( 1014): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/Tethering( 1014): Boot complete.
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,V/EnterpriseBillingEngine( 1014): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1014): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1014): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1014): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1014): handleAllprofiles - end
,D/UsbHostNotification( 1014): boot completed
,D/UsbHostRestrictor( 1014): mBootCompletedReceiver onReceive
,D/UsbHostRestrictor( 1014): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1014): SIM was never inserted
,D/UsbHostRestrictor( 1014): writableHostSysNode[false]
D/UsbHostRestrictor( 1014): Can NOT Write Disable Sys Node to [ON]
,D/WIFI    ( 1014): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/PersonaManagerService( 1014): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1014):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1014): onBootComplete
,D/SensorService( 1014): [SO] 0.096 0.383 10.113
,D/SensorService( 1014): [SO] [100 -> 255]
,D/UsbStorageNotification( 1014): boot completed
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1014): BOOT_COMPLETED native_init 
,I/KnoxKeyguardUpdateMonitor( 1014): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1014): onTrustChanged user:0, enable:false
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/KeyguardViewMediator( 1176): onTrustChanged( Showing = false , userId = 0 )
,D/GpsLocationProvider( 1014): set_capabilities_callback: 55u
,I/libmdmdetect( 1014): ESOC framework not supported
,I/libmdmdetect( 1014): Found internal modem: modem
E/PerMgrLib( 1014): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1014): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1014): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1014): BOOT_COMPLETED native_cleanup 
,D/qmi_secgps_clnt( 1014): qmi_secgps_client_init()
,D/StorageNotification( 1176): boot completed
,D/PhoneStatusBar( 1176): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ),
D/StatusBarManagerService( 1014): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1014): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2,
D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/Zygote  ( 2749): MountEmulatedStorage()
,E/Zygote  ( 2749): v2
I/libpersona( 2749): KNOX_SDCARD checking this for 10099
I/libpersona( 2749): KNOX_SDCARD not a persona
,I/SELinux ( 2749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2749 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 2749): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2749): TimaSignature is unavailable
,D/ActivityThread( 2749): Added TimaKeyStore provider
,D/SensorService( 1014): [SO] 0.115 0.383 10.113
,E/LocSvc_utils_cfg( 1014): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1014): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt( 1014): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1014): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1014): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,E/ActivityThread( 2749): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2749): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1014): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1014): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/ActivityManager( 1014): Killing 1538:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/DrmEventReceiver( 1014): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1014): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1014): DrmEventReceiver : beginStartingService
I/System.out( 1014): start Service
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1014): startService callerProcessName:android, calleePkgName: android
,D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0,
,V/DownloadManager( 1226): onReceive intent + android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 2429
E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 2429
,E/LocSvc_ApiV02( 1014): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1014): mCursor = null
,E/Zygote  ( 2771): MountEmulatedStorage()
E/Zygote  ( 2771): v2
I/libpersona( 2771): KNOX_SDCARD checking this for 1000
I/libpersona( 2771): KNOX_SDCARD not a persona
I/SELinux ( 2771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2771 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 2771): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 2785): MountEmulatedStorage(),
I/libpersona( 2785): KNOX_SDCARD checking this for 10152
E/Zygote  ( 2785): v2
I/libpersona( 2785): KNOX_SDCARD not a persona,
I/SELinux ( 2785): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2785 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 2785): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2785): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DrmEventService( 1014): action event :android.intent.action.BOOT_COMPLETED
,I/TimaServiceEventReceiver( 1014): TimaServiceEventReceiver : onReceive
,D/TimaKeyStoreProvider( 2771): TimaSignature is unavailable
,D/ActivityThread( 2771): Added TimaKeyStore provider
,I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/MediaScannerReceiver( 1226): action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ResourcesManager( 2771): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2785): TimaSignature is unavailable
,D/ActivityThread( 2785): Added TimaKeyStore provider
,E/CscReceiver( 1452): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_1538/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
D/BluetoothBDAdrressReceiver( 2771): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media,
W/ContextImpl( 2771): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 ,
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,D/CscUpdateService( 1452): onStart
,E/CscUpdateService( 1452): costomer file is exists : it has been preconfiged.
,I/CscUpdateService( 1452): set_CSC_version
,E/CscParser( 1452): update(): xml file exist
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/CscUtil ( 1452): isWifiOnly = false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,I/System.out( 1452): HandDataNode = null
,I/CscUpdateService( 1452): PATH_CSCNAME =CustomerDataSet.CSCName
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/CscUpdateService( 1452): This is normal boot : CSC not updated
,E/CscParser( 1452): update(): xml file exist
,E/Zygote  ( 2805): MountEmulatedStorage()
I/libpersona( 2805): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2805): v2
I/libpersona( 2805): KNOX_SDCARD not a persona
,I/SELinux ( 2805): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2805 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 2805): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2805): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
I/CscUpdateService( 1452): same CSC Version
D/CscUtil ( 1452): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,E/SQLiteLog( 2785): (284) automatic index on shooting_modes(title_id)
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
D/CscGPS  ( 1452): CSCGPS.updateParameters
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/CscGPS  ( 1452): supl host : null
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/CscGPS  ( 1452): SUPL Host is null or invalid
D/CscGPS  ( 1452): supl_ver : null
D/CscGPS  ( 1452): SUPL Ver is null or invalid
,D/CscGPS  ( 1452): supl port : null
D/CscGPS  ( 1452): SUPL PORT is null or invalid
D/CscGPS  ( 1452): LPP : null
D/CscGPS  ( 1452): LPP is null or invalid
,D/CscGPS  ( 1452): CSC don't have any AGPS value.
,W/ResourcesManager( 1452): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1452): onCreate()
,E/BluetoothBDTestService( 1452): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1452): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1452): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 2818): MountEmulatedStorage()
,I/libpersona( 2818): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2818): v2
I/libpersona( 2818): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 2805): TimaSignature is unavailable
,I/SELinux ( 2818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityThread( 2805): Added TimaKeyStore provider
,I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2818 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 1821:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
D/MediaScannerService( 1226): !@start scanning volume internal: [/system/media, /oem/media]
,I/SELinux ( 2818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/TimaKeyStoreProvider( 2818): TimaSignature is unavailable
D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,D/ActivityThread( 2818): Added TimaKeyStore provider
,D/TP/MmsProvider( 1452): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1452): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ServiceManager(  329): Waiting for service AtCmdFwd...
E/Zygote  ( 2837): MountEmulatedStorage()
E/Zygote  ( 2837): v2
I/libpersona( 2837): KNOX_SDCARD checking this for 1101
I/libpersona( 2837): KNOX_SDCARD not a persona
I/SELinux ( 2837): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2837): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2837): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2837 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,I/Mms:transaction( 2284): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2284): [start]    nonBlockingUpdateMessageIndicator() consume time = 3357.897655
I/Mms/ReservationManager( 2284): resetAfterConnected()
,D/TP/MmsSmsProvider( 1452): query,matched:7, calling pid = 2284
,D/TP/MmsSmsProvider( 1452): match 7:Elapsed time : 3.089 ms
I/art     (  317): Explicit concurrent mark sweep GC freed 8767(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 851us total 21.096ms
D/TimaKeyStoreProvider( 2837): TimaSignature is unavailable
,D/ActivityThread( 2837): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2284): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2284): isDefault true
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 27
,D/TP/MmsProvider( 1452): Query uri=content://mms, match=0, calling pid = 2284
,I/Mms/ReservationManager( 2284): getReservedSendMessageCount(): retMessageCount=0
,D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/TP/MmsSmsProvider( 1452): query,matched:200, calling pid = 2284
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1452): match 200:Elapsed time : 2.279 ms
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.251ms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2837): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.109ms
,E/SQLiteLog( 1226): (283) recovered 142 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
V/SmartcardService( 2837): main Received broadcast
V/SmartcardService( 2837): Starting smartcard service after boot completed
,W/libprocessgroup( 1014): failed to open /acct/uid_10138/pid_1821/cgroup.procs: No such file or directory
,E/Zygote  ( 2854): MountEmulatedStorage()
,I/libpersona( 2854): KNOX_SDCARD checking this for 10048
E/Zygote  ( 2854): v2
I/libpersona( 2854): KNOX_SDCARD not a persona
I/SELinux ( 2854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2854 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,D/ActivityManager( 1014): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
,D/ActivityManager( 1014): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0,
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
I/SELinux ( 2854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1452): query,matched:0, calling pid = 2284
I/ActivityManager( 1014): Killing 1603:com.google.android.apps.maps/u0a107 (adj 15): empty #31
D/TP/SmsProvider( 1452): match 0:Elapsed time : 2.957 ms
I/KnoxUsageLogPro( 2818): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,I/KnoxUsageLogPro( 2818): premStatus:2
,I/KnoxUsageLogPro( 2818): savePreference: key = previous_sys_time value = 1457427810465
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/KnoxUsageLogPro( 2818): isEulaShown : false
I/KnoxUsageLogPro( 2818): KnoxUsageReceiver onReceive : not Processible, just return
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 2854): TimaSignature is unavailable
D/ActivityThread( 2854): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/TP/SmsProvider( 1452): query,matched:51, calling pid = 2284
,D/TP/SmsProvider( 1452): match 51:Elapsed time : 1.933 ms
,D/Mms/SmsReceiverService( 2284): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
D/Mms/TelephonyPermission( 2284): isDefault true
D/Mms/SmsReceiverService( 2284): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2284): [start]    handleBootCompleted() consume time = 111.198437
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2805): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/MediaScanner( 1226): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/libpersona( 2877): KNOX_SDCARD checking this for 10085
E/Zygote  ( 2877): MountEmulatedStorage()
I/libpersona( 2877): KNOX_SDCARD not a persona
E/Zygote  ( 2877): v2,
,I/ActivityManager( 1014): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2877 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 2096:com.vlingo.midas/u0a31 (adj 15): empty #31
,I/SELinux ( 2877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,I/SELinux ( 2877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2877): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 2818): savePreference: key = previous_elapsed_time value = 33707
,I/SecureStorage( 2805): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  404): [INFO]: SPID(0x00000002)Credentials: uid 10003, gid 10003, pid 2805
I/SecureStorage(  404): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 2805): [INFO]: SPID(0x00000000)SS Daemon is running
,I/SecureStorage( 2805): [INFO]: SPID(0x00000000)Processing data
W/ResourcesManager( 2854): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2854): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,I/SecureStorage(  404): [INFO]: SPID(0x00000002)Credentials: uid 10003, gid 10003, pid 2805
I/SecureStorage(  404): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,V/MediaScanner( 1226): processDirectory :  /system/media
,E/Zygote  ( 2893): MountEmulatedStorage(),
E/Zygote  ( 2893): v2
I/libpersona( 2893): KNOX_SDCARD checking this for 10157
I/libpersona( 2893): KNOX_SDCARD not a persona
,I/SELinux ( 2893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2893 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
I/SELinux ( 2893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
E/SELinux ( 2893): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2877): TimaSignature is unavailable
,D/ActivityThread( 2877): Added TimaKeyStore provider,
,D/TimaKeyStoreProvider( 2893): TimaSignature is unavailable
D/ActivityThread( 2893): Added TimaKeyStore provider
,V/MediaScanner( 1226):  prescan time: 209ms (DB items: 141),
V/MediaScanner( 1226):     scan time: 66ms (Caching mode: true), (makeEntry time: 40ms ~60%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 275ms,
V/MediaScanner( 1226): checked files: 133  directories : 6  (I: 0, U: 0),
D/MediaScanner( 1226): checkDefaultSounds
D/MediaScanner( 1226): system alarm_alert  : Vwiurug_etwofi5wgg
,E/Zygote  ( 2911): MountEmulatedStorage()
,E/Zygote  ( 2911): v2
I/libpersona( 2911): KNOX_SDCARD checking this for 1000
I/libpersona( 2911): KNOX_SDCARD not a persona
,I/SELinux ( 2911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_1603/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10031/pid_2096/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2911): TimaSignature is unavailable
,D/ActivityThread( 2911): Added TimaKeyStore provider
,D/SettingsProvider( 1014): name = block_emergency_message
,D/MediaScanner( 1226): OK. alarm_alert is already exist in setting DB.
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 10048
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/ActivityManager( 1014): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,W/ResourcesManager( 2893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1452): getThreadUnReadCount unreadCount=0 imUnreadCount=0
W/ResourcesManager( 2877): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1452): deleteConversation threadId: 9223372036854775806
W/ResourcesManager( 2877): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2877): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2877): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2877): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 2284): isBlockingModeEnabled() = false, Zen mode = 0
,D/MediaScanner( 1226): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1226): OK. notification_sound is already exist in setting DB.
,D/TP/MmsSmsProvider( 1452): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1452): updateThread(), thread_id = 9223372036854775806
,V/TP/MmsSmsDatabaseHelper( 1452): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1452): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
,D/MediaScanner( 1226): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/Mms/Conversation( 2284): deleteTempConversation(),deleted=0
,D/BadgeProvider( 1557): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/MediaScanner( 1226): OK. ringtone is already exist in setting DB.
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,I/WifiCredService( 1282): onCreate
,D/FactoryTestApp( 2648): [DummyFtClient$mBroadcastReceiver](2648) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2648): [DummyFtClient$mBroadcastReceiver](2648) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2648): [DummyFtClient$mBroadcastReceiver](2648) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/SmsProvider( 1452): Update uri=content://sms/outbox, match=8
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
,D/MediaScannerService( 1226): !@done scanning volume internal
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Launcher.Model( 1472): reloadBadges entered.,
D/BadgeProvider( 1557): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): sendNotify, [notify] : null
D/BadgeProvider( 1557): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1557): update, [UpdateCount] : 1
,E/Zygote  ( 2929): MountEmulatedStorage()
E/Zygote  ( 2929): v2
I/libpersona( 2929): KNOX_SDCARD checking this for 10159
I/libpersona( 2929): KNOX_SDCARD not a persona
,I/SELinux ( 2929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2929 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 2929): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/MediaScannerService( 1226): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{ffd017b u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/Mms/SmsReceiverService( 2284): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2284): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2284): [SIM-1]sendFirstQueuedMessage()
,D/Mms/MessagingNotification( 2284): setBadgeCount(), count=0
,D/WifiTimerReceiver( 1282): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1282): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1282): Action boot completed received
D/TP/SmsProvider( 1452): query,matched:26, calling pid = 2284
,D/Mms/MessagingNotification( 2284): remove alarm
,D/TimaKeyStoreProvider( 2929): TimaSignature is unavailable
,D/ActivityThread( 2929): Added TimaKeyStore provider
,D/TP/SmsProvider( 1452): query,matched:0, calling pid = 2284
D/TP/SmsProvider( 1452): match 26:Elapsed time : 7.972 ms
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/Mms/MessagingNotification( 2284): updateAllHistoryAsRead()
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1226): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/ActivityManager( 1014): Killing 1487:com.android.printspooler/u0a136 (adj 15): empty #31
,I/Intent to TravelDirActivity( 2929): inside TravelBroadcastReceiver
,D/NearbySettings( 1282): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1282): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1282): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 1282): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1282): MountReceiver.mPrefHandler - 7002
D/SettingsProvider( 1014): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,I/art     ( 1452): Explicit concurrent mark sweep GC freed 39264(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 994us total 93.156ms
,I/art     ( 1452): WaitForGcToComplete blocked for 93.557ms for cause Explicit
E/SQLiteLog( 2911): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,I/NearbySettings( 1282): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1282): MountReceiver.onReceive - Internal Path
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/art     ( 1452): Explicit concurrent mark sweep GC freed 1811(71KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/13MB, paused 906us total 41.167ms
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 40938(2MB) AllocSpace objects, 26(1545KB) LOS objects, 33% free, 25MB/38MB, paused 2.330ms total 163.203ms
,D/TP/SmsProvider( 1452): match 0:Elapsed time : 212.603 ms
,D/SettingsProvider( 1014): name = personal_mode_enabled
,D/Mms/MessagingNotification( 2284): [end]    nonBlockingUpdateMessageIndicator() consume time = 557.312031
,W/libprocessgroup( 1014): failed to open /acct/uid_10136/pid_1487/cgroup.procs: No such file or directory
,D/Mms/SmsReceiver( 2284): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2284): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2284): isDefault true
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/DSM     ( 2911): [Lines:107] Normal booted
,D/DSM     ( 2911): [Lines:114] Boot completed
,V/MediaScanner( 1226): processDirectory :  /storage/emulated/0
,E/Zygote  ( 2955): MountEmulatedStorage(),
E/Zygote  ( 2955): v2
I/libpersona( 2955): KNOX_SDCARD checking this for 1000
I/libpersona( 2955): KNOX_SDCARD not a persona
,I/SELinux ( 2955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/MediaScanner( 1226): Skipping:
I/ActivityManager( 1014): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(75ebcf7
I/ActivityManager( 1014): Killing 2125:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
E/SELinux ( 2955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/MmsProvider( 1452): Query uri=content://mms, match=0, calling pid = 2284
,W/ResourcesManager( 1452): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1452): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2955): TimaSignature is unavailable
D/ActivityThread( 2955): Added TimaKeyStore provider
,E/Zygote  ( 2966): MountEmulatedStorage()
E/Zygote  ( 2966): v2
I/libpersona( 2966): KNOX_SDCARD checking this for 1000
I/libpersona( 2966): KNOX_SDCARD not a persona
,I/SELinux ( 2966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 2966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 2190:com.google.android.apps.magazines/u0a113 (adj 15): empty #31,
E/SELinux ( 2966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaScanner( 1226): processDirectory :  /storage/extSdCard
W/MediaScanner( 1226): Error opening directory, reason : Permission denied.
W/MediaScanner( 1226): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1226):  prescan time: 207ms (DB items: 27)
V/MediaScanner( 1226):     scan time: 59ms (Caching mode: true), (makeEntry time: 17ms ~28%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 5ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 271ms
V/MediaScanner( 1226): checked files: 10  directories : 17  (I: 0, U: 0)
,I/SmartcardBootCompleteReceiver( 1282): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1282): Received intent with action - android.intent.action.BOOT_COMPLETED
D/FactoryTestApp( 2648): [DummyFtClient$mBroadcastReceiver](2648) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2648): [DummyFtClient$mBroadcastReceiver](2648) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2648): [DummyFtClient$sendBootCompletedAndFinish](2648) ...
D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2648): [ModuleCommon$isConnectionModeNone](2648) mConnectionMode = gsm
,D/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$ResponseWriter](2648) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$connectToSecPhoneService](2648)  
,D/SettingsProvider( 1014): name = next_alarm_formatted
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10085
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/ContextImpl( 2648): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/ActivityManager( 1014): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,D/MediaScannerService( 1226): !@done scanning volume external
,D/TimaKeyStoreProvider( 2966): TimaSignature is unavailable
,D/ActivityThread( 2966): Added TimaKeyStore provider
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,I/iu.UploadsManager( 2023): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SmartcardBootCompleteReceiver( 1282): Broadcast sent with current lockscreen type
,I/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$onServiceConnected](2648) connected done
D/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$write](2648) Send Response Message to SecPhone
D/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$write](2648) Response ��
,W/ResourcesManager( 2966): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1452): query,matched:200, calling pid = 2284
,D/TP/MmsSmsProvider( 1452): match 200:Elapsed time : 23.829 ms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/AT_Distributor(  325): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$handleMessage](2648) Send BOOTING COMPLETED done
,E/Zygote  ( 2991): MountEmulatedStorage(),
I/libpersona( 2991): KNOX_SDCARD checking this for 10160
E/Zygote  ( 2991): v2
I/libpersona( 2991): KNOX_SDCARD not a persona
I/SELinux ( 2991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2991 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,W/ActivityThread( 2966): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/SELinux ( 2991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[SBeam] ( 1282): SBeamEnabler.initPreferenceForSbeam : 0
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,I/SettingSearch/SearchIntentReceiver( 1282): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1282): search setting db init!!
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/SecureStorage(  404): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
I/SettingSearch/SearchIntentReceiver( 1282): BOOT_COMPLETED call InitSerachDBThread thread start!
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2991): TimaSignature is unavailable
,D/ActivityThread( 2991): Added TimaKeyStore provider
,D/TP/SmsProvider( 1452): query,matched:0, calling pid = 2284
,D/TP/SmsProvider( 1452): match 0:Elapsed time : 3.261 ms
,E/Zygote  ( 3007): MountEmulatedStorage()
E/Zygote  ( 3007): v2
I/libpersona( 3007): KNOX_SDCARD checking this for 1000
I/ActivityManager( 1014): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3007 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 3007): KNOX_SDCARD not a persona
I/SELinux ( 3007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2805): [INFO]: SPID(0x00000003)Processing data has been completed
I/SecureStorage( 2805): [INFO]: SPID(0x00000003)Skip using SecureStorageExceptionJNI
,D/AT_Distributor(  325): SetAtdStatus(), 1_1_0
I/ActivityManager( 1014): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3017 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/AT_Distributor(  325): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
I/libpersona( 3017): KNOX_SDCARD checking this for 10150
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
I/libpersona( 3017): KNOX_SDCARD not a persona
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
E/Zygote  ( 3017): MountEmulatedStorage()
E/Zygote  ( 3017): v2
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
I/SELinux ( 3017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
I/iu.UploadsManager( 2023): End new media; added: 0, uploading: 0, time: 176 ms
W/ResourcesManager( 2991): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/SELinux ( 3017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/TimaKeyStoreProvider( 3007): TimaSignature is unavailable
E/SELinux ( 3017): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityThread( 3007): Added TimaKeyStore provider
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,E/SMD     (  292): DCD OFF
D/LcdtestApp( 2966): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/ServiceManager(  329): Waiting for service AtCmdFwd...
D/TimaKeyStoreProvider( 3017): TimaSignature is unavailable
,D/ActivityThread( 3017): Added TimaKeyStore provider
,I/LcdtestApp( 2966): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,W/ResourcesManager( 3007): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1452): query,matched:51, calling pid = 2284
,D/TP/SmsProvider( 1452): match 51:Elapsed time : 1.113 ms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3039): MountEmulatedStorage(),
I/libpersona( 3039): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3039): v2
I/libpersona( 3039): KNOX_SDCARD not a persona
I/SELinux ( 3039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/USB_UICC(  308): Timeout! No signal received. Retry num = 28
,W/art     ( 2877): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 224.310ms
I/ActivityManager( 1014): Killing 1635:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/SELinux ( 3039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3039): TimaSignature is unavailable,
D/ActivityThread( 3039): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 29.079ms
,D/Mms/MessagingNotification( 2284): isBlockingModeEnabled() = false, Zen mode = 0
,D/BadgeProvider( 1557): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,W/libprocessgroup( 1014): failed to open /acct/uid_10050/pid_2125/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10113/pid_2190/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_1635/cgroup.procs: No such file or directory
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 27.278ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 16.663ms
,I/FOTA    ( 3007): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/[0]UMC:UMCContentProvider( 2991): @onCreate
,D/Launcher.Model( 1472): reloadBadges entered.
,D/BadgeProvider( 1557): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 1557): sendNotify, [notify] : null
D/BadgeProvider( 1557): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1557): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 2284): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2284): remove alarm
,D/[0]UMC:Core( 2991): onCreate(): 
,D/Mms/MessagingNotification( 2284): updateAllHistoryAsRead()
,D/[0]UMC:Core( 2991): @isManagedProfileUser
D/[0]UMC:Core( 2991): userId: 0
,D/[0]UMC:Core( 2991): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2991): userInfo.isManagedProfile() : false
,D/TP/SmsProvider( 1452): query,matched:0, calling pid = 2284
,D/TP/SmsProvider( 1452): match 0:Elapsed time : 1.545 ms
,D/Mms/SmsReceiverService( 2284): [end]    handleBootCompleted() consume time = 488.94401
,I/ActivityManager( 1014): Killing 2263:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,I/DIAGMON_AGENT( 3039): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/[0]UMC:DeviceInfo( 2991): USA==US==
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2263/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3007): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3007): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1014): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/OverheatReceiver( 1176): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1176): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1176): VZW on -> change to Global UX [safe mode]
I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/OverheatReceiver( 1176): isSafeMode = false
,I/DBG_DM  ( 3007): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3007): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 3007): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,D/BootupListener( 1452): intent.getAction() = android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3007): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,D/SettingsProvider( 1014): name = internet_call_settings_visibility
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
D/SettingsProvider( 1014): ret = -1
,D/PhoneUtilsCommon( 1452): isSupportVoLTE is false.
,I/DBG_DM  ( 3007): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/Telecom ( 1425): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,E/Zygote  ( 3059): MountEmulatedStorage()
I/libpersona( 3059): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3059): v2
I/libpersona( 3059): KNOX_SDCARD not a persona
I/DBG_DM  ( 3007): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/SELinux ( 3059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
E/SELinux ( 3059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/ActivityManager( 1014): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 2301:com.sec.android.omc/1000 (adj 15): empty #31
D/ActivityManager( 1014): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3007): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
W/ContextImpl( 3007): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,D/ActivityManager( 1014): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
E/BluetoothHeadset( 2805): BTStateChangeCB is registed
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/BluetoothHeadset( 2805): doBind(): CallingUid(myUserHandle) = 0
I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(155/onStartCommand)] 
D/ActivityManager( 1014): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/ActivityManager( 1014): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2805): BluetoothHeadset service is binded
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,D/BluetoothA2dp( 2805): doBind(): CallingUid(myUserHandle) = 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3059): TimaSignature is unavailable
,D/ActivityThread( 3059): Added TimaKeyStore provider
,E/Zygote  ( 3074): MountEmulatedStorage()
,E/Zygote  ( 3074): v2
I/libpersona( 3074): KNOX_SDCARD checking this for 10057
I/libpersona( 3074): KNOX_SDCARD not a persona
I/SELinux ( 3074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3074 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,D/ActivityManager( 1014): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
I/SELinux ( 3074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/SELinux ( 3074): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/Telecom ( 1425): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/DBG_DM  ( 3007): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/BluetoothAdapter( 2805): 214902706: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2805): 214902706: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2805): 214902706: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2805): 214902706: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2805): 214902706: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager( 3059): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2301/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3074): TimaSignature is unavailable
,D/ActivityThread( 3074): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 3039): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/ActivityManager( 1014): Killing 2332:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/DIAGMON_AGENT( 3039): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 3039): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 3039): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,I/DIAGMON_AGENT( 3039): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 3039): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/USER_AGENT( 2991): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,I/DBG_DM  ( 3007): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:AdminManager( 2991): init - start
,E/Zygote  ( 3090): MountEmulatedStorage()
,E/Zygote  ( 3090): v2
I/libpersona( 3090): KNOX_SDCARD checking this for 10086
I/libpersona( 3090): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3090 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 2347:com.sec.tcpdumpservice/1000 (adj 15): empty #31
I/SELinux ( 3090): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3090): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3090): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3090): TimaSignature is unavailable
,D/ActivityThread( 3090): Added TimaKeyStore provider
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,V/audio_hw_primary(  286): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  286): audio_extn_get_parameters: returns 
V/msm8974_platform(  286): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  286): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  286): key: 'call_forwarding' value: ''
,V/InCall  ( 1980): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1980): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1980): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1980): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
E/Tethering( 1014): No numeric data
,D/InCall  ( 1980): InCallUtils - isCoverClosed false
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,I/Telecom ( 1425): ProximitySensorManager: Proximity wake lock already released
D/InCall  ( 1980): InCallUtils - isCoverClosed false
I/InCall  ( 1980): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1980): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1980): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1980): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1980): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,I/DBG_DM  ( 3007): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,D/PhoneStatusBarView( 1176): setCallBackground:0
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1980): InCallUtils - isCoverClosed false
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,D/[0]UMC:AdminManager( 2991): loadAdmins
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3107): MountEmulatedStorage()
,E/Zygote  ( 3107): v2
I/libpersona( 3107): KNOX_SDCARD checking this for 1000
I/libpersona( 3107): KNOX_SDCARD not a persona
,I/SELinux ( 3107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/[0]UMC:AdminManager( 2991): init - end
,D/GSLBManager( 2991): migrateStoredUrlFromOldPref
,D/GSLBManager( 2991): migrateStoredUrlFromOldPref : Migration Not Needed
,D/TimaKeyStoreProvider( 3107): TimaSignature is unavailable
,D/ActivityThread( 3107): Added TimaKeyStore provider
,D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2991): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2991): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
,D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2991): No active admin owned by uid 10160
,D/[0]UMC:UMCAdmin( 2991): isContainer : 0
,D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin - UMC App Admin deactivated
,W/libprocessgroup( 1014): failed to open /acct/uid_10131/pid_2332/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2347/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2991): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/[0]UMC:CoreReceiver( 2991): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2991):  check PreETag 
,I/DBG_DM  ( 3007): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/UpdateRequestReceiver( 3090): ignoring update request
,D/[SBeam] ( 1282): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1282): SBeamEnabler.isSBeamSupported : EXIST
,E/UpdateRequestReceiver( 3090): ignoring update request
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3007): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT,
,E/Zygote  ( 3134): MountEmulatedStorage()
E/Zygote  ( 3134): v2
,I/libpersona( 3134): KNOX_SDCARD checking this for 10015
,I/libpersona( 3134): KNOX_SDCARD not a persona
,I/SELinux ( 3134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/[0]UMC:CoreReceiver( 2991): bulk enrolled package: null
,I/SELinux ( 3134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,V/[0]UMC:ProfileStorage( 2991): Enter loadList
D/[0]UMC:CoreReceiver( 2991): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdminIfNotRequired : -1
E/SELinux ( 3134): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/[0]UMC:Utils( 2991): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2991): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
,D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
,I/ActivityManager( 1014): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3134 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/[0]UMC:UMCAdmin( 2991): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
,D/VideoCallManager( 1980): Instantiating VideoCallManager
,D/LocationManagerService( 1014): getProviders()=[passive]
,E/Tethering( 1014): No numeric data
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1980): took 2.923334ms for 0*0 texture 0
,E/Tethering( 1014): No numeric data
,D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin - UMC App Admin deactivated
,I/GFX generate_partition_tables( 1980): took 5.754271ms for 0*0 texture 0
,E/Tethering( 1014): No numeric data
,D/TimaKeyStoreProvider( 3134): TimaSignature is unavailable
,D/ActivityThread( 3134): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 3090): ignoring update request
,I/GFX raster( 1980): took 13.571093ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb8eb9530 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8ec78b0 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1980): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1980): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1980): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1980): Local Branch: 
I/Adreno-EGL( 1980): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1980): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1980):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/[0]UMC:ByodSetupStarter( 2991): Container ID : 0
V/[0]UMC:Utils( 2991): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2991): shutdown
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2991): @GuardService - stopService Result = true
E/Tethering( 1014): No numeric data
E/UpdateRequestReceiver( 3090): ignoring update request
,I/art     ( 2991): System.exit called, status: 0
,I/AndroidRuntime( 2991): VM exiting with result code 0, cleanup skipped.
,I/GFX GPU raster( 1980): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1980): took 0.289479ms for 320*61440 texture 37809
,E/UpdateRequestReceiver( 3090): ignoring update request
,I/draw setup( 1980): took 11.838281ms for 320*240 texture 37809
E/GFX GPU raster( 1980): drawn
,I/GFX GPU raster ASTC( 1980): took 46.224010ms for 320*240 texture 12
I/GFX raster( 1980): took 46.305728ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb8ec6e48 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8eb9348 counterpartCT=4 counterpartW=320 counterparth=240
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,E/UpdateRequestReceiver( 3090): ignoring update request
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1980): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1980): took 0.371771ms for 480*122880 texture 37813
I/draw setup( 1980): took 0.769740ms for 480*640 texture 37813
E/GFX GPU raster( 1980): drawn
,I/GFX GPU raster ASTC( 1980): took 7.526459ms for 480*640 texture 12
I/GFX raster( 1980): took 7.603438ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb8eb9348 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb90f6568 counterpartCT=4 counterpartW=480 counterparth=640
,E/Zygote  ( 3164): MountEmulatedStorage()
E/Zygote  ( 3164): v2
I/libpersona( 3164): KNOX_SDCARD checking this for 10092
I/libpersona( 3164): KNOX_SDCARD not a persona
,I/SELinux ( 3164): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3164): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3164 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3164): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3164): TimaSignature is unavailable
,D/ActivityThread( 3164): Added TimaKeyStore provider
,W/NotificationAccessSettings( 1282): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1980): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1980): took 0.371875ms for 440*116864 texture 37809
I/draw setup( 1980): took 0.874531ms for 440*330 texture 37809
E/GFX GPU raster( 1980): drawn
,I/GFX GPU raster ASTC( 1980): took 5.292032ms for 440*330 texture 12
,I/GFX raster( 1980): took 5.374116ms for 440*330 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb910a688 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb910a9b0 counterpartCT=4 counterpartW=440 counterparth=330
,W/ResourcesManager( 1282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2991)(adj 0) has died(274,993)
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/Zygote  ( 3189): MountEmulatedStorage()
,E/Zygote  ( 3189): v2,
I/libpersona( 3189): KNOX_SDCARD checking this for 10009
I/libpersona( 3189): KNOX_SDCARD not a persona
,I/SELinux ( 3189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
I/SELinux ( 3189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3189 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GFX GPU raster( 1980): eglCreateImageKHR: EGL_SUCCESS
D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
E/SELinux ( 3189): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
I/glCompressedTexImage2D( 1980): took 1.252084ms for 480*163840 texture 37811
I/draw setup( 1980): took 1.659844ms for 480*640 texture 37811
E/GFX GPU raster( 1980): drawn
E/USB_UICC(  308): Timeout! No signal received. Retry num = 29
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/GFX GPU raster ASTC( 1980): took 7.532708ms for 480*640 texture 12
I/GFX raster( 1980): took 7.625833ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb911f440 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb90fab40 counterpartCT=4 counterpartW=480 counterparth=640
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/ActivityManager( 1014): Killing 2254:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/ActivityManager( 1014): Killing 1557:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3189): TimaSignature is unavailable
,D/ActivityThread( 3189): Added TimaKeyStore provider
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1980): took 2.326302ms for 0*0 texture 0
,I/DBG_POLICYDM( 3107): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,W/TRThreadPoolExecutor( 3074): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/DBG_POLICYDM( 3107): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/SearchServiceFactory( 3074): refreshing search history.
,I/GFX generate_partition_tables( 1980): took 7.576927ms for 0*0 texture 0
,I/DBG_POLICYDM( 3107): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/GFX raster( 1980): took 11.835729ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb90f3e08 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb90f3f08 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_POLICYDM( 3107): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1309): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1309): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,I/DBG_POLICYDM( 3107): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,E/        ( 1980): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 1980): took 2.183853ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1980): took 6.031304ms for 0*0 texture 0
,I/GFX raster( 1980): took 10.370416ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1980): Bitmap=0xb90f3cf0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb90f6568 counterpartCT=4 counterpartW=176 counterparth=144
,E/Zygote  ( 3209): MountEmulatedStorage(),
E/Zygote  ( 3209): v2
I/libpersona( 3209): KNOX_SDCARD checking this for 10003
I/libpersona( 3209): KNOX_SDCARD not a persona,
I/SELinux ( 3209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ScoverManager( 1980): registerListener,
,I/SELinux ( 3209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH,
E/SELinux ( 3209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3209 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/DBG_POLICYDM( 3107): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,I/DBG_POLICYDM( 3107): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1410): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1410): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1176): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1176): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/ScoverManager( 1282): serviceVersion : 16908288
,W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_1557/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2254/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3209): TimaSignature is unavailable
,D/ActivityThread( 3209): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 12577(673KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 25MB/38MB, paused 2.237ms total 180.013ms
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManager.StateNotifier( 1014): registerListenerCallback : binder = android.os.BinderProxy@100cd592, pid : 1980, uid : 1001, type : 1
,I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SettingsProvider( 1014): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10162
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/InCall  ( 1980): InCallPresenter -  - Finished InCallPresenter.setUp
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1309): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1309): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457427812716
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457449380000
D/daemonapp( 1309): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1309): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457449380000
,I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
,D/Settings_Utils( 1282): isSupportVNFestival SM-A500FU XEO
,D/UserAnalysis.PlaceProvider( 3209): PlaceProvider onCreate()
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 82
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457449380000
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3233): MountEmulatedStorage()
E/Zygote  ( 3233): v2
I/libpersona( 3233): KNOX_SDCARD checking this for 1000
,I/libpersona( 3233): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3233 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3233): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Killing 2467:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 2452:com.sec.android.gallery3d/u0a44 (adj 15): empty #32,
I/ActivityManager( 1014): Killing 2403:com.wsomacp/u0a25 (adj 15): empty #33
,I/SELinux ( 3233): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3233): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3107): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/DBG_POLICYDM( 3107): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3107): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/TimaKeyStoreProvider( 3233): TimaSignature is unavailable
,D/ActivityThread( 3233): Added TimaKeyStore provider
,D/comdaemonstockapp( 1309): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1309): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.SecureDbManager( 3209): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3209): SecurePlaceDbHelper() 
D/UserAnalysis( 3209): Create SecureDbHelper
,I/WebViewFactory( 3074): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,E/Zygote  ( 3248): MountEmulatedStorage()
E/Zygote  ( 3248): v2
I/libpersona( 3248): KNOX_SDCARD checking this for 10166
I/libpersona( 3248): KNOX_SDCARD not a persona
,I/SELinux ( 3248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3248 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3248): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 3074): Time to load native libraries: 2 ms (timestamps 6186-6188)
I/LibraryLoader( 3074): Expected native library version number "",actual native library version number ""
,I/DBG_FMMDM( 3233): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,E/Zygote  ( 3265): MountEmulatedStorage()
E/Zygote  ( 3265): v2
I/libpersona( 3265): KNOX_SDCARD checking this for 10092
I/libpersona( 3265): KNOX_SDCARD not a persona
I/SELinux ( 3265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3265 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3265): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/art     ( 3074): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 3248): TimaSignature is unavailable
,D/ActivityThread( 3248): Added TimaKeyStore provider
,W/TRThreadPoolExecutor( 3074): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_2403/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_2452/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10088/pid_2467/cgroup.procs: No such file or directory
,D/IntelligenceServiceApplication( 3209): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3209): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,I/art     (  317): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.161ms total 33.385ms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3265): TimaSignature is unavailable
I/DBG_FMMDM( 3233): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,D/ActivityThread( 3265): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 3209): no applications having user consent for prediction
,I/DBG_FMMDM( 3233): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3233): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 25.126ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 23.267ms,
,E/Zygote  ( 3285): MountEmulatedStorage()
E/Zygote  ( 3285): v2
I/libpersona( 3285): KNOX_SDCARD checking this for 10060
,I/libpersona( 3285): KNOX_SDCARD not a persona
I/SELinux ( 3285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3285 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3285): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 2480:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
V/PlaceDetection v1.0.19 ( 3209): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3285): TimaSignature is unavailable
D/ActivityThread( 3285): Added TimaKeyStore provider
,E/Zygote  ( 3302): MountEmulatedStorage()
E/Zygote  ( 3302): v2,
I/libpersona( 3302): KNOX_SDCARD checking this for 1000
I/libpersona( 3302): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Killing 2512:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/SELinux ( 3302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 2611:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,V/AlarmManager( 1014): waitForAlarm result :8
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3302): TimaSignature is unavailable
,D/ActivityThread( 3302): Added TimaKeyStore provider
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,V/PlaceDetection v1.0.19 ( 3209): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3209): Constructor Preference
,I/PCWCLIENTTRACE_LOG( 3302): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3302): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3302): new DMDBOpenHelper instance
,W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_2480/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10139/pid_2512/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2611/cgroup.procs: No such file or directory
,D/PCWCLIENTTRACE_DMContentProvider( 3302): [URIMatcher] - result : 2
,I/ActivityManager( 1014): Killing 2566:com.android.calendar/u0a135 (adj 15): empty #31
,I/DBG_FMMDM( 3233): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3233): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3233): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1014): Killing 1755:com.android.defcontainer/u0a4 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 2677:com.android.keychain/1000 (adj 15): empty #32
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3319): MountEmulatedStorage()
E/Zygote  ( 3319): v2
I/libpersona( 3319): KNOX_SDCARD checking this for 1000
I/libpersona( 3319): KNOX_SDCARD not a persona
,I/SELinux ( 3319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3319 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3164): Setting receiver enabled: false
,D/TimaKeyStoreProvider( 3319): TimaSignature is unavailable
,D/ActivityThread( 3319): Added TimaKeyStore provider
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/USB_UICC(  308): Timeout! No signal received. Retry num = 30
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2677/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10004/pid_1755/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_2566/cgroup.procs: No such file or directory
,W/ResourcesManager( 3248): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/DBG_FMMDS( 3319): [50.18.150420][Line:56][onCreate] FMMDS Application Start
W/ResourcesManager( 3248): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_FMMDS( 3319): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,E/ActivityThread( 3164): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,V/JNIHelp ( 3248): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PCWCLIENTTRACE_DMContentProvider( 3302): [URIMatcher] - result : 2
,E/USB_UICC(  308): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  308): usb_uicc_init_qmi failed ! 
I/USB_UICC(  308): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  308): usb_uicc_cleanup, Issuing QMI deinit ... 
E/DBG_FMMDS( 3319): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/dbxyzptlk.db240408.D.h( 3164): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/DBG_FMMDS( 3319): [50.18.150420][Line:43][xdbDBInit] 
,I/sCloudBackupApp( 3285): sCloudBackupApp Version Info : 4.04.8.KK_APP
,I/dbxyzptlk.db240408.D.h( 3164): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3164): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,W/ActivityThread( 3248): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3248): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@227ce162: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3248): Installed default security provider GmsCore_OpenSSL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3348): MountEmulatedStorage()
,E/Zygote  ( 3348): v2
I/libpersona( 3348): KNOX_SDCARD checking this for 10062
,I/libpersona( 3348): KNOX_SDCARD not a persona
,I/SELinux ( 3348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3348 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3348): TimaSignature is unavailable
,D/ActivityThread( 3348): Added TimaKeyStore provider
,I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
,I/ExternalOEMControlProvider( 3348): onCreate
,I/dbxyzptlk.db240408.D.h( 3164): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/breakpad( 3164): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps",
,E/Zygote  ( 3367): MountEmulatedStorage(),
E/Zygote  ( 3367): v2
I/libpersona( 3367): KNOX_SDCARD checking this for 1000
I/SELinux ( 3367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3367): KNOX_SDCARD not a persona
,I/SELinux ( 3367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1014): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3367 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2715:com.samsung.android.sm/1000 (adj 15): empty #31
,E/SELinux ( 3367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1014): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10062
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/TimaKeyStoreProvider( 3367): TimaSignature is unavailable
,D/ActivityThread( 3367): Added TimaKeyStore provider
,I/com.dropbox.sync.android.a( 3164): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,W/ResourcesManager( 3367): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/DBG_FMMDS( 3319): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/ServiceMode( 3367): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3367): setReferenceIsDumpState : 0
,D/SettingsProvider( 1014): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10062
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,I/DBG_FMMDS( 3319): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3319): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_FMMDS( 3319): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
I/DBG_FMMDS( 3319): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3319): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3319): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,E/Zygote  ( 3390): MountEmulatedStorage()
E/Zygote  ( 3390): v2
I/libpersona( 3390): KNOX_SDCARD checking this for 1000
I/libpersona( 3390): KNOX_SDCARD not a persona
,I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,W/art     ( 3248): Suspending all threads took: 7.208ms
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
,D/ActivityThread( 3390): Added TimaKeyStore provider
,I/com.dropbox.sync.android.ad( 3164): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,I/FOTA_Client( 3189): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3189): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2715/cgroup.procs: No such file or directory
,I/FOTA_Client( 3189): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,W/ResourcesManager( 3248): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3248): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/FOTA_Client( 3189): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3413): MountEmulatedStorage()
E/Zygote  ( 3413): v2
,I/libpersona( 3413): KNOX_SDCARD checking this for 10014
I/libpersona( 3413): KNOX_SDCARD not a persona
,I/SELinux ( 3413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3413): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3390): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,I/ActivityManager( 1014): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3413 uid=10014 gids={50014, 9997} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 2749:flipboard.boxer.app/u0a99 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/TimaKeyStoreProvider( 3413): TimaSignature is unavailable
D/ActivityThread( 3413): Added TimaKeyStore provider
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,I/ActivityManager( 1014): Killing 2141:flipboard.app/u0a98 (adj 15): empty #31
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1282): InitSerachDBThread thread end!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,D/NPS_WSSNPS( 3390): [] Service onCreate!!
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/dex2oat ( 3411): ----------------------------------------------------
I/dex2oat ( 3411): <SS>: S T A R T I N G . . .
I/dex2oat ( 3411): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3411): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1481041258.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1481041258.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Zygote  ( 3433): MountEmulatedStorage()
E/Zygote  ( 3433): v2
I/libpersona( 3433): KNOX_SDCARD checking this for 1000
I/libpersona( 3433): KNOX_SDCARD not a persona
,I/SELinux ( 3433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3433): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3433 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,V/OneTimeInitializerReceiver( 3413): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3433): TimaSignature is unavailable
,D/ActivityThread( 3433): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3390): [50.150621] NpsServiceTask Start,
,E/Zygote  ( 3454): MountEmulatedStorage()
,E/Zygote  ( 3454): v2
I/libpersona( 3454): KNOX_SDCARD checking this for 10094
I/libpersona( 3454): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3454 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2771:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/SELinux ( 3454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/ResourcesManager( 3433): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/NPS_WSSNPS( 3390): [50.150621] smlDBHelper
,V/OneTimeService( 3413): OneTimeService.onHandleIntent
,D/TimaKeyStoreProvider( 3454): TimaSignature is unavailable
,D/ActivityThread( 3454): Added TimaKeyStore provider
,W/System.err( 3248): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3411): dex2oat took 105.846ms (threads: 4)
,I/System.out( 3164): Thread-430(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
I/System.out( 3164): Thread-430(ApacheHTTPLog):isSBSettingEnabled false
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
I/System.out( 3164): Thread-430(ApacheHTTPLog):isShipBuild true
I/System.out( 3164): Thread-430(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3164): Thread-430(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
D/EnterpriseController(  278): uids 10092
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10092
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/System.out( 3164): pool-10-thread-1 calls detatch()
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/elm:15183( 3454): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3454): ELMEngine.ELMEngine( context ).
I/FactoryTestApp( 2648): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2989)  
,D/elm:15183( 3454): MDMBridge.setEnterpriseBridge()
,I/ActivityManager( 1014): Killing 2785:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3454): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,V/EmergencyMode( 1410): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 3454): ElmAgentService : onCreate()
,D/elm:15183( 3454): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3454): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3454): BootCompletedState : startBootCompleted() call
,I/System.out( 3248): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 3248): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 3248): YouTube MDX: MDX ad player state moved to UNSTARTED
,E/Zygote  ( 3488): MountEmulatedStorage(),
E/Zygote  ( 3488): v2
I/libpersona( 3488): KNOX_SDCARD checking this for 1000
I/libpersona( 3488): KNOX_SDCARD not a persona
,D/elm:15183( 3454): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 3488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/elm:15183( 3454): Get License : 0
I/ActivityManager( 1014): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3488 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3488): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/NPS_WSSNPS( 3390): [50.150621] AsyncBulkFlagCheck
D/elm:15183( 3454): ElmAgentService : onDestroy().
V/EmergencyMode( 1410): [EmergencyBase] setBootTime
V/EmergencyMode( 1410): [EmergencyFactory] No Recovery State, kill my self.
,I/ActivityManager( 1014): Killing 2314:com.sec.modem.settings/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3390): [50.150621] IsRemain_AsyncBulkCheck
,E/Zygote  ( 3501): MountEmulatedStorage()
E/Zygote  ( 3501): v2
I/libpersona( 3501): KNOX_SDCARD checking this for 1000
I/libpersona( 3501): KNOX_SDCARD not a persona
,I/SELinux ( 3501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3501): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3501 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/NPS_WSSNPS( 3390): [50.150621] IsRemain_Asyncing nothing
W/ContextImpl( 3390): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3390): [50.150621] Service onDestroy
,D/TimaKeyStoreProvider( 3488): TimaSignature is unavailable
,D/ActivityThread( 3488): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3390): [50.150621] smlBRConfigurationDelete
,I/art     ( 1653): Explicit concurrent mark sweep GC freed 7164(354KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 759us total 51.814ms
,I/NPS_WSSNPS( 3390): [50.150621] smlBRMessageDelete
I/NPS_WSSNPS( 3390): [50.150621] smlBREmailDelete
I/NPS_WSSNPS( 3390): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3390): [50.150621] smlBRCallLogDelete
,I/art     (  317): Explicit concurrent mark sweep GC freed 8782(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 33.119ms
,I/NPS_WSSNPS( 3390): [50.150621] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3390): [50.150621] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3390): [50.150621] smlBRSMemoDelete
,I/NPS_WSSNPS( 3390): [50.150621] verifier installed? false
,I/NPS_WSSNPS( 3390): [50.150621] cpuBooster release : false
,D/TimaKeyStoreProvider( 3501): TimaSignature is unavailable
,D/ActivityThread( 3501): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 23.673ms
,D/NPS_WSSNPS( 3390): [50.150621] dsServerSocket close
,I/ActivityManager( 1014): Killing 2284:com.android.mms/u0a46 (adj 15): empty #31
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 19.256ms
,E/SMD     (  292): DCD OFF
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1014): failed to open /acct/uid_10099/pid_2749/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2771/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10098/pid_2141/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2314/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_2785/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/Hs20UtilService( 3488): onCreate
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/CameraApp( 3501): CameraApp.onCreate()... mFeature : null
,I/Hs20UtilService( 3488): Starting #1
,I/Hs20UtilService( 3488): Message received 5003
,I/testFeature( 3501): Feature.Feature(context)
I/testFeature( 3501): Feature.readInternalDefaultXml()
I/testFeature( 3501): ResetFeatureValue
E/Zygote  ( 3534): MountEmulatedStorage()
E/Zygote  ( 3534): v2
I/libpersona( 3534): KNOX_SDCARD checking this for 10019
I/libpersona( 3534): KNOX_SDCARD not a persona
I/SELinux ( 3534): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/CameraFirmware_broadcast( 3501): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3501): CameraApp.getAppFeature()...
,I/ActivityManager( 1014): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3534 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3534): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/SELinux ( 3534): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3549): MountEmulatedStorage()
E/Zygote  ( 3549): v2
I/libpersona( 3549): KNOX_SDCARD checking this for 10100
I/libpersona( 3549): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 3534): TimaSignature is unavailable
I/SELinux ( 3549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityThread( 3534): Added TimaKeyStore provider
,I/SELinux ( 3549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3549 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/RlzPingService( 3134): Setting next ping for 1458032614485
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3549): TimaSignature is unavailable
,D/ActivityThread( 3549): Added TimaKeyStore provider
,E/Zygote  ( 3565): MountEmulatedStorage()
E/Zygote  ( 3565): v2
I/libpersona( 3565): KNOX_SDCARD checking this for 1000
I/libpersona( 3565): KNOX_SDCARD not a persona
,I/SELinux ( 3565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3565): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3565 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2837:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,D/CountryDetector( 1014): No listener is left
,I/KLMS-2.5.183: ( 3534): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 08 10:03:34 GMT+01:00 2016
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/TimaKeyStoreProvider( 3565): TimaSignature is unavailable
,D/ActivityThread( 3565): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3534): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3534): KLMSIntentService(): onCreate()
,E/Zygote  ( 3583): MountEmulatedStorage()
E/Zygote  ( 3583): v2
I/libpersona( 3583): KNOX_SDCARD checking this for 10022
I/libpersona( 3583): KNOX_SDCARD not a persona
,I/SELinux ( 3583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3583 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_2284/cgroup.procs: No such file or directory
I/SELinux ( 3583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_1101/pid_2837/cgroup.procs: No such file or directory
,I/KLMS-2.5.183: ( 3534): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3534): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/PackageIntentReceiver( 3549): ACTION_BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3583): TimaSignature is unavailable
,D/ActivityThread( 3583): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3534): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/PackageIntentReceiver( 3549): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,I/KLMS-2.5.183: ( 3534): KLMSIntentService(): BOOT_COMPLETED
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3602): MountEmulatedStorage(),
,E/Zygote  ( 3602): v2
I/libpersona( 3602): KNOX_SDCARD checking this for 10101
I/libpersona( 3602): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3602 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Killing 2818:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/SELinux ( 3602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/SettingsProvider( 1014): name = access_control_enabled
E/SELinux ( 3602): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3534): KLMSIntentService(): onDestroy()
,E/Zygote  ( 3614): MountEmulatedStorage()
I/libpersona( 3614): KNOX_SDCARD checking this for 10069
E/Zygote  ( 3614): v2
I/libpersona( 3614): KNOX_SDCARD not a persona
I/SELinux ( 3614): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3614 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2854:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,I/SELinux ( 3614): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3614): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3602): TimaSignature is unavailable
,D/ActivityThread( 3602): Added TimaKeyStore provider
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1014): Killing 2893:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3614): TimaSignature is unavailable
,D/ActivityThread( 3614): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3634): MountEmulatedStorage()
,E/Zygote  ( 3634): v2
I/libpersona( 3634): KNOX_SDCARD checking this for 1000
I/libpersona( 3634): KNOX_SDCARD not a persona
,I/SELinux ( 3634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3634 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2929:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3634): TimaSignature is unavailable
,D/ActivityThread( 3634): Added TimaKeyStore provider
,D/FileShare-Server( 3614): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2818/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to kill pid 2929: No such process
,E/MTPRx   ( 3634): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
W/libprocessgroup( 1014): failed to open /acct/uid_10048/pid_2854/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10157/pid_2893/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_2929/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 3634): sealedState: false
V/MTPRx   ( 3634): sealedUsbMassStorageState: false
,D/SettingsProvider( 1014): name = mtp_usb_connection_status
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3248): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/SettingsProvider( 1014): name = media_player_mode
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = media_mount_count
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = mtp_sync_alive
,D/SettingsProvider( 1014): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/ActivityManager( 1014): Killing 2911:com.sec.dsm.system/1000 (adj 15): empty #31
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1014): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/PCWCLIENTTRACE_PushUtil( 3302): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3302): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3302): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3302): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3302): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3302): ACTION_BOOTUP - Push type: [SPP, GCM]
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3660): MountEmulatedStorage()
,E/Zygote  ( 3660): v2
I/libpersona( 3660): KNOX_SDCARD checking this for 1000
I/libpersona( 3660): KNOX_SDCARD not a persona
,I/SELinux ( 3660): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3660): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3660): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3660 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3660): TimaSignature is unavailable
,D/ActivityThread( 3660): Added TimaKeyStore provider
,W/PCWCLIENTTRACE_PCWHandler( 3302): [ensureRegistration] - netwrok is not available. action ignored
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3676): MountEmulatedStorage(),
,E/Zygote  ( 3676): v2
,I/libpersona( 3676): KNOX_SDCARD checking this for 10031,
I/libpersona( 3676): KNOX_SDCARD not a persona,
I/ActivityManager( 1014): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3676 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2955:com.sec.usbsettings/1000 (adj 15): empty #31
,I/SELinux ( 3676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3676): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 3676): TimaSignature is unavailable
,D/ActivityThread( 3676): Added TimaKeyStore provider
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 24291(1336KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 26MB/39MB, paused 2.849ms total 155.916ms
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2911/cgroup.procs: No such file or directory
,W/ResourcesManager( 3676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3693): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 3693): v2
I/libpersona( 3693): KNOX_SDCARD checking this for 1000
I/SELinux ( 3693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3693): KNOX_SDCARD not a persona
I/SELinux ( 3693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3693): TimaSignature is unavailable
,D/ActivityThread( 3693): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2955/cgroup.procs: No such file or directory
,W/ResourcesManager( 3693): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3248): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
W/ContextImpl( 3248): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3248): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3602): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaService( 1014): TIMA: in getTimaVersion
,D/TimaService( 1014): TIMA3: KeyStore3_init
,D/TimaService( 1014): TIMA: in getTimaVersion
E/TLC_TZ_KEYSTORE: ( 1014): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 1014): creating new keystore context...
,I/TLC_TZ_KEYSTORE: ( 1014): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1014): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1014): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1014): process = tima_key, process_strlen = 8
,I/TZ: qc_tlc_communication( 1014): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1014): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1014): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x880
,D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 8
,I/VlingoApplication( 3676): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1014): ctx = 0xb920dc18, comm = 0xb91671f0, sendmsg = 0xacab6000, recvmsg = 0xacab6440
I/TZ_init: ( 1014): TZ_init: sending initialization request...
,E/TZ_init: ( 1014): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1014): trustlet initialization failed
I/TZ_init: ( 1014): TZ_init_START...
,I/TZ_init: ( 1014): TZ_init_with_data: sending initialization request...
,W/GAV2    ( 3602): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/TZ_init: ( 1014): TZ_init: successful initialization
D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1014): Count : 1, Ret : 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/BluetoothAdapter( 3676): 16413311: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3676): 16413311: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3676): 16413311: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3676): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/ActivityManager( 1014): Killing 2966:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 3602): Error finding the version of the Email provider.....
E/Gmail   ( 3602): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3602): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3602): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3602): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3602): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3602): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3602): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/Gmail   ( 3602): getAccountsCursor
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2966/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ContextImpl( 3693): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/VlingoApplication( 3676): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3676): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/DialogFlow( 3676): initQueue()
,I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3764 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/GoogleHttpClient( 1653): GMS http client unavailable, use old client
I/Gmail   ( 3602): Observing account changes for notifications
,E/Zygote  ( 3764): MountEmulatedStorage(),
I/libpersona( 3764): KNOX_SDCARD checking this for 10104
E/Zygote  ( 3764): v2
I/libpersona( 3764): KNOX_SDCARD not a persona
,I/SELinux ( 3764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ContextImpl( 1960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,E/SELinux ( 3764): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3660): Resource data:2131165186
,W/ResourcesManager( 3660): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,I/AMMetaDataParserService( 3660): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
I/art     (  317): Explicit concurrent mark sweep GC freed 8762(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 34.021ms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3764): TimaSignature is unavailable
D/ActivityThread( 3764): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 20.297ms
,I/AMMetaDataParserService( 3660): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 16.771ms
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaD,ataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,I/ActivityManager( 1014): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3781 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3781): MountEmulatedStorage()
,D/ActivityManager( 1014): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,E/Zygote  ( 3781): v2
I/libpersona( 3781): KNOX_SDCARD checking this for 1000
I/libpersona( 3781): KNOX_SDCARD not a persona
,I/SELinux ( 3781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/SEAMService( 1014):  hashset_to_int_array returning null
,I/SELinux ( 3781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecUISvc( 1960): Thread created.
D/SecUISvc( 1960): Service started flags 0 startId 1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131034113
W/SEAMService( 1014):  hashset_to_int_array returning null
,E/SQLiteLog( 3693): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3693): (284) automatic index on seams_container_info(sp_id)
,E/Zygote  ( 3799): MountEmulatedStorage(),
D/TimaKeyStoreProvider( 3781): TimaSignature is unavailable
I/ActivityManager( 1014): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3799 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityThread( 3781): Added TimaKeyStore provider
E/Zygote  ( 3799): v2
I/libpersona( 3799): KNOX_SDCARD checking this for 10028
,I/libpersona( 3799): KNOX_SDCARD not a persona
W/ResourcesManager( 3660): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3660): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,I/SELinux ( 3799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/SEAMService( 1014):  hashset_to_int_array returning null
,I/SELinux ( 3799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,E/SELinux ( 3799): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3781): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,I/GFX construct_block_size_descriptor_2d second part( 3660): took 2.381093ms for 0*0 texture 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/GFX generate_partition_tables( 3660): took 6.302135ms for 0*0 texture 0
,I/GFX raster( 3660): took 9.963958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb96d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8eb9698 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3660): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/SQLiteLog( 3602): (283) recovered 125 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/TimaKeyStoreProvider( 3799): TimaSignature is unavailable
,D/ActivityThread( 3799): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3764): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 3816): MountEmulatedStorage()
,E/Zygote  ( 3816): v2
,I/libpersona( 3816): KNOX_SDCARD checking this for 10032
I/libpersona( 3816): KNOX_SDCARD not a persona,
I/SELinux ( 3816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,I/SELinux ( 3816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3816): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3816 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3017:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3660): took 0.831875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb96d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8eb9698 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 3816): TimaSignature is unavailable
D/ActivityThread( 3816): Added TimaKeyStore provider
,E/ActivityThread( 3602): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@ac47281 that was originally bound here
E/ActivityThread( 3602): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@ac47281 that was originally bound here
E/ActivityThread( 3602): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3602): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3602): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3602): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3602): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3602): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3602): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3602): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3602): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3602): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3602): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3602): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3602): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3602): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 1014): Killing 3039:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@23d24a37
,I/ActivityManager( 1014): Killing 3059:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 2877:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #32
,I/AMMetaDataParserService( 3660): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/F_PHONE ( 3781): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3781): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1014): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/F_PHONE ( 3781): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3781): default registerAction()
I/F_PHONE ( 3781): [[com.sec.bcservice]] sendPendingMessage()
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3660): took 2.468802ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3660): took 7.492240ms for 0*0 texture 0
,I/GFX raster( 3660): took 10.883438ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebe188 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_3017/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3039/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_2877/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3059/cgroup.procs: No such file or directory
,D/FactoryTestApp( 2648): [DummyFtClient$onDestroy](2648) Destroy DummyFtClient service
,D/FactoryTestApp( 2648): [Support$Values.getString](2648) id=MODEL_COMMUNICATION_MODE, value=gsm,
,I/FactoryTestApp( 2648): [ModuleCommon$isConnectionModeNone](2648) mConnectionMode = gsm
,I/FactoryTestApp( 2648): [ModuleCommon$isRunningFtClient](2648) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2648): [DummyFtClient$onDestroy](2648) kill process
,I/Process ( 2648): Sending signal. PID: 2648 SIG: 9
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3836 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1014): Process com.sec.factory (pid 2648)(adj 0) has died(176,1065)
,E/Zygote  ( 3836): MountEmulatedStorage()
E/Zygote  ( 3836): v2
I/libpersona( 3836): KNOX_SDCARD checking this for 10033
I/libpersona( 3836): KNOX_SDCARD not a persona
,I/SELinux ( 3836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3836): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3836): TimaSignature is unavailable
,D/ActivityThread( 3836): Added TimaKeyStore provider
,E/File    ( 3602): fail readDirectory() errno=2
,I/Gmail   ( 3602): notifyAccountChanged
,I/Gmail   ( 3602): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 3602): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3602): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3602): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3602): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.607657ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ec2d30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec2e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.818646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ebf738 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf890 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/Gmail   ( 3602): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3799): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.649791ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebe218 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3836): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3836): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3836): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.771198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ebe218 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec0400 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3836): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3836): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3836): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.526406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ebdde8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebe6f8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3836): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3836): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3836): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131034113
,I/AMMetaDataParserService( 3660): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.806094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb96d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/Babel   ( 3764): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3764): MmsConfig.loadMmsSettings
I/Babel   ( 3764): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3764): MmsConfig.loadFromDatabase
,E/Babel   ( 3764): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3764): MmsConfig.loadFromResources
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.809271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb96d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Babel   ( 3764): canonicalizeMccMnc: invalid mccmnc nullnull
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 3764): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 3764): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Finsky  ( 3799): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.606822ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e80920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Babel_StickerModule( 3764): App launched.
,I/Babel_StickerModule( 3764): Sticker update initiated. last:1456825783062 empty:false
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 3799): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.596771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dfd360 counterpartCT=4 counterpartW=96 counterparth=96
,W/Settings( 3799): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/AMMetaDataParserService( 3660): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/art     ( 3764): Suspending all threads took: 13.352ms
,V/Babel   ( 3764): babel boot account: SMS
,I/System.out( 3676): INFO:Resource not found:/Common.properties Using default values
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.960522ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/Babel   ( 3764): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3764): java.lang.Exception
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3764): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3764): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3764): 	at ckh.a(SourceFile:67)
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3764): 	at bhn.a(SourceFile:301)
W/Babel   ( 3764): 	at bhn.a(SourceFile:137)
W/Babel   ( 3764): 	at bhn.a(SourceFile:126)
W/Babel   ( 3764): 	at bhn.a(SourceFile:159)
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3764): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3764): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3764): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3764): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3764): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3764): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3764): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3764): java.lang.Exception
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3764): 	at aes.a(SourceFile:145)
W/Babel   ( 3764): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3764): 	at ckh.a(SourceFile:67)
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3764): 	at bhn.a(SourceFile:301)
W/Babel   ( 3764): 	at bhn.a(SourceFile:137)
W/Babel   ( 3764): 	at bhn.a(SourceFile:126)
W/Babel   ( 3764): 	at bhn.a(SourceFile:159)
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3764): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3764): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3764): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3764): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3764): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3764): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/AMMetaDataParserService( 3660): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/Volley  ( 3799): [571] DiskBasedCache.clear: Cache cleared.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Volley  ( 3799): [578] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3799): Skipping gmscore version check
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.626980ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea1640 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.683594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8dfd360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.532187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ebdde8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3660): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3660): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131034112
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 25476(1664KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.306ms total 189.072ms
D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3660): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.604739ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GFX raster( 3660): took 0.649844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf3a0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Process ( 3836): Sending signal. PID: 3836 SIG: 9
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/SMD     (  292): DCD OFF
D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
V/Babel   ( 3764): babel boot account: thalitester@gmail.com
,I/AMMetaDataParserService( 3660): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/Finsky  ( 3799): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3799): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Babel   ( 3764): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3764): java.lang.Exception
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3764): 	at aes.a(SourceFile:145)
W/Babel   ( 3764): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3764): 	at ckh.a(SourceFile:67)
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3764): 	at bhn.a(SourceFile:301)
W/Babel   ( 3764): 	at bhn.a(SourceFile:137)
W/Babel   ( 3764): 	at bhn.a(SourceFile:126)
W/Babel   ( 3764): 	at bhn.a(SourceFile:159)
W/Babel   ( 3764): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3764): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3764): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3764): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3764): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3764): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3764): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3764): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 1014): Process com.sec.android.app.sns3 (pid 3836)(adj 0) has died(144,1087)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 2023): Spent 36ms computing apk sha1.
D/FileApkUtils( 2023): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2023): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/Zygote  ( 3901): MountEmulatedStorage()
E/Zygote  ( 3901): v2
I/libpersona( 3901): KNOX_SDCARD checking this for 10034
I/libpersona( 3901): KNOX_SDCARD not a persona
,I/SELinux ( 3901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3901): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3901 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,D/DexOptUtils( 2023): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 2023): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 2023): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2023): Primary ABI of odexing process is armeabi-v7a
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.770939ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ebf3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3799): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/AMMetaDataParserService( 3660): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/TimaKeyStoreProvider( 3901): TimaSignature is unavailable
,D/ActivityThread( 3901): Added TimaKeyStore provider
,E/Zygote  ( 3919): MountEmulatedStorage()
E/Zygote  ( 3919): v2
I/libpersona( 3919): KNOX_SDCARD checking this for 1000
I/libpersona( 3919): KNOX_SDCARD not a persona
,I/SELinux ( 3919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 3816): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/GFX raster( 3660): took 0.640781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea1640 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 3919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3919): TimaSignature is unavailable
,D/ActivityThread( 3919): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131034113
,I/AMMetaDataParserService( 3660): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.828750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb96d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 3799): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  286): getCameraInfo: X
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  286): getCameraInfo: X
,W/ResourcesManager( 3816): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3816): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3816): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/dex2oat ( 3916): ----------------------------------------------------
I/dex2oat ( 3916): <SS>: S T A R T I N G . . .
I/dex2oat ( 3916): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3916): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=41 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/AMMetaDataParserService( 3660): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/ActivityManager( 1014): Killing 3107:com.policydm/1000 (adj 15): empty #31
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.834375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb96d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3764): Unrecognized profile 2130706433 for video/avc
,I/AMMetaDataParserService( 3660): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/AudioCapabilities( 3764): Unsupported mime audio/evrc
,W/AudioCapabilities( 3764): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3764): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3764): Unsupported mime audio/mpeg-L2
,W/InstanceID/Rpc( 2023): Found 10012
,W/AudioCapabilities( 3764): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3764): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3764): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3764): Unsupported mime audio/evrc
,W/VideoCapabilities( 3764): Unsupported mime video/wvc1
,W/VideoCapabilities( 3764): Unsupported mime video/x-ms-wmv
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3107/cgroup.procs: No such file or directory
,W/VideoCapabilities( 3764): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3764): Unsupported mime video/wvc1
,W/VideoCapabilities( 3764): Unsupported mime video/x-ms-wmv
,I/System.out( 3799): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 3799): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3799): (HTTPLog)-Static: isShipBuild true
I/System.out( 3799): (HTTPLog)-Thread-583-944808777: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3799): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,W/VideoCapabilities( 3764): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3764): Unsupported mime video/x-ms-wmv8
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/VideoCapabilities( 3764): Unsupported mime video/mp43
,W/VideoCapabilities( 3764): Unsupported mime video/sorenson
,I/GFX raster( 3660): took 0.686406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e80920 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3764): Unsupported mime video/mp4v-esdp
,I/AMMetaDataParserService( 3660): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.738125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530,
,I/ActivityManager( 1014): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3943 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3090:com.google.android.configupdater/u0a86 (adj 15): empty #31
,E/Zygote  ( 3943): MountEmulatedStorage()
E/Zygote  ( 3943): v2
I/libpersona( 3943): KNOX_SDCARD checking this for 1000
I/libpersona( 3943): KNOX_SDCARD not a persona
,I/SELinux ( 3943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
E/SELinux ( 3943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3956): MountEmulatedStorage(),
E/Zygote  ( 3956): v2
I/libpersona( 3956): KNOX_SDCARD checking this for 1000
,I/libpersona( 3956): KNOX_SDCARD not a persona
,I/SELinux ( 3956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3956 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/VideoCapabilities( 3764): Unsupported profile 4 for video/mp4v-es,
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.959062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3943): TimaSignature is unavailable
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 3943): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3956): TimaSignature is unavailable
,D/ActivityThread( 3956): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10086/pid_3090/cgroup.procs: No such file or directory
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.815313ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea1640 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/KnoxSetupWizardDbHelper( 3956): dbMigrationFlag : false
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.871406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8dfd360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e84d50 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 2023): COMPAT: Multi user not supported
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ShortcutReceiver( 3956):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,D/GCM     ( 1802): COMPAT: Multi user not supported
,I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 3764): Creating RTCS
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/KnoxShortcutUtil( 3956): getIsShortcutMigrationFor_2_3_0_Done true,
I/CheckinService( 2023): Checkin interval check for package: unspecified last checkin: 1456600236354 min interval config: 0 actual interval: 827581708
,D/ShortcutReceiver( 3956):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 3956):  shortcut migration not required 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.658438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ebdde8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3943): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/AMMetaDataParserService( 3660): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/DBG_POLICYDM( 3943): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3943): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
E/Zygote  ( 3993): MountEmulatedStorage()
I/libpersona( 3993): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3993): v2
I/libpersona( 3993): KNOX_SDCARD not a persona
,I/SELinux ( 3993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3993 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3164:com.dropbox.android/u0a92 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3943): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3993): TimaSignature is unavailable
,D/ActivityThread( 3993): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/DBG_POLICYDM( 3943): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660,): Resource data:2131165203
,W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3164/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/ResourcesManager( 3660): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/KnoxSetupWizardClient( 3993): isShipMode : 1
,I/KnoxSetupWizardClient( 3993): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3660): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3660): took 2.619584ms for 0*0 texture 0,
,I/GFX generate_partition_tables( 3660): took 10.191667ms for 0*0 texture 0
,I/GFX raster( 3660): took 13.615000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb9071ac8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9071b70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4012 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/GFX raster( 3660): took 0.757604ms for 96*96 texture 0,
D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1176 (0x0)
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e906c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e90768 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1014): Killing 3074:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31,
,I/AMMetaDataParserService( 3660): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
I/DBG_POLICYDM( 3943): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3943): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false],
E/Zygote  ( 4012): MountEmulatedStorage()
I/libpersona( 4012): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4012): v2
I/libpersona( 4012): KNOX_SDCARD not a persona
,I/SELinux ( 4012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/SELinux ( 4012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4012): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 2023): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.769688ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e906c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e96c40 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/AMMetaDataParserService( 3660): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 4012): TimaSignature is unavailable
,D/ActivityThread( 4012): Added TimaKeyStore provider
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.952969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e906c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9071660 counterpartCT=4 counterpartW=96 counterparth=96
,W/System.err( 3993): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 3993): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3993): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3993): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 3993): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 3993): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3993): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast,
I/AMMetaDataParserService( 3660): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/art     ( 2023): WaitForGcToComplete blocked for 43.588ms for cause DisableMovingGc
I/art     ( 2023): WaitForGcToComplete blocked for 8.391ms for cause DisableMovingGc
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4027): MountEmulatedStorage(),
E/Zygote  ( 4027): v2
I/libpersona( 4027): KNOX_SDCARD checking this for 10035,
I/libpersona( 4027): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4027 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 3209:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/SELinux ( 4027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4027): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,E/SQLiteLog( 3764): (284) automatic index on conversation_participants_view(conversation_id)
,D/TimaKeyStoreProvider( 4027): TimaSignature is unavailable,
D/ActivityThread( 4027): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 8755(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.286ms total 55.452ms
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3660): took 0.810781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb9071660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8eb40a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.276ms total 25.381ms,
,I/AMMetaDataParserService( 3660): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/CheckinService( 2023): Disabling old GoogleServicesFramework version
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 887us total 34.343ms
,E/libprocessgroup( 1014): failed to kill 1 processes for processgroup 3074
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ChimeraCfgMgr( 2023): Reading stored module config
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.612500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb9071660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8dfd360 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4027): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4027): [PushClientApplication] Push log off : This is Ship build version
,I/AMMetaDataParserService( 3660): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/SPPClientService( 4027): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/DBG_POLICYDM( 3943): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3943): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/SPPClientService( 4027): PushLog.txt file is not deleted.
D/SPPClientService( 4027): PushLog.txt file is not deleted.
D/SPPClientService( 4027): ============PushLog. stop!
,D/BootCompletedReceiver( 2023): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
E/DBG_POLICYDM( 3943): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
D/BootCompletedReceiver( 2023): Got an BootCompleted event.
,W/ResourcesManager( 3764): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3764): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BootCompletedReceiver( 2023): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 2023): onCreate
,E/SQLiteLog( 3764): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,D/SystemUpdateService( 2023): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 2023): Checking schedule, now: 1457427818833 next: 1457139499243
I/CheckinService( 2023): active receiver: enabled
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,W/ResourcesManager( 3660): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,V/AuthZen ( 2023): Handling intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/SQLiteLog( 3764): (284) automatic index on conversation_participants_view(conversation_id)
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3660): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3660): took 0.681667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb93d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ea9fb8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,E/Zygote  ( 4052): MountEmulatedStorage(),
E/Zygote  ( 4052): v2
,I/libpersona( 4052): KNOX_SDCARD checking this for 10041
I/libpersona( 4052): KNOX_SDCARD not a persona,
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4052 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Killing 3233:com.fmm.dm/1000 (adj 15): empty #31
,I/SELinux ( 4052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4052): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0,
,D/AuthZenEventHandler( 2023): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3660): took 2.451511ms for 0*0 texture 0
,V/JNIHelp ( 3764): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GFX generate_partition_tables( 3660): took 8.789895ms for 0*0 texture 0
,I/GFX raster( 3660): took 12.226562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea7050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8ea7088 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SQLiteLog( 3764): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.642604ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea7088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb93b9340 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4052): TimaSignature is unavailable
,D/ActivityThread( 4052): Added TimaKeyStore provider
,E/SQLiteLog( 3764): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.806823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93ba6a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb93ba6d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.746510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bb810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb93bbaa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.841823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bcb08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SystemUpdateService( 2023): cancelUpdate (empty URL)
I/SystemUpdateService( 2023): active receiver: disabled
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,I/AMMetaDataParserService( 3660): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,I/AMMetaDataParserService( 3660): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.704011ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb93d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityThread( 3764): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3764): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37787273: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3764): Installed default security provider GmsCore_OpenSSL
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 3764): Destroying RTCS
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/BaseAppContext( 2023): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_3209/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3233/cgroup.procs: No such file or directory
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/SA      ( 4052): [SSP] onCreated
,I/GFX raster( 3660): took 3.144479ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea7050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.642916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea7088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1802): DispatchingService.onCreate()
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,I/art     ( 1653): Explicit concurrent mark sweep GC freed 5569(226KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 780us total 30.340ms
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/GCM     ( 1802): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 2023): onDestroy
,W/SQLiteConnectionPool( 1653): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/SA      ( 4052): [TPM] There is no property file
,I/SA      ( 4052): [SCU] isHaveSA() - false
,I/AuthZen ( 2023): Fetching signing key...
,I/SA      ( 4052): [TPM] getModelProperty : null
I/SA      ( 4052): [TPM] getCSCProperty : null
,I/SA      ( 4052): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4052): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4052): [DM] TFT FEATURE: false
,I/SA      ( 4052): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4052): [DM] init START
,I/SA      ( 4052): [DM] This device is not a Vodafone
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.636458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93ba6a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourceType( 4052): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,I/AMMetaDataParserService( 3660): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ResourceType( 4052): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4052): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4052): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4052): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4052): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4052): [SCU] isHaveSA() - false
,I/SA      ( 4052): support phone number id : false
I/SA      ( 4052): [DM] Supports Ref Jpn : true
,I/SA      ( 4052): [DM] init END
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.626354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bb810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4052): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4052): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1014): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4052): [OR] onReceive END
,I/AuthZen ( 2023): Signing key fetched successfully!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,I/ActivityManager( 1014): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4102 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4102): MountEmulatedStorage()
I/libpersona( 4102): KNOX_SDCARD checking this for 10042
E/Zygote  ( 4102): v2
I/libpersona( 4102): KNOX_SDCARD not a persona
,I/SELinux ( 4102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 ,
E/SELinux ( 4102): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3660): took 0.734166ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bcb08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96,
,I/AMMetaDataParserService( 3660): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/SA      ( 4052): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,I/SA      ( 4052): [ODM] queryOpenData(key= GEO_IP )
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3660): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.682761ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb93d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,D/a       ( 2023): Opening database auth.proximity.permit_store...
,D/TimaKeyStoreProvider( 4102): TimaSignature is unavailable
,D/ActivityThread( 4102): Added TimaKeyStore provider
,D/SSRM:n  ( 1014): SIOP:: AP = 400
,I/SA      ( 4052): getMccForGalaxyJpn step2 GEO_IP MCC : 260
,I/SA      ( 4052): [LBE] REF_JPN : true
I/SA      ( 4052): [BDC] create
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/AuthZenTransactionCache( 2023): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2023): Clearing transaction cache
,W/ResourcesManager( 4102): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4052): [DBMV2] getEmailID
,I/SA      ( 4052): [DBMV2] getDataV02ForItems
I/SA      ( 4052): [SSP] query invoked
,I/SA      ( 4052): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4052): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4052): [BDC] destroy
,I/ActivityManager( 1014): Killing 3265:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/art     ( 1802): Explicit concurrent mark sweep GC freed 24763(1783KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 12MB/20MB, paused 1.230ms total 114.693ms
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GCoreUlr( 1802): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/StrictMode( 4012): StrictMode policy violation; ~duration=1055 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4012): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4012): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4012): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4012): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4012): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4012): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=986 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4012): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4012): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4012): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4012): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4012): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012):, 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=807 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4012): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4012): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4012): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4012): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4012): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4012): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=806 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4012): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4012): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4012): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4012): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrum,entation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=806 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4012): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4012): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4012): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4012): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=804 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4012): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4012): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4012): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4012): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4012): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4012): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4012): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4012): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4012): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4012): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4012): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4012): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=801 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4012): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4012): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4012): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4012): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4012): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4012): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4012): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4012): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4012): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4012): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4012): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4012): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4012): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=764 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4012): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4012): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4012): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4012): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4012): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4012): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4012): StrictMode policy violation; ~duration=764 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4012): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4012): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4012): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4012): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4012): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4012): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4012): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4012): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4012): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4012): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4012): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4012): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4012): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4012): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4012): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SecDataIO(  257): Write to block
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3660): took 0.818489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea7050 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8ec3638 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4119): MountEmulatedStorage()
E/Zygote  ( 4119): v2
I/libpersona( 4119): KNOX_SDCARD checking this for 1000
I/AMMetaDataParserService( 3660): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
I/libpersona( 4119): KNOX_SDCARD not a persona
I/SELinux ( 4119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3285:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/SELinux ( 4119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 2629): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.648229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea7088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3007): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3007): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3007): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4119): TimaSignature is unavailable
,D/ActivityThread( 4119): Added TimaKeyStore provider
,W/GCoreFlp( 1802): No location to return for getLastLocation()
W/FusedLocationProvider( 1802): location=null
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/ActivityManager( 1014): Killing 3319:com.fmm.ds/1000 (adj 15): empty #31
,W/Auth    ( 1802): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/Process ( 2629): Sending signal. PID: 2629 SIG: 9
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3660): took 0.752343ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93ba6a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ec3638 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3660): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/GCoreFlp( 1802): No location to return for getLastLocation()
,W/FusedLocationProvider( 1802): location=null
,I/CalendarProvider2( 4102): CalendarProvider2.onCreate() called
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1014): Process com.sec.android.app.sysscope (pid 2629)(adj 0) has died(116,1106)
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.623958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bb810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071930 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusChecker( 4119): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SQLiteLog( 2023): (10) POSIX Error : 11 SQLite Error : 3850
,I/StatusChecker( 4119): onReceive : net.mt.init : DONE
,W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3265/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10060/pid_3285/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4144): MountEmulatedStorage()
E/Zygote  ( 4144): v2
I/libpersona( 4144): KNOX_SDCARD checking this for 10116
I/libpersona( 4144): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4144 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/SELinux ( 4144): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4144): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4144): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3319/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4144): TimaSignature is unavailable
,D/ActivityThread( 4144): Added TimaKeyStore provider
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.737917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bcb08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec3638 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1014): Killing 3348:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/AMMetaDataParserService( 3660): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,W/com.google.a.a.b.d.a( 4012): Application name is not set. Call Builder#setApplicationName.
,I/PageBuddyNotiSvc( 4144): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_3348/cgroup.procs: No such file or directory
,W/ContextImpl( 4144): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4144): onCreate mCpBitFlag=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3007): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/AMMetaDataParserService( 3660): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/Zygote  ( 4161): MountEmulatedStorage()
I/libpersona( 4161): KNOX_SDCARD checking this for 10125
E/Zygote  ( 4161): v2
I/libpersona( 4161): KNOX_SDCARD not a persona
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 4161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
I/GFX raster( 3660): took 0.710417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea74d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec2e58 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4161 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 4161): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/DBG_DM  ( 3007): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 3007): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4161): TimaSignature is unavailable
,D/ActivityThread( 4161): Added TimaKeyStore provider
,I/GCoreUlr( 1802): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PersistentNotificationBroadcastReceiver( 1802): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,E/SMD     (  292): DCD OFF
,W/ResourcesManager( 4161): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4161): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4161): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1802): Unbound from all location providers
I/GCoreUlr( 1802): Place inference reporting - stopped
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.636094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea0710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SensorService( 1014): [SO] 0.115 0.402 10.132
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.637292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bcb08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9071490 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/GCoreUlr( 1802): DispatchingService.onDestroy()
I/GCoreUlr( 1802): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1802): Unbound from all location providers
,I/GCoreUlr( 1802): Place inference reporting - stopped
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.639688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e86d68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/QuickConnect( 4161): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4161): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1014): name = scon_is_running
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10125
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,I/AMMetaDataParserService( 3660): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GFX raster( 3660): took 0.660208ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e96d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071490 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3602): Thread[GAThread,5,main]: No campaign data found.
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 33012(1926KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 26MB/39MB, paused 2.731ms total 177.562ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/QuickConnect( 4161): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/QuickConnect( 4161): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4185): MountEmulatedStorage(),
E/Zygote  ( 4185): v2
I/libpersona( 4185): KNOX_SDCARD checking this for 10131
I/libpersona( 4185): KNOX_SDCARD not a persona,
I/SELinux ( 4185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4185 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 3367:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,E/SELinux ( 4185): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4185): TimaSignature is unavailable
,D/ActivityThread( 4185): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 3189:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 1.004740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ResourcesManager( 4185): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4185): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4185): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4185): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3660): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/GFX raster( 3660): took 0.832760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea74d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.640781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea0710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3367/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_3189/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3660): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SBrowserFeatureFlag( 4185): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.669792ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bcb08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,D/ManifestProvider( 4185): onCreate()
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.639115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e86d68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/NetworkSettingsReceiver( 4185): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3660): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.650104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e96d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071660 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/SBrowserFeatureFlag( 4185): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@356865c6
,D/SBrowserFeatureFlag( 4185): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4185): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4205 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 4205): KNOX_SDCARD checking this for 10135
I/GFX raster( 3660): took 0.721875ms for 96*96 texture 0
I/libpersona( 4205): KNOX_SDCARD not a persona
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 4205): MountEmulatedStorage()
E/Zygote  ( 4205): v2
I/SELinux ( 4205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4205): TimaSignature is unavailable
D/ActivityThread( 4205): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
V/AlarmManager( 1014): waitForAlarm result :4
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,I/AMMetaDataParserService( 3660): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,W/ResourcesManager( 4205): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourcesManager( 4205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4205): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GFX raster( 3660): took 0.852813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea74d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071660 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.641927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8ea0710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9071490 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/iu.UploadsManager( 2023): End new media; added: 0, uploading: 0, time: 52 ms
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 1.765989ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb93bcb08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8ec1920 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/dex2oat ( 3916): dex2oat took 3.347s (threads: 4)
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/DexOptUtils( 2023): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
D/DexOptUtils( 2023): Set odex to world readable.
,D/DexOptUtils( 2023): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
,D/FileApkUtils( 2023): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.728959ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e86d68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ec1498 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/GmsModuleFndr( 2023): Beginning GMS chimera module scan
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.732916ms for 96*96 texture 0
D/GmsModuleFndr( 2023): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8e96d50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec12d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ChimeraCfgMgr( 2023): Beginning module configuration check
,D/ChimeraCfgMgr( 2023): Module APKs unchanged, check complete
,I/ActivityManager( 1014): Killing 3390:com.wssnps/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4229): MountEmulatedStorage()
I/libpersona( 4229): KNOX_SDCARD checking this for 10139
E/Zygote  ( 4229): v2
I/libpersona( 4229): KNOX_SDCARD not a persona
,I/SELinux ( 4229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4229 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.732500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb8eb9b58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9071490 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3390/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4229): TimaSignature is unavailable
,D/ActivityThread( 4229): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity,
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
W/ResourcesManager( 4229): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
,W/ResourcesManager( 4229): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
W/ResourcesManager( 4229): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
W/ResourcesManager( 4229): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
,W/ResourcesManager( 4229): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131165197
,W/ResourcesManager( 3660): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,I/AMMetaDataParserService( 3660): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1014): Killing 3413:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 3454:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/AMMetaDataParserService( 3660): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4246): MountEmulatedStorage(),
E/Zygote  ( 4246): v2
I/libpersona( 4246): KNOX_SDCARD checking this for 10145
I/libpersona( 4246): KNOX_SDCARD not a persona,
,I/AMMetaDataParserService( 3660): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/SELinux ( 4246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4246 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 4246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4246): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/TimaKeyStoreProvider( 4246): TimaSignature is unavailable
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131165197
,D/ActivityThread( 4246): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3660): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,I/AMMetaDataParserService( 3660): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3660): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ResourcesManager( 4246): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4246): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4246): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4246): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4246): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131165197
,I/AMMetaDataParserService( 3660): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,W/libprocessgroup( 1014): failed to open /acct/uid_10094/pid_3454/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10014/pid_3413/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3660): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3660): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3660): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3660): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.camera.Camera,
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131099648
,W/ResourcesManager( 3660): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3660): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3660): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,I/AMMetaDataParserService( 3660): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:assistant
I/AMMetaDataParserService( 3660): Resource data:2131165220
,W/ResourcesManager( 3660): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3660): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3660): getResourceTypeNamexml
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.688020ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb95bc758 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb95bc488 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3660): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3660): took 0.590625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3660): Bitmap=0xb95bc5a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb95cef98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3660): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Password
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AM,MetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settin,gs$DateTimeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity,
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DisplaySettings
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/ActivityManager( 1014): Killing 3501:com.sec.factory.camera/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SecuritySettings
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
,I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
,I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER,_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettin,gsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/libpersona( 4269): KNOX_SDCARD checking this for 10072
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/libpersona( 4269): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4269 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
D/ActivityManager( 1014): startService callerProcessName:com.android.email, calleePkgName: com.android.email
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1014): Killing 3433:com.samsung.android.sm/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3501/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3660): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3660): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3660): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/RCPManagerService( 1014): exchangeData() failure , invalid userId
E/Zygote  ( 4269): MountEmulatedStorage()
E/Zygote  ( 4269): v2
I/SELinux ( 4269): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4269): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4269): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1014): exchangeData() failure , invalid userId
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
I/CalendarProvider2( 4102): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
D/TimaKeyStoreProvider( 4269): TimaSignature is unavailable
D/ActivityThread( 4269): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 4269): onCreate
D/BadgeProvider( 4269): DatabaseHelper
E/Zygote  ( 4289): MountEmulatedStorage()
I/libpersona( 4289): KNOX_SDCARD checking this for 10146
E/Zygote  ( 4289): v2
I/libpersona( 4289): KNOX_SDCARD not a persona
I/SELinux ( 4289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4289 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 3549:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
I/ActivityManager( 1014): Killing 3134:com.google.android.partnersetup/u0a15 (adj 15): empty #32
,D/BadgeProvider( 4269): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/art     (  317): Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 699us total 22.517ms
,D/TimaKeyStoreProvider( 4289): TimaSignature is unavailable
,D/ActivityThread( 4289): Added TimaKeyStore provider
,D/Launcher.Model( 1472): reloadBadges entered.
D/BadgeProvider( 4269): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4269): sendNotify, [notify] : null
D/BadgeProvider( 4269): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4269): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4269): update, [UpdateCount] : 1
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.327ms
,W/ResourcesManager( 4289): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 18.797ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): getTasks: caller 10145 does not hold GET_TASKS; limiting output,
,I/Process ( 4246): Sending signal. PID: 4246 SIG: 9
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3433/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_3134/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_3549/cgroup.procs: No such file or directory
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4305): MountEmulatedStorage(),
,E/Zygote  ( 4305): v2
I/libpersona( 4305): KNOX_SDCARD checking this for 1000
,I/libpersona( 4305): KNOX_SDCARD not a persona
,I/SELinux ( 4305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4305 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/lowmemorykiller(  255): Error writing /proc/4246/oom_score_adj; errno=22
I/ActivityManager( 1014): Killing 3565:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31,
,I/ActivityManager( 1014): Process com.android.email (pid 4246)(adj 11) has died(110,1130)
,I/ActivityThread( 4289): Removing dead content provider:android.content.ContentProviderProxy@e8fb625
I/ActivityThread( 4289): Removing dead content provider:android.content.ContentProviderProxy@e8fb625
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4321): MountEmulatedStorage(),
E/Zygote  ( 4321): v2
I/libpersona( 4321): KNOX_SDCARD checking this for 10145
I/libpersona( 4321): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 4305): TimaSignature is unavailable
,I/ActivityManager( 1014): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4321 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityThread( 4305): Added TimaKeyStore provider
,E/SELinux ( 4321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4321): TimaSignature is unavailable
D/ActivityThread( 4321): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3565/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4321): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4321): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4321): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4321): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4337): MountEmulatedStorage()
,E/Zygote  ( 4337): v2
I/libpersona( 4337): KNOX_SDCARD checking this for 1000
I/libpersona( 4337): KNOX_SDCARD not a persona
,I/SELinux ( 4337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 3583:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,I/SELinux ( 4337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4337): TimaSignature is unavailable
,D/ActivityThread( 4337): Added TimaKeyStore provider
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 4337): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4337): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4337): StateMachine : Current State = 1
D/SecurityLogAgent( 4337): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 3614:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1802): callingUid 10012, callindPid: 1802
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2023): Restart initialization of location
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1802): [236] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1802): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4269): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/GCoreFlp( 1802): No location to return for getLastLocation()
,W/FusedLocationProvider( 1802): location=null
,D/BadgeProvider( 4269): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4269): sendNotify, [notify] : null
D/BadgeProvider( 4269): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4269): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4269): update, [UpdateCount] : 1
,D/Launcher.Model( 1472): reloadBadges entered.
,I/HomeSyncInstallReceiver( 1439): This pkg do not need BT addr. Do nothing
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4368): MountEmulatedStorage()
,E/Zygote  ( 4368): v2
I/libpersona( 4368): KNOX_SDCARD checking this for 1000
I/libpersona( 4368): KNOX_SDCARD not a persona
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
I/SELinux ( 4368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=4368 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 4368): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4368): TimaSignature is unavailable
,E/Zygote  ( 4383): MountEmulatedStorage(),
E/Zygote  ( 4383): v2
I/libpersona( 4383): KNOX_SDCARD checking this for 10044
I/libpersona( 4383): KNOX_SDCARD not a persona
D/ActivityThread( 4368): Added TimaKeyStore provider
I/SELinux ( 4383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=4383 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 4383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
E/SELinux ( 4383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 4397): MountEmulatedStorage()
,E/Zygote  ( 4397): v2
I/libpersona( 4397): KNOX_SDCARD checking this for 1000
I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=4397 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 4397): KNOX_SDCARD not a persona
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,I/SELinux ( 4397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 4397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 4409): MountEmulatedStorage()
E/Zygote  ( 4409): v2
I/libpersona( 4409): KNOX_SDCARD checking this for 10152,
I/libpersona( 4409): KNOX_SDCARD not a persona
I/SELinux ( 4409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/TimaKeyStoreProvider( 4383): TimaSignature is unavailable,
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4409 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 4409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityThread( 4383): Added TimaKeyStore provider
E/SELinux ( 4409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/TimaKeyStoreProvider( 4397): TimaSignature is unavailable
,D/ActivityThread( 4397): Added TimaKeyStore provider
,I/Process ( 4289): Sending signal. PID: 4289 SIG: 9
,D/TimaKeyStoreProvider( 4409): TimaSignature is unavailable
,D/ActivityThread( 4409): Added TimaKeyStore provider
,D/AASAservice-UpdateReceiver( 4368): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.example.hello, uid = -1
,I/AASAservice-TokenRule( 4368): parseToken()
W/System.err( 4368): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4368): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 4368): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 4368): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 4368): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 4368): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 4368): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4368): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4368): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4368): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4368): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4368): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4368): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4368): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4368): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4368): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 4368): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4368): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4368): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 4368): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 4368): 	... 14 more
E/AASAservice-TokenRule( 4368): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 4368): AASARuleUpdateResult() : Rule file is not exist.
,W/ResourcesManager( 4383): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4383): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4383): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4383): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4383): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4383): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4383): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
W/ResourcesManager( 4383): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4397): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4429): MountEmulatedStorage()
E/Zygote  ( 4429): v2
I/libpersona( 4429): KNOX_SDCARD checking this for 10015
I/libpersona( 4429): KNOX_SDCARD not a persona
,I/SELinux ( 4429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4429): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 4409): (284) automatic index on shooting_modes(title_id)
,D/TimaKeyStoreProvider( 4429): TimaSignature is unavailable
,D/ActivityThread( 4429): Added TimaKeyStore provider
,I/ActivityManager( 1014): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4429 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3634:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/ActivityManager( 1014): Process com.android.exchange (pid 4289)(adj 13) has died(97,1130)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4446): MountEmulatedStorage()
I/libpersona( 4446): KNOX_SDCARD checking this for 10156
E/Zygote  ( 4446): v2
I/libpersona( 4446): KNOX_SDCARD not a persona
I/SELinux ( 4446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4446 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 4446): TimaSignature is unavailable
,D/ActivityThread( 4446): Added TimaKeyStore provider
,W/ContextImpl( 3660): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,I/PCWCLIENTTRACE_PushUtil( 3302): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3302): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3302): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3302): [onReceive] - android.intent.action.PACKAGE_ADDED
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4446): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4446): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_3614/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10022/pid_3583/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3634/cgroup.procs: No such file or directory
,I/TapandpayWidget:Utils( 4446): Clear T&P info.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4469): MountEmulatedStorage()
I/libpersona( 4469): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4469): v2
I/libpersona( 4469): KNOX_SDCARD not a persona
I/SELinux ( 4469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TapandpayWidget:TapandpayAppWidgetProvider( 4446): Widget is not attached.
,E/SELinux ( 4469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4469 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4469): TimaSignature is unavailable
,D/ActivityThread( 4469): Added TimaKeyStore provider,
,E/Zygote  ( 4484): MountEmulatedStorage()
I/libpersona( 4484): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4484): v2
I/libpersona( 4484): KNOX_SDCARD not a persona
I/SELinux ( 4484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SELinux ( 4484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/art     (  317): Explicit concurrent mark sweep GC freed 8749(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.765ms total 38.313ms
I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/NearbySource( 4383): Nearby Source Create!
D/NearbyContext( 4383): Nearby Context Create!
,V/EmergencyMode( 1410): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1410): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/TimaKeyStoreProvider( 4484): TimaSignature is unavailable
D/ActivityThread( 4484): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 806us total 21.196ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 1014): Killing 3602:com.google.android.gm/u0a101 (adj 15): empty #31
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.511ms
,W/ResourcesManager( 4484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/ActivityManager( 1014): Killing 3248:com.google.android.youtube/u0a166 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3799): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/FeatureConfig( 4469): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4383): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
E/Zygote  ( 4502): MountEmulatedStorage()
I/libpersona( 4502): KNOX_SDCARD checking this for 10010
E/Zygote  ( 4502): v2
I/libpersona( 4502): KNOX_SDCARD not a persona
,D/SLinkSource( 4383): Samsung link source created
,I/SELinux ( 4502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4502): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4502 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
,W/ResourcesManager( 4469): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 4513): MountEmulatedStorage()
,E/Zygote  ( 4513): v2
I/libpersona( 4513): KNOX_SDCARD checking this for 10091
I/libpersona( 4513): KNOX_SDCARD not a persona
I/SELinux ( 4513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4513): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4513 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3676:com.vlingo.midas/u0a31 (adj 15): empty #31,
W/ResourcesManager( 4469): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4502): TimaSignature is unavailable
I/ActivityManager( 1014): Killing 3816:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
D/ActivityThread( 4502): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4513): TimaSignature is unavailable
D/ActivityThread( 4513): Added TimaKeyStore provider
,W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3943): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
,W/ResourcesManager( 4469): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 4469): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4536): MountEmulatedStorage(),
E/Zygote  ( 4536): v2
I/libpersona( 4536): KNOX_SDCARD checking this for 10038
I/libpersona( 4536): KNOX_SDCARD not a persona
,I/SELinux ( 4536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4536 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 4536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4536): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4469): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 4383): PackagesMonitor onReceive :com.example.hello
,D/ContactProvider( 4383): getAllContactInfoList Start
,W/ResourcesManager( 4469): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_3602/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10166/pid_3248/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4536): TimaSignature is unavailable
,D/ActivityThread( 4536): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_3816/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10031/pid_3676/cgroup.procs: No such file or directory
,W/ResourcesManager( 4469): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4536): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 4536): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ContactProvider( 4383): getAllContactInfoList End
,I/syncContacts( 4383): thread: 693, sync time = 120
,W/ResourcesManager( 4469): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 4469): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4553): MountEmulatedStorage()
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=4553 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/Zygote  ( 4553): v2
I/ActivityManager( 1014): Killing 3901:com.sec.android.soagent/u0a34 (adj 15): empty #31
I/libpersona( 4553): KNOX_SDCARD checking this for 10046
I/libpersona( 4553): KNOX_SDCARD not a persona
,I/SELinux ( 4553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4553): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4553): TimaSignature is unavailable
,D/ActivityThread( 4553): Added TimaKeyStore provider
,W/ResourcesManager( 4553): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4553): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4553): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4553): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4553): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4553): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 4553): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1014): Killing 3919:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2023): Loading module APK com.google.android.play.games
I/art     ( 1014): Explicit concurrent mark sweep GC freed 30089(1845KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.520ms total 146.696ms
,D/PackageBroadcastService( 2023): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10034/pid_3901/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3919/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4571): MountEmulatedStorage(),
E/Zygote  ( 4571): v2
I/libpersona( 4571): KNOX_SDCARD checking this for 10032
I/libpersona( 4571): KNOX_SDCARD not a persona
,I/SELinux ( 4571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=4571 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 4571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/art     ( 4553): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 130.213ms
,D/TimaKeyStoreProvider( 4571): TimaSignature is unavailable
,D/ActivityThread( 4571): Added TimaKeyStore provider
,E/PhotosPlugin( 4513): Loading PhotosPlugin
,E/SMD     (  292): DCD OFF
,D/Mms/TelephonyPermission( 4553): start operation mode monitor
,D/Mms/ArtClassLoader( 4553): init before art
,W/ResourcesManager( 4553): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4553): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4553): isDefault true
,D/Mms/MmsApp( 4553): onCreate() com.android.mms
,I/SL_DEBUG( 4536): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 4536): isLoggable:: SL_DEBUG_EXIST = false
,D/Mms/MmsApp( 4553): [start]    initCountryIso consume time = 382.080208
,D/CountryDetector( 1014): The first listener is added
,D/Mms/MmsApp( 4553): [end]    initCountryIso consume time = 7.883542
,D/Mms/MmsConfig( 4553): [start]    MmsConfig.init() consume time = 0.313125
,D/Mms/MmsConfig( 4553): before partial update
,D/Mms/MmsConfig( 4553): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4553): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4553): isAuth is false
,D/Mms/MmsConfig( 4553): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1452): query,matched:2117, calling pid = 4553,
,D/TP/MmsSmsProvider( 1452): match 2117:Elapsed time : 2.002 ms
,D/EasySignUpManager_1.0.1( 4553): isAuth is false
,D/EasySignUpManager_1.0.1( 4553): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4553): mps_code.dat does not exist
,E/CscParser( 4553): customer_path =/system/csc/customer.xml
E/CscParser( 4553): fileName + /system/csc/customer.xml
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/CscParser( 4553): mps_code.dat does not exist
E/CscParser( 4553): customer_path =/system/csc/customer.xml
E/CscParser( 4553): fileName + /system/csc/customer.xml
,D/CscParser( 4553): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4553):  enable multiwindow = true
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Mms/MessageUtils( 4553): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4553): updateCountryIso : update country iso info 
D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2023): Module APK com.google.android.play.games already loaded
D/Mms/MmsConfig( 4553): [end]    init() consume time = 174.579896
D/Mms/Contact( 4553): [start]    init() consume time = 0.803541
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/ContextImpl( 4536): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,I/Icing   ( 2023): Storage manager: low false usage 1.72MB avail 10.18GB capacity 11.68GB
,D/TP/MmsSmsProvider( 1452): query,matched:13, calling pid = 4553
,D/AsyncTaskServiceImpl( 2023): Submit a task: k
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1452): match 13:Elapsed time : 1.505 ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Contact( 4553): [end]    init consume time = 26.499896
,D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/Mms/DraftCache( 4553): [start]    rebuildCache consume time = 12.003281
,D/TP/MmsSmsProvider( 1452): query,matched:12, calling pid = 4553
,D/TP/MmsSmsProvider( 1452): match 12:Elapsed time : 2.159 ms
,D/Mms/DraftCache( 4553): [end]    rebuildCache consume time = 14.229011
,D/Mms/MethodReflector( 4553): getSubId is called
,D/Mms/TelephonyUtils( 4553): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4553): getTelephonyProperty is called
,D/Mms/DownloadManager( 4553): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 4553): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 4553): auto download without roaming -> true
,D/Mms/DownloadManager( 4553): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 4553): getSubId is called
,D/Mms/MethodReflector( 4553): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 4553): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4553): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4553): getTelephonyProperty is called
D/Mms/DownloadManager( 4553): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4553): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4553): auto download without roaming -> true
D/Mms/DownloadManager( 4553): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4553): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4553): mAutoDownload ------> true
,D/k       ( 2023): Processing package: com.example.hello
,D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ComposerPerformance( 4553): 1457427823771 ms / [DONE] Composer constructor
,E/CII     ( 4553): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4553): ReservationManager()
,I/Mms/ReservationManager( 4553): resetAfterConnected()
,D/TP/MmsSmsProvider( 1452): query,matched:7, calling pid = 4553
,D/TP/MmsSmsProvider( 1452): match 7:Elapsed time : 1.957 ms
,I/Mms/ReservationManager( 4553): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 4553): [end]    onCreate() consume time = 101.249323
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4536): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/Mms/Conversation( 4553): [start]    init() consume time = 5.367291
,D/TP/MmsSmsProvider( 1452): deleteConversation threadId: 9223372036854775807
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,D/TP/MmsSmsProvider( 1452): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1452): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1452): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1452): (284) automatic index on im_threads(normal_thread_id)
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/TP/MmsSmsProvider( 1452): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1452): need read changed broadcast:false
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Conversation( 4553): [end]    init consume time = 27.722657
,D/Mms/MessagingNotification( 4553): [start]    init() consume time = 3.412031
,D/Mms/DownloadManager( 4553): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4553): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4553): getSubId is called
,D/Mms/TelephonyUtils( 4553): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4553): getTelephonyProperty is called
D/Mms/DownloadManager( 4553): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4553): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4553): auto download without roaming -> true
D/Mms/DownloadManager( 4553): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4553): mAutoDownload ------> true
,D/GassUtils( 2023): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/k       ( 2023): Found info for package com.example.hello in db.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/Mms/MessagingNotification( 4553): [end]    init consume time = 15.81776
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/TP/MmsSmsProvider( 1452): query,matched:0, calling pid = 4553
V/TP/MmsSmsProvider( 1452): getSimpleConversations entered.
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1452): match 0:Elapsed time : 1.786 ms
,D/Mms/SpamFilter( 4553): [start]    SpamFilter fill() begin consume time = 12.466458
,D/Mms/FreeMessageStatusReceiver( 4553): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/Mms/Synchronizer( 4553): [start]    doSync consume time = 5.406771
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1452): query,matched:400, calling pid = 4553
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1452): update, matched:300, calling pid = 4553
V/TP/MmsSmsProvider( 1452): syncDBData start
,V/TP/MmsSmsProvider( 1452): syncDBData sms end
,V/TP/MmsSmsProvider( 1452): syncDBData mms end
,V/TP/MmsSmsProvider( 1452): syncDBData end
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Synchronizer( 4553): [end]    doSync consume time = 26.715261
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4636): MountEmulatedStorage(),
E/Zygote  ( 4636): v2
I/libpersona( 4636): KNOX_SDCARD checking this for 10047
I/libpersona( 4636): KNOX_SDCARD not a persona
,I/SELinux ( 4636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2,
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4636 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
I/SELinux ( 4636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 4636): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
,D/Mms/SpamFilter( 4553): [end]    SpamFilter fill() finished consume time = 30.255052
,D/lights  ( 1014): lcd : 32 +
,I/SA      ( 4052): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,I/SA      ( 4052): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4052): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
,D/lights  ( 1014): lcd : 32 -
,D/lights  ( 1014): lcd : 19 +
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/FreeMessageReceiverService( 4553): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 4553): onHandleIntent: ACTION_PACKAGE_ADDED
,D/TimaKeyStoreProvider( 4636): TimaSignature is unavailable
,D/ActivityThread( 4636): Added TimaKeyStore provider
,D/lights  ( 1014): lcd : 19 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/MessagingNotification( 4553): checkBadgeCount unreadCount=0 badgeCount=0
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,W/ResourcesManager( 4636): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1014): Killing 3956:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/PeopleDatabaseHelper( 2023): cleanUpNonGplusAccounts done.
D/TP/SmsProvider( 1452): query,matched:26, calling pid = 4553
W/ResourcesManager( 4636): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1452): match 26:Elapsed time : 1.244 ms
,W/ResourcesManager( 4636): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,D/Mms/ArtClassLoader( 4553): init [DONE] art
,D/TP/MmsSmsProvider( 1452): query,matched:6, calling pid = 4553
,D/TP/MmsSmsProvider( 1452): match 6:Elapsed time : 1.791 ms
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/BaseAppContext( 2023): Using Auth Proxy for data requests.
,E/Zygote  ( 4654): MountEmulatedStorage()
E/Zygote  ( 4654): v2
I/libpersona( 4654): KNOX_SDCARD checking this for 10025
I/libpersona( 4654): KNOX_SDCARD not a persona
,I/SELinux ( 4654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4654 uid=10025 gids={50025, 9997} abi=armeabi-v7a
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3956/cgroup.procs: No such file or directory
E/SELinux ( 4654): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4654): TimaSignature is unavailable
,D/ActivityThread( 4654): Added TimaKeyStore provider
,I/ActivityManager( 1014): Killing 3993:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/MyFiles ( 4636): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4654): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 4670): MountEmulatedStorage()
E/Zygote  ( 4670): v2
I/libpersona( 4670): KNOX_SDCARD checking this for 10004
I/libpersona( 4670): KNOX_SDCARD not a persona
,I/SELinux ( 4670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4670 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4012:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/SELinux ( 4670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
,I/TactileAssist( 1014): List of disabled apps :
,D/TimaKeyStoreProvider( 4670): TimaSignature is unavailable
,D/ActivityThread( 4670): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4685): MountEmulatedStorage(),
E/Zygote  ( 4685): v2
,I/libpersona( 4685): KNOX_SDCARD checking this for 10053
,I/libpersona( 4685): KNOX_SDCARD not a persona
,I/SELinux ( 4685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4685 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4119:com.sec.android.app.mt/1000 (adj 15): empty #31
E/SELinux ( 4685): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 4654): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/TimaKeyStoreProvider( 4685): TimaSignature is unavailable
E/installd(  287): system dir 0 : /system/app/
E/installd(  287): system dir 1 : /system/priv-app/
E/installd(  287): system dir 2 : /vendor/app/
E/installd(  287): system dir 3 : /oem/app/
D/ActivityThread( 4685): Added TimaKeyStore provider
,W/ResourcesManager( 4685): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/Mms/Omacp( 4553): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Compatibility( 4685): onReceive() it will make start service
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4685): onHandleIntent()
,D/Compatibility( 4685): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369,
,D/Compatibility( 4685): found: 2
I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true,
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4654): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/Compatibility( 4685): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,E/Zygote  ( 4705): MountEmulatedStorage()
I/libpersona( 4705): KNOX_SDCARD checking this for 10057
E/Zygote  ( 4705): v2
I/libpersona( 4705): KNOX_SDCARD not a persona
,I/SELinux ( 4705): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/Compatibility( 4685): skipping ResolveInfo{f30bc69 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 4685): considering ResolveInfo{335e66ee com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000},
D/Compatibility( 4685): default: com.sec.android.app.soundalive.SAControlPanelActivity,
,I/SELinux ( 4705): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4705 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/SELinux ( 4705): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/Compatibility( 4685): enabling receiver ResolveInfo{2ca2878f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 4685): enabling receiver ResolveInfo{2e1b7a1c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 4685): enabling receiver ResolveInfo{e8fb625 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 4685): enabling receiver ResolveInfo{24e03fa com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 4685): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/ActivityManager( 1014): Killing 4161:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,I/art     ( 2023): Background sticky concurrent mark sweep GC freed 10782(893KB) AllocSpace objects, 8(128KB) LOS objects, 7% free, 12MB/13MB, paused 4.779ms total 114.158ms
,D/TimaKeyStoreProvider( 4705): TimaSignature is unavailable
,D/ActivityThread( 4705): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3993/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4119/cgroup.procs: No such file or directory
,W/ResourcesManager( 4571): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_4012/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10125/pid_4161/cgroup.procs: No such file or directory
,W/ResourcesManager( 4571): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4571): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4571): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/UpdateIcingCorporaServi( 4705): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/GAV2    ( 4513): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationManagerService( 1014): getProviders()=[passive]
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 2023): updateResources: need to parse f{com.google.android.gms}
,W/art     ( 4513): Suspending all threads took: 5.784ms
,E/Watchdog( 1014): !@Sync 1
,D/SettingsProvider( 1014): name = audio_safe_volume_state
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4741 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4185:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
W/art     ( 2023): Suspending all threads took: 10.508ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,E/Zygote  ( 4741): MountEmulatedStorage()
I/libpersona( 4741): KNOX_SDCARD checking this for 10100
E/Zygote  ( 4741): v2
I/libpersona( 4741): KNOX_SDCARD not a persona
,W/GAV2    ( 4513): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
I/SELinux ( 4741): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
I/SELinux ( 4741): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/art     ( 2023): Background partial concurrent mark sweep GC freed 14484(898KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 13MB/21MB, paused 14.101ms total 78.891ms
,E/SELinux ( 4741): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1802): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  317): Explicit concurrent mark sweep GC freed 8709(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 27.448ms
,D/TimaKeyStoreProvider( 4741): TimaSignature is unavailable
,D/ActivityThread( 4741): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 897us total 17.431ms
,I/UpdateIcingCorporaServi( 4705): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 17.306ms
,D/PackageIntentReceiver( 4741): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4741): Not GearManger package! 
,W/AccountFeatureHelper( 4513): Write apps_features disabled false
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 2023): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2023): Module APK com.google.android.play.games already loaded
,E/Zygote  ( 4763): MountEmulatedStorage()
E/Zygote  ( 4763): v2
I/libpersona( 4763): KNOX_SDCARD checking this for 1000
I/SELinux ( 4763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4763): KNOX_SDCARD not a persona
,I/SELinux ( 4763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4763 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4205:com.android.calendar/u0a135 (adj 15): empty #31
,E/SELinux ( 4763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4763): TimaSignature is unavailable
,D/ActivityThread( 4763): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4780): MountEmulatedStorage(),
E/Zygote  ( 4780): v2
I/libpersona( 4780): KNOX_SDCARD checking this for 1000
I/libpersona( 4780): KNOX_SDCARD not a persona
,I/SELinux ( 4780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4780): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4780 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4102:com.android.providers.calendar/u0a42 (adj 15): empty #31
W/libprocessgroup( 1014): failed to open /acct/uid_10131/pid_4185/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_4205/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4780): TimaSignature is unavailable
,D/ActivityThread( 4780): Added TimaKeyStore provider
,W/GAV2    ( 4513): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager( 1014): Killing 4229:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/Icing   ( 2023): Internal init done: storage state 0
,I/Icing   ( 2023): Post-init done
,W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_4102/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 4780): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 4780): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 4798): MountEmulatedStorage()
I/libpersona( 4798): KNOX_SDCARD checking this for 10120
E/Zygote  ( 4798): v2
I/libpersona( 4798): KNOX_SDCARD not a persona
I/SELinux ( 4798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4798): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4798 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4305:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4798): TimaSignature is unavailable
,D/ActivityThread( 4798): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsService( 4780): Enter Oncreate
,D/AcmsServiceMonitor( 4780): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 4780): creating AcmsCore
,D/AcmsCore( 4780): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 4780): AcmsCore
,W/ResourcesManager( 4798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsCore( 4780): init
,D/AcmsCore( 4780): Looper handler is not null
,D/AcmsCore( 4780): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4780): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4780): Incrementing - Counter value: 1
D/AcmsCore( 4780): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 4780): onStartCommand
D/AcmsService( 4780): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 4780): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 4780): Incrementing - Counter value: 2
D/AcmsService( 4780): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsCertificateMngr( 4780): AcmsCertificateMngr
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 4780): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 4780): AcmsRevocationMngr
,D/AcmsService( 4780): Inside handle Intent
,D/AcmsService( 4780): App added - package name: com.example.hello
,D/AcmsCore( 4780): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4780): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4780): Incrementing - Counter value: 3
D/AcmsCore( 4780): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 4780): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 4780): Decrementing - Counter value: 2
,W/libprocessgroup( 1014): failed to open /acct/uid_10139/pid_4229/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4305/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{fe577c3 u0 com.samsung.android.providers.context/.ContextService}
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{139dcd1f u0 com.android.settings/.wifi.WifiCredService}
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/Mms/MmsApp( 4553):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 4553): [start]    fillCache consume time = 1874.525051
,D/Mms/ComposeMessageFragment( 4553): fillCache, easy = false
,E/Zygote  ( 4822): MountEmulatedStorage()
,E/Zygote  ( 4822): v2
I/libpersona( 4822): KNOX_SDCARD checking this for 10142
I/libpersona( 4822): KNOX_SDCARD not a persona
,I/SELinux ( 4822): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4822): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=4822 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4822): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4822): TimaSignature is unavailable
,D/ActivityThread( 4822): Added TimaKeyStore provider
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 23914(1366KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 3.035ms total 138.085ms,
,V/TaskCloserActivity( 4822): TaskCloserActivity enter()
,V/TaskCloserActivity( 4822): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/ActivityManager( 1014): Killing 4321:com.android.email/u0a145 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AbsListView( 4553): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 4553): [end]    fillCache consume time = 242.320625
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4838): MountEmulatedStorage(),
E/Zygote  ( 4838): v2
I/libpersona( 4838): KNOX_SDCARD checking this for 1000
I/libpersona( 4838): KNOX_SDCARD not a persona
I/SELinux ( 4838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4838 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4838): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4838): TimaSignature is unavailable
,D/ActivityThread( 4838): Added TimaKeyStore provider
,E/MTPRx   ( 4838): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 4838): sealedState: false
V/MTPRx   ( 4838): sealedUsbMassStorageState: false
E/MTPRx   ( 4838): check value of boot_completed is1
E/MTPRx   ( 4838): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4838): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4838): Status for mount/Unmount :removed
E/MTPRx   ( 4838): SDcard is not available
,W/MTPRx   ( 4838): value of connected istrue
W/MTPRx   ( 4838): value of configured istrue
W/MTPRx   ( 4838): value of mtpEnabled istrue
W/MTPRx   ( 4838): value of ptpEnabled isfalse
,E/MTPRx   ( 4838): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4838): mFirstTime: false
,D/        ( 4838): MTP: reading debug level property
,E/MTPJNIInterface( 4838): Getting CryptionKey from JAVA
,E/MTPRx   ( 4838): currentUserId is 0
,E/MTPRx   ( 4838): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4838): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4838): is_Privatemode is NOT 1
,D/Mms/BubbleViewCache( 4553): fillCache bubble = 1
,I/ValidateNoPeople( 1014): mEvictionCount: 0
,D/Mms/Contact( 4553): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4553): performUpdate:widgetCount=0
,D/SettingsProvider( 1014): name = boot_time_connected
,E/MTPRx   ( 4838): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4838): noti = 17
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,D/Mms/ContactsCache( 4553): [start]    invalidate() consume time = 149.100104
,D/Mms/ContactsCache( 4553): [end]    invalidate() consume time = 0.693229
,D/SecContentProvider( 1014): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4838): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/ContactProvider( 4383): getAllContactInfoList Start
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MTPRx   ( 4838): else part ... so first time!!!
,E/MTPPlaObsrvr( 4838): inside setContext()
E/MTPPlaObsrvr( 4838):  inside createplafiles
,W/libprocessgroup( 1014): failed to open /acct/uid_10145/pid_4321/cgroup.procs: No such file or directory
,E/MTPPlaObsrvr( 4838): playlist count is0
E/MTPPlaObsrvr( 4838):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4838):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4838): Inside registerContentObserver
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,E/MtpAdbObserver( 4838): inside setContext()
E/MtpAdbObserver( 4838): Inside registerContentObserver
W/Settings( 4838): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MtpService( 4838): onCreate.
,V/MtpMediaDBManager( 4838): inside deleteAllDB
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ContactProvider( 4383): getAllContactInfoList End
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,I/syncContacts( 4383): thread: 695, onChange
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4838): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 4838): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1802): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/MtpService( 4838): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MtpService( 4838): onStartCommand.
,W/MTPRx   ( 4838): calling native method
E/MTPJNIInterface( 4838): < MTP > Registering BroadCast receiver :::::
E/MtpService( 4838): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
V/MtpMediaDBManager( 4838): inside Thread updateDB
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 4838): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4838): noti = 10
,W/MTPRx   ( 4838): calling native method
E/MTPRx   ( 4838): Checking the driver time out
E/MTPJNIInterface( 4838): noti = 2
D/        ( 4838): deleting sockets before message queue initialization
,D/        ( 4838): event handler thread is created, so set the flag
,E/MtpMediaDBManager( 4838): count : 27
,E/MTPRx   ( 4838): called native method
E/MTPJNIInterface( 4838): setting Media scanner status0
E/MTPJNIInterface( 4838): After setting Media scanner status0
E/MtpService( 4838): onStartCommand.
,E/MtpService( 4838): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/MTPRx   ( 4838): notification from stack 1
,E/        ( 4838): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4838): Getting media scanner status0
,E/MTPJNIInterface( 4838): DeviceName is A5-1
D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/Icing   ( 2023): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,W/MtpMediaDBManager( 4838): sending db update complete noti to stack
E/MTPJNIInterface( 4838): noti = 29
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1309): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1309): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1309): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457449380000
D/daemonapp( 1309): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457427826318
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename,
,E/MTPJNIInterface( 4838): Status for mount/Unmount :removed
E/MTPJNIInterface( 4838): SDcard is not available
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1309): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/        ( 4838): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/daemonapp( 1309): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
E/SMD     (  292): DCD OFF
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 4838): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] ,
,E/Zygote  ( 4863): MountEmulatedStorage()
E/Zygote  ( 4863): v2
I/libpersona( 4863): KNOX_SDCARD checking this for 10111
I/libpersona( 4863): KNOX_SDCARD not a persona
,E/MTPJNIInterface( 4838): Status for mount/Unmount :removed
E/MTPJNIInterface( 4838): SDcard is not available
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer,
I/ActivityManager( 1014): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4863 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SQLiteLog( 4838): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
,E/SQLiteLog( 4838): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
E/SQLiteLog( 4838): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
E/SQLiteLog( 4838): (21) misuse at line 106108 of [9491ba7d73]
W/MTPRx   ( 4838): notification from stack 2
D/        ( 4838): [mtp_init_device] Library open with 32 bits.
D/        ( 4838): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4838): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4838): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4838):  [sua_support_present:1287] returning false 
D/        ( 4838): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,I/SELinux ( 4863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4863): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/Icing   ( 2023): Loaded CLD2 Version V2.0 - 20141016

```
