#### Test 61703351ed386f4_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/BrowserStartupController( 2188): Initializing chromium process, singleProcess=true
W/art     ( 2188): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2188): ApplicationContext is null in ApplicationStatus
W/chromium( 2188): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
E/USB_UICC(  300): Timeout! No signal received. Retry num = 20
W/chromium( 2188): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2188): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 2188): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
I/Adreno-EGL( 2188): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2188): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2188): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2188): Local Branch: 
I/Adreno-EGL( 2188): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2188): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2188):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/AudioManagerAndroid( 2188): Requires BLUETOOTH permission
I/NSApplication( 2188): Starting up...
D/SettingsProvider( 1013): name = vibrate_in_silent
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
--------- beginning of system
W/ResourcesManager( 1442): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/CscReceiver( 1442): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1442): Recieve Sim State Changed : ABSENT
I/splitIntent( 1013): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1013): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/BroadcastQueue( 1013): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1442, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/WifiApBroadcastReceiver( 1290): onReceive: action android.intent.action.SIM_STATE_CHANGED
E/Zygote  ( 2252): MountEmulatedStorage()
E/Zygote  ( 2252): v2
I/libpersona( 2252): KNOX_SDCARD checking this for 1000
I/libpersona( 2252): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2252 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
I/SELinux ( 2252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2263): MountEmulatedStorage()
E/Zygote  ( 2263): v2
I/libpersona( 2263): KNOX_SDCARD checking this for 1000
I/libpersona( 2263): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2263 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
I/SELinux ( 2263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/BootupListener( 1442): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider( 1013): name = internet_call_settings_visibility
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1001
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
D/PhoneUtilsCommon( 1442): isSupportVoLTE is false.
D/TimaKeyStoreProvider( 2252): TimaSignature is unavailable
D/ActivityThread( 2252): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
E/Zygote  ( 2282): MountEmulatedStorage()
E/Zygote  ( 2282): v2
I/libpersona( 2282): KNOX_SDCARD checking this for 10046
I/libpersona( 2282): KNOX_SDCARD not a persona
I/SELinux ( 2282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2282 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 2282): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2263): TimaSignature is unavailable
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/ActivityThread( 2263): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 2282): TimaSignature is unavailable
D/ActivityThread( 2282): Added TimaKeyStore provider
D/StatusChecker( 2252): onReceive : android.intent.action.SIM_STATE_CHANGED
W/ResourcesManager( 2282): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2282): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2282): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2282): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2282): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2282): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/StatusChecker( 2252): onReceive : net.mt.init : 
D/StatusChecker( 2252): onReceive : preference initializing
E/Zygote  ( 2300): MountEmulatedStorage()
E/Zygote  ( 2300): v2
I/libpersona( 2300): KNOX_SDCARD checking this for 1000
I/libpersona( 2300): KNOX_SDCARD not a persona
I/SELinux ( 2300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
E/SELinux ( 2300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2313): MountEmulatedStorage()
E/Zygote  ( 2313): v2
I/libpersona( 2313): KNOX_SDCARD checking this for 1000
I/libpersona( 2313): KNOX_SDCARD not a persona
I/SELinux ( 2313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2313 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 2300): TimaSignature is unavailable
D/ActivityThread( 2300): Added TimaKeyStore provider
E/SELinux ( 2313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2313): TimaSignature is unavailable
D/ActivityThread( 2313): Added TimaKeyStore provider
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/Omc:Receiver( 2313): onReceive : android.intent.action.SIM_STATE_CHANGED
I/Omc:OmcData( 2313): omc.xml not exist
I/Omc:Receiver( 2313): OM Customize disabled
E/Zygote  ( 2330): MountEmulatedStorage()
E/Zygote  ( 2330): v2
I/libpersona( 2330): KNOX_SDCARD checking this for 1000
I/libpersona( 2330): KNOX_SDCARD not a persona
I/SELinux ( 2330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2330 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2330): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/art     (  315): Explicit concurrent mark sweep GC freed 8771(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 23.337ms
D/TimaKeyStoreProvider( 2330): TimaSignature is unavailable
D/ActivityThread( 2330): Added TimaKeyStore provider
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 591us total 16.564ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 592us total 16.141ms
E/Zygote  ( 2345): MountEmulatedStorage()
E/Zygote  ( 2345): v2
I/libpersona( 2345): KNOX_SDCARD checking this for 10131
I/libpersona( 2345): KNOX_SDCARD not a persona
I/SELinux ( 2345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2345 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 2282): [start]    onCreate() consume time = 0.0
D/TimaKeyStoreProvider( 2345): TimaSignature is unavailable
D/ActivityThread( 2345): Added TimaKeyStore provider
W/ResourcesManager( 2345): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2345): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2345): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2345): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/SBrowserFeatureFlag( 2345): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 2345): onCreate()
D/Mms/ArtClassLoader( 2282): init before art
D/Mms/TelephonyPermission( 2282): start operation mode monitor
W/ResourcesManager( 2282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2282): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2282): isDefault true
D/Mms/MmsApp( 2282): onCreate() com.android.mms
E/OperatorBookmarksSIMReceiver( 2345): onReceive runs..android.intent.action.SIM_STATE_CHANGED
D/Mms/MmsApp( 2282): [start]    initCountryIso consume time = 336.945468
D/CountryDetector( 1013): The first listener is added
D/Mms/MmsApp( 2282): [end]    initCountryIso consume time = 35.690782
D/Mms/MmsConfig( 2282): [start]    MmsConfig.init() consume time = 0.107812
D/Mms/MmsConfig( 2282): before partial update
D/Mms/MmsConfig( 2282): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2282): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2282): isAuth is false
D/Mms/MmsConfig( 2282): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
E/USB_UICC(  300): Timeout! No signal received. Retry num = 21
D/TP/MmsSmsProvider( 1442): query,matched:2117, calling pid = 2282
D/TP/MmsSmsProvider( 1442): match 2117:Elapsed time : 10.107 ms
D/EasySignUpManager_1.0.1( 2282): isAuth is false
D/EasySignUpManager_1.0.1( 2282): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2282): mps_code.dat does not exist
E/CscParser( 2282): customer_path =/system/csc/customer.xml
E/CscParser( 2282): fileName + /system/csc/customer.xml
D/AndroidRuntime( 2363): 
D/AndroidRuntime( 2363): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2363): CheckJNI is OFF
E/CscParser( 2282): mps_code.dat does not exist
E/CscParser( 2282): customer_path =/system/csc/customer.xml
E/CscParser( 2282): fileName + /system/csc/customer.xml
D/AndroidRuntime( 2363): readGMSProperty: start
D/AndroidRuntime( 2363): readGMSProperty: already setted!!
D/AndroidRuntime( 2363): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2363): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2363): readGMSProperty: end
D/AndroidRuntime( 2363): addProductProperty: start
D/CscParser( 2282): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2282):  enable multiwindow = true
E/Mms/MessageUtils( 2282): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2282): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2282): [end]    init() consume time = 147.302917
D/Mms/Contact( 2282): [start]    init() consume time = 2.323906
D/TP/MmsSmsProvider( 1442): query,matched:13, calling pid = 2282
D/Mms/Contact( 2282): [end]    init consume time = 15.428177
D/TP/MmsSmsProvider( 1442): match 13:Elapsed time : 2.972 ms
D/Mms/DraftCache( 2282): [start]    rebuildCache consume time = 9.539583
D/TP/MmsSmsProvider( 1442): query,matched:12, calling pid = 2282
D/TP/MmsSmsProvider( 1442): match 12:Elapsed time : 3.225 ms
D/Mms/DraftCache( 2282): [end]    rebuildCache consume time = 15.425938
D/Mms/MethodReflector( 2282): getSubId is called
D/Mms/TelephonyUtils( 2282): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2282): getTelephonyProperty is called
D/Mms/DownloadManager( 2282): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2282): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2282): auto download without roaming -> true
D/Mms/DownloadManager( 2282): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2282): getSubId is called
D/Mms/MethodReflector( 2282): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2282): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2282): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2282): getTelephonyProperty is called
D/Mms/DownloadManager( 2282): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2282): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2282): auto download without roaming -> true
D/Mms/DownloadManager( 2282): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2282): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2282): mAutoDownload ------> true
D/Mms/ArtClassLoader( 2282): init [DONE] art
E/AffinityControl( 2363): AffinityControl: registerfunction enter
D/ComposerPerformance( 2282): 1457596411713 ms / [DONE] Composer constructor
D/Mms/Conversation( 2282): [start]    init() consume time = 93.482604
E/CII     ( 2282): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 2282): ReservationManager()
I/Mms/ReservationManager( 2282): resetAfterConnected()
D/TP/MmsSmsDatabaseHelper( 1442): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1442): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1442): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
D/TP/MmsSmsDatabaseHelper( 1442): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1442): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
D/TP/MmsSmsProvider( 1442): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1442): query,matched:7, calling pid = 2282
D/TP/MmsSmsProvider( 1442): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
D/TP/MmsSmsProvider( 1442): match 7:Elapsed time : 3.549 ms
V/TP/MmsSmsDatabaseHelper( 1442): updateThread(), thread_id = 9223372036854775807
I/Mms/ReservationManager( 2282): getReservedSendMessageCount(): retMessageCount=0
D/AndroidRuntime( 2363): Calling main entry com.android.commands.am.Am
D/Mms/MmsApp( 2282): [end]    onCreate() consume time = 19.268281
V/TP/MmsSmsDatabaseHelper( 1442): sUpgradeVersion = 0, db.getVersion() = 81
D/Mms/SmsReceiver( 2282): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/PersonaManagerService( 1013): inState():  stateMachine is null !!
D/ActivityManager( 1013): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
I/PersonaManagerService( 1013): PersonaId don't exist
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
I/ActivityManager( 1013): do not start freezing screen for locked container getKeyguardshowstate = false
W/ActivityManager( 1013): userId = 0, bbcId = -10000
I/splitIntent( 1013): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/DownloadManager( 2282): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2282): roaming ------> false, mSimSlot = 0
D/TP/MmsSmsProvider( 1442): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1442): need read changed broadcast:false
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/Mms/MethodReflector( 2282): getSubId is called
D/Mms/TelephonyUtils( 2282): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2282): getTelephonyProperty is called
D/Mms/DownloadManager( 2282): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2282): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2282): auto download without roaming -> true
D/Mms/DownloadManager( 2282): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 2282): mAutoDownload ------> true
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/BootupListener( 1442): intent.getAction() = android.intent.action.SERVICE_STATE
D/SettingsProvider( 1013): name = internet_call_settings_visibility
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 1001
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/PhoneUtilsCommon( 1442): isSupportVoLTE is false.
W/ActivityManager( 1013): mDVFSHelper.acquire()
D/FocusedStackFrame( 1013): Set to : 0
D/PhoneWindow( 1013): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1013): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1465): onPause
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1013): Focused application set to: xxxx
D/Launcher( 1465): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1013): Focus left window: 1465
D/AndroidRuntime( 2363): Shutting down VM
D/Mms/Conversation( 2282): [end]    init consume time = 34.911615
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/StatusChecker( 2252): onReceive : android.intent.action.SERVICE_STATE
D/Mms/SmsReceiverService( 2282): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
I/StatusChecker( 2252): onReceive : net.mt.init : DONE
D/Mms/TelephonyPermission( 2282): isDefault true
D/Mms/SmsReceiverService( 2282): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2282): handleSIMStatus()
D/Mms/SmsReceiverService( 2282): handleSIMStatus(): SIM_STATUS = ABSENT
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1013): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
D/Mms/MessagingNotification( 2282): [start]    init() consume time = 13.22026
D/StatusChecker( 2252): Service state changed : 3 mSub-1
E/Zygote  ( 2384): MountEmulatedStorage()
I/libpersona( 2384): KNOX_SDCARD checking this for 10174
E/Zygote  ( 2384): v2
I/libpersona( 2384): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2384 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2384): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2384): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2384): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
D/Mms/MessagingNotification( 2282): [end]    init consume time = 23.891146
D/Mms/SpamFilter( 2282): [start]    SpamFilter fill() begin consume time = 4.649219
D/TP/MmsSmsProvider( 1442): query,matched:0, calling pid = 2282
V/ActivityThread( 1465): updateVisibility : ActivityRecord{df0075d token=android.os.BinderProxy@24683e4d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/TP/MmsSmsProvider( 1442): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1442): match 0:Elapsed time : 1.188 ms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/Synchronizer( 2282): [start]    doSync consume time = 12.742135
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 2384): TimaSignature is unavailable
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/ActivityThread( 2384): Added TimaKeyStore provider
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1013): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1013): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1465): onStop
V/ActivityThread( 1465): updateVisibility : ActivityRecord{df0075d token=android.os.BinderProxy@24683e4d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1013): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1013): isKioskContainerExistOnDevice
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Launcher( 1465): onTrimMemory. Level: 20
D/TP/MmsSmsProvider( 1442): update, matched:300, calling pid = 2282
V/TP/MmsSmsProvider( 1442): syncDBData start
V/TP/MmsSmsProvider( 1442): syncDBData sms end
V/TP/MmsSmsProvider( 1442): syncDBData mms end
V/TP/MmsSmsProvider( 1442): syncDBData end
D/TP/MmsSmsProvider( 1442): query,matched:400, calling pid = 2282
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/Synchronizer( 2282): [end]    doSync consume time = 81.945781
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/MessagingNotification( 2282): checkBadgeCount unreadCount=0 badgeCount=0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/SpamFilter( 2282): [end]    SpamFilter fill() finished consume time = 32.453021
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/SmsProvider( 1442): query,matched:26, calling pid = 2282
D/TP/SmsProvider( 1442): match 26:Elapsed time : 1.986 ms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1442): query,matched:6, calling pid = 2282
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/WebViewFactory( 2384): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/TP/MmsSmsProvider( 1442): match 6:Elapsed time : 1.871 ms
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
W/art     ( 2363): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/LibraryLoader( 2384): Time to load native libraries: 1 ms (timestamps 8165-8166)
I/LibraryLoader( 2384): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 2402): MountEmulatedStorage()
E/Zygote  ( 2402): v2
,I/libpersona( 2402): KNOX_SDCARD checking this for 10020
I/libpersona( 2402): KNOX_SDCARD not a persona
,I/SELinux ( 2402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2402 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 2402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2402): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/WebViewChromiumFactoryProvider( 2384): Binding Chromium to main looper Looper (main, tid 1) {338c4086}
,I/LibraryLoader( 2384): Expected native library version number "",actual native library version number ""
I/chromium( 2384): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 2402): TimaSignature is unavailable
,D/ActivityThread( 2402): Added TimaKeyStore provider
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2417): MountEmulatedStorage()
,E/Zygote  ( 2417): v2
I/libpersona( 2417): KNOX_SDCARD checking this for 10025
I/libpersona( 2417): KNOX_SDCARD not a persona
,W/ResourcesManager( 2402): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2402): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2402): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/BrowserStartupController( 2384): Initializing chromium process, singleProcess=true
I/SELinux ( 2417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1013): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2417 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
,I/SELinux ( 2417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SysUtils( 2384): ApplicationContext is null in ApplicationStatus
E/SELinux ( 2417): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/chromium( 2384): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 2384): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2384): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2384): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/TimaKeyStoreProvider( 2417): TimaSignature is unavailable
D/ActivityThread( 2417): Added TimaKeyStore provider
,I/Adreno-EGL( 2384): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2384): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2384): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2384): Local Branch: 
I/Adreno-EGL( 2384): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2384): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2384):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ResourcesManager( 2417): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 2384): 769384210: getState() :  mService = null. Returning STATE_OFF
,I/OMACP   ( 2417): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 2282): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/chromium( 2384): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 2417): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/8)
,W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,W/AwContents( 2384): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2384): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 2384): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2384): CordovaWebView is running on device made by: samsung
,W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2384): Attempt to remove local handle scope entry from IRT, ignoring
,D/EasySignUpManager_1.15.0305( 2402): serviceId : 0, features : -1
,I/splitIntent( 1013): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1013): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD OFF,
,E/Zygote  ( 2454): MountEmulatedStorage()
,E/Zygote  ( 2454): v2
I/libpersona( 2454): KNOX_SDCARD checking this for 10044
I/libpersona( 2454): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2454 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 2454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SecContentProvider2( 1013): uri = 18 selection = isCopyContactToSimAllowed
,I/SELinux ( 2454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/SELinux ( 2454): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1013): mCursor = null
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/SecContentProvider2( 1013): isCopyContactToSimAllowed = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2454): TimaSignature is unavailable
,D/ActivityThread( 2454): Added TimaKeyStore provider
,E/Zygote  ( 2471): MountEmulatedStorage()
,E/Zygote  ( 2471): v2
I/libpersona( 2471): KNOX_SDCARD checking this for 10088
I/libpersona( 2471): KNOX_SDCARD not a persona
,I/SELinux ( 2471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2471): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2471 uid=10088 gids={50088, 9997} abi=armeabi-v7a
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2485): MountEmulatedStorage()
,E/Zygote  ( 2485): v2
I/libpersona( 2485): KNOX_SDCARD checking this for 10142
I/libpersona( 2485): KNOX_SDCARD not a persona,
I/SELinux ( 2485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2485 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2485): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 2471): TimaSignature is unavailable
D/ActivityThread( 2471): Added TimaKeyStore provider
D/ActivityThread( 2485): Added TimaKeyStore provider
D/OpenGLRenderer( 2384): Render dirty regions requested: true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/BroadcastQueue( 1013): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1465, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ResourcesManager( 2454): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2454): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 2454): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2471): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2504): MountEmulatedStorage(),
I/libpersona( 2504): KNOX_SDCARD checking this for 10054
E/Zygote  ( 2504): v2
I/libpersona( 2504): KNOX_SDCARD not a persona
I/SELinux ( 2504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 22
,I/SELinux ( 2504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2504 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
,E/SELinux ( 2504): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1013): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1013): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1013): handleActiveUserChange for user 0
,D/PhoneWindow( 2384): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2384): *FMB* isFloatingMenuEnabled return false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1013): Focus entered window: 2384,
,D/SRIB_DCS( 2384): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2384): Initialized EGL, version 1.4
D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,E/Zygote  ( 2519): MountEmulatedStorage()
E/Zygote  ( 2519): v2
I/libpersona( 2519): KNOX_SDCARD checking this for 10139
I/libpersona( 2519): KNOX_SDCARD not a persona
,I/SELinux ( 2519): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 2504): TimaSignature is unavailable
,D/OpenGLRenderer( 2384): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2384): Enabling debug mode 0
,D/ActivityThread( 2504): Added TimaKeyStore provider
,I/ActivityManager( 1013): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2519 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,I/SELinux ( 2519): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2519): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/TaskCloserActivity( 2485): TaskCloserActivity enter()
,D/SecContentProvider2( 1013): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1013): mCursor = null
,D/TimaKeyStoreProvider( 2519): TimaSignature is unavailable
,D/ActivityThread( 2519): Added TimaKeyStore provider
,V/TaskCloserActivity( 2485): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ResourcesManager( 2504): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 2519): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2519): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2519): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2519): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2519): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Recents_RecreateReceiver( 2504): onReceive by home
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 34084(1823KB) AllocSpace objects, 2(146KB) LOS objects, 33% free, 24MB/37MB, paused 2.075ms total 134.134ms
,D/InputMethodManagerService( 1013): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1013): Displayed Component not be shown by security: +1s6ms
,I/Timeline( 2384): Timeline: Activity_idle id: android.os.BinderProxy@346cf90d time:28937
W/ActivityManager( 1013): mDVFSHelper.release()
I/Timeline( 1013): Timeline: Activity_windows_visible id: ActivityRecord{218d14ac u0 com.example.hello/.MainActivity t10} time:28938
,W/art     ( 2402): Verification of void com.android.contacts.common.list.l.P() took 112.524ms
,I/SamsungIME( 1800): getCurrentCandidateView
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
W/BindingManager( 2384): Cannot call determinedVisibility() - never saw a connection for the pid: 2384
,D/SamsungIME( 1800): Dismiss ExpandCandiate,
I/chromium( 2384): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/AbsListView( 2402): Get MotionRecognitionManager
,D/MotionRecognitionService( 1013):  ssp status : false
,D/NearbySource( 2454): Nearby Source Create!
,D/NearbyContext( 2454): Nearby Context Create!
,D/JsMessageQueue( 2384): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2384): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2454): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2454): Samsung link source created
,I/SamsungIME( 1800): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1800): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1800): KeybaordView init() : load resources
,D/ContactProvider( 2454): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SamsungIME( 1800): getCurrentKeyboard
I/SamsungIME( 1800): getTextKeyboard
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2454): Receive : home resume
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/SamsungIME( 1800): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/Mms/UIEventReceiver( 2282): ui event
,I/splitIntent( 1013): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteLog( 1223): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/jxcore_app_log( 2384): JniHelper::setJavaVM(0xb854c450), pthread_self() = -1196641984
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ContactProvider( 2454): getAllContactInfoList End
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/syncContacts( 2454): thread: 253, sync time = 177
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,W/jxcore-log( 2384): Initializing JXcore engine
W/jxcore-log( 2384): JXcore engine is ready
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1725): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1725): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1725): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 1725): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1725): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 08 53
,E/audit   ( 1933): type=1400 msg=audit(1457596413.491:203): avc:  denied  { ioctl } for  pid=2552 comm="Thread-256" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1933):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1933): type=1300 msg=audit(1457596413.491:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=9d39f8f8 items=0 ppid=315 ppcomm=main pid=2552 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-256" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1933): type=1320 msg=audit(1457596413.491:203): 
,E/accuweather( 1725): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/jxcore-log( 2384): Starting JXcore engine
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 23
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1725): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1725): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/accuweather( 1725): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1725): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1725): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1346): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1346): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,W/jxcore-log( 2384): Platform android
W/jxcore-log( 2384): 
,W/jxcore-log( 2384): Process ARCH arm
W/jxcore-log( 2384): 
,I/jxcore-log( 2384): JXcore Cordova bridge is ready!
I/jxcore-log( 2384): 
,W/jxcore-log( 2384): JXcore engine is started
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/jxcore  ( 2384): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2384): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/Mms/MmsApp( 2282):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 2282): [start]    fillCache consume time = 1797.345885
D/Mms/ComposeMessageFragment( 2282): fillCache, easy = false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneWindow( 2384): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 2384): *FMB* installDecor flags : 8388610
D/SIP     ( 1442): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/File    ( 1442): fail readDirectory() errno=2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/InputDispatcher( 1013): Focus left window: 2384
D/InputDispatcher( 1013): Focus entered window: 2384
,D/PointerIcon( 1013): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1013): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneWindow( 2384): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2384): *FMB* isFloatingMenuEnabled return false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=4, NainActivit,
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SRIB_DCS( 2384): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1757): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/AbsListView( 2282): Get MotionRecognitionManager
,D/MotionRecognitionService( 1013):  ssp status : false
,D/SamsungIME( 1800): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/Mms/ComposeMessageFragment( 2282): [end]    fillCache consume time = 169.386771
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1013): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1013): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1013): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/BubbleViewCache( 2282): fillCache bubble = 1
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1757): callingUid 10012, callindPid: 1757
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsWearableNodeHelper( 1757): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1757): [191] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1997): Restart initialization of location
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1442): query,matched:0, calling pid = 1997
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/TP/SmsProvider( 1442): match 0:Elapsed time : 1.910 ms
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1442): Query uri=content://mms, match=0, calling pid = 1997
,D/TP/SmsProvider( 1442): query,matched:0, calling pid = 1997
,D/TP/SmsProvider( 1442): match 0:Elapsed time : 1.905 ms
,D/TP/MmsProvider( 1442): Query uri=content://mms, match=0, calling pid = 1997
,I/Scheduler( 1757): Use legacy PeriodicScheduler
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1757): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/InstanceID/Rpc( 1757): Found 10012
,D/a       ( 1757): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 1997): getNumBytesRead when not calculated.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 24
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,W/GCoreFlp( 1757): No location to return for getLastLocation()
,W/FusedLocationProvider( 1757): location=null
D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1346): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1346): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1175): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/AdaptiveEventManager( 1175): currentCityId is null
D/AdaptiveEventManager( 1175): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1175): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1175): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1175): Widget Count: Previous= 0 >> Now= 0
D/daemonapp( 1346): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
D/AdaptiveEventManager( 1175): mWeatherInfo is not reliable
,E/daemonapp( 1346): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1346): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/daemonapp( 1346): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,E/daemonapp( 1346): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1346): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2593): MountEmulatedStorage()
,E/Zygote  ( 2593): v2
I/libpersona( 2593): KNOX_SDCARD checking this for 10135
I/libpersona( 2593): KNOX_SDCARD not a persona
,I/SELinux ( 2593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1013): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2593 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,I/SELinux ( 2593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1457596414686
D/daemonapp( 1346): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1457618014680
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1346): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1457617980000
D/daemonapp( 1346): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457617980000
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
D/daemonapp( 1346): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1457617980000
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2593): TimaSignature is unavailable
D/ActivityThread( 2593): Added TimaKeyStore provider
,E/Zygote  ( 2608): MountEmulatedStorage(),
E/Zygote  ( 2608): v2
I/libpersona( 2608): KNOX_SDCARD checking this for 1000
I/libpersona( 2608): KNOX_SDCARD not a persona
,I/SELinux ( 2608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2608 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2608): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 2593): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2593): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2593): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2608): TimaSignature is unavailable
,I/art     (  315): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.095ms total 28.064ms
D/ActivityThread( 2608): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 20.611ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 18.643ms
,D/SecurityLogAgent( 2608):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2608):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2608):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2608): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2608): FileZippingService : onHandleIntent 
,D/SecurityLogAgent( 2608): FileZippingService : file path =  /data/misc/audit/audit.old
,E/Zygote  ( 2625): MountEmulatedStorage()
,E/Zygote  ( 2625): v2
I/libpersona( 2625): KNOX_SDCARD checking this for 1000
I/libpersona( 2625): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2625 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2625): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/SecurityLogAgent( 2608): FileZippingService : onPremise disabled. Zipping..  
,I/SELinux ( 2625): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2625): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2625): TimaSignature is unavailable
,D/ActivityThread( 2625): Added TimaKeyStore provider
,D/SecurityLogAgent( 2608): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2608): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2608): DenialLogFileZipCreator : Files exceeded the max limit 
,D/SecurityLogAgent( 2608): DenialLogFileZipCreator File existence : true audit.old file size 631
,W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,D/SecurityLogAgent( 2608): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/SecurityLogAgent( 2608): FileZippingService : completed task. Returning wakelock . 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2643): MountEmulatedStorage()
,E/Zygote  ( 2643): v2
I/libpersona( 2643): KNOX_SDCARD checking this for 1000
I/libpersona( 2643): KNOX_SDCARD not a persona
I/SELinux ( 2643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2643 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2643): TimaSignature is unavailable
D/ActivityThread( 2643): Added TimaKeyStore provider
,W/ResourcesManager( 2643): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$onReceive](2643) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2643): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) is Live Demo : false
,D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) modelXML=sm-a500fu.dat
D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) deviceXML=a5ulte.dat
D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) nameXML=a5ultexx.dat
D/FactoryTestApp( 2643): [XMLDataStorage$parseAsset](2643) parseAsset Is Started
,I/FactoryTestApp( 2643): [XMLDataStorage$parseAsset](2643) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2643): [XMLDataStorage$parseAsset](2643) Decode base file: factory.dat
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FACTORY_TEST_APP
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FAILHIST_VERSION
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MODEL_NAME
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MODEL_NUMBER
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MODEL_HARDWARE_REVISION
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=CHIPSET_NAME
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=DEVICE_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATT_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PANEL_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SPEAKER_COUNT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MIC_COUNT
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_LTE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_DUAL_STANBY_ONE_CP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_RCV
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_BOOST_MEDIASCAN
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_EPEN
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HW_VER_EFS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FONT_SIZE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=RAM_SIZE_IF
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MULTI_TSK_THD
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_FM_RADIO
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_POWER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_HOME
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_BACK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_KEY_TEST_THRESHOLD
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_SENSOR_TEST_ACC_REVERSE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=G_VECTOR_SUM_ACC_BIT,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_VIBETONZ_UNSUPPORTED,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=AT_GPSSTEST,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HALL_IC_TEST,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_NEW_TSP_SELFTEST_SYNAPTICS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=READ_TARGET_GEOMAGNETIC,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATTERY_VOLT_AVER,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATTERY_VF_OCV,
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 16508(910KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 2.022ms total 133.325ms
D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_THERMISTER_CELCIUS
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_THERMISTER_ADC
,I/GAV4    ( 2188): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA1_THERMISTER_ADC
,I/GAv4-SVC( 1997): Google Analytics 8.4.89 is starting up.
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,E/SMD     (  289): DCD OFF
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=LPA_MODE_SET
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2643): [XMLDataStorage$parseAsset](2643) SemiFunctionMenu
,D/FactoryTestApp( 2643): [XMLDataStorage$parseAsset](2643) parseAsset Is Completed
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2643): [ModuleCommon$ModuleCommon](2643) Create ModuleCommon
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2643): [Support$Kernel.read](2643) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2643): [ModuleCommon$readFactoryMode](2643) mode: ON
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$onReceive](2643) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2643): [Support$Values.getBoolean](2643) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=BINARY_TYPE, key=ro.factory.factory_binary,
D/FactoryTestApp( 2643): [Support$Properties.get](2643) property=ro.factory.factory_binary
D/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$onReceive](2643) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2643): [ModuleCommon$getFtClientEnableState](2643) result : false
I/FactoryTestApp( 2643): [ModuleCommon$connectedJIG](2643) ...
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2643): [ModuleCommon$connectedJIG](2643) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2643): [Support$Kernel.read](2643) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 2643): [ModuleCommon$connectedJIG](2643) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
I/FactoryTestApp( 2643): [ModuleCommon$isRunningFtClient](2643) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2643) start DummyFtClient service for APO
,W/ContextImpl( 2643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1013): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2643): User mode
I/FactoryTestApp( 2643): [ModuleCommon$disableFtClient](2643) ...
,D/FactoryTestApp( 2643): [DummyFtClient$onCreate](2643) Create DummyFtClient service
,I/FactoryTestApp( 2643): [XMLDataStorage$parsingXML](2643) FtClient => data parsing was completed.
D/FactoryTestApp( 2643): [DummyFtClient$onReceive](2643) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
,D/FactoryTestApp( 2643): [Support$Values.getBoolean](2643) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2643): [DummyFtClient$onStartCommand](2643) ...
,I/WifiService( 1013): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1013): boot completed
,D/UsbDeviceManager( 1013): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1013): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/UsbDeviceManager( 1013): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1013): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,I/KeyguardEffectViewUtil( 1175): set resource id
,D/SettingsProvider( 1013): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10054
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BOOT_COMPLETED
,D/KeyguardUpdateMonitor( 1175): handleBootCompleted()
D/KeyguardUpdateMonitor( 1175): handleBootCompleted()
,I/PalmMotion( 1013): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1013): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1013): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1013): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1013): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1013) 
,D/LightsService( 1013): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 1013): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1013): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,D/SamsungIME( 1800): showDlgMsgBox : false true true
,I/RecoverySystem( 1013): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1013): No recovery log file
D/NfcService( 1427): call the applyRouting
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 25
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/RecoverySystem( 1013): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1013): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory),
E/RecoverySystem( 1013): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,E/Zygote  ( 2672): MountEmulatedStorage()
E/Zygote  ( 2672): v2
I/libpersona( 2672): KNOX_SDCARD checking this for 1000
I/libpersona( 2672): KNOX_SDCARD not a persona
,I/SELinux ( 2672): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1013): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2672 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2672): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2672): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
D/Reset_Reason( 1013): resetString = NPON
,I/BootReceiver( 1013): Copying audit failures to DropBox,
I/BootReceiver( 1013): Checking for fsck errors
I/BootReceiver( 1013): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,V/OtaStartupReceiver( 1442): onOtaspChanged: mOtaspMode=1
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2672): TimaSignature is unavailable
,D/ActivityThread( 2672): Added TimaKeyStore provider
,E/Zygote  ( 2692): MountEmulatedStorage()
E/Zygote  ( 2692): v2
I/libpersona( 2692): KNOX_SDCARD checking this for 1001
I/SELinux ( 2692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2692): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2692 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 2692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2692): TimaSignature is unavailable
,W/ResourceType( 1013): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ActivityThread( 2692): Added TimaKeyStore provider
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/File    ( 2672): fail readDirectory() errno=2
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 2692): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1013): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1013): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BootReceiver( 1013): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/ActivityManager( 1013): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FactoryTestApp( 2643): [ProtectedFactoryTestBroadcastReceiver$onReceive](2643) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2643): [ProtectedFactoryTestBroadcastReceiver$onReceive](2643) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2643): User mode
,D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 31510, tid: 31510, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1013):     r0 b914bd48  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1013):     r4 0045b0a0  r5 be11f218  r6 b914bd48  r7 be11f228
D/CrashAnrDetector( 1013):     r8 be11ee60  r9 ba64e378  sl ba64e378  fp be11f1dc
D/CrashAnrDetector( 1013):     ip be11f228  sp be11ee58  lr a0b0030c  pc a0affd98  cpsr a00f0010
D/CrashAnrDetector( 1013):     d0  ffffff859ec62bb0  d1  0000000000000000
D/CrashAnrDetector( 1013):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1013):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1013):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1013):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1013):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1013):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1013):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1013):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1013):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1013):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1013):     scr 20000013
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1013):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1013):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1013):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          be11edd8  00000000  
D/CrashAnrDetector( 1013):          be11eddc  00000000  
D/CrashAnrDetector( 1013):          be11ede0  00000000  
D/CrashAnrDetector( 1013):          be11ede4  00000000  
D/CrashAnrDetector( 1013):          be11ede8  00000000  
D/CrashAnrDetector( 1013):          be11edec  00000000  
D/CrashAnrDetector( 1013):          be11edf0  00000000  
D/CrashAnrDetector( 1013):          be11edf4  00000000  
D/CrashAnrDetector( 1013):          be11edf8  00000000  
D/CrashAnrDetector( 1013):          be11edfc  00000000  
D/CrashAnrDetector( 1013):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1013):          be11ee04  00000000  
D/CrashAnrDetector( 1013):          be11ee08  00000000  
D/CrashAnrDetector( 1013):          be11ee0c  00000000  
D/CrashAnrDetector( 1013):          be11ee10  00000000  
D/CrashAnrDetector( 1013):          be11ee14  00000000  
D/CrashAnrDetector( 1013):          be11ee18  00000000  
D/CrashAnrDetector( 1013):          be11ee1c  00000000  
D/CrashAnrDetector( 1013):          be11ee20  00000000  
D/CrashAnrDetector( 1013):          be11ee24  00000000  
D/CrashAnrDetector( 1013):          be11ee28  00000000  
D/CrashAnrDetector( 1013):          be11ee2c  00000000  
D/CrashAnrDetector( 1013):          be11ee30  00000000  
D/CrashAnrDetector( 1013):          be11ee34  00000000  
D/CrashAnrDetector( 1013):          be11ee38  00000000  
D/CrashAnrDetector( 1013):          be11ee3c  00000000  
D/CrashAnrDetector( 1013):          be11ee40  00000000  
D/CrashAnrDetector( 1013):          be11ee44  00000000  
D/CrashAnrDetector( 1013):          be11ee48  00000000  
D/CrashAnrDetector( 1013):          be11ee4c  00000000  
D/CrashAnrDetector( 1013):          be11ee50  00000000  
D/CrashAnrDetector( 1013):          be11ee54  00000000  
D/CrashAnrDetector( 1013):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1013):          be11ee5c  00000000  
D/CrashAnrDetector( 1013):          be11ee60  00000000  
D/CrashAnrDetector( 1013):          be11ee64  00000000  
D/CrashAnrDetector( 1013):          be11ee68  00000000  
D/CrashAnrDetector( 1013):          be11ee6c  00000000  
D/CrashAnrDetector( 1013):          be11ee70  00000000  
D/CrashAnrDetector( 1013):          be11ee74  00000000  
D/CrashAnrDetector( 1013):          be11ee78  00000000  
D/CrashAnrDetector( 1013):          be11ee7c  00000000  
D/CrashAnrDetector( 1013):          be11ee80  00000000  
D/CrashAnrDetector( 1013):          be11ee84  00000000  
D/CrashAnrDetector( 1013):          be11ee88  00000000  
D/CrashAnrDetector( 1013):          be11ee8c  00000000  
D/CrashAnrDetector( 1013):          be11ee90  00000000  
D/CrashAnrDetector( 1013):          be11ee94  00000000  
D/CrashAnrDetector( 1013):          be11ee98  00000000  
D/CrashAnrDetector( 1013):          be11ee9c  00000000  
D/CrashAnrDetector( 1013):          be11eea0  00000000  
D/CrashAnrDetector( 1013):          be11eea4  00000000  
D/CrashAnrDetector( 1013):          be11eea8  00000000  
D/CrashAnrDetector( 1013):          be11eeac  00000000  
D/CrashAnrDetector( 1013):          be11eeb0  00000000  
D/CrashAnrDetector( 1013):          be11eeb4  00000000  
D/CrashAnrDetector( 1013):          be11eeb8  00000000  
D/CrashAnrDetector( 1013):          be11eebc  00000000  
D/CrashAnrDetector( 1013):       
D/CrashAnrDetector( 1013): processName:com.test.thalitest
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/CrashAnrDetector( 1013): broadcastEvent : null SYSTEM_TOMBSTONE
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/Mms/NotificationReceiver( 2282): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2282): handleBootCompleted()
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Mms/RcsOwnCapsManager( 2282): queue Uri = content://im/queue-messages?box=pending
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TP/ImProvider( 1442): im query match24
D/TP/ImProvider( 1442): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1442): ftSesstionId must be a long.
D/TP/ImProvider( 1442): getQueuedImMessages
D/TP/ImProvider( 1442): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
W/Resources( 1013): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/BootReceiver( 1013): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
D/Mms/NotificationReceiver( 2282):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2282): Call to GET_LAST_MESSAGES_SENT
E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 2016, tid: 2016, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1013):     r0 b926a1f0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1013):     r4 0045b0a0  r5 be11f218  r6 b926a1f0  r7 be11f228
D/CrashAnrDetector( 1013):     r8 be11ee60  r9 baf12548  sl baf12548  fp be11f1dc
D/CrashAnrDetector( 1013):     ip be11f228  sp be11ee58  lr a09c330c  pc a09c2d98  cpsr a00f0010
D/CrashAnrDetector( 1013):     d0  ffffff859e8579c0  d1  0000000000000000
D/CrashAnrDetector( 1013):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1013):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1013):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1013):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1013):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1013):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1013):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1013):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1013):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1013):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1013):     scr 20000013
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1013):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1013):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1013):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          be11edd8  00000000  
D/CrashAnrDetector( 1013):          be11eddc  00000000  
D/CrashAnrDetector( 1013):          be11ede0  00000000  
D/CrashAnrDetector( 1013):          be11ede4  00000000  
D/CrashAnrDetector( 1013):          be11ede8  00000000  
D/CrashAnrDetector( 1013):          be11edec  00000000  
D/CrashAnrDetector( 1013):          be11edf0  00000000  
D/CrashAnrDetector( 1013):          be11edf4  00000000  
D/CrashAnrDetector( 1013):          be11edf8  00000000  
D/CrashAnrDetector( 1013):          be11edfc  00000000  
D/CrashAnrDetector( 1013):          be11ee00  00000000  
D/CrashAnrDetector( 1013):          be11ee04  00000000  
D/CrashAnrDetector( 1013):          be11ee08  00000000  
D/CrashAnrDetector( 1013):          be11ee0c  00000000  
D/CrashAnrDetector( 1013):          be11ee10  00000000  
D/CrashAnrDetector( 1013):          be11ee14  00000000  
D/CrashAnrDetector( 1013):          be11ee18  00000000  
D/CrashAnrDetector( 1013):          be11ee1c  00000000  
D/CrashAnrDetector( 1013):          be11ee20  00000000  
D/CrashAnrDetector( 1013):          be11ee24  00000000  
D/CrashAnrDetector( 1013):          be11ee28  00000000  
D/CrashAnrDetector( 1013):          be11ee2c  00000000  
D/CrashAnrDetector( 1013):          be11ee30  00000000  
D/CrashAnrDetector( 1013):          be11ee34  00000000  
D/CrashAnrDetector( 1013):          be11ee38  00000000  
D/CrashAnrDetector( 1013):          be11ee3c  00000000  
D/CrashAnrDetector( 1013):          be11ee40  00000000  
D/CrashAnrDetector( 1013):          be11ee44  00000000  
D/CrashAnrDetector( 1013):          be11ee48  00000000  
D/CrashAnrDetector( 1013):          be11ee4c  00000000  
D/CrashAnrDetector( 1013):          be11ee50  00000000  
D/CrashAnrDetector( 1013):          be11ee54  00000000  
D/CrashAnrDetector( 1013):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1013):          be11ee5c  00000000  
D/CrashAnrDetector( 1013):          be11ee60  00000000  
D/CrashAnrDetector( 1013):          be11ee64  00000000  
D/CrashAnrDetector( 1013):          be11ee68  00000000  
D/CrashAnrDetector( 1013):          be11ee6c  00000000  
D/CrashAnrDetector( 1013):          be11ee70  00000000  
D/CrashAnrDetector( 1013):          be11ee74  00000000  
D/CrashAnrDetector( 1013):          be11ee78  00000000  
D/CrashAnrDetector( 1013):          be11ee7c  00000000  
D/CrashAnrDetector( 1013):          be11ee80  00000000  
D/CrashAnrDetector( 1013):          be11ee84  00000000  
D/CrashAnrDetector( 1013):          be11ee88  00000000  
D/CrashAnrDetector( 1013):          be11ee8c  00000000  
D/CrashAnrDetector( 1013):          be11ee90  00000000  
D/CrashAnrDetector( 1013):          be11ee94  00000000  
D/CrashAnrDetector( 1013):          be11ee98  00000000  
D/CrashAnrDetector( 1013):          be11ee9c  00000000  
D/CrashAnrDetector( 1013):          be11eea0  00000000  
D/CrashAnrDetector( 1013):          be11eea4  00000000  
D/CrashAnrDetector( 1013):          be11eea8  00000000  
D/CrashAnrDetector( 1013):          be11eeac  00000000  
D/CrashAnrDetector( 1013):          be11eeb0  00000000  
D/CrashAnrDetector( 1013):          be11eeb4  00000000  
D/CrashAnrDetector( 1013):          be11eeb8  00000000  
D/CrashAnrDetector( 1013):          be11eebc  00000000  
D/CrashAnrDetector( 1013):         
D/CrashAnrDetector( 1013): processName:com.test.thalitest
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1013): broadcastEvent : null SYSTEM_TOMBSTONE
,I/BootReceiver( 1013): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 8409, tid: 8409, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1013):     r0 b9145f50  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1013):     r4 0045b0a0  r5 be11f218  r6 b9145f50  r7 be11f228
D/CrashAnrDetector( 1013):     r8 be11ee60  r9 bab49fd0  sl bab49fd0  fp be11f1dc
D/CrashAnrDetector( 1013):     ip be11f228  sp be11ee58  lr 9fdfc30c  pc 9fdfbd98  cpsr a00f0010
D/CrashAnrDetector( 1013):     d0  ffffff859df5ebb0  d1  646f6d5f65646f6e
D/CrashAnrDetector( 1013):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1013):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1013):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1013):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1013):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1013):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1013):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1013):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1013):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1013):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1013):     scr 20000012
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1013):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1013):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1013):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          be11edd8  00000000  
D/CrashAnrDetector( 1013):          be11eddc  00000000  
D/CrashAnrDetector( 1013):          be11ede0  00000000  
D/CrashAnrDetector( 1013):          be11ede4  00000000  
D/CrashAnrDetector( 1013):          be11ede8  00000000  
D/CrashAnrDetector( 1013):          be11edec  00000000  
D/CrashAnrDetector( 1013):          be11edf0  00000000  
D/CrashAnrDetector( 1013):          be11edf4  00000000  
D/CrashAnrDetector( 1013):          be11edf8  00000000  
D/CrashAnrDetector( 1013):          be11edfc  00000000  
D/CrashAnrDetector( 1013):          be11ee00  00000000  
D/CrashAnrDetector( 1013):          be11ee04  00000000  
D/CrashAnrDetector( 1013):          be11ee08  00000000  
D/CrashAnrDetector( 1013):          be11ee0c  00000000  
D/CrashAnrDetector( 1013):          be11ee10  00000000  
D/CrashAnrDetector( 1013):          be11ee14  00000000  
D/CrashAnrDetector( 1013):          be11ee18  00000000  
D/CrashAnrDetector( 1013):          be11ee1c  00000000  
D/CrashAnrDetector( 1013):          be11ee20  00000000  
D/CrashAnrDetector( 1013):          be11ee24  00000000  
D/CrashAnrDetector( 1013):          be11ee28  00000000  
D/CrashAnrDetector( 1013):          be11ee2c  00000000  
D/CrashAnrDetector( 1013):          be11ee30  00000000  
D/CrashAnrDetector( 1013):          be11ee34  00000000  
D/CrashAnrDetector( 1013):          be11ee38  00000000  
D/CrashAnrDetector( 1013):          be11ee3c  00000000  
D/CrashAnrDetector( 1013):          be11ee40  00000000  
D/CrashAnrDetector( 1013):          be11ee44  00000000  
D/CrashAnrDetector( 1013):          be11ee48  00000000  
D/CrashAnrDetector( 1013):          be11ee4c  00000000  
D/CrashAnrDetector( 1013):          be11ee50  00000000  
D/CrashAnrDetector( 1013):          be11ee54  00000000  
D/CrashAnrDetector( 1013):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1013):          be11ee5c  00000000  
D/CrashAnrDetector( 1013):          be11ee60  00000000  
D/CrashAnrDetector( 1013):          be11ee64  00000000  
D/CrashAnrDetector( 1013):          be11ee68  00000000  
D/CrashAnrDetector( 1013):          be11ee6c  00000000  
D/CrashAnrDetector( 1013):          be11ee70  00000000  
D/CrashAnrDetector( 1013):          be11ee74  00000000  
D/CrashAnrDetector( 1013):          be11ee78  00000000  
D/CrashAnrDetector( 1013):          be11ee7c  00000000  
D/CrashAnrDetector( 1013):          be11ee80  00000000  
D/CrashAnrDetector( 1013):          be11ee84  00000000  
D/CrashAnrDetector( 1013):          be11ee88  00000000  
D/CrashAnrDetector( 1013):          be11ee8c  00000000  
D/CrashAnrDetector( 1013):          be11ee90  00000000  
D/CrashAnrDetector( 1013):          be11ee94  00000000  
D/CrashAnrDetector( 1013):          be11ee98  00000000  
D/CrashAnrDetector( 1013):          be11ee9c  00000000  
D/CrashAnrDetector( 1013):          be11eea0  00000000  
D/CrashAnrDetector( 1013):          be11eea4  00000000  
D/CrashAnrDetector( 1013):          be11eea8  00000000  
D/CrashAnrDetector( 1013):          be11eeac  00000000  
D/CrashAnrDetector( 1013):          be11eeb0  00000000  
D/CrashAnrDetector( 1013):          be11eeb4  00000000  
D/CrashAnrDetector( 1013):          be11eeb8  00000000  
D/CrashAnrDetector( 1013):          be11eebc  00000000  
D/CrashAnrDetector( 1013):         
D/CrashAnrDetector( 1013): processName:com.test.thalitest
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1013): broadcastEvent : null SYSTEM_TOMBSTONE
D/SettingsProvider( 1013): name = db_smartlock_supported
I/BootReceiver( 1013): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/AccessibilityManagerService( 1013): setmDNIeNegative (false)
,D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 10813, tid: 10813, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1013):     r0 b92c7dd0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1013):     r4 0045b0a0  r5 be11f218  r6 b92c7dd0  r7 be11f228
D/CrashAnrDetector( 1013):     r8 be11ee60  r9 b9a6af30  sl b9a6af30  fp be11f1dc
D/CrashAnrDetector( 1013):     ip be11f228  sp be11ee58  lr a0d6430c  pc a0d63d98  cpsr a00f0010
D/CrashAnrDetector( 1013):     d0  ffffff859ec579c0  d1  0000000000000000
D/CrashAnrDetector( 1013):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1013):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1013):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1013):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1013):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1013):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1013):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1013):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1013):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1013):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1013):     scr 20000012
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1013):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1013):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1013):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          be11edd8  00000000  
D/CrashAnrDetector( 1013):          be11eddc  00000000  
D/CrashAnrDetector( 1013):          be11ede0  00000000  
D/CrashAnrDetector( 1013):          be11ede4  00000000  
D/CrashAnrDetector( 1013):          be11ede8  00000000  
D/CrashAnrDetector( 1013):          be11edec  00000000  
D/CrashAnrDetector( 1013):          be11edf0  00000000  
D/CrashAnrDetector( 1013):          be11edf4  00000000  
D/CrashAnrDetector( 1013):          be11edf8  00000000  
D/CrashAnrDetector( 1013):          be11edfc  00000000  
D/CrashAnrDetector( 1013):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1013):          be11ee04  00000000  
D/CrashAnrDetector( 1013):          be11ee08  00000000  
D/CrashAnrDetector( 1013):          be11ee0c  00000000  
D/CrashAnrDetector( 1013):          be11ee10  00000000  
D/CrashAnrDetector( 1013):          be11ee14  00000000  
D/CrashAnrDetector( 1013):          be11ee18  00000000  
D/CrashAnrDetector( 1013):          be11ee1c  00000000  
D/CrashAnrDetector( 1013):          be11ee20  00000000  
D/CrashAnrDetector( 1013):          be11ee24  00000000  
D/CrashAnrDetector( 1013):          be11ee28  00000000  
D/CrashAnrDetector( 1013):          be11ee2c  00000000  
D/CrashAnrDetector( 1013):          be11ee30  00000000  
D/CrashAnrDetector( 1013):          be11ee34  00000000  
D/CrashAnrDetector( 1013):          be11ee38  00000000  
D/CrashAnrDetector( 1013):          be11ee3c  00000000  
D/CrashAnrDetector( 1013):          be11ee40  00000000  
D/CrashAnrDetector( 1013):          be11ee44  00000000  
D/CrashAnrDetector( 1013):          be11ee48  00000000  
D/CrashAnrDetector( 1013):          be11ee4c  00000000  
D/CrashAnrDetector( 1013):          be11ee50  00000000  
D/CrashAnrDetector( 1013):          be11ee54  00000000  
D/CrashAnrDetector( 1013):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1013):          be11ee5c  00000000  
D/CrashAnrDetector( 1013):          be11ee60  00000000  
D/CrashAnrDetector( 1013):          be11ee64  00000000  
D/CrashAnrDetector( 1013):          be11ee68  00000000  
D/CrashAnrDetector( 1013):          be11ee6c  00000000  
D/CrashAnrDetector( 1013):          be11ee70  00000000  
D/CrashAnrDetector( 1013):          be11ee74  00000000  
D/CrashAnrDetector( 1013):          be11ee78  00000000  
D/CrashAnrDetector( 1013):          be11ee7c  00000000  
D/CrashAnrDetector( 1013):          be11ee80  00000000  
D/CrashAnrDetector( 1013):          be11ee84  00000000  
D/CrashAnrDetector( 1013):          be11ee88  00000000  
D/CrashAnrDetector( 1013):          be11ee8c  00000000  
D/CrashAnrDetector( 1013):          be11ee90  00000000  
D/CrashAnrDetector( 1013):          be11ee94  00000000  
D/CrashAnrDetector( 1013):          be11ee98  00000000  
D/CrashAnrDetector( 1013):          be11ee9c  00000000  
D/CrashAnrDetector( 1013):          be11eea0  00000000  
D/CrashAnrDetector( 1013):          be11eea4  00000000  
D/CrashAnrDetector( 1013):          be11eea8  00000000  
D/CrashAnrDetector( 1013):          be11eeac  00000000  
D/CrashAnrDetector( 1013):          be11eeb0  00000000  
D/CrashAnrDetector( 1013):          be11eeb4  00000000  
D/CrashAnrDetector( 1013):          be11eeb8  00000000  
D/CrashAnrDetector( 1013):          be11eebc  00000000  
D/CrashAnrDetector( 1013):       
D/CrashAnrDetector( 1013): processName:com.test.thalitest
D/CrashAnrDetector( 1013): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/BootReceiver( 1013): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 6058, tid: 6772, name: Thread-1061  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9c909ff0
D/CrashAnrDetector( 1013):     r0 710804a8  r1 735927c8  r2 12dd4780  r3 13533ec0
D/CrashAnrDetector( 1013):     r4 000000c2  r5 710804a8  r6 735927c8  r7 13533ec0
D/CrashAnrDetector( 1013):     r8 73592770  r9 ba677458  sl 12dd4780  fp 9ca0b8a8
D/CrashAnrDetector( 1013):     ip 9c909ff0  sp 9c90bff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1013):     d0  12dd4780735927c0  d1  007300200065003e
D/CrashAnrDetector( 1013):     d2  c0c0c0c0c0c0c053  d3  0102020202020213
D/CrashAnrDetector( 1013):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1013):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1013):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1013):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1013):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1013):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1013):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1013):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1013):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1013):     scr 20000013
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1013):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          9c90bf70  00000000  
D/CrashAnrDetector( 1013):          9c90bf74  00000000  
D/CrashAnrDetector( 1013):          9c90bf78  00000000  
D/CrashAnrDetector( 1013):          9c90bf7c  00000000  
D/CrashAnrDetector( 1013):          9c90bf80  00000000  
D/CrashAnrDetector( 1013):          9c90bf84  00000000  
D/CrashAnrDetector( 1013):          9c90bf88  00000000  
D/CrashAnrDetector( 1013):          9c90bf8c  00000000  
D/CrashAnrDetector( 1013):          9c90bf90  00000000  
D/CrashAnrDetector( 1013):          9c90bf94  00000000  
D/CrashAnrDetector( 1013):          9c90bf98  00000000  
D/CrashAnrDetector( 1013):          9c90bf9c  00000000  
D/CrashAnrDetector( 1013):          9c90bfa0  00000000  
D/CrashAnrDetector( 1013):          9c90bfa4  00000000  
D/CrashAnrDetector( 1013):          9c90bfa8  00000000  
D/CrashAnrDetector( 1013):          9c90bfac  00000000  
D/CrashAnrDetector( 1013):          9c90bfb0  00000000  
D/CrashAnrDetector( 1013):          9c90bfb4  00000000  
D/CrashAnrDetector( 1013):          9c90bfb8  00000000  
D/CrashAnrDetector( 1013):          9c90bfbc  00000000  
D/CrashAnrDetector( 1013):          9c90bfc0  00000000  
D/CrashAnrDetector( 1013):          9c90bfc4 , 00000000  
D/CrashAnrDetector( 1013):          9c90bfc8  00000000  
D/CrashAnrDetector( 1013):          9c90bfcc  00000000  
D/CrashAnrDetector( 1013):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90bfd4  00000000  
D/CrashAnrDetector( 1013):          9c90bfd8  00000000  
D/CrashAnrDetector( 1013):          9c90bfdc  00000000  
D/CrashAnrDetector( 1013):          9c90bfe0  00000000  
D/CrashAnrDetector( 1013):          9c90bfe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90bfe8  e3a070ad  
D/CrashAnrDetector( 1013):          9c90bfec  ef9000ad  
D/CrashAnrDetector( 1013):     #00  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          ........  ........
D/CrashAnrDetector( 1013):     #01  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90bff4  00000000  
D/CrashAnrDetector( 1013):          9c90bff8  00000000  
D/CrashAnrDetector( 1013):          9c90bffc  00000000  
D/CrashAnrDetector( 1013):          9c90c000  00000000  
D/CrashAnrDetector( 1013):          9c90c004  00000000  
D/CrashAnrDetector( 1013):          9c90c008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c00c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c010  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1013):          9c90c014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c018  12dd4780  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1013):          9c90c01c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1013):          9c90c020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c024  00000000  
D/CrashAnrDetector( 1013):          9c90c028  00000000  
D/CrashAnrDetector( 1013):          9c90c02c  00000000  
D/CrashAnrDetector( 1013):          9c90c030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c034  00000000  
D/CrashAnrDetector( 1013):          9c90c038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c03c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          9c90c040  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1013):          9c90c044  73
D/CrashAnrDetector( 1013): processName:com.test.thalitest
D/CrashAnrDetector( 1013): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/BootReceiver( 1013): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1013): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 6080, tid: 6935, name: Thread-1071  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa37a6ff0
D/CrashAnrDetector( 1013):     r0 710804a8  r1 735927c8  r2 12e00890  r3 133c2fc0
D/CrashAnrDetector( 1013):     r4 000000c2  r5 710804a8  r6 735927c8  r7 133c2fc0
D/CrashAnrDetector( 1013):     r8 73592770  r9 b8284ec8  sl 12e00890  fp a38a88a8
D/CrashAnrDetector( 1013):     ip a37a6ff0  sp a37a8ff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1013):     d0  12e00890735927c0  d1  007300200065002f
D/CrashAnrDetector( 1013):     d2  c0c0c0c0c0c0c03c  d3  0102020202020213
D/CrashAnrDetector( 1013):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1013):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1013):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1013):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1013):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1013):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1013):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1013):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1013):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1013):     scr 20000013
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1013):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          a37a8f70  00000000  
D/CrashAnrDetector( 1013):          a37a8f74  00000000  
D/CrashAnrDetector( 1013):          a37a8f78  00000000  
D/CrashAnrDetector( 1013):          a37a8f7c  00000000  
D/CrashAnrDetector( 1013):          a37a8f80  00000000  
D/CrashAnrDetector( 1013):          a37a8f84  00000000  
D/CrashAnrDetector( 1013):          a37a8f88  00000000  
D/CrashAnrDetector( 1013):          a37a8f8c  00000000  
D/CrashAnrDetector( 1013):          a37a8f90  00000000  
D/CrashAnrDetector( 1013):          a37a8f94  00000000  
D/CrashAnrDetector( 1013):          a37a8f98  00000000  
D/CrashAnrDetector( 1013):          a37a8f9c  00000000  
D/CrashAnrDetector( 1013):          a37a8fa0  00000000  
D/CrashAnrDetector( 1013):          a37a8fa4  00000000  
D/CrashAnrDetector( 1013):          a37a8fa8  00000000  
D/CrashAnrDetector( 1013):          a37a8fac  00000000  
D/CrashAnrDetector( 1013):          a37a8fb0  00000000  
D/CrashAnrDetector( 1013):          a37a8fb4  00000000  
D/CrashAnrDetector( 1013):          a37a8fb8  00000000  
D/CrashAnrDetector( 1013):          a37a8fbc  00000000  
D/CrashAnrDetector( 1013):          a37a8fc0  00000000  
D/CrashAnrDetector( 1013):          a37a8fc4 , 00000000  
D/CrashAnrDetector( 1013):          a37a8fc8  00000000  
D/CrashAnrDetector( 1013):          a37a8fcc  00000000  
D/CrashAnrDetector( 1013):          a37a8fd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a8fd4  00000000  
D/CrashAnrDetector( 1013):          a37a8fd8  00000000  
D/CrashAnrDetector( 1013):          a37a8fdc  00000000  
D/CrashAnrDetector( 1013):          a37a8fe0  00000000  
D/CrashAnrDetector( 1013):          a37a8fe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a8fe8  e3a070ad  
D/CrashAnrDetector( 1013):          a37a8fec  ef9000ad  
D/CrashAnrDetector( 1013):     #00  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          ........  ........
D/CrashAnrDetector( 1013):     #01  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a8ff4  00000000  
D/CrashAnrDetector( 1013):          a37a8ff8  00000000  
D/CrashAnrDetector( 1013):          a37a8ffc  00000000  
D/CrashAnrDetector( 1013):          a37a9000  00000000  
D/CrashAnrDetector( 1013):          a37a9004  00000000  
D/CrashAnrDetector( 1013):          a37a9008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a900c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a9010  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1013):          a37a9014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a9018  12e00890  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1013):          a37a901c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1013):          a37a9020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a9024  00000000  
D/CrashAnrDetector( 1013):          a37a9028  00000000  
D/CrashAnrDetector( 1013):          a37a902c  00000000  
D/CrashAnrDetector( 1013):          a37a9030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a9034  00000000  
D/CrashAnrDetector( 1013):          a37a9038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a903c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1013):          a37a9040  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1013):          a37a9044  73
D/CrashAnrDetector( 1013): processName:com.test.thalitest
D/CrashAnrDetector( 1013): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/Settings( 1290): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1013): name = block_emergency_message
,D/SettingsProvider( 1013): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/CrashAnrDetector( 1013): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1013): Hardware: MSM8916
D/CrashAnrDetector( 1013): Revision: 2
D/CrashAnrDetector( 1013): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1013): Radio: unknown
D/CrashAnrDetector( 1013): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1013): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1013): Revision: '2'
D/CrashAnrDetector( 1013): ABI: 'arm'
D/CrashAnrDetector( 1013): pid: 2458, tid: 2624, name: Thread-256  >>> com.example.hello <<<
D/CrashAnrDetector( 1013): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1013):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1013):     r4 9dddde78  r5 9dddde38  r6 b8adc500  r7 9dddde38
D/CrashAnrDetector( 1013):     r8 00000000  r9 9dddde74  sl 9dddf3d0  fp 9dddde1c
D/CrashAnrDetector( 1013):     ip 9d93cba0  sp 9dddde00  lr 9d643308  pc b6f2d468  cpsr 600d0030
D/CrashAnrDetector( 1013):     d0  513802003a373ed5  d1  0000b80c030000a1
D/CrashAnrDetector( 1013):     d2  88000000560a109d  d3  0000003502000060
D/CrashAnrDetector( 1013):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1013):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1013):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1013):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1013):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1013):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1013):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1013):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1013):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1013):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1013):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1013):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1013):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1013):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1013):     scr 20000012
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): backtrace:
D/CrashAnrDetector( 1013):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1013):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1013): 
D/CrashAnrDetector( 1013): stack:
D/CrashAnrDetector( 1013):          9ddddd80  00000000  
D/CrashAnrDetector( 1013):          9ddddd84  00000000  
D/CrashAnrDetector( 1013):          9ddddd88  9cd2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1013):          9ddddd8c  e8bc0f76  
D/CrashAnrDetector( 1013):          9ddddd90  9dddddbc  [stack:2624]
D/CrashAnrDetector( 1013):          9ddddd94  9dddde64  [stack:2624]
D/CrashAnrDetector( 1013):          9ddddd98  b8adc500  [heap]
D/CrashAnrDetector( 1013):          9ddddd9c  00000003  
D/CrashAnrDetector( 1013):          9ddddda0  9ddddddc  [stack:2624]
D/CrashAnrDetector( 1013):          9ddddda4  b8b162a8  [heap]
D/CrashAnrDetector( 1013):          9ddddda8  9cd53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1013):          9dddddac  9da11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1013):          9dddddb0  00000000  
D/CrashAnrDetector( 1013):          9dddddb4  ffffff82  
D/CrashAnrDetector( 1013):          9dddddb8  00000000  
D/CrashAnrDetector( 1013):          9dddddbc  ffffff82  
D/CrashAnrDetector( 1013):          9dddddc0  9cd2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1013):          9dddddc4  b8b132a8  [heap]
D/CrashAnrDetector( 1013):,          9dddddc8  b8bcbd18  [heap]
D/CrashAnrDetector( 1013):          9dddddcc  00000001  
D/CrashAnrDetector( 1013):          9dddddd0  9cd49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1013):          9dddddd4  b8adc500  [heap]
D/CrashAnrDetector( 1013):          9dddddd8  9cd4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1013):          9ddddddc  00000000  
D/CrashAnrDetector( 1013):          9ddddde0  00000000  
D/CrashAnrDetector( 1013):          9ddddde4  00000000  
D/CrashAnrDetector( 1013):          9ddddde8  00000003  
D/CrashAnrDetector( 1013):          9dddddec  000000aa  
D/CrashAnrDetector( 1013):          9dddddf0  0000006b  
D/CrashAnrDetector( 1013):          9dddddf4  0001416e  
D/CrashAnrDetector( 1013):          9dddddf8  00000000  
D/CrashAnrDetector( 1013):          9dddddfc  9dddde30  [stack:2624]
D/CrashAnrDetector( 1013):     #00  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1013):          ........  ........
D/CrashAnrDetector( 1013):     #01  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde04  00000000  
D/CrashAnrDetector( 1013):          9dddde08  9dddde78  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde0c  9dddde5c  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde10  9dddde48  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde14  00000000  
D/CrashAnrDetector( 1013):          9dddde18  9dddee94  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde1c  9d61a3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1013):          9dddde20  9dddde50  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde24  00000000  
D/CrashAnrDetector( 1013):          9dddde28  9dddde44  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde2c  9d44c184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1013):          9dddde30  00000000  
D/CrashAnrDetector( 1013):          9dddde34  00000000  
D/CrashAnrDetector( 1013):          9dddde38  b6f73de4  
D/CrashAnrDetector( 1013):          9dddde3c  00000000  
D/CrashAnrDetector( 1013):          9dddde40  9ddde1cc  [stack:2624]
D/CrashAnrDetector( 1013):          9dddde44  9d528b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1013):          9dddde48  b8adc500  [heap]
D/CrashAnrDetector( 1013):          9dddde4c  b8adc500  [heap]
D/CrashAnrDetector( 1013):          9dddde50  b8bcbd18  [heap]
D/CrashAnrDetector( 1013):          9dddde54  00000001  
D/CrashAnrDetector( 1013):          9dddde58  9
D/CrashAnrDetector( 1013): processName:com.example.hello
D/CrashAnrDetector( 1013): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,W/CursorWrapperInner( 2282): Cursor finalized without prior close()
,I/art     ( 1013): Background sticky concurrent mark sweep GC freed 31020(2MB) AllocSpace objects, 105(8MB) LOS objects, 27% free, 27MB/37MB, paused 2.614ms total 105.739ms
,D/[LPC]   ( 1013): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2712): MountEmulatedStorage()
,E/Zygote  ( 2712): v2
I/libpersona( 2712): KNOX_SDCARD checking this for 1000
I/libpersona( 2712): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 2712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2712): TimaSignature is unavailable
,D/ActivityThread( 2712): Added TimaKeyStore provider
,W/ResourcesManager( 2712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 2712): (539) recovered 3 pages from /data/user/0/com.samsung.android.sm/databases/lowpowercontext-system-db-journal,
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,I/i       ( 1013): No model
,D/FactoryTest( 1013): Not factory mode
D/FactoryTest( 1013): Not factory mode. isFactoryMode() returend false
D/w       ( 1013): isUserBuild = true
,D/SSRM:aZ ( 1013): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1013): Updating Threshold Value.. isSystemReady: true
,E/SmartFaceService( 1013): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1013): no icon
E/SmartFaceService( 1013): mActiveServiceType: 0
,D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1013): [SO] activate (ident=0xb8c81468, enabled=0)
E/SmartFaceService( 1013): mLightIntensityEnough: true mLux: 0.0
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/Stay/Rotation Worker( 1013): updateClientsDone. def. do nothing.,
E/SmartFaceService( 1013): Service Type to Worker: 0
E/SmartFaceService( 1013): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1013): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/SensorManager( 1013): unregisterListener ::   
,I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1013): [SO] changed settle time [0]
,D/SensorService( 1013): [SO] setDelay [200000000]
D/SensorService( 1013): [SO] activate (ident=0xb8c81468, enabled=1)
D/SensorService( 1013): [SO] AR_init
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,V/AlarmManagerEXT( 1013): mGmsLocationBundling: false
,D/SSRM:n  ( 1013): SIOP:: AP = 350
,I/ActivityManager( 1013): Killing 1186:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,D/RCPManagerService( 1013): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1013):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/RCPManagerService( 1013): BootReceiver.onReceive(): Starting RCP Proxy for user = null
D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
E/RCPManagerService( 1013):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1013):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/SSRM:a  ( 1013): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1013): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1013):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1013): [SO] activate (ident=0xb8c81468, enabled=0)
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_1186/cgroup.procs: No such file or directory
,D/SensorManager( 1013): unregisterListener ::   
I/Sensors ( 1013): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1013): [SO] changed settle time [1]
D/SensorService( 1013): [SO] setDelay [66000000]
D/SensorService( 1013): [SO] activate (ident=0xb8c81468, enabled=1)
D/SensorService( 1013): [SO] AR_init
I/Sensors ( 1013): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1013): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/EnterpriseDeviceManagerService( 1013): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1013): runAdminUpdate
D/EnterpriseUtils( 1013): File Not Found : /data/system/selfUpdateAdmin.conf
,V/ApplicationPolicy( 1013): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1013): refresh widget status for user 0
D/EnterpriseDeviceManagerService( 1013): nothing to selfUpdate
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
,V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1013): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,W/PhoneRestrictionPolicy( 1013): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler },
,D/KnoxMUMContainerPolicy( 1013): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy( 1013): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1013):  >>>> deliveryBlockedMsgs
,D/WifiP2pService( 1013): P2pDisabledState{ what=143415 }
,D/WifiP2pService( 1013): DefaultState{ what=143415 }
,W/PhoneRestrictionPolicy( 1013): cvList size 0
,D/Tethering( 1013): Boot complete.
,W/PhoneRestrictionPolicy( 1013):  >>>> deliveryBlockedMsgs
D/ConnectivityService( 1013): Got NetworkFactory Messenger for WIFI,
W/PhoneRestrictionPolicy( 1013): cvList size 0
D/ConnectivityService( 1013): Got NetworkFactory Messenger for WIFI_P2P,
D/WIFI_P2P( 1013): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI_P2P( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
V/EnterpriseBillingEngine( 1013): ACTION_BOOT_COMPLETED
E/WifiStateMachine( 1013): Blacklist file delete
V/EnterpriseBillingEngine( 1013): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1013): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1013): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1013): handleAllprofiles - end
,D/UsbHostNotification( 1013): boot completed
,D/UsbHostRestrictor( 1013): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1013): initSetUsbBlock STARTED
,D/SensorService( 1013): [SO] Reset Rotation Old [100], Init [1]
,D/UsbHostRestrictor( 1013): SIM was never inserted
D/UsbHostRestrictor( 1013): writableHostSysNode[false]
D/UsbHostRestrictor( 1013): Can NOT Write Disable Sys Node to [ON]
,D/PersonaManagerService( 1013): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1013):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1013): onBootComplete
,D/UsbStorageNotification( 1013): boot completed
,D/WIFI    ( 1013): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1013): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/GpsLocationProvider( 1013): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1013): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1013): set_capabilities_callback: 55u
I/KnoxKeyguardUpdateMonitor( 1013): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1013): onTrustChanged user:0, enable:false
D/KeyguardViewMediator( 1175): onTrustChanged( Showing = false , userId = 0 )
,I/libmdmdetect( 1013): ESOC framework not supported
,D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,D/qmi_secgps_clnt( 1013): qmi_secgps_client_init()
,I/libmdmdetect( 1013): Found internal modem: modem
E/PerMgrLib( 1013): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1013): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1013): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1013): BOOT_COMPLETED native_cleanup 
,D/PackageManager( 1013): [MSG] MCS_UNBIND
,D/qmi_secgps_clnt( 1013): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/StorageNotification( 1175): boot completed
,D/qmi_secgps_clnt( 1013): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2,
,D/qmi_secgps_clnt( 1013): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,D/SensorService( 1013): [SO] 0.115 0.383 10.094
D/SensorService( 1013): [SO] [100 -> 255]
,I/ActivityManager( 1013): Killing 1384:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/StatusBarManagerService( 1013): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/PhoneStatusBar( 1175): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1013): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2747): MountEmulatedStorage()
I/libpersona( 2747): KNOX_SDCARD checking this for 10099,
E/Zygote  ( 2747): v2,
I/libpersona( 2747): KNOX_SDCARD not a persona
E/USB_UICC(  300): Timeout! No signal received. Retry num = 26
I/SELinux ( 2747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2747 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 2747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2747): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_10096/pid_1384/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2747): TimaSignature is unavailable
,D/ActivityThread( 2747): Added TimaKeyStore provider
,E/LocSvc_utils_cfg( 1013): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,I/qmi_secgps_clnt( 1013): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt( 1013): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1013): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1013): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt( 1013): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt( 1013): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1013): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1013): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1013): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1013): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1013): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1013): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1013): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1013): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,E/ActivityThread( 2747): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2747): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1013): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1013): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/ActivityManager( 1013): Killing 1567:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/DrmEventReceiver( 1013): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1013): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1013): DrmEventReceiver : beginStartingService
I/System.out( 1013): start Service
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1223): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2764): MountEmulatedStorage()
E/Zygote  ( 2764): v2
I/libpersona( 2764): KNOX_SDCARD checking this for 1000
I/libpersona( 2764): KNOX_SDCARD not a persona
I/SELinux ( 2764): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2764): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2764): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2764 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1013): startService callerProcessName:android, calleePkgName: android,
D/ActivityManager( 1013): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2764): TimaSignature is unavailable
,D/ActivityThread( 2764): Added TimaKeyStore provider
E/Zygote  ( 2782): MountEmulatedStorage()
E/Zygote  ( 2782): v2
I/libpersona( 2782): KNOX_SDCARD checking this for 10152
I/libpersona( 2782): KNOX_SDCARD not a persona
,I/SELinux ( 2782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/WVMDrmPlugIn(  280): WVMDrmPlugin::onInitialize : 702
D/WVMDrmPlugIn(  280): WVMDrmPlugin::onSetOnInfoListener : add 702
D/SecContentProvider2( 1013): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1013): mCursor = null
,I/ActivityManager( 1013): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2782 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 2782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DrmEventService( 1013): action event :android.intent.action.BOOT_COMPLETED
,I/TimaServiceEventReceiver( 1013): TimaServiceEventReceiver : onReceive
,D/MediaScannerReceiver( 1223): action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,I/ANDROID_DRM_FRWORKS_DrmManager(  280): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ResourcesManager( 2764): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/CscReceiver( 1442): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/TimaKeyStoreProvider( 2782): TimaSignature is unavailable
,D/ActivityThread( 2782): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,D/BluetoothBDAdrressReceiver( 2764): onReceive(), action: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 2764): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1442): onStart
E/CscUpdateService( 1442): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1442): set_CSC_version
E/CscParser( 1442): update(): xml file exist
,E/Zygote  ( 2799): MountEmulatedStorage()
,E/Zygote  ( 2799): v2
I/libpersona( 2799): KNOX_SDCARD checking this for 10003
I/libpersona( 2799): KNOX_SDCARD not a persona
,I/SELinux ( 2799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_1567/cgroup.procs: No such file or directory
,I/ActivityManager( 1013): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2799 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
I/SELinux ( 2799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,I/CscUtil ( 1442): isWifiOnly = false,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/System.out( 1442): HandDataNode = null
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/CscUpdateService( 1442): PATH_CSCNAME =CustomerDataSet.CSCName
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/CscUpdateService( 1442): This is normal boot : CSC not updated
,E/Zygote  ( 2812): MountEmulatedStorage()
I/libpersona( 2812): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2812): v2
I/libpersona( 2812): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2812 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 1528:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/SELinux ( 2812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/CscParser( 1442): update(): xml file exist
I/SELinux ( 2812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 2799): TimaSignature is unavailable
D/ActivityThread( 2799): Added TimaKeyStore provider
E/SELinux ( 2812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CscUpdateService( 1442): same CSC Version
D/CscUtil ( 1442): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,D/CscGPS  ( 1442): CSCGPS.updateParameters
D/CscGPS  ( 1442): supl host : null
D/CscGPS  ( 1442): SUPL Host is null or invalid
D/CscGPS  ( 1442): supl_ver : null
D/CscGPS  ( 1442): SUPL Ver is null or invalid
D/CscGPS  ( 1442): supl port : null
D/CscGPS  ( 1442): SUPL PORT is null or invalid
D/CscGPS  ( 1442): LPP : null
D/CscGPS  ( 1442): LPP is null or invalid
D/CscGPS  ( 1442): CSC don't have any AGPS value.
,W/ResourcesManager( 1442): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1442): onCreate()
,E/BluetoothBDTestService( 1442): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1442): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1442): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/SQLiteLog( 2782): (284) automatic index on shooting_modes(title_id)
,D/TimaKeyStoreProvider( 2812): TimaSignature is unavailable
,D/ActivityThread( 2812): Added TimaKeyStore provider,
D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/MediaScannerService( 1223): !@start scanning volume internal: [/system/media, /oem/media]
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
,W/ResourcesManager( 2812): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 2835): MountEmulatedStorage(),
I/libpersona( 2835): KNOX_SDCARD checking this for 1101
E/Zygote  ( 2835): v2
I/libpersona( 2835): KNOX_SDCARD not a persona
I/SELinux ( 2835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2835 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/SELinux ( 2835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsProvider( 1442): Update uri=content://mms, match=0
D/TP/MmsProvider( 1442): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1442): need read changed broadcast:false
,I/Mms:transaction( 2282): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2282): [start]    nonBlockingUpdateMessageIndicator() consume time = 3095.945728
,I/Mms/ReservationManager( 2282): resetAfterConnected()
E/SQLiteLog( 1223): (283) recovered 175 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,D/TP/MmsSmsProvider( 1442): query,matched:7, calling pid = 2282
,D/Mms/MessagingNotification( 2282): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2282): isDefault true
,D/TP/MmsSmsProvider( 1442): match 7:Elapsed time : 7.652 ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 25.714ms
W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_1528/cgroup.procs: No such file or directory
,D/TP/MmsProvider( 1442): Query uri=content://mms, match=0, calling pid = 2282
,I/Mms/ReservationManager( 2282): getReservedSendMessageCount(): retMessageCount=0
,D/TimaKeyStoreProvider( 2835): TimaSignature is unavailable
,D/ActivityThread( 2835): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 1442): query,matched:200, calling pid = 2282
,D/TP/MmsSmsProvider( 1442): match 200:Elapsed time : 2.113 ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.168ms
D/ActivityManager( 1013): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ResourcesManager( 2835): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1442): query,matched:0, calling pid = 2282
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/TP/SmsProvider( 1442): match 0:Elapsed time : 1.574 ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.586ms
,V/SmartcardService( 2835): main Received broadcast
V/SmartcardService( 2835): Starting smartcard service after boot completed
,D/SSRM:a  ( 1013): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1013): SettingsAirViewInfo:: 000000000
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
I/libpersona( 2854): KNOX_SDCARD checking this for 10048
E/Zygote  ( 2854): MountEmulatedStorage()
I/libpersona( 2854): KNOX_SDCARD not a persona
E/Zygote  ( 2854): v2
I/SELinux ( 2854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2854 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1013): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1013): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,I/ActivityManager( 1013): Killing 1818:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
D/MediaScanner( 1223): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/SensorService( 1013): [SO] 0.096 0.383 10.094
,D/PersonaManagerService( 1013): getPersonasForUser(): returning null!
,D/ActivityManager( 1013): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/TimaKeyStoreProvider( 2854): TimaSignature is unavailable
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0,
D/Mms/SmsReceiverService( 2282): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/ActivityThread( 2854): Added TimaKeyStore provider
,D/Mms/TelephonyPermission( 2282): isDefault true
D/Mms/SmsReceiverService( 2282): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2282): [start]    handleBootCompleted() consume time = 123.066458
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/TP/SmsProvider( 1442): query,matched:51, calling pid = 2282
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,D/TP/SmsProvider( 1442): match 51:Elapsed time : 2.065 ms
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 2812): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/SecureStorage(  408): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2799
,I/SecureStorage(  408): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
,I/KnoxUsageLogPro( 2812): savePreference: key = previous_sys_time value = 1457596417141
,I/SecureStorage( 2799): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2799): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  408): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2799
,I/SecureStorage(  408): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,E/Zygote  ( 2874): MountEmulatedStorage()
E/Zygote  ( 2874): v2
I/libpersona( 2874): KNOX_SDCARD checking this for 10157
I/libpersona( 2874): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2874 uid=10157 gids={50157, 9997} abi=armeabi-v7a
D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/KnoxUsageLogPro( 2812): premStatus:2
,I/SELinux ( 2874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/libprocessgroup( 1013): failed to open /acct/uid_10138/pid_1818/cgroup.procs: No such file or directory
,I/SELinux ( 2874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KnoxUsageLogPro( 2812): isEulaShown : false
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
I/KnoxUsageLogPro( 2812): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
V/MediaScanner( 1223): processDirectory :  /system/media
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2854): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2854): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2854): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
I/KnoxUsageLogPro( 2812): savePreference: key = previous_elapsed_time value = 33295
,E/Zygote  ( 2886): MountEmulatedStorage()
,E/Zygote  ( 2886): v2
I/libpersona( 2886): KNOX_SDCARD checking this for 1000
I/libpersona( 2886): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2886 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2874): TimaSignature is unavailable
,D/ActivityThread( 2874): Added TimaKeyStore provider
,I/SELinux ( 2886): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2886): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
V/MediaScanner( 1223):  prescan time: 204ms (DB items: 141)
V/MediaScanner( 1223):     scan time: 53ms (Caching mode: true), (makeEntry time: 27ms ~50%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 4ms ~7%)
V/MediaScanner( 1223): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 257ms
V/MediaScanner( 1223): checked files: 133  directories : 6  (I: 0, U: 0),
,E/SELinux ( 2886): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScanner( 1223): checkDefaultSounds
D/MediaScanner( 1223): system alarm_alert  : Vwiurug_etwofi5wgg
,I/ActivityManager( 1013): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2896 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 2896): MountEmulatedStorage(),
I/libpersona( 2896): KNOX_SDCARD checking this for 10085
E/Zygote  ( 2896): v2
I/libpersona( 2896): KNOX_SDCARD not a persona
I/SELinux ( 2896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Killing 1520:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/SELinux ( 2896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1013): name = block_emergency_message
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10048
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/ActivityManager( 1013): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/TimaKeyStoreProvider( 2886): TimaSignature is unavailable
,D/ActivityThread( 2886): Added TimaKeyStore provider
,W/ResourcesManager( 2874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 2282): isBlockingModeEnabled() = false, Zen mode = 0
,D/TP/MmsSmsProvider( 1442): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1442): deleteConversation threadId: 9223372036854775806
D/MediaScanner( 1223): OK. alarm_alert is already exist in setting DB.
,D/MediaScanner( 1223): system notification_sound  : K_Oprkltf5wgg
,D/TP/MmsSmsProvider( 1442): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1442): updateThread(), thread_id = 9223372036854775806
,D/TimaKeyStoreProvider( 2896): TimaSignature is unavailable
D/MediaScanner( 1223): OK. notification_sound is already exist in setting DB.
D/ActivityThread( 2896): Added TimaKeyStore provider
,D/MediaScanner( 1223): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/ActivityManager( 1013): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
V/TP/MmsSmsDatabaseHelper( 1442): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
,I/WifiCredService( 1290): onCreate
D/MediaScanner( 1223): OK. ringtone is already exist in setting DB.
,D/TP/MmsSmsProvider( 1442): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1442): need read changed broadcast:false
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2922): MountEmulatedStorage(),
W/ResourcesManager( 2896): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
E/Zygote  ( 2922): v2
I/libpersona( 2922): KNOX_SDCARD checking this for 10159
I/SELinux ( 2922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 2896): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/libpersona( 2922): KNOX_SDCARD not a persona
W/ResourcesManager( 2896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 2896): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2896): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2922 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2096:com.vlingo.midas/u0a31 (adj 15): empty #31
,I/SELinux ( 2922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2922): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/Mms/Conversation( 2282): deleteTempConversation(),deleted=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/WifiTimerReceiver( 1290): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1290): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1290): Action boot completed received
D/MediaScannerService( 1223): !@done scanning volume internal
D/TimaKeyStoreProvider( 2922): TimaSignature is unavailable
D/ActivityThread( 2922): Added TimaKeyStore provider
,E/Zygote  ( 2933): MountEmulatedStorage()
I/libpersona( 2933): KNOX_SDCARD checking this for 10072
E/Zygote  ( 2933): v2
I/libpersona( 2933): KNOX_SDCARD not a persona
,I/SELinux ( 2933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=2933 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 2933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,E/SELinux ( 2933): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/MediaScannerService( 1223): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/SmsProvider( 1442): Update uri=content://sms/outbox, match=8
,D/NearbySettings( 1290): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1290): MountReceiver.onReceive - Start HandlerThread
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,D/NearbySettings( 1290): MountReceiver.onReceive - Create mPrefHandler
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1442): need read changed broadcast:false
,D/Mms/SmsReceiverService( 2282): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2282): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2282): [SIM-1]sendFirstQueuedMessage()
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
,D/TimaKeyStoreProvider( 2933): TimaSignature is unavailable
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/ActivityThread( 2933): Added TimaKeyStore provider
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
,D/NearbySettings( 1290): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1013): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,V/NearbySettings( 1290): MountReceiver.mPrefHandler - 7002
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
,E/SQLiteLog( 2886): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/NearbySettings( 1290): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/Intent to TravelDirActivity( 2922): inside TravelBroadcastReceiver
,I/NearbySettings( 1290): MountReceiver.onReceive - Internal Path
D/TP/SmsProvider( 1442): query,matched:26, calling pid = 2282
,D/MediaScanner( 1223): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/SettingsProvider( 1013): name = personal_mode_enabled
,D/TP/SmsProvider( 1442): match 26:Elapsed time : 13.959 ms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,D/DSM     ( 2886): [Lines:107] Normal booted
D/DSM     ( 2886): [Lines:114] Boot completed
,D/BadgeProvider( 2933): onCreate
,D/BadgeProvider( 2933): DatabaseHelper
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2959): MountEmulatedStorage()
,E/Zygote  ( 2959): v2
I/libpersona( 2959): KNOX_SDCARD checking this for 1000
I/libpersona( 2959): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2959 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 1482:com.android.printspooler/u0a136 (adj 15): empty #31
,I/SELinux ( 2959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ResourcesManager( 1442): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
W/ResourcesManager( 1442): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 1442): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1442): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SELinux ( 2959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourcesManager( 1442): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SELinux ( 2959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 27,
,W/libprocessgroup( 1013): failed to open /acct/uid_10107/pid_1520/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2959): TimaSignature is unavailable
,D/ActivityThread( 2959): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10031/pid_2096/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10136/pid_1482/cgroup.procs: No such file or directory
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 41879(2MB) AllocSpace objects, 28(1688KB) LOS objects, 33% free, 25MB/38MB, paused 2.264ms total 228.936ms
,I/SmartcardBootCompleteReceiver( 1290): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1290): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/Mms/SmsReceiver( 2282): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2282): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2282): isDefault true
,E/Zygote  ( 2976): MountEmulatedStorage()
I/libpersona( 2976): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2976): v2
I/libpersona( 2976): KNOX_SDCARD not a persona
I/SELinux ( 2976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2123:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,D/BadgeProvider( 2933): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/TP/MmsProvider( 1442): Query uri=content://mms, match=0, calling pid = 2282
,E/Zygote  ( 2991): MountEmulatedStorage(),
E/Zygote  ( 2991): v2
I/libpersona( 2991): KNOX_SDCARD checking this for 10160
I/libpersona( 2991): KNOX_SDCARD not a persona
I/SELinux ( 2991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
V/MediaScanner( 1223): processDirectory :  /storage/emulated/0
,I/SELinux ( 2991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2991 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/SELinux ( 2991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 2188:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,D/TimaKeyStoreProvider( 2976): TimaSignature is unavailable
,I/SmartcardBootCompleteReceiver( 1290): Broadcast sent with current lockscreen type
,D/ActivityThread( 2976): Added TimaKeyStore provider
,D/SettingsProvider( 1013): name = next_alarm_formatted
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10085
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(75ebcf7
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,D/TimaKeyStoreProvider( 2991): TimaSignature is unavailable
D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ActivityThread( 2991): Added TimaKeyStore provider
,V/MediaScanner( 1223): processDirectory :  /storage/extSdCard
W/MediaScanner( 1223): Error opening directory, reason : Permission denied.
W/MediaScanner( 1223): 7klwibgf7fxlKdCbid7
D/BadgeProvider( 2933): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2933): sendNotify, [notify] : null
D/BadgeProvider( 2933): update, [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1465): reloadBadges entered.
D/BadgeProvider( 2933): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2933): update, [UpdateCount] : 1
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,V/MediaScanner( 1223):  prescan time: 342ms (DB items: 27)
V/MediaScanner( 1223):     scan time: 42ms (Caching mode: true), (makeEntry time: 35ms ~83%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 13ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 397ms
V/MediaScanner( 1223): checked files: 10  directories : 17  (I: 0, U: 0)
,D/Mms/MessagingNotification( 2282): setBadgeCount(), count=0
,D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2643): [DummyFtClient$sendBootCompletedAndFinish](2643) ...
D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
,D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$ResponseWriter](2643) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$connectToSecPhoneService](2643)  
,W/ContextImpl( 2643): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/ActivityManager( 1013): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
W/ResourcesManager( 2991): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 2282): remove alarm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ResourcesManager( 2976): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,I/iu.UploadsManager( 1997): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,D/TP/SmsProvider( 1442): query,matched:0, calling pid = 2282
D/MediaScannerService( 1223): !@done scanning volume external
,D/[SBeam] ( 1290): SBeamEnabler.initPreferenceForSbeam : 0
,D/TP/SmsProvider( 1442): match 0:Elapsed time : 1.571 ms
,D/Mms/MessagingNotification( 2282): updateAllHistoryAsRead()
,I/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$onServiceConnected](2643) connected done
D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$write](2643) Send Response Message to SecPhone
D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$write](2643) Response ��
,D/Mms/MessagingNotification( 2282): [end]    nonBlockingUpdateMessageIndicator() consume time = 754.057656
,D/TP/MmsSmsProvider( 1442): query,matched:200, calling pid = 2282
,W/ActivityThread( 2976): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/SettingSearch/SearchIntentReceiver( 1290): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1290): search setting db init!!
,D/TP/MmsSmsProvider( 1442): match 200:Elapsed time : 15.182 ms
I/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,D/AT_Distributor(  322): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$handleMessage](2643) Send BOOTING COMPLETED done
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/iu.UploadsManager( 1997): End new media; added: 0, uploading: 0, time: 87 ms
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
I/SettingSearch/SearchIntentReceiver( 1290): BOOT_COMPLETED call InitSerachDBThread thread start!
D/TP/SmsProvider( 1442): query,matched:0, calling pid = 2282
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/TP/SmsProvider( 1442): match 0:Elapsed time : 2.150 ms
D/LcdtestApp( 2976): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/LcdtestApp( 2976): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3015): MountEmulatedStorage()
,E/Zygote  ( 3015): v2
I/libpersona( 3015): KNOX_SDCARD checking this for 1000
I/libpersona( 3015): KNOX_SDCARD not a persona
,I/SELinux ( 3015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/art     ( 2896): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 176.123ms
I/ActivityManager( 1013): Killing 1617:com.google.android.partnersetup/u0a15 (adj 15): empty #31
E/SELinux ( 3015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_10050/pid_2123/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10113/pid_2188/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1442): query,matched:51, calling pid = 2282
,D/TP/SmsProvider( 1442): match 51:Elapsed time : 2.923 ms,
D/AT_Distributor(  322): SetAtdStatus(), 1_1_0
D/AT_Distributor(  322): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,E/Zygote  ( 3028): MountEmulatedStorage()
I/libpersona( 3028): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3028): v2
I/libpersona( 3028): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 3028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecureStorage(  408): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,D/TimaKeyStoreProvider( 3015): TimaSignature is unavailable
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3015): Added TimaKeyStore provider
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:UMCContentProvider( 2991): @onCreate
,I/art     (  315): Explicit concurrent mark sweep GC freed 8751(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 33.739ms
,D/TimaKeyStoreProvider( 3028): TimaSignature is unavailable
W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_1617/cgroup.procs: No such file or directory
D/ActivityThread( 3028): Added TimaKeyStore provider
I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 671us total 16.708ms,
,I/SecureStorage( 2799): [INFO]: SPID(0x00000001)Processing data has been completed,
I/SecureStorage( 2799): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 17.275ms
,E/Zygote  ( 3046): MountEmulatedStorage()
,E/Zygote  ( 3046): v2
I/libpersona( 3046): KNOX_SDCARD checking this for 10150
I/libpersona( 3046): KNOX_SDCARD not a persona
,I/SELinux ( 3046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3046 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
I/SELinux ( 3046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3046): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification( 2282): isBlockingModeEnabled() = false, Zen mode = 0
,D/[0]UMC:Core( 2991): onCreate(): 
D/[0]UMC:Core( 2991): @isManagedProfileUser
D/[0]UMC:Core( 2991): userId: 0
,D/[0]UMC:Core( 2991): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2991): userInfo.isManagedProfile() : false
,D/TimaKeyStoreProvider( 3046): TimaSignature is unavailable
,D/ActivityThread( 3046): Added TimaKeyStore provider
,W/ResourcesManager( 3028): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BadgeProvider( 2933): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/[0]UMC:DeviceInfo( 2991): USA==US==
,I/FOTA    ( 3028): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/DIAGMON_AGENT( 3015): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,D/Launcher.Model( 1465): reloadBadges entered.
D/BadgeProvider( 2933): sendNotify entered. [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 2933): sendNotify, [notify] : null
D/BadgeProvider( 2933): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2933): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2933): update, [UpdateCount] : 1,
D/Mms/MessagingNotification( 2282): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2282): remove alarm
,D/Mms/MessagingNotification( 2282): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1442): query,matched:0, calling pid = 2282
,D/TP/SmsProvider( 1442): match 0:Elapsed time : 1.468 ms
,D/Mms/SmsReceiverService( 2282): [end]    handleBootCompleted() consume time = 422.703906
,I/ActivityManager( 1013): Killing 2263:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3066): MountEmulatedStorage()
E/Zygote  ( 3066): v2
I/libpersona( 3066): KNOX_SDCARD checking this for 1000
I/libpersona( 3066): KNOX_SDCARD not a persona,
,I/ActivityManager( 1013): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3066): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/SMD     (  289): DCD OFF
,I/ActivityManager( 1013): Killing 2313:com.sec.android.omc/1000 (adj 15): empty #31
,I/SELinux ( 3066): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3066): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/USER_AGENT( 2991): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/TimaKeyStoreProvider( 3066): TimaSignature is unavailable
,D/ActivityThread( 3066): Added TimaKeyStore provider
,D/[0]UMC:AdminManager( 2991): init - start
,W/ResourcesManager( 3066): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3028): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3028): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1013): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2263/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2313/cgroup.procs: No such file or directory
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/[0]UMC:AdminManager( 2991): loadAdmins
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/OverheatReceiver( 1175): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1175): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1175): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1175): isSafeMode = false
,E/BluetoothHeadset( 2799): BTStateChangeCB is registed
D/[0]UMC:AdminManager( 2991): init - end
,D/GSLBManager( 2991): migrateStoredUrlFromOldPref
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/BootupListener( 1442): intent.getAction() = android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3028): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,D/SettingsProvider( 1013): name = internet_call_settings_visibility
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
,D/SettingsProvider( 1013): selectionArgs: 1001
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
,I/DBG_DM  ( 3028): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,D/SettingsProvider( 1013): ret = -1
D/BluetoothHeadset( 2799): doBind(): CallingUid(myUserHandle) = 0
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
E/USB_UICC(  300): Timeout! No signal received. Retry num = 28
,D/ActivityManager( 1013): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
I/DBG_DM  ( 3028): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,D/PhoneUtilsCommon( 1442): isSupportVoLTE is false.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
E/BluetoothHeadset( 2799): BluetoothHeadset service is binded
,I/DBG_DM  ( 3028): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,D/BluetoothA2dp( 2799): doBind(): CallingUid(myUserHandle) = 0
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,D/ActivityManager( 1013): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,I/DBG_DM  ( 3028): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,I/Telecom ( 1419): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,D/ActivityManager( 1013): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,D/GSLBManager( 2991): migrateStoredUrlFromOldPref : Migration Not Needed
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdminIfNotRequired : -1
,I/DIAGMON_AGENT( 3015): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,D/ActivityManager( 1013): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3028): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,E/[0]UMC:Utils( 2991): Admin not found in package com.samsung.knoxpb.mdm
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/[0]UMC:Utils( 2991): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin : -1
D/BluetoothAdapter( 2799): 651682101: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 651682101: getState() :  mService = null. Returning STATE_OFF
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
D/BluetoothAdapter( 2799): 651682101: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 651682101: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2799): 651682101: getState() :  mService = null. Returning STATE_OFF
I/DBG_DM  ( 3028): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
I/DIAGMON_AGENT( 3015): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/ContextImpl( 3028): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DIAGMON_AGENT( 3015): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/DIAGMON_AGENT( 3015): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,I/DIAGMON_AGENT( 3015): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 3015): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver,
I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,D/EnterpriseDeviceManagerService( 1013): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2991): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
,D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin - UMC App Admin deactivated
E/Zygote  ( 3084): MountEmulatedStorage()
E/Zygote  ( 3084): v2
I/libpersona( 3084): KNOX_SDCARD checking this for 10057
I/libpersona( 3084): KNOX_SDCARD not a persona
I/SELinux ( 3084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3084): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3084 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/ActivityManager( 1013): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1013): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
I/Telecom ( 1419): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2991): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:CoreReceiver( 2991): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2991):  check PreETag 
,E/Zygote  ( 3100): MountEmulatedStorage()
E/Zygote  ( 3100): v2
I/libpersona( 3100): KNOX_SDCARD checking this for 10086
I/libpersona( 3100): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 3084): TimaSignature is unavailable
I/SELinux ( 3100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityThread( 3084): Added TimaKeyStore provider
,I/SELinux ( 3100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3100 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 3100): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2330:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 2345:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/DBG_DM  ( 3028): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/TimaKeyStoreProvider( 3100): TimaSignature is unavailable
,D/ActivityThread( 3100): Added TimaKeyStore provider
,D/[0]UMC:CoreReceiver( 2991): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2991): Enter loadList
,D/[0]UMC:CoreReceiver( 2991): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2991): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2991): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
,D/EnterpriseDeviceManagerService( 1013): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2991): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2991): isContainer : 0
D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,D/[0]UMC:UMCAdmin( 2991): deactivateUMCAdmin - UMC App Admin deactivated
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3028): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,E/Zygote  ( 3120): MountEmulatedStorage()
E/Zygote  ( 3120): v2
I/libpersona( 3120): KNOX_SDCARD checking this for 1000
I/libpersona( 3120): KNOX_SDCARD not a persona
,I/SELinux ( 3120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/Tethering( 1013): No numeric data
,W/libprocessgroup( 1013): failed to open /acct/uid_10131/pid_2345/cgroup.procs: No such file or directory
,I/SELinux ( 3120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/Tethering( 1013): No numeric data
E/SELinux ( 3120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2330/cgroup.procs: No such file or directory
,D/[0]UMC:ByodSetupStarter( 2991): Container ID : 0
,V/[0]UMC:Utils( 2991): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2991): shutdown
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2991): @GuardService - stopService Result = true
I/art     ( 2991): System.exit called, status: 0
I/AndroidRuntime( 2991): VM exiting with result code 0, cleanup skipped.
,V/audio_hw_primary(  281): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  281): audio_extn_get_parameters: returns 
D/TimaKeyStoreProvider( 3120): TimaSignature is unavailable
V/msm8974_platform(  281): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  281): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  281): key: 'call_forwarding' value: ''
V/InCall  ( 1968): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1968): ProximitySensor -  - mFromRcsShare: false
D/ActivityThread( 3120): Added TimaKeyStore provider
I/InCall  ( 1968): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1968): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1968): InCallUtils - isCoverClosed false
,I/Telecom ( 1419): ProximitySensorManager: Proximity wake lock already released
D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1968): InCallUtils - isCoverClosed false
,I/InCall  ( 1968): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1968): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1968): InCallPresenter -  - dismissCoverDialog()...
,D/[SBeam] ( 1290): SBeamEnabler.isSBeamSupported : [-1]
,I/InCall  ( 1968): CallSContextMotion - stopPutDownListening
,D/[SBeam] ( 1290): SBeamEnabler.isSBeamSupported : EXIST
D/InCall  ( 1968): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/PhoneStatusBarView( 1175): setCallBackground:0
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1968): InCallUtils - isCoverClosed false
,I/ActivityManager( 1013): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2991)(adj 0) has died(295,992)
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/Tethering( 1013): No numeric data
,E/Tethering( 1013): No numeric data
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/Tethering( 1013): No numeric data
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1346): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1346): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/SettingsProvider( 1013): name = aw_daemon_service_key_version_check
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10162
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1346): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1346): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457596418851
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457617980000
D/daemonapp( 1346): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,E/Tethering( 1013): No numeric data
,E/UpdateRequestReceiver( 3100): ignoring update request
,D/daemonapp( 1346): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457617980000
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457617980000
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/UpdateRequestReceiver( 3100): ignoring update request
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3146): MountEmulatedStorage()
I/libpersona( 3146): KNOX_SDCARD checking this for 10015
,E/Zygote  ( 3146): v2
I/libpersona( 3146): KNOX_SDCARD not a persona
,I/SELinux ( 3146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3146 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3146): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/LocationManagerService( 1013): getProviders()=[passive]
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/comdaemonstockapp( 1346): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1346): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/Zygote  ( 3165): MountEmulatedStorage()
E/Zygote  ( 3165): v2
I/libpersona( 3165): KNOX_SDCARD checking this for 10009
I/libpersona( 3165): KNOX_SDCARD not a persona
,I/SELinux ( 3165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3165): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3165 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast,
,D/VideoCallManager( 1968): Instantiating VideoCallManager
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3146): TimaSignature is unavailable
,D/ActivityThread( 3146): Added TimaKeyStore provider
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1968): took 2.418750ms for 0*0 texture 0
I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,E/Zygote  ( 3177): MountEmulatedStorage(),
E/Zygote  ( 3177): v2
I/libpersona( 3177): KNOX_SDCARD checking this for 10166
I/libpersona( 3177): KNOX_SDCARD not a persona
,I/SELinux ( 3177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/GFX generate_partition_tables( 1968): took 5.601927ms for 0*0 texture 0
,I/SELinux ( 3177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3177): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GFX raster( 1968): took 12.946198ms for 176*144 texture 0
I/ActivityManager( 1013): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3177 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb8915f30 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb892e140 counterpartCT=4 counterpartW=176 counterparth=144
,E/UpdateRequestReceiver( 3100): ignoring update request
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1968): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1968): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1968): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1968): Local Branch: 
I/Adreno-EGL( 1968): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1968): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1968):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,D/TimaKeyStoreProvider( 3165): TimaSignature is unavailable
,D/ActivityThread( 3165): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/TimaKeyStoreProvider( 3177): TimaSignature is unavailable
,D/ActivityThread( 3177): Added TimaKeyStore provider
,W/NotificationAccessSettings( 1290): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,E/UpdateRequestReceiver( 3100): ignoring update request
,I/GFX GPU raster( 1968): eglCreateImageKHR: EGL_SUCCESS
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,I/glCompressedTexImage2D( 1968): took 0.270053ms for 320*61440 texture 37809
,V/VibratorService( 1013): hasVibrator - useVibetonz: true
,E/UpdateRequestReceiver( 3100): ignoring update request
,I/DBG_POLICYDM( 3120): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3120): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/draw setup( 1968): took 11.984688ms for 320*240 texture 37809
E/UpdateRequestReceiver( 3100): ignoring update request
E/GFX GPU raster( 1968): drawn
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,I/GFX GPU raster ASTC( 1968): took 46.492866ms for 320*240 texture 12
I/GFX raster( 1968): took 46.571564ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb892e140 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8930480 counterpartCT=4 counterpartW=320 counterparth=240
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3028): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/DBG_POLICYDM( 3120): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard,
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
I/GFX GPU raster( 1968): eglCreateImageKHR: EGL_SUCCESS
,I/ActivityManager( 1013): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3207 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 3207): MountEmulatedStorage(),
I/libpersona( 3207): KNOX_SDCARD checking this for 10092
E/Zygote  ( 3207): v2,
I/libpersona( 3207): KNOX_SDCARD not a persona
I/ServiceManager(  329): Waiting for service AtCmdFwd...
I/glCompressedTexImage2D( 1968): took 0.357500ms for 480*122880 texture 37813
I/draw setup( 1968): took 0.702500ms for 480*640 texture 37813
E/GFX GPU raster( 1968): drawn
I/SELinux ( 3207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_POLICYDM( 3120): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/SELinux ( 3207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3207): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/GFX GPU raster ASTC( 1968): took 7.315364ms for 480*640 texture 12
I/GFX raster( 1968): took 7.398853ms for 480*640 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb8930480 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8b5e910 counterpartCT=4 counterpartW=480 counterparth=640
,W/ResourcesManager( 1290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3028): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_POLICYDM( 3120): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/TimaKeyStoreProvider( 3207): TimaSignature is unavailable
,I/DBG_POLICYDM( 3120): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/ActivityThread( 3207): Added TimaKeyStore provider
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/GFX GPU raster( 1968): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1968): took 0.350053ms for 440*116864 texture 37809
I/draw setup( 1968): took 0.727136ms for 440*330 texture 37809
I/DBG_DM  ( 3028): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
E/GFX GPU raster( 1968): drawn
,I/GFX GPU raster ASTC( 1968): took 4.774791ms for 440*330 texture 12
I/GFX raster( 1968): took 4.852552ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb8b5e910 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8b72d00 counterpartCT=4 counterpartW=440 counterparth=330
,I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1968): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1968): took 0.470990ms for 480*163840 texture 37811
I/draw setup( 1968): took 0.968386ms for 480*640 texture 37811
E/GFX GPU raster( 1968): drawn
,I/GFX GPU raster ASTC( 1968): took 6.294167ms for 480*640 texture 12
I/GFX raster( 1968): took 6.416042ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb8b62b10 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8b72838 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_POLICYDM( 3120): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/ScoverManager( 1290): serviceVersion : 16908288
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/ActivityManager( 1013): Killing 2252:com.sec.android.app.mt/1000 (adj 15): empty #31
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1968): took 2.083177ms for 0*0 texture 0
,I/ActivityManager( 1013): Killing 2417:com.wsomacp/u0a25 (adj 15): empty #31
,I/GFX generate_partition_tables( 1968): took 7.474062ms for 0*0 texture 0
,I/GFX raster( 1968): took 11.622396ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb8b5c1d0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8b5c2f0 counterpartCT=4 counterpartW=176 counterparth=144
,W/TRThreadPoolExecutor( 3084): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/SearchServiceFactory( 3084): refreshing search history.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/        ( 1968): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1968): took 2.222030ms for 0*0 texture 0
,E/Zygote  ( 3239): MountEmulatedStorage()
E/Zygote  ( 3239): v2
I/libpersona( 3239): KNOX_SDCARD checking this for 10003
I/libpersona( 3239): KNOX_SDCARD not a persona
I/SELinux ( 3239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/GFX generate_partition_tables( 1968): took 6.258698ms for 0*0 texture 0
I/SELinux ( 3239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX raster( 1968): took 10.809479ms for 176*144 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1968): Bitmap=0xb8b5c510 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8b5c4b0 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1968): registerListener,
I/ActivityManager( 1013): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3239 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2252/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10025/pid_2417/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3239): TimaSignature is unavailable
,D/ActivityThread( 3239): Added TimaKeyStore provider
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,I/DBG_POLICYDM( 3120): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/PowerUI ( 1175): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1175): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3120): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3120): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 13663(740KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 25MB/38MB, paused 2.512ms total 192.495ms
,D/CoverManagerWhiteLists( 1013): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1013): registerListenerCallback : binder = android.os.BinderProxy@3190384a, pid : 1968, uid : 1001, type : 1
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/InCall  ( 1968): InCallPresenter -  - Finished InCallPresenter.setUp
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 29
,W/ResourcesManager( 3177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 3177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 3256): MountEmulatedStorage()
E/Zygote  ( 3256): v2
I/libpersona( 3256): KNOX_SDCARD checking this for 1000
I/libpersona( 3256): KNOX_SDCARD not a persona
,I/SELinux ( 3256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2485:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
I/ActivityManager( 1013): Killing 2471:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #32
I/ActivityManager( 1013): Killing 2454:com.sec.android.gallery3d/u0a44 (adj 15): empty #33
,I/art     (  315): Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 19.715ms
,I/ActivityManager( 1013): Killing 2519:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 20.578ms
,D/TimaKeyStoreProvider( 3256): TimaSignature is unavailable
,D/ActivityThread( 3256): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 22.674ms
,I/LockPatternUtils( 1290): isSmartCardAuthenticationAvailable: false
,D/UserAnalysis.PlaceProvider( 3239): PlaceProvider onCreate()
,D/Settings_Utils( 1290): isSupportVNFestival SM-A500FU XEO
,V/JNIHelp ( 3177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup( 1013): failed to open /acct/uid_10142/pid_2485/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10044/pid_2454/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10088/pid_2471/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10139/pid_2519/cgroup.procs: No such file or directory
,I/WebViewFactory( 3084): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 3084): Time to load native libraries: 2 ms (timestamps 5911-5913)
I/LibraryLoader( 3084): Expected native library version number "",actual native library version number ""
,W/art     ( 3084): Attempt to remove local handle scope entry from IRT, ignoring
,W/TRThreadPoolExecutor( 3084): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/DBG_FMMDM( 3256): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/UserAnalysis.SecureDbManager( 3239): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3239): SecurePlaceDbHelper() 
D/UserAnalysis( 3239): Create SecureDbHelper
,W/ActivityThread( 3177): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@194481a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3177): Installed default security provider GmsCore_OpenSSL
,I/DBG_FMMDM( 3256): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3256): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3256): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3276): MountEmulatedStorage(),
E/Zygote  ( 3276): v2
I/libpersona( 3276): KNOX_SDCARD checking this for 1000
I/libpersona( 3276): KNOX_SDCARD not a persona
,I/SELinux ( 3276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3276 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3276): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 3239): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3239): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,D/TimaKeyStoreProvider( 3276): TimaSignature is unavailable
,I/ActivityManager( 1013): Killing 2608:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/ActivityThread( 3276): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3292): MountEmulatedStorage(),
E/Zygote  ( 3292): v2
I/libpersona( 3292): KNOX_SDCARD checking this for 10060
,I/libpersona( 3292): KNOX_SDCARD not a persona
,I/SELinux ( 3292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3292 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/IntelligenceServiceApplication( 3239): no applications having user consent for prediction
,I/ActivityManager( 1013): Killing 2593:com.android.calendar/u0a135 (adj 15): empty #31
,V/AlarmManager( 1013): waitForAlarm result :8
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3292): TimaSignature is unavailable
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
D/ActivityThread( 3292): Added TimaKeyStore provider
,V/PlaceDetection v1.0.19 ( 3239): [PlaceDetection::stopService] Service stopped.
,D/ActivityManager( 1013): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3308): MountEmulatedStorage()
I/libpersona( 3308): KNOX_SDCARD checking this for 10092
E/Zygote  ( 3308): v2
I/libpersona( 3308): KNOX_SDCARD not a persona
,I/SELinux ( 3308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3308 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3308): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 3239): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3239): Constructor Preference
I/PCWCLIENTTRACE_LOG( 3276): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3276): DEFAULT_LOGLEVEL : 3
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2608/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10135/pid_2593/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3308): TimaSignature is unavailable
,D/ActivityThread( 3308): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3276): new DMDBOpenHelper instance
,D/PCWCLIENTTRACE_DMContentProvider( 3276): [URIMatcher] - result : 2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/DBG_FMMDM( 3256): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3256): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3256): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3328): MountEmulatedStorage(),
I/libpersona( 3328): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3328): v2
,I/libpersona( 3328): KNOX_SDCARD not a persona
I/SELinux ( 3328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2712:com.samsung.android.sm/1000 (adj 15): empty #31
I/ActivityManager( 1013): Killing 2672:com.android.keychain/1000 (adj 15): empty #32
,I/SELinux ( 3328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3328): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3328): TimaSignature is unavailable
,D/ActivityThread( 3328): Added TimaKeyStore provider
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/DBG_FMMDS( 3328): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/sCloudBackupApp( 3292): sCloudBackupApp Version Info : 4.04.8.KK_APP
,I/DBG_FMMDS( 3328): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2672/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2712/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3349): MountEmulatedStorage()
,I/libpersona( 3349): KNOX_SDCARD checking this for 10062
E/Zygote  ( 3349): v2
I/libpersona( 3349): KNOX_SDCARD not a persona
I/SELinux ( 3349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3349 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 1772:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/PCWCLIENTTRACE_DMContentProvider( 3276): [URIMatcher] - result : 2
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3207): Setting receiver enabled: false
,E/DBG_FMMDS( 3328): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,D/TimaKeyStoreProvider( 3349): TimaSignature is unavailable
,D/ActivityThread( 3349): Added TimaKeyStore provider
,I/DBG_FMMDS( 3328): [50.18.150420][Line:43][xdbDBInit] 
,W/libprocessgroup( 1013): failed to open /acct/uid_10004/pid_1772/cgroup.procs: No such file or directory
,E/ActivityThread( 3207): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/dbxyzptlk.db240408.D.h( 3207): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/dbxyzptlk.db240408.D.h( 3207): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3207): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,W/ResourcesManager( 3177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/LockPatternUtils( 1290): isSmartCardAuthenticationAvailable: false
,I/dbxyzptlk.db240408.D.h( 3207): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/DBG_FMMDS( 3328): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/ExternalOEMControlProvider( 3349): onCreate
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3373): MountEmulatedStorage(),
I/libpersona( 3373): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3373): v2
I/libpersona( 3373): KNOX_SDCARD not a persona
I/SELinux ( 3373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/breakpad( 3207): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,D/SettingsProvider( 1013): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10062
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
I/DBG_FMMDS( 3328): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1013): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10062
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/DBG_FMMDS( 3328): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/TimaKeyStoreProvider( 3373): TimaSignature is unavailable
D/ActivityThread( 3373): Added TimaKeyStore provider
,I/DBG_FMMDS( 3328): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3328): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3328): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3328): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,W/ResourcesManager( 3373): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 30
,I/ActivityManager( 1013): Killing 2747:flipboard.boxer.app/u0a99 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/FOTA_Client( 3165): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3165): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/ServiceMode( 3373): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3373): setReferenceIsDumpState : 0
,I/com.dropbox.sync.android.a( 3207): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3397): MountEmulatedStorage()
,E/Zygote  ( 3397): v2,
,I/libpersona( 3397): KNOX_SDCARD checking this for 1000,
I/FOTA_Client( 3165): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
I/libpersona( 3397): KNOX_SDCARD not a persona
I/SELinux ( 3397): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/USB_UICC(  300): Timeout! No signal received. Reach maximum retries!
,E/USB_UICC(  300): usb_uicc_init_qmi failed ! 
I/USB_UICC(  300): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  300): usb_uicc_cleanup, Issuing QMI deinit ... 
,I/SELinux ( 3397): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3397): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3397 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/dex2oat ( 3380): ----------------------------------------------------
I/dex2oat ( 3380): <SS>: S T A R T I N G . . .
I/dex2oat ( 3380): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3380): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1888120027.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1888120027.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/FOTA_Client( 3165): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
D/TimaKeyStoreProvider( 3397): TimaSignature is unavailable
D/ActivityThread( 3397): Added TimaKeyStore provider
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3422): MountEmulatedStorage()
E/Zygote  ( 3422): v2
I/libpersona( 3422): KNOX_SDCARD checking this for 10014
I/libpersona( 3422): KNOX_SDCARD not a persona
,I/SELinux ( 3422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/libprocessgroup( 1013): failed to open /acct/uid_10099/pid_2747/cgroup.procs: No such file or directory
,I/SELinux ( 3422): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3422 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,E/SELinux ( 3422): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 2140:flipboard.app/u0a98 (adj 15): empty #31
,I/com.dropbox.sync.android.ad( 3207): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,D/TimaKeyStoreProvider( 3422): TimaSignature is unavailable
D/ActivityThread( 3422): Added TimaKeyStore provider
,W/System.err( 3177): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,V/OneTimeInitializerReceiver( 3422): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,I/dex2oat ( 3380): dex2oat took 134.618ms (threads: 4)
,V/OneTimeService( 3422): OneTimeService.onHandleIntent
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
I/System.out( 3177): YouTube MDX: MDX video stage moved to NEW
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/System.out( 3177): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 3177): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/NPS_WSSNPS( 3397): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,I/SettingSearch/SearchIntentReceiver( 1290): InitSerachDBThread thread end!
,D/ActivityManager( 1013): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,I/ActivityManager( 1013): Killing 2764:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
D/NPS_WSSNPS( 3397): [] Service onCreate!!
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3451): MountEmulatedStorage()
E/Zygote  ( 3451): v2
I/libpersona( 3451): KNOX_SDCARD checking this for 1000
I/libpersona( 3451): KNOX_SDCARD not a persona
,I/SELinux ( 3451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1013): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3451 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
I/SELinux ( 3451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
,E/SELinux ( 3451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3451): TimaSignature is unavailable
,W/libprocessgroup( 1013): failed to open /acct/uid_10098/pid_2140/cgroup.procs: No such file or directory,
D/ActivityThread( 3451): Added TimaKeyStore provider
,E/Zygote  ( 3475): MountEmulatedStorage(),
E/Zygote  ( 3475): v2
I/libpersona( 3475): KNOX_SDCARD checking this for 10094
I/libpersona( 3475): KNOX_SDCARD not a persona
,I/SELinux ( 3475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3475 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2782:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/SELinux ( 3475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3012)  
,I/System.out( 3207): Thread-445(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3207): Thread-445(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3207): Thread-445(ApacheHTTPLog):isShipBuild true
I/System.out( 3207): Thread-445(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3207): Thread-445(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/NPS_WSSNPS( 3397): [] NpsServiceTask Start
,D/EnterpriseController(  276): uids 10092
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10092
,I/System.out( 3207): pool-10-thread-1 calls detatch()
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ActivityManager( 1013): Killing 2300:com.sec.modem.settings/1000 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,D/TimaKeyStoreProvider( 3475): TimaSignature is unavailable
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 3475): Added TimaKeyStore provider
,W/ResourcesManager( 3451): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/NPS_WSSNPS( 3397): [50.150621] smlDBHelper
,E/Zygote  ( 3497): MountEmulatedStorage(),
E/Zygote  ( 3497): v2
,I/libpersona( 3497): KNOX_SDCARD checking this for 1000
I/libpersona( 3497): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3497 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 795us total 27.623ms,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2764/cgroup.procs: No such file or directory
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/art     ( 1628): Explicit concurrent mark sweep GC freed 7273(358KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 780us total 34.598ms,
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 27.483ms,
,D/TimaKeyStoreProvider( 3497): TimaSignature is unavailable
,D/ActivityThread( 3497): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 18.812ms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/NPS_WSSNPS( 3397): [50.150621] AsyncBulkFlagCheck
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/RlzPingService( 3146): Setting next ping for 1458201221061
,I/NPS_WSSNPS( 3397): [50.150621] IsRemain_AsyncBulkCheck
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/NPS_WSSNPS( 3397): [50.150621] IsRemain_Asyncing nothing
W/ContextImpl( 3397): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/libprocessgroup( 1013): failed to open /acct/uid_10152/pid_2782/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2300/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,I/Hs20UtilService( 3497): onCreate
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/Hs20UtilService( 3497): Starting #1
I/Hs20UtilService( 3497): Message received 5003
,E/Zygote  ( 3523): MountEmulatedStorage()
E/Zygote  ( 3523): v2
I/libpersona( 3523): KNOX_SDCARD checking this for 10019
I/libpersona( 3523): KNOX_SDCARD not a persona
,I/SELinux ( 3523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3523 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/elm:15183( 3475): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3397): [50.150621] Service onDestroy
,D/elm:15183( 3475): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3475): MDMBridge.setEnterpriseBridge()
,I/NPS_WSSNPS( 3397): [50.150621] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3397): [50.150621] smlBRMessageDelete
,I/NPS_WSSNPS( 3397): [50.150621] smlBREmailDelete
D/ActivityManager( 1013): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
I/NPS_WSSNPS( 3397): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3397): [50.150621] smlBRCallLogDelete
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/NPS_WSSNPS( 3397): [50.150621] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3397): [50.150621] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3397): [50.150621] smlBRSMemoDelete
I/NPS_WSSNPS( 3397): [50.150621] verifier installed? false
I/NPS_WSSNPS( 3397): [50.150621] cpuBooster release : false
,D/elm:15183( 3475): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/TimaKeyStoreProvider( 3523): TimaSignature is unavailable
,D/ActivityThread( 3523): Added TimaKeyStore provider
,D/elm:15183( 3475): ElmAgentService : onCreate()
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/elm:15183( 3475): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3475): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3475): BootCompletedState : startBootCompleted() call
,V/EmergencyMode( 1402): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/NPS_WSSNPS( 3397): [50.150621] dsServerSocket close
,D/elm:15183( 3475): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3475): Get License : 0
D/elm:15183( 3475): ElmAgentService : onDestroy().
,I/ActivityManager( 1013): Killing 2835:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 2282:com.android.mms/u0a46 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3523): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 10 08:53:41 GMT+01:00 2016
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,V/EmergencyMode( 1402): [EmergencyBase] setBootTime
V/EmergencyMode( 1402): [EmergencyFactory] No Recovery State, kill my self.
,I/KLMS-2.5.183: ( 3523): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,I/KLMS-2.5.183: ( 3523): KLMSIntentService(): onCreate()
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3523): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3523): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3523): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,E/Zygote  ( 3545): MountEmulatedStorage()
E/Zygote  ( 3545): v2
I/libpersona( 3545): KNOX_SDCARD checking this for 10022
I/libpersona( 3545): KNOX_SDCARD not a persona
,I/SELinux ( 3545): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3545 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3545): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3545): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CountryDetector( 1013): No listener is left
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,I/KLMS-2.5.183: ( 3523): KLMSIntentService(): BOOT_COMPLETED
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3557): MountEmulatedStorage()
E/Zygote  ( 3557): v2
I/libpersona( 3557): KNOX_SDCARD checking this for 1000
I/libpersona( 3557): KNOX_SDCARD not a persona
,I/SELinux ( 3557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3557 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3545): TimaSignature is unavailable
D/ActivityThread( 3545): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_1101/pid_2835/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10046/pid_2282/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3557): TimaSignature is unavailable
,D/ActivityThread( 3557): Added TimaKeyStore provider
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3580 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,E/Zygote  ( 3580): MountEmulatedStorage(),
I/ActivityManager( 1013): Killing 2812:com.sec.knox.bridge/1000 (adj 15): empty #31
E/Zygote  ( 3580): v2
I/libpersona( 3580): KNOX_SDCARD checking this for 1000
I/libpersona( 3580): KNOX_SDCARD not a persona
,I/SELinux ( 3580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,I/KLMS-2.5.183: ( 3523): KLMSIntentService(): onDestroy()
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CameraApp( 3557): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3557): Feature.Feature(context)
,E/Zygote  ( 3590): MountEmulatedStorage(),
E/Zygote  ( 3590): v2
I/libpersona( 3590): KNOX_SDCARD checking this for 1000
,I/testFeature( 3557): Feature.readInternalDefaultXml()
I/libpersona( 3590): KNOX_SDCARD not a persona
I/testFeature( 3557): ResetFeatureValue
,I/SELinux ( 3590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2854:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
I/SELinux ( 3590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SMD     (  289): DCD OFF
E/SELinux ( 3590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/CameraFirmware_broadcast( 3557): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3557): CameraApp.getAppFeature()...
W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 3580): TimaSignature is unavailable
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
D/ActivityThread( 3580): Added TimaKeyStore provider
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3590): TimaSignature is unavailable,
,D/ActivityThread( 3590): Added TimaKeyStore provider
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3177): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Zygote  ( 3610): MountEmulatedStorage()
E/Zygote  ( 3610): v2
I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3610 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/libpersona( 3610): KNOX_SDCARD checking this for 10100
I/libpersona( 3610): KNOX_SDCARD not a persona
I/SELinux ( 3610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Killing 2874:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,I/SELinux ( 3610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3610): TimaSignature is unavailable
D/ActivityThread( 3610): Added TimaKeyStore provider
,E/MTPRx   ( 3590): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedState
D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1013): mCursor = null
,V/MTPRx   ( 3590): sealedState: false
V/MTPRx   ( 3590): sealedUsbMassStorageState: false
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2812/cgroup.procs: No such file or directory
,D/SettingsProvider( 1013): name = mtp_usb_connection_status
W/libprocessgroup( 1013): failed to open /acct/uid_10048/pid_2854/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10157/pid_2874/cgroup.procs: No such file or directory
,D/SettingsProvider( 1013): name = media_player_mode
,D/PackageIntentReceiver( 3610): ACTION_BOOT_COMPLETED
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,D/PackageIntentReceiver( 3610): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1013): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = media_mount_count
,D/SettingsProvider( 1013): name = mtp_sync_alive
D/SettingsProvider( 1013): name = sdcard_launch
,E/Zygote  ( 3630): MountEmulatedStorage(),
E/Zygote  ( 3630): v2
I/libpersona( 3630): KNOX_SDCARD checking this for 10101
D/SettingsProvider( 1013): name = boot_time_connected
I/libpersona( 3630): KNOX_SDCARD not a persona
I/SELinux ( 3630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3630 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3630): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 2922:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3630): TimaSignature is unavailable
,D/ActivityThread( 3630): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/SettingsProvider( 1013): name = access_control_enabled
,I/PCWCLIENTTRACE_PushUtil( 3276): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3276): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3276): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3276): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3276): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3276): ACTION_BOOTUP - Push type: [SPP, GCM]
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3648): MountEmulatedStorage()
E/Zygote  ( 3648): v2
I/libpersona( 3648): KNOX_SDCARD checking this for 10069
I/libpersona( 3648): KNOX_SDCARD not a persona
,I/SELinux ( 3648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/PCWCLIENTTRACE_PCWHandler( 3276): [ensureRegistration] - netwrok is not available. action ignored
,I/ActivityManager( 1013): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3648 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1013): Killing 2933:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/SELinux ( 3648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
E/SELinux ( 3648): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3648): TimaSignature is unavailable
,D/ActivityThread( 3648): Added TimaKeyStore provider
,E/Zygote  ( 3659): MountEmulatedStorage()
E/Zygote  ( 3659): v2
I/libpersona( 3659): KNOX_SDCARD checking this for 10031
,I/libpersona( 3659): KNOX_SDCARD not a persona
I/SELinux ( 3659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3659): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3659 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 2886:com.sec.dsm.system/1000 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 3659): TimaSignature is unavailable
D/ActivityThread( 3659): Added TimaKeyStore provider
,W/ResourcesManager( 3659): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/FileShare-Server( 3648): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/libprocessgroup( 1013): failed to open /acct/uid_10159/pid_2922/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10072/pid_2933/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2886/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1013): getStreamVolume 3 index 0
,I/VlingoApplication( 3659): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,D/BluetoothAdapter( 3659): 724293430: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3659): 724293430: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3659): 724293430: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3659): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3177): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
,W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3177): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3177): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files,
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1013): Killing 2959:com.sec.usbsettings/1000 (adj 15): empty #31
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1013): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3714): MountEmulatedStorage(),
,E/Zygote  ( 3714): v2
,I/libpersona( 3714): KNOX_SDCARD checking this for 1000
I/libpersona( 3714): KNOX_SDCARD not a persona
,I/SELinux ( 3714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
I/SELinux ( 3714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3714): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3714): TimaSignature is unavailable
,D/ActivityThread( 3714): Added TimaKeyStore provider
,D/VlingoApplication( 3659): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3659): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/DialogFlow( 3659): initQueue()
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 26894(1473KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 26MB/39MB, paused 3.379ms total 161.703ms
,I/Gmail   ( 3630): getAccountsCursor
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3737): MountEmulatedStorage()
,E/Zygote  ( 3737): v2
I/libpersona( 3737): KNOX_SDCARD checking this for 10032
I/libpersona( 3737): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3737 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 2976:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31,
I/SELinux ( 3737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/TimaKeyStoreProvider( 3737): TimaSignature is unavailable
I/art     (  315): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 716us total 24.803ms
,D/ActivityThread( 3737): Added TimaKeyStore provider
,W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2959/cgroup.procs: No such file or directory
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 948us total 19.328ms
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_2976/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
W/GAV2    ( 3630): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 21.013ms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3758): MountEmulatedStorage(),
E/Zygote  ( 3758): v2
I/libpersona( 3758): KNOX_SDCARD checking this for 1000
I/libpersona( 3758): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3758 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1950): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1950): Service started flags 0 startId 1
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,D/SecUISvc( 1950): Thread created.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3758): TimaSignature is unavailable
,D/ActivityThread( 3758): Added TimaKeyStore provider,
,E/Zygote  ( 3777): MountEmulatedStorage()
,E/Zygote  ( 3777): v2
I/libpersona( 3777): KNOX_SDCARD checking this for 10028
I/libpersona( 3777): KNOX_SDCARD not a persona
,I/SELinux ( 3777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3777 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
D/ActivityManager( 1013): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/SELinux ( 3777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3777): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3777): TimaSignature is unavailable
D/ActivityThread( 3777): Added TimaKeyStore provider
,W/ResourcesManager( 3758): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Killing 2896:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
I/ActivityManager( 1013): Killing 3015:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1013): Killing 3046:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3630): getAccountsCursor
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Gmail   ( 3630): Error finding the version of the Email provider.....
E/Gmail   ( 3630): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3630): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3630): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3630): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3630): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3630): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3630): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3630): We do not support migrating this version of the Email provider.
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3015/cgroup.procs: No such file or directory
,E/Zygote  ( 3801): MountEmulatedStorage(),
E/Zygote  ( 3801): v2
I/libpersona( 3801): KNOX_SDCARD checking this for 10033
I/libpersona( 3801): KNOX_SDCARD not a persona
,I/SELinux ( 3801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3801 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 3801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,E/SELinux ( 3801): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1013): failed to open /acct/uid_10085/pid_2896/cgroup.procs: No such file or directory
,E/Zygote  ( 3817): MountEmulatedStorage()
E/Zygote  ( 3817): v2
I/libpersona( 3817): KNOX_SDCARD checking this for 10104
I/libpersona( 3817): KNOX_SDCARD not a persona
,I/SELinux ( 3817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3817 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 3817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3817): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_10150/pid_3046/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3801): TimaSignature is unavailable
,D/ActivityThread( 3801): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3817): TimaSignature is unavailable
,I/GoogleHttpClient( 1628): GMS http client unavailable, use old client
D/ActivityThread( 3817): Added TimaKeyStore provider
,W/ResourcesManager( 3817): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Killing 3066:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3066/cgroup.procs: No such file or directory
,I/Gmail   ( 3630): Observing account changes for notifications
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3630): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@14f0d740 that was originally bound here
E/ActivityThread( 3630): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@14f0d740 that was originally bound here
E/ActivityThread( 3630): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3630): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3630): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3630): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3630): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3630): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3630): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3630): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3630): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3630): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3630): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3630): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3630): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3630): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3630): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1013): Unbind failed: could not find connection for android.os.BinderProxy@37eabc70
,D/FactoryTestApp( 2643): [DummyFtClient$onDestroy](2643) Destroy DummyFtClient service
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
I/FactoryTestApp( 2643): [ModuleCommon$isRunningFtClient](2643) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2643): [DummyFtClient$onDestroy](2643) kill process
I/Process ( 2643): Sending signal. PID: 2643 SIG: 9
,W/art     ( 3630): No such thread id for suspend: 21
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1013): Process com.sec.factory (pid 2643)(adj 0) has died(176,1070)
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 3714): Resource data:2131165186
,W/ResourcesManager( 3714): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3714): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3714): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,I/AMMetaDataParserService( 3714): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,D/Finsky  ( 3777): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{3564ab86 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 3714): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,E/SQLiteLog( 3630): (283) recovered 146 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/AMMetaDataParserService( 3714): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,D/TimaService( 1013): TIMA: in getTimaVersion
,D/TimaService( 1013): TIMA3: KeyStore3_init
,D/TimaService( 1013): TIMA: in getTimaVersion
E/TLC_TZ_KEYSTORE: ( 1013): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 1013): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1013): initializing ccm context...
,I/TLC_TZ_KEYSTORE: ( 1013): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1013): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1013): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1013): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1013): aligned max_sendmsg_size = 1088 = 0x440
,I/TZ: qc_tlc_communication( 1013): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1013): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1013): QSEECom_get_handle sb_length = 0x880
,D/QSEECOMAPI: ( 1013): App is not loaded in QSEE
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,D/QSEECOMAPI: ( 1013): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1013): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1013): ctx = 0xb8bdde18, comm = 0xb8b9b9f0, sendmsg = 0xa08a1000, recvmsg = 0xa08a1440
I/TZ_init: ( 1013): TZ_init: sending initialization request...
,I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3714): Resource data:2131034113
E/TZ_init: ( 1013): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1013): trustlet initialization failed
I/TZ_init: ( 1013): TZ_init_START...
,W/ResourcesManager( 3801): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3801): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3801): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/TZ_init: ( 1013): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1013): TZ_init: successful initialization
W/ResourcesManager( 3714): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
D/QSEECOMAPI: ( 1013): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1013): QSEECom_shutdown_app, app_id = 8
E/TLC_TZ_KEYSTORE: ( 1013): Count : 1, Ret : 0
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourcesManager( 3801): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3801): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3801): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/GFX construct_block_size_descriptor_2d second part( 3714): took 2.664895ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3714): took 6.311823ms for 0*0 texture 0
,I/GFX raster( 3714): took 10.397551ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89224b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8922480 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3801): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3801): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3801): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 1.169896ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89224b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8922480 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ContextImpl( 3758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/Finsky  ( 3777): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/File    ( 3630): fail readDirectory() errno=2
,E/Zygote  ( 3865): MountEmulatedStorage(),
E/Zygote  ( 3865): v2
,I/libpersona( 3865): KNOX_SDCARD checking this for 1000
,I/libpersona( 3865): KNOX_SDCARD not a persona
,I/SELinux ( 3865): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1013): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3865): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3865): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/Settings( 3777): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3777): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/GFX construct_block_size_descriptor_2d second part( 3714): took 2.413698ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 3865): TimaSignature is unavailable
,D/ActivityThread( 3865): Added TimaKeyStore provider,
,I/Gmail   ( 3630): notifyAccountChanged
,W/art     ( 3659): Suspending all threads took: 6.952ms
,I/GFX generate_partition_tables( 3714): took 7.461719ms for 0*0 texture 0
,I/GFX raster( 3714): took 10.921875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8922480 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8926f70 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3865): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,I/Babel   ( 3817): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3817): MmsConfig.loadMmsSettings
I/Babel   ( 3817): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3817): MmsConfig.loadFromDatabase
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/SEAMService( 1013):  hashset_to_int_array returning null
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/Volley  ( 3777): [571] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3777): [578] DiskBasedCache.clear: Cache cleared.
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Ads     ( 3777): Skipping gmscore version check
,I/Gmail   ( 3630): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ContextImpl( 3865): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1013): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
W/SEAMService( 1013):  hashset_to_int_array returning null
,E/SQLiteLog( 3758): (284) automatic index on seams_container_info(seams_container_id),
,E/SQLiteLog( 3758): (284) automatic index on seams_container_info(sp_id),
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,W/SEAMService( 1013):  hashset_to_int_array returning null
,I/System.out( 3659): INFO:Resource not found:/Common.properties Using default values
,E/Babel   ( 3817): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3817): MmsConfig.loadFromResources
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.600833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb892bb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb892bc70 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Babel   ( 3817): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3817): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/AMMetaDataParserService( 3714): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/Gmail   ( 3630): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager( 1013): Killing 3120:com.policydm/1000 (adj 15): empty #31
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/F_PHONE ( 3865): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3865): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.850104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8928520 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8928678 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/AMMetaDataParserService( 3714): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/Gmail   ( 3630): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3630): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 1.291563ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8922908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8927000 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/F_PHONE ( 3865): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3865): default registerAction()
I/F_PHONE ( 3865): [[com.sec.bcservice]] sendPendingMessage()
,W/Settings( 3817): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3120/cgroup.procs: No such file or directory
D/Finsky  ( 3777): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3777): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 3817): Suspending all threads took: 21.986ms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.692343ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8927000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89278a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 3777): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.522448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88d0548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88dc3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131034113
,I/AMMetaDataParserService( 3714): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.808229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,I/Process ( 3801): Sending signal. PID: 3801 SIG: 9
,W/art     ( 3817): Suspending all threads took: 12.144ms
,I/AMMetaDataParserService( 3714): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3777): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 3737): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1013): Process com.sec.android.app.sns3 (pid 3801)(adj 0) has died(144,1088)
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 1997): Spent 76ms computing apk sha1.
D/FileApkUtils( 1997): Module already staged or being staged:chimera-modules/MapsModule.apk
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/art     ( 1997): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/Babel_StickerModule( 3817): App launched.,
W/ResourcesManager( 3737): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3737): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/System.out( 3777): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager,
W/ResourcesManager( 3737): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/System.out( 3777): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3777): (HTTPLog)-Static: isShipBuild true,
I/libpersona( 3908): KNOX_SDCARD checking this for 10034
I/System.out( 3777): (HTTPLog)-Thread-583-319456587: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/libpersona( 3908): KNOX_SDCARD not a persona
I/System.out( 3777): (HTTPLog)-Static: isSBSettingEnabled false
,E/Zygote  ( 3908): MountEmulatedStorage()
E/Zygote  ( 3908): v2
I/SELinux ( 3908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,I/SELinux ( 3908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3908): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3908 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/Babel_StickerModule( 3817): Sticker update initiated. last:1456825783062 empty:false
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.883125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8708448 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/DexOptUtils( 1997): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1997): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 1997): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1997): Primary ABI of odexing process is armeabi-v7a
,I/AMMetaDataParserService( 3714): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3908): TimaSignature is unavailable
,D/ActivityThread( 3908): Added TimaKeyStore provider
,W/InstanceID/Rpc( 1997): Found 10012
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.617604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88dc3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/dex2oat ( 3926): ----------------------------------------------------
I/dex2oat ( 3926): <SS>: S T A R T I N G . . .
I/dex2oat ( 3926): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3926): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/Babel   ( 3817): babel boot account: SMS
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Babel   ( 3817): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3817): java.lang.Exception
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3817): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3817): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3817): 	at ckh.a(SourceFile:67)
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3817): 	at bhn.a(SourceFile:301)
W/Babel   ( 3817): 	at bhn.a(SourceFile:137)
W/Babel   ( 3817): 	at bhn.a(SourceFile:126)
W/Babel   ( 3817): 	at bhn.a(SourceFile:159)
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3817): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3817): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3817): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3817): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3817): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3817): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3817): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3817): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3817): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3817): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3817): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3817): java.lang.Exception
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3817): 	at aes.a(SourceFile:145)
W/Babel   ( 3817): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3817): 	at ckh.a(SourceFile:67)
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3817): 	at bhn.a(SourceFile:301)
W/Babel   ( 3817): 	at bhn.a(SourceFile:137)
W/Babel   ( 3817): 	at bhn.a(SourceFile:126)
W/Babel   ( 3817): 	at bhn.a(SourceFile:159)
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3817): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3817): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3817): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3817): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3817): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3817): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3817): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3817): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3817): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3817): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3714): took 0.596094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89236f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.827656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,I/Gmail   ( 3630): getAccountsCursor
,I/AMMetaDataParserService( 3714): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.635312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8922908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.718021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8927000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,V/Babel   ( 3817): babel boot account: thalitester@gmail.com
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Babel   ( 3817): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3817): java.lang.Exception
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3817): 	at aes.a(SourceFile:145)
W/Babel   ( 3817): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3817): 	at ckh.a(SourceFile:67)
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3817): 	at bhn.a(SourceFile:301)
W/Babel   ( 3817): 	at bhn.a(SourceFile:137)
W/Babel   ( 3817): 	at bhn.a(SourceFile:126)
W/Babel   ( 3817): 	at bhn.a(SourceFile:159)
W/Babel   ( 3817): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3817): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3817): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3817): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3817): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3817): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3817): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3817): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3817): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3817): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3817): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.524427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88d0548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3714): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3714): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3714): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131034112
,I/AMMetaDataParserService( 3714): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.608021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89236f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88edb48 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/GCM     ( 1997): COMPAT: Multi user not supported
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1757): COMPAT: Multi user not supported
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3942): MountEmulatedStorage()
E/Zygote  ( 3942): v2
I/libpersona( 3942): KNOX_SDCARD checking this for 1000
I/libpersona( 3942): KNOX_SDCARD not a persona
,I/SELinux ( 3942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SMD     (  289): DCD OFF
,E/SELinux ( 3942): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3942 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3942): TimaSignature is unavailable
D/ActivityThread( 3942): Added TimaKeyStore provider
,I/GCoreUlr( 1997): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/art     ( 1013): Explicit concurrent mark sweep GC freed 26923(1755KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.618ms total 172.484ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3630): getAccountsCursor
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.612864ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89236f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89280a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/CheckinService( 1997): Checkin interval check for package: unspecified last checkin: 1456600236354 min interval config: 0 actual interval: 996188076
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  281): getCameraInfo: X
,D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService( 1013): Got CLOSE_WRITE Event sk.log
,I/AMMetaDataParserService( 3714): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,E/Zygote  ( 3958): MountEmulatedStorage(),
E/Zygote  ( 3958): v2,
W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
I/ActivityManager( 1013): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
W/QCamera2Factory(  281): getCameraInfo: X
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 3958): KNOX_SDCARD checking this for 1000
I/libpersona( 3958): KNOX_SDCARD not a persona,
I/GFX raster( 3714): took 0.657760ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88edb48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89280a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 3958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/AMMetaDataParserService( 3714): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
E/SELinux ( 3958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.668490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8922908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89280a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,W/VideoCapabilities( 3817): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3817): Unsupported mime audio/evrc
,W/AudioCapabilities( 3817): Unsupported mime audio/qcelp
,D/ChimeraCfgMgr( 1997): Reading stored module config
I/CheckinService( 1997): Disabling old GoogleServicesFramework version
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
W/AudioCapabilities( 3817): Unsupported mime audio/mpeg-L1
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaData,ParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131034113
,W/AudioCapabilities( 3817): Unsupported mime audio/mpeg-L2
I/AMMetaDataParserService( 3714): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 3958): TimaSignature is unavailable
,I/GFX raster( 3714): took 1.015157ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 3958): Added TimaKeyStore provider
,W/AudioCapabilities( 3817): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3817): Unsupported mime audio/x-ima
,I/AMMetaDataParserService( 3714): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.817187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a428 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3817): Unsupported mime audio/qcelp
,D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/AMMetaDataParserService( 3714): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/art     ( 1997): Suspending all threads took: 13.901ms
,W/AudioCapabilities( 3817): Unsupported mime audio/evrc
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.659948ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88dc3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/VideoCapabilities( 3817): Unsupported mime video/wvc1
,W/VideoCapabilities( 3817): Unsupported mime video/x-ms-wmv
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3976): MountEmulatedStorage(),
E/Zygote  ( 3976): v2
I/libpersona( 3976): KNOX_SDCARD checking this for 1000,
I/libpersona( 3976): KNOX_SDCARD not a persona
,I/SELinux ( 3976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/BootCompletedReceiver( 1997): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 1997): Got an BootCompleted event.
,I/SELinux ( 3976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1013): Killing 3100:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/GFX raster( 3714): took 0.715521ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89236f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3817): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/BootCompletedReceiver( 1997): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 1997): onCreate
,I/AMMetaDataParserService( 3714): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/TimaKeyStoreProvider( 3976): TimaSignature is unavailable
,D/ActivityThread( 3976): Added TimaKeyStore provider,
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/VideoCapabilities( 3817): Unsupported mime video/wvc1
,I/GFX raster( 3714): took 0.859844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3817): Unsupported mime video/x-ms-wmv
,D/SystemUpdateService( 1997): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/VideoCapabilities( 3817): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3817): Unsupported mime video/x-ms-wmv8
,I/AMMetaDataParserService( 3714): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,V/AuthZen ( 1997): Handling intent: android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 3817): Unsupported mime video/mp43
,I/CheckinService( 1997): Checking schedule, now: 1457596424815 next: 1457139499243
,W/VideoCapabilities( 3817): Unsupported mime video/sorenson
,I/CheckinService( 1997): active receiver: enabled
,W/libprocessgroup( 1013): failed to open /acct/uid_10086/pid_3100/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/VideoCapabilities( 3817): Unsupported mime video/mp4v-esdp
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.698803ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8922908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
,D/KnoxSetupWizardDbHelper( 3976): dbMigrationFlag : false
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/ShortcutReceiver( 3976):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/KnoxShortcutUtil( 3976): getIsShortcutMigrationFor_2_3_0_Done true
,I/GFX raster( 3714): took 0.693177ms for 96*96 texture 0
D/ShortcutReceiver( 3976):  KnoxContainerVersion 2.4.0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8927000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88c9da0 counterpartCT=4 counterpartW=96 counterparth=96
D/ShortcutReceiver( 3976):  shortcut migration not required 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/Zygote  ( 4004): MountEmulatedStorage(),
I/libpersona( 4004): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4004): v2
I/libpersona( 4004): KNOX_SDCARD not a persona
I/SELinux ( 4004): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4004): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4004): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1013): Killing 3207:com.dropbox.android/u0a92 (adj 15): empty #31
,I/SystemUpdateService( 1997): cancelUpdate (empty URL)
,D/TimaKeyStoreProvider( 4004): TimaSignature is unavailable
,D/AuthZenEventHandler( 1997): Handling event: android.intent.action.BOOT_COMPLETED
,D/ActivityThread( 4004): Added TimaKeyStore provider
D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/SystemUpdateService( 1997): active receiver: disabled
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3958): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3958): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VideoCapabilities( 3817): Unsupported profile 4 for video/mp4v-es
,I/DBG_POLICYDM( 3958): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3958): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3958): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.686458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88d0548 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8916970 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/libprocessgroup( 1013): failed to open /acct/uid_10092/pid_3207/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/KnoxSetupWizardClient( 4004): isShipMode : 1
I/KnoxSetupWizardClient( 4004): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714,): Resource data:2131165203
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/ResourcesManager( 3714): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,I/GFX construct_block_size_descriptor_2d second part( 3714): took 2.651823ms for 0*0 texture 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/GFX generate_partition_tables( 3714): took 10.240312ms for 0*0 texture 0
,I/GFX raster( 3714): took 13.724948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8adaa78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8adab20 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4027): MountEmulatedStorage(),
E/Zygote  ( 4027): v2
I/libpersona( 4027): KNOX_SDCARD checking this for 10107,
I/libpersona( 4027): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4027 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/SELinux ( 4027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1013): Killing 3084:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/SELinux ( 4027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/SELinux ( 4027): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/art     (  315): Explicit concurrent mark sweep GC freed 8779(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 770us total 25.926ms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3714): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.653ms
,I/DBG_POLICYDM( 3958): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3958): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/Babel   ( 3817): Creating RTCS
,D/TimaKeyStoreProvider( 4027): TimaSignature is unavailable
,D/ActivityThread( 4027): Added TimaKeyStore provider
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 21.310ms
,E/BaseAppContext( 1997): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,W/System.err( 4004): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4004): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4004): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4004): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4004): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4004): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4004): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 1.950573ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88f8f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88f9040 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,D/SystemUpdateService( 1997): onDestroy
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3714): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4053): MountEmulatedStorage()
I/libpersona( 4053): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4053): v2
I/libpersona( 4053): KNOX_SDCARD not a persona
I/SELinux ( 4053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4053): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4053 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3239:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4053): TimaSignature is unavailable
,D/ActivityThread( 4053): Added TimaKeyStore provider
,I/AuthZen ( 1997): Fetching signing key...
,I/art     ( 1628): Explicit concurrent mark sweep GC freed 5211(214KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 813us total 28.034ms
,W/SQLiteConnectionPool( 1628): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.764271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88f8f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88d9458 counterpartCT=4 counterpartW=96 counterparth=96
,I/AuthZen ( 1997): Signing key fetched successfully!
,I/AMMetaDataParserService( 3714): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,W/art     ( 3817): Suspending all threads took: 119.701ms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 2.571249ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb88f8f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8909838 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/a       ( 1997): Opening database auth.proximity.permit_store...
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 4053): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4053): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4053): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4053): PushLog.txt file is not deleted.
,D/SPPClientService( 4053): PushLog.txt file is not deleted.
I/DBG_POLICYDM( 3958): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/SPPClientService( 4053): ============PushLog. stop!
,D/AuthZenTransactionCache( 1997): Initialized cache in: /data/data/com.google.android.gms/files,
D/AuthZenTransactionCache( 1997): Clearing transaction cache,
I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 3958): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3958): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4083): MountEmulatedStorage(),
E/Zygote  ( 4083): v2
,I/libpersona( 4083): KNOX_SDCARD checking this for 10041
I/libpersona( 4083): KNOX_SDCARD not a persona,
I/ActivityManager( 1013): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4083 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1013): Killing 3256:com.fmm.dm/1000 (adj 15): empty #31
,I/SELinux ( 4083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 4083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4083): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/GFX raster( 3714): took 0.616458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89236f0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3817): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3817): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/TimaKeyStoreProvider( 4083): TimaSignature is unavailable
,D/ActivityThread( 4083): Added TimaKeyStore provider
,E/SQLiteLog( 3817): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 3817): (284) automatic index on conversation_participants_view(conversation_id)
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.606667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88dc3a0 counterpartCT=4 counterpartW=96 counterparth=96
,V/JNIHelp ( 3817): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AMMetaDataParserService( 3714): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/SQLiteLog( 3817): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/GCoreUlr( 1757): DispatchingService.onCreate()
,D/GCM     ( 1757): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10012
,D/StrictMode( 4027): StrictMode policy violation; ~duration=655 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4027): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4027): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4027): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4027): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4027): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4027): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=643 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4027): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4027): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4027): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4027): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4027): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=439 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4027): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4027): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4027): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4027): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4027): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4027): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=438 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4027): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4027): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4027): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4027): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrume,ntation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=438 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4027): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4027): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4027): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4027): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=426 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4027): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4027): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4027): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4027): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4027): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4027): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4027): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4027): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4027): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4027): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4027): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4027): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=425 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4027): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4027): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4027): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4027): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4027): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4027): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4027): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4027): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4027): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4027): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4027): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4027): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4027): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=368 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4027): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4027): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4027): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4027): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4027): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4027): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4027): StrictMode policy violation; ~duration=368 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4027): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4027): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4027): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4027): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4027): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4027): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4027): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4027): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4027): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4027): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4027): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4027): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4027): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4027): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
E/Zygote  ( 4103): MountEmulatedStorage()
E/Zygote  ( 4103): v2
I/ActivityManager( 1013): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/libpersona( 4103): KNOX_SDCARD checking this for 1000
I/libpersona( 4103): KNOX_SDCARD not a persona
I/SELinux ( 4103): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SA      ( 4083): [SSP] onCreated
I/SELinux ( 4103): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4103): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 3292:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
W/libprocessgroup( 1013): failed to open /acct/uid_10057/pid_3084/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10003/pid_3239/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3256/cgroup.procs: No such file or directory
E/SQLiteLog( 3817): (284) automatic index on conversation_participants_view(conversation_id)
V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3714): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3714): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.690730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89221b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8921d58 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4103): TimaSignature is unavailable
,D/ActivityThread( 4103): Added TimaKeyStore provider
,E/SQLiteLog( 3817): (284) automatic index on conversation_participants_view(conversation_id)
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SA      ( 4083): [TPM] There is no property file
,W/dex2oat ( 3926): Verification of boolean com.google.android.gms.maps.internal.j.onTransact(int, android.os.Parcel, android.os.Parcel, int) took 104.186ms
,W/ActivityThread( 3817): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3817): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26afd6fa: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3817): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1013): Killing 3308:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1013): failed to open /acct/uid_10060/pid_3292/cgroup.procs: No such file or directory
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/SA      ( 4083): [SCU] isHaveSA() - false
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,I/GFX construct_block_size_descriptor_2d second part( 3714): took 2.385156ms for 0*0 texture 0
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4083): [TPM] getModelProperty : null,
I/SA      ( 4083): [TPM] getCSCProperty : null
,I/Babel   ( 3817): Destroying RTCS
,D/SSRM:n  ( 1013): SIOP:: AP = 370
,D/StatusChecker( 4103): onReceive : android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1757): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4103): onReceive : net.mt.init : DONE
,I/GFX generate_partition_tables( 3714): took 8.976564ms for 0*0 texture 0
,I/GFX raster( 3714): took 12.309585ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e1ef40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8e1efe8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3714): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4083): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4083): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4083): [DM] TFT FEATURE: false
,E/Zygote  ( 4128): MountEmulatedStorage(),
E/Zygote  ( 4128): v2
,I/libpersona( 4128): KNOX_SDCARD checking this for 10116,
I/libpersona( 4128): KNOX_SDCARD not a persona
,I/ActivityManager( 1013): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4128 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
I/ActivityManager( 1013): Killing 3328:com.fmm.ds/1000 (adj 15): empty #31,
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 1757): Explicit concurrent mark sweep GC freed 24813(1795KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 12MB/20MB, paused 1.184ms total 110.905ms
,I/SELinux ( 4128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SA      ( 4083): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4083): [DM] init START
,D/TimaKeyStoreProvider( 4128): TimaSignature is unavailable
,D/ActivityThread( 4128): Added TimaKeyStore provider
,I/SA      ( 4083): [DM] This device is not a Vodafone
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.795312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24b30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e24c68 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourceType( 4083): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4083): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4083): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4083): No package identifier when getting value for resource number 0x00000000
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourceType( 4083): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4083): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4083): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4083): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4083): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4083): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,W/GCoreFlp( 1757): No location to return for getLastLocation()
,W/FusedLocationProvider( 1757): location=null
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.721614ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e26d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e26de0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3714): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/Auth    ( 1757): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/libprocessgroup( 1013): failed to open /acct/uid_10092/pid_3308/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3328/cgroup.procs: No such file or directory
,I/SA      ( 4083): [SCU] isHaveSA() - false
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,I/SA      ( 4083): support phone number id : false
I/SA      ( 4083): [DM] Supports Ref Jpn : true
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4083): [DM] init END
,I/SA      ( 4083): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4083): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1013): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,I/GFX raster( 3714): took 0.642135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e26108 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e261b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/PageBuddyNotiSvc( 4128): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4083): [OR] onReceive END
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1757): No location to return for getLastLocation()
,W/FusedLocationProvider( 1757): location=null
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
W/ContextImpl( 4128): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,E/Zygote  ( 4153): MountEmulatedStorage()
I/libpersona( 4153): KNOX_SDCARD checking this for 10042
E/Zygote  ( 4153): v2
I/libpersona( 4153): KNOX_SDCARD not a persona
,I/SELinux ( 4153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 4153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4153): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4153 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4128): onCreate mCpBitFlag=0
,I/SA      ( 4083): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4083): [ODM] queryOpenData(key= GEO_IP )
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4153): TimaSignature is unavailable
,D/ActivityThread( 4153): Added TimaKeyStore provider,
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3714): took 0.751250ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e260c8 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4083): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4083): [LBE] REF_JPN : true,
I/SA      ( 4083): [BDC] create
,E/Zygote  ( 4170): MountEmulatedStorage(),
E/Zygote  ( 4170): v2
I/libpersona( 4170): KNOX_SDCARD checking this for 10125
I/ActivityManager( 1013): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4170 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/libpersona( 4170): KNOX_SDCARD not a persona
,I/SELinux ( 4170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4170): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3714): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ResourcesManager( 4153): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
,D/TimaKeyStoreProvider( 4170): TimaSignature is unavailable
,I/AMMetaDataParserService( 3714): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 1.518489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb89221b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e260c8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 4170): Added TimaKeyStore provider,
D/PersistentNotificationBroadcastReceiver( 1757): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1757): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ResourcesManager( 4170): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4170): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4170): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SA      ( 4083): [DBMV2] getEmailID
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4083): [DBMV2] getDataV02ForItems
,I/SA      ( 4083): [SSP] query invoked
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.792604ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e1ef40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb891d210 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/GCoreUlr( 1757): Unbound from all location providers
,I/GCoreUlr( 1757): Place inference reporting - stopped
,I/SA      ( 4083): [SCU] get signed id from samsung account2.0 DB.
,I/CalendarProvider2( 4153): CalendarProvider2.onCreate() called
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.859688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24b30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e329a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4083): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4083): [BDC] destroy
,I/ActivityManager( 1013): Killing 3349:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/QuickConnect( 4170): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4170): Util.setSCRunningSetting - [value]0
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SettingsProvider( 1013): name = scon_is_running
,D/SettingsProvider( 1013): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1013): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1013): selectionArgs: false
D/SettingsProvider( 1013): selectionArgs: 10125
D/SecContentProvider( 1013): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1013): ret = -1
,W/BackupManagerService( 1013): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.671406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e26d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e260c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/QuickConnect( 4170): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/GCoreUlr( 1757): DispatchingService.onDestroy()
,I/GCoreUlr( 1757): Stopping handler for UlrDispSvcFast
,I/AMMetaDataParserService( 3714): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/QuickConnect( 4170): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4189): MountEmulatedStorage(),
E/Zygote  ( 4189): v2
I/libpersona( 4189): KNOX_SDCARD checking this for 10131
I/libpersona( 4189): KNOX_SDCARD not a persona
,I/SELinux ( 4189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4189): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4189 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
I/ActivityManager( 1013): Killing 3373:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.717552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e26108 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891d210 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/GCoreUlr( 1757): Unbound from all location providers
,I/GCoreUlr( 1757): Place inference reporting - stopped
,D/TimaKeyStoreProvider( 4189): TimaSignature is unavailable
,D/ActivityThread( 4189): Added TimaKeyStore provider
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.734010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e329a8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4189): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4189): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4189): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4189): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/com.google.a.a.b.d.a( 4027): Application name is not set. Call Builder#setApplicationName.
,W/libprocessgroup( 1013): failed to open /acct/uid_10062/pid_3349/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3373/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3714): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
,I/AMMetaDataParserService( 3714): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.681458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e31b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb891ca70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SBrowserFeatureFlag( 4189): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.649375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb892c0a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb89094f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ManifestProvider( 4189): onCreate()
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.635053ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8ada440 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/NetworkSettingsReceiver( 4189): onReceive: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 1.052813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a298 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8928170 counterpartCT=4 counterpartW=96 counterparth=96
,I/GAV2    ( 3630): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 3714): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.622864ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8ada440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8927e50 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,I/ActivityManager( 1013): Killing 3165:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,E/SBrowserFeatureFlag( 4189): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@37141799
,D/SBrowserFeatureFlag( 4189): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4189): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/SecDataIO(  255): Write to block
,V/AlarmManager( 1013): waitForAlarm result :4,
,E/SMD     (  289): DCD OFF
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.883333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8928170 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity,
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
,I/AMMetaDataParserService( 3714): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3714): getResourceTypeNamexml
E/Zygote  ( 4213): MountEmulatedStorage()
I/libpersona( 4213): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4213): v2
I/libpersona( 4213): KNOX_SDCARD not a persona
I/SELinux ( 4213): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 4213): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4213): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3714): took 0.714687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e31b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8927390 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1013): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4213 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3422:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3028): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3028): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3028): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.644479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb892c0a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8928170 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4213): TimaSignature is unavailable
,D/ActivityThread( 4213): Added TimaKeyStore provider
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3714): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.666303ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8927390 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4213): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4213): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4213): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.648958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a298 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88da9d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3714): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.630886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8ada440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8927390 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1013): failed to open /acct/uid_10009/pid_3165/cgroup.procs: No such file or directory
,I/iu.UploadsManager( 1997): End new media; added: 0, uploading: 0, time: 187 ms
,W/libprocessgroup( 1013): failed to open /acct/uid_10014/pid_3422/cgroup.procs: No such file or directory
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/dex2oat ( 3926): dex2oat took 3.589s (threads: 4)
,D/SensorService( 1013): [SO] 0.115 0.383 10.132
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.921146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb85a0420 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/DexOptUtils( 1997): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
D/DexOptUtils( 1997): Set odex to world readable.
,D/DexOptUtils( 1997): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
,D/FileApkUtils( 1997): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 31340(1818KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 26MB/39MB, paused 2.392ms total 177.347ms
,I/AMMetaDataParserService( 3714): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
I/Process ( 2625): Sending signal. PID: 2625 SIG: 9
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.901979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e31b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb892baa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/GmsModuleFndr( 1997): Beginning GMS chimera module scan
,D/ActivityManager( 1013): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/GmsModuleFndr( 1997): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/ChimeraCfgMgr( 1997): Beginning module configuration check
,D/ChimeraCfgMgr( 1997): Module APKs unchanged, check complete
,E/Zygote  ( 4238): MountEmulatedStorage(),
E/Zygote  ( 4238): v2
I/libpersona( 4238): KNOX_SDCARD checking this for 10139
I/libpersona( 4238): KNOX_SDCARD not a persona
,I/SELinux ( 4238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4238 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.654375ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb892c0a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8928170 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4238): TimaSignature is unavailable
,D/ActivityThread( 4238): Added TimaKeyStore provider
,I/ActivityManager( 1013): Process com.sec.android.app.sysscope (pid 2625)(adj 0) has died(113,1116)
E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.627240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8927390 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4238): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4238): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4238): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4238): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.640990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a298 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb89094f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/ActivityManager( 1013): Killing 3397:com.wssnps/1000 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 3146:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.628437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8ada440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89221b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4255): MountEmulatedStorage()
,E/Zygote  ( 4255): v2
I/libpersona( 4255): KNOX_SDCARD checking this for 10145
I/libpersona( 4255): KNOX_SDCARD not a persona
,I/SELinux ( 4255): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4255 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 4255): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/GFX raster( 3714): took 0.732761ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb890a110 counterpartCT=4 counterpartW=96 counterparth=96
,E/SELinux ( 4255): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3714): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
I/AMMetaDataParserService( 3714): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4255): TimaSignature is unavailable
I/GFX raster( 3714): took 0.745469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e31b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8927e50 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityThread( 4255): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.642240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb892c0a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb891ca70 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4255): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4255): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4255): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4255): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.637188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8708448 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb88da9d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.727500ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb890a298 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb85a0420 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.718334ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8ada440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb892baa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.718073ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb8e24cf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8928170 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1013): failed to open /acct/uid_10015/pid_3146/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3397/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 an,droid.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.widget.Noti,ceDeleteActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131165197
W/ResourcesManager( 3714): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/RCPManagerService( 1013): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 3714): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,I/AMMetaDataParserService( 3714): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3714): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3714): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131165197
,I/AMMetaDataParserService( 3714): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3714): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3714): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,I/DBG_DM  ( 3028): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,I/AMMetaDataParserService( 3714): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/DBG_DM  ( 3028): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 3028): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131165197
I/AMMetaDataParserService( 3714): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,I/AMMetaDataParserService( 3714): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId,
,E/Zygote  ( 4278): MountEmulatedStorage(),
,E/Zygote  ( 4278): v2
I/libpersona( 4278): KNOX_SDCARD checking this for 10072
I/libpersona( 4278): KNOX_SDCARD not a persona
,I/SELinux ( 4278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AMMetaDataParserService( 3714): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/ActivityManager( 1013): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4278 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/ActivityManager( 1013): startService callerProcessName:com.android.email, calleePkgName: com.android.email
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,I/SELinux ( 4278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
E/SELinux ( 4278): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/AMMetaDataParserService( 3714): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/art     (  315): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 24.046ms
,D/TimaKeyStoreProvider( 4278): TimaSignature is unavailable
D/ActivityThread( 4278): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.869ms
,I/AMMetaDataParserService( 3714): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.163ms
D/BadgeProvider( 4278): onCreate
D/BadgeProvider( 4278): DatabaseHelper
E/Zygote  ( 4298): MountEmulatedStorage()
I/libpersona( 4298): KNOX_SDCARD checking this for 10146
E/Zygote  ( 4298): v2
I/libpersona( 4298): KNOX_SDCARD not a persona
I/SELinux ( 4298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4298 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 3545:com.android.managedprovisioning/u0a22 (adj 15): empty #31
I/ActivityManager( 1013): Killing 3475:com.sec.esdk.elm/u0a94 (adj 15): empty #32
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
I/AMMetaDataParserService( 3714): Resource data:2131099648
,D/BadgeProvider( 4278): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 4298): TimaSignature is unavailable
,D/ActivityThread( 4298): Added TimaKeyStore provider
W/ResourcesManager( 3714): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,D/BadgeProvider( 4278): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4278): sendNotify, [notify] : null
D/BadgeProvider( 4278): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4278): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4278): update, [UpdateCount] : 1
,D/Launcher.Model( 1465): reloadBadges entered.
I/AMMetaDataParserService( 3714): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ResourcesManager( 4298): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,W/ActivityManager( 1013): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/Process ( 4255): Sending signal. PID: 4255 SIG: 9
,W/libprocessgroup( 1013): failed to open /acct/uid_10022/pid_3545/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10094/pid_3475/cgroup.procs: No such file or directory
,D/RCPManagerService( 1013): exchangeData() failure , invalid userId
,D/ActivityManager( 1013): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4315): MountEmulatedStorage()
,E/Zygote  ( 4315): v2
I/libpersona( 4315): KNOX_SDCARD checking this for 1000
I/libpersona( 4315): KNOX_SDCARD not a persona
,I/SELinux ( 4315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/CalendarProvider2( 4153): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/SELinux ( 4315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/lowmemorykiller(  253): Error writing /proc/4255/oom_score_adj; errno=22
I/ActivityManager( 1013): Killing 3451:com.samsung.android.sm/1000 (adj 15): empty #31
E/SELinux ( 4315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
E/JavaBinder( 4298): !!! FAILED BINDER TRANSACTION !!!
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3714): Resource data:2131165220
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1013): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/ActivityManager( 1013): Process com.android.email (pid 4255)(adj 11) has died(100,1130)
,W/ResourcesManager( 3714): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3714): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3714): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3714): getResourceTypeNamexml
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.857708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb9025990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb90256c0 counterpartCT=4 counterpartW=96 counterparth=96
I/Process ( 4298): Sending signal. PID: 4298 SIG: 9
,D/TimaKeyStoreProvider( 4315): TimaSignature is unavailable
,D/ActivityThread( 4315): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3714): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/        ( 3714): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3714): took 0.600625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3714): Bitmap=0xb90257e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9038998 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3714): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DockSettings
I/ActivityManager( 1013): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1013): Killing 3557:com.sec.factory.camera/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/libpersona( 4331): KNOX_SDCARD checking this for 1000
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/libpersona( 4331): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1013): Killing 3590:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/ActivityManager( 1013): Process com.android.exchange (pid 4298)(adj 9) has died(104,1130)
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getRes,ourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
,I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3451/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3557/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3590/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
W/ProcessCpuTracker( 1013): Skipping unknown process pid 4298
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3714): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3714): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3714): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
E/Zygote  ( 4331): MountEmulatedStorage()
E/Zygote  ( 4331): v2
I/SELinux ( 4331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4331): TimaSignature is unavailable
D/ActivityThread( 4331): Added TimaKeyStore provider
D/SecurityLogAgent( 4331): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4331): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4331): StateMachine : Current State = 1
D/SecurityLogAgent( 4331): BootReceiver : completed task. Failed to return wakelock . 
I/splitIntent( 1013): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/splitIntent( 1013): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1013): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1013): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1013): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/WearableService( 1757): callingUid 10012, callindPid: 1757
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1757): [226] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1997): Restart initialization of location
,D/AuthorizationBluetoothService( 1757): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1757): No location to return for getLastLocation()
,W/FusedLocationProvider( 1757): location=null
,I/HomeSyncInstallReceiver( 1427): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1013): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47,
I/splitIntent( 1013): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=4353 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4353): MountEmulatedStorage()
I/libpersona( 4353): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4353): v2
I/libpersona( 4353): KNOX_SDCARD not a persona
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,I/SELinux ( 4353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
I/SELinux ( 4353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 4368): MountEmulatedStorage()
E/Zygote  ( 4368): v2
I/libpersona( 4368): KNOX_SDCARD checking this for 10044
I/libpersona( 4368): KNOX_SDCARD not a persona
,I/SELinux ( 4368): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 4353): TimaSignature is unavailable
,I/SELinux ( 4368): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityThread( 4353): Added TimaKeyStore provider
,E/SELinux ( 4368): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=4368 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4368): TimaSignature is unavailable
,D/ActivityThread( 4368): Added TimaKeyStore provider
,E/Zygote  ( 4383): MountEmulatedStorage(),
E/Zygote  ( 4383): v2
I/libpersona( 4383): KNOX_SDCARD checking this for 1000
,I/libpersona( 4383): KNOX_SDCARD not a persona
,I/SELinux ( 4383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=4383 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4398): MountEmulatedStorage()
E/Zygote  ( 4398): v2
I/libpersona( 4398): KNOX_SDCARD checking this for 10152
,I/libpersona( 4398): KNOX_SDCARD not a persona
,I/SELinux ( 4398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4398 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
E/SELinux ( 4398): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4383): TimaSignature is unavailable
,D/ActivityThread( 4383): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4398): TimaSignature is unavailable
,D/ActivityThread( 4398): Added TimaKeyStore provider
,W/ResourcesManager( 4383): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4368): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4368): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4368): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4368): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4368): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4368): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4368): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/AASAservice-UpdateReceiver( 4353): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.example.hello, uid = -1
,I/AASAservice-TokenRule( 4353): parseToken()
,W/System.err( 4353): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4353): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 4353): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 4353): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 4353): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 4353): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 4353): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4353): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4353): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4353): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4353): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4353): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4353): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4353): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4353): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4353): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 4353): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4353): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4353): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 4353): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 4353): 	... 14 more
E/AASAservice-TokenRule( 4353): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 4353): AASARuleUpdateResult() : Rule file is not exist.
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4398): (284) automatic index on shooting_modes(title_id)
,E/Zygote  ( 4413): MountEmulatedStorage()
E/Zygote  ( 4413): v2
,I/libpersona( 4413): KNOX_SDCARD checking this for 10015
I/libpersona( 4413): KNOX_SDCARD not a persona
,I/SELinux ( 4413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4413 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 4413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Killing 3580:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
E/SELinux ( 4413): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4427): MountEmulatedStorage()
,E/Zygote  ( 4427): v2
I/libpersona( 4427): KNOX_SDCARD checking this for 10156
I/libpersona( 4427): KNOX_SDCARD not a persona
,I/SELinux ( 4427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4427 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,I/SELinux ( 4427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Killing 3610:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
D/TimaKeyStoreProvider( 4413): TimaSignature is unavailable
D/ActivityThread( 4413): Added TimaKeyStore provider
E/SELinux ( 4427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,D/TimaKeyStoreProvider( 4427): TimaSignature is unavailable
,D/ActivityThread( 4427): Added TimaKeyStore provider
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1013): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4448 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4448): MountEmulatedStorage()
E/Zygote  ( 4448): v2
I/libpersona( 4448): KNOX_SDCARD checking this for 1000
I/libpersona( 4448): KNOX_SDCARD not a persona
,I/SELinux ( 4448): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4448): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4448): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 3276:com.sec.pcw.device/1000 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 4448): TimaSignature is unavailable
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3580/cgroup.procs: No such file or directory
,D/ActivityThread( 4448): Added TimaKeyStore provider
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/JavaBinder( 1013): !!! FAILED BINDER TRANSACTION !!!,
W/BroadcastQueue( 1013): Exception when sending broadcast to ComponentInfo{com.sec.pcw.device/com.sec.pcw.device.receiver.SYSTEMReceiver}
W/BroadcastQueue( 1013): android.os.TransactionTooLargeException
W/BroadcastQueue( 1013): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1013): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1013): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1013): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1013): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1013): 	,at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20562)
W/BroadcastQueue( 1013): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1013): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3405)
W/BroadcastQueue( 1013): 	at android.os.Binder.execTransact(Binder.java:461)
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4448): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4427): onReceive()
E/Zygote  ( 4465): MountEmulatedStorage()
I/libpersona( 4465): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4465): v2
I/libpersona( 4465): KNOX_SDCARD not a persona
D/TapandpayWidget:TapandpayAppWidgetProvider( 4427): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/SELinux ( 4465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4465 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 4465): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NearbySource( 4368): Nearby Source Create!
D/NearbyContext( 4368): Nearby Context Create!
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4465): TimaSignature is unavailable
,I/art     (  315): Explicit concurrent mark sweep GC freed 8775(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 689us total 21.476ms
,I/TapandpayWidget:Utils( 4427): Clear T&P info.
,D/ActivityThread( 4465): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10100/pid_3610/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3276/cgroup.procs: No such file or directory
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4427): Widget is not attached.
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.027ms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4368): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 4368): Samsung link source created
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 16.723ms
,E/Zygote  ( 4482): MountEmulatedStorage()
E/Zygote  ( 4482): v2
I/libpersona( 4482): KNOX_SDCARD checking this for 10091
I/libpersona( 4482): KNOX_SDCARD not a persona
,I/SELinux ( 4482): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4482 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3648:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31,
,I/SELinux ( 4482): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4482): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Killing 3659:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/TimaKeyStoreProvider( 4482): TimaSignature is unavailable
,D/ActivityThread( 4482): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,D/Finsky  ( 3777): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4499): MountEmulatedStorage()
I/libpersona( 4499): KNOX_SDCARD checking this for 10010
E/Zygote  ( 4499): v2
I/libpersona( 4499): KNOX_SDCARD not a persona
,I/PCWCLIENTTRACE_LOG( 4465): DEFAULT_LOGON : true
I/SELinux ( 4499): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/PCWCLIENTTRACE_LOG( 4465): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4465): new DMDBOpenHelper instance
,I/SELinux ( 4499): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4499): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4499 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PCWCLIENTTRACE_PushUtil( 4465): SPPPushClient is installed : true
I/ActivityManager( 1013): Killing 3737:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
I/PCWCLIENTTRACE_PushUtil( 4465): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4465): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4465): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1013): failed to open /acct/uid_10069/pid_3648/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10031/pid_3659/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4499): TimaSignature is unavailable,
,D/ActivityThread( 4499): Added TimaKeyStore provider
,E/Zygote  ( 4514): MountEmulatedStorage()
,E/Zygote  ( 4514): v2
I/libpersona( 4514): KNOX_SDCARD checking this for 10032
I/libpersona( 4514): KNOX_SDCARD not a persona
,I/SELinux ( 4514): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4514 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 4514): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1013): Killing 3177:com.google.android.youtube/u0a166 (adj 15): empty #31
,E/SELinux ( 4514): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ContactProvider( 4368): getAllContactInfoList Start
D/WifiDisplayAdapter( 1013): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 4368): PackagesMonitor onReceive :com.example.hello
,D/TimaKeyStoreProvider( 4514): TimaSignature is unavailable
,D/ActivityThread( 4514): Added TimaKeyStore provider
,D/ContactProvider( 4368): getAllContactInfoList End
,I/syncContacts( 4368): thread: 693, sync time = 114
,W/libprocessgroup( 1013): failed to open /acct/uid_10032/pid_3737/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10166/pid_3177/cgroup.procs: No such file or directory
,I/FeatureConfig( 4514): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/BatteryService( 1013): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1013): level:100, scale:100, status:2, health:2, present:true, voltage: 4318, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1013): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1013): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1013): Plugged
,I/MotionRecognitionService( 1013): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ResourcesManager( 4514): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 4514): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3958): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4514): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4514): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4533): MountEmulatedStorage()
,I/libpersona( 4533): KNOX_SDCARD checking this for 10046
E/Zygote  ( 4533): v2
I/libpersona( 4533): KNOX_SDCARD not a persona
,I/SELinux ( 4533): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=4533 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 4533): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1013): Killing 3630:com.google.android.gm/u0a101 (adj 15): empty #31
,E/SELinux ( 4533): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1013): Killing 3908:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,W/ResourcesManager( 4514): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4514): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1997): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/TimaKeyStoreProvider( 4533): TimaSignature is unavailable
,D/ActivityThread( 4533): Added TimaKeyStore provider
,E/Zygote  ( 4549): MountEmulatedStorage()
,E/Zygote  ( 4549): v2
I/libpersona( 4549): KNOX_SDCARD checking this for 10038
I/libpersona( 4549): KNOX_SDCARD not a persona
,I/SELinux ( 4549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 4514): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/SELinux ( 4549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4549): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4549 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1997): Loading module APK com.google.android.play.games
D/TimaKeyStoreProvider( 4549): TimaSignature is unavailable
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4549): Added TimaKeyStore provider
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4533): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4533): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4533): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4533): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4533): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4533): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4549): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4549): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4514): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4514): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1013): failed to open /acct/uid_10101/pid_3630/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_10034/pid_3908/cgroup.procs: No such file or directory
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/PhotosPlugin( 4482): Loading PhotosPlugin
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MmsApp( 4533): [start]    onCreate() consume time = 0.0
,W/GalaxyFinderApplication( 4514): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4566): MountEmulatedStorage()
,E/Zygote  ( 4566): v2
I/ActivityManager( 1013): Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=4566 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
I/libpersona( 4566): KNOX_SDCARD checking this for 10032
I/SELinux ( 4566): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4566): KNOX_SDCARD not a persona
,I/SELinux ( 4566): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4566): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4566): TimaSignature is unavailable
,D/ActivityThread( 4566): Added TimaKeyStore provider
,W/art     ( 4533): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 134.983ms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 4533): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 123.179ms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/TelephonyPermission( 4533): start operation mode monitor
,D/Mms/ArtClassLoader( 4533): init before art
,W/ResourcesManager( 4533): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1997): Module APK com.google.android.play.games already loaded
,D/Mms/TelephonyPermission( 4533): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4533): isDefault true
,D/Mms/MmsApp( 4533): onCreate() com.android.mms
,I/Icing   ( 1997): Storage manager: low false usage 1.73MB avail 10.18GB capacity 11.68GB
,D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1997): Submit a task: k
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1997): Processing package: com.example.hello
,D/GassUtils( 1997): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 1997): Found info for package com.example.hello in db.
,D/ActivityManager( 1013): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 31909(1965KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.379ms total 151.590ms
,I/PeopleDatabaseHelper( 1997): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,I/SL_DEBUG( 4549): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 4549): isLoggable:: SL_DEBUG_EXIST = false
,D/Mms/MmsApp( 4533): [start]    initCountryIso consume time = 662.865521
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,D/CountryDetector( 1013): The first listener is added
,D/Mms/MmsApp( 4533): [end]    initCountryIso consume time = 26.956042,
D/Mms/MmsConfig( 4533): [start]    MmsConfig.init() consume time = 0.133958
,D/Mms/MmsConfig( 4533): before partial update
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,D/Mms/MmsConfig( 4533): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4533): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4533): isAuth is false
,D/Mms/MmsConfig( 4533): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1442): query,matched:2117, calling pid = 4533,
,D/TP/MmsSmsProvider( 1442): match 2117:Elapsed time : 2.843 ms
,D/EasySignUpManager_1.0.1( 4533): isAuth is false
D/EasySignUpManager_1.0.1( 4533): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4533): mps_code.dat does not exist
E/CscParser( 4533): customer_path =/system/csc/customer.xml
E/CscParser( 4533): fileName + /system/csc/customer.xml
,W/BaseAppContext( 1997): Using Auth Proxy for data requests.
,E/CscParser( 4533): mps_code.dat does not exist
E/CscParser( 4533): customer_path =/system/csc/customer.xml
E/CscParser( 4533): fileName + /system/csc/customer.xml
,D/CscParser( 4533): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4533):  enable multiwindow = true
,D/Mms/ArtClassLoader( 4533): init [DONE] art
,E/Mms/MessageUtils( 4533): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4533): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4533): [end]    init() consume time = 139.065781
,D/Mms/Contact( 4533): [start]    init() consume time = 0.758646
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4549): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1442): query,matched:13, calling pid = 4533
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/TP/MmsSmsProvider( 1442): match 13:Elapsed time : 9.580 ms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4549): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/Mms/Contact( 4533): [end]    init consume time = 73.936823
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/Mms/DraftCache( 4533): [start]    rebuildCache consume time = 23.054219
,D/TP/MmsSmsProvider( 1442): query,matched:12, calling pid = 4533
,D/TP/MmsSmsProvider( 1442): match 12:Elapsed time : 9.504 ms
,D/Mms/DraftCache( 4533): [end]    rebuildCache consume time = 16.689427
,D/Mms/MethodReflector( 4533): getSubId is called
D/Mms/TelephonyUtils( 4533): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4533): getTelephonyProperty is called
D/Mms/DownloadManager( 4533): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4533): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4533): auto download without roaming -> true
D/Mms/DownloadManager( 4533): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 4533): getSubId is called
,D/Mms/MethodReflector( 4533): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4533): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4533): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4533): getTelephonyProperty is called
D/Mms/DownloadManager( 4533): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4533): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4533): auto download without roaming -> true
D/Mms/DownloadManager( 4533): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4533): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4533): mAutoDownload ------> true
,I/SA      ( 4083): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4083): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4083): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
,D/ComposerPerformance( 4533): 1457596430808 ms / [DONE] Composer constructor
,E/CII     ( 4533): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4533): ReservationManager()
,I/Mms/ReservationManager( 4533): resetAfterConnected()
,D/TP/MmsSmsProvider( 1442): query,matched:7, calling pid = 4533
,D/PowerManagerService( 1013): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1013): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/Conversation( 4533): [start]    init() consume time = 67.2875
,D/TP/MmsSmsProvider( 1442): match 7:Elapsed time : 5.951 ms
,D/PowerManagerService( 1013): [s] DisplayPowerCallbacks : onStateChanged()
,D/TP/MmsSmsProvider( 1442): deleteConversation threadId: 9223372036854775807
,I/Mms/ReservationManager( 4533): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1442): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1442): updateThread(), thread_id = 9223372036854775807
,D/Mms/MmsApp( 4533): [end]    onCreate() consume time = 11.527135
,V/TP/MmsSmsDatabaseHelper( 1442): sUpgradeVersion = 0, db.getVersion() = 81
,D/lights  ( 1013): lcd : 32 +
,E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1442): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1442): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1442): need read changed broadcast:false
,D/Mms/Conversation( 4533): [end]    init consume time = 11.486875
,D/Mms/MessagingNotification( 4533): [start]    init() consume time = 4.13099
,D/Mms/MessagingNotification( 4533): [end]    init consume time = 2.264218
D/DisplayPowerController( 1013): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1013): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1013): lcd : 32 -
,D/lights  ( 1013): lcd : 19 +
,D/Mms/SpamFilter( 4533): [start]    SpamFilter fill() begin consume time = 4.499167
,D/Mms/Synchronizer( 4533): [start]    doSync consume time = 2.65276
,D/TP/MmsSmsProvider( 1442): query,matched:0, calling pid = 4533
V/TP/MmsSmsProvider( 1442): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1442): query,matched:400, calling pid = 4533
D/TP/MmsSmsProvider( 1442): match 0:Elapsed time : 0.024 ms
,D/TP/MmsSmsProvider( 1442): update, matched:300, calling pid = 4533
V/TP/MmsSmsProvider( 1442): syncDBData start
,V/TP/MmsSmsProvider( 1442): syncDBData sms end
,V/TP/MmsSmsProvider( 1442): syncDBData mms end
,D/lights  ( 1013): lcd : 19 -
,D/DisplayPowerController( 1013): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1013): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/TP/MmsSmsProvider( 1442): syncDBData end
,D/Mms/Synchronizer( 4533): [end]    doSync consume time = 11.666823
,D/Mms/SpamFilter( 4533): [end]    SpamFilter fill() finished consume time = 3.076667
,D/Mms/MessagingNotification( 4533): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1442): query,matched:26, calling pid = 4533
,D/TP/SmsProvider( 1442): match 26:Elapsed time : 1.484 ms
,D/TP/MmsSmsProvider( 1442): query,matched:6, calling pid = 4533
,D/TP/MmsSmsProvider( 1442): match 6:Elapsed time : 1.734 ms
,D/Mms/DownloadManager( 4533): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4533): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4533): getSubId is called
,D/Mms/TelephonyUtils( 4533): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4533): getTelephonyProperty is called
,D/Mms/DownloadManager( 4533): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4533): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 4533): auto download without roaming -> true
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/Mms/DownloadManager( 4533): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4533): mAutoDownload ------> true
,E/Zygote  ( 4634): MountEmulatedStorage()
I/libpersona( 4634): KNOX_SDCARD checking this for 10025
E/Zygote  ( 4634): v2
I/libpersona( 4634): KNOX_SDCARD not a persona
I/SELinux ( 4634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4634 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 3942:com.samsung.helphub/1000 (adj 15): empty #31
,D/Mms/FreeMessageStatusReceiver( 4533): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1013): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4634): TimaSignature is unavailable
,D/ActivityThread( 4634): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 4533): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 4533): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 4652): MountEmulatedStorage()
E/Zygote  ( 4652): v2
I/libpersona( 4652): KNOX_SDCARD checking this for 10047
I/libpersona( 4652): KNOX_SDCARD not a persona
,I/SELinux ( 4652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4652): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1013): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4652 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 4004:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/ActivityManager( 1013): Killing 3976:com.sec.knox.foldercontainer/1000 (adj 15): empty #32
,W/ResourcesManager( 4634): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4652): TimaSignature is unavailable
,D/ActivityThread( 4652): Added TimaKeyStore provider
,W/GAV2    ( 4482): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3942/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4004/cgroup.procs: No such file or directory
W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_3976/cgroup.procs: No such file or directory
,I/Icing   ( 1997): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 4652): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4652): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4652): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/OMACP   ( 4634): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 4533): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true,
W/art     ( 1997): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 140.301ms
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 4634): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ResourcesManager( 4566): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4566): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4566): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4566): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MyFiles ( 4652): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4670): MountEmulatedStorage()
,E/Zygote  ( 4670): v2
I/libpersona( 4670): KNOX_SDCARD checking this for 10004
I/libpersona( 4670): KNOX_SDCARD not a persona
,I/SELinux ( 4670): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4670 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager( 1013): Killing 4027:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/SELinux ( 4670): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4670): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/TactileAssist( 1013): enable value -1
,I/TactileAssist( 1013): internal enable value -1
,I/TactileAssist( 1013): intensity value -1
I/TactileAssist( 1013): saveAppList value true
,I/TactileAssist( 1013): List of disabled apps :
,D/TimaKeyStoreProvider( 4670): TimaSignature is unavailable
,D/ActivityThread( 4670): Added TimaKeyStore provider
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4686): MountEmulatedStorage(),
E/Zygote  ( 4686): v2
I/libpersona( 4686): KNOX_SDCARD checking this for 10053
I/libpersona( 4686): KNOX_SDCARD not a persona
,I/SELinux ( 4686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4686 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 4686): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4686): TimaSignature is unavailable
,D/ActivityThread( 4686): Added TimaKeyStore provider
,W/ContextImpl( 1013): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/installd(  282): system dir 0 : /system/app/
,E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/PackageManager( 1013): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,W/ResourcesManager( 4686): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/art     ( 1997): Background sticky concurrent mark sweep GC freed 7974(574KB) AllocSpace objects, 4(64KB) LOS objects, 5% free, 13MB/13MB, paused 5.652ms total 35.242ms
,D/Compatibility( 4686): onReceive() it will make start service
,D/ActivityManager( 1013): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4686): onHandleIntent()
,D/Compatibility( 4686): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
D/Compatibility( 4686): found: 2
W/GAV2    ( 4482): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 4712): MountEmulatedStorage()
,E/Zygote  ( 4712): v2
I/libpersona( 4712): KNOX_SDCARD checking this for 10057
I/libpersona( 4712): KNOX_SDCARD not a persona
,I/SELinux ( 4712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/Compatibility( 4686): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
I/SELinux ( 4712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4712): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/Compatibility( 4686): skipping ResolveInfo{2a48c8 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 4686): considering ResolveInfo{6de1d61 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,D/Compatibility( 4686): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 4686): enabling receiver ResolveInfo{338c4086 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/ActivityManager( 1013): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4712 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4686): enabling receiver ResolveInfo{1c047d47 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 4712): TimaSignature is unavailable
D/ActivityThread( 4712): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 27.737ms
,D/Compatibility( 4686): enabling receiver ResolveInfo{37ff2974 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 4686): enabling receiver ResolveInfo{19fe2e9d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 4686): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 27.979ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.122ms,
,W/libprocessgroup( 1013): failed to open /acct/uid_10107/pid_4027/cgroup.procs: No such file or directory
,E/Zygote  ( 4729): MountEmulatedStorage()
,E/Zygote  ( 4729): v2,
I/libpersona( 4729): KNOX_SDCARD checking this for 10100
I/SELinux ( 4729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 4729): KNOX_SDCARD not a persona,
,I/ActivityManager( 1013): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4729 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
I/SELinux ( 4729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ChimeraCfgMgr( 1997): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1997): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1013): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1757): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1013): Killing 4103:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4729): TimaSignature is unavailable
,D/ActivityThread( 4729): Added TimaKeyStore provider
,W/AccountFeatureHelper( 4482): Write apps_features disabled false
,D/PackageIntentReceiver( 4729): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 4729): Not GearManger package! 
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Watchdog( 1013): !@Sync 1
,E/Zygote  ( 4748): MountEmulatedStorage()
I/libpersona( 4748): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4748): v2
I/libpersona( 4748): KNOX_SDCARD not a persona
,I/SELinux ( 4748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1013): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 4748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4103/cgroup.procs: No such file or directory
,E/SELinux ( 4748): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/SettingsProvider( 1013): name = audio_safe_volume_state
,W/GAV2    ( 4482): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1013): Killing 4170:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4748): TimaSignature is unavailable
,D/ActivityThread( 4748): Added TimaKeyStore provider
,I/ActivityManager( 1013): Killing 4189:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/Icing   ( 1997): Internal init done: storage state 0
,I/Icing   ( 1997): Post-init done
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/UpdateIcingCorporaServi( 4712): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4768): MountEmulatedStorage(),
I/ActivityManager( 1013): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4768): v2
,I/libpersona( 4768): KNOX_SDCARD checking this for 1000
I/libpersona( 4768): KNOX_SDCARD not a persona
I/ActivityManager( 1013): Killing 4213:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 4768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4768): TimaSignature is unavailable,
D/ActivityThread( 4768): Added TimaKeyStore provider
,W/libprocessgroup( 1013): failed to open /acct/uid_10131/pid_4189/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10125/pid_4170/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_10135/pid_4213/cgroup.procs: No such file or directory
,D/LocationManagerService( 1013): getProviders()=[passive]
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 4768): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 4768): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/art     ( 1628): Explicit concurrent mark sweep GC freed 3910(162KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 775us total 29.049ms,
E/Zygote  ( 4792): MountEmulatedStorage()
E/Zygote  ( 4792): v2
I/libpersona( 4792): KNOX_SDCARD checking this for 10120
I/libpersona( 4792): KNOX_SDCARD not a persona
I/SELinux ( 4792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4792): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1013): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4792 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 4768): Enter Oncreate
,D/AcmsServiceMonitor( 4768): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 4768): creating AcmsCore
,D/AcmsCore( 4768): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 4768): AcmsCore
,D/TimaKeyStoreProvider( 4792): TimaSignature is unavailable
,D/ActivityThread( 4792): Added TimaKeyStore provider
,D/AcmsCore( 4768): init
D/AcmsCore( 4768): Looper handler is not null
D/AcmsCore( 4768): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4768): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4768): Incrementing - Counter value: 1
D/AcmsCore( 4768): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsCertificateMngr( 4768): AcmsCertificateMngr
,D/AcmsService( 4768): onStartCommand
,D/AcmsService( 4768): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 4768): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 4768): Incrementing - Counter value: 2
D/AcmsService( 4768): Incremented Counter Value : onStartCommand
,D/AcmsRevocationMngr( 4768): AcmsRevocationMngr
,D/ActivityManager( 1013): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 4768): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,W/ResourcesManager( 4792): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 4768): Inside handle Intent
D/AcmsService( 4768): App added - package name: com.example.hello
D/AcmsCore( 4768): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4768): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4768): Incrementing - Counter value: 3
D/AcmsCore( 4768): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 4768): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 4768): Decrementing - Counter value: 2
,I/UpdateIcingCorporaServi( 4712): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] ,
,I/ActivityManager( 1013): Killing 4153:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{2f356c1b u0 com.samsung.android.providers.context/.ContextService}
,W/libprocessgroup( 1013): failed to open /acct/uid_10042/pid_4153/cgroup.procs: No such file or directory
,I/ActivityManager( 1013): Waited long enough for: ServiceRecord{19c7f164 u0 com.android.settings/.wifi.WifiCredService}
,V/AlarmManager( 1013): waitForAlarm result :4
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1013): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus,
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus,
,I/splitIntent( 1013): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget,
D/ActivityManager( 1013): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast,
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4815): MountEmulatedStorage(),
E/Zygote  ( 4815): v2
I/libpersona( 4815): KNOX_SDCARD checking this for 10142
I/libpersona( 4815): KNOX_SDCARD not a persona,
I/SELinux ( 4815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1013): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=4815 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4815): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1013): Killing 4238:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4815): TimaSignature is unavailable
,D/ActivityThread( 4815): Added TimaKeyStore provider
,V/TaskCloserActivity( 4815): TaskCloserActivity enter()
,V/TaskCloserActivity( 4815): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/ActivityManager( 1013): Killing 4315:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/ActivityManager( 1013): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1013): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1013): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4831): MountEmulatedStorage()
,E/Zygote  ( 4831): v2
I/libpersona( 4831): KNOX_SDCARD checking this for 1000
I/libpersona( 4831): KNOX_SDCARD not a persona
,I/SELinux ( 4831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1013): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4831 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4831): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1013): failed to open /acct/uid_10139/pid_4238/cgroup.procs: No such file or directory
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4315/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4831): TimaSignature is unavailable
,D/ActivityThread( 4831): Added TimaKeyStore provider
,E/MTPRx   ( 4831): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1013): mCursor = null
,D/SecContentProvider2( 1013): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1013): mCursor = null
,V/MTPRx   ( 4831): sealedState: false
V/MTPRx   ( 4831): sealedUsbMassStorageState: false
E/MTPRx   ( 4831): check value of boot_completed is1
E/MTPRx   ( 4831): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4831): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4831): Status for mount/Unmount :removed
,E/MTPRx   ( 4831): SDcard is not available
,W/MTPRx   ( 4831): value of connected istrue
,W/MTPRx   ( 4831): value of configured istrue
W/MTPRx   ( 4831): value of mtpEnabled istrue
,W/MTPRx   ( 4831): value of ptpEnabled isfalse
,E/MTPRx   ( 4831): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4831): mFirstTime: false
,D/        ( 4831): MTP: reading debug level property
,E/MTPJNIInterface( 4831): Getting CryptionKey from JAVA
,E/MTPRx   ( 4831): currentUserId is 0
,E/MTPRx   ( 4831): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4831): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4831): is_Privatemode is NOT 1
,D/SettingsProvider( 1013): name = boot_time_connected
,E/MTPRx   ( 4831): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4831): noti = 17
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,D/SecContentProvider( 1013): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4831): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1013): name = mtp_running_status
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
E/MTPRx   ( 4831): else part ... so first time!!!
,E/MTPPlaObsrvr( 4831): inside setContext()
E/MTPPlaObsrvr( 4831):  inside createplafiles
,I/SecKeyguardClockSingleView( 1175): Ignore. Because it is same clock text
,I/Icing   ( 1997): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,D/Icing   ( 1997): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1997): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,I/Mms/MmsApp( 4533):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 4533): [start]    fillCache consume time = 1962.439166
,D/Mms/ComposeMessageFragment( 4533): fillCache, easy = false
,I/art     ( 1013): Explicit concurrent mark sweep GC freed 18843(1119KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.115ms total 145.365ms
,E/MTPPlaObsrvr( 4831): playlist count is0
,E/MTPPlaObsrvr( 4831):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4831):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4831): Inside registerContentObserver
,E/MtpAdbObserver( 4831): inside setContext()
,E/MtpAdbObserver( 4831): Inside registerContentObserver
W/Settings( 4831): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1013): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,V/MtpMediaDBManager( 4831): inside deleteAllDB
,D/SettingsProvider( 1013): name = mtp_running_status
,D/SettingsProvider( 1013): name = mtp_usb_conditions_met
,E/MtpService( 4831): onCreate.
,D/ActivityManager( 1013): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ValidateNoPeople( 1013): mEvictionCount: 0
,D/ActivityManager( 1013): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1013): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/ActivityManager( 1013): Killing 4331:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,E/MtpService( 4831): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4831): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4831): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/MTPRx   ( 4831): calling native method
E/MTPJNIInterface( 4831): < MTP > Registering BroadCast receiver :::::
,E/MTPJNIInterface( 4831): < MTP > Registering BroadCast receiver :::::::
,W/ActivityManager( 1013): userId = 0, bbcId = -10000,
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 4831): noti = 10
E/MtpService( 4831): onStartCommand.
,E/MtpService( 4831): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/ContactProvider( 4368): getAllContactInfoList Start
,V/MtpMediaDBManager( 4831): inside Thread updateDB
,W/MTPRx   ( 4831): calling native method
,E/MTPRx   ( 4831): Checking the driver time out
,E/MTPJNIInterface( 4831): noti = 2
,D/        ( 4831): deleting sockets before message queue initialization
,D/        ( 4831): event handler thread is created, so set the flag
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPRx   ( 4831): called native method
,E/MTPJNIInterface( 4831): setting Media scanner status0
E/MTPJNIInterface( 4831): After setting Media scanner status0
E/MtpService( 4831): onStartCommand.
,E/MtpService( 4831): handleMessage. msg= { when=-3ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,V/UserPresentBroadcastReceiver( 1757): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/MtpMediaDBManager( 4831): count : 27
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
D/AbsListView( 4533): Get MotionRecognitionManager
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/MTPRx   ( 4831): notification from stack 1
,D/MotionRecognitionService( 1013):  ssp status : false
E/        ( 4831): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4831): Getting media scanner status0
,D/ActivityManager( 1013): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MTPJNIInterface( 4831): DeviceName is A5-1
,D/Mms/ComposeMessageFragment( 4533): [end]    fillCache consume time = 138.322812
,W/ActivityManager( 1013): userId = 0, bbcId = -10000
,W/ActivityManager( 1013): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1013): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/MtpMediaDBManager( 4831): sending db update complete noti to stack
E/MTPJNIInterface( 4831): noti = 29
,E/MTPJNIInterface( 4831): Status for mount/Unmount :removed
E/MTPJNIInterface( 4831): SDcard is not available
,D/ContactProvider( 4368): getAllContactInfoList End
,I/syncContacts( 4368): thread: 695, onChange
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,E/        ( 4831): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,E/        ( 4831): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/libprocessgroup( 1013): failed to open /acct/uid_1000/pid_4331/cgroup.procs: No such file or directory
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1346): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1346): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1346): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/MTPJNIInterface( 4831): Status for mount/Unmount :removed
E/MTPJNIInterface( 4831): SDcard is not available
E/SQLiteLog( 4831): (21) API call with NULL database connection pointer
D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
E/SQLiteLog( 4831): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4831): (21) API call with NULL database connection pointer
E/SQLiteLog( 4831): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4831): (21) API call with NULL database connection pointer
E/SQLiteLog( 4831): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4831): (21) API call with NULL database connection pointer
E/SQLiteLog( 4831): (21) misuse at line 106108 of [9491ba7d73]
D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457617980000
D/daemonapp( 1346): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457596433042
,W/MTPRx   ( 4831): notification from stack 2
D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/        ( 4831): [mtp_init_device] Library open with 32 bits.
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/        ( 4831): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 4831): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4831): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 4831):  [sua_support_present:1287] returning false 
D/        ( 4831): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1346): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1346): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1346): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1346): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!

```
