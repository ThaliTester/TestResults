#### Test 50388019831b9e1_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ContextImpl( 2196): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/ContextImpl( 2196): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
--------- beginning of system
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2196): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2196): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
E/USB_UICC(  297): Timeout! No signal received. Retry num = 20
I/WebViewFactory( 2196): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/LibraryLoader( 2196): Time to load native libraries: 10 ms (timestamps 6766-6776)
I/LibraryLoader( 2196): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2196): Binding Chromium to main looper Looper (main, tid 1) {2f7c1226}
I/LibraryLoader( 2196): Expected native library version number "",actual native library version number ""
I/chromium( 2196): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2196): Initializing chromium process, singleProcess=true
W/art     ( 2196): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2196): ApplicationContext is null in ApplicationStatus
W/chromium( 2196): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 2196): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2196): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 2196): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
I/Adreno-EGL( 2196): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2196): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2196): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2196): Local Branch: 
I/Adreno-EGL( 2196): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2196): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2196):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/AudioManagerAndroid( 2196): Requires BLUETOOTH permission
I/NSApplication( 2196): Starting up...
D/SettingsProvider( 1014): name = vibrate_in_silent
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
W/ResourcesManager( 1444): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/CscReceiver( 1444): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1444): Recieve Sim State Changed : ABSENT
I/splitIntent( 1014): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1014): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1444, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
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
E/Zygote  ( 2256): MountEmulatedStorage()
E/Zygote  ( 2256): v2
I/libpersona( 2256): KNOX_SDCARD checking this for 1000
I/libpersona( 2256): KNOX_SDCARD not a persona
I/SELinux ( 2256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/WifiApBroadcastReceiver( 1281): onReceive: action android.intent.action.SIM_STATE_CHANGED
I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2256 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
E/SELinux ( 2256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2267): MountEmulatedStorage()
E/Zygote  ( 2267): v2
I/libpersona( 2267): KNOX_SDCARD checking this for 1000
I/libpersona( 2267): KNOX_SDCARD not a persona
I/SELinux ( 2267): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2267 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
I/SELinux ( 2267): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2267): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/BootupListener( 1444): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1014): name = internet_call_settings_visibility
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/PhoneUtilsCommon( 1444): isSupportVoLTE is false.
D/TimaKeyStoreProvider( 2256): TimaSignature is unavailable
D/ActivityThread( 2256): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 2267): TimaSignature is unavailable
D/ActivityThread( 2267): Added TimaKeyStore provider
E/Zygote  ( 2285): MountEmulatedStorage()
E/Zygote  ( 2285): v2
I/libpersona( 2285): KNOX_SDCARD checking this for 10046
I/libpersona( 2285): KNOX_SDCARD not a persona
I/SELinux ( 2285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2285 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 2285): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TimaKeyStoreProvider( 2285): TimaSignature is unavailable
D/ActivityThread( 2285): Added TimaKeyStore provider
W/ResourcesManager( 2285): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2285): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2285): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2285): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2285): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2285): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/StatusChecker( 2256): onReceive : android.intent.action.SIM_STATE_CHANGED
I/StatusChecker( 2256): onReceive : net.mt.init : 
D/StatusChecker( 2256): onReceive : preference initializing
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2304): MountEmulatedStorage()
E/Zygote  ( 2304): v2
I/libpersona( 2304): KNOX_SDCARD checking this for 1000
I/libpersona( 2304): KNOX_SDCARD not a persona
I/SELinux ( 2304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2304 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
I/SELinux ( 2304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2313): MountEmulatedStorage()
E/Zygote  ( 2313): v2
I/libpersona( 2313): KNOX_SDCARD checking this for 1000
I/libpersona( 2313): KNOX_SDCARD not a persona
I/SELinux ( 2313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2313 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2304): TimaSignature is unavailable
D/ActivityThread( 2304): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2313): TimaSignature is unavailable
D/ActivityThread( 2313): Added TimaKeyStore provider
I/Omc:Receiver( 2304): onReceive : android.intent.action.SIM_STATE_CHANGED
I/Omc:OmcData( 2304): omc.xml not exist
I/Omc:Receiver( 2304): OM Customize disabled
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2334): MountEmulatedStorage()
E/Zygote  ( 2334): v2
I/libpersona( 2334): KNOX_SDCARD checking this for 10131
I/libpersona( 2334): KNOX_SDCARD not a persona
I/SELinux ( 2334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2334 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
I/SELinux ( 2334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2334): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/art     (  309): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 21.901ms
D/TimaKeyStoreProvider( 2334): TimaSignature is unavailable
D/ActivityThread( 2334): Added TimaKeyStore provider
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 17.095ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 16.476ms
E/Zygote  ( 2351): MountEmulatedStorage()
E/Zygote  ( 2351): v2
I/libpersona( 2351): KNOX_SDCARD checking this for 1000
I/libpersona( 2351): KNOX_SDCARD not a persona
I/SELinux ( 2351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2351 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2351): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MmsApp( 2285): [start]    onCreate() consume time = 0.0
W/ResourcesManager( 2334): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2334): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2334): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2334): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2351): TimaSignature is unavailable
D/ActivityThread( 2351): Added TimaKeyStore provider
D/AndroidRuntime( 2340): 
D/AndroidRuntime( 2340): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2340): CheckJNI is OFF
D/AndroidRuntime( 2340): readGMSProperty: start
D/AndroidRuntime( 2340): readGMSProperty: already setted!!
D/AndroidRuntime( 2340): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2340): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2340): readGMSProperty: end
D/AndroidRuntime( 2340): addProductProperty: start
W/art     ( 2285): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 115.524ms
D/SBrowserFeatureFlag( 2334): initialized in static block : loadCscFeatureValue() succeed! 
D/ManifestProvider( 2334): onCreate()
D/Mms/ArtClassLoader( 2285): init before art
D/Mms/TelephonyPermission( 2285): start operation mode monitor
E/OperatorBookmarksSIMReceiver( 2334): onReceive runs..android.intent.action.SIM_STATE_CHANGED
W/ResourcesManager( 2285): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/USB_UICC(  297): Timeout! No signal received. Retry num = 21
D/Mms/TelephonyPermission( 2285): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2285): isDefault true
D/Mms/MmsApp( 2285): onCreate() com.android.mms
E/AffinityControl( 2340): AffinityControl: registerfunction enter
D/AndroidRuntime( 2340): Calling main entry com.android.commands.am.Am
D/Mms/MmsApp( 2285): [start]    initCountryIso consume time = 379.258124
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
D/CountryDetector( 1014): The first listener is added
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1014): mDVFSHelper.acquire()
I/SurfaceFlinger(  257): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  257): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1014): Set to : 0
D/Mms/MmsApp( 2285): [end]    initCountryIso consume time = 19.86724
D/Mms/MmsConfig( 2285): [start]    MmsConfig.init() consume time = 0.083438
D/Launcher.HomeView( 1467): onPause
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1467
D/Launcher( 1467): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 2340): Shutting down VM
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
D/Mms/MmsConfig( 2285): before partial update
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2382): MountEmulatedStorage()
I/libpersona( 2382): KNOX_SDCARD checking this for 10177
E/Zygote  ( 2382): v2
I/libpersona( 2382): KNOX_SDCARD not a persona
I/SELinux ( 2382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2382 uid=10177 gids={50177, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 2382): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/Mms/MmsConfig( 2285): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 2285): serviceId : 1, features : -1
D/EasySignUpManager_1.0.1( 2285): isAuth is false
D/Mms/MmsConfig( 2285): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
V/ActivityThread( 1467): updateVisibility : ActivityRecord{2862dd9b token=android.os.BinderProxy@1563532c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TP/MmsSmsProvider( 1444): query,matched:2117, calling pid = 2285
D/TP/MmsSmsProvider( 1444): match 2117:Elapsed time : 3.471 ms
D/TimaKeyStoreProvider( 2382): TimaSignature is unavailable
D/ActivityThread( 2382): Added TimaKeyStore provider
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1467): onStop
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/ActivityThread( 1467): updateVisibility : ActivityRecord{2862dd9b token=android.os.BinderProxy@1563532c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1467): onTrimMemory. Level: 20
D/PersonaManager( 1014): isKioskContainerExistOnDevice
D/EasySignUpManager_1.0.1( 2285): isAuth is false
D/EasySignUpManager_1.0.1( 2285): getServiceStatus : serviceId (1) is OFF
E/CscParser( 2285): mps_code.dat does not exist
E/CscParser( 2285): customer_path =/system/csc/customer.xml
E/CscParser( 2285): fileName + /system/csc/customer.xml
E/CscParser( 2285): mps_code.dat does not exist
E/CscParser( 2285): customer_path =/system/csc/customer.xml
E/CscParser( 2285): fileName + /system/csc/customer.xml
D/CscParser( 2285): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 2285):  enable multiwindow = true
E/Mms/MessageUtils( 2285): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2285): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2285): [end]    init() consume time = 182.89802
D/Mms/Contact( 2285): [start]    init() consume time = 2.549375
I/WebViewFactory( 2382): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/Mms/Contact( 2285): [end]    init consume time = 20.244688
I/LibraryLoader( 2382): Time to load native libraries: 2 ms (timestamps 8009-8011)
I/LibraryLoader( 2382): Expected native library version number "",actual native library version number ""
D/TP/MmsSmsProvider( 1444): query,matched:13, calling pid = 2285
D/Mms/DraftCache( 2285): [start]    rebuildCache consume time = 7.075885
D/TP/MmsSmsProvider( 1444): match 13:Elapsed time : 2.876 ms
D/TP/MmsSmsProvider( 1444): query,matched:12, calling pid = 2285
D/TP/MmsSmsProvider( 1444): match 12:Elapsed time : 2.467 ms
D/Mms/DraftCache( 2285): [end]    rebuildCache consume time = 22.507604
W/art     ( 2340): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Mms/MethodReflector( 2285): getSubId is called
V/WebViewChromiumFactoryProvider( 2382): Binding Chromium to main looper Looper (main, tid 1) {3bf27c8e}
D/Mms/TelephonyUtils( 2285): getLongSubId from simSlot 0, return Value = -1
,I/LibraryLoader( 2382): Expected native library version number "",actual native library version number ""
I/chromium( 2382): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/Mms/MethodReflector( 2285): getTelephonyProperty is called
,D/Mms/DownloadManager( 2285): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 2285): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 2285): auto download without roaming -> true
D/Mms/DownloadManager( 2285): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 2285): getSubId is called
,D/Mms/MethodReflector( 2285): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2285): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2285): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2285): getTelephonyProperty is called
D/Mms/DownloadManager( 2285): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2285): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2285): auto download without roaming -> true
D/Mms/DownloadManager( 2285): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2285): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2285): mAutoDownload ------> true
,I/BrowserStartupController( 2382): Initializing chromium process, singleProcess=true
,W/art     ( 2382): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2382): ApplicationContext is null in ApplicationStatus
,W/chromium( 2382): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,D/Mms/ArtClassLoader( 2285): init [DONE] art
,W/chromium( 2382): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2382): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 2382): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 2382): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2382): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2382): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2382): Local Branch: 
I/Adreno-EGL( 2382): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2382): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2382):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ComposerPerformance( 2285): 1451921604634 ms / [DONE] Composer constructor
,E/CII     ( 2285): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 2285): ReservationManager()
D/Mms/Conversation( 2285): [start]    init() consume time = 112.053959
,I/Mms/ReservationManager( 2285): resetAfterConnected()
,D/TP/MmsSmsProvider( 1444): query,matched:7, calling pid = 2285
,D/TP/MmsSmsDatabaseHelper( 1444): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 1444): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1444): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1444): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 1444): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
,D/TP/MmsSmsProvider( 1444): match 7:Elapsed time : 11.536 ms
,D/TP/MmsSmsProvider( 1444): deleteConversation threadId: 9223372036854775807
,I/Mms/ReservationManager( 2285): getReservedSendMessageCount(): retMessageCount=0
D/Mms/MmsApp( 2285): [end]    onCreate() consume time = 20.073802
D/Mms/SmsReceiver( 2285): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
D/TP/MmsSmsProvider( 1444): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1444): updateThread(), thread_id = 9223372036854775807
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
V/TP/MmsSmsDatabaseHelper( 1444): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
D/Mms/DownloadManager( 2285): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 2285): roaming ------> false, mSimSlot = 0
I/splitIntent( 1014): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/MethodReflector( 2285): getSubId is called
D/Mms/TelephonyUtils( 2285): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2285): getTelephonyProperty is called
D/Mms/DownloadManager( 2285): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2285): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2285): auto download without roaming -> true
D/Mms/DownloadManager( 2285): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/Mms/DownloadManager( 2285): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1444): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1444): need read changed broadcast:false
,D/Mms/Conversation( 2285): [end]    init consume time = 20.322135
,D/BootupListener( 1444): intent.getAction() = android.intent.action.SERVICE_STATE
,D/SettingsProvider( 1014): name = internet_call_settings_visibility
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/PhoneUtilsCommon( 1444): isSupportVoLTE is false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
,D/StatusChecker( 2256): onReceive : android.intent.action.SERVICE_STATE
,D/Mms/MessagingNotification( 2285): [start]    init() consume time = 12.967813
,D/Mms/SmsReceiverService( 2285): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
I/StatusChecker( 2256): onReceive : net.mt.init : DONE
,D/Mms/TelephonyPermission( 2285): isDefault true
,D/Mms/SmsReceiverService( 2285): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
,D/Mms/SmsReceiverService( 2285): handleSIMStatus()
D/Mms/SmsReceiverService( 2285): handleSIMStatus(): SIM_STATUS = ABSENT
,D/Mms/MessagingNotification( 2285): [end]    init consume time = 3.706562
,D/BluetoothAdapter( 2382): 776241221: getState() :  mService = null. Returning STATE_OFF
,D/Mms/SpamFilter( 2285): [start]    SpamFilter fill() begin consume time = 7.218594
,D/StatusChecker( 2256): Service state changed : 3 mSub-1
,D/Mms/Synchronizer( 2285): [start]    doSync consume time = 4.273802
,D/TP/MmsSmsProvider( 1444): query,matched:400, calling pid = 2285
,D/TP/MmsSmsProvider( 1444): query,matched:0, calling pid = 2285
V/TP/MmsSmsProvider( 1444): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1444): match 0:Elapsed time : 1.930 ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1444): update, matched:300, calling pid = 2285
,V/TP/MmsSmsProvider( 1444): syncDBData start
,V/TP/MmsSmsProvider( 1444): syncDBData sms end
D/Mms/SpamFilter( 2285): [end]    SpamFilter fill() finished consume time = 22.213906
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
V/TP/MmsSmsProvider( 1444): syncDBData mms end
,V/TP/MmsSmsProvider( 1444): syncDBData end
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/Synchronizer( 2285): [end]    doSync consume time = 7.331459
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
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
,D/Mms/MessagingNotification( 2285): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/TP/SmsProvider( 1444): query,matched:26, calling pid = 2285
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/SmsProvider( 1444): match 26:Elapsed time : 1.989 ms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
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
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/chromium( 2382): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/accuweather( 1738): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/TP/MmsSmsProvider( 1444): query,matched:6, calling pid = 2285
,D/TP/MmsSmsProvider( 1444): match 6:Elapsed time : 3.278 ms
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1738): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1738): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1738): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1738): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
D/accuweather( 1738): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1738): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1738): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SurfaceFlinger(  257): id=7 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=7 Removed Mauncher (-2/8)
,W/art     ( 2382): Attempt to remove local handle scope entry from IRT, ignoring
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2423): MountEmulatedStorage(),
I/libpersona( 2423): KNOX_SDCARD checking this for 10025,
E/Zygote  ( 2423): v2
I/libpersona( 2423): KNOX_SDCARD not a persona
I/SELinux ( 2423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2423 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 2423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/AwContents( 2382): onDetachedFromWindow called when already detached. Ignoring,
D/accuweather( 1738): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1738): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 1738): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1738): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1738): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,D/PhoneWindow( 2382): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2382): *FMB* installDecor flags : 8456448
,E/accuweather( 1738): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 16 33
,E/accuweather( 1738): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/SystemWebViewEngine( 2382): CordovaWebView is running on device made by: samsung
,D/TimaKeyStoreProvider( 2423): TimaSignature is unavailable
,D/ActivityThread( 2423): Added TimaKeyStore provider
,D/accuweather( 1738): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1738): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1738): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1738): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1738): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1738): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,W/art     ( 2382): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2382): Attempt to remove local handle scope entry from IRT, ignoring
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1738): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ResourcesManager( 2423): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/accuweather( 1738): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1738): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1738): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
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
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1304): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1304): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/OpenGLRenderer( 2382): Render dirty regions requested: true
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 2382): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2382): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 2382
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2382): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2382): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2382): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2382): Enabling debug mode 0
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1172): There is/are notification(s) 
,I/Timeline( 2382): Timeline: Activity_idle id: android.os.BinderProxy@27df04b5 time:28588
,I/SamsungIME( 1885): getCurrentCandidateView
,I/ActivityManager( 1014): Displayed Component not be shown by security: +768ms
,W/ActivityManager( 1014): mDVFSHelper.release()
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{26dd1990 u0 com.example.hello/.MainActivity t2} time:28597
,I/OMACP   ( 2423): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 2285): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 2423): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
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
,E/SMD     (  288): DCD OFF
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SamsungIME( 1885): Dismiss ExpandCandiate
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
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
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 22
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
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2450 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
E/Zygote  ( 2450): MountEmulatedStorage()
E/Zygote  ( 2450): v2
I/libpersona( 2450): KNOX_SDCARD checking this for 10020
I/libpersona( 2450): KNOX_SDCARD not a persona
,I/SELinux ( 2450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2450): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2450): TimaSignature is unavailable
,D/ActivityThread( 2450): Added TimaKeyStore provider
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
W/ResourcesManager( 2450): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2450): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/BindingManager( 2382): Cannot call determinedVisibility() - never saw a connection for the pid: 2382
,I/chromium( 2382): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,I/SamsungIME( 1885): KeybaordView init() : load resources
,I/SamsungIME( 1885): getCurrentKeyboard
,I/SamsungIME( 1885): getTextKeyboard
,D/JsMessageQueue( 2382): Set native->JS mode to OnlineEventsBridgeMode
,D/SamsungIME( 1885): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/AndroidProtocolHandler( 2382): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/EasySignUpManager_1.15.0305( 2450): serviceId : 0, features : -1
,I/splitIntent( 1014): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1014): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2475): MountEmulatedStorage()
,E/Zygote  ( 2475): v2
I/libpersona( 2475): KNOX_SDCARD checking this for 10044
I/libpersona( 2475): KNOX_SDCARD not a persona
,I/SELinux ( 2475): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2475 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 2475): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2475): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2475): TimaSignature is unavailable
,D/ActivityThread( 2475): Added TimaKeyStore provider
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2490 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/Zygote  ( 2490): MountEmulatedStorage()
E/Zygote  ( 2490): v2
I/libpersona( 2490): KNOX_SDCARD checking this for 10088
I/libpersona( 2490): KNOX_SDCARD not a persona
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2490): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 2498): MountEmulatedStorage()
I/libpersona( 2498): KNOX_SDCARD checking this for 10142
E/Zygote  ( 2498): v2
I/libpersona( 2498): KNOX_SDCARD not a persona
I/SELinux ( 2498): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2498): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2498): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2498 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 2498): TimaSignature is unavailable
,D/ActivityThread( 2498): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2490): TimaSignature is unavailable
,D/ActivityThread( 2490): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1467, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/TaskCloserActivity( 2498): TaskCloserActivity enter()
,E/Zygote  ( 2521): MountEmulatedStorage(),
E/Zygote  ( 2521): v2
I/ActivityManager( 1014): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2521 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a,
I/libpersona( 2521): KNOX_SDCARD checking this for 10054
I/libpersona( 2521): KNOX_SDCARD not a persona
,I/SELinux ( 2521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2521): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 1014): Explicit concurrent mark sweep GC freed 36047(1963KB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 25MB/37MB, paused 4.379ms total 175.543ms,
,W/ResourcesManager( 2475): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2475): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2475): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2475): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 2475): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2475): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2475): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/TaskCloserActivity( 2498): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/SecContentProvider2( 1014): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): isCopyContactToSimAllowed = true
,D/jxcore_app_log( 2382): JniHelper::setJavaVM(0xb747f450), pthread_self() = -1214380096
,D/JX-Cordova( 2382): jxcore cordova android initializing
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/TimaKeyStoreProvider( 2521): TimaSignature is unavailable
,D/ActivityThread( 2521): Added TimaKeyStore provider
,W/ResourcesManager( 2490): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2521): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/jxcore-log( 2382): Initializing JXcore engine
W/jxcore-log( 2382): JXcore engine is ready
,W/jxcore-log( 2382): Starting JXcore engine
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2537): MountEmulatedStorage(),
E/Zygote  ( 2537): v2
I/libpersona( 2537): KNOX_SDCARD checking this for 10139,
I/libpersona( 2537): KNOX_SDCARD not a persona
,I/SELinux ( 2537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2537 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,D/Recents_RecreateReceiver( 2521): onReceive by home
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,D/TimaKeyStoreProvider( 2537): TimaSignature is unavailable
,D/ActivityThread( 2537): Added TimaKeyStore provider
,W/ResourcesManager( 2537): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2537): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2537): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2537): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2537): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/audit   ( 1909): type=1400 msg=audit(1451921605.934:203): avc:  denied  { ioctl } for  pid=2382 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1909):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1909): type=1300 msg=audit(1451921605.934:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=5 a3=bedecd58 items=0 ppid=309 ppcomm=main pid=2382 auid=4294967295 uid=10177 gid=10177 euid=10177 suid=10177 fsuid=10177 egid=10177 sgid=10177 fsgid=10177 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1909): type=1320 msg=audit(1451921605.934:203): 
,W/jxcore-log( 2382): Platform android
W/jxcore-log( 2382): 
W/jxcore-log( 2382): Process ARCH arm
W/jxcore-log( 2382): 
,I/jxcore-log( 2382): JXcore Cordova bridge is ready!
I/jxcore-log( 2382): 
,W/jxcore-log( 2382): JXcore engine is started
,W/art     ( 2450): Verification of void com.android.contacts.common.list.l.P() took 119.914ms
,E/jxcore-log( 2382): >> samsung-SM-A500FU
E/jxcore-log( 2382): 
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 23
I/jxcore-log( 2382): Total memory 1983791104
I/jxcore-log( 2382): 
,I/jxcore-log( 2382): Free memory 412606464
I/jxcore-log( 2382): 
I/jxcore-log( 2382): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2382): 
I/jxcore-log( 2382): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2382): 
,I/jxcore-log( 2382): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2382): 
,I/jxcore-log( 2382): Size 720 1280
I/jxcore-log( 2382): 
,I/jxcore-log( 2382): Screen Brightness 5
I/jxcore-log( 2382): 
,E/jxcore-log( 2382): Dummy Error Log.
E/jxcore-log( 2382): 
,D/NearbySource( 2475): Nearby Source Create!
,D/NearbyContext( 2475): Nearby Context Create!
,D/SamsungIME( 1885): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2475): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2475): Samsung link source created
,D/AbsListView( 2450): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/ContactProvider( 2475): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2475): Receive : home resume
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 2285): ui event
,I/splitIntent( 1014): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SQLiteLog( 1223): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
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
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ContactProvider( 2475): getAllContactInfoList End
,I/syncContacts( 2475): thread: 253, sync time = 77
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
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
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
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SIP     ( 1444): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1444): fail readDirectory() errno=2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1804): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Mms/MmsApp( 2285):  start initViewCache mms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/Mms/ComposeMessageFragment( 2285): [start]    fillCache consume time = 1927.435832
,D/Mms/ComposeMessageFragment( 2285): fillCache, easy = false
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
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
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
,I/jxcore-log( 2382): getBuffer is called!!!!
I/jxcore-log( 2382): 
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
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1304): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1304): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/AbsListView( 2285): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 2285): [end]    fillCache consume time = 160.884479
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1172): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,D/AdaptiveEventManager( 1172): currentCityId is null
D/AdaptiveEventManager( 1172): NetWork disabled : Don't refresh weather info : 205
,D/AdaptiveEventManager( 1172): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
E/daemonapp( 1304): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/AdaptiveEventManager( 1172): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1172): Widget Count: Previous= 0 >> Now= 0
,D/AdaptiveEventManager( 1172): mWeatherInfo is not reliable
D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/daemonapp( 1304): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1304): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1304): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2567): MountEmulatedStorage()
E/Zygote  ( 2567): v2
I/libpersona( 2567): KNOX_SDCARD checking this for 10135
I/libpersona( 2567): KNOX_SDCARD not a persona
,I/SELinux ( 2567): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/Mms/BubbleViewCache( 2285): fillCache bubble = 1
I/SELinux ( 2567): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2567): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2567 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1451921607023
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1451943207015
D/daemonapp( 1304): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
D/daemonapp( 1304): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1451943180000
,D/daemonapp( 1304): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1451943180000
,D/TimaKeyStoreProvider( 2567): TimaSignature is unavailable
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1451943180000
D/ActivityThread( 2567): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2582): MountEmulatedStorage()
E/Zygote  ( 2582): v2
I/libpersona( 2582): KNOX_SDCARD checking this for 1000
I/libpersona( 2582): KNOX_SDCARD not a persona
,I/SELinux ( 2582): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2582): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2582 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 20.497ms
,D/TimaKeyStoreProvider( 2582): TimaSignature is unavailable
,D/ActivityThread( 2582): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.322ms total 40.221ms
,W/ResourcesManager( 2567): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2567): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2567): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 17.975ms
,I/Scheduler( 1804): Use legacy PeriodicScheduler
,W/InstanceID/Rpc( 1804): Found 10012
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 24
,D/SecurityLogAgent( 2582):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2582):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2582):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent( 2582): FileZippingService : onHandleIntent 
,D/SecurityLogAgent( 2582): FileZippingService : file path =  /data/misc/audit/audit.old
,D/SecurityLogAgent( 2582): FileZippingService : onPremise disabled. Zipping..  
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SecurityLogAgent( 2582): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2582): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2582): DenialLogFileZipCreator : Files exceeded the max limit 
,D/SecurityLogAgent( 2582): DenialLogFileZipCreator File existence : true audit.old file size 631
,D/SecurityLogAgent( 2582): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2582): FileZippingService : completed task. Returning wakelock . 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1804): callingUid 10012, callindPid: 1804
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsWearableNodeHelper( 1804): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1804): [203] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 2049): Restart initialization of location
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1444): query,matched:0, calling pid = 2049
,D/TP/SmsProvider( 1444): match 0:Elapsed time : 1.375 ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1444): Query uri=content://mms, match=0, calling pid = 2049
,D/TP/SmsProvider( 1444): query,matched:0, calling pid = 2049
,D/TP/SmsProvider( 1444): match 0:Elapsed time : 1.558 ms
,D/TP/MmsProvider( 1444): Query uri=content://mms, match=0, calling pid = 2049
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1804): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1804): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/IcingInternalCorpora( 2049): getNumBytesRead when not calculated.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1804): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2627): MountEmulatedStorage(),
E/Zygote  ( 2627): v2
I/libpersona( 2627): KNOX_SDCARD checking this for 1000
I/libpersona( 2627): KNOX_SDCARD not a persona
,I/SELinux ( 2627): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2627 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2627): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2627): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GCoreFlp( 1804): No location to return for getLastLocation()
,W/FusedLocationProvider( 1804): location=null
,D/TimaKeyStoreProvider( 2627): TimaSignature is unavailable
,D/ActivityThread( 2627): Added TimaKeyStore provider
,W/ContextImpl( 2627): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2643): MountEmulatedStorage(),
E/Zygote  ( 2643): v2
I/libpersona( 2643): KNOX_SDCARD checking this for 1000
I/libpersona( 2643): KNOX_SDCARD not a persona
,I/SELinux ( 2643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2643 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2643): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2643): TimaSignature is unavailable
,D/ActivityThread( 2643): Added TimaKeyStore provider
,W/ResourcesManager( 2643): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$onReceive](2643) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2643): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) is Live Demo : false
,D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) deviceXML=a5ulte.dat
D/FactoryTestApp( 2643): [XMLDataStorage$parseXML](2643) nameXML=a5ultexx.dat
D/FactoryTestApp( 2643): [XMLDataStorage$parseAsset](2643) parseAsset Is Started,
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
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PANEL_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_NAME_ACCELEROMETER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SPEAKER_COUNT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MIC_COUNT
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_VIBRATOR
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_LTE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_RCV
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FACTORY_TEST_APO
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_EPEN
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SENSORHUB
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_CAM_FRONT_NOT_ISP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=NEED_CAMDRIVER_OPEN
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HW_VER_EFS
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_HOVER_HIGHTLIGHT
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_AUTO_WAKELOCK,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_MULTI_SIM_FRAMEWORK
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_DSDS_MSIMM_CHECK
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FONT_SIZE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=RAM_SIZE_IF
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=MULTI_TSK_THD
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_FUNCTION_FONT_SIZE
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_FM_RADIO
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
I/GAV4    ( 2196): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_GRAPHIC_ACCLETOR
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_VOLUME_UP
,I/GAv4-SVC( 2049): Google Analytics 8.4.89 is starting up.
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_POWER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_HOME
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_BACK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_TOUCH_KEY_ODER,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_KEY_TEST_VOLUME_UP,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_KEY_TEST_VOLUME_DOWN,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEMI_KEY_TEST_HOME
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_KEY_TEST_THRESHOLD,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_TSP_STANDARD_CHANNEL
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_SENSOR_TEST_ACC_REVERSE,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_GEOMAGNETIC_ALPS_CAL
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=GEOMAGNETIC_IC_POINT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=AT_GPSSTEST
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_TEMP_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HALL_IC_TEST
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=READ_TARGET_GEOMAGNETIC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_NODE_COUNT_HEIGHT,
,E/SMD     (  288): DCD OFF
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_MIN_MELFAS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATTERY_VOLT_AVER,
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 25,
D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=BATTERY_VF_OCV
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_THERMISTER_CELCIUS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=SEC_EXT_THERMISTER_TEMP,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_THERMISTER_ADC,
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 15723(876KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 25MB/37MB, paused 1.875ms total 134.229ms
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_COMMAND_CMD,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS,
,D/FactoryTestApp( 2643): [XMLDataStorage$redefinitionById](2643) id=LPA_MODE_SET,
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
,D/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$onReceive](2643) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2643): [Support$Values.getBoolean](2643) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2643): [Support$Properties.get](2643) property=ro.factory.factory_binary
D/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$onReceive](2643) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2643): [ModuleCommon$getFtClientEnableState](2643) result : false
I/FactoryTestApp( 2643): [ModuleCommon$connectedJIG](2643) ...
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2643): [ModuleCommon$connectedJIG](2643) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2643): [Support$Kernel.read](2643) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2643): [ModuleCommon$connectedJIG](2643) value = 1f, JIG_ON = 1C
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
I/FactoryTestApp( 2643): [ModuleCommon$isRunningFtClient](2643) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2643): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2643) start DummyFtClient service for APO
,W/ContextImpl( 2643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2643): User mode
,I/FactoryTestApp( 2643): [ModuleCommon$disableFtClient](2643) ...
,D/FactoryTestApp( 2643): [DummyFtClient$onCreate](2643) Create DummyFtClient service
,I/FactoryTestApp( 2643): [XMLDataStorage$parsingXML](2643) FtClient => data parsing was completed.
,D/FactoryTestApp( 2643): [DummyFtClient$onReceive](2643) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
,D/FactoryTestApp( 2643): [Support$Values.getBoolean](2643) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2643): [DummyFtClient$onStartCommand](2643) ...
,I/WifiService( 1014): android.intent.action.BOOT_COMPLETED,
,D/UsbDeviceManager( 1014): boot completed,
,D/UsbDeviceManager( 1014): handleMessage -> MSG_BOOT_COMPLETED
D/UsbDeviceManager( 1014): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1014): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
D/UsbDeviceManager( 1014): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb,
,I/KeyguardEffectViewUtil( 1172): set resource id
,D/SettingsProvider( 1014): name = keyguard_default_wallpaper_res_id
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10054
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/KeyguardUpdateMonitor( 1172): handleBootCompleted()
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1172): handleBootCompleted()
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,D/SamsungIME( 1885): showDlgMsgBox : false true true
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/NfcService( 1428): call the applyRouting
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 2673): MountEmulatedStorage()
E/Zygote  ( 2673): v2
I/libpersona( 2673): KNOX_SDCARD checking this for 1000
I/libpersona( 2673): KNOX_SDCARD not a persona
,I/SELinux ( 2673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/RecoverySystem( 1014): !@RecoverySystem handleAftermath
,I/RecoverySystem( 1014): No recovery log file
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TimaKeyStoreProvider( 2673): TimaSignature is unavailable
,V/OtaStartupReceiver( 1444): onOtaspChanged: mOtaspMode=1
D/ActivityThread( 2673): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,E/Zygote  ( 2692): MountEmulatedStorage()
E/Zygote  ( 2692): v2
I/libpersona( 2692): KNOX_SDCARD checking this for 1001
I/libpersona( 2692): KNOX_SDCARD not a persona
,I/SELinux ( 2692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2692 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 2692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Reset_Reason( 1014): resetString = NPON,
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BootReceiver( 1014): Copying audit failures to DropBox
,I/BootReceiver( 1014): Checking for fsck errors
,D/TimaKeyStoreProvider( 2692): TimaSignature is unavailable
,D/ActivityThread( 2692): Added TimaKeyStore provider
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/File    ( 2673): fail readDirectory() errno=2
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 2692): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1014): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/FactoryTestApp( 2643): [ProtectedFactoryTestBroadcastReceiver$onReceive](2643) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2643): [ProtectedFactoryTestBroadcastReceiver$onReceive](2643) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2643): User mode
,D/Mms/NotificationReceiver( 2285): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED,
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/NotificationReceiver( 2285): handleBootCompleted()
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Mms/RcsOwnCapsManager( 2285): queue Uri = content://im/queue-messages?box=pending
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TP/ImProvider( 1444): im query match24
D/TP/ImProvider( 1444): URI_IM_QUEUED_MESSAGES
,D/TP/ImProvider( 1444): ftSesstionId must be a long.
D/TP/ImProvider( 1444): getQueuedImMessages
,D/TP/ImProvider( 1444): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/Mms/NotificationReceiver( 2285):  getPendingMessageIds: no pending messages.
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Mms/ActionsFactory( 2285): Call to GET_LAST_MESSAGES_SENT
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
D/SettingsProvider( 1014): name = db_smartlock_supported
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
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
D/CrashAnrDetect,or( 1014):          be11edf4  00000000  
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
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
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
,I/AccessibilityManagerService( 1014): setmDNIeNegative (false)
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
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
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
,W/CursorWrapperInner( 2285): Cursor finalized without prior close()
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
D/CrashAnrDetector( 1014): processName:com.test.thalitest
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
,W/Settings( 1281): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1014): name = block_emergency_message
,D/SettingsProvider( 1014): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/[LPC]   ( 1014): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2715): MountEmulatedStorage(),
E/Zygote  ( 2715): v2
I/libpersona( 2715): KNOX_SDCARD checking this for 1000
I/libpersona( 2715): KNOX_SDCARD not a persona,
I/ActivityManager( 1014): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2715 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 2715): TimaSignature is unavailable
,D/ActivityThread( 2715): Added TimaKeyStore provider
,W/ResourcesManager( 2715): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,E/SQLiteLog( 2715): (539) recovered 3 pages from /data/user/0/com.samsung.android.sm/databases/lowpowercontext-system-db-journal,
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,I/i       ( 1014): No model
,D/FactoryTest( 1014): Not factory mode
D/FactoryTest( 1014): Not factory mode. isFactoryMode() returend false
D/w       ( 1014): isUserBuild = true
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,D/SSRM:aZ ( 1014): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1014): Updating Threshold Value.. isSystemReady: true
,I/ActivityManager( 1014): Killing 1186:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,E/SmartFaceService( 1014): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1014): no icon
,E/SmartFaceService( 1014): mActiveServiceType: 0
E/SmartFaceService( 1014): mLightIntensityEnough: true mLux: 0.0
D/Stay/Rotation Worker( 1014): updateClientsDone. def. do nothing.
E/SmartFaceService( 1014): Service Type to Worker: 0
E/SmartFaceService( 1014): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1014): Last Smart Pause clients: 0 Current Smart Pause clients: 0
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1014): [SO] activate (ident=0xb7c06b60, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1014): [SO] changed settle time [0]
,D/SensorService( 1014): [SO] setDelay [200000000]
D/SensorService( 1014): [SO] activate (ident=0xb7c06b60, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,V/AlarmManagerEXT( 1014): mGmsLocationBundling: false
,D/SSRM:n  ( 1014): SIOP:: AP = 320
,I/ActivityManager( 1014): Killing 1387:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/RCPManagerService( 1014): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1014):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/RCPManagerService( 1014): BootReceiver.onReceive(): Starting RCP Proxy for user = null
E/RCPManagerService( 1014):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 26
,D/SensorService( 1014): [SO] activate (ident=0xb7c06b60, enabled=0)
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_1186/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10096/pid_1387/cgroup.procs: No such file or directory
D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1014): [SO] changed settle time [1]
,D/SensorService( 1014): [SO] setDelay [66000000]
D/SensorService( 1014): [SO] activate (ident=0xb7c06b60, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/EnterpriseDeviceManagerService( 1014): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1014): runAdminUpdate
,V/ApplicationPolicy( 1014): boot completed - refreshWidgetStatus
,V/ApplicationPolicy( 1014): refresh widget status for user 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.w,idgetapp.SPlannerAppWidget
,D/EnterpriseUtils( 1014): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService( 1014): nothing to selfUpdate
,W/PhoneRestrictionPolicy( 1014): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1014): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
I/KnoxMUMContainerPolicy( 1014): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1014):  >>>> deliveryBlockedMsgs
,D/WifiP2pService( 1014): P2pDisabledState{ what=143415 }
,D/ConnectivityService( 1014): Got NetworkFactory Messenger for WIFI
,D/WifiP2pService( 1014): DefaultState{ what=143415 }
E/WifiStateMachine( 1014): Blacklist file delete
,D/ConnectivityService( 1014): Got NetworkFactory Messenger for WIFI_P2P
W/PhoneRestrictionPolicy( 1014): cvList size 0
W/PhoneRestrictionPolicy( 1014):  >>>> deliveryBlockedMsgs
,D/WIFI_P2P( 1014): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,W/PhoneRestrictionPolicy( 1014): cvList size 0
D/Tethering( 1014): Boot complete.
,V/EnterpriseBillingEngine( 1014): ACTION_BOOT_COMPLETED
,V/EnterpriseBillingEngine( 1014): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1014): getCurrentActiveProfiles - start - 
V/EnterpriseBillingPolicyStorage( 1014): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1014): handleAllprofiles - end
,D/UsbHostNotification( 1014): boot completed
,D/UsbHostRestrictor( 1014): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1014): initSetUsbBlock STARTED
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,D/UsbHostRestrictor( 1014): SIM was never inserted
,D/UsbHostRestrictor( 1014): writableHostSysNode[false]
,D/UsbHostRestrictor( 1014): Can NOT Write Disable Sys Node to [ON]
,D/PersonaManagerService( 1014): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1014):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1014): onBootComplete
,D/UsbStorageNotification( 1014): boot completed
,D/WIFI    ( 1014): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1014): BOOT_COMPLETED native_init 
,I/KnoxKeyguardUpdateMonitor( 1014): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1014): onTrustChanged user:0, enable:false
,D/GpsLocationProvider( 1014): set_capabilities_callback: 55u
,D/KeyguardViewMediator( 1172): onTrustChanged( Showing = false , userId = 0 )
,I/libmdmdetect( 1014): ESOC framework not supported
,I/libmdmdetect( 1014): Found internal modem: modem
E/PerMgrLib( 1014): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1014): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1014): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1014): BOOT_COMPLETED native_cleanup 
,D/StorageNotification( 1172): boot completed
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/qmi_secgps_clnt( 1014): qmi_secgps_client_init()
,D/SensorService( 1014): [SO] currT = 32910249413, prevT = 32590077018, diff = 320172395, [0.057 0.172 10.094]
D/SensorService( 1014): [SO] 0.057 0.172 10.094
D/SensorService( 1014): [SO] 0.057 0.172 10.094
D/SensorService( 1014): [SO] [100 -> 255]
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/StatusBarManagerService( 1014): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/PhoneStatusBar( 1172): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1014): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,E/Zygote  ( 2748): MountEmulatedStorage(),
E/Zygote  ( 2748): v2
D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
I/libpersona( 2748): KNOX_SDCARD checking this for 10099
,I/libpersona( 2748): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2748 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2748): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2748): TimaSignature is unavailable
,D/ActivityThread( 2748): Added TimaKeyStore provider
,E/LocSvc_utils_cfg( 1014): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,E/ActivityThread( 2748): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2748): Failed to find provider info for flipboard.auth.internal
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,I/splitIntent( 1014): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1014): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,I/ActivityManager( 1014): Killing 1555:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,I/DrmEventReceiver( 1014): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1014): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1014): SECGPS: Set AGPS Mode : 7
,I/DrmEventReceiver( 1014): DrmEventReceiver : beginStartingService
I/System.out( 1014): start Service
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,D/ActivityManager( 1014): startService callerProcessName:android, calleePkgName: android
,D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,V/DownloadManager( 1223): onReceive intent + android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2766): MountEmulatedStorage()
,E/Zygote  ( 2766): v2
I/libpersona( 2766): KNOX_SDCARD checking this for 1000
I/libpersona( 2766): KNOX_SDCARD not a persona
,I/SELinux ( 2766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02,
I/ActivityManager( 1014): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/qmi_secgps_clnt( 1014): SECGPS: Set XTRA enable : 1
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1014): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
I/qmi_secgps_clnt( 1014): SECGPS: Set CERT TYPE : 15
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2766): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2766): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 2778): MountEmulatedStorage()
E/Zygote  ( 2778): v2
I/libpersona( 2778): KNOX_SDCARD checking this for 10152
I/libpersona( 2778): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2778 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 2778): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2778): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2778): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/WVMDrmPlugIn(  281): WVMDrmPlugin::onInitialize : 1277
D/WVMDrmPlugIn(  281): WVMDrmPlugin::onSetOnInfoListener : add 1277
,D/TimaKeyStoreProvider( 2766): TimaSignature is unavailable
,D/ActivityThread( 2766): Added TimaKeyStore provider
I/DrmEventService( 1014): action event :android.intent.action.BOOT_COMPLETED
,I/TimaServiceEventReceiver( 1014): TimaServiceEventReceiver : onReceive
,D/TimaKeyStoreProvider( 2778): TimaSignature is unavailable
,D/ActivityThread( 2778): Added TimaKeyStore provider
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1014): mCursor = null
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
I/ANDROID_DRM_FRWORKS_DrmManager(  281): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,D/MediaScannerReceiver( 1223): action: android.intent.action.BOOT_COMPLETED
,E/LocSvc_ApiV02( 1014): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ResourcesManager( 2766): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/CscReceiver( 1444): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/BluetoothBDAdrressReceiver( 2766): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,D/CscUpdateService( 1444): onStart,
E/CscUpdateService( 1444): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1444): set_CSC_version
,E/CscParser( 1444): update(): xml file exist
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 2778): (284) automatic index on shooting_modes(title_id),
,E/Zygote  ( 2801): MountEmulatedStorage()
,E/Zygote  ( 2801): v2
I/libpersona( 2801): KNOX_SDCARD checking this for 10003
,I/libpersona( 2801): KNOX_SDCARD not a persona
,I/SELinux ( 2801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2801 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
I/SELinux ( 2801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2811): MountEmulatedStorage()
,E/Zygote  ( 2811): v2
I/libpersona( 2811): KNOX_SDCARD checking this for 1000
I/libpersona( 2811): KNOX_SDCARD not a persona
,I/SELinux ( 2811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2811 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 1522:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,I/SELinux ( 2811): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
E/SELinux ( 2811): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2801): TimaSignature is unavailable
,D/ActivityThread( 2801): Added TimaKeyStore provider,
I/CscUtil ( 1444): isWifiOnly = false
I/System.out( 1444): HandDataNode = null
I/CscUpdateService( 1444): PATH_CSCNAME =CustomerDataSet.CSCName
I/CscUpdateService( 1444): This is normal boot : CSC not updated
,D/ActivityManager( 1014): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1444): update(): xml file exist
,D/TimaKeyStoreProvider( 2811): TimaSignature is unavailable
,I/CscUpdateService( 1444): same CSC Version
D/CscGPS  ( 1444): CSCGPS.updateParameters
D/CscGPS  ( 1444): supl host : null
D/ActivityThread( 2811): Added TimaKeyStore provider
D/CscGPS  ( 1444): SUPL Host is null or invalid
D/CscGPS  ( 1444): supl_ver : null
D/CscGPS  ( 1444): SUPL Ver is null or invalid
D/CscGPS  ( 1444): supl port : null
D/CscGPS  ( 1444): SUPL PORT is null or invalid
D/CscGPS  ( 1444): LPP : null
D/CscGPS  ( 1444): LPP is null or invalid
D/CscGPS  ( 1444): CSC don't have any AGPS value.
,D/CscUtil ( 1444): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,E/Zygote  ( 2835): MountEmulatedStorage(),
I/libpersona( 2835): KNOX_SDCARD checking this for 1101
E/Zygote  ( 2835): v2,
I/libpersona( 2835): KNOX_SDCARD not a persona
,I/SELinux ( 2835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2835 uid=1101 gids={41101, 9997} abi=armeabi-v7a
W/ResourcesManager( 1444): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MediaScannerService( 1223): !@start scanning volume internal: [/system/media, /oem/media]
I/SELinux ( 2835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/BluetoothBDTestService( 1444): onCreate()
,E/SELinux ( 2835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
E/BluetoothBDTestService( 1444): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1444): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1444): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_1555/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/ActivityManager( 1014): Killing 1787:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/art     (  309): Explicit concurrent mark sweep GC freed 8788(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 25.248ms
,D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
,D/TP/MmsProvider( 1444): Update uri=content://mms, match=0
D/TP/MmsProvider( 1444): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1444): need read changed broadcast:false
,D/TimaKeyStoreProvider( 2835): TimaSignature is unavailable
,I/Mms:transaction( 2285): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/ActivityThread( 2835): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2285): [start]    nonBlockingUpdateMessageIndicator() consume time = 3089.493593
I/Mms/ReservationManager( 2285): resetAfterConnected()
,D/TP/MmsSmsProvider( 1444): query,matched:7, calling pid = 2285
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.877ms
,W/ResourcesManager( 2811): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 1444): match 7:Elapsed time : 3.213 ms
,I/Mms/ReservationManager( 2285): getReservedSendMessageCount(): retMessageCount=0
,D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/Mms/MessagingNotification( 2285): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2285): isDefault true
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.714ms
,D/TP/MmsProvider( 1444): Query uri=content://mms, match=0, calling pid = 2285
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2835): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
,E/Zygote  ( 2853): MountEmulatedStorage()
I/libpersona( 2853): KNOX_SDCARD checking this for 10048
E/Zygote  ( 2853): v2
I/libpersona( 2853): KNOX_SDCARD not a persona
V/SmartcardService( 2835): main Received broadcast
I/SELinux ( 2853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
V/SmartcardService( 2835): Starting smartcard service after boot completed
I/SELinux ( 2853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2853): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2853 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_1522/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1014): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,W/libprocessgroup( 1014): failed to open /acct/uid_10138/pid_1787/cgroup.procs: No such file or directory
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,D/Mms/SmsReceiverService( 2285): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2285): isDefault true
,D/Mms/SmsReceiverService( 2285): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/Mms/SmsReceiverService( 2285): [start]    handleBootCompleted() consume time = 93.827916
,D/TimaKeyStoreProvider( 2853): TimaSignature is unavailable
,D/ActivityThread( 2853): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1444): query,matched:200, calling pid = 2285
,D/TP/MmsSmsProvider( 1444): match 200:Elapsed time : 2.601 ms
,I/KnoxUsageLogPro( 2811): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0,
,I/KnoxUsageLogPro( 2811): savePreference: key = previous_sys_time value = 1451921610025
,E/Zygote  ( 2872): MountEmulatedStorage(),
E/Zygote  ( 2872): v2
I/libpersona( 2872): KNOX_SDCARD checking this for 10157
I/libpersona( 2872): KNOX_SDCARD not a persona
,I/SELinux ( 2872): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2872 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,I/KnoxUsageLogPro( 2811): premStatus:2,
I/SELinux ( 2872): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/KnoxUsageLogPro( 2811): isEulaShown : false
I/KnoxUsageLogPro( 2811): KnoxUsageReceiver onReceive : not Processible, just return
,E/SELinux ( 2872): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1444): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1444): deleteConversation threadId: 9223372036854775806
,W/ResourcesManager( 2853): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2853): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2853): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
E/SQLiteLog( 1223): (283) recovered 589 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/TP/MmsSmsProvider( 1444): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1444): updateThread(), thread_id = 9223372036854775806
,V/TP/MmsSmsDatabaseHelper( 1444): sUpgradeVersion = 0, db.getVersion() = 81
,E/Zygote  ( 2887): MountEmulatedStorage()
E/Zygote  ( 2887): v2
,I/libpersona( 2887): KNOX_SDCARD checking this for 10085
I/libpersona( 2887): KNOX_SDCARD not a persona
,E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1444): (284) automatic index on im_threads(normal_thread_id)
,I/ActivityManager( 1014): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2887 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 1578:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/SELinux ( 2887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/SELinux ( 2887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1444): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1444): need read changed broadcast:false
,D/Mms/Conversation( 2285): deleteTempConversation(),deleted=0
I/KnoxUsageLogPro( 2811): savePreference: key = previous_elapsed_time value = 33535
,D/TimaKeyStoreProvider( 2872): TimaSignature is unavailable
D/ActivityThread( 2872): Added TimaKeyStore provider
,I/SecureStorage( 2801): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/SmsProvider( 1444): Update uri=content://sms/outbox, match=8
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1444): need read changed broadcast:false
,D/TP/SmsProvider( 1444): query,matched:0, calling pid = 2285
,D/TP/SmsProvider( 1444): match 0:Elapsed time : 3.279 ms
,W/ResourcesManager( 2872): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2907): MountEmulatedStorage()
,E/Zygote  ( 2907): v2
I/libpersona( 2907): KNOX_SDCARD checking this for 1000
I/libpersona( 2907): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 2887): TimaSignature is unavailable
I/SELinux ( 2907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityThread( 2887): Added TimaKeyStore provider
E/SELinux ( 2907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/SmsReceiverService( 2285): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2285): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2285): [SIM-1]sendFirstQueuedMessage()
,I/SecureStorage( 2801): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  400): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2801
I/SecureStorage(  400): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2801): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2801): [INFO]: SPID(0x00000000)Processing data
D/SettingsProvider( 1014): name = block_emergency_message
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10048
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
I/SecureStorage(  400): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2801
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SecureStorage(  400): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_1578/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2907): TimaSignature is unavailable
,D/ActivityThread( 2907): Added TimaKeyStore provider
,E/Zygote  ( 2922): MountEmulatedStorage()
E/Zygote  ( 2922): v2
I/libpersona( 2922): KNOX_SDCARD checking this for 10159
I/libpersona( 2922): KNOX_SDCARD not a persona
,I/SELinux ( 2922): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/MediaScanner( 1223): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2922 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2922): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 2096:com.vlingo.midas/u0a31 (adj 15): empty #31
E/SELinux ( 2922): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
D/TP/SmsProvider( 1444): query,matched:26, calling pid = 2285
,D/TP/SmsProvider( 1444): match 26:Elapsed time : 6.964 ms
,D/TP/SmsProvider( 1444): query,matched:51, calling pid = 2285
,D/TP/SmsProvider( 1444): match 51:Elapsed time : 1.231 ms
,D/TimaKeyStoreProvider( 2922): TimaSignature is unavailable
,D/ActivityThread( 2922): Added TimaKeyStore provider
,W/ResourcesManager( 2887): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2887): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2887): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Mms/SmsReceiver( 2285): unregisterForServiceStateChanges, already unregistered
W/ResourcesManager( 2887): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 2285): sDisableVibrateForCamera = false
W/ResourcesManager( 2887): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2285): isDefault true
W/ResourcesManager( 2887): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,I/WifiCredService( 1281): onCreate
E/USB_UICC(  297): Timeout! No signal received. Retry num = 27
,D/WifiTimerReceiver( 1281): action: android.intent.action.BOOT_COMPLETED
,D/WifiTimerReceiver( 1281): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1281): Action boot completed received
,D/TP/MmsProvider( 1444): Query uri=content://mms, match=0, calling pid = 2285
,D/NearbySettings( 1281): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 1281): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1281): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 1281): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1014): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,V/NearbySettings( 1281): MountReceiver.mPrefHandler - 7002
,D/TP/MmsSmsProvider( 1444): query,matched:200, calling pid = 2285
,D/TP/MmsSmsProvider( 1444): match 200:Elapsed time : 0.886 ms
,I/art     ( 1444): Explicit concurrent mark sweep GC freed 39050(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 1.073ms total 80.351ms
,D/TP/SmsProvider( 1444): query,matched:0, calling pid = 2285
,D/TP/SmsProvider( 1444): match 0:Elapsed time : 1.998 ms
,I/NearbySettings( 1281): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1281): MountReceiver.onReceive - Internal Path
,I/Intent to TravelDirActivity( 2922): inside TravelBroadcastReceiver
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/Mms/MessagingNotification( 2285): isBlockingModeEnabled() = false, Zen mode = 0
D/SettingsProvider( 1014): name = personal_mode_enabled
,V/MediaScanner( 1223): processDirectory :  /system/media
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2943): MountEmulatedStorage()
I/libpersona( 2943): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2943): v2
I/libpersona( 2943): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2943 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10031/pid_2096/cgroup.procs: No such file or directory
,I/SELinux ( 2943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Killing 1482:com.android.printspooler/u0a136 (adj 15): empty #31
,I/SELinux ( 2943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2943): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 2907): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1444): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1444): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1444): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 2955): MountEmulatedStorage()
,E/Zygote  ( 2955): v2
I/libpersona( 2955): KNOX_SDCARD checking this for 10072
I/libpersona( 2955): KNOX_SDCARD not a persona
,I/SELinux ( 2955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2955): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/MediaScanner( 1223):  prescan time: 305ms (DB items: 141)
V/MediaScanner( 1223):     scan time: 160ms (Caching mode: true), (makeEntry time: 39ms ~24%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=2955 uid=10072 gids={50072, 9997} abi=armeabi-v7a
V/MediaScanner( 1223): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 465ms
V/MediaScanner( 1223): checked files: 133  directories : 6  (I: 0, U: 0)
,D/MediaScanner( 1223): checkDefaultSounds
,D/MediaScanner( 1223): system alarm_alert  : Vwiurug_etwofi5wgg
D/TimaKeyStoreProvider( 2943): TimaSignature is unavailable
D/ActivityThread( 2943): Added TimaKeyStore provider
D/TP/SmsProvider( 1444): query,matched:51, calling pid = 2285
I/SmartcardBootCompleteReceiver( 1281): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1281): Received intent with action - android.intent.action.BOOT_COMPLETED
D/TP/SmsProvider( 1444): match 51:Elapsed time : 0.920 ms
,D/MediaScanner( 1223): OK. alarm_alert is already exist in setting DB.
,D/DSM     ( 2907): [Lines:107] Normal booted
,D/DSM     ( 2907): [Lines:114] Boot completed
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
D/MediaScanner( 1223): system notification_sound  : K_Oprkltf5wgg
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1223): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1223): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/TimaKeyStoreProvider( 2955): TimaSignature is unavailable
,D/ActivityThread( 2955): Added TimaKeyStore provider
,D/MediaScanner( 1223): OK. ringtone is already exist in setting DB.
,E/Zygote  ( 2973): MountEmulatedStorage(),
E/Zygote  ( 2973): v2
I/libpersona( 2973): KNOX_SDCARD checking this for 1000,
I/ActivityManager( 1014): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2973 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 2132:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
I/libpersona( 2973): KNOX_SDCARD not a persona
,I/SELinux ( 2973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2285): isBlockingModeEnabled() = false, Zen mode = 0
,I/SmartcardBootCompleteReceiver( 1281): Broadcast sent with current lockscreen type
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2988 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2196:com.google.android.apps.magazines/u0a113 (adj 15): empty #31,
,E/Zygote  ( 2988): MountEmulatedStorage()
E/Zygote  ( 2988): v2
I/libpersona( 2988): KNOX_SDCARD checking this for 10160
I/libpersona( 2988): KNOX_SDCARD not a persona
I/SELinux ( 2988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/TimaKeyStoreProvider( 2973): TimaSignature is unavailable
,D/ActivityThread( 2973): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2988): TimaSignature is unavailable
,D/ActivityThread( 2988): Added TimaKeyStore provider
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 34464(2MB) AllocSpace objects, 16(651KB) LOS objects, 33% free, 25MB/38MB, paused 8.184ms total 157.500ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10136/pid_1482/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10050/pid_2132/cgroup.procs: No such file or directory
,D/MediaScannerService( 1223): !@done scanning volume internal
,W/libprocessgroup( 1014): failed to open /acct/uid_10113/pid_2196/cgroup.procs: No such file or directory
,D/MediaScannerService( 1223): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,W/ResourcesManager( 2973): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 2988): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/BadgeProvider( 2955): onCreate
,D/BadgeProvider( 2955): DatabaseHelper
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/[SBeam] ( 1281): SBeamEnabler.initPreferenceForSbeam : 0
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/BadgeProvider( 2955): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/SettingSearch/SearchIntentReceiver( 1281): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1281): search setting db init!!
,W/ContextImpl( 1281): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/SettingSearch/SearchIntentReceiver( 1281): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3010): MountEmulatedStorage()
,E/Zygote  ( 3010): v2
I/libpersona( 3010): KNOX_SDCARD checking this for 1000
I/libpersona( 3010): KNOX_SDCARD not a persona
,I/SELinux ( 3010): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty,
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,I/SELinux ( 3010): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished,
I/ActivityManager( 1014): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3010 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3010): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/MediaScanner( 1223): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/ActivityThread( 2973): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat,
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
E/Zygote  ( 3022): MountEmulatedStorage()
E/Zygote  ( 3022): v2
I/libpersona( 3022): KNOX_SDCARD checking this for 10150,
I/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
I/libpersona( 3022): KNOX_SDCARD not a persona,
,I/ActivityManager( 1014): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3022 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,I/SELinux ( 3022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3022): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 2955): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2955): sendNotify, [notify] : null
,D/BadgeProvider( 2955): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2955): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2955): update, [UpdateCount] : 1,
D/Launcher.Model( 1467): reloadBadges entered.
D/SettingsProvider( 1014): name = next_alarm_formatted
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10085
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/Mms/MessagingNotification( 2285): setBadgeCount(), count=0
D/BadgeProvider( 2955): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 3010): TimaSignature is unavailable
,D/ActivityThread( 3010): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 2285): remove alarm
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,D/TimaKeyStoreProvider( 3022): TimaSignature is unavailable
,D/ActivityThread( 3022): Added TimaKeyStore provider
,D/[0]UMC:UMCContentProvider( 2988): @onCreate
,I/art     (  309): Explicit concurrent mark sweep GC freed 8728(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 54.135ms
,W/ResourcesManager( 3010): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 18.955ms
,D/Mms/MessagingNotification( 2285): updateAllHistoryAsRead()
,D/[0]UMC:Core( 2988): onCreate(): 
D/[0]UMC:Core( 2988): @isManagedProfileUser
D/[0]UMC:Core( 2988): userId: 0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.281ms total 24.263ms
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,D/[0]UMC:Core( 2988): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2988): userInfo.isManagedProfile() : false
,D/TP/SmsProvider( 1444): query,matched:0, calling pid = 2285
,D/TP/SmsProvider( 1444): match 0:Elapsed time : 1.147 ms
,I/ActivityManager( 1014): Killing 1623:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/Mms/MessagingNotification( 2285): [end]    nonBlockingUpdateMessageIndicator() consume time = 942.786511
,I/SecureStorage(  400): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 2973): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,V/MediaScanner( 1223): processDirectory :  /storage/emulated/0
,D/[0]UMC:DeviceInfo( 2988): USA==US==
,I/iu.UploadsManager( 2049): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(75ebcf7
I/LcdtestApp( 2973): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
D/MediaScanner( 1223): Skipping:
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/MediaScanner( 1223): processDirectory :  /storage/extSdCard
W/MediaScanner( 1223): Error opening directory, reason : Permission denied.
W/MediaScanner( 1223): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 1223):  prescan time: 202ms (DB items: 27)
,V/MediaScanner( 1223):     scan time: 20ms (Caching mode: true), (makeEntry time: 9ms ~45%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 8ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 230ms
V/MediaScanner( 1223): checked files: 10  directories : 17  (I: 0, U: 0)
,I/SecureStorage( 2801): [INFO]: SPID(0x00000001)Processing data has been completed
I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3044 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SecureStorage( 2801): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
,D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 1223): !@done scanning volume external
D/FactoryTestApp( 2643): [DummyFtClient$mBroadcastReceiver](2643) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2643): [DummyFtClient$sendBootCompletedAndFinish](2643) ...
D/FactoryTestApp( 2643): [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2643): [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
,E/Zygote  ( 3044): MountEmulatedStorage()
I/libpersona( 3044): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3044): v2
I/libpersona( 3044): KNOX_SDCARD not a persona
,I/SELinux ( 3044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$ResponseWriter](2643) Create IPCWriterToSecPhoneService
,I/SELinux ( 3044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$connectToSecPhoneService](2643)  
W/ContextImpl( 2643): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/ActivityManager( 1014): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,D/BadgeProvider( 2955): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2955): sendNotify, [notify] : null
D/BadgeProvider( 2955): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2955): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2955): update, [UpdateCount] : 1
,I/FOTA    ( 3010): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/Launcher.Model( 1467): reloadBadges entered.
,D/Mms/MessagingNotification( 2285): setBadgeCount(), count=0
,D/TimaKeyStoreProvider( 3044): TimaSignature is unavailable
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_1623/cgroup.procs: No such file or directory
,D/ActivityThread( 3044): Added TimaKeyStore provider
,I/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$onServiceConnected](2643) connected done
D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$write](2643) Send Response Message to SecPhone
D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$write](2643) Response ��
,D/Mms/MessagingNotification( 2285): remove alarm
,W/art     ( 2887): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 216.104ms
,D/AT_Distributor(  320): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/Mms/MessagingNotification( 2285): updateAllHistoryAsRead()
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,D/FactoryTestApp( 2643): [IPCWriterToSecPhoneService$handleMessage](2643) Send BOOTING COMPLETED done
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,D/TP/SmsProvider( 1444): query,matched:0, calling pid = 2285
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/TP/SmsProvider( 1444): match 0:Elapsed time : 5.130 ms
,I/iu.UploadsManager( 2049): End new media; added: 0, uploading: 0, time: 153 ms
,D/Mms/SmsReceiverService( 2285): [end]    handleBootCompleted() consume time = 205.395729
,I/ActivityManager( 1014): Killing 2267:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
,D/AT_Distributor(  320): SetAtdStatus(), 1_1_0
D/AT_Distributor(  320): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/BluetoothAdapter( 2382): disable()
,E/BluetoothManagerService( 1014): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1014): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1014): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1014): mCursor = null
,I/DIAGMON_AGENT( 3044): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/WifiService( 1014): setWifiEnabled: false pid=2382, uid=10177
,D/SettingsProvider( 1014): name = wifi_on
,I/jxcore-log( 2382): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 2382): 
,I/jxcore-log( 2382): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2382): 
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2267/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3010): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,D/USER_AGENT( 2988): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3010): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1014): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/[0]UMC:AdminManager( 2988): init - start
,D/OverheatReceiver( 1172): onReceive() getAction : android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/OverheatReceiver( 1172): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1172): VZW on -> change to Global UX [safe mode]
,I/DBG_DM  ( 3010): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,D/OverheatReceiver( 1172): isSafeMode = false
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3010): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 3010): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,D/BootupListener( 1444): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1014): name = internet_call_settings_visibility
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,D/PhoneUtilsCommon( 1444): isSupportVoLTE is false.
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3010): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/Telecom ( 1420): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1014): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,D/ActivityManager( 1014): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3010): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,E/Zygote  ( 3071): MountEmulatedStorage(),
I/libpersona( 3071): KNOX_SDCARD checking this for 10057,
E/Zygote  ( 3071): v2
I/libpersona( 3071): KNOX_SDCARD not a persona
I/SELinux ( 3071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3071): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3071 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
I/Telecom ( 1420): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl},
,D/[0]UMC:AdminManager( 2988): loadAdmins,
,I/DBG_DM  ( 3010): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 3010): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,D/ActivityManager( 1014): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3071): TimaSignature is unavailable
,D/ActivityThread( 3071): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,D/[0]UMC:AdminManager( 2988): init - end
,I/DBG_DM  ( 3010): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,D/GSLBManager( 2988): migrateStoredUrlFromOldPref
,I/ActivityManager( 1014): Killing 2304:com.sec.android.omc/1000 (adj 15): empty #31
,D/GSLBManager( 2988): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 2988): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2988): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2988): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2988): deactivateUMCAdmin : -1
,D/[0]UMC:UMCAdmin( 2988): isContainer : 0
,D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2988): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2988): isContainer : 0
,D/[0]UMC:UMCAdmin( 2988): deactivateUMCAdmin - UMC App Admin deactivated
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,D/ActivityManager( 1014): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2988): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,I/DBG_DM  ( 3010): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/[0]UMC:CoreReceiver( 2988): Intent : android.intent.action.BOOT_COMPLETED
,D/[0]UMC:CoreReceiver( 2988):  check PreETag 
,I/DIAGMON_AGENT( 3044): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/BluetoothHeadset( 2801): BTStateChangeCB is registed
,D/BluetoothHeadset( 2801): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/DIAGMON_AGENT( 3044): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2801): BluetoothHeadset service is binded
,D/AndroidRuntime( 3067): 
D/AndroidRuntime( 3067): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothA2dp( 2801): doBind(): CallingUid(myUserHandle) = 0
,D/AndroidRuntime( 3067): CheckJNI is OFF
D/ActivityManager( 1014): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/AndroidRuntime( 3067): readGMSProperty: start
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 3067): readGMSProperty: already setted!!
D/AndroidRuntime( 3067): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3067): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3067): readGMSProperty: end
D/AndroidRuntime( 3067): addProductProperty: start
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 2801): 932590557: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2801): 932590557: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2801): 932590557: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2801): 932590557: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2801): 932590557: getState() :  mService = null. Returning STATE_OFF
,I/DIAGMON_AGENT( 3044): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2304/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3010): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
I/DIAGMON_AGENT( 3044): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3044): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 3044): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/[0]UMC:CoreReceiver( 2988): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2988): Enter loadList
,D/[0]UMC:CoreReceiver( 2988): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2988): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2988): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2988): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2988): deactivateUMCAdmin : -1,
D/[0]UMC:UMCAdmin( 2988): isContainer : 0
V/audio_hw_primary(  282): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  282): audio_extn_get_parameters: returns 
V/msm8974_platform(  282): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  282): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  282): key: 'call_forwarding' value: ''
D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2988): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2988): isContainer : 0
V/InCall  ( 1949): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1949): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1949): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/[0]UMC:UMCAdmin( 2988): deactivateUMCAdmin - UMC App Admin deactivated
D/ScoverManager( 1949): serviceVersion : 16908288
D/[0]UMC:ByodSetupStarter( 2988): Container ID : 0
D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,D/InCall  ( 1949): InCallUtils - isCoverClosed false
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/Telecom ( 1420): ProximitySensorManager: Proximity wake lock already released
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data,
D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1949): InCallUtils - isCoverClosed false
I/InCall  ( 1949): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1949): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1949): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1949): CallSContextMotion - stopPutDownListening,
D/InCall  ( 1949): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,E/Zygote  ( 3101): MountEmulatedStorage(),
E/Zygote  ( 3101): v2
I/libpersona( 3101): KNOX_SDCARD checking this for 1000
,I/libpersona( 3101): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3101 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Killing 2334:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/SELinux ( 3101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1949): InCallUtils - isCoverClosed false
E/Tethering( 1014): No numeric data
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,E/SELinux ( 3101): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering( 1014): No numeric data
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,V/[0]UMC:Utils( 2988): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2988): shutdown
D/PhoneStatusBarView( 1172): setCallBackground:0
,D/TimaKeyStoreProvider( 3101): TimaSignature is unavailable
,D/ActivityThread( 3101): Added TimaKeyStore provider
I/DBG_DM  ( 3010): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/Zygote  ( 3116): MountEmulatedStorage()
,E/Zygote  ( 3116): v2
I/libpersona( 3116): KNOX_SDCARD checking this for 1000
I/libpersona( 3116): KNOX_SDCARD not a persona
,I/SELinux ( 3116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/[0]UMC:GuardService( 2988): @GuardService - stopService Result = true
,E/AffinityControl( 3067): AffinityControl: registerfunction enter
,W/ResourcesManager( 3101): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/art     ( 2988): System.exit called, status: 0
I/AndroidRuntime( 2988): VM exiting with result code 0, cleanup skipped.
,D/TimaKeyStoreProvider( 3116): TimaSignature is unavailable
,D/ActivityThread( 3116): Added TimaKeyStore provider
,D/AndroidRuntime( 3067): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1014): START PACKAGE DELETE: observer{779877147}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{3}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1014): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1014): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 1014): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1014): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1014): !@killApplicatoin: 10177, uninstall pkg
,I/ActivityManager( 1014): Force stopping com.example.hello appid=10177 user=-1: uninstall pkg
,I/ActivityManager( 1014): Killing 2382:com.example.hello/u0a177 (adj 0): stop com.example.hello cause uninstall pkg
,W/libprocessgroup( 1014): failed to open /acct/uid_10131/pid_2334/cgroup.procs: No such file or directory
,D/VideoCallManager( 1949): Instantiating VideoCallManager
,I/DBG_DM  ( 3010): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3010): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3010): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/WindowState( 1014): WIN DEATH: Window{350c7ed9 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1014): Focus left window: 2382
,W/PackageSettings( 1014): Skipping PackageSetting{26596115 com.test.thalitest/10175} due to missing metadata
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1014): Force removing ActivityRecord{26dd1990 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/FocusedStackFrame( 1014): Set to : 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1014): Focused application set to: xxxx
E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1949): took 2.422916ms for 0*0 texture 0
,D/[SBeam] ( 1281): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1281): SBeamEnabler.isSBeamSupported : EXIST
,I/GFX generate_partition_tables( 1949): took 5.385000ms for 0*0 texture 0
,D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,I/GFX raster( 1949): took 11.560000ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7848a88 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7860c98 counterpartCT=4 counterpartW=176 counterparth=144
,V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1949): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1949): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1949): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1949): Local Branch: 
I/Adreno-EGL( 1949): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1949): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1949):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Tethering( 1014): No numeric data
,E/Zygote  ( 3137): MountEmulatedStorage()
,E/Zygote  ( 3137): v2
I/libpersona( 3137): KNOX_SDCARD checking this for 10086
I/libpersona( 3137): KNOX_SDCARD not a persona
,I/GFX GPU raster( 1949): eglCreateImageKHR: EGL_SUCCESS
,I/SELinux ( 3137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
D/Launcher( 1467): onRestart, Launcher: 204594113
I/ActivityManager( 1014): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3137 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/glCompressedTexImage2D( 1949): took 0.246250ms for 320*61440 texture 37809
I/ActivityManager( 1014): Killing 2351:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,I/SELinux ( 3137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3137): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/draw setup( 1949): took 10.555938ms for 320*240 texture 37809
E/GFX GPU raster( 1949): drawn
,I/GFX GPU raster ASTC( 1949): took 38.640519ms for 320*240 texture 12
I/GFX raster( 1949): took 38.727759ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7860c98 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7862fd8 counterpartCT=4 counterpartW=320 counterparth=240
,E/Zygote  ( 3150): MountEmulatedStorage()
,E/Zygote  ( 3150): v2
I/libpersona( 3150): KNOX_SDCARD checking this for 10015
I/libpersona( 3150): KNOX_SDCARD not a persona
,I/SELinux ( 3150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1949): eglCreateImageKHR: EGL_SUCCESS
,I/ActivityManager( 1014): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3150 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager( 1014): Spurious death for ProcessRecord{232e54b8 2382:com.example.hello/u0a177}, curProc for 2382: null
,I/glCompressedTexImage2D( 1949): took 0.302396ms for 480*122880 texture 37813
I/draw setup( 1949): took 0.637968ms for 480*640 texture 37813
E/GFX GPU raster( 1949): drawn
,I/ActivityManager( 1014): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2988)(adj 0) has died(328,992)
,I/SELinux ( 3150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3150): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GFX GPU raster ASTC( 1949): took 6.884167ms for 480*640 texture 12
I/GFX raster( 1949): took 6.973385ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7862fd8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7a91468 counterpartCT=4 counterpartW=480 counterparth=640
,D/Launcher( 1467): onStart, Launcher: 204594113
D/Launcher.HomeView( 1467): onStart
D/Launcher( 1467): onResume, Launcher: 204594113
,D/SettingsProvider( 1014): name = kids_home_mode
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10007
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/Launcher.HomeView( 1467): onResume
,D/TimaKeyStoreProvider( 3137): TimaSignature is unavailable
,I/ActivityManager( 1014): Force stopping com.example.hello appid=10177 user=0: pkg removed
,D/ActivityThread( 3137): Added TimaKeyStore provider
D/Launcher( 1467): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/Tethering( 1014): No numeric data
D/LocationManagerService( 1014): getProviders()=[passive]
,D/TimaKeyStoreProvider( 3150): TimaSignature is unavailable
,D/ActivityThread( 3150): Added TimaKeyStore provider
,E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1949): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1949): took 0.336146ms for 440*116864 texture 37809
I/draw setup( 1949): took 0.825677ms for 440*330 texture 37809
E/GFX GPU raster( 1949): drawn
,I/GFX GPU raster ASTC( 1949): took 4.387916ms for 440*330 texture 12
I/GFX raster( 1949): took 4.491718ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7a91468 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7aa5858 counterpartCT=4 counterpartW=440 counterparth=330
,E/JavaBinder( 1014): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
,E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1949): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1949): took 0.414271ms for 480*163840 texture 37811
I/draw setup( 1949): took 0.772761ms for 480*640 texture 37811
E/GFX GPU raster( 1949): drawn
,I/GFX GPU raster ASTC( 1949): took 6.795313ms for 480*640 texture 12
I/GFX raster( 1949): took 6.877656ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7a95668 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7ad5040 counterpartCT=4 counterpartW=480 counterparth=640
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:2, health:2, present:true, voltage: 4312, temperature: 234, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,D/MenuAppsGridFragment( 1467): onResume
,D/ActivityManager( 1014): handle home activity for 0
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2351/cgroup.procs: No such file or directory
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/InputDispatcher( 1014): Focus entered window: 1467
,E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/GFX construct_block_size_descriptor_2d second part( 1949): took 2.644844ms for 0*0 texture 0
,D/SRIB_DCS( 1467): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,I/GFX generate_partition_tables( 1949): took 8.015156ms for 0*0 texture 0
,I/GFX raster( 1949): took 12.915209ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7aa5390 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7ad5050 counterpartCT=4 counterpartW=176 counterparth=144
,D/Launcher( 1467): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1304): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1304): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1304): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1304): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,E/        ( 1949): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1949): took 2.425521ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1949): took 6.562916ms for 0*0 texture 0
,I/GFX raster( 1949): took 11.650260ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1949): Bitmap=0xb7aa5ce8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7a91170 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1949): registerListener
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,E/SamsungIME( 1885): mOCRHelper is null
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1444): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 1804): Ignoring removeGeofence because network location is disabled.
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1014): registerListenerCallback : binder = android.os.BinderProxy@1cb988da, pid : 1949, uid : 1001, type : 1
,W/InputMethodManagerService( 1014): Got RemoteException sending setActive(false) notification to pid 2382 uid 10177
,D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
,W/NotificationAccessSettings( 1281): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
D/SettingsProvider( 1014): name = aw_daemon_service_key_version_check
W/TextServicesManagerService( 1014): no available spell checker services found
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10162
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,V/EmergencyMode( 1405): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1405): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1172): Cable  true --> true mBootCompleted : true
,D/PowerUI ( 1172): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/SamsungIME( 1885): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/DBG_POLICYDM( 3116): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3116): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3116): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3116): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 3190): MountEmulatedStorage(),
,I/Timeline( 1467): Timeline: Activity_idle id: android.os.BinderProxy@1563532c time:35816,
I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3190 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/daemonapp( 1304): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/RegisteredComponentCache( 1428): Collect Tech packages for Knox,
E/Zygote  ( 3190): v2
I/libpersona( 3190): KNOX_SDCARD checking this for 10009
I/libpersona( 3190): KNOX_SDCARD not a persona
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,I/SELinux ( 3190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1304): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/SELinux ( 3190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3190): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3116): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3116): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,D/PersonaManager( 1428): isKioskContainerExistOnDevice
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3116): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/SearchServiceFactory( 3071): refreshing internal icing corpora
,D/TimaKeyStoreProvider( 3190): TimaSignature is unavailable
,D/ActivityThread( 3190): Added TimaKeyStore provider
,I/SearchServiceFactory( 3071): checking for language pack updates
,I/SecKeyguardClockSingleView( 1172): Ignore. Because it is same clock text
,I/ActivityManager( 1014): Displayed Component not be shown by security: +489ms
,D/InCall  ( 1949): InCallPresenter -  - Finished InCallPresenter.setUp
,E/daemonapp( 1304): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1014): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1014): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1451921612409
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1451943180000
E/UpdateRequestReceiver( 3137): ignoring update request
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1304): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1304): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1451943180000
,D/daemonapp( 1304): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/daemonapp( 1304): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1451943180000
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_POLICYDM( 3116): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 29112(1969KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/39MB, paused 4.816ms total 432.497ms
,I/art     ( 1014): WaitForGcToComplete blocked for 53.593ms for cause Explicit
,I/DBG_POLICYDM( 3116): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/RCPManagerService( 1014): PackageReceiver onReceive()
,I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,E/DBG_POLICYDM( 3116): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/PersonaManager( 1428): isKioskContainerExistOnDevice
I/OTPFW   ( 1014): PackageRemovalReceiver::onReceive Enter
,D/RegisteredServicesCache( 1428): empty dynamic service
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/OTPFW   ( 1014): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1014): DBIntegrity::getInstance - New instance created
,D/ScoverManager( 1281): serviceVersion : 16908288
,D/OTPFW   ( 1014): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10177 container id = 0
,I/OTPFW   ( 1014): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1014): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10177
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/TaskPersister( 1014): removeObsoleteFile: deleting file=2_task.xml
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1014): [SO] activate (ident=0xb7c06b60, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
,D/PanelView( 1172): There is/are notification(s) 
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1014): [SO] changed settle time [0]
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1014): [SO] setDelay [200000000]
D/SensorService( 1014): [SO] activate (ident=0xb7cc1fb8, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10177
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,V/AlarmManagerEXT( 1014): com.example.hello(10177) is removed.
,D/PackageManager( 1014): delete codoeFile: 
,I/AASA_removePackage( 1014): UID=10177 Target=com.example.hello,
D/AASAuninstall( 1014): userId = 0, info.removedAppID = -1, info.uid = 10177, packageName = com.example.hello
,D/PackageManager( 1014): result of delete: 1{779877147}
,D/AndroidRuntime( 3067): Shutting down VM
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 9544(513KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/39MB, paused 3.413ms total 206.206ms
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,D/CustomFrequencyManagerService( 1014): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1014  tag : ACTIVITY_RESUME_BOOSTER@11
,E/UpdateRequestReceiver( 3137): ignoring update request
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{2ff45885 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:36293
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1]
,I/ActivityManager( 1014): Killing 2256:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/comdaemonstockapp( 1304): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1304): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/UpdateRequestReceiver( 3137): ignoring update request
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 3221): MountEmulatedStorage()
I/libpersona( 3221): KNOX_SDCARD checking this for 10166
E/Zygote  ( 3221): v2
I/libpersona( 3221): KNOX_SDCARD not a persona
,I/SELinux ( 3221): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3221): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
E/SELinux ( 3221): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3221 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3010): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[update_gservices_config]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1014): Killing 2423:com.wsomacp/u0a25 (adj 15): empty #31
,V/AlarmManager( 1014): waitForAlarm result :8
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/art     ( 3067): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/TimaKeyStoreProvider( 3221): TimaSignature is unavailable
D/ActivityThread( 3221): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[update_icing_corpora]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[update_language_packs]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,E/TRThreadPoolExecutor( 3071): Queue length for executor Background Blocking with unbounded threads is now 4. Perhaps some tasks are too long, or the pool is too small.
,W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[refresh_doodle]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[fetch_opt_in_statuses]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/TRThreadPoolExecutor( 3071): Task "NotifyOnDoneFutureTask[refresh_auth_tokens]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3249): MountEmulatedStorage()
E/Zygote  ( 3249): v2
I/libpersona( 3249): KNOX_SDCARD checking this for 10003
I/libpersona( 3249): KNOX_SDCARD not a persona
,E/UpdateRequestReceiver( 3137): ignoring update request
,I/SELinux ( 3249): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3249 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 3249): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3249): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/UsbSettingsManager( 1014): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1014): onPackageRemoved : com.example.hello
,D/TimaKeyStoreProvider( 3249): TimaSignature is unavailable
,D/SensorService( 1014): [SO] currT = 36501966391, prevT = 36070087485, diff = 431878906, [0.057 0.192 10.132]
D/SensorService( 1014): [SO] 0.057 0.192 10.132
D/SensorService( 1014): [SO] [100 -> 255]
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2256/cgroup.procs: No such file or directory
,D/ActivityThread( 3249): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_2423/cgroup.procs: No such file or directory
,I/SearchServiceFactory( 3071): refreshing search history.
,I/GservicesUpdateTask( 3071): Updating Gservices keys
,E/UpdateRequestReceiver( 3137): ignoring update request
,I/UpdateIcingCorporaServi( 3071): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,E/Search.SharedPreferencesProto( 3071): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/UpdateRequestReceiver( 3137): ignoring update request
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1281): isSmartCardAuthenticationAvailable: false,
E/Zygote  ( 3274): MountEmulatedStorage()
E/Zygote  ( 3274): v2
I/libpersona( 3274): KNOX_SDCARD checking this for 10092
I/libpersona( 3274): KNOX_SDCARD not a persona
,I/SELinux ( 3274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3274 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2475:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/SELinux ( 3274): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/Choreographer( 1467): Skipped 46 frames!  The application may be doing too much work on its main thread.
,D/WallpaperManager( 1467): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1467): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/Settings_Utils( 1281): isSupportVNFestival SM-A500FU XEO

```
