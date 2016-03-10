#### Test 623445121bdd37c_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/chromium( 2189): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2189): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 2189): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
I/Adreno-EGL( 2189): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2189): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2189): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2189): Local Branch: 
I/Adreno-EGL( 2189): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2189): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2189):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/AudioManagerAndroid( 2189): Requires BLUETOOTH permission
I/NSApplication( 2189): Starting up...
D/SettingsProvider( 1017): name = vibrate_in_silent
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
--------- beginning of system
W/ResourcesManager( 1448): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/CscReceiver( 1448): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1448): Recieve Sim State Changed : ABSENT
I/splitIntent( 1017): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1017): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1448, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/WifiApBroadcastReceiver( 1293): onReceive: action android.intent.action.SIM_STATE_CHANGED
E/Zygote  ( 2255): MountEmulatedStorage()
E/Zygote  ( 2255): v2
I/libpersona( 2255): KNOX_SDCARD checking this for 1000
I/libpersona( 2255): KNOX_SDCARD not a persona
I/SELinux ( 2255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2255 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
I/SELinux ( 2255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2268): MountEmulatedStorage()
E/Zygote  ( 2268): v2
I/libpersona( 2268): KNOX_SDCARD checking this for 1000
I/libpersona( 2268): KNOX_SDCARD not a persona
I/SELinux ( 2268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 2255): TimaSignature is unavailable
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityThread( 2255): Added TimaKeyStore provider
E/SELinux ( 2268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
D/BootupListener( 1448): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
D/TimaKeyStoreProvider( 2268): TimaSignature is unavailable
D/ActivityThread( 2268): Added TimaKeyStore provider
D/PhoneUtilsCommon( 1448): isSupportVoLTE is false.
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
E/Zygote  ( 2286): MountEmulatedStorage()
I/libpersona( 2286): KNOX_SDCARD checking this for 10046
E/Zygote  ( 2286): v2
I/libpersona( 2286): KNOX_SDCARD not a persona
I/SELinux ( 2286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2286 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux ( 2286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2286): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/StatusChecker( 2255): onReceive : android.intent.action.SIM_STATE_CHANGED
I/StatusChecker( 2255): onReceive : net.mt.init : 
D/StatusChecker( 2255): onReceive : preference initializing
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2286): TimaSignature is unavailable
D/ActivityThread( 2286): Added TimaKeyStore provider
E/Zygote  ( 2302): MountEmulatedStorage()
E/Zygote  ( 2302): v2
I/libpersona( 2302): KNOX_SDCARD checking this for 1000
I/libpersona( 2302): KNOX_SDCARD not a persona
I/SELinux ( 2302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2286): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2286): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2286): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2286): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2286): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2286): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2302): TimaSignature is unavailable
D/ActivityThread( 2302): Added TimaKeyStore provider
E/Zygote  ( 2318): MountEmulatedStorage()
E/Zygote  ( 2318): v2
I/libpersona( 2318): KNOX_SDCARD checking this for 1000
I/libpersona( 2318): KNOX_SDCARD not a persona
I/SELinux ( 2318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2318 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2318): TimaSignature is unavailable
D/ActivityThread( 2318): Added TimaKeyStore provider
I/Omc:Receiver( 2302): onReceive : android.intent.action.SIM_STATE_CHANGED
I/Omc:OmcData( 2302): omc.xml not exist
I/Omc:Receiver( 2302): OM Customize disabled
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2333): MountEmulatedStorage()
E/Zygote  ( 2333): v2
I/libpersona( 2333): KNOX_SDCARD checking this for 10131
I/libpersona( 2333): KNOX_SDCARD not a persona
I/SELinux ( 2333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2333): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2333 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/art     (  309): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 21.202ms
D/TimaKeyStoreProvider( 2333): TimaSignature is unavailable
D/ActivityThread( 2333): Added TimaKeyStore provider
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 591us total 16.567ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 595us total 16.650ms
E/Zygote  ( 2348): MountEmulatedStorage()
E/Zygote  ( 2348): v2
I/libpersona( 2348): KNOX_SDCARD checking this for 1000
I/libpersona( 2348): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2348 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/Mms/MmsApp( 2286): [start]    onCreate() consume time = 0.0
E/SELinux ( 2348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 2333): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2333): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2333): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2333): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2348): TimaSignature is unavailable
D/ActivityThread( 2348): Added TimaKeyStore provider
E/USB_UICC(  295): Timeout! No signal received. Retry num = 21
W/art     ( 2286): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 117.020ms
D/SBrowserFeatureFlag( 2333): initialized in static block : loadCscFeatureValue() succeed! 
,D/Mms/ArtClassLoader( 2286): init before art
D/Mms/TelephonyPermission( 2286): start operation mode monitor
W/ResourcesManager( 2286): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2286): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2286): isDefault true
D/Mms/MmsApp( 2286): onCreate() com.android.mms
D/ManifestProvider( 2333): onCreate()
E/OperatorBookmarksSIMReceiver( 2333): onReceive runs..android.intent.action.SIM_STATE_CHANGED
D/Mms/MmsApp( 2286): [start]    initCountryIso consume time = 373.950781
D/CountryDetector( 1017): The first listener is added
D/Mms/MmsApp( 2286): [end]    initCountryIso consume time = 23.932709
D/Mms/MmsConfig( 2286): [start]    MmsConfig.init() consume time = 0.098333
D/Mms/MmsConfig( 2286): before partial update
D/Mms/MmsConfig( 2286): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2286): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2286): isAuth is false
D/AndroidRuntime( 2366): 
D/AndroidRuntime( 2366): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Mms/MmsConfig( 2286): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
D/AndroidRuntime( 2366): CheckJNI is OFF
D/AndroidRuntime( 2366): readGMSProperty: start
D/AndroidRuntime( 2366): readGMSProperty: already setted!!
D/AndroidRuntime( 2366): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2366): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2366): readGMSProperty: end
D/AndroidRuntime( 2366): addProductProperty: start
D/TP/MmsSmsProvider( 1448): query,matched:2117, calling pid = 2286
D/TP/MmsSmsProvider( 1448): match 2117:Elapsed time : 4.772 ms
D/EasySignUpManager_1.0.1( 2286): isAuth is false
D/EasySignUpManager_1.0.1( 2286): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2286): mps_code.dat does not exist
E/CscParser( 2286): customer_path =/system/csc/customer.xml
E/CscParser( 2286): fileName + /system/csc/customer.xml
E/CscParser( 2286): mps_code.dat does not exist
E/CscParser( 2286): customer_path =/system/csc/customer.xml
E/CscParser( 2286): fileName + /system/csc/customer.xml
D/CscParser( 2286): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2286):  enable multiwindow = true
E/Mms/MessageUtils( 2286): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2286): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2286): [end]    init() consume time = 184.838073
D/Mms/Contact( 2286): [start]    init() consume time = 2.506041
D/Mms/Contact( 2286): [end]    init consume time = 13.138855
D/TP/MmsSmsProvider( 1448): query,matched:13, calling pid = 2286
D/TP/MmsSmsProvider( 1448): match 13:Elapsed time : 1.078 ms
D/Mms/DraftCache( 2286): [start]    rebuildCache consume time = 8.16177
D/TP/MmsSmsProvider( 1448): query,matched:12, calling pid = 2286
D/TP/MmsSmsProvider( 1448): match 12:Elapsed time : 1.476 ms
D/Mms/MethodReflector( 2286): getSubId is called
D/Mms/TelephonyUtils( 2286): getLongSubId from simSlot 0, return Value = -1
D/Mms/DraftCache( 2286): [end]    rebuildCache consume time = 15.045782
D/Mms/MethodReflector( 2286): getTelephonyProperty is called
D/Mms/DownloadManager( 2286): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2286): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2286): auto download without roaming -> true
D/Mms/DownloadManager( 2286): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2286): getSubId is called
D/Mms/MethodReflector( 2286): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2286): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2286): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2286): getTelephonyProperty is called
D/Mms/DownloadManager( 2286): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2286): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2286): auto download without roaming -> true
D/Mms/DownloadManager( 2286): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2286): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2286): mAutoDownload ------> true
E/AffinityControl( 2366): AffinityControl: registerfunction enter
D/Mms/ArtClassLoader( 2286): init [DONE] art
D/AndroidRuntime( 2366): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/Launcher.HomeView( 1473): onPause
D/InputDispatcher( 1017): Focus left window: 1473
D/Launcher( 1473): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
D/AndroidRuntime( 2366): Shutting down VM
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/ComposerPerformance( 2286): 1457591075050 ms / [DONE] Composer constructor
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
E/CII     ( 2286): CommonIMSInterface: VoLTE CSC feature disabled.
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
I/Mms/ReservationManager( 2286): ReservationManager()
I/Mms/ReservationManager( 2286): resetAfterConnected()
D/Mms/Conversation( 2286): [start]    init() consume time = 102.849948
D/TP/MmsSmsProvider( 1448): query,matched:7, calling pid = 2286
D/TP/MmsSmsProvider( 1448): match 7:Elapsed time : 2.853 ms
E/Zygote  ( 2386): MountEmulatedStorage()
E/Zygote  ( 2386): v2
I/libpersona( 2386): KNOX_SDCARD checking this for 10174
I/libpersona( 2386): KNOX_SDCARD not a persona
I/SELinux ( 2386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2386 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2386): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsDatabaseHelper( 1448): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1448): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
I/Mms/ReservationManager( 2286): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsDatabaseHelper( 1448): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
V/ActivityThread( 1473): updateVisibility : ActivityRecord{106a3976 token=android.os.BinderProxy@25feca8a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TP/MmsSmsDatabaseHelper( 1448): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1448): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1448): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1448): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1448): updateThread(), thread_id = 9223372036854775807
D/Mms/MmsApp( 2286): [end]    onCreate() consume time = 40.245989
D/Mms/SmsReceiver( 2286): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
V/TP/MmsSmsDatabaseHelper( 1448): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TimaKeyStoreProvider( 2386): TimaSignature is unavailable
I/splitIntent( 1017): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/DownloadManager( 2286): Service state changed: Bundle[mParcelledData.dataSize=744]
D/TP/MmsSmsProvider( 1448): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
D/Mms/DownloadManager( 2286): roaming ------> false, mSimSlot = 0
D/ActivityThread( 2386): Added TimaKeyStore provider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Mms/MethodReflector( 2286): getSubId is called
D/Mms/TelephonyUtils( 2286): getLongSubId from simSlot 0, return Value = -1
D/Mms/Conversation( 2286): [end]    init consume time = 18.583802
D/Mms/MethodReflector( 2286): getTelephonyProperty is called
D/Mms/DownloadManager( 2286): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2286): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2286): auto download without roaming -> true
D/Mms/DownloadManager( 2286): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/BootupListener( 1448): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1448): isSupportVoLTE is false.
D/Mms/DownloadManager( 2286): mAutoDownload ------> true
D/Launcher.HomeView( 1473): onStop
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/Launcher( 1473): onTrimMemory. Level: 20
V/ActivityThread( 1473): updateVisibility : ActivityRecord{106a3976 token=android.os.BinderProxy@25feca8a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/Mms/MessagingNotification( 2286): [start]    init() consume time = 13.134844
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/Mms/SmsReceiverService( 2286): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/StatusChecker( 2255): onReceive : android.intent.action.SERVICE_STATE
I/StatusChecker( 2255): onReceive : net.mt.init : DONE
D/Mms/TelephonyPermission( 2286): isDefault true
D/Mms/MessagingNotification( 2286): [end]    init consume time = 27.583177
D/Mms/SmsReceiverService( 2286): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2286): handleSIMStatus()
D/Mms/SmsReceiverService( 2286): handleSIMStatus(): SIM_STATUS = ABSENT
D/StatusChecker( 2255): Service state changed : 3 mSub-1
D/Mms/SpamFilter( 2286): [start]    SpamFilter fill() begin consume time = 12.664375
D/TP/MmsSmsProvider( 1448): query,matched:0, calling pid = 2286
V/TP/MmsSmsProvider( 1448): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1448): match 0:Elapsed time : 1.682 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/Synchronizer( 2286): [start]    doSync consume time = 8.525469
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1448): query,matched:400, calling pid = 2286
D/TP/MmsSmsProvider( 1448): update, matched:300, calling pid = 2286
V/TP/MmsSmsProvider( 1448): syncDBData start
V/TP/MmsSmsProvider( 1448): syncDBData sms end
V/TP/MmsSmsProvider( 1448): syncDBData mms end
V/TP/MmsSmsProvider( 1448): syncDBData end
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/Synchronizer( 2286): [end]    doSync consume time = 30.659218
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/SpamFilter( 2286): [end]    SpamFilter fill() finished consume time = 8.105678
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/MessagingNotification( 2286): checkBadgeCount unreadCount=0 badgeCount=0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/WebViewFactory( 2386): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/SmsProvider( 1448): query,matched:26, calling pid = 2286
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/SmsProvider( 1448): match 26:Elapsed time : 4.166 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/LibraryLoader( 2386): Time to load native libraries: 2 ms (timestamps 8446-8448)
I/LibraryLoader( 2386): Expected native library version number "",actual native library version number ""
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/art     ( 2366): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1448): query,matched:6, calling pid = 2286
D/TP/MmsSmsProvider( 1448): match 6:Elapsed time : 1.212 ms
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/WebViewChromiumFactoryProvider( 2386): Binding Chromium to main looper Looper (main, tid 1) {2d10fb45}
,I/LibraryLoader( 2386): Expected native library version number "",actual native library version number ""
I/chromium( 2386): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1705): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2405): MountEmulatedStorage()
,E/Zygote  ( 2405): v2
I/libpersona( 2405): KNOX_SDCARD checking this for 10025
I/SELinux ( 2405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/libpersona( 2405): KNOX_SDCARD not a persona
,I/BrowserStartupController( 2386): Initializing chromium process, singleProcess=true
D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
W/art     ( 2386): Attempt to remove local handle scope entry from IRT, ignoring
,I/SELinux ( 2405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SysUtils( 2386): ApplicationContext is null in ApplicationStatus
E/SELinux ( 2405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2405 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,D/accuweather( 1705): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1705): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1705): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1705): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1705): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1705): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1705): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/chromium( 2386): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,D/TimaKeyStoreProvider( 2405): TimaSignature is unavailable
D/ActivityThread( 2405): Added TimaKeyStore provider
D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/chromium( 2386): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2386): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2386): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 2386): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2386): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2386): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2386): Local Branch: 
I/Adreno-EGL( 2386): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2386): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2386):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/accuweather( 1705): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
W/ResourcesManager( 2405): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/accuweather( 1705): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
D/accuweather( 1705): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1705): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
D/accuweather( 1705): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1705): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 07 24
,E/accuweather( 1705): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1705): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1705): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,E/SMD     (  287): DCD OFF,
D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1705): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1705): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1705): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1705): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 22
,D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
D/accuweather( 1705): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/OMACP   ( 2405): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/BluetoothAdapter( 2386): 784784998: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/Omacp( 2286): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,D/comsamsunglog( 1319): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1319): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1319): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1319): [MSC_Daemon]>>> ====================================================================================================================
I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,I/OMACP   ( 2405): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,W/chromium( 2386): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 2386): Attempt to remove local handle scope entry from IRT, ignoring
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8),
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/AwContents( 2386): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PhoneWindow( 2386): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2386): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2386): CordovaWebView is running on device made by: samsung
E/Zygote  ( 2439): MountEmulatedStorage()
E/Zygote  ( 2439): v2
I/libpersona( 2439): KNOX_SDCARD checking this for 10020
I/libpersona( 2439): KNOX_SDCARD not a persona
,I/SELinux ( 2439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2439 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 2439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2439): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
W/art     ( 2386): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2386): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 2439): TimaSignature is unavailable
,D/ActivityThread( 2439): Added TimaKeyStore provider
,W/ResourcesManager( 2439): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2439): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 2386): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false,
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/PhoneWindow( 2386): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2386): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 2386
,D/SRIB_DCS( 2386): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/OpenGLRenderer( 2386): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2386): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 2386): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +763ms
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{1871f09f u0 com.example.hello/.MainActivity t10} time:29012
,I/SamsungIME( 1818): getCurrentCandidateView
,I/Timeline( 2386): Timeline: Activity_idle id: android.os.BinderProxy@3a9b1ed8 time:29030
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/EasySignUpManager_1.15.0305( 2439): serviceId : 0, features : -1
,I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
D/SecContentProvider2( 1017): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): isCopyContactToSimAllowed = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2468): MountEmulatedStorage()
E/Zygote  ( 2468): v2
I/libpersona( 2468): KNOX_SDCARD checking this for 10044
I/libpersona( 2468): KNOX_SDCARD not a persona
,I/SELinux ( 2468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2468): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2468 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/BindingManager( 2386): Cannot call determinedVisibility() - never saw a connection for the pid: 2386
,E/Zygote  ( 2482): MountEmulatedStorage(),
I/libpersona( 2482): KNOX_SDCARD checking this for 10088
E/Zygote  ( 2482): v2
I/libpersona( 2482): KNOX_SDCARD not a persona
I/SELinux ( 2482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2482): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2482 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2468): TimaSignature is unavailable,
D/ActivityThread( 2468): Added TimaKeyStore provider,
I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SamsungIME( 1818): Dismiss ExpandCandiate
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/chromium( 2386): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/Zygote  ( 2495): MountEmulatedStorage(),
E/Zygote  ( 2495): v2
I/libpersona( 2495): KNOX_SDCARD checking this for 10142,
I/libpersona( 2495): KNOX_SDCARD not a persona
,I/SELinux ( 2495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2495 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2495): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2482): TimaSignature is unavailable
D/ActivityThread( 2482): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2495): TimaSignature is unavailable
,D/ActivityThread( 2495): Added TimaKeyStore provider
,D/JsMessageQueue( 2386): Set native->JS mode to OnlineEventsBridgeMode
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 35103(1936KB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 24MB/37MB, paused 3.643ms total 167.008ms
,E/AndroidProtocolHandler( 2386): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1473, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2482): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SamsungIME( 1818): getDebugLevel  : 0x4f4c
,W/ResourcesManager( 2468): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Zygote  ( 2515): MountEmulatedStorage()
E/Zygote  ( 2515): v2
I/libpersona( 2515): KNOX_SDCARD checking this for 10054
I/libpersona( 2515): KNOX_SDCARD not a persona
,I/SELinux ( 2515): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2515): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1017): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2515 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a,
E/SELinux ( 2515): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,V/TaskCloserActivity( 2495): TaskCloserActivity enter()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2468): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2468): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2468): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 2468): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2468): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 2526): MountEmulatedStorage()
E/Zygote  ( 2526): v2
I/libpersona( 2526): KNOX_SDCARD checking this for 10139
I/libpersona( 2526): KNOX_SDCARD not a persona
,I/SELinux ( 2526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 2515): TimaSignature is unavailable
,D/ActivityThread( 2515): Added TimaKeyStore provider
,I/SELinux ( 2526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2526 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,V/TaskCloserActivity( 2495): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/TimaKeyStoreProvider( 2526): TimaSignature is unavailable
,W/ResourcesManager( 2515): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,D/ActivityThread( 2526): Added TimaKeyStore provider
,I/SamsungIME( 1818): getDebugLevel  : 0x4f4c
,W/ResourcesManager( 2526): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2526): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2526): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2526): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2526): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Recents_RecreateReceiver( 2515): onReceive by home
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/jxcore_app_log( 2386): JniHelper::setJavaVM(0xb8eef450), pthread_self() = -1186639952
,D/JX-Cordova( 2386): jxcore cordova android initializing
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 23
,I/SamsungIME( 1818): KeybaordView init() : load resources
,W/jxcore-log( 2386): Initializing JXcore engine
W/jxcore-log( 2386): JXcore engine is ready
,W/jxcore-log( 2386): Starting JXcore engine
,E/audit   ( 1862): type=1400 msg=audit(1457591076.571:203): avc:  denied  { ioctl } for  pid=2386 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3088 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1862):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1862): type=1300 msg=audit(1457591076.571:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=becc2d58 items=0 ppid=309 ppcomm=main pid=2386 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1862): type=1320 msg=audit(1457591076.571:203): 
,I/SamsungIME( 1818): getCurrentKeyboard
I/SamsungIME( 1818): getTextKeyboard
,W/art     ( 2439): Verification of void com.android.contacts.common.list.l.P() took 135.061ms
,D/SamsungIME( 1818): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 2386): Platform android
W/jxcore-log( 2386): 
W/jxcore-log( 2386): Process ARCH arm
W/jxcore-log( 2386): 
,I/jxcore-log( 2386): JXcore Cordova bridge is ready!
I/jxcore-log( 2386): 
,W/jxcore-log( 2386): JXcore engine is started
,E/jxcore-log( 2386): >> samsung-SM-A500FU
E/jxcore-log( 2386): 
,I/jxcore-log( 2386): Total memory 1983791104
I/jxcore-log( 2386): 
,I/jxcore-log( 2386): Free memory 422944768
I/jxcore-log( 2386): 
I/jxcore-log( 2386): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2386): 
I/jxcore-log( 2386): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2386): 
,I/jxcore-log( 2386): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log( 2386): 
,D/NearbySource( 2468): Nearby Source Create!
,D/NearbyContext( 2468): Nearby Context Create!
,I/jxcore-log( 2386): Size 720 1280
I/jxcore-log( 2386): 
,I/jxcore-log( 2386): Screen Brightness 60
I/jxcore-log( 2386): 
,E/jxcore-log( 2386): Dummy Error Log.
E/jxcore-log( 2386): 
,D/AbsListView( 2439): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2468): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2468): Samsung link source created,
,D/ContactProvider( 2468): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2468): Receive : home resume
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,I/Mms/MmsApp( 2286):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 2286): [start]    fillCache consume time = 1889.85802
,D/Mms/ComposeMessageFragment( 2286): fillCache, easy = false
,E/SQLiteLog( 1233): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
,D/ContactProvider( 2468): getAllContactInfoList End
,I/syncContacts( 2468): thread: 253, sync time = 104
,D/AbsListView( 2286): Get MotionRecognitionManager
,D/MotionRecognitionService( 1017):  ssp status : false
,D/Mms/ComposeMessageFragment( 2286): [end]    fillCache consume time = 132.409166
,D/SamsungIME( 1818): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/Mms/BubbleViewCache( 2286): fillCache bubble = 1
,D/Mms/UIEventReceiver( 2286): ui event
,I/splitIntent( 1017): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/jxcore-log( 2386): getBuffer is called!!!!
I/jxcore-log( 2386): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 24
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1803): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/SIP     ( 1448): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/File    ( 1448): fail readDirectory() errno=2
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1319): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1319): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1319): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1319): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1319): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1176): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,D/AdaptiveEventManager( 1176): currentCityId is null
,D/AdaptiveEventManager( 1176): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1176): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1176): Weather Visibility: Previous= 0 >> Now= 0
,D/AdaptiveEventManager( 1176): Widget Count: Previous= 0 >> Now= 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,D/AdaptiveEventManager( 1176): mWeatherInfo is not reliable
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/daemonapp( 1319): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1319): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,E/Zygote  ( 2565): MountEmulatedStorage(),
E/Zygote  ( 2565): v2
I/libpersona( 2565): KNOX_SDCARD checking this for 10135
,I/SELinux ( 2565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 2565): KNOX_SDCARD not a persona
,I/SELinux ( 2565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2565 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 2565): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1457591077708
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1457612677701
D/daemonapp( 1319): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
D/daemonapp( 1319): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1457612640000
D/daemonapp( 1319): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457612640000
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1457612640000
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2565): TimaSignature is unavailable
,D/ActivityThread( 2565): Added TimaKeyStore provider
,E/Zygote  ( 2580): MountEmulatedStorage(),
E/Zygote  ( 2580): v2
I/libpersona( 2580): KNOX_SDCARD checking this for 1000
I/libpersona( 2580): KNOX_SDCARD not a persona
,I/SELinux ( 2580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2580 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 20.281ms
,D/TimaKeyStoreProvider( 2580): TimaSignature is unavailable
,D/ActivityThread( 2580): Added TimaKeyStore provider
W/ResourcesManager( 2565): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2565): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 2565): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.230ms
,I/Scheduler( 1803): Use legacy PeriodicScheduler
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.131ms
,W/InstanceID/Rpc( 1803): Found 10012
,D/SecurityLogAgent( 2580):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2580):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2580):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2580): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,D/SecurityLogAgent( 2580): FileZippingService : onHandleIntent 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2580): FileZippingService : file path =  /data/misc/audit/audit.old,
,E/Zygote  ( 2601): MountEmulatedStorage()
I/libpersona( 2601): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2601): v2
,I/libpersona( 2601): KNOX_SDCARD not a persona
I/SELinux ( 2601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2601 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 2580): FileZippingService : onPremise disabled. Zipping..  
D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2601): TimaSignature is unavailable
,D/ActivityThread( 2601): Added TimaKeyStore provider
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator File existence : true audit.old file size 643
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2580): FileZippingService : completed task. Returning wakelock . 
,W/ContextImpl( 2601): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2619): MountEmulatedStorage(),
E/Zygote  ( 2619): v2
I/libpersona( 2619): KNOX_SDCARD checking this for 1000
I/libpersona( 2619): KNOX_SDCARD not a persona
I/SELinux ( 2619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2619 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2619): TimaSignature is unavailable
,D/ActivityThread( 2619): Added TimaKeyStore provider
,W/ResourcesManager( 2619): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2619): [FactoryTestBroadcastReceiver$onReceive](2619) onReceive action=android.intent.action.BOOT_COMPLETED,
W/ActivityThread( 2619): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2619): [XMLDataStorage$parseXML](2619) is Live Demo : false
,D/FactoryTestApp( 2619): [XMLDataStorage$parseXML](2619) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2619): [XMLDataStorage$parseXML](2619) deviceXML=a5ulte.dat
,D/FactoryTestApp( 2619): [XMLDataStorage$parseXML](2619) nameXML=a5ultexx.dat
D/FactoryTestApp( 2619): [XMLDataStorage$parseAsset](2619) parseAsset Is Started
,I/FactoryTestApp( 2619): [XMLDataStorage$parseAsset](2619) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2619): [XMLDataStorage$parseAsset](2619) Decode base file: factory.dat
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FACTORY_TEST_APP
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FAILHIST_VERSION
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=MODEL_NAME
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=MODEL_NUMBER
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=CHIPSET_NAME
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=DEVICE_TYPE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=BATT_TYPE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PANEL_TYPE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SPEAKER_COUNT
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=MIC_COUNT
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_LTE
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_RCV
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_EPEN
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HW_VER_EFS
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FONT_SIZE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=RAM_SIZE_IF
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=MULTI_TSK_THD
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_POWER
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_HOME
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_BACK
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=AT_GPSSTEST
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PA0_TEMP_ADC
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HALL_IC_TEST
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=READ_TARGET_GEOMAGNETIC,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=BATTERY_TEST_MODE
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=BATTERY_VF_OCV,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=SEC_EXT_THERMISTER_TEMP,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PA0_THERMISTER_ADC,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PA1_THERMISTER_ADC,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_COMMAND_CMD,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_COMMAND_STATUS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=TSP_COMMAND_RESULT,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=PATH_HALLIC_STATE,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=KEY_PRESSED_POWER,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=APCHIP_TEMP_ADC,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HUMITEMP_THERMISTER_PAM,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HUMITEMP_THERMISTER_BATT,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HUMITEMP_THERMISTER_BATT_CELCIUS,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HUMITEMP_THERMISTER_S_HUB_BATT,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=LPA_MODE_SET,
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2619): [XMLDataStorage$redefinitionById](2619) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2619): [XMLDataStorage$parseAsset](2619) SemiFunctionMenu
,E/SMD     (  287): DCD OFF
,D/FactoryTestApp( 2619): [XMLDataStorage$parseAsset](2619) parseAsset Is Completed
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2619): [ModuleCommon$ModuleCommon](2619) Create ModuleCommon
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2619): [Support$Kernel.read](2619) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2619): [ModuleCommon$readFactoryMode](2619) mode: ON
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2619): [FactoryTestBroadcastReceiver$onReceive](2619) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2619): [Support$Values.getBoolean](2619) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2619): [Support$Properties.get](2619) property=ro.factory.factory_binary
D/FactoryTestApp( 2619): [FactoryTestBroadcastReceiver$onReceive](2619) Boot completed, IS_FACTORY_BINARY = USER MODE
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 25
,I/FactoryTestApp( 2619): [ModuleCommon$getFtClientEnableState](2619) result : false
I/FactoryTestApp( 2619): [ModuleCommon$connectedJIG](2619) ...
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2619): [ModuleCommon$connectedJIG](2619) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2619): [Support$Kernel.read](2619) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 2619): [ModuleCommon$connectedJIG](2619) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2619): [ModuleCommon$isConnectionModeNone](2619) mConnectionMode = gsm
I/FactoryTestApp( 2619): [ModuleCommon$isRunningFtClient](2619) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2619): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2619) start DummyFtClient service for APO
,W/ContextImpl( 2619): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2619): User mode
I/FactoryTestApp( 2619): [ModuleCommon$disableFtClient](2619) ...
,D/FactoryTestApp( 2619): [DummyFtClient$onCreate](2619) Create DummyFtClient service
,I/FactoryTestApp( 2619): [XMLDataStorage$parsingXML](2619) FtClient => data parsing was completed.
,D/FactoryTestApp( 2619): [DummyFtClient$onReceive](2619) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2619): [ModuleCommon$isConnectionModeNone](2619) mConnectionMode = gsm
,D/FactoryTestApp( 2619): [Support$Values.getBoolean](2619) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2619): [DummyFtClient$onStartCommand](2619) ...
,I/WifiService( 1017): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1017): boot completed
,D/UsbDeviceManager( 1017): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1017): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/UsbDeviceManager( 1017): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/ActivityManager( 1017): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,I/KeyguardEffectViewUtil( 1176): set resource id
,D/UsbDeviceManager( 1017): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1017): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10054
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1176): handleBootCompleted()
D/KeyguardUpdateMonitor( 1176): handleBootCompleted()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1017): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
E/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1017): [PALM] SURFACE_PALM_SWIPE: 1
D/LightsService( 1017): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1017) 
D/PalmMotion( 1017): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/PalmMotion( 1017): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,D/LightsService( 1017): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1017): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1017): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/GAV4    ( 2189): Thread[GAThread,5,main]: No campaign data found.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NfcService( 1435): call the applyRouting
,D/ActivityManager( 1017): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,D/SamsungIME( 1818): showDlgMsgBox : false true true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/Zygote  ( 2643): MountEmulatedStorage(),
E/Zygote  ( 2643): v2
I/libpersona( 2643): KNOX_SDCARD checking this for 1000
I/libpersona( 2643): KNOX_SDCARD not a persona,
I/SELinux ( 2643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2643 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/RecoverySystem( 1017): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1017): No recovery log file
,D/ActivityManager( 1017): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/GAv4-SVC( 2056): Google Analytics 8.4.89 is starting up.
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1017): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,V/OtaStartupReceiver( 1448): onOtaspChanged: mOtaspMode=1
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Reset_Reason( 1017): resetString = NPON
,E/Zygote  ( 2663): MountEmulatedStorage()
,E/Zygote  ( 2663): v2
,D/TimaKeyStoreProvider( 2643): TimaSignature is unavailable
I/libpersona( 2663): KNOX_SDCARD checking this for 1001
D/ActivityThread( 2643): Added TimaKeyStore provider
I/libpersona( 2663): KNOX_SDCARD not a persona
I/SELinux ( 2663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2663 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 2663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2663): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/BootReceiver( 1017): Copying audit failures to DropBox
I/BootReceiver( 1017): Checking for fsck errors
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/File    ( 2643): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 2663): TimaSignature is unavailable
,D/ActivityThread( 2663): Added TimaKeyStore provider
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 2663): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/FactoryTestApp( 2619): [ProtectedFactoryTestBroadcastReceiver$onReceive](2619) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2619): [ProtectedFactoryTestBroadcastReceiver$onReceive](2619) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2619): User mode
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/NotificationReceiver( 2286): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2286): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2286): queue Uri = content://im/queue-messages?box=pending
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TP/ImProvider( 1448): im query match24
,D/TP/ImProvider( 1448): URI_IM_QUEUED_MESSAGES
,D/TP/ImProvider( 1448): ftSesstionId must be a long.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TP/ImProvider( 1448): getQueuedImMessages
,D/TP/ImProvider( 1448): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Mms/NotificationReceiver( 2286):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2286): Call to GET_LAST_MESSAGES_SENT
I/BootReceiver( 1017): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 31510, tid: 31510, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b914bd48  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b914bd48  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 ba64e378  sl ba64e378  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr a0b0030c  pc a0affd98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859ec62bb0  d1  0000000000000000
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):          be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):       
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/SettingsProvider( 1017): name = db_smartlock_supported
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 2016, tid: 2016, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b926a1f0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b926a1f0  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 baf12548  sl baf12548  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr a09c330c  pc a09c2d98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859e8579c0  d1  0000000000000000
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):          be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):         
D/CrashAnrDetector( 1017): processName:com.test.thalitest
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
I/BootReceiver( 1017): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/AccessibilityManagerService( 1017): setmDNIeNegative (false)
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 8409, tid: 8409, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b9145f50  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b9145f50  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 bab49fd0  sl bab49fd0  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr 9fdfc30c  pc 9fdfbd98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859df5ebb0  d1  646f6d5f65646f6e
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000012
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):     ,     be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):         
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 10813, tid: 10813, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1017):     r0 b92c7dd0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1017):     r4 0045b0a0  r5 be11f218  r6 b92c7dd0  r7 be11f228
D/CrashAnrDetector( 1017):     r8 be11ee60  r9 b9a6af30  sl b9a6af30  fp be11f1dc
D/CrashAnrDetector( 1017):     ip be11f228  sp be11ee58  lr a0d6430c  pc a0d63d98  cpsr a00f0010
D/CrashAnrDetector( 1017):     d0  ffffff859ec579c0  d1  0000000000000000
D/CrashAnrDetector( 1017):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1017):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1017):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000012
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1017):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1017):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1017):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          be11edd8  00000000  
D/CrashAnrDetector( 1017):          be11eddc  00000000  
D/CrashAnrDetector( 1017):          be11ede0  00000000  
D/CrashAnrDetector( 1017):          be11ede4  00000000  
D/CrashAnrDetector( 1017):          be11ede8  00000000  
D/CrashAnrDetector( 1017):          be11edec  00000000  
D/CrashAnrDetector( 1017):          be11edf0  00000000  
D/CrashAnrDetector( 1017):          be11edf4  00000000  
D/CrashAnrDetector( 1017):          be11edf8  00000000  
D/CrashAnrDetector( 1017):          be11edfc  00000000  
D/CrashAnrDetector( 1017):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1017):          be11ee04  00000000  
D/CrashAnrDetector( 1017):          be11ee08  00000000  
D/CrashAnrDetector( 1017):          be11ee0c  00000000  
D/CrashAnrDetector( 1017):          be11ee10  00000000  
D/CrashAnrDetector( 1017):          be11ee14  00000000  
D/CrashAnrDetector( 1017):          be11ee18  00000000  
D/CrashAnrDetector( 1017):          be11ee1c  00000000  
D/CrashAnrDetector( 1017):          be11ee20  00000000  
D/CrashAnrDetector( 1017):          be11ee24  00000000  
D/CrashAnrDetector( 1017):          be11ee28  00000000  
D/CrashAnrDetector( 1017):          be11ee2c  00000000  
D/CrashAnrDetector( 1017):          be11ee30  00000000  
D/CrashAnrDetector( 1017):          be11ee34  00000000  
D/CrashAnrDetector( 1017):          be11ee38  00000000  
D/CrashAnrDetector( 1017):          be11ee3c  00000000  
D/CrashAnrDetector( 1017):          be11ee40  00000000  
D/CrashAnrDetector( 1017):          be11ee44  00000000  
D/CrashAnrDetector( 1017):          be11ee48  00000000  
D/CrashAnrDetector( 1017):          be11ee4c  00000000  
D/CrashAnrDetector( 1017):          be11ee50  00000000  
D/CrashAnrDetector( 1017):          be11ee54  00000000  
D/CrashAnrDetector( 1017):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1017):          be11ee5c  00000000  
D/CrashAnrDetector( 1017):          be11ee60  00000000  
D/CrashAnrDetector( 1017):          be11ee64  00000000  
D/CrashAnrDetector( 1017):          be11ee68  00000000  
D/CrashAnrDetector( 1017):          be11ee6c  00000000  
D/CrashAnrDetector( 1017):          be11ee70  00000000  
D/CrashAnrDetector( 1017):          be11ee74  00000000  
D/CrashAnrDetector( 1017):          be11ee78  00000000  
D/CrashAnrDetector( 1017):          be11ee7c  00000000  
D/CrashAnrDetector( 1017):          be11ee80  00000000  
D/CrashAnrDetector( 1017):          be11ee84  00000000  
D/CrashAnrDetector( 1017):          be11ee88  00000000  
D/CrashAnrDetector( 1017):          be11ee8c  00000000  
D/CrashAnrDetector( 1017):          be11ee90  00000000  
D/CrashAnrDetector( 1017):          be11ee94  00000000  
D/CrashAnrDetector( 1017):          be11ee98  00000000  
D/CrashAnrDetector( 1017):          be11ee9c  00000000  
D/CrashAnrDetector( 1017):          be11eea0  00000000  
D/CrashAnrDetector( 1017):          be11eea4  00000000  
D/CrashAnrDetector( 1017):          be11eea8  00000000  
D/CrashAnrDetector( 1017):          be11eeac  00000000  
D/CrashAnrDetector( 1017):          be11eeb0  00000000  
D/CrashAnrDetector( 1017):          be11eeb4  00000000  
D/CrashAnrDetector( 1017):          be11eeb8  00000000  
D/CrashAnrDetector( 1017):          be11eebc  00000000  
D/CrashAnrDetector( 1017):       
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 6058, tid: 6772, name: Thread-1061  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9c909ff0
D/CrashAnrDetector( 1017):     r0 710804a8  r1 735927c8  r2 12dd4780  r3 13533ec0
D/CrashAnrDetector( 1017):     r4 000000c2  r5 710804a8  r6 735927c8  r7 13533ec0
D/CrashAnrDetector( 1017):     r8 73592770  r9 ba677458  sl 12dd4780  fp 9ca0b8a8
D/CrashAnrDetector( 1017):     ip 9c909ff0  sp 9c90bff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1017):     d0  12dd4780735927c0  d1  007300200065003e
D/CrashAnrDetector( 1017):     d2  c0c0c0c0c0c0c053  d3  0102020202020213
D/CrashAnrDetector( 1017):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1017):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1017):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1017):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1017):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1017):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1017):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1017):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1017):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          9c90bf70  00000000  
D/CrashAnrDetector( 1017):          9c90bf74  00000000  
D/CrashAnrDetector( 1017):          9c90bf78  00000000  
D/CrashAnrDetector( 1017):          9c90bf7c  00000000  
D/CrashAnrDetector( 1017):          9c90bf80  00000000  
D/CrashAnrDetector( 1017):          9c90bf84  00000000  
D/CrashAnrDetector( 1017):          9c90bf88  00000000  
D/CrashAnrDetector( 1017):          9c90bf8c  00000000  
D/CrashAnrDetector( 1017):          9c90bf90  00000000  
D/CrashAnrDetector( 1017):          9c90bf94  00000000  
D/CrashAnrDetector( 1017):          9c90bf98  00000000  
D/CrashAnrDetector( 1017):          9c90bf9c  00000000  
D/CrashAnrDetector( 1017):          9c90bfa0  00000000  
D/CrashAnrDetector( 1017):          9c90bfa4  00000000  
D/CrashAnrDetector( 1017):          9c90bfa8  00000000  
D/CrashAnrDetector( 1017):          9c90bfac  00000000  
D/CrashAnrDetector( 1017):          9c90bfb0  00000000  
D/CrashAnrDetector( 1017):          9c90bfb4  00000000  
D/CrashAnrDetector( 1017):          9c90bfb8  00000000  
D/CrashAnrDetector( 1017):          9c90bfbc  00000000  
D/CrashAnrDetector( 1017):          9c90bfc0  00000000  
D/CrashAnrDetector( 1017):          9c90bfc4 , 00000000  
D/CrashAnrDetector( 1017):          9c90bfc8  00000000  
D/CrashAnrDetector( 1017):          9c90bfcc  00000000  
D/CrashAnrDetector( 1017):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90bfd4  00000000  
D/CrashAnrDetector( 1017):          9c90bfd8  00000000  
D/CrashAnrDetector( 1017):          9c90bfdc  00000000  
D/CrashAnrDetector( 1017):          9c90bfe0  00000000  
D/CrashAnrDetector( 1017):          9c90bfe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90bfe8  e3a070ad  
D/CrashAnrDetector( 1017):          9c90bfec  ef9000ad  
D/CrashAnrDetector( 1017):     #00  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          ........  ........
D/CrashAnrDetector( 1017):     #01  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90bff4  00000000  
D/CrashAnrDetector( 1017):          9c90bff8  00000000  
D/CrashAnrDetector( 1017):          9c90bffc  00000000  
D/CrashAnrDetector( 1017):          9c90c000  00000000  
D/CrashAnrDetector( 1017):          9c90c004  00000000  
D/CrashAnrDetector( 1017):          9c90c008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c00c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c010  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          9c90c014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c018  12dd4780  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          9c90c01c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):          9c90c020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c024  00000000  
D/CrashAnrDetector( 1017):          9c90c028  00000000  
D/CrashAnrDetector( 1017):          9c90c02c  00000000  
D/CrashAnrDetector( 1017):          9c90c030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c034  00000000  
D/CrashAnrDetector( 1017):          9c90c038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c03c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          9c90c040  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          9c90c044  73
D/CrashAnrDetector( 1017): processName:com.test.thalitest
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/Settings( 1293): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/BootReceiver( 1017): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1017): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/SettingsProvider( 1017): name = block_emergency_message
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 6080, tid: 6935, name: Thread-1071  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa37a6ff0
D/CrashAnrDetector( 1017):     r0 710804a8  r1 735927c8  r2 12e00890  r3 133c2fc0
D/CrashAnrDetector( 1017):     r4 000000c2  r5 710804a8  r6 735927c8  r7 133c2fc0
D/CrashAnrDetector( 1017):     r8 73592770  r9 b8284ec8  sl 12e00890  fp a38a88a8
D/CrashAnrDetector( 1017):     ip a37a6ff0  sp a37a8ff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1017):     d0  12e00890735927c0  d1  007300200065002f
D/CrashAnrDetector( 1017):     d2  c0c0c0c0c0c0c03c  d3  0102020202020213
D/CrashAnrDetector( 1017):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1017):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1017):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1017):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1017):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1017):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1017):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1017):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1017):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1017):     scr 20000013
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          a37a8f70  00000000  
D/CrashAnrDetector( 1017):          a37a8f74  00000000  
D/CrashAnrDetector( 1017):          a37a8f78  00000000  
D/CrashAnrDetector( 1017):          a37a8f7c  00000000  
D/CrashAnrDetector( 1017):          a37a8f80  00000000  
D/CrashAnrDetector( 1017):          a37a8f84  00000000  
D/CrashAnrDetector( 1017):          a37a8f88  00000000  
D/CrashAnrDetector( 1017):          a37a8f8c  00000000  
D/CrashAnrDetector( 1017):          a37a8f90  00000000  
D/CrashAnrDetector( 1017):          a37a8f94  00000000  
D/CrashAnrDetector( 1017):          a37a8f98  00000000  
D/CrashAnrDetector( 1017):          a37a8f9c  00000000  
D/CrashAnrDetector( 1017):          a37a8fa0  00000000  
D/CrashAnrDetector( 1017):          a37a8fa4  00000000  
D/CrashAnrDetector( 1017):          a37a8fa8  00000000  
D/CrashAnrDetector( 1017):          a37a8fac  00000000  
D/CrashAnrDetector( 1017):          a37a8fb0  00000000  
D/CrashAnrDetector( 1017):          a37a8fb4  00000000  
D/CrashAnrDetector( 1017):          a37a8fb8  00000000  
D/CrashAnrDetector( 1017):          a37a8fbc  00000000  
D/CrashAnrDetector( 1017):          a37a8fc0  00000000  
D/CrashAnrDetector( 1017):          a37a8fc4 , 00000000  
D/CrashAnrDetector( 1017):          a37a8fc8  00000000  
D/CrashAnrDetector( 1017):          a37a8fcc  00000000  
D/CrashAnrDetector( 1017):          a37a8fd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a8fd4  00000000  
D/CrashAnrDetector( 1017):          a37a8fd8  00000000  
D/CrashAnrDetector( 1017):          a37a8fdc  00000000  
D/CrashAnrDetector( 1017):          a37a8fe0  00000000  
D/CrashAnrDetector( 1017):          a37a8fe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a8fe8  e3a070ad  
D/CrashAnrDetector( 1017):          a37a8fec  ef9000ad  
D/CrashAnrDetector( 1017):     #00  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          ........  ........
D/CrashAnrDetector( 1017):     #01  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a8ff4  00000000  
D/CrashAnrDetector( 1017):          a37a8ff8  00000000  
D/CrashAnrDetector( 1017):          a37a8ffc  00000000  
D/CrashAnrDetector( 1017):          a37a9000  00000000  
D/CrashAnrDetector( 1017):          a37a9004  00000000  
D/CrashAnrDetector( 1017):          a37a9008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a900c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9010  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          a37a9014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9018  12e00890  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          a37a901c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1017):          a37a9020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9024  00000000  
D/CrashAnrDetector( 1017):          a37a9028  00000000  
D/CrashAnrDetector( 1017):          a37a902c  00000000  
D/CrashAnrDetector( 1017):          a37a9030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9034  00000000  
D/CrashAnrDetector( 1017):          a37a9038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a903c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1017):          a37a9040  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1017):          a37a9044  73
D/CrashAnrDetector( 1017): processName:com.test.thalitest
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1017): broadcastEvent : null SYSTEM_TOMBSTONE
,D/SettingsProvider( 1017): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Killing 1189:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1189/cgroup.procs: No such file or directory
,D/[LPC]   ( 1017): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2688): MountEmulatedStorage()
,E/Zygote  ( 2688): v2
I/libpersona( 2688): KNOX_SDCARD checking this for 1000
I/libpersona( 2688): KNOX_SDCARD not a persona
,I/SELinux ( 2688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1017): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2688 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/SELinux ( 2688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2688): TimaSignature is unavailable
,D/ActivityThread( 2688): Added TimaKeyStore provider
,W/ResourcesManager( 2688): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 2688): (539) recovered 3 pages from /data/user/0/com.samsung.android.sm/databases/lowpowercontext-system-db-journal
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,W/CursorWrapperInner( 2286): Cursor finalized without prior close()
,I/i       ( 1017): No model
,D/FactoryTest( 1017): Not factory mode
D/FactoryTest( 1017): Not factory mode. isFactoryMode() returend false
D/w       ( 1017): isUserBuild = true
,E/SmartFaceService( 1017): onReceive: android.intent.action.BOOT_COMPLETED
D/SmartFaceIndicator( 1017): no icon
,E/SmartFaceService( 1017): mActiveServiceType: 0
E/SmartFaceService( 1017): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1017): updateClientsDone. def. do nothing.
E/SmartFaceService( 1017): Service Type to Worker: 0
E/SmartFaceService( 1017): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1017): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,V/AlarmManagerEXT( 1017): mGmsLocationBundling: false
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb9685908, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SSRM:aZ ( 1017): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1017): Updating Threshold Value.. isSystemReady: true
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb9a02d18, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/CrashAnrDetector( 1017): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1017): Hardware: MSM8916
D/CrashAnrDetector( 1017): Revision: 2
D/CrashAnrDetector( 1017): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1017): Radio: unknown
D/CrashAnrDetector( 1017): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1017): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1017): Revision: '2'
D/CrashAnrDetector( 1017): ABI: 'arm'
D/CrashAnrDetector( 1017): pid: 2458, tid: 2624, name: Thread-256  >>> com.example.hello <<<
D/CrashAnrDetector( 1017): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1017):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1017):     r4 9dddde78  r5 9dddde38  r6 b8adc500  r7 9dddde38
D/CrashAnrDetector( 1017):     r8 00000000  r9 9dddde74  sl 9dddf3d0  fp 9dddde1c
D/CrashAnrDetector( 1017):     ip 9d93cba0  sp 9dddde00  lr 9d643308  pc b6f2d468  cpsr 600d0030
D/CrashAnrDetector( 1017):     d0  513802003a373ed5  d1  0000b80c030000a1
D/CrashAnrDetector( 1017):     d2  88000000560a109d  d3  0000003502000060
D/CrashAnrDetector( 1017):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1017):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1017):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1017):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1017):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1017):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1017):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1017):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1017):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1017):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1017):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1017):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1017):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1017):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1017):     scr 20000012
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): backtrace:
D/CrashAnrDetector( 1017):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1017):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1017): 
D/CrashAnrDetector( 1017): stack:
D/CrashAnrDetector( 1017):          9ddddd80  00000000  
D/CrashAnrDetector( 1017):          9ddddd84  00000000  
D/CrashAnrDetector( 1017):          9ddddd88  9cd2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9ddddd8c  e8bc0f76  
D/CrashAnrDetector( 1017):          9ddddd90  9dddddbc  [stack:2624]
D/CrashAnrDetector( 1017):          9ddddd94  9dddde64  [stack:2624]
D/CrashAnrDetector( 1017):          9ddddd98  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9ddddd9c  00000003  
D/CrashAnrDetector( 1017):          9ddddda0  9ddddddc  [stack:2624]
D/CrashAnrDetector( 1017):          9ddddda4  b8b162a8  [heap]
D/CrashAnrDetector( 1017):          9ddddda8  9cd53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddac  9da11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddb0  00000000  
D/CrashAnrDetector( 1017):          9dddddb4  ffffff82  
D/CrashAnrDetector( 1017):          9dddddb8  00000000  
D/CrashAnrDetector( 1017):          9dddddbc  ffffff82  
D/CrashAnrDetector( 1017):          9dddddc0  9cd2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddc4  b8b132a8  [heap]
D/CrashAnrDetector( 1017):,          9dddddc8  b8bcbd18  [heap]
D/CrashAnrDetector( 1017):          9dddddcc  00000001  
D/CrashAnrDetector( 1017):          9dddddd0  9cd49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9dddddd4  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9dddddd8  9cd4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1017):          9ddddddc  00000000  
D/CrashAnrDetector( 1017):          9ddddde0  00000000  
D/CrashAnrDetector( 1017):          9ddddde4  00000000  
D/CrashAnrDetector( 1017):          9ddddde8  00000003  
D/CrashAnrDetector( 1017):          9dddddec  000000aa  
D/CrashAnrDetector( 1017):          9dddddf0  0000006b  
D/CrashAnrDetector( 1017):          9dddddf4  0001416e  
D/CrashAnrDetector( 1017):          9dddddf8  00000000  
D/CrashAnrDetector( 1017):          9dddddfc  9dddde30  [stack:2624]
D/CrashAnrDetector( 1017):     #00  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1017):          ........  ........
D/CrashAnrDetector( 1017):     #01  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde04  00000000  
D/CrashAnrDetector( 1017):          9dddde08  9dddde78  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde0c  9dddde5c  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde10  9dddde48  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde14  00000000  
D/CrashAnrDetector( 1017):          9dddde18  9dddee94  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde1c  9d61a3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1017):          9dddde20  9dddde50  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde24  00000000  
D/CrashAnrDetector( 1017):          9dddde28  9dddde44  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde2c  9d44c184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1017):          9dddde30  00000000  
D/CrashAnrDetector( 1017):          9dddde34  00000000  
D/CrashAnrDetector( 1017):          9dddde38  b6f73de4  
D/CrashAnrDetector( 1017):          9dddde3c  00000000  
D/CrashAnrDetector( 1017):          9dddde40  9ddde1cc  [stack:2624]
D/CrashAnrDetector( 1017):          9dddde44  9d528b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1017):          9dddde48  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9dddde4c  b8adc500  [heap]
D/CrashAnrDetector( 1017):          9dddde50  b8bcbd18  [heap]
D/CrashAnrDetector( 1017):          9dddde54  00000001  
D/CrashAnrDetector( 1017):          9dddde58  9
D/CrashAnrDetector( 1017): processName:com.example.hello
D/CrashAnrDetector( 1017): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/SSRM:n  ( 1017): SIOP:: AP = 340
,I/ActivityManager( 1017): Killing 1393:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/RCPManagerService( 1017): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1017):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/RCPManagerService( 1017): BootReceiver.onReceive(): Starting RCP Proxy for user = null
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
E/RCPManagerService( 1017):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1017):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1017): [SO] activate (ident=0xb9a02d18, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb9a02d18, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/EnterpriseDeviceManagerService( 1017): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1017): runAdminUpdate
,D/EnterpriseUtils( 1017): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1017): nothing to selfUpdate
,V/ApplicationPolicy( 1017): boot completed - refreshWidgetStatus
,V/ApplicationPolicy( 1017): refresh widget status for user 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1393/cgroup.procs: No such file or directory
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap,.hero.accuweather
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 26,
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1],
,W/PhoneRestrictionPolicy( 1017): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1017): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
I/KnoxMUMContainerPolicy( 1017): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1017): cvList size 0
W/PhoneRestrictionPolicy( 1017):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1017): cvList size 0
,D/WifiP2pService( 1017): P2pDisabledState{ what=143415 }
D/WifiP2pService( 1017): DefaultState{ what=143415 }
,D/WIFI_P2P( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0,
,D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI_P2P,
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1017): Got NetworkFactory Messenger for WIFI
D/Tethering( 1017): Boot complete.
E/WifiStateMachine( 1017): Blacklist file delete
,V/EnterpriseBillingEngine( 1017): ACTION_BOOT_COMPLETED
,V/EnterpriseBillingEngine( 1017): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1017): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1017): handleAllprofiles - end
,D/UsbHostNotification( 1017): boot completed
,D/UsbHostRestrictor( 1017): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1017): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1017): SIM was never inserted
,D/UsbHostRestrictor( 1017): writableHostSysNode[false]
D/UsbHostRestrictor( 1017): Can NOT Write Disable Sys Node to [ON]
,D/SensorService( 1017): [SO] 0.096 0.383 10.094
D/SensorService( 1017): [SO] 0.096 0.383 10.094
,D/SensorService( 1017): [SO] [100 -> 255]
,D/WIFI    ( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/PersonaManagerService( 1017): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1017):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1017): onBootComplete
,D/UsbStorageNotification( 1017): boot completed
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_init 
,D/GpsLocationProvider( 1017): set_capabilities_callback: 55u
,I/KnoxKeyguardUpdateMonitor( 1017): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1017): onTrustChanged user:0, enable:false
,D/KeyguardViewMediator( 1176): onTrustChanged( Showing = false , userId = 0 )
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
I/libmdmdetect( 1017): ESOC framework not supported
,I/libmdmdetect( 1017): Found internal modem: modem
,E/PerMgrLib( 1017): Peripheral manager is not supported on this device
,D/qmi_secgps_clnt( 1017): qmi_secgps_client_init()
,E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_cleanup 
,D/StorageNotification( 1176): boot completed
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2,
,D/StatusBarManagerService( 1017): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ),
D/PhoneStatusBar( 1176): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/ActivityManager( 1017): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/Zygote  ( 2721): MountEmulatedStorage()
,E/Zygote  ( 2721): v2
,I/libpersona( 2721): KNOX_SDCARD checking this for 10099
I/libpersona( 2721): KNOX_SDCARD not a persona
,I/SELinux ( 2721): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2721 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2721): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2721): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2721): TimaSignature is unavailable
,D/ActivityThread( 2721): Added TimaKeyStore provider
,E/ActivityThread( 2721): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2721): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/ActivityManager( 1017): Killing 1559:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
I/System.out( 1017): start Service
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1233): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2738): MountEmulatedStorage()
,E/Zygote  ( 2738): v2
I/libpersona( 2738): KNOX_SDCARD checking this for 1000
I/libpersona( 2738): KNOX_SDCARD not a persona
,I/SELinux ( 2738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2738 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 2750): MountEmulatedStorage()
,E/Zygote  ( 2750): v2
I/libpersona( 2750): KNOX_SDCARD checking this for 10152
I/libpersona( 2750): KNOX_SDCARD not a persona
,I/SELinux ( 2750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,E/LocSvc_utils_cfg( 1017): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2750 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/ActivityManager( 1017): startService callerProcessName:android, calleePkgName: android
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,I/SELinux ( 2750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,D/TimaKeyStoreProvider( 2738): TimaSignature is unavailable
,D/ActivityThread( 2738): Added TimaKeyStore provider
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 2467
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 2467
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1017): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
,I/ANDROID_DRM_FRWORKS_DrmManager(  281): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,W/ResourcesManager( 2738): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2750): TimaSignature is unavailable
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
D/ActivityThread( 2750): Added TimaKeyStore provider
,D/MediaScannerReceiver( 1233): action: android.intent.action.BOOT_COMPLETED
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/BluetoothBDAdrressReceiver( 2738): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2738): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,W/ResourcesManager( 1448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1559/cgroup.procs: No such file or directory
,D/BluetoothBDTestService( 1448): onCreate()
,E/BluetoothBDTestService( 1448): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1448): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1448): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 2772): MountEmulatedStorage(),
I/libpersona( 2772): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 2772): v2
I/libpersona( 2772): KNOX_SDCARD not a persona
,I/SELinux ( 2772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2772 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1536:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,E/SQLiteLog( 2750): (284) automatic index on shooting_modes(title_id)
,E/CscReceiver( 1448): onReceive android.intent.action.BOOT_COMPLETED
I/SELinux ( 2772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2772): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CscUpdateService( 1448): onStart
,E/CscUpdateService( 1448): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1448): set_CSC_version
E/CscParser( 1448): update(): xml file exist
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/Zygote  ( 2788): MountEmulatedStorage()
I/libpersona( 2788): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2788): v2
I/libpersona( 2788): KNOX_SDCARD not a persona
,I/SELinux ( 2788): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,D/TimaKeyStoreProvider( 2772): TimaSignature is unavailable
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,D/ActivityThread( 2772): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2788 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 2788): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2788): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CscUtil ( 1448): isWifiOnly = false
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/System.out( 1448): HandDataNode = null
I/CscUpdateService( 1448): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1448): This is normal boot : CSC not updated
,D/ActivityManager( 1017): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,W/ResourcesManager( 2772): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1448): update(): xml file exist
,I/CscUpdateService( 1448): same CSC Version
D/CscUtil ( 1448): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,E/Zygote  ( 2808): MountEmulatedStorage()
E/Zygote  ( 2808): v2
I/libpersona( 2808): KNOX_SDCARD checking this for 1101
I/libpersona( 2808): KNOX_SDCARD not a persona
,I/SELinux ( 2808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/CscGPS  ( 1448): CSCGPS.updateParameters,
D/TimaKeyStoreProvider( 2788): TimaSignature is unavailable
D/CscGPS  ( 1448): supl host : null
D/CscGPS  ( 1448): SUPL Host is null or invalid
D/CscGPS  ( 1448): supl_ver : null
D/CscGPS  ( 1448): SUPL Ver is null or invalid
D/CscGPS  ( 1448): supl port : null
D/CscGPS  ( 1448): SUPL PORT is null or invalid
,D/CscGPS  ( 1448): LPP : null
D/CscGPS  ( 1448): LPP is null or invalid
D/CscGPS  ( 1448): CSC don't have any AGPS value.
D/ActivityThread( 2788): Added TimaKeyStore provider
,I/SELinux ( 2808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2808 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,I/ActivityManager( 1017): Killing 1794:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/KnoxUsageLogPro( 2772): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 8767(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 662us total 26.065ms
,D/TimaKeyStoreProvider( 2808): TimaSignature is unavailable
I/KnoxUsageLogPro( 2772): savePreference: key = previous_sys_time value = 1457591080017
,D/ActivityThread( 2808): Added TimaKeyStore provider
I/KnoxUsageLogPro( 2772): premStatus:2
,D/MediaScannerService( 1233): !@start scanning volume internal: [/system/media, /oem/media]
,I/KnoxUsageLogPro( 2772): isEulaShown : false
I/KnoxUsageLogPro( 2772): KnoxUsageReceiver onReceive : not Processible, just return
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 17.394ms,
,W/ResourcesManager( 2808): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 2772): savePreference: key = previous_elapsed_time value = 33220
,V/SmartcardService( 2808): main Received broadcast
V/SmartcardService( 2808): Starting smartcard service after boot completed
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.883ms
,E/Zygote  ( 2825): MountEmulatedStorage()
,E/Zygote  ( 2825): v2
I/libpersona( 2825): KNOX_SDCARD checking this for 10085
I/libpersona( 2825): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2825 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Killing 1585:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/SELinux ( 2825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1017): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
E/SELinux ( 2825): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
,D/ActivityManager( 1017): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/ActivityManager( 1017): Killing 2098:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/MtpService( 1233): updating state; isCurrentUser=true, mMtpLocked=false
D/ActivityManager( 1017): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 1233): (283) recovered 171 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/TimaKeyStoreProvider( 2825): TimaSignature is unavailable
,D/ActivityThread( 2825): Added TimaKeyStore provider
,E/Zygote  ( 2841): MountEmulatedStorage()
E/Zygote  ( 2841): v2
,I/libpersona( 2841): KNOX_SDCARD checking this for 10157
I/libpersona( 2841): KNOX_SDCARD not a persona
I/SELinux ( 2841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2841 uid=10157 gids={50157, 9997} abi=armeabi-v7a
E/SELinux ( 2841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1536/cgroup.procs: No such file or directory
,D/TP/MmsProvider( 1448): Update uri=content://mms, match=0
,D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
D/TP/MmsProvider( 1448): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ResourcesManager( 2825): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 2825): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
W/ResourcesManager( 2825): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Mms:transaction( 2286): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
W/ResourcesManager( 2825): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 2286): [start]    nonBlockingUpdateMessageIndicator() consume time = 2908.044687
W/ResourcesManager( 2825): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2825): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/Mms/ReservationManager( 2286): resetAfterConnected()
,D/TimaKeyStoreProvider( 2841): TimaSignature is unavailable
D/ActivityManager( 1017): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
D/ActivityThread( 2841): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/TP/MmsSmsProvider( 1448): query,matched:7, calling pid = 2286
,D/TP/MmsSmsProvider( 1448): match 7:Elapsed time : 3.174 ms
,D/Mms/MessagingNotification( 2286): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2286): isDefault true
,D/MediaScanner( 1233): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/MmsProvider( 1448): Query uri=content://mms, match=0, calling pid = 2286
I/Mms/ReservationManager( 2286): getReservedSendMessageCount(): retMessageCount=0
D/ActivityManager( 1017): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/PackageManager( 1017): [MSG] MCS_UNBIND
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SecureStorage( 2788): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1794/cgroup.procs: No such file or directory
,E/Zygote  ( 2862): MountEmulatedStorage()
E/Zygote  ( 2862): v2
I/libpersona( 2862): KNOX_SDCARD checking this for 10048
I/libpersona( 2862): KNOX_SDCARD not a persona
,I/SELinux ( 2862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2862): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaScanner( 1233): processDirectory :  /system/media
,I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2862 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_10107/pid_1585/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2098/cgroup.procs: No such file or directory
,I/SecureStorage( 2788): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SecureStorage(  392): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2788
I/SecureStorage(  392): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2788): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2788): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  392): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2788
I/SecureStorage(  392): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,E/Zygote  ( 2876): MountEmulatedStorage()
I/libpersona( 2876): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2876): v2
I/libpersona( 2876): KNOX_SDCARD not a persona
I/SELinux ( 2876): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2876): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2876): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2862): TimaSignature is unavailable
D/ActivityThread( 2862): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1448): query,matched:200, calling pid = 2286
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
D/TP/MmsSmsProvider( 1448): match 200:Elapsed time : 1.353 ms
V/MediaScanner( 1233):  prescan time: 140ms (DB items: 141)
V/MediaScanner( 1233):     scan time: 81ms (Caching mode: true), (makeEntry time: 33ms ~40%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1233): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1233):    total time: 221ms
V/MediaScanner( 1233): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1233): checkDefaultSounds
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1233): system alarm_alert  : Vwiurug_etwofi5wgg
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2862): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2862): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2862): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2876): TimaSignature is unavailable
D/ActivityThread( 2876): Added TimaKeyStore provider
E/Zygote  ( 2894): MountEmulatedStorage()
E/Zygote  ( 2894): v2
I/libpersona( 2894): KNOX_SDCARD checking this for 10159
I/libpersona( 2894): KNOX_SDCARD not a persona
I/SELinux ( 2894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2894 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1489:com.android.printspooler/u0a136 (adj 15): empty #31
I/SELinux ( 2894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2894): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2286): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2286): isDefault true
D/Mms/SmsReceiverService( 2286): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2286): [start]    handleBootCompleted() consume time = 188.879166
,D/MediaScanner( 1233): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1233): system notification_sound  : K_Oprkltf5wgg
,D/TimaKeyStoreProvider( 2894): TimaSignature is unavailable
D/ActivityThread( 2894): Added TimaKeyStore provider
,D/MediaScanner( 1233): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1233): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1233): OK. ringtone is already exist in setting DB.
,D/TP/MmsSmsProvider( 1448): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1448): deleteConversation threadId: 9223372036854775806
,D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2286
,D/FactoryTestApp( 2619): [DummyFtClient$mBroadcastReceiver](2619) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 1233): !@done scanning volume internal
D/FactoryTestApp( 2619): [DummyFtClient$mBroadcastReceiver](2619) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2619): [DummyFtClient$mBroadcastReceiver](2619) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/TP/SmsProvider( 1448): match 0:Elapsed time : 11.018 ms
,D/TP/MmsSmsProvider( 1448): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1448): updateThread(), thread_id = 9223372036854775806
,D/MediaScannerService( 1233): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/TP/SmsProvider( 1448): query,matched:51, calling pid = 2286
,D/TP/SmsProvider( 1448): match 51:Elapsed time : 2.706 ms
,V/TP/MmsSmsDatabaseHelper( 1448): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id),
E/SQLiteLog( 1448): (284) automatic index on im_threads(normal_thread_id)
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
D/SettingsProvider( 1017): name = block_emergency_message
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1489/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1448): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
,W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/Mms/Conversation( 2286): deleteTempConversation(),deleted=0
,I/Intent to TravelDirActivity( 2894): inside TravelBroadcastReceiver
,D/Mms/MessagingNotification( 2286): isBlockingModeEnabled() = false, Zen mode = 0
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter started
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SmsProvider( 1448): Update uri=content://sms/outbox, match=8
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1448): need read changed broadcast:false
,E/Zygote  ( 2911): MountEmulatedStorage()
E/Zygote  ( 2911): v2
I/libpersona( 2911): KNOX_SDCARD checking this for 1000
I/libpersona( 2911): KNOX_SDCARD not a persona
E/USB_UICC(  295): Timeout! No signal received. Retry num = 27
I/SELinux ( 2911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/SQLiteLog( 2876): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
I/SELinux ( 2911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2911): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2911 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2126:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,D/ActivityManager( 1017): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/Mms/SmsReceiverService( 2286): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2286): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2286): [SIM-1]sendFirstQueuedMessage()
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1233): savePlaylistTableInBulkDeleter finished
,I/WifiCredService( 1293): onCreate
E/Zygote  ( 2926): MountEmulatedStorage(),
E/Zygote  ( 2926): v2
I/libpersona( 2926): KNOX_SDCARD checking this for 10072
I/libpersona( 2926): KNOX_SDCARD not a persona
,I/SELinux ( 2926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/DSM     ( 2876): [Lines:107] Normal booted
D/DSM     ( 2876): [Lines:114] Boot completed
,D/TimaKeyStoreProvider( 2911): TimaSignature is unavailable
D/ActivityThread( 2911): Added TimaKeyStore provider
I/SELinux ( 2926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=2926 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/SELinux ( 2926): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/MediaScanner( 1233): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/SmsProvider( 1448): query,matched:26, calling pid = 2286
,D/TP/SmsProvider( 1448): match 26:Elapsed time : 3.553 ms
,D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,D/WifiTimerReceiver( 1293): action: android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/WifiTimerReceiver( 1293): extra: Bundle[mParcelledData.dataSize=84]
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/MY_TAG  ( 1293): Action boot completed received
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2926): TimaSignature is unavailable
,D/ActivityThread( 2926): Added TimaKeyStore provider
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,E/Zygote  ( 2944): MountEmulatedStorage()
I/libpersona( 2944): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2944): v2
I/libpersona( 2944): KNOX_SDCARD not a persona
I/SELinux ( 2944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2944 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2189:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2126/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2944): TimaSignature is unavailable
D/ActivityThread( 2944): Added TimaKeyStore provider
,W/art     ( 2825): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 142.277ms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 39104(2MB) AllocSpace objects, 29(1732KB) LOS objects, 33% free, 26MB/39MB, paused 2.600ms total 172.751ms,
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2189/cgroup.procs: No such file or directory
,E/Zygote  ( 2960): MountEmulatedStorage(),
E/Zygote  ( 2960): v2
I/libpersona( 2960): KNOX_SDCARD checking this for 10160
I/libpersona( 2960): KNOX_SDCARD not a persona,
,I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2960 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 2960): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2960): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,V/MediaScanner( 1233): processDirectory :  /storage/emulated/0
,I/ActivityManager( 1017): Killing 1622:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/BadgeProvider( 2926): onCreate
,D/BadgeProvider( 2926): DatabaseHelper
,E/SELinux ( 2960): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 2944): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/MediaScanner( 1233): Skipping:
D/MediaScanner( 1233): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 1233): Skipping:
D/MediaScanner( 1233): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/TimaKeyStoreProvider( 2960): TimaSignature is unavailable
,D/ActivityThread( 2960): Added TimaKeyStore provider
,D/BadgeProvider( 2926): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/Mms/SmsReceiver( 2286): unregisterForServiceStateChanges, already unregistered
,D/Mms/MessagingNotification( 2286): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2286): isDefault true
,V/MediaScanner( 1233): processDirectory :  /storage/extSdCard
W/MediaScanner( 1233): Error opening directory, reason : Permission denied.
W/MediaScanner( 1233): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1233):  prescan time: 253ms (DB items: 27)
V/MediaScanner( 1233):     scan time: 52ms (Caching mode: true), (makeEntry time: 21ms ~40%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 1ms ~1%)
V/MediaScanner( 1233): postscan time: 5ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1233):    total time: 310ms
V/MediaScanner( 1233): checked files: 10  directories : 17  (I: 0, U: 0)
,D/TP/MmsProvider( 1448): Query uri=content://mms, match=0, calling pid = 2286
,D/MediaScannerService( 1233): !@done scanning volume external
,D/FactoryTestApp( 2619): [DummyFtClient$mBroadcastReceiver](2619) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,D/BadgeProvider( 2926): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2926): sendNotify, [notify] : null
D/BadgeProvider( 2926): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2926): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2926): update, [UpdateCount] : 1
,D/Launcher.Model( 1473): reloadBadges entered.
,D/FactoryTestApp( 2619): [DummyFtClient$mBroadcastReceiver](2619) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2619): [DummyFtClient$sendBootCompletedAndFinish](2619) ...
D/Mms/MessagingNotification( 2286): setBadgeCount(), count=0
,W/ActivityThread( 2944): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2619): [Support$Values.getString](2619) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2619): [ModuleCommon$isConnectionModeNone](2619) mConnectionMode = gsm
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
I/ActivityManager( 1017): Killing 2268:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,D/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$ResponseWriter](2619) Create IPCWriterToSecPhoneService
,D/Mms/MessagingNotification( 2286): remove alarm
I/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$connectToSecPhoneService](2619)  
,W/ContextImpl( 2619): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/NearbySettings( 1293): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1293): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1293): MountReceiver.onReceive - Create mPrefHandler
D/ActivityManager( 1017): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,W/ResourcesManager( 2960): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/NearbySettings( 1293): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{1b35f98b u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,V/NearbySettings( 1293): MountReceiver.mPrefHandler - 7002
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/NearbySettings( 1293): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,I/NearbySettings( 1293): MountReceiver.onReceive - Internal Path
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2286
,D/TP/SmsProvider( 1448): match 0:Elapsed time : 4.021 ms
,I/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$onServiceConnected](2619) connected done
,D/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$write](2619) Send Response Message to SecPhone
D/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$write](2619) Response ��
,D/Mms/MessagingNotification( 2286): [end]    nonBlockingUpdateMessageIndicator() consume time = 527.706198
,D/SettingsProvider( 1017): name = personal_mode_enabled
,D/Mms/MessagingNotification( 2286): updateAllHistoryAsRead()
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/AT_Distributor(  313): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$handleMessage](2619) Send BOOTING COMPLETED done
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 2944): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1622/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2268/cgroup.procs: No such file or directory
,D/TP/MmsSmsProvider( 1448): query,matched:200, calling pid = 2286
,D/TP/MmsSmsProvider( 1448): match 200:Elapsed time : 3.005 ms
,I/LcdtestApp( 2944): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2983): MountEmulatedStorage()
,E/Zygote  ( 2983): v2,
I/libpersona( 2983): KNOX_SDCARD checking this for 1000
I/libpersona( 2983): KNOX_SDCARD not a persona
,I/SELinux ( 2983): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2983 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2983): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2983): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 1448): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1448): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1448): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2983): TimaSignature is unavailable
,D/ActivityThread( 2983): Added TimaKeyStore provider
,I/SmartcardBootCompleteReceiver( 1293): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1293): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/[0]UMC:UMCContentProvider( 2960): @onCreate
,W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SmartcardBootCompleteReceiver( 1293): Broadcast sent with current lockscreen type
,D/AT_Distributor(  313): SetAtdStatus(), 1_1_0,
D/AT_Distributor(  313): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
I/SecureStorage(  392): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2286
,D/TP/SmsProvider( 1448): match 0:Elapsed time : 1.996 ms
,D/[0]UMC:Core( 2960): onCreate(): 
D/[0]UMC:Core( 2960): @isManagedProfileUser
D/[0]UMC:Core( 2960): userId: 0
,D/[0]UMC:Core( 2960): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2960): userInfo.isManagedProfile() : false
,I/SecureStorage( 2788): [INFO]: SPID(0x00000001)Processing data has been completed
,I/SecureStorage( 2788): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
,I/art     ( 1448): Background sticky concurrent mark sweep GC freed 39284(2MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 8MB/11MB, paused 957us total 120.557ms
I/art     ( 1448): WaitForGcToComplete blocked for 15.454ms for cause Explicit
,D/[0]UMC:DeviceInfo( 2960): USA==US==
,I/art     ( 1448): Explicit concurrent mark sweep GC freed 2095(106KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 943us total 38.839ms
,D/TP/SmsProvider( 1448): query,matched:51, calling pid = 2286
,D/TP/SmsProvider( 1448): match 51:Elapsed time : 0.853 ms
,D/Mms/MessagingNotification( 2286): isBlockingModeEnabled() = false, Zen mode = 0
,D/BadgeProvider( 2926): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/[SBeam] ( 1293): SBeamEnabler.initPreferenceForSbeam : 0
,I/DIAGMON_AGENT( 2983): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/SettingSearch/SearchIntentReceiver( 1293): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1293): search setting db init!!
,W/ContextImpl( 1293): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/SettingSearch/SearchIntentReceiver( 1293): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3001): MountEmulatedStorage(),
I/libpersona( 3001): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3001): v2
I/libpersona( 3001): KNOX_SDCARD not a persona
,I/SELinux ( 3001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     (  309): Explicit concurrent mark sweep GC freed 8749(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 21.236ms
,D/TimaKeyStoreProvider( 3001): TimaSignature is unavailable
,D/ActivityThread( 3001): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 977us total 19.851ms
D/Launcher.Model( 1473): reloadBadges entered.
,D/BadgeProvider( 2926): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 2926): sendNotify, [notify] : null
D/BadgeProvider( 2926): update, [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 2926): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2926): update, [UpdateCount] : 1
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 40.995ms
,E/Zygote  ( 3016): MountEmulatedStorage(),
E/Zygote  ( 3016): v2
I/libpersona( 3016): KNOX_SDCARD checking this for 10150
I/libpersona( 3016): KNOX_SDCARD not a persona
,I/SELinux ( 3016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3016): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3016 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,D/Mms/MessagingNotification( 2286): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2286): remove alarm
,D/TimaKeyStoreProvider( 3016): TimaSignature is unavailable
,D/ActivityThread( 3016): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2286): updateAllHistoryAsRead()
,D/USER_AGENT( 2960): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,W/ResourcesManager( 3001): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1448): query,matched:0, calling pid = 2286
,D/TP/SmsProvider( 1448): match 0:Elapsed time : 14.836 ms
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/Mms/SmsReceiverService( 2286): [end]    handleBootCompleted() consume time = 543.274166
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1017): Killing 2302:com.sec.android.omc/1000 (adj 15): empty #31
,D/[0]UMC:AdminManager( 2960): init - start
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 28
,D/[0]UMC:AdminManager( 2960): loadAdmins
,D/[0]UMC:AdminManager( 2960): init - end
,D/GSLBManager( 2960): migrateStoredUrlFromOldPref
,D/GSLBManager( 2960): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 2960): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2960): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2960): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2960): deactivateUMCAdmin : -1
,D/[0]UMC:UMCAdmin( 2960): isContainer : 0
,I/FOTA    ( 3001): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2960): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2960): isContainer : 0
,D/[0]UMC:UMCAdmin( 2960): deactivateUMCAdmin - UMC App Admin deactivated
,D/ActivityManager( 1017): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms,
D/[0]UMC:GuardService( 2960): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 2960): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2960):  check PreETag 
,I/DIAGMON_AGENT( 2983): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 2983): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2302/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 2983): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED,
,E/Zygote  ( 3039): MountEmulatedStorage()
I/libpersona( 3039): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3039): v2
I/libpersona( 3039): KNOX_SDCARD not a persona
I/SELinux ( 3039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DIAGMON_AGENT( 2983): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/DIAGMON_AGENT( 2983): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/SELinux ( 3039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/DIAGMON_AGENT( 2983): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
E/SELinux ( 3039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 2333:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3039): TimaSignature is unavailable
D/ActivityThread( 3039): Added TimaKeyStore provider
,D/[0]UMC:CoreReceiver( 2960): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2960): Enter loadList
,D/[0]UMC:CoreReceiver( 2960): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2960): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2960): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2960): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2960): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2960): isContainer : 0
,W/ResourcesManager( 3039): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2960): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2960): isContainer : 0
D/[0]UMC:UMCAdmin( 2960): deactivateUMCAdmin - UMC App Admin deactivated
,D/[0]UMC:ByodSetupStarter( 2960): Container ID : 0
,V/[0]UMC:Utils( 2960): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2960): shutdown
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2960): @GuardService - stopService Result = true
,I/art     ( 2960): System.exit called, status: 0
,I/AndroidRuntime( 2960): VM exiting with result code 0, cleanup skipped.
,W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2333/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3057): MountEmulatedStorage()
E/Zygote  ( 3057): v2
I/libpersona( 3057): KNOX_SDCARD checking this for 10086
I/libpersona( 3057): KNOX_SDCARD not a persona
,I/SELinux ( 3057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3057 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2348:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,I/SELinux ( 3057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3057): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3057): TimaSignature is unavailable
,D/ActivityThread( 3057): Added TimaKeyStore provider
,E/Zygote  ( 3072): MountEmulatedStorage()
,E/Zygote  ( 3072): v2
I/libpersona( 3072): KNOX_SDCARD checking this for 1000
I/libpersona( 3072): KNOX_SDCARD not a persona
,I/SELinux ( 3072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3072 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3072): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2255:com.sec.android.app.mt/1000 (adj 15): empty #31
,E/BluetoothHeadset( 2788): BTStateChangeCB is registed
,I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2960)(adj 0) has died(320,979)
,D/BluetoothHeadset( 2788): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1017): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
E/BluetoothHeadset( 2788): BluetoothHeadset service is binded
,D/BluetoothA2dp( 2788): doBind(): CallingUid(myUserHandle) = 0
D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/DBG_DM  ( 3001): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,D/TimaKeyStoreProvider( 3072): TimaSignature is unavailable
W/ContextImpl( 3001): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityThread( 3072): Added TimaKeyStore provider
D/ActivityManager( 1017): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/ActivityManager( 1017): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/comsamsunglog( 1319): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1319): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1319): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1319): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1319): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/BluetoothAdapter( 2788): 542930464: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2788): 542930464: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2788): 542930464: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2788): 542930464: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2788): 542930464: getState() :  mService = null. Returning STATE_OFF
,D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10162
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2348/cgroup.procs: No such file or directory
I/DBG_DM  ( 3001): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2255/cgroup.procs: No such file or directory
,D/OverheatReceiver( 1176): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1176): into the SAFE_MODE_ACTION
I/DBG_DM  ( 3001): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
D/OverheatReceiver( 1176): VZW on -> change to Global UX [safe mode]
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,E/Tethering( 1017): No numeric data
,I/DBG_DM  ( 3001): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
D/OverheatReceiver( 1176): isSafeMode = false
,I/DBG_DM  ( 3001): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,E/Tethering( 1017): No numeric data
I/DBG_DM  ( 3001): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/BootupListener( 1448): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
E/Tethering( 1017): No numeric data
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1448): isSupportVoLTE is false.
D/daemonapp( 1319): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
E/Tethering( 1017): No numeric data
I/Telecom ( 1426): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3001): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1319): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/ActivityManager( 1017): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
D/ActivityManager( 1017): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,E/Tethering( 1017): No numeric data
,I/DBG_DM  ( 3001): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 3001): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,E/daemonapp( 1319): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/Tethering( 1017): No numeric data
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457591081843
,D/daemonapp( 1319): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457612640000
D/daemonapp( 1319): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1319): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,E/Zygote  ( 3089): MountEmulatedStorage()
,E/Zygote  ( 3089): v2
I/libpersona( 3089): KNOX_SDCARD checking this for 10057
,I/libpersona( 3089): KNOX_SDCARD not a persona
I/SELinux ( 3089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3089 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/SELinux ( 3089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3089): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
,D/BluetoothAdapter( 2386): disable(),
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/daemonapp( 1319): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457612640000
,E/BluetoothManagerService( 1017): Bluetooth is already disabled. DO NOT disable again.
,I/Telecom ( 1426): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,D/daemonapp( 1319): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
I/DBG_DM  ( 3001): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/daemonapp( 1319): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457612640000
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/TimaKeyStoreProvider( 3089): TimaSignature is unavailable
D/ActivityThread( 3089): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 3057): ignoring update request
,D/WifiService( 1017): setWifiEnabled: false pid=2386, uid=10174
,D/SettingsProvider( 1017): name = wifi_on
,I/DBG_DM  ( 3001): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,I/jxcore-log( 2386): ****TEST TOOK:  5106  ms ****
I/jxcore-log( 2386): 
,I/jxcore-log( 2386): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2386): 
,D/comdaemonstockapp( 1319): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1319): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3109): MountEmulatedStorage()
E/Zygote  ( 3109): v2
I/libpersona( 3109): KNOX_SDCARD checking this for 10166
I/libpersona( 3109): KNOX_SDCARD not a persona
,I/SELinux ( 3109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1017): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3109 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3109): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/UpdateRequestReceiver( 3057): ignoring update request
,D/[SBeam] ( 1293): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1293): SBeamEnabler.isSBeamSupported : EXIST
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1017): No numeric data
,D/TimaKeyStoreProvider( 3109): TimaSignature is unavailable
E/Tethering( 1017): No numeric data
D/ActivityThread( 3109): Added TimaKeyStore provider
,E/Zygote  ( 3132): MountEmulatedStorage()
I/libpersona( 3132): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3132): v2
I/libpersona( 3132): KNOX_SDCARD not a persona
,I/SELinux ( 3132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/Tethering( 1017): No numeric data
E/UpdateRequestReceiver( 3057): ignoring update request
I/SELinux ( 3132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3132): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3132 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,V/audio_hw_primary(  282): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  282): audio_extn_get_parameters: returns 
V/msm8974_platform(  282): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  282): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  282): key: 'call_forwarding' value: ''
,V/InCall  ( 1937): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1937): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1937): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/Tethering( 1017): No numeric data
,D/ScoverManager( 1937): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1937): InCallUtils - isCoverClosed false
,I/Telecom ( 1426): ProximitySensorManager: Proximity wake lock already released
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1937): InCallUtils - isCoverClosed false
I/InCall  ( 1937): InCallPresenter -  - InCallState = NO_CALLS
,D/TimaKeyStoreProvider( 3132): TimaSignature is unavailable
D/ActivityThread( 3132): Added TimaKeyStore provider
,I/InCall  ( 1937): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1937): InCallPresenter -  - dismissCoverDialog()...
,E/UpdateRequestReceiver( 3057): ignoring update request
,I/InCall  ( 1937): CallSContextMotion - stopPutDownListening
D/InCall  ( 1937): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
E/UpdateRequestReceiver( 3057): ignoring update request
,I/DBG_POLICYDM( 3072): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3072): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/PhoneStatusBarView( 1176): setCallBackground:0
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/DBG_DM  ( 3001): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/UpdateRequestReceiver( 3057): ignoring update request
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/InCall  ( 1937): InCallUtils - isCoverClosed false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/NotificationAccessSettings( 1293): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/DBG_POLICYDM( 3072): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/DBG_POLICYDM( 3072): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,E/Zygote  ( 3157): MountEmulatedStorage(),
V/VibratorService( 1017): hasVibrator - useVibetonz: true
E/Zygote  ( 3157): v2
I/ActivityManager( 1017): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3157 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/libpersona( 3157): KNOX_SDCARD checking this for 10092
I/libpersona( 3157): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Killing 2405:com.wsomacp/u0a25 (adj 15): empty #31,
,I/SELinux ( 3157): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,W/ResourcesManager( 1293): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,I/SELinux ( 3157): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3157): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3072): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3072): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/TimaKeyStoreProvider( 3157): TimaSignature is unavailable
,D/ActivityThread( 3157): Added TimaKeyStore provider
I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_DM  ( 3001): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_DM  ( 3001): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3001): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3072): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/AndroidRuntime( 3135): 
D/AndroidRuntime( 3135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3135): CheckJNI is OFF
,D/AndroidRuntime( 3135): readGMSProperty: start
D/AndroidRuntime( 3135): readGMSProperty: already setted!!
D/AndroidRuntime( 3135): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3135): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3135): readGMSProperty: end
D/AndroidRuntime( 3135): addProductProperty: start
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2405/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3176): MountEmulatedStorage(),
E/Zygote  ( 3176): v2
I/libpersona( 3176): KNOX_SDCARD checking this for 10015
I/libpersona( 3176): KNOX_SDCARD not a persona
,I/SELinux ( 3176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1017): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3176 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3176): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/VideoCallManager( 1937): Instantiating VideoCallManager,
,E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1937): took 2.427344ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1937): took 5.205260ms for 0*0 texture 0
,D/LocationManagerService( 1017): getProviders()=[passive]
,D/TimaKeyStoreProvider( 3176): TimaSignature is unavailable
I/GFX raster( 1937): took 11.576876ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb92e30d0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb92ca598 counterpartCT=4 counterpartW=176 counterparth=144
,D/ActivityThread( 3176): Added TimaKeyStore provider
,E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/Adreno-EGL( 1937): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1937): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1937): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1937): Local Branch: 
I/Adreno-EGL( 1937): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1937): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1937):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/GFX GPU raster( 1937): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1937): took 0.249531ms for 320*61440 texture 37809
,I/draw setup( 1937): took 10.014844ms for 320*240 texture 37809
E/GFX GPU raster( 1937): drawn
,I/GFX GPU raster ASTC( 1937): took 39.523853ms for 320*240 texture 12
I/GFX raster( 1937): took 39.594842ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb92ca3d0 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb92ca5b8 counterpartCT=4 counterpartW=320 counterparth=240
,E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1937): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1937): took 0.283125ms for 480*122880 texture 37813
I/draw setup( 1937): took 0.607552ms for 480*640 texture 37813
E/GFX GPU raster( 1937): drawn
,I/GFX GPU raster ASTC( 1937): took 6.942603ms for 480*640 texture 12
I/GFX raster( 1937): took 6.999843ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb92ca5b8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb9511e40 counterpartCT=4 counterpartW=480 counterparth=640
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/AffinityControl( 3135): AffinityControl: registerfunction enter
,D/AndroidRuntime( 3135): Calling main entry com.android.commands.pm.Pm
E/USB_UICC(  295): Timeout! No signal received. Retry num = 29
E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1937): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1937): took 0.585885ms for 440*116864 texture 37809,
I/draw setup( 1937): took 1.141198ms for 440*330 texture 37809
E/GFX GPU raster( 1937): drawn
,I/GFX GPU raster ASTC( 1937): took 5.334688ms for 440*330 texture 12
I/GFX raster( 1937): took 5.414948ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb9511e40 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb9526230 counterpartCT=4 counterpartW=440 counterparth=330
,D/PackageManager( 1017): START PACKAGE DELETE: observer{381621460}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
,D/ScoverManager( 1293): serviceVersion : 16908288
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10174, uninstall pkg
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 2386:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,W/ActivityManager( 1017): Force removing ActivityRecord{1871f09f u0 com.example.hello/.MainActivity t10}: app died, no saved state
,D/FocusedStackFrame( 1017): Set to : 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,D/InputDispatcher( 1017): Focus left window: 2386
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1937): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1937): took 0.530417ms for 480*163840 texture 37811
I/draw setup( 1937): took 0.856927ms for 480*640 texture 37811
E/GFX GPU raster( 1937): drawn
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/GFX GPU raster ASTC( 1937): took 5.812032ms for 480*640 texture 12,
I/GFX raster( 1937): took 5.882032ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb9516040 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb92d0cf8 counterpartCT=4 counterpartW=480 counterparth=640
,E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,W/PackageSettings( 1017): Skipping PackageSetting{442b8cd com.test.thalitest/10155} due to missing metadata
,I/GFX construct_block_size_descriptor_2d second part( 1937): took 2.607292ms for 0*0 texture 0
,I/DBG_POLICYDM( 3072): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3072): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/GFX generate_partition_tables( 1937): took 8.093177ms for 0*0 texture 0
,I/GFX raster( 1937): took 13.080313ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb950f700 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb950f820 counterpartCT=4 counterpartW=176 counterparth=144
,E/DBG_POLICYDM( 3072): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/        ( 1937): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1937): took 2.381406ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1937): took 6.025469ms for 0*0 texture 0
,I/GFX raster( 1937): took 10.529739ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1937): Bitmap=0xb950fa40 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb950f9e0 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1937): registerListener
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@17aca67d, pid : 1937, uid : 1001, type : 1
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/Launcher( 1473): onRestart, Launcher: 767732308
,D/Launcher( 1473): onStart, Launcher: 767732308
D/Launcher.HomeView( 1473): onStart
,D/Launcher( 1473): onResume, Launcher: 767732308
I/ActivityManager( 1017): Killing 2482:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1473): onResume
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=0: pkg removed
D/InCall  ( 1937): InCallPresenter -  - Finished InCallPresenter.setUp
,D/Launcher( 1473): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ResourcesManager( 3109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/JavaBinder( 1017): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/MenuAppsGridFragment( 1473): onResume
,D/ActivityManager( 1017): handle home activity for 0
,I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/ActivityManager( 1017): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 1473
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 1473): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/Launcher( 1473): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 2386 uid 10174
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1176): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1176): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,I/Timeline( 1473): Timeline: Activity_idle id: android.os.BinderProxy@25feca8a time:36021,
,D/SamsungIME( 1818): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,W/libprocessgroup( 1017): failed to open /acct/uid_10088/pid_2482/cgroup.procs: No such file or directory
,E/SamsungIME( 1818): mOCRHelper is null
,W/GeofencerStateMachine( 1803): Ignoring removeGeofence because network location is disabled.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
W/ResourcesManager( 1448): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/TRThreadPoolExecutor( 3089): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3089): Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3089): Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/JNIHelp ( 3109): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SearchServiceFactory( 3089): refreshing search history.,
,E/Zygote  ( 3230): MountEmulatedStorage()
,E/Zygote  ( 3230): v2
I/libpersona( 3230): KNOX_SDCARD checking this for 10003
I/libpersona( 3230): KNOX_SDCARD not a persona
I/SELinux ( 3230): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 23570(1702KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 26MB/39MB, paused 6.329ms total 284.356ms
,I/SELinux ( 3230): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,V/AlarmManager( 1017): waitForAlarm result :8
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3230 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1017): [SO] activate (ident=0xb9a02d18, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/SELinux ( 3230): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RegisteredComponentCache( 1435): Collect Tech packages for Knox
,I/art     ( 1017): WaitForGcToComplete blocked for 213.842ms for cause Explicit
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,I/ActivityManager( 1017): Displayed Component not be shown by security: +363ms
,D/SensorService( 1017): [SO] changed settle time [0]
,D/SensorService( 1017): [SO] setDelay [200000000]
,D/SensorService( 1017): [SO] activate (ident=0xb9683858, enabled=1)
,D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1435): isKioskContainerExistOnDevice
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/TimaKeyStoreProvider( 3230): TimaSignature is unavailable
,D/ActivityThread( 3230): Added TimaKeyStore provider
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityThread( 3109): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3109): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3709a750: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3109): Installed default security provider GmsCore_OpenSSL
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/ActivityManager( 1017): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3249): MountEmulatedStorage(),
E/Zygote  ( 3249): v2
I/libpersona( 3249): KNOX_SDCARD checking this for 10092,
I/libpersona( 3249): KNOX_SDCARD not a persona
,I/SELinux ( 3249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1017): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3249 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 3249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3249): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  309): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 24.308ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.201ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 20.115ms
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3157): Setting receiver enabled: false
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,D/PersonaManager( 1435): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1435): empty dynamic service
,I/DBG_DM  ( 3001): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,D/TimaKeyStoreProvider( 3249): TimaSignature is unavailable
,D/ActivityThread( 3249): Added TimaKeyStore provider
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{206ba7f5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:36495
,D/UserAnalysis.PlaceProvider( 3230): PlaceProvider onCreate()
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,E/Zygote  ( 3273): MountEmulatedStorage()
,E/Zygote  ( 3273): v2,
I/libpersona( 3273): KNOX_SDCARD checking this for 1000
I/libpersona( 3273): KNOX_SDCARD not a persona
,I/SELinux ( 3273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3273 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UserAnalysis.SecureDbManager( 3230): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3230): SecurePlaceDbHelper() 
D/UserAnalysis( 3230): Create SecureDbHelper
,I/ActivityManager( 1017): Killing 2495:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2468:com.sec.android.gallery3d/u0a44 (adj 15): empty #32
,E/ActivityThread( 3157): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 3273): TimaSignature is unavailable
,D/ActivityThread( 3273): Added TimaKeyStore provider
,D/SensorService( 1017): [SO] currT = 36630094047, prevT = 36150080350, diff = 480013697, [0.096 0.383 10.113]
D/SensorService( 1017): [SO] 0.096 0.383 10.113
D/SensorService( 1017): [SO] [100 -> 255]
,D/IntelligenceServiceApplication( 3230): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3230): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,I/dbxyzptlk.db240408.D.h( 3157): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  295): Timeout! No signal received. Retry num = 30
,I/dbxyzptlk.db240408.D.h( 3157): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3157): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/IntelligenceServiceApplication( 3230): no applications having user consent for prediction
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 3289): MountEmulatedStorage()
I/libpersona( 3289): KNOX_SDCARD checking this for 10060
E/Zygote  ( 3289): v2
I/libpersona( 3289): KNOX_SDCARD not a persona
,I/SELinux ( 3289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/dbxyzptlk.db240408.D.h( 3157): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/SELinux ( 3289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3289 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/RCPManagerService( 1017): PackageReceiver onReceive(),
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/ActivityManager( 1017): Killing 2526:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3230): [PlaceDetection::stopService] Service stopped.
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/TimaKeyStoreProvider( 3289): TimaSignature is unavailable
,D/ActivityThread( 3289): Added TimaKeyStore provider
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/AlarmManagerEXT( 1017): com.example.hello(10174) is removed.
D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=10_task.xml
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/USB_UICC(  295): Timeout! No signal received. Reach maximum retries!
,E/USB_UICC(  295): usb_uicc_init_qmi failed ! 
I/USB_UICC(  295): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  295): usb_uicc_cleanup, Issuing QMI deinit ... 
V/PlaceDetection v1.0.19 ( 3230): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3230): Constructor Preference
,D/breakpad( 3157): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/ActivityManager( 1017): Killing 2580:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/WebViewFactory( 3089): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/DBG_FMMDM( 3273): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_FMMDM( 3273): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3273): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3273): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,I/LockPatternUtils( 1293): isSmartCardAuthenticationAvailable: false
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/com.dropbox.sync.android.a( 3157): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Settings_Utils( 1293): isSupportVNFestival SM-A500FU XEO
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1017): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 3089): Time to load native libraries: 3 ms (timestamps 6925-6928)
I/LibraryLoader( 3089): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 3317): MountEmulatedStorage()
,E/Zygote  ( 3317): v2
I/libpersona( 3317): KNOX_SDCARD checking this for 1000
I/libpersona( 3317): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3317 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3317): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/art     ( 3089): Attempt to remove local handle scope entry from IRT, ignoring
,W/TRThreadPoolExecutor( 3089): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/TimaKeyStoreProvider( 3317): TimaSignature is unavailable
,D/ActivityThread( 3317): Added TimaKeyStore provider
,I/com.dropbox.sync.android.ad( 3157): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,I/sCloudBackupApp( 3289): sCloudBackupApp Version Info : 4.04.8.KK_APP
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_2468/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_2495/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2526/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2580/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_LOG( 3317): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3317): DEFAULT_LOGLEVEL : 3
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 19469(1029KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 6.779ms total 844.611ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Choreographer( 1473): Skipped 56 frames!  The application may be doing too much work on its main thread.
,D/WallpaperManager( 1473): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1473): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,E/Zygote  ( 3337): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3337 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3337): v2
I/ActivityManager( 1017): Killing 2565:com.android.calendar/u0a135 (adj 15): empty #31
I/libpersona( 3337): KNOX_SDCARD checking this for 10062
I/libpersona( 3337): KNOX_SDCARD not a persona
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3317): new DMDBOpenHelper instance
I/SELinux ( 3337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FactoryTestApp( 2619): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2981)  
,D/PCWCLIENTTRACE_DMContentProvider( 3317): [URIMatcher] - result : 2
,I/ActivityManager( 1017): Killing 2056:com.google.android.gms/u0a12 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3337): TimaSignature is unavailable
,D/ActivityThread( 3337): Added TimaKeyStore provider
,I/DBG_FMMDM( 3273): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3273): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3273): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3354): MountEmulatedStorage()
E/Zygote  ( 3354): v2
I/libpersona( 3354): KNOX_SDCARD checking this for 1000
I/libpersona( 3354): KNOX_SDCARD not a persona
,I/SELinux ( 3354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3354 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Killing 2688:com.samsung.android.sm/1000 (adj 15): empty #31
,E/SELinux ( 3354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2643:com.android.keychain/1000 (adj 15): empty #32
,I/ActivityManager( 1017): Killing 2721:flipboard.boxer.app/u0a99 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3354): TimaSignature is unavailable
,D/ActivityThread( 3354): Added TimaKeyStore provider
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
I/AASA_removePackage( 1017): UID=10174 Target=com.example.hello
,D/PackageManager( 1017): result of delete: 1{381621460}
,D/AndroidRuntime( 3135): Shutting down VM,
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2565/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_2056/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_2721/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2688/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2643/cgroup.procs: No such file or directory
,I/DBG_FMMDS( 3354): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3354): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/PCWCLIENTTRACE_DMContentProvider( 3317): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3354): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3354): [50.18.150420][Line:43][xdbDBInit] 
,W/System.err( 3109): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/ExternalOEMControlProvider( 3337): onCreate
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3380): MountEmulatedStorage()
E/Zygote  ( 3380): v2
,I/libpersona( 3380): KNOX_SDCARD checking this for 1000
I/libpersona( 3380): KNOX_SDCARD not a persona
,I/SELinux ( 3380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/SettingsProvider( 1017): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3391): MountEmulatedStorage(),
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3391 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2141:flipboard.app/u0a98 (adj 15): empty #31
E/Zygote  ( 3391): v2
I/libpersona( 3391): KNOX_SDCARD checking this for 10094
I/libpersona( 3391): KNOX_SDCARD not a persona
,I/SELinux ( 3391): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/TimaKeyStoreProvider( 3380): TimaSignature is unavailable,
D/ActivityThread( 3380): Added TimaKeyStore provider
,I/SELinux ( 3391): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3391): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1017): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 ,
,W/art     ( 3135): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/DBG_DM  ( 3001): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec,
I/System.out( 3109): YouTube MDX: MDX video stage moved to NEW
W/ResourcesManager( 3380): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
I/DBG_FMMDS( 3354): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/System.out( 3109): YouTube MDX: MDX video player state moved to UNSTARTED
I/System.out( 3109): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/TimaKeyStoreProvider( 3391): TimaSignature is unavailable
,D/ActivityThread( 3391): Added TimaKeyStore provider
,I/DBG_FMMDS( 3354): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3354): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3354): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3354): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3354): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3354): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/ActivityManager( 1017): Killing 2738:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/ServiceMode( 3380): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3380): setReferenceIsDumpState : 0
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
D/elm:15183( 3391): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3391): ELMEngine.ELMEngine( context ).
,I/FOTA_Client( 3132): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
D/elm:15183( 3391): MDMBridge.setEnterpriseBridge()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3424): MountEmulatedStorage(),
E/Zygote  ( 3424): v2
I/libpersona( 3424): KNOX_SDCARD checking this for 1000
I/libpersona( 3424): KNOX_SDCARD not a persona
,I/SELinux ( 3424): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3424): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3424): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/System.out( 3157): Thread-439(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
E/SMD     (  287): DCD OFF
,I/System.out( 3157): Thread-439(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3157): Thread-439(ApacheHTTPLog):isShipBuild true
I/ActivityManager( 1017): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3424 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/System.out( 3157): Thread-439(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3157): Thread-439(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager( 1017): Killing 2750:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/EnterpriseController(  277): uids 10092
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10092
,D/ActivityManager( 1017): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3391): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/System.out( 3157): pool-10-thread-1 calls detatch()
,I/FOTA_Client( 3132): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,D/elm:15183( 3391): ElmAgentService : onCreate()
,V/EmergencyMode( 1411): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15183( 3391): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/TimaKeyStoreProvider( 3424): TimaSignature is unavailable
,D/ActivityThread( 3424): Added TimaKeyStore provider
,D/elm:15183( 3391): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3391): BootCompletedState : startBootCompleted() call
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/LockPatternUtils( 1293): isSmartCardAuthenticationAvailable: false
,D/elm:15183( 3391): MDMBridge.getAllLicenseInfoFromSDK()
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_2141/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2738/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_2750/cgroup.procs: No such file or directory
,I/elm:15183( 3391): Get License : 0
D/elm:15183( 3391): ElmAgentService : onDestroy().
I/dex2oat ( 3376): ----------------------------------------------------
I/dex2oat ( 3376): <SS>: S T A R T I N G . . .
I/dex2oat ( 3376): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3376): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1734095697.jar --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1734095697.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager( 1017): Killing 2318:com.sec.modem.settings/1000 (adj 15): empty #31
,I/FOTA_Client( 3132): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,D/NPS_WSSNPS( 3424): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/FOTA_Client( 3132): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1017): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,D/NPS_WSSNPS( 3424): [] Service onCreate!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/EmergencyMode( 1411): [EmergencyBase] setBootTime
,V/EmergencyMode( 1411): [EmergencyFactory] No Recovery State, kill my self.
,E/Zygote  ( 3450): MountEmulatedStorage()
E/Zygote  ( 3450): v2
I/libpersona( 3450): KNOX_SDCARD checking this for 10014
I/libpersona( 3450): KNOX_SDCARD not a persona
,I/SELinux ( 3450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3450): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3450 uid=10014 gids={50014, 9997} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 2772:com.sec.knox.bridge/1000 (adj 15): empty #31
I/dex2oat ( 3376): dex2oat took 88.087ms (threads: 4)
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3465): MountEmulatedStorage()
,E/Zygote  ( 3465): v2
I/libpersona( 3465): KNOX_SDCARD checking this for 1000
I/libpersona( 3465): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3465 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3450): TimaSignature is unavailable
D/ActivityThread( 3450): Added TimaKeyStore provider
,I/SELinux ( 3465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3465): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
,D/TimaKeyStoreProvider( 3465): TimaSignature is unavailable
,D/ActivityThread( 3465): Added TimaKeyStore provider
,E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30),
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unkno,wn Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,I/libpersona( 3481): KNOX_SDCARD checking this for 10012
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.,
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
E/SQLiteDatabase( 2601): ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
,E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
I/libpersona( 3481): KNOX_SDCARD not a persona
,E/Zygote  ( 3481): MountEmulatedStorage()
,E/Zygote  ( 3481): v2
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): ,	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
,I/SELinux ( 3481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): ,	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
I/SELinux ( 3481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1017): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3481 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SELinux ( 3481): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.a,ndroid.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/ActivityManager( 1017): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/art     (  309): Explicit concurrent mark sweep GC freed 8776(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 894us total 20.868ms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
D/TimaKeyStoreProvider( 3481): TimaSignature is unavailable
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/ActivityThread( 3481): Added TimaKeyStore provider
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
D/NPS_WSSNPS( 3424): [50.150621] NpsServiceTask Start
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 18.479ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.428ms
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2601): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2601): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2601): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2601): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2601): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2601): 
```
