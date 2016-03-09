#### Test 61703351436c7c0_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/USB_UICC(  296): Timeout! No signal received. Retry num = 20
--------- beginning of system
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2191): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2191): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2191): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2191): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
I/WebViewFactory( 2191): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/LibraryLoader( 2191): Time to load native libraries: 10 ms (timestamps 7193-7203)
I/LibraryLoader( 2191): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2191): Binding Chromium to main looper Looper (main, tid 1) {cbf476b}
I/LibraryLoader( 2191): Expected native library version number "",actual native library version number ""
I/chromium( 2191): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2191): Initializing chromium process, singleProcess=true
W/art     ( 2191): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2191): ApplicationContext is null in ApplicationStatus
W/chromium( 2191): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 2191): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2191): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 2191): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
I/Adreno-EGL( 2191): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2191): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2191): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2191): Local Branch: 
I/Adreno-EGL( 2191): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2191): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2191):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/AudioManagerAndroid( 2191): Requires BLUETOOTH permission
I/NSApplication( 2191): Starting up...
D/SettingsProvider( 1016): name = vibrate_in_silent
W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ResourcesManager( 1449): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/CscReceiver( 1449): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1449): Recieve Sim State Changed : ABSENT
I/splitIntent( 1016): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1016): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/BroadcastQueue( 1016): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1449, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2252): MountEmulatedStorage()
E/Zygote  ( 2252): v2
I/libpersona( 2252): KNOX_SDCARD checking this for 1000
I/libpersona( 2252): KNOX_SDCARD not a persona
I/WifiApBroadcastReceiver( 1282): onReceive: action android.intent.action.SIM_STATE_CHANGED
I/SELinux ( 2252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2252 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
I/SELinux ( 2252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2260): MountEmulatedStorage()
E/Zygote  ( 2260): v2
I/libpersona( 2260): KNOX_SDCARD checking this for 1000
I/libpersona( 2260): KNOX_SDCARD not a persona
I/SELinux ( 2260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/SELinux ( 2260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
D/BootupListener( 1449): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider( 1016): name = internet_call_settings_visibility
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1001
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneUtilsCommon( 1449): isSupportVoLTE is false.
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 2252): TimaSignature is unavailable
D/ActivityThread( 2252): Added TimaKeyStore provider
E/Zygote  ( 2279): MountEmulatedStorage()
E/Zygote  ( 2279): v2
I/libpersona( 2279): KNOX_SDCARD checking this for 10046
I/SELinux ( 2279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2279): KNOX_SDCARD not a persona
I/SELinux ( 2279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 2260): TimaSignature is unavailable
E/SELinux ( 2279): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityThread( 2260): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2279 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TimaKeyStoreProvider( 2279): TimaSignature is unavailable
D/ActivityThread( 2279): Added TimaKeyStore provider
D/StatusChecker( 2252): onReceive : android.intent.action.SIM_STATE_CHANGED
W/ResourcesManager( 2279): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2279): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2279): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2279): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2279): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/StatusChecker( 2252): onReceive : net.mt.init : 
D/StatusChecker( 2252): onReceive : preference initializing
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2302): MountEmulatedStorage()
E/Zygote  ( 2302): v2
I/libpersona( 2302): KNOX_SDCARD checking this for 1000
I/libpersona( 2302): KNOX_SDCARD not a persona
I/SELinux ( 2302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2302 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2302): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2315): MountEmulatedStorage()
I/libpersona( 2315): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2315): v2
I/libpersona( 2315): KNOX_SDCARD not a persona
I/SELinux ( 2315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/TimaKeyStoreProvider( 2302): TimaSignature is unavailable
D/ActivityThread( 2302): Added TimaKeyStore provider
I/ActivityManager( 1016): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2315): TimaSignature is unavailable
D/ActivityThread( 2315): Added TimaKeyStore provider
I/Omc:Receiver( 2302): onReceive : android.intent.action.SIM_STATE_CHANGED
E/USB_UICC(  296): Timeout! No signal received. Retry num = 21
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2332): MountEmulatedStorage()
E/Zygote  ( 2332): v2
I/libpersona( 2332): KNOX_SDCARD checking this for 1000
I/SELinux ( 2332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2332): KNOX_SDCARD not a persona
I/SELinux ( 2332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2332 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/AndroidRuntime( 2283): 
D/AndroidRuntime( 2283): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/TimaKeyStoreProvider( 2332): TimaSignature is unavailable
D/ActivityThread( 2332): Added TimaKeyStore provider
D/AndroidRuntime( 2283): CheckJNI is OFF
D/AndroidRuntime( 2283): readGMSProperty: start
D/AndroidRuntime( 2283): readGMSProperty: already setted!!
D/AndroidRuntime( 2283): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2283): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2283): readGMSProperty: end
D/AndroidRuntime( 2283): addProductProperty: start
I/art     (  306): Explicit concurrent mark sweep GC freed 8761(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 28.911ms
D/Mms/MmsApp( 2279): [start]    onCreate() consume time = 0.0
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.225ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 678us total 17.370ms
I/Omc:OmcData( 2302): omc.xml not exist
I/Omc:Receiver( 2302): OM Customize disabled
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2354): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2354 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 2354): v2
I/libpersona( 2354): KNOX_SDCARD checking this for 10131
I/libpersona( 2354): KNOX_SDCARD not a persona
I/SELinux ( 2354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2354): TimaSignature is unavailable
D/ActivityThread( 2354): Added TimaKeyStore provider
W/ResourcesManager( 2354): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2354): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2354): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2354): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/AffinityControl( 2283): AffinityControl: registerfunction enter
W/art     ( 2279): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 107.744ms
D/AndroidRuntime( 2283): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/Launcher.HomeView( 1469): onPause
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1469
D/Launcher( 1469): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 2283): Shutting down VM
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
E/Zygote  ( 2372): MountEmulatedStorage()
E/Zygote  ( 2372): v2
I/libpersona( 2372): KNOX_SDCARD checking this for 10174
I/libpersona( 2372): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2372 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2372): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2372): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2372): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1469): updateVisibility : ActivityRecord{18abb79d token=android.os.BinderProxy@1539519 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/art     ( 2279): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 108.541ms
D/TimaKeyStoreProvider( 2372): TimaSignature is unavailable
D/ActivityThread( 2372): Added TimaKeyStore provider
D/Mms/ArtClassLoader( 2279): init before art
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1469): onStop
V/ActivityThread( 1469): updateVisibility : ActivityRecord{18abb79d token=android.os.BinderProxy@1539519 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Mms/TelephonyPermission( 2279): start operation mode monitor
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
W/ResourcesManager( 2279): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/Mms/TelephonyPermission( 2279): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 2279): isDefault true
D/Mms/MmsApp( 2279): onCreate() com.android.mms
D/Launcher( 1469): onTrimMemory. Level: 20
I/WebViewFactory( 2372): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
W/art     ( 2283): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/LibraryLoader( 2372): Time to load native libraries: 2 ms (timestamps 8299-8301)
I/LibraryLoader( 2372): Expected native library version number "",actual native library version number ""
,D/SBrowserFeatureFlag( 2354): initialized in static block : loadCscFeatureValue() succeed! 
,V/WebViewChromiumFactoryProvider( 2372): Binding Chromium to main looper Looper (main, tid 1) {13a59533}
,I/LibraryLoader( 2372): Expected native library version number "",actual native library version number ""
,I/chromium( 2372): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/Mms/MmsApp( 2279): [start]    initCountryIso consume time = 519.685364
,D/ManifestProvider( 2354): onCreate()
,I/BrowserStartupController( 2372): Initializing chromium process, singleProcess=true
,W/art     ( 2372): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2372): ApplicationContext is null in ApplicationStatus
,D/CountryDetector( 1016): The first listener is added
,W/chromium( 2372): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,D/Mms/MmsApp( 2279): [end]    initCountryIso consume time = 23.853021
D/Mms/MmsConfig( 2279): [start]    MmsConfig.init() consume time = 0.119948
,W/chromium( 2372): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2372): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2372): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 2372): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2372): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2372): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2372): Local Branch: 
I/Adreno-EGL( 2372): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2372): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2372):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/Mms/MmsConfig( 2279): before partial update
,E/OperatorBookmarksSIMReceiver( 2354): onReceive runs..android.intent.action.SIM_STATE_CHANGED
,D/Mms/MmsConfig( 2279): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 2279): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 2279): isAuth is false
,D/Mms/MmsConfig( 2279): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1449): query,matched:2117, calling pid = 2279
,D/TP/MmsSmsProvider( 1449): match 2117:Elapsed time : 7.435 ms
,D/BluetoothAdapter( 2372): 875068444: getState() :  mService = null. Returning STATE_OFF
,D/EasySignUpManager_1.0.1( 2279): isAuth is false
D/EasySignUpManager_1.0.1( 2279): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 2279): mps_code.dat does not exist
,E/CscParser( 2279): customer_path =/system/csc/customer.xml
E/CscParser( 2279): fileName + /system/csc/customer.xml
,E/CscParser( 2279): mps_code.dat does not exist
E/CscParser( 2279): customer_path =/system/csc/customer.xml
E/CscParser( 2279): fileName + /system/csc/customer.xml
,D/CscParser( 2279): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 2279):  enable multiwindow = true
E/Mms/MessageUtils( 2279): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2279): updateCountryIso : update country iso info 
D/Mms/MmsConfig( 2279): [end]    init() consume time = 134.347552
W/chromium( 2372): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
D/Mms/Contact( 2279): [start]    init() consume time = 13.526302
,D/TP/MmsSmsProvider( 1449): query,matched:13, calling pid = 2279
,D/TP/MmsSmsProvider( 1449): match 13:Elapsed time : 3.337 ms
,D/Mms/Contact( 2279): [end]    init consume time = 22.522969
,D/Mms/DraftCache( 2279): [start]    rebuildCache consume time = 5.147031
,D/TP/MmsSmsProvider( 1449): query,matched:12, calling pid = 2279
D/TP/MmsSmsProvider( 1449): match 12:Elapsed time : 1.781 ms
,D/Mms/DraftCache( 2279): [end]    rebuildCache consume time = 17.337708
,D/Mms/MethodReflector( 2279): getSubId is called
,D/Mms/TelephonyUtils( 2279): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 2279): getTelephonyProperty is called
,D/Mms/DownloadManager( 2279): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2279): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 2279): auto download without roaming -> true
D/Mms/DownloadManager( 2279): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 2279): getSubId is called
,D/Mms/MethodReflector( 2279): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 2279): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2279): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 2279): getTelephonyProperty is called
D/Mms/DownloadManager( 2279): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2279): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2279): auto download without roaming -> true
D/Mms/DownloadManager( 2279): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2279): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2279): mAutoDownload ------> true
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
,W/art     ( 2372): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2372): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2372): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 2372): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2372): CordovaWebView is running on device made by: samsung
,D/Mms/ArtClassLoader( 2279): init [DONE] art
,W/art     ( 2372): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2372): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2372): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/PhoneWindow( 2372): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2372): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 2372
E/SMD     (  288): DCD OFF
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 2372): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2372): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2372): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 2372): Enabling debug mode 0
,D/ComposerPerformance( 2279): 1457533270389 ms / [DONE] Composer constructor
,D/Mms/Conversation( 2279): [start]    init() consume time = 174.988854
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 22
,D/TP/MmsSmsDatabaseHelper( 1449): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 1449): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1449): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1449): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
D/TP/MmsSmsDatabaseHelper( 1449): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
,D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,E/CII     ( 2279): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 2279): ReservationManager()
,I/Mms/ReservationManager( 2279): resetAfterConnected()
,D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 2279
,D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 2.996 ms
,I/Mms/ReservationManager( 2279): getReservedSendMessageCount(): retMessageCount=0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/Mms/MmsApp( 2279): [end]    onCreate() consume time = 40.289896
D/Mms/SmsReceiver( 2279): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1180): There is/are notification(s) 
,D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/Timeline( 2372): Timeline: Activity_idle id: android.os.BinderProxy@fe9999e time:28803
,D/Mms/DownloadManager( 2279): Service state changed: Bundle[mParcelledData.dataSize=744]
,I/ActivityManager( 1016): Displayed Component not be shown by security: +750ms
V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775807
,W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{339ac469 u0 com.example.hello/.MainActivity t10} time:28811
I/splitIntent( 1016): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
,V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/DownloadManager( 2279): roaming ------> false, mSimSlot = 0
,D/BootupListener( 1449): intent.getAction() = android.intent.action.SERVICE_STATE
D/Mms/MethodReflector( 2279): getSubId is called
D/Mms/TelephonyUtils( 2279): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
,D/Mms/MethodReflector( 2279): getTelephonyProperty is called
D/Mms/DownloadManager( 2279): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2279): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2279): auto download without roaming -> true
D/Mms/DownloadManager( 2279): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/SettingsProvider( 1016): name = internet_call_settings_visibility
D/Mms/Conversation( 2279): [end]    init consume time = 35.134583
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 1001
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/Mms/DownloadManager( 2279): mAutoDownload ------> true
D/PhoneUtilsCommon( 1449): isSupportVoLTE is false.
I/SamsungIME( 1806): getCurrentCandidateView
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
,D/StatusChecker( 2252): onReceive : android.intent.action.SERVICE_STATE
,I/StatusChecker( 2252): onReceive : net.mt.init : DONE
,D/StatusChecker( 2252): Service state changed : 3 mSub-1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 2279): [start]    init() consume time = 31.12349
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 2279): [end]    init consume time = 8.055313
D/Mms/SmsReceiverService( 2279): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/SpamFilter( 2279): [start]    SpamFilter fill() begin consume time = 9.096718
D/Mms/Synchronizer( 2279): [start]    doSync consume time = 0.028229
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1449): query,matched:0, calling pid = 2279
,V/TP/MmsSmsProvider( 1449): getSimpleConversations entered.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1449): match 0:Elapsed time : 2.406 ms
,D/Mms/TelephonyPermission( 2279): isDefault true
D/Mms/SmsReceiverService( 2279): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
,D/Mms/SmsReceiverService( 2279): handleSIMStatus()
D/Mms/SmsReceiverService( 2279): handleSIMStatus(): SIM_STATUS = ABSENT
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1449): query,matched:400, calling pid = 2279
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/TP/MmsSmsProvider( 1449): update, matched:300, calling pid = 2279
V/TP/MmsSmsProvider( 1449): syncDBData start
,V/TP/MmsSmsProvider( 1449): syncDBData sms end
,V/TP/MmsSmsProvider( 1449): syncDBData mms end
,V/TP/MmsSmsProvider( 1449): syncDBData end
,D/Mms/Synchronizer( 2279): [end]    doSync consume time = 49.825677,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/SpamFilter( 2279): [end]    SpamFilter fill() finished consume time = 9.204323
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SamsungIME( 1806): Dismiss ExpandCandiate
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/BindingManager( 2372): Cannot call determinedVisibility() - never saw a connection for the pid: 2372
,I/chromium( 2372): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 2279): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/SmsProvider( 1449): query,matched:26, calling pid = 2279
,D/TP/SmsProvider( 1449): match 26:Elapsed time : 1.243 ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2434): MountEmulatedStorage()
E/Zygote  ( 2434): v2
I/libpersona( 2434): KNOX_SDCARD checking this for 10020
I/libpersona( 2434): KNOX_SDCARD not a persona
I/SELinux ( 2434): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2434 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 2434): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2434): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/TP/MmsSmsProvider( 1449): query,matched:6, calling pid = 2279
D/TP/MmsSmsProvider( 1449): match 6:Elapsed time : 2.314 ms
,D/JsMessageQueue( 2372): Set native->JS mode to OnlineEventsBridgeMode
,D/TimaKeyStoreProvider( 2434): TimaSignature is unavailable
D/ActivityThread( 2434): Added TimaKeyStore provider
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/AndroidProtocolHandler( 2372): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2434): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
E/Zygote  ( 2449): MountEmulatedStorage()
I/libpersona( 2449): KNOX_SDCARD checking this for 10025
E/Zygote  ( 2449): v2
I/libpersona( 2449): KNOX_SDCARD not a persona
I/SELinux ( 2449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 2434): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 2434): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SELinux ( 2449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2449 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,E/SELinux ( 2449): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2449): TimaSignature is unavailable
,D/ActivityThread( 2449): Added TimaKeyStore provider
,W/ResourcesManager( 2449): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/SamsungIME( 1806): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 2372): JniHelper::setJavaVM(0xb8787450), pthread_self() = -1194529208
,W/jxcore-log( 2372): Initializing JXcore engine
W/jxcore-log( 2372): JXcore engine is ready
,I/SamsungIME( 1806): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1806): KeybaordView init() : load resources
,I/OMACP   ( 2449): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 2279): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,E/audit   ( 1917): type=1400 msg=audit(1457533271.031:203): avc:  denied  { ioctl } for  pid=2464 comm="Thread-255" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1917):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1917): type=1300 msg=audit(1457533271.031:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=5 a3=9d46f8f8 items=0 ppid=306 ppcomm=main pid=2464 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-255" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1917): type=1320 msg=audit(1457533271.031:203): 
,W/jxcore-log( 2372): Starting JXcore engine
,I/SamsungIME( 1806): getCurrentKeyboard
I/SamsungIME( 1806): getTextKeyboard
I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 2449): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/EasySignUpManager_1.15.0305( 2434): serviceId : 0, features : -1
,I/splitIntent( 1016): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
I/splitIntent( 1016): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SamsungIME( 1806): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/Zygote  ( 2469): MountEmulatedStorage(),
E/Zygote  ( 2469): v2
,I/libpersona( 2469): KNOX_SDCARD checking this for 10044
I/libpersona( 2469): KNOX_SDCARD not a persona
,I/SELinux ( 2469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2469 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/SELinux ( 2469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
E/SELinux ( 2469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2( 1016): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1016): mCursor = null
D/SecContentProvider2( 1016): isCopyContactToSimAllowed = true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2469): TimaSignature is unavailable,
,W/jxcore-log( 2372): Platform android
W/jxcore-log( 2372): 
W/jxcore-log( 2372): Process ARCH arm
W/jxcore-log( 2372): 
D/ActivityThread( 2469): Added TimaKeyStore provider
,E/Zygote  ( 2484): MountEmulatedStorage()
,E/Zygote  ( 2484): v2
I/libpersona( 2484): KNOX_SDCARD checking this for 10088
I/SELinux ( 2484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 2484): KNOX_SDCARD not a persona
,I/SELinux ( 2484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2484 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,E/SELinux ( 2484): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2497): MountEmulatedStorage(),
E/Zygote  ( 2497): v2
I/libpersona( 2497): KNOX_SDCARD checking this for 10142
I/libpersona( 2497): KNOX_SDCARD not a persona,
I/jxcore-log( 2372): JXcore Cordova bridge is ready!
I/jxcore-log( 2372): 
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2497 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
W/jxcore-log( 2372): JXcore engine is started
,I/SELinux ( 2497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2484): TimaSignature is unavailable
,D/ActivityThread( 2484): Added TimaKeyStore provider
,E/jxcore  ( 2372): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2372): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,W/ResourcesManager( 2469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2497): TimaSignature is unavailable,
,D/ActivityThread( 2497): Added TimaKeyStore provider
D/PhoneWindow( 2372): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 2372): *FMB* installDecor flags : 8388610,
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 37544(2MB) AllocSpace objects, 3(162KB) LOS objects, 33% free, 24MB/37MB, paused 1.943ms total 135.152ms
,D/InputDispatcher( 1016): Focus left window: 2372
D/InputDispatcher( 1016): Focus entered window: 2372
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/PhoneWindow( 2372): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/PhoneWindow( 2372): *FMB* isFloatingMenuEnabled return false
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/BroadcastQueue( 1016): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1469, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 23
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=4, NainActivit
,W/ResourcesManager( 2484): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2517): MountEmulatedStorage()
E/Zygote  ( 2517): v2
I/libpersona( 2517): KNOX_SDCARD checking this for 10054
I/libpersona( 2517): KNOX_SDCARD not a persona
,I/SELinux ( 2517): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2517 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
,I/SELinux ( 2517): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2517): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/TaskCloserActivity( 2497): TaskCloserActivity enter()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/SRIB_DCS( 2372): log_dcs ThreadedRenderer::initialize entered! 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
V/TaskCloserActivity( 2497): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,E/Zygote  ( 2527): MountEmulatedStorage()
E/Zygote  ( 2527): v2
I/libpersona( 2527): KNOX_SDCARD checking this for 10139
I/libpersona( 2527): KNOX_SDCARD not a persona
,I/SELinux ( 2527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2527 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 2527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/TimaKeyStoreProvider( 2517): TimaSignature is unavailable
,D/ActivityThread( 2517): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2527): TimaSignature is unavailable
,D/ActivityThread( 2527): Added TimaKeyStore provider
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/ResourcesManager( 2517): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 2527): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2527): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Recents_RecreateReceiver( 2517): onReceive by home
,D/NearbySource( 2469): Nearby Source Create!
,D/NearbyContext( 2469): Nearby Context Create!
,D/SamsungIME( 1806): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2469): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2469): Samsung link source created
,D/ContactProvider( 2469): getAllContactInfoList Start
,W/art     ( 2434): Verification of void com.android.contacts.common.list.l.P() took 175.744ms
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2469): Receive : home resume
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 2279): ui event
,I/splitIntent( 1016): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,E/SQLiteLog( 1226): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ContactProvider( 2469): getAllContactInfoList End
,I/syncContacts( 2469): thread: 253, sync time = 80
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SIP     ( 1449): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1449): fail readDirectory() errno=2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1788): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1765): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/AbsListView( 2434): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1765): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1,
,D/accuweather( 1765): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1765): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1765): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1765): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1765): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1765): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1765): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1765): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
D/accuweather( 1765): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1765): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
D/accuweather( 1765): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1765): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 21
,E/accuweather( 1765): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1765): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1765): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1765): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1765): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1765): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1765): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1765): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1765): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1765): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1765): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1311): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1311): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/USB_UICC(  296): Timeout! No signal received. Retry num = 24
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/Mms/MmsApp( 2279):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 2279): [start]    fillCache consume time = 1859.857552
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/ComposeMessageFragment( 2279): fillCache, easy = false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,I/Scheduler( 1788): Use legacy PeriodicScheduler
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1311): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1311): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,W/InstanceID/Rpc( 1788): Found 10012
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/AbsListView( 2279): Get MotionRecognitionManager
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/MotionRecognitionService( 1016):  ssp status : false
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/ComposeMessageFragment( 2279): [end]    fillCache consume time = 184.066718
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1311): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/AdaptiveEventManager( 1180): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/daemonapp( 1311): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/AdaptiveEventManager( 1180): currentCityId is null
D/AdaptiveEventManager( 1180): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1180): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1180): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1180): mWeatherInfo is not reliable
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/daemonapp( 1311): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,E/Zygote  ( 2564): MountEmulatedStorage()
E/Zygote  ( 2564): v2
I/libpersona( 2564): KNOX_SDCARD checking this for 10135
I/libpersona( 2564): KNOX_SDCARD not a persona
,I/SELinux ( 2564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2564): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2564): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2564 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1457533272693
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1457554872682
,D/TimaKeyStoreProvider( 2564): TimaSignature is unavailable
D/daemonapp( 1311): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
D/ActivityThread( 2564): Added TimaKeyStore provider
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1457554860000
,D/daemonapp( 1311): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457554860000
,W/ResourcesManager( 2564): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2564): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2564): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 15
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1457554860000
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2580): MountEmulatedStorage(),
E/Zygote  ( 2580): v2,
I/libpersona( 2580): KNOX_SDCARD checking this for 1000
,I/SELinux ( 2580): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2580): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2580 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2580): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2580): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  306): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 26.178ms
,D/TimaKeyStoreProvider( 2580): TimaSignature is unavailable
D/ActivityThread( 2580): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 18.129ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 679us total 19.674ms
,D/SecurityLogAgent( 2580):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2580):  SeDenialReceiver : File path = /data/misc/audit/audit.old
,D/SecurityLogAgent( 2580):  SeDenialReceiver : Start file Zipping Service 
,W/ContextImpl( 2580): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
,D/SecurityLogAgent( 2580): FileZippingService : onHandleIntent 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent( 2580): FileZippingService : file path =  /data/misc/audit/audit.old
,E/Zygote  ( 2598): MountEmulatedStorage()
,E/Zygote  ( 2598): v2
I/libpersona( 2598): KNOX_SDCARD checking this for 1000
I/libpersona( 2598): KNOX_SDCARD not a persona
,I/SELinux ( 2598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2598 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/Mms/BubbleViewCache( 2279): fillCache bubble = 1
,I/SELinux ( 2598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2598): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SecurityLogAgent( 2580): FileZippingService : onPremise disabled. Zipping..  
,D/TimaKeyStoreProvider( 2598): TimaSignature is unavailable
,D/ActivityThread( 2598): Added TimaKeyStore provider
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator File existence : true audit.old file size 631
,D/SecurityLogAgent( 2580): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
,D/SecurityLogAgent( 2580): FileZippingService : completed task. Returning wakelock . 
,W/ContextImpl( 2598): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2615): MountEmulatedStorage()
I/libpersona( 2615): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2615): v2
I/libpersona( 2615): KNOX_SDCARD not a persona
,I/SELinux ( 2615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2615 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2615): TimaSignature is unavailable,
D/ActivityThread( 2615): Added TimaKeyStore provider
,W/ResourcesManager( 2615): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2615): [FactoryTestBroadcastReceiver$onReceive](2615) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2615): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2615): [XMLDataStorage$parseXML](2615) is Live Demo : false
,D/FactoryTestApp( 2615): [XMLDataStorage$parseXML](2615) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2615): [XMLDataStorage$parseXML](2615) deviceXML=a5ulte.dat
,D/FactoryTestApp( 2615): [XMLDataStorage$parseXML](2615) nameXML=a5ultexx.dat
,D/FactoryTestApp( 2615): [XMLDataStorage$parseAsset](2615) parseAsset Is Started
,I/FactoryTestApp( 2615): [XMLDataStorage$parseAsset](2615) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2615): [XMLDataStorage$parseAsset](2615) Decode base file: factory.dat
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FACTORY_TEST_APP
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FAILHIST_VERSION
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=MODEL_NAME
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=MODEL_NUMBER
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=MODEL_COMMUNICATION_MODE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=CHIPSET_NAME
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=DEVICE_TYPE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=BATT_TYPE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PANEL_TYPE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SENSOR_NAME_ACCELEROMETER
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SENSOR_NAME_GYROSCOPE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SPEAKER_COUNT
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=MIC_COUNT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TORCH_MODE_FLASH_ON_CURRENT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_LTE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_DUAL_STANBY_ONE_CP
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_RCV
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_NVBACKUP_CMD
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_EPEN
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_SENSORHUB
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_CAM_ISP
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=NEED_CAMDRIVER_OPEN
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HW_VER_EFS
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_MULTI_SIM_FRAMEWORK
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FONT_SIZE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=RAM_SIZE_IF
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=MULTI_TSK_THD
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=NEED_LPA_MODE_SET
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_DISABLE_SCROLLING_CACHE
D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_POWER
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_APP_SWITCH
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_HOME
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_BACK
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SEMI_KEY_TEST_VOLUME_DOWN,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SEMI_KEY_TEST_HOME,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_KEY_TEST_THRESHOLD,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_TSP_STANDARD_CHANNEL,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_SENSOR_TEST_ACC_REVERSE,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_GEOMAGNETIC_ALPS_CAL,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=G_VECTOR_SUM_ACC_BIT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=AT_GPSSTEST
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SUPPORT_CHARGE_COUNT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PA1_TEMP_ADC,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HALL_IC_TEST,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_NEW_TSP_SELFTEST_SYNAPTICS,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=READ_TARGET_GEOMAGNETIC,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SYS_INFO_FONT_SIZE,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SYS_INFO_MEMORY_SIZE,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SYS_INFO_MODEL_NAME,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_NODE_COUNT_WIDTH,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_NODE_COUNT_HEIGHT,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_SELFTEST_MIN_MELFAS,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_SELFTEST_MAX_MELFAS,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TOUCH_KEY_SPEC_MIN,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TOUCH_KEY_SPEC_MAX,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=BOOTLOADER_VERSION,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=BATTERY_VOLT_AVER,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=BATTERY_VF_OCV,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=KEY_PRESSED_POWER
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HUMITEMP_THERMISTER_BATT,
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=LPA_MODE_SET
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2615): [XMLDataStorage$redefinitionById](2615) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2615): [XMLDataStorage$parseAsset](2615) SemiFunctionMenu,
,D/FactoryTestApp( 2615): [XMLDataStorage$parseAsset](2615) parseAsset Is Completed
,E/SMD     (  288): DCD OFF
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2615): [ModuleCommon$ModuleCommon](2615) Create ModuleCommon
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2615): [Support$Kernel.read](2615) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 2615): [ModuleCommon$readFactoryMode](2615) mode: ON
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 2615): [FactoryTestBroadcastReceiver$onReceive](2615) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2615): [Support$Values.getBoolean](2615) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=BINARY_TYPE, key=ro.factory.factory_binary
,D/FactoryTestApp( 2615): [Support$Properties.get](2615) property=ro.factory.factory_binary
D/FactoryTestApp( 2615): [FactoryTestBroadcastReceiver$onReceive](2615) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2615): [ModuleCommon$getFtClientEnableState](2615) result : false
I/FactoryTestApp( 2615): [ModuleCommon$connectedJIG](2615) ...
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2615): [ModuleCommon$connectedJIG](2615) cable_type = ANYWAY_JIG
D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
E/USB_UICC(  296): Timeout! No signal received. Retry num = 25
,D/FactoryTestApp( 2615): [Support$Kernel.read](2615) path=/sys/class/sec/switch/adc, value=1f
I/FactoryTestApp( 2615): [ModuleCommon$connectedJIG](2615) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2615): [ModuleCommon$isConnectionModeNone](2615) mConnectionMode = gsm
I/FactoryTestApp( 2615): [ModuleCommon$isRunningFtClient](2615) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2615): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2615) start DummyFtClient service for APO
,W/ContextImpl( 2615): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 ,
,D/ActivityManager( 1016): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2615): User mode
I/FactoryTestApp( 2615): [ModuleCommon$disableFtClient](2615) ...
,D/FactoryTestApp( 2615): [DummyFtClient$onCreate](2615) Create DummyFtClient service
I/FactoryTestApp( 2615): [XMLDataStorage$parsingXML](2615) FtClient => data parsing was completed.
D/FactoryTestApp( 2615): [DummyFtClient$onReceive](2615) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2615): [ModuleCommon$isConnectionModeNone](2615) mConnectionMode = gsm
D/FactoryTestApp( 2615): [Support$Values.getBoolean](2615) id=SUPPORT_AUTO_WAKELOCK, value=false
D/FactoryTestApp( 2615): [DummyFtClient$onStartCommand](2615) ...
,I/WifiService( 1016): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1016): boot completed
,D/UsbDeviceManager( 1016): handleMessage -> MSG_BOOT_COMPLETED
D/UsbDeviceManager( 1016): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1016): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,I/KeyguardEffectViewUtil( 1180): set resource id
,D/SettingsProvider( 1016): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10054
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BOOT_COMPLETED
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
D/KeyguardUpdateMonitor( 1180): handleBootCompleted()
,I/PalmMotion( 1016): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
E/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1016): [PALM] SURFACE_PALM_SWIPE: 1
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/PalmMotion( 1016): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PalmMotion( 1016): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/UsbDeviceManager( 1016): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,D/SamsungIME( 1806): showDlgMsgBox : false true true
,D/NfcService( 1433): call the applyRouting
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/RecoverySystem( 1016): !@RecoverySystem handleAftermath
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/RecoverySystem( 1016): No recovery log file
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 2641): MountEmulatedStorage()
,E/Zygote  ( 2641): v2
,I/libpersona( 2641): KNOX_SDCARD checking this for 1000
I/libpersona( 2641): KNOX_SDCARD not a persona
,I/SELinux ( 2641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2641 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/RecoverySystem( 1016): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
,E/RecoverySystem( 1016): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1016): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,I/SELinux ( 2641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2641): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/Reset_Reason( 1016): resetString = NPON
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/OtaStartupReceiver( 1449): onOtaspChanged: mOtaspMode=1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/BootReceiver( 1016): Copying audit failures to DropBox
I/BootReceiver( 1016): Checking for fsck errors
,D/TimaKeyStoreProvider( 2641): TimaSignature is unavailable
D/ActivityThread( 2641): Added TimaKeyStore provider
,I/BootReceiver( 1016): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/Zygote  ( 2659): MountEmulatedStorage()
I/libpersona( 2659): KNOX_SDCARD checking this for 1001
E/Zygote  ( 2659): v2
I/libpersona( 2659): KNOX_SDCARD not a persona
,I/SELinux ( 2659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/SELinux ( 2659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2659 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2659): TimaSignature is unavailable
,D/ActivityThread( 2659): Added TimaKeyStore provider
,W/ResourcesManager( 2659): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/File    ( 2641): fail readDirectory() errno=2
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,D/FactoryTestApp( 2615): [ProtectedFactoryTestBroadcastReceiver$onReceive](2615) onReceive action=com.samsung.intent.action.SECPHONE_READY
I/FactoryTestApp( 2615): [ProtectedFactoryTestBroadcastReceiver$onReceive](2615) com.samsung.intent.action.SECPHONE_READY
,D/FactoryTest( 2615): User mode
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/NotificationReceiver( 2279): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
,D/Mms/NotificationReceiver( 2279): handleBootCompleted()
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/RcsOwnCapsManager( 2279): queue Uri = content://im/queue-messages?box=pending
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/BootReceiver( 1016): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/TP/ImProvider( 1449): im query match24
,D/TP/ImProvider( 1449): URI_IM_QUEUED_MESSAGES
D/TP/ImProvider( 1449): ftSesstionId must be a long.
,D/TP/ImProvider( 1449): getQueuedImMessages
D/TP/ImProvider( 1449): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
D/Mms/NotificationReceiver( 2279):  getPendingMessageIds: no pending messages.
D/Mms/ActionsFactory( 2279): Call to GET_LAST_MESSAGES_SENT
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
I/GAV4    ( 2191): Thread[GAThread,5,main]: No campaign data found.
D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 31510, tid: 31510, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1016):     r0 b914bd48  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1016):     r4 0045b0a0  r5 be11f218  r6 b914bd48  r7 be11f228
D/CrashAnrDetector( 1016):     r8 be11ee60  r9 ba64e378  sl ba64e378  fp be11f1dc
D/CrashAnrDetector( 1016):     ip be11f228  sp be11ee58  lr a0b0030c  pc a0affd98  cpsr a00f0010
D/CrashAnrDetector( 1016):     d0  ffffff859ec62bb0  d1  0000000000000000
D/CrashAnrDetector( 1016):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1016):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1016):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1016):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1016):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1016):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1016):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1016):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1016):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1016):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1016):     scr 20000013
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1016):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1016):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1016):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          be11edd8  00000000  
D/CrashAnrDetector( 1016):          be11eddc  00000000  
D/CrashAnrDetector( 1016):          be11ede0  00000000  
D/CrashAnrDetector( 1016):          be11ede4  00000000  
D/CrashAnrDetector( 1016):          be11ede8  00000000  
D/CrashAnrDetector( 1016):          be11edec  00000000  
D/CrashAnrDetector( 1016):          be11edf0  00000000  
D/CrashAnrDetector( 1016):          be11edf4  00000000  
D/CrashAnrDetector( 1016):          be11edf8  00000000  
D/CrashAnrDetector( 1016):          be11edfc  00000000  
D/CrashAnrDetector( 1016):          be11ee00  00000000  
D/CrashAnrDetector( 1016):          be11ee04  00000000  
D/CrashAnrDetector( 1016):          be11ee08  00000000  
D/CrashAnrDetector( 1016):          be11ee0c  00000000  
D/CrashAnrDetector( 1016):          be11ee10  00000000  
D/CrashAnrDetector( 1016):          be11ee14  00000000  
D/CrashAnrDetector( 1016):          be11ee18  00000000  
D/CrashAnrDetector( 1016):          be11ee1c  00000000  
D/CrashAnrDetector( 1016):          be11ee20  00000000  
D/CrashAnrDetector( 1016):          be11ee24  00000000  
D/CrashAnrDetector( 1016):          be11ee28  00000000  
D/CrashAnrDetector( 1016):          be11ee2c  00000000  
D/CrashAnrDetector( 1016):          be11ee30  00000000  
D/CrashAnrDetector( 1016):          be11ee34  00000000  
D/CrashAnrDetector( 1016):          be11ee38  00000000  
D/CrashAnrDetector( 1016):          be11ee3c  00000000  
D/CrashAnrDetector( 1016):          be11ee40  00000000  
D/CrashAnrDetector( 1016):          be11ee44  00000000  
D/CrashAnrDetector( 1016):          be11ee48  00000000  
D/CrashAnrDetector( 1016):          be11ee4c  00000000  
D/CrashAnrDetector( 1016):          be11ee50  00000000  
D/CrashAnrDetector( 1016):          be11ee54  00000000  
D/CrashAnrDetector( 1016):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1016):          be11ee5c  00000000  
D/CrashAnrDetector( 1016):          be11ee60  00000000  
D/CrashAnrDetector( 1016):          be11ee64  00000000  
D/CrashAnrDetector( 1016):          be11ee68  00000000  
D/CrashAnrDetector( 1016):          be11ee6c  00000000  
D/CrashAnrDetector( 1016):          be11ee70  00000000  
D/CrashAnrDetector( 1016):          be11ee74  00000000  
D/CrashAnrDetector( 1016):          be11ee78  00000000  
D/CrashAnrDetector( 1016):          be11ee7c  00000000  
D/CrashAnrDetector( 1016):          be11ee80  00000000  
D/CrashAnrDetector( 1016):          be11ee84  00000000  
D/CrashAnrDetector( 1016):          be11ee88  00000000  
D/CrashAnrDetector( 1016):          be11ee8c  00000000  
D/CrashAnrDetector( 1016):          be11ee90  00000000  
D/CrashAnrDetector( 1016):          be11ee94  00000000  
D/CrashAnrDetector( 1016):          be11ee98  00000000  
D/CrashAnrDetector( 1016):          be11ee9c  00000000  
D/CrashAnrDetector( 1016):          be11eea0  00000000  
D/CrashAnrDetector( 1016):          be11eea4  00000000  
D/CrashAnrDetector( 1016):          be11eea8  00000000  
D/CrashAnrDetector( 1016):          be11eeac  00000000  
D/CrashAnrDetector( 1016):          be11eeb0  00000000  
D/CrashAnrDetector( 1016):          be11eeb4  00000000  
D/CrashAnrDetector( 1016):          be11eeb8  00000000  
D/CrashAnrDetector( 1016):          be11eebc  00000000  
D/CrashAnrDetector( 1016):       
D/CrashAnrDetector( 1016): processName:com.test.thalitest
D/CrashAnrDetector( 1016): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/GAv4-SVC( 2052): Google Analytics 8.4.89 is starting up.
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/BootReceiver( 1016): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/SettingsProvider( 1016): name = db_smartlock_supported
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 2016, tid: 2016, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1016):     r0 b926a1f0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1016):     r4 0045b0a0  r5 be11f218  r6 b926a1f0  r7 be11f228
D/CrashAnrDetector( 1016):     r8 be11ee60  r9 baf12548  sl baf12548  fp be11f1dc
D/CrashAnrDetector( 1016):     ip be11f228  sp be11ee58  lr a09c330c  pc a09c2d98  cpsr a00f0010
D/CrashAnrDetector( 1016):     d0  ffffff859e8579c0  d1  0000000000000000
D/CrashAnrDetector( 1016):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1016):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1016):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1016):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1016):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1016):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1016):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1016):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1016):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1016):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1016):     scr 20000013
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1016):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1016):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1016):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          be11edd8  00000000  
D/CrashAnrDetector( 1016):          be11eddc  00000000  
D/CrashAnrDetector( 1016):          be11ede0  00000000  
D/CrashAnrDetector( 1016):          be11ede4  00000000  
D/CrashAnrDetector( 1016):          be11ede8  00000000  
D/CrashAnrDetector( 1016):          be11edec  00000000  
D/CrashAnrDetector( 1016):          be11edf0  00000000  
D/CrashAnrDetector( 1016):          be11edf4  00000000  
D/CrashAnrDetector( 1016):          be11edf8  00000000  
D/CrashAnrDetector( 1016):          be11edfc  00000000  
D/CrashAnrDetector( 1016):          be11ee00  00000000  
D/CrashAnrDetector( 1016):          be11ee04  00000000  
D/CrashAnrDetector( 1016):          be11ee08  00000000  
D/CrashAnrDetector( 1016):          be11ee0c  00000000  
D/CrashAnrDetector( 1016):          be11ee10  00000000  
D/CrashAnrDetector( 1016):          be11ee14  00000000  
D/CrashAnrDetector( 1016):          be11ee18  00000000  
D/CrashAnrDetector( 1016):          be11ee1c  00000000  
D/CrashAnrDetector( 1016):          be11ee20  00000000  
D/CrashAnrDetector( 1016):          be11ee24  00000000  
D/CrashAnrDetector( 1016):          be11ee28  00000000  
D/CrashAnrDetector( 1016):          be11ee2c  00000000  
D/CrashAnrDetector( 1016):          be11ee30  00000000  
D/CrashAnrDetector( 1016):          be11ee34  00000000  
D/CrashAnrDetector( 1016):          be11ee38  00000000  
D/CrashAnrDetector( 1016):          be11ee3c  00000000  
D/CrashAnrDetector( 1016):          be11ee40  00000000  
D/CrashAnrDetector( 1016):          be11ee44  00000000  
D/CrashAnrDetector( 1016):          be11ee48  00000000  
D/CrashAnrDetector( 1016):          be11ee4c  00000000  
D/CrashAnrDetector( 1016):          be11ee50  00000000  
D/CrashAnrDetector( 1016):          be11ee54  00000000  
D/CrashAnrDetector( 1016):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1016):          be11ee5c  00000000  
D/CrashAnrDetector( 1016):          be11ee60  00000000  
D/CrashAnrDetector( 1016):          be11ee64  00000000  
D/CrashAnrDetector( 1016):          be11ee68  00000000  
D/CrashAnrDetector( 1016):          be11ee6c  00000000  
D/CrashAnrDetector( 1016):          be11ee70  00000000  
D/CrashAnrDetector( 1016):          be11ee74  00000000  
D/CrashAnrDetector( 1016):          be11ee78  00000000  
D/CrashAnrDetector( 1016):          be11ee7c  00000000  
D/CrashAnrDetector( 1016):          be11ee80  00000000  
D/CrashAnrDetector( 1016):          be11ee84  00000000  
D/CrashAnrDetector( 1016):          be11ee88  00000000  
D/CrashAnrDetector( 1016):          be11ee8c  00000000  
D/CrashAnrDetector( 1016):          be11ee90  00000000  
D/CrashAnrDetector( 1016):          be11ee94  00000000  
D/CrashAnrDetector( 1016):          be11ee98  00000000  
D/CrashAnrDetector( 1016):          be11ee9c  00000000  
D/CrashAnrDetector( 1016):          be11eea0  00000000  
D/CrashAnrDetector( 1016):          be11eea4  00000000  
D/CrashAnrDetector( 1016):          be11eea8  00000000  
D/CrashAnrDetector( 1016):          be11eeac  00000000  
D/CrashAnrDetector( 1016):          be11eeb0  00000000  
D/CrashAnrDetector( 1016):          be11eeb4  00000000  
D/CrashAnrDetector( 1016):          be11eeb8  00000000  
D/CrashAnrDetector( 1016):          be11eebc  00000000  
D/CrashAnrDetector( 1016):         
D/CrashAnrDetector( 1016): processName:com.test.thalitest
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1016): broadcastEvent : null SYSTEM_TOMBSTONE
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/BootReceiver( 1016): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/AccessibilityManagerService( 1016): setmDNIeNegative (false)
,D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 8409, tid: 8409, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1016):     r0 b9145f50  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1016):     r4 0045b0a0  r5 be11f218  r6 b9145f50  r7 be11f228
D/CrashAnrDetector( 1016):     r8 be11ee60  r9 bab49fd0  sl bab49fd0  fp be11f1dc
D/CrashAnrDetector( 1016):     ip be11f228  sp be11ee58  lr 9fdfc30c  pc 9fdfbd98  cpsr a00f0010
D/CrashAnrDetector( 1016):     d0  ffffff859df5ebb0  d1  646f6d5f65646f6e
D/CrashAnrDetector( 1016):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1016):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1016):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1016):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1016):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1016):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1016):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1016):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1016):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1016):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1016):     scr 20000012
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1016):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1016):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1016):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          be11edd8  00000000  
D/CrashAnrDetector( 1016):          be11eddc  00000000  
D/CrashAnrDetector( 1016):          be11ede0  00000000  
D/CrashAnrDetector( 1016):          be11ede4  00000000  
D/CrashAnrDetector( 1016):          be11ede8  00000000  
D/CrashAnrDetector( 1016):          be11edec  00000000  
D/CrashAnrDetector( 1016):          be11edf0  00000000  
D/CrashAnrDetector( 1016):          be11edf4  00000000  
D/CrashAnrDetector( 1016):          be11edf8  00000000  
D/CrashAnrDetector( 1016):          be11edfc  00000000  
D/CrashAnrDetector( 1016):     ,     be11ee00  00000000  
D/CrashAnrDetector( 1016):          be11ee04  00000000  
D/CrashAnrDetector( 1016):          be11ee08  00000000  
D/CrashAnrDetector( 1016):          be11ee0c  00000000  
D/CrashAnrDetector( 1016):          be11ee10  00000000  
D/CrashAnrDetector( 1016):          be11ee14  00000000  
D/CrashAnrDetector( 1016):          be11ee18  00000000  
D/CrashAnrDetector( 1016):          be11ee1c  00000000  
D/CrashAnrDetector( 1016):          be11ee20  00000000  
D/CrashAnrDetector( 1016):          be11ee24  00000000  
D/CrashAnrDetector( 1016):          be11ee28  00000000  
D/CrashAnrDetector( 1016):          be11ee2c  00000000  
D/CrashAnrDetector( 1016):          be11ee30  00000000  
D/CrashAnrDetector( 1016):          be11ee34  00000000  
D/CrashAnrDetector( 1016):          be11ee38  00000000  
D/CrashAnrDetector( 1016):          be11ee3c  00000000  
D/CrashAnrDetector( 1016):          be11ee40  00000000  
D/CrashAnrDetector( 1016):          be11ee44  00000000  
D/CrashAnrDetector( 1016):          be11ee48  00000000  
D/CrashAnrDetector( 1016):          be11ee4c  00000000  
D/CrashAnrDetector( 1016):          be11ee50  00000000  
D/CrashAnrDetector( 1016):          be11ee54  00000000  
D/CrashAnrDetector( 1016):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1016):          be11ee5c  00000000  
D/CrashAnrDetector( 1016):          be11ee60  00000000  
D/CrashAnrDetector( 1016):          be11ee64  00000000  
D/CrashAnrDetector( 1016):          be11ee68  00000000  
D/CrashAnrDetector( 1016):          be11ee6c  00000000  
D/CrashAnrDetector( 1016):          be11ee70  00000000  
D/CrashAnrDetector( 1016):          be11ee74  00000000  
D/CrashAnrDetector( 1016):          be11ee78  00000000  
D/CrashAnrDetector( 1016):          be11ee7c  00000000  
D/CrashAnrDetector( 1016):          be11ee80  00000000  
D/CrashAnrDetector( 1016):          be11ee84  00000000  
D/CrashAnrDetector( 1016):          be11ee88  00000000  
D/CrashAnrDetector( 1016):          be11ee8c  00000000  
D/CrashAnrDetector( 1016):          be11ee90  00000000  
D/CrashAnrDetector( 1016):          be11ee94  00000000  
D/CrashAnrDetector( 1016):          be11ee98  00000000  
D/CrashAnrDetector( 1016):          be11ee9c  00000000  
D/CrashAnrDetector( 1016):          be11eea0  00000000  
D/CrashAnrDetector( 1016):          be11eea4  00000000  
D/CrashAnrDetector( 1016):          be11eea8  00000000  
D/CrashAnrDetector( 1016):          be11eeac  00000000  
D/CrashAnrDetector( 1016):          be11eeb0  00000000  
D/CrashAnrDetector( 1016):          be11eeb4  00000000  
D/CrashAnrDetector( 1016):          be11eeb8  00000000  
D/CrashAnrDetector( 1016):          be11eebc  00000000  
D/CrashAnrDetector( 1016):         
D/CrashAnrDetector( 1016): processName:com.test.thalitest
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1016): broadcastEvent : null SYSTEM_TOMBSTONE
,I/BootReceiver( 1016): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 10813, tid: 10813, name: .test.thalitest  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xbe11ee60
D/CrashAnrDetector( 1016):     r0 b92c7dd0  r1 be11f228  r2 00000001  r3 00000000
D/CrashAnrDetector( 1016):     r4 0045b0a0  r5 be11f218  r6 b92c7dd0  r7 be11f228
D/CrashAnrDetector( 1016):     r8 be11ee60  r9 b9a6af30  sl b9a6af30  fp be11f1dc
D/CrashAnrDetector( 1016):     ip be11f228  sp be11ee58  lr a0d6430c  pc a0d63d98  cpsr a00f0010
D/CrashAnrDetector( 1016):     d0  ffffff859ec579c0  d1  0000000000000000
D/CrashAnrDetector( 1016):     d2  ffffff8200000000  d3  ffffff8200000000
D/CrashAnrDetector( 1016):     d4  ffffff8200000000  d5  ffffff8200000000
D/CrashAnrDetector( 1016):     d6  ffffff8200000000  d7  ffffff8200000000
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 ffffffffffff0000  d17 ffffffffffffffff
D/CrashAnrDetector( 1016):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1016):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1016):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1016):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1016):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1016):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1016):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1016):     scr 20000012
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 0064cd98  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+24)
D/CrashAnrDetector( 1016):     #01 pc 0064d308  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::Value const&, JS::Value const&, unsigned int, JS::Value const*, JS::MutableHandle<JS::Value>)+384)
D/CrashAnrDetector( 1016):     #02 pc 0054c65c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_CallFunctionValue(JSContext*, JS::Handle<JSObject*>, JS::Handle<JS::Value>, JS::HandleValueArray const&, JS::MutableHandle<JS::Value>)+88)
D/CrashAnrDetector( 1016):     #03 pc 00763e48  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::Call(MozJS::Value const&, int, MozJS::Value*) const+240)
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          be11edd8  00000000  
D/CrashAnrDetector( 1016):          be11eddc  00000000  
D/CrashAnrDetector( 1016):          be11ede0  00000000  
D/CrashAnrDetector( 1016):          be11ede4  00000000  
D/CrashAnrDetector( 1016):          be11ede8  00000000  
D/CrashAnrDetector( 1016):          be11edec  00000000  
D/CrashAnrDetector( 1016):          be11edf0  00000000  
D/CrashAnrDetector( 1016):          be11edf4  00000000  
D/CrashAnrDetector( 1016):          be11edf8  00000000  
D/CrashAnrDetector( 1016):          be11edfc  00000000  
D/CrashAnrDetector( 1016):   ,       be11ee00  00000000  
D/CrashAnrDetector( 1016):          be11ee04  00000000  
D/CrashAnrDetector( 1016):          be11ee08  00000000  
D/CrashAnrDetector( 1016):          be11ee0c  00000000  
D/CrashAnrDetector( 1016):          be11ee10  00000000  
D/CrashAnrDetector( 1016):          be11ee14  00000000  
D/CrashAnrDetector( 1016):          be11ee18  00000000  
D/CrashAnrDetector( 1016):          be11ee1c  00000000  
D/CrashAnrDetector( 1016):          be11ee20  00000000  
D/CrashAnrDetector( 1016):          be11ee24  00000000  
D/CrashAnrDetector( 1016):          be11ee28  00000000  
D/CrashAnrDetector( 1016):          be11ee2c  00000000  
D/CrashAnrDetector( 1016):          be11ee30  00000000  
D/CrashAnrDetector( 1016):          be11ee34  00000000  
D/CrashAnrDetector( 1016):          be11ee38  00000000  
D/CrashAnrDetector( 1016):          be11ee3c  00000000  
D/CrashAnrDetector( 1016):          be11ee40  00000000  
D/CrashAnrDetector( 1016):          be11ee44  00000000  
D/CrashAnrDetector( 1016):          be11ee48  00000000  
D/CrashAnrDetector( 1016):          be11ee4c  00000000  
D/CrashAnrDetector( 1016):          be11ee50  00000000  
D/CrashAnrDetector( 1016):          be11ee54  00000000  
D/CrashAnrDetector( 1016):     #00  be11ee58  00000000  
D/CrashAnrDetector( 1016):          be11ee5c  00000000  
D/CrashAnrDetector( 1016):          be11ee60  00000000  
D/CrashAnrDetector( 1016):          be11ee64  00000000  
D/CrashAnrDetector( 1016):          be11ee68  00000000  
D/CrashAnrDetector( 1016):          be11ee6c  00000000  
D/CrashAnrDetector( 1016):          be11ee70  00000000  
D/CrashAnrDetector( 1016):          be11ee74  00000000  
D/CrashAnrDetector( 1016):          be11ee78  00000000  
D/CrashAnrDetector( 1016):          be11ee7c  00000000  
D/CrashAnrDetector( 1016):          be11ee80  00000000  
D/CrashAnrDetector( 1016):          be11ee84  00000000  
D/CrashAnrDetector( 1016):          be11ee88  00000000  
D/CrashAnrDetector( 1016):          be11ee8c  00000000  
D/CrashAnrDetector( 1016):          be11ee90  00000000  
D/CrashAnrDetector( 1016):          be11ee94  00000000  
D/CrashAnrDetector( 1016):          be11ee98  00000000  
D/CrashAnrDetector( 1016):          be11ee9c  00000000  
D/CrashAnrDetector( 1016):          be11eea0  00000000  
D/CrashAnrDetector( 1016):          be11eea4  00000000  
D/CrashAnrDetector( 1016):          be11eea8  00000000  
D/CrashAnrDetector( 1016):          be11eeac  00000000  
D/CrashAnrDetector( 1016):          be11eeb0  00000000  
D/CrashAnrDetector( 1016):          be11eeb4  00000000  
D/CrashAnrDetector( 1016):          be11eeb8  00000000  
D/CrashAnrDetector( 1016):          be11eebc  00000000  
D/CrashAnrDetector( 1016):       
D/CrashAnrDetector( 1016): processName:com.test.thalitest
D/CrashAnrDetector( 1016): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/BootReceiver( 1016): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 6058, tid: 6772, name: Thread-1061  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9c909ff0
D/CrashAnrDetector( 1016):     r0 710804a8  r1 735927c8  r2 12dd4780  r3 13533ec0
D/CrashAnrDetector( 1016):     r4 000000c2  r5 710804a8  r6 735927c8  r7 13533ec0
D/CrashAnrDetector( 1016):     r8 73592770  r9 ba677458  sl 12dd4780  fp 9ca0b8a8
D/CrashAnrDetector( 1016):     ip 9c909ff0  sp 9c90bff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1016):     d0  12dd4780735927c0  d1  007300200065003e
D/CrashAnrDetector( 1016):     d2  c0c0c0c0c0c0c053  d3  0102020202020213
D/CrashAnrDetector( 1016):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1016):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1016):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1016):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1016):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1016):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1016):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1016):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1016):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1016):     scr 20000013
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1016):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          9c90bf70  00000000  
D/CrashAnrDetector( 1016):          9c90bf74  00000000  
D/CrashAnrDetector( 1016):          9c90bf78  00000000  
D/CrashAnrDetector( 1016):          9c90bf7c  00000000  
D/CrashAnrDetector( 1016):          9c90bf80  00000000  
D/CrashAnrDetector( 1016):          9c90bf84  00000000  
D/CrashAnrDetector( 1016):          9c90bf88  00000000  
D/CrashAnrDetector( 1016):          9c90bf8c  00000000  
D/CrashAnrDetector( 1016):          9c90bf90  00000000  
D/CrashAnrDetector( 1016):          9c90bf94  00000000  
D/CrashAnrDetector( 1016):          9c90bf98  00000000  
D/CrashAnrDetector( 1016):          9c90bf9c  00000000  
D/CrashAnrDetector( 1016):          9c90bfa0  00000000  
D/CrashAnrDetector( 1016):          9c90bfa4  00000000  
D/CrashAnrDetector( 1016):          9c90bfa8  00000000  
D/CrashAnrDetector( 1016):          9c90bfac  00000000  
D/CrashAnrDetector( 1016):          9c90bfb0  00000000  
D/CrashAnrDetector( 1016):          9c90bfb4  00000000  
D/CrashAnrDetector( 1016):          9c90bfb8  00000000  
D/CrashAnrDetector( 1016):          9c90bfbc  00000000  
D/CrashAnrDetector( 1016):          9c90bfc0  00000000  
D/CrashAnrDetector( 1016):          9c90bfc4 , 00000000  
D/CrashAnrDetector( 1016):          9c90bfc8  00000000  
D/CrashAnrDetector( 1016):          9c90bfcc  00000000  
D/CrashAnrDetector( 1016):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90bfd4  00000000  
D/CrashAnrDetector( 1016):          9c90bfd8  00000000  
D/CrashAnrDetector( 1016):          9c90bfdc  00000000  
D/CrashAnrDetector( 1016):          9c90bfe0  00000000  
D/CrashAnrDetector( 1016):          9c90bfe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90bfe8  e3a070ad  
D/CrashAnrDetector( 1016):          9c90bfec  ef9000ad  
D/CrashAnrDetector( 1016):     #00  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          ........  ........
D/CrashAnrDetector( 1016):     #01  9c90bff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90bff4  00000000  
D/CrashAnrDetector( 1016):          9c90bff8  00000000  
D/CrashAnrDetector( 1016):          9c90bffc  00000000  
D/CrashAnrDetector( 1016):          9c90c000  00000000  
D/CrashAnrDetector( 1016):          9c90c004  00000000  
D/CrashAnrDetector( 1016):          9c90c008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c00c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c010  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1016):          9c90c014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c018  12dd4780  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1016):          9c90c01c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1016):          9c90c020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c024  00000000  
D/CrashAnrDetector( 1016):          9c90c028  00000000  
D/CrashAnrDetector( 1016):          9c90c02c  00000000  
D/CrashAnrDetector( 1016):          9c90c030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c034  00000000  
D/CrashAnrDetector( 1016):          9c90c038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c03c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          9c90c040  13533ec0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1016):          9c90c044  73
D/CrashAnrDetector( 1016): processName:com.test.thalitest
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1016): broadcastEvent : null SYSTEM_TOMBSTONE
,I/BootReceiver( 1016): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1016): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 6080, tid: 6935, name: Thread-1071  >>> com.test.thalitest <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa37a6ff0
D/CrashAnrDetector( 1016):     r0 710804a8  r1 735927c8  r2 12e00890  r3 133c2fc0
D/CrashAnrDetector( 1016):     r4 000000c2  r5 710804a8  r6 735927c8  r7 133c2fc0
D/CrashAnrDetector( 1016):     r8 73592770  r9 b8284ec8  sl 12e00890  fp a38a88a8
D/CrashAnrDetector( 1016):     ip a37a6ff0  sp a37a8ff0  lr 76166389  pc 7616630c  cpsr a00f0030
D/CrashAnrDetector( 1016):     d0  12e00890735927c0  d1  007300200065002f
D/CrashAnrDetector( 1016):     d2  c0c0c0c0c0c0c03c  d3  0102020202020213
D/CrashAnrDetector( 1016):     d4  0040404040404040  d5  0004000400040004
D/CrashAnrDetector( 1016):     d6  0000000000000000  d7  0003000400040004
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector( 1016):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector( 1016):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector( 1016):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector( 1016):     d24 4000404040404040  d25 0040404040404040
D/CrashAnrDetector( 1016):     d26 0f0f0f0f0f0f0f0f  d27 0f0f0f0f0f0f0f0f
D/CrashAnrDetector( 1016):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector( 1016):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector( 1016):     scr 20000013
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 0009230c  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1016):     #01 pc 00092387  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          a37a8f70  00000000  
D/CrashAnrDetector( 1016):          a37a8f74  00000000  
D/CrashAnrDetector( 1016):          a37a8f78  00000000  
D/CrashAnrDetector( 1016):          a37a8f7c  00000000  
D/CrashAnrDetector( 1016):          a37a8f80  00000000  
D/CrashAnrDetector( 1016):          a37a8f84  00000000  
D/CrashAnrDetector( 1016):          a37a8f88  00000000  
D/CrashAnrDetector( 1016):          a37a8f8c  00000000  
D/CrashAnrDetector( 1016):          a37a8f90  00000000  
D/CrashAnrDetector( 1016):          a37a8f94  00000000  
D/CrashAnrDetector( 1016):          a37a8f98  00000000  
D/CrashAnrDetector( 1016):          a37a8f9c  00000000  
D/CrashAnrDetector( 1016):          a37a8fa0  00000000  
D/CrashAnrDetector( 1016):          a37a8fa4  00000000  
D/CrashAnrDetector( 1016):          a37a8fa8  00000000  
D/CrashAnrDetector( 1016):          a37a8fac  00000000  
D/CrashAnrDetector( 1016):          a37a8fb0  00000000  
D/CrashAnrDetector( 1016):          a37a8fb4  00000000  
D/CrashAnrDetector( 1016):          a37a8fb8  00000000  
D/CrashAnrDetector( 1016):          a37a8fbc  00000000  
D/CrashAnrDetector( 1016):          a37a8fc0  00000000  
D/CrashAnrDetector( 1016):          a37a8fc4 , 00000000  
D/CrashAnrDetector( 1016):          a37a8fc8  00000000  
D/CrashAnrDetector( 1016):          a37a8fcc  00000000  
D/CrashAnrDetector( 1016):          a37a8fd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a8fd4  00000000  
D/CrashAnrDetector( 1016):          a37a8fd8  00000000  
D/CrashAnrDetector( 1016):          a37a8fdc  00000000  
D/CrashAnrDetector( 1016):          a37a8fe0  00000000  
D/CrashAnrDetector( 1016):          a37a8fe4  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a8fe8  e3a070ad  
D/CrashAnrDetector( 1016):          a37a8fec  ef9000ad  
D/CrashAnrDetector( 1016):     #00  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          ........  ........
D/CrashAnrDetector( 1016):     #01  a37a8ff0  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a8ff4  00000000  
D/CrashAnrDetector( 1016):          a37a8ff8  00000000  
D/CrashAnrDetector( 1016):          a37a8ffc  00000000  
D/CrashAnrDetector( 1016):          a37a9000  00000000  
D/CrashAnrDetector( 1016):          a37a9004  00000000  
D/CrashAnrDetector( 1016):          a37a9008  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a900c  73592770  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a9010  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1016):          a37a9014  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a9018  12e00890  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1016):          a37a901c  7616633d  /system/framework/arm/boot.oat
D/CrashAnrDetector( 1016):          a37a9020  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a9024  00000000  
D/CrashAnrDetector( 1016):          a37a9028  00000000  
D/CrashAnrDetector( 1016):          a37a902c  00000000  
D/CrashAnrDetector( 1016):          a37a9030  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a9034  00000000  
D/CrashAnrDetector( 1016):          a37a9038  710804a8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a903c  735927c8  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1016):          a37a9040  133c2fc0  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector( 1016):          a37a9044  73
D/CrashAnrDetector( 1016): processName:com.test.thalitest
,D/CrashAnrDetector( 1016): broadcastEvent : null SYSTEM_TOMBSTONE
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/Settings( 1282): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SettingsProvider( 1016): name = block_emergency_message
,D/SettingsProvider( 1016): name = safetycare_geolookout_registering
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/ActivityManager( 1016): Killing 1193:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/CrashAnrDetector( 1016): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
D/CrashAnrDetector( 1016): Hardware: MSM8916
D/CrashAnrDetector( 1016): Revision: 2
D/CrashAnrDetector( 1016): Bootloader: A500FUXXU1BOH2
D/CrashAnrDetector( 1016): Radio: unknown
D/CrashAnrDetector( 1016): Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1016): Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
D/CrashAnrDetector( 1016): Revision: '2'
D/CrashAnrDetector( 1016): ABI: 'arm'
D/CrashAnrDetector( 1016): pid: 2458, tid: 2624, name: Thread-256  >>> com.example.hello <<<
D/CrashAnrDetector( 1016): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1016):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1016):     r4 9dddde78  r5 9dddde38  r6 b8adc500  r7 9dddde38
D/CrashAnrDetector( 1016):     r8 00000000  r9 9dddde74  sl 9dddf3d0  fp 9dddde1c
D/CrashAnrDetector( 1016):     ip 9d93cba0  sp 9dddde00  lr 9d643308  pc b6f2d468  cpsr 600d0030
D/CrashAnrDetector( 1016):     d0  513802003a373ed5  d1  0000b80c030000a1
D/CrashAnrDetector( 1016):     d2  88000000560a109d  d3  0000003502000060
D/CrashAnrDetector( 1016):     d4  0000008849000000  d5  0a0e000000b80c0c
D/CrashAnrDetector( 1016):     d6  01003a0f0000003d  d7  0000885103000057
D/CrashAnrDetector( 1016):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1016):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1016):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1016):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1016):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1016):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1016):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1016):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1016):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1016):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1016):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1016):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1016):     scr 20000012
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): backtrace:
D/CrashAnrDetector( 1016):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1016):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1016): 
D/CrashAnrDetector( 1016): stack:
D/CrashAnrDetector( 1016):          9ddddd80  00000000  
D/CrashAnrDetector( 1016):          9ddddd84  00000000  
D/CrashAnrDetector( 1016):          9ddddd88  9cd2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1016):          9ddddd8c  e8bc0f76  
D/CrashAnrDetector( 1016):          9ddddd90  9dddddbc  [stack:2624]
D/CrashAnrDetector( 1016):          9ddddd94  9dddde64  [stack:2624]
D/CrashAnrDetector( 1016):          9ddddd98  b8adc500  [heap]
D/CrashAnrDetector( 1016):          9ddddd9c  00000003  
D/CrashAnrDetector( 1016):          9ddddda0  9ddddddc  [stack:2624]
D/CrashAnrDetector( 1016):          9ddddda4  b8b162a8  [heap]
D/CrashAnrDetector( 1016):          9ddddda8  9cd53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1016):          9dddddac  9da11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1016):          9dddddb0  00000000  
D/CrashAnrDetector( 1016):          9dddddb4  ffffff82  
D/CrashAnrDetector( 1016):          9dddddb8  00000000  
D/CrashAnrDetector( 1016):          9dddddbc  ffffff82  
D/CrashAnrDetector( 1016):          9dddddc0  9cd2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1016):          9dddddc4  b8b132a8  [heap]
D/CrashAnrDetector( 1016):,          9dddddc8  b8bcbd18  [heap]
D/CrashAnrDetector( 1016):          9dddddcc  00000001  
D/CrashAnrDetector( 1016):          9dddddd0  9cd49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1016):          9dddddd4  b8adc500  [heap]
D/CrashAnrDetector( 1016):          9dddddd8  9cd4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1016):          9ddddddc  00000000  
D/CrashAnrDetector( 1016):          9ddddde0  00000000  
D/CrashAnrDetector( 1016):          9ddddde4  00000000  
D/CrashAnrDetector( 1016):          9ddddde8  00000003  
D/CrashAnrDetector( 1016):          9dddddec  000000aa  
D/CrashAnrDetector( 1016):          9dddddf0  0000006b  
D/CrashAnrDetector( 1016):          9dddddf4  0001416e  
D/CrashAnrDetector( 1016):          9dddddf8  00000000  
D/CrashAnrDetector( 1016):          9dddddfc  9dddde30  [stack:2624]
D/CrashAnrDetector( 1016):     #00  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1016):          ........  ........
D/CrashAnrDetector( 1016):     #01  9dddde00  9dddde78  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde04  00000000  
D/CrashAnrDetector( 1016):          9dddde08  9dddde78  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde0c  9dddde5c  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde10  9dddde48  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde14  00000000  
D/CrashAnrDetector( 1016):          9dddde18  9dddee94  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde1c  9d61a3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1016):          9dddde20  9dddde50  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde24  00000000  
D/CrashAnrDetector( 1016):          9dddde28  9dddde44  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde2c  9d44c184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1016):          9dddde30  00000000  
D/CrashAnrDetector( 1016):          9dddde34  00000000  
D/CrashAnrDetector( 1016):          9dddde38  b6f73de4  
D/CrashAnrDetector( 1016):          9dddde3c  00000000  
D/CrashAnrDetector( 1016):          9dddde40  9ddde1cc  [stack:2624]
D/CrashAnrDetector( 1016):          9dddde44  9d528b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1016):          9dddde48  b8adc500  [heap]
D/CrashAnrDetector( 1016):          9dddde4c  b8adc500  [heap]
D/CrashAnrDetector( 1016):          9dddde50  b8bcbd18  [heap]
D/CrashAnrDetector( 1016):          9dddde54  00000001  
D/CrashAnrDetector( 1016):          9dddde58  9
D/CrashAnrDetector( 1016): processName:com.example.hello
D/CrashAnrDetector( 1016): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_1193/cgroup.procs: No such file or directory
,D/[LPC]   ( 1016): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2687): MountEmulatedStorage()
E/Zygote  ( 2687): v2
I/libpersona( 2687): KNOX_SDCARD checking this for 1000
I/libpersona( 2687): KNOX_SDCARD not a persona
I/SELinux ( 2687): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2687 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2687): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2687): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2687): TimaSignature is unavailable
,D/ActivityThread( 2687): Added TimaKeyStore provider
,W/ResourcesManager( 2687): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,E/SmartFaceService( 1016): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1016): no icon
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1016): [SO] activate (ident=0xb9075d00, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/SmartFaceService( 1016): mActiveServiceType: 0
E/SmartFaceService( 1016): mLightIntensityEnough: true mLux: 0.0
I/i       ( 1016): No model
,D/Stay/Rotation Worker( 1016): updateClientsDone. def. do nothing.
E/SmartFaceService( 1016): Service Type to Worker: 0
,E/SmartFaceService( 1016): Last Active clients:0 Current Active clients: 0
E/SmartFaceService( 1016): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/FactoryTest( 1016): Not factory mode
D/FactoryTest( 1016): Not factory mode. isFactoryMode() returend false
D/w       ( 1016): isUserBuild = true
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SSRM:aZ ( 1016): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1016): Updating Threshold Value.. isSystemReady: true
,D/SensorService( 1016): [SO] changed settle time [0]
,D/SensorService( 1016): [SO] setDelay [200000000]
,D/SensorService( 1016): [SO] activate (ident=0xb8f6dc28, enabled=1)
,D/SensorService( 1016): [SO] AR_init
,I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,V/AlarmManagerEXT( 1016): mGmsLocationBundling: false
,I/ActivityManager( 1016): Killing 1392:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/SSRM:n  ( 1016): SIOP:: AP = 350
,D/RCPManagerService( 1016): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1016):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/RCPManagerService( 1016): BootReceiver.onReceive(): Starting RCP Proxy for user = null
,E/RCPManagerService( 1016):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000,
D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1016): [SO] activate (ident=0xb8f6dc28, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1016): [SO] changed settle time [1]
,D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb8f6dc28, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
W/libprocessgroup( 1016): failed to open /acct/uid_10096/pid_1392/cgroup.procs: No such file or directory
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/EnterpriseDeviceManagerService( 1016): android.intent.action.BOOT_COMPLETED
,V/ApplicationPolicy( 1016): boot completed - refreshWidgetStatus
,V/ApplicationPolicy( 1016): refresh widget status for user 0
,D/EnterpriseDeviceManagerService( 1016): runAdminUpdate
,D/EnterpriseUtils( 1016): File Not Found : /data/system/selfUpdateAdmin.conf
,D/EnterpriseDeviceManagerService( 1016): nothing to selfUpdate
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,W/PhoneRestrictionPolicy( 1016): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1016): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,W/PhoneRestrictionPolicy( 1016):  >>>> deliveryBlockedMsgs
,I/KnoxMUMContainerPolicy( 1016): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1016): cvList size 0
W/PhoneRestrictionPolicy( 1016):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1016): cvList size 0
,D/WifiP2pService( 1016): P2pDisabledState{ what=143415 }
,D/WifiP2pService( 1016): DefaultState{ what=143415 }
,D/ConnectivityService( 1016): Got NetworkFactory Messenger for WIFI_P2P
,D/ConnectivityService( 1016): Got NetworkFactory Messenger for WIFI
,D/WIFI_P2P( 1016): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/Tethering( 1016): Boot complete.
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/WifiStateMachine( 1016): Blacklist file delete
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,V/EnterpriseBillingEngine( 1016): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1016): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1016): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1016): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1016): handleAllprofiles - end
,D/UsbHostNotification( 1016): boot completed
,D/UsbHostRestrictor( 1016): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1016): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1016): SIM was never inserted,
D/UsbHostRestrictor( 1016): writableHostSysNode[false]
D/UsbHostRestrictor( 1016): Can NOT Write Disable Sys Node to [ON]
,W/CursorWrapperInner( 2279): Cursor finalized without prior close()
,D/SensorService( 1016): [SO] 0.096 0.383 10.094
,D/SensorService( 1016): [SO] [100 -> 255]
,D/WIFI    ( 1016): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/PersonaManagerService( 1016): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1016):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/KnoxKeyguardUpdateMonitor( 1016): onBootComplete
,D/UsbStorageNotification( 1016): boot completed
,I/KnoxKeyguardUpdateMonitor( 1016): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1016): onTrustChanged user:0, enable:false
,D/KeyguardViewMediator( 1180): onTrustChanged( Showing = false , userId = 0 )
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1016): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1016): set_capabilities_callback: 55u
E/USB_UICC(  296): Timeout! No signal received. Retry num = 26
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/libmdmdetect( 1016): ESOC framework not supported
,I/libmdmdetect( 1016): Found internal modem: modem
E/PerMgrLib( 1016): Peripheral manager is not supported on this device
,E/Geofence_Adapter( 1016): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 ,
E/Geofence_Adapter( 1016): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1016): BOOT_COMPLETED native_cleanup 
D/qmi_secgps_clnt( 1016): qmi_secgps_client_init()
,D/StorageNotification( 1180): boot completed,
,D/qmi_secgps_clnt( 1016): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/StatusBarManagerService( 1016): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/PhoneStatusBar( 1180): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1016): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,D/qmi_secgps_clnt( 1016): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,D/qmi_secgps_clnt( 1016): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2720): MountEmulatedStorage()
E/Zygote  ( 2720): v2
I/libpersona( 2720): KNOX_SDCARD checking this for 10099
I/SELinux ( 2720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 2720): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2720 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2720): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2720): TimaSignature is unavailable
,D/ActivityThread( 2720): Added TimaKeyStore provider
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 1554:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_1554/cgroup.procs: No such file or directory
,E/ActivityThread( 2720): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2720): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1016): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1016): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/ActivityManager( 1016): Killing 1536:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/DrmEventReceiver( 1016): DrmEventReceiver : onReceive
,I/DrmEventReceiver( 1016): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1016): DrmEventReceiver : beginStartingService
I/System.out( 1016): start Service
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/DownloadManager( 1226): onReceive intent + android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 2737): MountEmulatedStorage()
,E/Zygote  ( 2737): v2
I/libpersona( 2737): KNOX_SDCARD checking this for 1000
,I/libpersona( 2737): KNOX_SDCARD not a persona
,I/SELinux ( 2737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2737 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
E/SELinux ( 2737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/LocSvc_utils_cfg( 1016): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,D/TimaKeyStoreProvider( 2737): TimaSignature is unavailable
,D/ActivityThread( 2737): Added TimaKeyStore provider
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02,
I/qmi_secgps_clnt( 1016): SECGPS: Set AGPS Mode : 7
I/libpersona( 2747): KNOX_SDCARD checking this for 10152,
E/Zygote  ( 2747): MountEmulatedStorage()
I/libpersona( 2747): KNOX_SDCARD not a persona
E/Zygote  ( 2747): v2
,I/SELinux ( 2747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2747 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:android, calleePkgName: android
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/SELinux ( 2747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
E/SELinux ( 2747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1016): SECGPS: Set XTRA enable : 1
,W/ResourcesManager( 2737): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
,I/qmi_secgps_clnt( 1016): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1016): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1016): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 1432
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 1432
,D/MediaScannerReceiver( 1226): action: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 2747): TimaSignature is unavailable
,D/ActivityThread( 2747): Added TimaKeyStore provider
,D/BluetoothBDAdrressReceiver( 2737): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 2737): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/SensorService( 1016): [SO] 0.096 0.402 10.094
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,I/DrmEventService( 1016): action event :android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/TimaServiceEventReceiver( 1016): TimaServiceEventReceiver : onReceive
,W/ResourcesManager( 1449): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
D/BluetoothBDTestService( 1449): onCreate()
,E/BluetoothBDTestService( 1449): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1449): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1449): already exist!( /efs/bluetooth/bt_addr ), file length: 17
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2772): MountEmulatedStorage()
E/Zygote  ( 2772): v2
I/libpersona( 2772): KNOX_SDCARD checking this for 1000
I/libpersona( 2772): KNOX_SDCARD not a persona
,I/SELinux ( 2772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1016): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1016): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2772 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/LocSvc_ApiV02( 1016): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
I/ActivityManager( 1016): Killing 1902:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/SELinux ( 2772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2772): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/CscReceiver( 1449): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,E/SQLiteLog( 2747): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2772): TimaSignature is unavailable
,D/ActivityThread( 2772): Added TimaKeyStore provider
,D/CscUpdateService( 1449): onStart
E/CscUpdateService( 1449): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1449): set_CSC_version
E/Zygote  ( 2786): MountEmulatedStorage()
I/libpersona( 2786): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2786): v2
I/libpersona( 2786): KNOX_SDCARD not a persona
E/CscParser( 1449): update(): xml file exist
,I/SELinux ( 2786): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2786 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 2786): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2786): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
I/CscUtil ( 1449): isWifiOnly = false
,I/System.out( 1449): HandDataNode = null
I/CscUpdateService( 1449): PATH_CSCNAME =CustomerDataSet.CSCName
D/MediaScannerService( 1226): !@start scanning volume internal: [/system/media, /oem/media]
,I/CscUpdateService( 1449): This is normal boot : CSC not updated
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_1536/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10138/pid_1902/cgroup.procs: No such file or directory
,W/ResourcesManager( 2772): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/CscUpdateService( 1449): same CSC Version
,D/CscUtil ( 1449): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,D/TimaKeyStoreProvider( 2786): TimaSignature is unavailable
E/CscParser( 1449): update(): xml file exist
D/ActivityThread( 2786): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,D/CscGPS  ( 1449): CSCGPS.updateParameters
D/CscGPS  ( 1449): supl host : null
,D/CscGPS  ( 1449): SUPL Host is null or invalid
D/CscGPS  ( 1449): supl_ver : null
D/CscGPS  ( 1449): SUPL Ver is null or invalid
D/CscGPS  ( 1449): supl port : null
D/CscGPS  ( 1449): SUPL PORT is null or invalid
D/CscGPS  ( 1449): LPP : null
D/CscGPS  ( 1449): LPP is null or invalid
D/CscGPS  ( 1449): CSC don't have any AGPS value.
,D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
,E/Zygote  ( 2807): MountEmulatedStorage()
I/libpersona( 2807): KNOX_SDCARD checking this for 1101
E/Zygote  ( 2807): v2
I/libpersona( 2807): KNOX_SDCARD not a persona
I/SELinux ( 2807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2807 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
D/TP/MmsProvider( 1449): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1449): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
,I/Mms:transaction( 2279): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2279): [start]    nonBlockingUpdateMessageIndicator() consume time = 2348.060781
,I/Mms/ReservationManager( 2279): resetAfterConnected()
,I/art     (  306): Explicit concurrent mark sweep GC freed 8774(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 24.654ms
,I/KnoxUsageLogPro( 2772): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 2279
,I/KnoxUsageLogPro( 2772): premStatus:2
,D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 1.718 ms
I/KnoxUsageLogPro( 2772): isEulaShown : false
I/KnoxUsageLogPro( 2772): KnoxUsageReceiver onReceive : not Processible, just return
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
D/Mms/MessagingNotification( 2279): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2279): isDefault true
,I/KnoxUsageLogPro( 2772): savePreference: key = previous_sys_time value = 1457533274986
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 2279
,D/TimaKeyStoreProvider( 2807): TimaSignature is unavailable
,D/ActivityThread( 2807): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 17.303ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.762ms
,E/Zygote  ( 2826): MountEmulatedStorage(),
E/Zygote  ( 2826): v2
I/libpersona( 2826): KNOX_SDCARD checking this for 10085
I/libpersona( 2826): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2826 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 1585:com.google.android.apps.maps/u0a107 (adj 15): empty #31
I/SELinux ( 2826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SQLiteLog( 1226): (283) recovered 159 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,E/SELinux ( 2826): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Mms/ReservationManager( 2279): getReservedSendMessageCount(): retMessageCount=0
,D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/ResourcesManager( 2807): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 2772): savePreference: key = previous_elapsed_time value = 33336
,D/TP/MmsSmsProvider( 1449): query,matched:200, calling pid = 2279
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1449): match 200:Elapsed time : 7.651 ms,
,D/TimaKeyStoreProvider( 2826): TimaSignature is unavailable
D/ActivityThread( 2826): Added TimaKeyStore provider
V/SmartcardService( 2807): main Received broadcast
V/SmartcardService( 2807): Starting smartcard service after boot completed
,E/Zygote  ( 2841): MountEmulatedStorage(),
E/Zygote  ( 2841): v2
I/libpersona( 2841): KNOX_SDCARD checking this for 10048
,I/libpersona( 2841): KNOX_SDCARD not a persona
I/SELinux ( 2841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2841 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 2841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MediaScanner( 1226): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/ActivityManager( 1016): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1016): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,I/ActivityManager( 1016): Killing 2094:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1016): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2826): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2826): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2826): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2826): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2826): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2826): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/SecureStorage( 2786): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/TimaKeyStoreProvider( 2841): TimaSignature is unavailable
,D/ActivityThread( 2841): Added TimaKeyStore provider
,E/Zygote  ( 2862): MountEmulatedStorage()
E/Zygote  ( 2862): v2
I/libpersona( 2862): KNOX_SDCARD checking this for 10157
I/libpersona( 2862): KNOX_SDCARD not a persona
,I/SELinux ( 2862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2862 uid=10157 gids={50157, 9997} abi=armeabi-v7a
I/SecureStorage( 2786): [INFO]: SPID(0x00000000)This device supports Secure Storage,
E/SELinux ( 2862): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/MediaScanner( 1226): processDirectory :  /system/media
I/SecureStorage(  361): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2786
,I/SecureStorage(  361): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2786): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2786): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  361): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2786
I/SecureStorage(  361): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/Mms/SmsReceiverService( 2279): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/Mms/TelephonyPermission( 2279): isDefault true
D/Mms/SmsReceiverService( 2279): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2279): [start]    handleBootCompleted() consume time = 184.246302
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
D/TimaKeyStoreProvider( 2862): TimaSignature is unavailable
,D/ActivityThread( 2862): Added TimaKeyStore provider
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2279
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 1.233 ms
,W/ResourcesManager( 2841): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2841): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
V/MediaScanner( 1226):  prescan time: 161ms (DB items: 141)
V/MediaScanner( 1226):     scan time: 38ms (Caching mode: true), (makeEntry time: 23ms ~60%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 199ms
,V/MediaScanner( 1226): checked files: 133  directories : 6  (I: 0, U: 0)
,D/MediaScanner( 1226): checkDefaultSounds
D/MediaScanner( 1226): system alarm_alert  : Vwiurug_etwofi5wgg
,E/Zygote  ( 2877): MountEmulatedStorage()
E/Zygote  ( 2877): v2
I/libpersona( 2877): KNOX_SDCARD checking this for 1000
I/libpersona( 2877): KNOX_SDCARD not a persona
I/SELinux ( 2877): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2877 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2877): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2877): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1449): query,matched:51, calling pid = 2279
W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_1585/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_2094/cgroup.procs: No such file or directory
D/MediaScanner( 1226): OK. alarm_alert is already exist in setting DB.
,D/TP/SmsProvider( 1449): match 51:Elapsed time : 2.886 ms
D/MediaScanner( 1226): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1226): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1226): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/MediaScanner( 1226): OK. ringtone is already exist in setting DB.
,W/ResourcesManager( 2862): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 2279): isBlockingModeEnabled() = false, Zen mode = 0
D/MediaScannerService( 1226): !@done scanning volume internal
,D/TimaKeyStoreProvider( 2877): TimaSignature is unavailable
D/MediaScannerService( 1226): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/FactoryTestApp( 2615): [DummyFtClient$mBroadcastReceiver](2615) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2615): [DummyFtClient$mBroadcastReceiver](2615) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/TP/MmsSmsProvider( 1449): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775806
D/FactoryTestApp( 2615): [DummyFtClient$mBroadcastReceiver](2615) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/ActivityThread( 2877): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775806
,V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
,D/Mms/Conversation( 2279): deleteTempConversation(),deleted=0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1016): name = block_emergency_message
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
D/SettingsProvider( 1016): selectionArgs: 10048
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
D/SmsProvider( 1449): Update uri=content://sms/outbox, match=8
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1226): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,E/Zygote  ( 2893): MountEmulatedStorage(),
E/Zygote  ( 2893): v2
I/libpersona( 2893): KNOX_SDCARD checking this for 10159
I/libpersona( 2893): KNOX_SDCARD not a persona
I/SELinux ( 2893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2893): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2893 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 1485:com.android.printspooler/u0a136 (adj 15): empty #31
W/ActivityManager( 1016): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/Mms/SmsReceiverService( 2279): moveOutboxMessagesToFailedBox messageCount: 0
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/Mms/SmsReceiverService( 2279): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2279): [SIM-1]sendFirstQueuedMessage()
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1449): query,matched:26, calling pid = 2279
,D/TimaKeyStoreProvider( 2893): TimaSignature is unavailable
,D/ActivityThread( 2893): Added TimaKeyStore provider
,E/Zygote  ( 2909): MountEmulatedStorage()
E/Zygote  ( 2909): v2
I/libpersona( 2909): KNOX_SDCARD checking this for 10072
I/libpersona( 2909): KNOX_SDCARD not a persona
,I/SELinux ( 2909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TP/SmsProvider( 1449): match 26:Elapsed time : 12.157 ms
,I/SELinux ( 2909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=2909 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/SELinux ( 2909): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/MediaScanner( 1226): processDirectory :  /storage/emulated/0
,E/SQLiteLog( 2877): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(75ebcf7
,D/TimaKeyStoreProvider( 2909): TimaSignature is unavailable
,D/ActivityThread( 2909): Added TimaKeyStore provider
D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ActivityManager( 1016): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/Mms/SmsReceiver( 2279): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2279): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2279): isDefault true
,I/WifiCredService( 1282): onCreate
V/MediaScanner( 1226): processDirectory :  /storage/extSdCard
W/MediaScanner( 1226): Error opening directory, reason : Permission denied.
W/MediaScanner( 1226): 7klwibgf7fxlKdCbid7
,W/libprocessgroup( 1016): failed to open /acct/uid_10136/pid_1485/cgroup.procs: No such file or directory
,D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 2279
,I/Intent to TravelDirActivity( 2893): inside TravelBroadcastReceiver
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 27
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 42436(2MB) AllocSpace objects, 32(2MB) LOS objects, 33% free, 25MB/38MB, paused 2.283ms total 147.263ms
,D/DSM     ( 2877): [Lines:107] Normal booted
,D/DSM     ( 2877): [Lines:114] Boot completed
,D/WifiTimerReceiver( 1282): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1282): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1282): Action boot completed received
,V/MediaScanner( 1226):  prescan time: 66ms (DB items: 27)
V/MediaScanner( 1226):     scan time: 24ms (Caching mode: true), (makeEntry time: 16ms ~66%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 170ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1226):    total time: 260ms
V/MediaScanner( 1226): checked files: 10  directories : 17  (I: 0, U: 0)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,D/SettingsProvider( 1016): name = next_alarm_formatted
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10085,
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/Zygote  ( 2927): MountEmulatedStorage()
I/libpersona( 2927): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2927): v2
I/libpersona( 2927): KNOX_SDCARD not a persona
,I/SELinux ( 2927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/BadgeProvider( 2909): onCreate
,E/SELinux ( 2927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BadgeProvider( 2909): DatabaseHelper
,I/ActivityManager( 1016): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2927 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2127:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/MediaScannerService( 1226): !@done scanning volume external
,I/ActivityManager( 1016): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 2191:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,E/Zygote  ( 2938): MountEmulatedStorage()
I/libpersona( 2938): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2938): v2
I/libpersona( 2938): KNOX_SDCARD not a persona
,I/SELinux ( 2938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TP/MmsSmsProvider( 1449): query,matched:200, calling pid = 2279
I/SELinux ( 2938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TP/MmsSmsProvider( 1449): match 200:Elapsed time : 1.058 ms
E/SELinux ( 2938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 2909): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 2927): TimaSignature is unavailable
D/NearbySettings( 1282): MountReceiver.onReceive - Create HandlerThread
D/ActivityThread( 2927): Added TimaKeyStore provider
D/NearbySettings( 1282): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1282): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1282): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1016): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
V/NearbySettings( 1282): MountReceiver.mPrefHandler - 7002
,D/TimaKeyStoreProvider( 2938): TimaSignature is unavailable
,D/ActivityThread( 2938): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/NearbySettings( 1282): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1282): MountReceiver.onReceive - Internal Path
,W/ResourcesManager( 2927): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/SettingsProvider( 1016): name = personal_mode_enabled
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2279
,D/FactoryTestApp( 2615): [DummyFtClient$mBroadcastReceiver](2615) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2615): [DummyFtClient$mBroadcastReceiver](2615) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2615): [DummyFtClient$sendBootCompletedAndFinish](2615) ...
D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2615): [ModuleCommon$isConnectionModeNone](2615) mConnectionMode = gsm
,D/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$ResponseWriter](2615) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$connectToSecPhoneService](2615)  
W/ContextImpl( 2615): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,D/ActivityManager( 1016): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 20.031 ms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 2909): sendNotify entered. [uri] : content://com.sec.badge/apps/2,
D/BadgeProvider( 2909): sendNotify, [notify] : null
D/BadgeProvider( 2909): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2909): update, [BadgeCount] : badgecount=0,
D/BadgeProvider( 2909): update, [UpdateCount] : 1,
,D/Launcher.Model( 1469): reloadBadges entered.
,W/ActivityThread( 2927): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat,
,I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2959 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,D/Mms/MessagingNotification( 2279): setBadgeCount(), count=0
,E/Zygote  ( 2959): MountEmulatedStorage()
E/Zygote  ( 2959): v2
I/libpersona( 2959): KNOX_SDCARD checking this for 10160
I/libpersona( 2959): KNOX_SDCARD not a persona
,I/SELinux ( 2959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification( 2279): remove alarm
W/ResourcesManager( 1449): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1449): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$onServiceConnected](2615) connected done
D/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$write](2615) Send Response Message to SecPhone
D/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$write](2615) Response ��
,W/libprocessgroup( 1016): failed to open /acct/uid_10050/pid_2127/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10113/pid_2191/cgroup.procs: No such file or directory
,W/art     ( 2826): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 188.067ms
,D/TimaKeyStoreProvider( 2959): TimaSignature is unavailable
D/ActivityThread( 2959): Added TimaKeyStore provider
,D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2279
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 2.268 ms
,I/SmartcardBootCompleteReceiver( 1282): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1282): Received intent with action - android.intent.action.BOOT_COMPLETED
,I/art     ( 1449): Background sticky concurrent mark sweep GC freed 39530(2MB) AllocSpace objects, 11(176KB) LOS objects, 24% free, 8MB/11MB, paused 5.356ms total 98.026ms
,D/Mms/MessagingNotification( 2279): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 2279): [end]    nonBlockingUpdateMessageIndicator() consume time = 627.943385
,I/ActivityManager( 1016): Killing 1596:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SmartcardBootCompleteReceiver( 1282): Broadcast sent with current lockscreen type
,D/AT_Distributor(  311): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,D/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$handleMessage](2615) Send BOOTING COMPLETED done
,D/TP/SmsProvider( 1449): query,matched:51, calling pid = 2279
W/ResourcesManager( 2959): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME,
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE,
I/SecureStorage(  361): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
D/TP/SmsProvider( 1449): match 51:Elapsed time : 44.055 ms
,D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
,D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2927): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,D/[SBeam] ( 1282): SBeamEnabler.initPreferenceForSbeam : 0
D/Mms/MessagingNotification( 2279): isBlockingModeEnabled() = false, Zen mode = 0
,I/LcdtestApp( 2927): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
D/AT_Distributor(  311): SetAtdStatus(), 1_1_0
D/AT_Distributor(  311): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 2786): [INFO]: SPID(0x00000001)Processing data has been completed
,I/SecureStorage( 2786): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
,E/Zygote  ( 2981): MountEmulatedStorage()
,E/Zygote  ( 2981): v2
I/libpersona( 2981): KNOX_SDCARD checking this for 1000
,I/libpersona( 2981): KNOX_SDCARD not a persona
,I/SELinux ( 2981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2981 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SettingSearch/SearchIntentReceiver( 1282): action : android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1016): Killing 2260:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/SettingSearch/SearchIntentReceiver( 1282): search setting db init!!
E/SELinux ( 2981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_1596/cgroup.procs: No such file or directory
,I/SettingSearch/SearchIntentReceiver( 1282): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/BadgeProvider( 2909): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 2981): TimaSignature is unavailable
,D/ActivityThread( 2981): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2997): MountEmulatedStorage()
,E/Zygote  ( 2997): v2
I/libpersona( 2997): KNOX_SDCARD checking this for 1000
I/libpersona( 2997): KNOX_SDCARD not a persona
,I/SELinux ( 2997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2997 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2997): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2997): TimaSignature is unavailable
D/ActivityThread( 2997): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 21.770ms
,D/Launcher.Model( 1469): reloadBadges entered.
D/BadgeProvider( 2909): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2909): sendNotify, [notify] : null
D/BadgeProvider( 2909): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2909): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2909): update, [UpdateCount] : 1
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 596us total 16.658ms
,D/[0]UMC:UMCContentProvider( 2959): @onCreate
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 592us total 16.741ms
,E/Zygote  ( 3012): MountEmulatedStorage(),
E/Zygote  ( 3012): v2
I/libpersona( 3012): KNOX_SDCARD checking this for 10150
I/libpersona( 3012): KNOX_SDCARD not a persona,
I/SELinux ( 3012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3012 uid=10150 gids={50150, 9997} abi=armeabi-v7a
E/SELinux ( 3012): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2260/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 2279): setBadgeCount(), count=0
,W/ResourcesManager( 2997): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 2279): remove alarm
,D/Mms/MessagingNotification( 2279): updateAllHistoryAsRead()
,D/[0]UMC:Core( 2959): onCreate(): 
D/[0]UMC:Core( 2959): @isManagedProfileUser
D/[0]UMC:Core( 2959): userId: 0
,D/[0]UMC:Core( 2959): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2959): userInfo.isManagedProfile() : false
,D/TimaKeyStoreProvider( 3012): TimaSignature is unavailable
,D/ActivityThread( 3012): Added TimaKeyStore provider
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2279
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 6.320 ms
,I/DIAGMON_AGENT( 2981): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/Mms/SmsReceiverService( 2279): [end]    handleBootCompleted() consume time = 314.539114
,I/ActivityManager( 1016): Killing 2302:com.sec.android.omc/1000 (adj 15): empty #31
,D/[0]UMC:DeviceInfo( 2959): USA==US==
,I/FOTA    ( 2997): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2302/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,E/Zygote  ( 3031): MountEmulatedStorage()
,I/libpersona( 3031): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3031): v2
I/libpersona( 3031): KNOX_SDCARD not a persona
I/SELinux ( 3031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3031): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3031 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2332:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3031): TimaSignature is unavailable
,D/ActivityThread( 3031): Added TimaKeyStore provider
,E/SMD     (  288): DCD OFF
,W/ResourcesManager( 3031): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/BluetoothHeadset( 2786): BTStateChangeCB is registed
,D/BluetoothHeadset( 2786): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2786): BluetoothHeadset service is binded
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/BluetoothA2dp( 2786): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1016): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 28
,D/BluetoothAdapter( 2786): 285487398: getState() :  mService = null. Returning STATE_OFF
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2332/cgroup.procs: No such file or directory
D/BluetoothAdapter( 2786): 285487398: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2786): 285487398: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2786): 285487398: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2786): 285487398: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager( 1016): Killing 2354:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,I/DBG_DM  ( 2997): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2997): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1016): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DIAGMON_AGENT( 2981): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DBG_DM  ( 2997): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 2997): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,E/Zygote  ( 3048): MountEmulatedStorage()
I/libpersona( 3048): KNOX_SDCARD checking this for 10086
E/Zygote  ( 3048): v2
I/libpersona( 3048): KNOX_SDCARD not a persona
,I/SELinux ( 3048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/DBG_DM  ( 2997): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DIAGMON_AGENT( 2981): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/SELinux ( 3048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
E/SELinux ( 3048): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DIAGMON_AGENT( 2981): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 2981): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 2981): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 2981): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver,
,I/DBG_DM  ( 2997): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On,
I/ActivityManager( 1016): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3048 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2252:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/USER_AGENT( 2959): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,D/TimaKeyStoreProvider( 3048): TimaSignature is unavailable,
D/ActivityThread( 3048): Added TimaKeyStore provider
,D/OverheatReceiver( 1180): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1180): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1180): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1180): isSafeMode = false
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
D/BootupListener( 1449): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1016): name = internet_call_settings_visibility
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1016): selectionArgs: false
D/[0]UMC:AdminManager( 2959): init - start
D/SettingsProvider( 1016): selectionArgs: 1001
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/PhoneUtilsCommon( 1449): isSupportVoLTE is false.
,I/Telecom ( 1424): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,D/ActivityManager( 1016): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_2354/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2252/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 2997): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,D/ActivityManager( 1016): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2997): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_DM  ( 2997): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,W/ContextImpl( 2997): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!,
D/[0]UMC:AdminManager( 2959): loadAdmins
I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,E/Zygote  ( 3063): MountEmulatedStorage()
,I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3063 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,E/Zygote  ( 3063): v2,
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
I/libpersona( 3063): KNOX_SDCARD checking this for 10057,
I/libpersona( 3063): KNOX_SDCARD not a persona
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3063): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3074): MountEmulatedStorage()
,E/Zygote  ( 3074): v2
I/libpersona( 3074): KNOX_SDCARD checking this for 1000
I/libpersona( 3074): KNOX_SDCARD not a persona
,I/SELinux ( 3074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3074 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1016): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/SELinux ( 3074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Telecom ( 1424): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,D/[SBeam] ( 1282): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1282): SBeamEnabler.isSBeamSupported : EXIST
,D/TimaKeyStoreProvider( 3063): TimaSignature is unavailable
,I/DBG_DM  ( 2997): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/ActivityThread( 3063): Added TimaKeyStore provider
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,E/Tethering( 1016): No numeric data
,D/TimaKeyStoreProvider( 3074): TimaSignature is unavailable
D/ActivityThread( 3074): Added TimaKeyStore provider
D/[0]UMC:AdminManager( 2959): init - end
D/GSLBManager( 2959): migrateStoredUrlFromOldPref
,E/Tethering( 1016): No numeric data
,D/GSLBManager( 2959): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 2959): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2959): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2959): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2959): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2959): isContainer : 0
,I/DBG_DM  ( 2997): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
,V/InCall  ( 1934): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1934): ProximitySensor -  - mFromRcsShare: false
,D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
,I/InCall  ( 1934): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,E/[0]UMC:UMCAdmin( 2959): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2959): isContainer : 0
,D/ScoverManager( 1934): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1934): InCallUtils - isCoverClosed false
,I/Telecom ( 1424): ProximitySensorManager: Proximity wake lock already released
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/[0]UMC:UMCAdmin( 2959): deactivateUMCAdmin - UMC App Admin deactivated
,D/InCall  ( 1934): InCallUtils - isCoverClosed false
I/InCall  ( 1934): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1934): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,D/InCall  ( 1934): InCallPresenter -  - dismissCoverDialog()...
,D/ActivityManager( 1016): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,I/InCall  ( 1934): CallSContextMotion - stopPutDownListening
,D/[0]UMC:GuardService( 2959): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/InCall  ( 1934): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
D/[0]UMC:CoreReceiver( 2959): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2959):  check PreETag 
,D/PhoneStatusBarView( 1180): setCallBackground:0
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1934): InCallUtils - isCoverClosed false
,D/[0]UMC:CoreReceiver( 2959): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2959): Enter loadList
,D/[0]UMC:CoreReceiver( 2959): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2959): deactivateUMCAdminIfNotRequired : -1
,E/[0]UMC:Utils( 2959): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2959): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,D/[0]UMC:UMCAdmin( 2959): deactivateUMCAdmin : -1
,D/[0]UMC:UMCAdmin( 2959): isContainer : 0
,E/UpdateRequestReceiver( 3048): ignoring update request
,D/EnterpriseDeviceManagerService( 1016): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2959): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2959): isContainer : 0
,D/[0]UMC:UMCAdmin( 2959): deactivateUMCAdmin - UMC App Admin deactivated
,E/UpdateRequestReceiver( 3048): ignoring update request
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,D/[0]UMC:ByodSetupStarter( 2959): Container ID : 0
,W/NotificationAccessSettings( 1282): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/[0]UMC:Utils( 2959): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2959): shutdown
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,D/[0]UMC:GuardService( 2959): @GuardService - stopService Result = true
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,V/VibratorService( 1016): hasVibrator - useVibetonz: true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     ( 2959): System.exit called, status: 0
I/AndroidRuntime( 2959): VM exiting with result code 0, cleanup skipped.
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] ,
,W/ResourcesManager( 1282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,E/Zygote  ( 3113): MountEmulatedStorage()
I/libpersona( 3113): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3113): v2
I/libpersona( 3113): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3113 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3113): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3113): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3113): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/TimaKeyStoreProvider( 3113): TimaSignature is unavailable
I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
D/ActivityThread( 3113): Added TimaKeyStore provider
,I/ActivityManager( 1016): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2959)(adj 0) has died(306,986)
,D/VideoCallManager( 1934): Instantiating VideoCallManager
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1934): took 2.201823ms for 0*0 texture 0
,I/DBG_DM  ( 2997): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/GFX generate_partition_tables( 1934): took 5.131927ms for 0*0 texture 0
,E/UpdateRequestReceiver( 3048): ignoring update request
,I/GFX raster( 1934): took 11.568855ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8b50e48 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8b69058 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_DM  ( 2997): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
E/UpdateRequestReceiver( 3048): ignoring update request
D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1934): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1934): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1934): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1934): Local Branch: 
I/Adreno-EGL( 1934): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1934): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1934):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/UpdateRequestReceiver( 3048): ignoring update request
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/ScoverManager( 1282): serviceVersion : 16908288
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GFX GPU raster( 1934): eglCreateImageKHR: EGL_SUCCESS
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
E/Zygote  ( 3135): MountEmulatedStorage(),
E/Zygote  ( 3135): v2
I/libpersona( 3135): KNOX_SDCARD checking this for 10015
I/SELinux ( 3135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 3135): KNOX_SDCARD not a persona
,I/glCompressedTexImage2D( 1934): took 0.306615ms for 320*61440 texture 37809
,I/SELinux ( 3135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3135): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3135 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,I/DBG_POLICYDM( 3074): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1311): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,I/draw setup( 1934): took 10.948334ms for 320*240 texture 37809
E/GFX GPU raster( 1934): drawn
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 2997): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/GFX GPU raster ASTC( 1934): took 42.091040ms for 320*240 texture 12
I/GFX raster( 1934): took 42.170207ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8b69058 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8b6b398 counterpartCT=4 counterpartW=320 counterparth=240
,D/TimaKeyStoreProvider( 3135): TimaSignature is unavailable
,D/ActivityThread( 3135): Added TimaKeyStore provider
,D/comsamsunglog( 1311): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/GFX GPU raster( 1934): eglCreateImageKHR: EGL_SUCCESS
,I/DBG_POLICYDM( 3074): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false],
I/glCompressedTexImage2D( 1934): took 0.360573ms for 480*122880 texture 37813
I/draw setup( 1934): took 0.679844ms for 480*640 texture 37813
E/GFX GPU raster( 1934): drawn
,E/UpdateRequestReceiver( 3048): ignoring update request
,I/GFX GPU raster ASTC( 1934): took 7.527916ms for 480*640 texture 12
I/GFX raster( 1934): took 7.611354ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8b6b398 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8d99828 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,D/SettingsProvider( 1016): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10162
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,D/LocationManagerService( 1016): getProviders()=[passive]
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/Zygote  ( 3155): MountEmulatedStorage(),
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
E/Zygote  ( 3155): v2,
I/libpersona( 3155): KNOX_SDCARD checking this for 10092,
I/libpersona( 3155): KNOX_SDCARD not a persona
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/SELinux ( 3155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/ActivityManager( 1016): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3155 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3155): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1934): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1934): took 0.364011ms for 440*116864 texture 37809
I/draw setup( 1934): took 0.776927ms for 440*330 texture 37809
E/GFX GPU raster( 1934): drawn
,D/TimaKeyStoreProvider( 3155): TimaSignature is unavailable
I/GFX GPU raster ASTC( 1934): took 4.960990ms for 440*330 texture 12
I/GFX raster( 1934): took 5.018645ms for 440*330 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8d99828 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8dadc18 counterpartCT=4 counterpartW=440 counterparth=330
,D/ActivityThread( 3155): Added TimaKeyStore provider
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1934): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1934): took 0.493385ms for 480*163840 texture 37811
I/draw setup( 1934): took 0.900573ms for 480*640 texture 37811
E/GFX GPU raster( 1934): drawn
,I/GFX GPU raster ASTC( 1934): took 6.284219ms for 480*640 texture 12
I/GFX raster( 1934): took 6.364584ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8d9da28 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8dad750 counterpartCT=4 counterpartW=480 counterparth=640
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1408): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1408): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1180): Cable  true --> true mBootCompleted : true
,D/PowerUI ( 1180): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1934): took 2.293282ms for 0*0 texture 0
,E/daemonapp( 1311): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/GFX generate_partition_tables( 1934): took 7.393021ms for 0*0 texture 0
,I/GFX raster( 1934): took 11.721147ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8d970e8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8d97208 counterpartCT=4 counterpartW=176 counterparth=144
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457533277277
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457554860000
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,E/        ( 1934): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1934): took 2.825574ms for 0*0 texture 0
,I/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,D/daemonapp( 1311): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457554860000
,I/GFX generate_partition_tables( 1934): took 6.558229ms for 0*0 texture 0
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,I/GFX raster( 1934): took 11.849375ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1934): Bitmap=0xb8d97428 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8d973c8 counterpartCT=4 counterpartW=176 counterparth=144
D/daemonapp( 1311): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457554860000
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,D/ScoverManager( 1934): registerListener
,I/DBG_POLICYDM( 3074): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1016): registerListenerCallback : binder = android.os.BinderProxy@3c9f76e9, pid : 1934, uid : 1001, type : 1
,E/DBG_POLICYDM( 3074): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/InCall  ( 1934): InCallPresenter -  - Finished InCallPresenter.setUp
,D/comdaemonstockapp( 1311): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1311): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3183): MountEmulatedStorage(),
I/libpersona( 3183): KNOX_SDCARD checking this for 10166,
E/Zygote  ( 3183): v2
I/libpersona( 3183): KNOX_SDCARD not a persona
I/SELinux ( 3183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3183): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3183 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/ActivityManager( 1016): Killing 2449:com.wsomacp/u0a25 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 2469:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3183): TimaSignature is unavailable
,D/ActivityThread( 3183): Added TimaKeyStore provider
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 29
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3199): MountEmulatedStorage()
E/Zygote  ( 3199): v2
I/libpersona( 3199): KNOX_SDCARD checking this for 10003
I/libpersona( 3199): KNOX_SDCARD not a persona
,I/SELinux ( 3199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3199 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 3199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 2497:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,I/SearchServiceFactory( 3063): refreshing internal icing corpora
,W/libprocessgroup( 1016): failed to kill pid 2449: No such process
,D/TimaKeyStoreProvider( 3199): TimaSignature is unavailable
,D/ActivityThread( 3199): Added TimaKeyStore provider
,I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_2449/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Settings_Utils( 1282): isSupportVNFestival SM-A500FU XEO
W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_2469/cgroup.procs: No such file or directory
,E/Zygote  ( 3214): MountEmulatedStorage()
,E/Zygote  ( 3214): v2
,I/libpersona( 3214): KNOX_SDCARD checking this for 1000
,I/libpersona( 3214): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2580:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 2527:com.sec.android.app.camera/u0a139 (adj 15): empty #32
I/ActivityManager( 1016): Killing 2484:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #33
I/SELinux ( 3214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SELinux ( 3214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/TRThreadPoolExecutor( 3063): Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3063): Task "NotifyOnDoneFutureTask[update_icing_corpora]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/art     (  306): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.224ms total 43.067ms
,W/TRThreadPoolExecutor( 3063): Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
W/TRThreadPoolExecutor( 3063): Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/SearchServiceFactory( 3063): refreshing search history.
,W/TRThreadPoolExecutor( 3063): Task "NotifyOnDoneFutureTask[refresh_doodle]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/TRThreadPoolExecutor( 3063): Task "NotifyOnDoneFutureTask[refresh_auth_tokens]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/TimaKeyStoreProvider( 3214): TimaSignature is unavailable
,D/ActivityThread( 3214): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 28.890ms
W/TRThreadPoolExecutor( 3063): Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 17.415ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_2497/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2580/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_2527/cgroup.procs: No such file or directory
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.gms, action: null
W/libprocessgroup( 1016): failed to open /acct/uid_10088/pid_2484/cgroup.procs: No such file or directory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UpdateIcingCorporaServi( 3063): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,D/UserAnalysis.PlaceProvider( 3199): PlaceProvider onCreate()
,I/DBG_FMMDM( 3214): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_FMMDM( 3214): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3214): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3214): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 17964(1011KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 25MB/38MB, paused 2.436ms total 132.257ms
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3243): MountEmulatedStorage()
E/Zygote  ( 3243): v2
I/libpersona( 3243): KNOX_SDCARD checking this for 1000
I/libpersona( 3243): KNOX_SDCARD not a persona
,I/SELinux ( 3243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3243 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/UserAnalysis.SecureDbManager( 3199): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3199): SecurePlaceDbHelper() 
D/UserAnalysis( 3199): Create SecureDbHelper
,D/TimaKeyStoreProvider( 3243): TimaSignature is unavailable
,D/ActivityThread( 3243): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 3199): onCreate()
,W/ResourcesManager( 3183): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3183): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3199): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3259): MountEmulatedStorage()
I/libpersona( 3259): KNOX_SDCARD checking this for 10060
E/Zygote  ( 3259): v2
I/libpersona( 3259): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3259 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3259): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 3199): no applications having user consent for prediction
,I/PCWCLIENTTRACE_LOG( 3243): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3243): DEFAULT_LOGLEVEL : 3
,D/TimaKeyStoreProvider( 3259): TimaSignature is unavailable
,D/ActivityThread( 3259): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3243): new DMDBOpenHelper instance
,V/AlarmManager( 1016): waitForAlarm result :8
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3274): MountEmulatedStorage()
E/Zygote  ( 3274): v2
I/libpersona( 3274): KNOX_SDCARD checking this for 10092
I/libpersona( 3274): KNOX_SDCARD not a persona
,I/SELinux ( 3274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,V/JNIHelp ( 3183): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 3063): UpdateCorporaTask done [took 309 ms] updated apps [took 309 ms] 
I/SELinux ( 3274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3274): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3274 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3199): [PlaceDetection::stopService] Service stopped.
,D/TimaKeyStoreProvider( 3274): TimaSignature is unavailable
,D/ActivityThread( 3274): Added TimaKeyStore provider
,D/PCWCLIENTTRACE_DMContentProvider( 3243): [URIMatcher] - result : 2
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDM( 3214): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3214): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3214): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3291): MountEmulatedStorage()
E/Zygote  ( 3291): v2
I/libpersona( 3291): KNOX_SDCARD checking this for 1000
I/libpersona( 3291): KNOX_SDCARD not a persona
,I/SELinux ( 3291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3291 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2641:com.android.keychain/1000 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 2564:com.android.calendar/u0a135 (adj 15): empty #32
I/SELinux ( 3291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3291): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 3199): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3199): Constructor Preference
,W/ActivityThread( 3183): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3183): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37512fd6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3183): Installed default security provider GmsCore_OpenSSL
,D/TimaKeyStoreProvider( 3291): TimaSignature is unavailable
,D/ActivityThread( 3291): Added TimaKeyStore provider
,W/art     ( 3063): Suspending all threads took: 9.294ms
,I/System.out( 1788): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1788): (HTTPLog)-Static: isShipBuild true
I/System.out( 1788): (HTTPLog)-Thread-149-312213133: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,E/Auth    ( 1788): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2641/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_2564/cgroup.procs: No such file or directory
,W/Search.LoginHelper( 3063): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3063): java.io.IOException: NetworkError
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3063): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3063): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,I/WebViewFactory( 3063): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
E/Auth    ( 1788): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 3063): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3063): java.io.IOException: NetworkError
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3063): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3063): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,W/TRThreadPoolExecutor( 3063): Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,I/ActivityManager( 1016): Killing 2052:com.google.android.gms/u0a12 (adj 15): empty #31
,I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
,I/DBG_FMMDS( 3291): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/LibraryLoader( 3063): Time to load native libraries: 2 ms (timestamps 6608-6610)
I/LibraryLoader( 3063): Expected native library version number "",actual native library version number ""
,I/DBG_FMMDS( 3291): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,W/art     ( 3063): Attempt to remove local handle scope entry from IRT, ignoring
,E/Auth    ( 1788): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/TRThreadPoolExecutor( 3063): Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,W/Search.LoginHelper( 3063): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3063): java.io.IOException: NetworkError
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3063): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3063): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,D/PCWCLIENTTRACE_DMContentProvider( 3243): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3291): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3291): [50.18.150420][Line:43][xdbDBInit] 
,I/System.out( 1788): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1788): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 3063): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 3063): java.io.IOException: NetworkError
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.b(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.gms.auth.e.a(Unknown Source)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.j.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.f.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.b.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.k.b(LoginHelper.java:841)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.aMt(LoginHelper.java:727)
W/Search.LoginHelper( 3063): 	at com.google.android.search.core.google.b.p.call(LoginHelper.java:724)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 3063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 3063): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 3063): 	at com.google.android.apps.gsa.shared.util.c.a.k.run(GsaThreadFactory.java:100)
,I/sCloudBackupApp( 3259): sCloudBackupApp Version Info : 4.04.8.KK_APP
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3325): MountEmulatedStorage(),
E/Zygote  ( 3325): v2
I/libpersona( 3325): KNOX_SDCARD checking this for 10062
,I/libpersona( 3325): KNOX_SDCARD not a persona
,I/SELinux ( 3325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3325 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 2687:com.samsung.android.sm/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3325): TimaSignature is unavailable
,D/ActivityThread( 3325): Added TimaKeyStore provider
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3155): Setting receiver enabled: false
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/USB_UICC(  296): Timeout! No signal received. Retry num = 30
,I/DBG_FMMDS( 3291): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/ExternalOEMControlProvider( 3325): onCreate
,E/ActivityThread( 3155): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_2052/cgroup.procs: No such file or directory
I/DBG_FMMDS( 3291): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3291): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3291): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3291): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
E/Zygote  ( 3349): MountEmulatedStorage()
I/libpersona( 3349): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3349): v2
I/libpersona( 3349): KNOX_SDCARD not a persona
I/SELinux ( 3349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_FMMDS( 3291): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3291): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2687/cgroup.procs: No such file or directory
,I/SELinux ( 3349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3349 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/dbxyzptlk.db240408.D.h( 3155): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,D/SettingsProvider( 1016): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10062
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,I/dbxyzptlk.db240408.D.h( 3155): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1016): name = PREVIOUS_ELAPSED_TIME
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10062
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1016): ret = -1
,D/TimaKeyStoreProvider( 3349): TimaSignature is unavailable
,D/ActivityThread( 3349): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/USB_UICC(  296): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  296): usb_uicc_init_qmi failed ! 
I/USB_UICC(  296): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  296): usb_uicc_cleanup, Issuing QMI deinit ... 
,W/ResourcesManager( 3349): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/dbxyzptlk.db240408.D.h( 3155): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm,
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,I/FOTA_Client( 3113): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/ActivityManager( 1016): Killing 2720:flipboard.boxer.app/u0a99 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1282): InitSerachDBThread thread end!
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/FOTA_Client( 3113): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/ServiceMode( 3349): received = ACTION_BOOT_COMPLETED,
I/ServiceMode( 3349): setReferenceIsDumpState : 0
,I/FOTA_Client( 3113): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
W/FOTA_Client( 3113): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,W/ResourcesManager( 3183): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3183): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/dbxyzptlk.db240408.D.h( 3155): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,E/Zygote  ( 3371): MountEmulatedStorage()
,E/Zygote  ( 3371): v2
I/libpersona( 3371): KNOX_SDCARD checking this for 1000
I/libpersona( 3371): KNOX_SDCARD not a persona
I/SELinux ( 3371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3371 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 1732:com.android.defcontainer/u0a4 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3371): TimaSignature is unavailable
,D/ActivityThread( 3371): Added TimaKeyStore provider
,D/breakpad( 3155): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,E/Zygote  ( 3389): MountEmulatedStorage()
,E/Zygote  ( 3389): v2
I/libpersona( 3389): KNOX_SDCARD checking this for 10014
I/libpersona( 3389): KNOX_SDCARD not a persona
,I/SELinux ( 3389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3389 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/SELinux ( 3389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3389): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 2144:flipboard.app/u0a98 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3389): TimaSignature is unavailable
,I/com.dropbox.sync.android.a( 3155): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
D/ActivityThread( 3389): Added TimaKeyStore provider
,I/FactoryTestApp( 2615): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2969)  
,I/ActivityManager( 1016): Killing 2737:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,V/OneTimeInitializerReceiver( 3389): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3389): OneTimeService.onHandleIntent
,W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_1732/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_2720/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10098/pid_2144/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2737/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/com.dropbox.sync.android.ad( 3155): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/NPS_WSSNPS( 3371): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3371): [] Service onCreate!!
,I/dex2oat ( 3409): ----------------------------------------------------
I/dex2oat ( 3409): <SS>: S T A R T I N G . . .
I/dex2oat ( 3409): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3409): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-257474247.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-257474247.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Zygote  ( 3415): MountEmulatedStorage()
E/Zygote  ( 3415): v2
I/libpersona( 3415): KNOX_SDCARD checking this for 1000
I/libpersona( 3415): KNOX_SDCARD not a persona
,I/SELinux ( 3415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3415 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3371): [50.150621] NpsServiceTask Start
,D/TimaKeyStoreProvider( 3415): TimaSignature is unavailable
,D/ActivityThread( 3415): Added TimaKeyStore provider
,E/Zygote  ( 3437): MountEmulatedStorage()
,E/Zygote  ( 3437): v2
,I/libpersona( 3437): KNOX_SDCARD checking this for 1000
I/SELinux ( 3437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3437): KNOX_SDCARD not a persona
,I/SELinux ( 3437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3437): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3437 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/NPS_WSSNPS( 3371): [50.150621] smlDBHelper
,D/TimaKeyStoreProvider( 3437): TimaSignature is unavailable
,D/ActivityThread( 3437): Added TimaKeyStore provider
,W/ResourcesManager( 3415): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/NPS_WSSNPS( 3371): [50.150621] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 3371): [50.150621] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3371): [50.150621] IsRemain_Asyncing nothing
,W/ContextImpl( 3371): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3371): [50.150621] Service onDestroy
,I/NPS_WSSNPS( 3371): [50.150621] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3371): [50.150621] smlBRMessageDelete
D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
I/NPS_WSSNPS( 3371): [50.150621] smlBREmailDelete
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/NPS_WSSNPS( 3371): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3371): [50.150621] smlBRCallLogDelete
,I/NPS_WSSNPS( 3371): [50.150621] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3371): [50.150621] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3371): [50.150621] smlBRSMemoDelete
I/NPS_WSSNPS( 3371): [50.150621] verifier installed? false
,I/NPS_WSSNPS( 3371): [50.150621] cpuBooster release : false
,I/Hs20UtilService( 3437): onCreate
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/dex2oat ( 3409): dex2oat took 199.444ms (threads: 4)
,E/Zygote  ( 3459): MountEmulatedStorage()
,E/Zygote  ( 3459): v2
I/libpersona( 3459): KNOX_SDCARD checking this for 10019
I/libpersona( 3459): KNOX_SDCARD not a persona
,I/SELinux ( 3459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3459 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/NPS_WSSNPS( 3371): [50.150621] dsServerSocket close,
,I/ActivityManager( 1016): Killing 2747:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/art     (  306): Explicit concurrent mark sweep GC freed 8767(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 746us total 25.968ms
,D/TimaKeyStoreProvider( 3459): TimaSignature is unavailable
,D/ActivityThread( 3459): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 721us total 21.371ms
,I/Hs20UtilService( 3437): Starting #1
,I/Hs20UtilService( 3437): Message received 5003
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 18.123ms
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
W/System.err( 3183): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/Zygote  ( 3478): MountEmulatedStorage()
,E/Zygote  ( 3478): v2
I/libpersona( 3478): KNOX_SDCARD checking this for 10094
,I/libpersona( 3478): KNOX_SDCARD not a persona
,I/SELinux ( 3478): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3478): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3478): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3478 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2315:com.sec.modem.settings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3478): TimaSignature is unavailable
,D/ActivityThread( 3478): Added TimaKeyStore provider
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,W/art     ( 3183): Suspending all threads took: 19.048ms
,I/RlzPingService( 3135): Setting next ping for 1458138079197
,I/System.out( 3155): Thread-439(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/elm:15183( 3478): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_2747/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2315/cgroup.procs: No such file or directory
,D/elm:15183( 3478): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3478): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3478): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 3478): ElmAgentService : onCreate()
,D/elm:15183( 3478): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,V/EmergencyMode( 1408): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,I/System.out( 3183): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 3183): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 3183): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/elm:15183( 3478): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3478): BootCompletedState : startBootCompleted() call
,I/KLMS-2.5.183: ( 3459): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 09 15:21:19 GMT+01:00 2016
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/System.out( 3155): Thread-439(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3155): Thread-439(ApacheHTTPLog):isShipBuild true
I/System.out( 3155): Thread-439(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3155): Thread-439(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/EnterpriseController(  278): uids 10092
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10092
,I/KLMS-2.5.183: ( 3459): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,D/elm:15183( 3478): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/elm:15183( 3478): Get License : 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/elm:15183( 3478): ElmAgentService : onDestroy().
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/System.out( 3155): pool-10-thread-1 calls detatch()
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.183: ( 3459): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3459): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.183: ( 3459): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/Zygote  ( 3513): MountEmulatedStorage()
E/Zygote  ( 3513): v2
I/libpersona( 3513): KNOX_SDCARD checking this for 10022
I/libpersona( 3513): KNOX_SDCARD not a persona
,I/SELinux ( 3513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3513 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3513): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/KLMS-2.5.183: ( 3459): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3459): KLMSIntentService(): BOOT_COMPLETED
,E/Zygote  ( 3524): MountEmulatedStorage()
E/Zygote  ( 3524): v2
I/libpersona( 3524): KNOX_SDCARD checking this for 10012
I/libpersona( 3524): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3524 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 2772:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3513): TimaSignature is unavailable
D/ActivityThread( 3513): Added TimaKeyStore provider
I/ActivityManager( 1016): Killing 2807:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3524): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SMD     (  288): DCD OFF
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3547): MountEmulatedStorage()
,E/Zygote  ( 3547): v2
I/libpersona( 3547): KNOX_SDCARD checking this for 1000
I/libpersona( 3547): KNOX_SDCARD not a persona
I/SELinux ( 3547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2279:com.android.mms/u0a46 (adj 15): empty #31
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/SELinux ( 3547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/KLMS-2.5.183: ( 3459): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 3524): TimaSignature is unavailable
,D/ActivityThread( 3524): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3547): TimaSignature is unavailable
,D/ActivityThread( 3547): Added TimaKeyStore provider
,W/ResourcesManager( 3524): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3524): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CountryDetector( 1016): No listener is left
,E/MTPRx   ( 3547): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2772/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1101/pid_2807/cgroup.procs: No such file or directory
V/MTPRx   ( 3547): sealedState: false
V/MTPRx   ( 3547): sealedUsbMassStorageState: false
,D/SettingsProvider( 1016): name = mtp_usb_connection_status
,D/SettingsProvider( 1016): name = media_player_mode
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,I/MultiDex( 3524): VM with version 2.1.0 has multidex support
I/MultiDex( 3524): install
I/MultiDex( 3524): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_2279/cgroup.procs: No such file or directory
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = mtp_running_status
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/SettingsProvider( 1016): name = media_mount_count
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = mtp_sync_alive
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = sdcard_launch
,D/SettingsProvider( 1016): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,D/SettingsProvider( 1016): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3243): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3243): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3243): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3243): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3243): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3243): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/PCWCLIENTTRACE_PCWHandler( 3243): [ensureRegistration] - netwrok is not available. action ignored
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
V/EmergencyMode( 1408): [EmergencyBase] setBootTime
V/EmergencyMode( 1408): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3574): MountEmulatedStorage()
,E/Zygote  ( 3574): v2,
,I/SELinux ( 3574): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3574 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2841:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
I/libpersona( 3574): KNOX_SDCARD checking this for 10031
I/libpersona( 3574): KNOX_SDCARD not a persona
,I/SELinux ( 3574): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3574): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3585): MountEmulatedStorage()
I/libpersona( 3585): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3585): v2
I/libpersona( 3585): KNOX_SDCARD not a persona
,I/SELinux ( 3585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3585): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3585 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3574): TimaSignature is unavailable
D/ActivityThread( 3574): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3585): TimaSignature is unavailable
,D/ActivityThread( 3585): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10048/pid_2841/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/JNIHelp ( 3524): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3574): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 3609): MountEmulatedStorage(),
,E/Zygote  ( 3609): v2
I/libpersona( 3609): KNOX_SDCARD checking this for 1000
I/libpersona( 3609): KNOX_SDCARD not a persona
,I/SELinux ( 3609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3609 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/CameraApp( 3585): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3585): Feature.Feature(context)
I/testFeature( 3585): Feature.readInternalDefaultXml()
I/testFeature( 3585): ResetFeatureValue
,I/CameraFirmware_broadcast( 3585): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3585): CameraApp.getAppFeature()...
,I/ActivityManager( 1016): Killing 2862:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,E/SELinux ( 3609): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3617): MountEmulatedStorage()
E/Zygote  ( 3617): v2
I/libpersona( 3617): KNOX_SDCARD checking this for 10100
I/libpersona( 3617): KNOX_SDCARD not a persona
,I/SELinux ( 3617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3617 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 2893:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,E/SELinux ( 3617): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityThread( 3524): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3524): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c429655: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3524): Installed default security provider GmsCore_OpenSSL
,D/TimaKeyStoreProvider( 3609): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 3617): TimaSignature is unavailable
,D/ActivityThread( 3609): Added TimaKeyStore provider
,D/ActivityThread( 3617): Added TimaKeyStore provider
,D/PackageIntentReceiver( 3617): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3617): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/SettingsProvider( 1016): name = access_control_enabled
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3643): MountEmulatedStorage()
E/Zygote  ( 3643): v2
I/libpersona( 3643): KNOX_SDCARD checking this for 10101
I/libpersona( 3643): KNOX_SDCARD not a persona
,I/SELinux ( 3643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3643): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3643 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 2909:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3656): MountEmulatedStorage()
E/Zygote  ( 3656): v2
I/libpersona( 3656): KNOX_SDCARD checking this for 10069
I/libpersona( 3656): KNOX_SDCARD not a persona
I/SELinux ( 3656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3656 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 2877:com.sec.dsm.system/1000 (adj 15): empty #31
,I/SELinux ( 3656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3643): TimaSignature is unavailable
D/ActivityThread( 3643): Added TimaKeyStore provider
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 22246(1190KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 26MB/39MB, paused 2.553ms total 171.153ms
,D/TimaKeyStoreProvider( 3656): TimaSignature is unavailable
,D/ActivityThread( 3656): Added TimaKeyStore provider
,D/FileShare-Server( 3656): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,W/libprocessgroup( 1016): failed to open /acct/uid_10157/pid_2862/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_2893/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2877/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_2909/cgroup.procs: No such file or directory
,I/VlingoApplication( 3574): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,D/BluetoothAdapter( 3574): 1073623331: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3574): 1073623331: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3574): 1073623331: getState() :  mService = null. Returning STATE_OFF
D/NativeLibraryUtils( 3524): Install completed successfully. count=14 extracted=0
,I/VlingoAndroidCore( 3574): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/AudioService( 1016): getStreamVolume 3 index 0
,D/VlingoApplication( 3574): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3574): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 3574): initQueue()
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3684): MountEmulatedStorage(),
E/Zygote  ( 3684): v2
,I/libpersona( 3684): KNOX_SDCARD checking this for 10032
I/libpersona( 3684): KNOX_SDCARD not a persona,
I/SELinux ( 3684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3684 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 3684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 2927:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3684): TimaSignature is unavailable
I/art     (  306): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 699us total 25.470ms,
D/ActivityThread( 3684): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 713us total 20.155ms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2927/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.307ms total 20.899ms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3183): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1016): Killing 2938:com.sec.usbsettings/1000 (adj 15): empty #31,
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3731): MountEmulatedStorage(),
E/Zygote  ( 3731): v2
,I/libpersona( 3731): KNOX_SDCARD checking this for 10033
I/libpersona( 3731): KNOX_SDCARD not a persona
I/SELinux ( 3731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3731 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 3731): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Killing 2981:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager( 1016): Killing 2826:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1016): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3731): TimaSignature is unavailable
,D/ActivityThread( 3731): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3750): MountEmulatedStorage(),
E/Zygote  ( 3750): v2
I/libpersona( 3750): KNOX_SDCARD checking this for 1000
I/libpersona( 3750): KNOX_SDCARD not a persona,
,I/SELinux ( 3750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3750): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3750 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2938/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10085/pid_2826/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_2981/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/TimaKeyStoreProvider( 3750): TimaSignature is unavailable
,D/ActivityThread( 3750): Added TimaKeyStore provider
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 2981
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ContextImpl( 1924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SecUISvc( 1924): Thread created.
D/SecUISvc( 1924): Service started flags 0 startId 1
,E/Zygote  ( 3772): MountEmulatedStorage()
,E/Zygote  ( 3772): v2,
I/SELinux ( 3772): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 3772): KNOX_SDCARD checking this for 10028
I/libpersona( 3772): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3772 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/FactoryTestApp( 2615): [DummyFtClient$onDestroy](2615) Destroy DummyFtClient service
,D/FactoryTestApp( 2615): [Support$Values.getString](2615) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2615): [ModuleCommon$isConnectionModeNone](2615) mConnectionMode = gsm
I/FactoryTestApp( 2615): [ModuleCommon$isRunningFtClient](2615) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2615): [DummyFtClient$onDestroy](2615) kill process
I/Process ( 2615): Sending signal. PID: 2615 SIG: 9
I/SELinux ( 3772): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3772): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3772): TimaSignature is unavailable
,D/ActivityThread( 3772): Added TimaKeyStore provider
,I/Gmail   ( 3643): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1016): Process com.sec.factory (pid 2615)(adj 0) has died(207,1049)
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3791): MountEmulatedStorage()
E/Zygote  ( 3791): v2
I/libpersona( 3791): KNOX_SDCARD checking this for 1000
I/libpersona( 3791): KNOX_SDCARD not a persona
,I/SELinux ( 3791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3791): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3791): TimaSignature is unavailable
,D/ActivityThread( 3791): Added TimaKeyStore provider
,W/ResourcesManager( 3791): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,W/GAV2    ( 3643): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1016): Killing 3012:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ResourcesManager( 3731): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3731): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3731): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ResourcesManager( 3731): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3731): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ResourcesManager( 3731): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3731): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3731): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
E/Gmail   ( 3643): Error finding the version of the Email provider.....
E/Gmail   ( 3643): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3643): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3643): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3643): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3643): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3643): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3643): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3643): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3643): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_3012/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaService( 1016): TIMA: in getTimaVersion
,D/TimaService( 1016): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1016): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1016): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1016): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1016): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1016): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/Gmail   ( 3643): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,I/Gmail   ( 3643): Observing account changes for notifications
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 8
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1016): ctx = 0xb91f80d0, comm = 0xb8f2cbd0, sendmsg = 0xa0c99000, recvmsg = 0xa0c99440
I/TZ_init: ( 1016): TZ_init: sending initialization request...
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/TZ_init: ( 1016): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1016): trustlet initialization failed
I/TZ_init: ( 1016): TZ_init_START...
,E/Zygote  ( 3823): MountEmulatedStorage()
E/Zygote  ( 3823): v2
I/libpersona( 3823): KNOX_SDCARD checking this for 10104
I/libpersona( 3823): KNOX_SDCARD not a persona
I/TZ_init: ( 1016): TZ_init_with_data: sending initialization request...
,I/SELinux ( 3823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/TZ_init: ( 1016): TZ_init: successful initialization
D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 8,
E/TLC_TZ_KEYSTORE: ( 1016): Count : 1, Ret : 0
,I/SELinux ( 3823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 3823): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3823 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/TimaKeyStoreProvider( 3823): TimaSignature is unavailable
,D/ActivityThread( 3823): Added TimaKeyStore provider
,E/ActivityThread( 3643): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3291d95a that was originally bound here
E/ActivityThread( 3643): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3291d95a that was originally bound here
E/ActivityThread( 3643): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3643): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3643): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3643): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3643): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3643): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3643): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3643): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3643): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3643): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3643): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3643): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3643): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3643): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3643): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3643): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1016): Unbind failed: could not find connection for android.os.BinderProxy@23130513
,I/GoogleHttpClient( 1611): GMS http client unavailable, use old client
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3823): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 3772): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3750): Resource data:2131165186
,W/ResourcesManager( 3750): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3750): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3750): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,I/AMMetaDataParserService( 3750): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,I/System.out( 3574): INFO:Resource not found:/Common.properties Using default values
,W/ContextImpl( 3791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
E/SQLiteLog( 3643): (283) recovered 135 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3858): MountEmulatedStorage(),
I/libpersona( 3858): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3858): v2
I/libpersona( 3858): KNOX_SDCARD not a persona
I/SELinux ( 3858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/AMMetaDataParserService( 3750): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,I/SELinux ( 3858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3858): TimaSignature is unavailable
,D/ActivityThread( 3858): Added TimaKeyStore provider
,W/ResourcesManager( 3858): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,W/ContextImpl( 3858): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
W/SEAMService( 1016):  hashset_to_int_array returning null
,W/SEAMService( 1016):  hashset_to_int_array returning null
,E/SQLiteLog( 3791): (284) automatic index on seams_container_info(seams_container_id)
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,E/SQLiteLog( 3791): (284) automatic index on seams_container_info(sp_id)
,W/SEAMService( 1016):  hashset_to_int_array returning null
I/F_PHONE ( 3858): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131034113
,I/ActivityManager( 1016): Killing 3031:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,W/ResourcesManager( 3750): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,W/ContextImpl( 3858): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/Finsky  ( 3772): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3750): took 2.366355ms for 0*0 texture 0
,D/ActivityManager( 1016): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,I/GFX generate_partition_tables( 3750): took 6.047501ms for 0*0 texture 0
,I/GFX raster( 3750): took 9.684896ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5b5b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b5b578 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,W/ResourcesManager( 3684): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/F_PHONE ( 3858): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3858): default registerAction()
I/F_PHONE ( 3858): [[com.sec.bcservice]] sendPendingMessage()
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3031/cgroup.procs: No such file or directory
,I/Process ( 3731): Sending signal. PID: 3731 SIG: 9
,E/File    ( 3643): fail readDirectory() errno=2
,W/ResourcesManager( 3684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.821250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5b5b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b5b578 counterpartCT=4 counterpartW=96 counterparth=96
,I/Gmail   ( 3643): getAccountsCursor
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3643): notifyAccountChanged
,I/AMMetaDataParserService( 3750): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3750): took 2.461198ms for 0*0 texture 0
,W/Settings( 3772): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3772): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/GFX generate_partition_tables( 3750): took 7.416823ms for 0*0 texture 0
,I/GFX raster( 3750): took 10.811250ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5b578 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b60068 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,I/Gmail   ( 3643): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3750): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Gmail   ( 3643): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3643): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3643): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 3731)(adj 0) has died(167,1074)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3896): MountEmulatedStorage()
E/Zygote  ( 3896): v2
I/libpersona( 3896): KNOX_SDCARD checking this for 10034
I/libpersona( 3896): KNOX_SDCARD not a persona
,I/SELinux ( 3896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3896 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3896): TimaSignature is unavailable
,D/ActivityThread( 3896): Added TimaKeyStore provider
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.620469ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b64c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b64d68 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/Babel   ( 3823): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3823): MmsConfig.loadMmsSettings
,I/Babel   ( 3823): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3823): MmsConfig.loadFromDatabase
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.868958ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b61770 counterpartCT=4 counterpartW=96 counterparth=96
,D/Volley  ( 3772): [583] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3772): [576] DiskBasedCache.clear: Cache cleared.
,E/Babel   ( 3823): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3823): MmsConfig.loadFromResources
,D/Ads     ( 3772): Skipping gmscore version check
,E/Babel   ( 3823): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3823): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3750): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3772): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3772): [1] Libraries$2.run: Finished loading 1 libraries.
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.629219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5ba00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b600f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.700417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b622e0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/Settings( 3823): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3921): MountEmulatedStorage()
E/Zygote  ( 3921): v2
I/libpersona( 3921): KNOX_SDCARD checking this for 10035
I/libpersona( 3921): KNOX_SDCARD not a persona
,I/SELinux ( 3921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3921 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3048:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/SELinux ( 3921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3921): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 25654(1625KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.583ms total 187.234ms
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.535729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5fcc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b605d8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,I/AMMetaDataParserService( 3750): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131034113
,D/Finsky  ( 3772): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/AMMetaDataParserService( 3750): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/TimaKeyStoreProvider( 3921): TimaSignature is unavailable,
,D/ActivityThread( 3921): Added TimaKeyStore provider
,I/GFX raster( 3750): took 0.869427ms for 96*96 texture 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5b5b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b60468 counterpartCT=4 counterpartW=96 counterparth=96,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1016): failed to open /acct/uid_10086/pid_3048/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3750): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/SMD     (  288): DCD OFF
,I/Babel_StickerModule( 3823): App launched.
,I/Babel_StickerModule( 3823): Sticker update initiated. last:1456825783062 empty:false
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 3921): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 3921): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/SPPClientService( 3921): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.851093ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5b5b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b61770 counterpartCT=4 counterpartW=96 counterparth=96
,D/Finsky  ( 3772): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/AMMetaDataParserService( 3750): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/Gmail   ( 3643): getAccountsCursor
,D/SPPClientService( 3921): PushLog.txt file is not deleted.
D/SPPClientService( 3921): PushLog.txt file is not deleted.
D/SPPClientService( 3921): ============PushLog. stop!
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.616146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5b578 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5bbf8 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3750): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/WearableService( 1788): callingUid 10012, callindPid: 1788
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.609167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b64c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b56058 counterpartCT=4 counterpartW=96 counterparth=96
,E/GmsWearableNodeHelper( 1788): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/AMMetaDataParserService( 3750): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
I/GFX raster( 3750): took 0.841407ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61618 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b62500 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3750): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,V/Babel   ( 3823): babel boot account: SMS,
,E/Zygote  ( 3945): MountEmulatedStorage(),
E/Zygote  ( 3945): v2
I/libpersona( 3945): KNOX_SDCARD checking this for 10041
I/libpersona( 3945): KNOX_SDCARD not a persona
,I/SELinux ( 3945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3945): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=3945 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3155:com.dropbox.android/u0a92 (adj 15): empty #31
,W/Babel   ( 3823): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,D/TimaKeyStoreProvider( 3945): TimaSignature is unavailable
,D/ActivityThread( 3945): Added TimaKeyStore provider
,W/Babel   ( 3823): java.lang.Exception
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3823): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3823): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3823): 	at ckh.a(SourceFile:67)
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3823): 	at bhn.a(SourceFile:301)
W/Babel   ( 3823): 	at bhn.a(SourceFile:137)
W/Babel   ( 3823): 	at bhn.a(SourceFile:126)
W/Babel   ( 3823): 	at bhn.a(SourceFile:159)
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3823): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3823): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3823): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3823): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3823): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3823): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/Babel   ( 3823): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3823): java.lang.Exception
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3823): 	at aes.a(SourceFile:145)
W/Babel   ( 3823): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3823): 	at ckh.a(SourceFile:67)
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3823): 	at bhn.a(SourceFile:301)
W/Babel   ( 3823): 	at bhn.a(SourceFile:137)
W/Babel   ( 3823): 	at bhn.a(SourceFile:126)
W/Babel   ( 3823): 	at bhn.a(SourceFile:159)
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3823): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3823): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3823): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3823): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3823): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3823): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/GFX raster( 3750): took 0.911092ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5ba00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b61770 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.901875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5e390 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 1.048958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5fcc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b61280 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3155/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3750): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 3772): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 3772): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3772): (HTTPLog)-Static: isShipBuild true
I/System.out( 3772): (HTTPLog)-Thread-588-244447565: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3772): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10028
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10028
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3823): babel boot account: thalitester@gmail.com
,I/AMMetaDataParserService( 3750): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3750): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3750): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131034112
I/AMMetaDataParserService( 3750): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.853958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b1cbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b61280 counterpartCT=4 counterpartW=96 counterparth=96
,D/FileApkUtils( 3524): Spent 72ms computing apk sha1.
,D/FileApkUtils( 3524): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 3524): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/Babel   ( 3823): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3823): java.lang.Exception
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3823): 	at aes.a(SourceFile:145)
W/Babel   ( 3823): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3823): 	at ckh.a(SourceFile:67)
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3823): 	at bhn.a(SourceFile:301)
W/Babel   ( 3823): 	at bhn.a(SourceFile:137)
W/Babel   ( 3823): 	at bhn.a(SourceFile:126)
W/Babel   ( 3823): 	at bhn.a(SourceFile:159)
W/Babel   ( 3823): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3823): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3823): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3823): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3823): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3823): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3823): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/DexOptUtils( 3524): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
,D/DexOptUtils( 3524): Lollipop platform, using <isa> directory.
D/DexOptUtils( 3524): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 3524): Primary ABI of odexing process is armeabi-v7a
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.607605ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b1cbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b20f20 counterpartCT=4 counterpartW=96 counterparth=96
,W/InstanceID/Rpc( 3524): Found 10012
,I/SA      ( 3945): [SSP] onCreated
,I/AMMetaDataParserService( 3750): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/SA      ( 3945): [TPM] There is no property file
,I/SA      ( 3945): [SCU] isHaveSA() - false
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.682813ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b1c608 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,I/SA      ( 3945): [TPM] getModelProperty : null
I/SA      ( 3945): [TPM] getCSCProperty : null
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SA      ( 3945): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 3945): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 3945): [DM] TFT FEATURE: false
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3750): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529,
,I/SA      ( 3945): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0,
I/SA      ( 3945): [DM] init START
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/dex2oat ( 3965): ----------------------------------------------------
I/dex2oat ( 3965): <SS>: S T A R T I N G . . .
I/dex2oat ( 3965): <SS>: Zip is absent. Canceled.
I/GFX raster( 3750): took 0.647917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b43520 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1bf20 counterpartCT=4 counterpartW=96 counterparth=96
I/dex2oat ( 3965): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=38 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Zygote  ( 3970): MountEmulatedStorage()
,E/Zygote  ( 3970): v2
I/libpersona( 3970): KNOX_SDCARD checking this for 1000
,I/libpersona( 3970): KNOX_SDCARD not a persona
,I/SELinux ( 3970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/SELinux ( 3970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/SA      ( 3945): [DM] This device is not a Vodafone
,E/SELinux ( 3970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3970 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3199:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,W/ResourceType( 3945): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 3945): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ResourceType( 3945): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ResourceType( 3945): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourceType( 3945): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 3945): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131034113
I/AMMetaDataParserService( 3750): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.867396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b61280 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3970): TimaSignature is unavailable
,D/ActivityThread( 3970): Added TimaKeyStore provider
,W/ResourceType( 3945): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 3945): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,I/AMMetaDataParserService( 3750): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourceType( 3945): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 3945): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 3945): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 3945): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourceType( 3945): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 3945): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
I/GFX raster( 3750): took 0.815208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourceType( 3945): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 3945): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,W/VideoCapabilities( 3823): Unrecognized profile 2130706433 for video/avc
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3750): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 3823): Unsupported mime audio/evrc
,I/SA      ( 3945): [SCU] isHaveSA() - false
I/SA      ( 3945): support phone number id : false
I/SA      ( 3945): [DM] Supports Ref Jpn : true
,I/SA      ( 3945): [DM] init END
,I/SA      ( 3945): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 3945): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,W/AudioCapabilities( 3823): Unsupported mime audio/qcelp
,I/SA      ( 3945): [OR] onReceive END
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 3823): Unsupported mime audio/mpeg-L1,
,W/AudioCapabilities( 3823): Unsupported mime audio/mpeg-L2,
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3750): took 0.616614ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b1bf20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b61280 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3199/cgroup.procs: No such file or directory,
,W/AudioCapabilities( 3823): Unsupported mime audio/x-ms-wma
,E/Zygote  ( 3989): MountEmulatedStorage()
E/Zygote  ( 3989): v2
I/libpersona( 3989): KNOX_SDCARD checking this for 10042
I/libpersona( 3989): KNOX_SDCARD not a persona
,I/SELinux ( 3989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/AudioCapabilities( 3823): Unsupported mime audio/x-ima
I/AMMetaDataParserService( 3750): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/SA      ( 3945): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 3945): [ODM] queryOpenData(key= GEO_IP )
I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3989 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 3823): Unsupported mime audio/qcelp
I/SELinux ( 3989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
E/SELinux ( 3989): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  306): Explicit concurrent mark sweep GC freed 8730(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 20.563ms
,W/AudioCapabilities( 3823): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 3989): TimaSignature is unavailable
,D/ActivityThread( 3989): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 20.467ms
,I/SA      ( 3945): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 3945): [LBE] REF_JPN : true
I/SA      ( 3945): [BDC] create
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.601146ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b1cbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3823): Unsupported mime video/wvc1
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 17.400ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3750): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/VideoCapabilities( 3823): Unsupported mime video/x-ms-wmv
W/ResourcesManager( 3989): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 3524): COMPAT: Multi user not supported
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.824427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3823): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/GCM     ( 1788): COMPAT: Multi user not supported
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3750): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,W/VideoCapabilities( 3823): Unsupported mime video/wvc1
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4006): MountEmulatedStorage()
,E/Zygote  ( 4006): v2
I/libpersona( 4006): KNOX_SDCARD checking this for 1000
I/libpersona( 4006): KNOX_SDCARD not a persona
,I/SELinux ( 4006): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/VideoCapabilities( 3823): Unsupported mime video/x-ms-wmv
,I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4006 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4006): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4006): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3823): Unsupported mime video/x-ms-wmv7
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.667084ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b43520 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b18fa8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3823): Unsupported mime video/x-ms-wmv8
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 4006): TimaSignature is unavailable
,D/ActivityThread( 4006): Added TimaKeyStore provider
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 3524): Checkin interval check for package: unspecified last checkin: 1456600236354 min interval config: 0 actual interval: 933046883
I/GCoreUlr( 3524): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/VideoCapabilities( 3823): Unsupported mime video/mp43
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SA      ( 3945): [DBMV2] getEmailID
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3750): took 0.697916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3823): Unsupported mime video/sorenson
,I/SA      ( 3945): [DBMV2] getDataV02ForItems
,I/SA      ( 3945): [SSP] query invoked
,I/SA      ( 3945): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/CalendarProvider2( 3989): CalendarProvider2.onCreate() called
,W/VideoCapabilities( 3823): Unsupported mime video/mp4v-esdp
,I/SA      ( 3945): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 3945): [BDC] destroy
,I/ActivityManager( 1016): Killing 3214:com.fmm.dm/1000 (adj 15): empty #31
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.603176ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5fcc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b18fa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/CheckinService( 3524): Disabling old GoogleServicesFramework version
,I/AMMetaDataParserService( 3750): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/ChimeraCfgMgr( 3524): Reading stored module config
,D/KnoxSetupWizardDbHelper( 4006): dbMigrationFlag : false
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131165203
,I/VideoCapabilities( 3823): Unsupported profile 4 for video/mp4v-es
,D/ShortcutReceiver( 4006):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3750): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3750): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3750): took 2.543854ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3750): took 10.271041ms for 0*0 texture 0
,I/GFX raster( 3750): took 13.635988ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b37f20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d12bb0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/KnoxShortcutUtil( 4006): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4006):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4006):  shortcut migration not required 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3214/cgroup.procs: No such file or directory
,D/BootCompletedReceiver( 3524): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 3524): Got an BootCompleted event.
,E/Zygote  ( 4032): MountEmulatedStorage(),
I/libpersona( 4032): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4032): v2
I/libpersona( 4032): KNOX_SDCARD not a persona,
I/SELinux ( 4032): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4032 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/AMMetaDataParserService( 3750): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/ActivityManager( 1016): Killing 3063:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
I/SELinux ( 4032): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4032): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.786511ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8ebbbd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ebbcf8 counterpartCT=4 counterpartW=96 counterparth=96
,D/BootCompletedReceiver( 3524): Will NOT schedule AdAttestation signal task because it's disabled.
,I/AMMetaDataParserService( 3750): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 4032): TimaSignature is unavailable
,D/ActivityThread( 4032): Added TimaKeyStore provider
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.811874ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8ebbbd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ebd030 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 3524): onCreate
,I/AMMetaDataParserService( 3750): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.785884ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8ebbbd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ebe280 counterpartCT=4 counterpartW=96 counterparth=96
,E/KnoxSetupWizardClient( 4032): isShipMode : 1
I/KnoxSetupWizardClient( 4032): onReceive : android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/AMMetaDataParserService( 3750): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4056 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3259:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31,
,E/Zygote  ( 4056): MountEmulatedStorage(),
E/Zygote  ( 4056): v2,
I/libpersona( 4056): KNOX_SDCARD checking this for 10107
,I/libpersona( 4056): KNOX_SDCARD not a persona
,I/SELinux ( 4056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4056): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3750): took 0.651354ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8ebf648 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebf780 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 3524): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/AMMetaDataParserService( 3750): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/Babel   ( 3823): Creating RTCS
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaKeyStoreProvider( 4056): TimaSignature is unavailable
,D/ActivityThread( 4056): Added TimaKeyStore provider
,I/GFX raster( 3750): took 0.771719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8ebf648 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ec0898 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/System.err( 4032): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4032): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4032): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4032): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4032): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4032): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4032): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,V/AuthZen ( 3524): Handling intent: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3750): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/CheckinService( 3524): Checking schedule, now: 1457533283740 next: 1457139499243
I/CheckinService( 3524): active receiver: enabled
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/AuthZenEventHandler( 3524): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3063/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3259/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 3274:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131099648
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3750): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.705677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb9067b40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9067e18 counterpartCT=4 counterpartW=96 counterparth=96
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3274/cgroup.procs: No such file or directory
,I/SystemUpdateService( 3524): cancelUpdate (empty URL)
I/SystemUpdateService( 3524): active receiver: disabled
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3750): took 3.026614ms for 0*0 texture 0
,I/art     ( 3524): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3524): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3750): took 9.732813ms for 0*0 texture 0
,I/GFX raster( 3750): took 14.261771ms for 96*96 texture 0,
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b20ea8 counterpartCT=4 counterpartW=96 counterparth=96
,E/BaseAppContext( 3524): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/AMMetaDataParserService( 3750): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.624167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b631f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.643489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b60970 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.627031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb88cf358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ebbbd8 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1788): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 10012
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.736355ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b60970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b5bb20 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3823): (284) automatic index on conversation_participants_view(conversation_id)
,I/AuthZen ( 3524): Fetching signing key...
,I/AMMetaDataParserService( 3750): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/GCoreUlr( 1788): DispatchingService.onCreate()
,D/SSRM:n  ( 1016): SIOP:: AP = 370
,I/AuthZen ( 3524): Signing key fetched successfully!
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131099648
,I/AMMetaDataParserService( 3750): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.688542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb9067b40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b392e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,I/GCoreUlr( 1788): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,E/SQLiteLog( 3823): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SystemUpdateService( 3524): onDestroy
,D/a       ( 3524): Opening database auth.proximity.permit_store...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AuthZenTransactionCache( 3524): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 3524): Clearing transaction cache
,E/SQLiteLog( 3823): (284) automatic index on conversation_participants_view(conversation_id)
,W/ResourcesManager( 3823): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3823): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.756198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b426b0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3823): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3750): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 3823): (284) automatic index on conversation_participants_view(conversation_id)
,I/SecDataIO(  257): Write to block
,W/ContextImpl( 2598): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.780729ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b18fa8 counterpartCT=4 counterpartW=96 counterparth=96
,V/JNIHelp ( 3823): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_DM  ( 2997): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 2997): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 2997): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/Process ( 2598): Sending signal. PID: 2598 SIG: 9
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,W/Auth    ( 1788): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.636302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b1b6e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityThread( 3823): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3823): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e2139d7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3823): Installed default security provider GmsCore_OpenSSL
,I/AMMetaDataParserService( 3750): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.628073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb88cf358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b61c48 counterpartCT=4 counterpartW=96 counterparth=96
,I/Babel   ( 3823): Destroying RTCS
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2598)(adj 0) has died(108,1104)
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GCoreUlr( 1788): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GFX raster( 3750): took 0.726146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b60970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1cbc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/art     ( 3524): WaitForGcToComplete blocked for 164.496ms for cause DisableMovingGc
,I/art     ( 3524): WaitForGcToComplete blocked for 163.977ms for cause DisableMovingGc
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131099648
,I/AMMetaDataParserService( 3750): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.701823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb9067b40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b3b458 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.649219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b1c608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/EventLogService( 3524): Aggregate from 1457530554773 (log), 1457530554773 (data)
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.637708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb88cecf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.638906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b1bf20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/StrictMode( 4056): StrictMode policy violation; ~duration=833 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4056): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4056): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4056): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4056): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4056): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4056): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4056): StrictMode policy violation; ~duration=699 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4056): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4056): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4056): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4056): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4056): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4056): StrictMode policy violation; ~duration=438 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4056): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4056): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4056): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4056): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4056): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4056): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4056): StrictMode policy violation; ~duration=437 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4056): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4056): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4056): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4056): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
,D/StrictMode( 4056): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372),
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4056): StrictMode policy violation; ~duration=436 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4056): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4056): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4056): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4056): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4056): ,	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4056): StrictMode policy violation; ~duration=435 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4056): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4056): 	,at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4056): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4056): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4056): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4056): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4056): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4056): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4056): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4056): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4056): ,	at com.google.r.e.b(PG:170)
D/StrictMode( 4056): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145),
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4056): StrictMode policy violation; ~duration=433 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): ,	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4056): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4056): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4056): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4056): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4056): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4056): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4056): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4056): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4056): ,	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4056): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4056): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4056): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4056): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	,at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): ,	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/StrictMode( 4056): StrictMode policy violation; ~duration=390 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4056): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4056): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4056): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4056): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4056): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497),
D/StrictMode( 4056): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method),
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4056): StrictMode policy violation; ~duration=390 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4056): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4056): ,	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4056): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4056): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4056): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4056): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4056): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4056): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4056): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4056): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4056): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4056): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4056): 	at android.os.Looper.loop(Looper.java:145),
D/StrictMode( 4056): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4056): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4056): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.632500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb88cf358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b392e8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4119): MountEmulatedStorage(),
,E/Zygote  ( 4119): v2,
I/libpersona( 4119): KNOX_SDCARD checking this for 1000
I/libpersona( 4119): KNOX_SDCARD not a persona,
I/SELinux ( 4119): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4119): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4119): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4119 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3750): took 0.720157ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b60970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4119): TimaSignature is unavailable
,D/ActivityThread( 4119): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3750): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131099648
,I/AMMetaDataParserService( 3750): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.688073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb9067b40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b20f20 counterpartCT=4 counterpartW=96 counterparth=96
,D/StatusChecker( 4119): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/StatusChecker( 4119): onReceive : net.mt.init : DONE
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.636823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b631f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/art     ( 1788): Explicit concurrent mark sweep GC freed 28358(1986KB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 12MB/20MB, paused 1.135ms total 464.284ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4137): MountEmulatedStorage()
E/Zygote  ( 4137): v2
I/libpersona( 4137): KNOX_SDCARD checking this for 10116
I/libpersona( 4137): KNOX_SDCARD not a persona
,I/SELinux ( 4137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4137 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3291:com.fmm.ds/1000 (adj 15): empty #31
,I/SELinux ( 4137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4137): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3750): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4137): TimaSignature is unavailable
,D/ActivityThread( 4137): Added TimaKeyStore provider
,I/CalendarProvider2( 3989): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.620260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b1bf20 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/PersistentNotificationBroadcastReceiver( 1788): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/ActivityManager( 1016): Killing 3325:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1788): No location to return for getLastLocation()
,W/FusedLocationProvider( 1788): location=null
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3291/cgroup.procs: No such file or directory
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.676771ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b392e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2997): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,W/GCoreFlp( 1788): No location to return for getLastLocation()
,W/FusedLocationProvider( 1788): location=null
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/AMMetaDataParserService( 3750): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.659375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb88cf358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3325/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/PageBuddyNotiSvc( 4137): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 32405(1948KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 26MB/39MB, paused 3.484ms total 166.191ms
,E/DBG_DM  ( 2997): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2997): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,D/SensorService( 1016): [SO] 0.096 0.402 10.132
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.778124ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b60970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b20f20 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1788): Unbound from all location providers
I/GCoreUlr( 1788): Place inference reporting - stopped
,W/ContextImpl( 4137): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/AMMetaDataParserService( 3750): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131099648
,I/PageBuddyNotiSvc( 4137): onCreate mCpBitFlag=0
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4159 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 4159): MountEmulatedStorage()
E/Zygote  ( 4159): v2
I/libpersona( 4159): KNOX_SDCARD checking this for 10125
I/libpersona( 4159): KNOX_SDCARD not a persona
W/com.google.a.a.b.d.a( 4056): Application name is not set. Call Builder#setApplicationName.
,I/SELinux ( 4159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3750): getResourceName:com.android.mms:xml/assistant_messaging
I/ActivityManager( 1016): Killing 3349:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3750): took 0.688958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb9067b40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88cecf8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TimaKeyStoreProvider( 4159): TimaSignature is unavailable
,D/ActivityThread( 4159): Added TimaKeyStore provider
,E/SMD     (  288): DCD OFF
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.765104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b631f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1788): DispatchingService.onDestroy()
,I/GCoreUlr( 1788): Stopping handler for UlrDispSvcFast
,I/AMMetaDataParserService( 3750): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourcesManager( 4159): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4159): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4159): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/GCoreUlr( 1788): Unbound from all location providers
,I/GCoreUlr( 1788): Place inference reporting - stopped
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 1.719114ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b392e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3349/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/QuickConnect( 4159): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4159): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1016): name = scon_is_running
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10125
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4159): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.729427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b20ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b1c760 counterpartCT=4 counterpartW=96 counterparth=96
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,I/QuickConnect( 4159): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3750): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/Zygote  ( 4174): MountEmulatedStorage()
E/Zygote  ( 4174): v2
I/libpersona( 4174): KNOX_SDCARD checking this for 10131
I/libpersona( 4174): KNOX_SDCARD not a persona
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SELinux ( 4174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/GFX raster( 3750): took 0.653230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb88cf358 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b20f20 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4174 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Killing 3113:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
E/SELinux ( 4174): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4174): TimaSignature is unavailable
D/ActivityThread( 4174): Added TimaKeyStore provider
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.812657ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b60970 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88cecf8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4174): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4174): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4174): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4174): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3750): Resource data:2131099648
,I/AMMetaDataParserService( 3750): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.705573ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb9067b40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b392e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.645260ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b600f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8b1b6e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/SBrowserFeatureFlag( 4174): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.644271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b61280 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b1c608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ManifestProvider( 4174): onCreate()
,W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3113/cgroup.procs: No such file or directory
,E/NetworkSettingsReceiver( 4174): onReceive: android.intent.action.BOOT_COMPLETED
,E/SBrowserFeatureFlag( 4174): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@14d7d5fa
,D/SBrowserFeatureFlag( 4174): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4174): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4193): MountEmulatedStorage(),
E/Zygote  ( 4193): v2,
I/libpersona( 4193): KNOX_SDCARD checking this for 10135
I/libpersona( 4193): KNOX_SDCARD not a persona
,I/SELinux ( 4193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4193): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/GFX raster( 3750): took 0.637708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b63180 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88cecf8 counterpartCT=4 counterpartW=96 counterparth=96,
,I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4193 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3389:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3750): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4193): TimaSignature is unavailable
,D/ActivityThread( 4193): Added TimaKeyStore provider
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.671979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b631f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b1cbc8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4193): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4193): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4193): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAv4-SVC( 3524): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 3643): Thread[GAThread,5,main]: No campaign data found.
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.762552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb8b5ec60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b426b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3750): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3389/cgroup.procs: No such file or directory
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.m,ms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3750): Resource data:Loop for r,unning activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131165197
W/ResourcesManager( 3750): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3750): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
I/AMMetaDataParserService( 3750): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3750): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3750): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/Zygote  ( 4219): MountEmulatedStorage(),
E/Zygote  ( 4219): v2
I/libpersona( 4219): KNOX_SDCARD checking this for 10139
I/SELinux ( 4219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4219): KNOX_SDCARD not a persona
,I/SELinux ( 4219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4219 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/art     ( 1611): Explicit concurrent mark sweep GC freed 6026(233KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 800us total 39.548ms
,D/TimaKeyStoreProvider( 4219): TimaSignature is unavailable
,D/ActivityThread( 4219): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ResourcesManager( 4219): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4219): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4219): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4219): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4219): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/SQLiteConnectionPool( 1611): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131165197
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3750): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,I/dex2oat ( 3965): dex2oat took 3.111s (threads: 4)
,I/AMMetaDataParserService( 3750): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
E/Zygote  ( 4240): MountEmulatedStorage()
E/Zygote  ( 4240): v2
I/libpersona( 4240): KNOX_SDCARD checking this for 10145
I/libpersona( 4240): KNOX_SDCARD not a persona
I/SELinux ( 4240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4240 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3371:com.wssnps/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3750): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/DexOptUtils( 3524): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
,D/DexOptUtils( 3524): Set odex to world readable.
,D/DexOptUtils( 3524): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
,D/FileApkUtils( 3524): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/TimaKeyStoreProvider( 4240): TimaSignature is unavailable
,D/ActivityThread( 4240): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3750): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/GmsModuleFndr( 3524): Beginning GMS chimera module scan
,I/ActivityManager( 1016): Killing 3135:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3371/cgroup.procs: No such file or directory
,W/ResourcesManager( 4240): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4240): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4240): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4240): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4240): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/GmsModuleFndr( 3524): Module pkg com.google.android.apps.kids.familylink not installed, skipping
,D/ChimeraCfgMgr( 3524): Beginning module configuration check
,D/ChimeraCfgMgr( 3524): Module APKs unchanged, check complete
,I/ActivityManager( 1016): Killing 3478:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3750): Resource data:2131165197
,I/AMMetaDataParserService( 3750): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,I/AMMetaDataParserService( 3750): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3135/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3478/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3750): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3750): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3750): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
,I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3750): getResourcePackageName:android.wallpaper.preview
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant
I/AMMetaDataParserService( 3750): Resource data:2131099648
,W/ResourcesManager( 3750): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,I/AMMetaDataParserService( 3750): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3750): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4262): MountEmulatedStorage()
,E/Zygote  ( 4262): v2
I/libpersona( 4262): KNOX_SDCARD checking this for 10072
I/libpersona( 4262): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.GridSettings
I/SELinux ( 4262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:assistant,
I/AMMetaDataParserService( 3750): Resource data:2131165220
,I/SELinux ( 4262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4262): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3750): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3750): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3750): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3750): getResourceTypeNamexml
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3750): took 0.772500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb925e980 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb925e6b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4262 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/AMMetaDataParserService( 3750): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4262): TimaSignature is unavailable
,D/ActivityThread( 4262): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 686us total 21.128ms
,E/        ( 3750): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3750): took 0.642344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3750): Bitmap=0xb925e7d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9271228 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,I/AMMetaDataParserService( 3750): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.026ms
,D/BadgeProvider( 4262): onCreate
,D/BadgeProvider( 4262): DatabaseHelper
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.652ms
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.,settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserServic,e( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
D/BadgeProvider( 4262): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1016): Killing 3513:com.android.managedprovisioning/u0a22 (adj 15): empty #31
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMM,etaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/libpersona( 4284): KNOX_SDCARD checking this for 10146
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/libpersona( 4284): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4284 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1016): Killing 3243:com.sec.pcw.device/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/ActivityManager( 1016): Killing 3547:com.samsung.android.MtpApplication/1000 (adj 15): empty #32
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3750): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3750): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3750): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/BadgeProvider( 4262): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4262): sendNotify, [notify] : null
D/BadgeProvider( 4262): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4262): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4262): update, [UpdateCount] : 1
D/Launcher.Model( 1469): reloadBadges entered.
E/Zygote  ( 4284): MountEmulatedStorage()
E/Zygote  ( 4284): v2
I/SELinux ( 4284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4284): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4284): TimaSignature is unavailable
D/ActivityThread( 4284): Added TimaKeyStore provider
W/ResourcesManager( 4284): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3243/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3513/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3547/cgroup.procs: No such file or directory
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
I/Process ( 4240): Sending signal. PID: 4240 SIG: 9
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4300): MountEmulatedStorage(),
E/Zygote  ( 4300): v2
I/libpersona( 4300): KNOX_SDCARD checking this for 1000
I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 4300): KNOX_SDCARD not a persona
,I/SELinux ( 4300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Killing 3415:com.samsung.android.sm/1000 (adj 15): empty #31
,I/SELinux ( 4300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4300): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/JavaBinder( 4284): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/Process ( 4284): Sending signal. PID: 4284 SIG: 9
,D/TimaKeyStoreProvider( 4300): TimaSignature is unavailable
,D/ActivityThread( 4300): Added TimaKeyStore provider,
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4318): MountEmulatedStorage()
,I/libpersona( 4318): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4318): v2
I/libpersona( 4318): KNOX_SDCARD not a persona
E/lowmemorykiller(  255): Error opening /proc/4240/oom_score_adj; errno=2
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4318 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Killing 3585:com.sec.factory.camera/1000 (adj 15): empty #31
,I/SELinux ( 4318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ProcessCpuTracker( 1016): Skipping unknown process pid 4240
I/ActivityManager( 1016): Process com.android.email (pid 4240)(adj 11) has died(114,1125)
,D/TimaKeyStoreProvider( 4318): TimaSignature is unavailable
,D/ActivityThread( 4318): Added TimaKeyStore provider
,I/ActivityManager( 1016): Process com.android.exchange (pid 4284)(adj 9) has died(115,1125)
,D/SecurityLogAgent( 4318): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4318): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4318): StateMachine : Current State = 1
D/SecurityLogAgent( 4318): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3415/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1788): [216] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 3524): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 3524
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 1.874 ms
,D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 3524
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 3524
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 3.337 ms
,D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 3524
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3585/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1788): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1788): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/IcingInternalCorpora( 3524): getNumBytesRead when not calculated.
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/GCoreFlp( 1788): No location to return for getLastLocation()
,W/FusedLocationProvider( 1788): location=null
,E/MDM     ( 1788): [230] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1408): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1408): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 3524): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/AuthorizationBluetoothService( 1788): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/GCoreFlp( 1788): No location to return for getLastLocation()
,W/FusedLocationProvider( 1788): location=null
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1433): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4361): MountEmulatedStorage()
E/Zygote  ( 4361): v2
I/libpersona( 4361): KNOX_SDCARD checking this for 1000
I/libpersona( 4361): KNOX_SDCARD not a persona
,I/SELinux ( 4361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=4361 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,I/SELinux ( 4361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 4361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 4370): MountEmulatedStorage()
E/Zygote  ( 4370): v2
I/libpersona( 4370): KNOX_SDCARD checking this for 10044
I/libpersona( 4370): KNOX_SDCARD not a persona
,I/SELinux ( 4370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=4370 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SELinux ( 4370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4361): TimaSignature is unavailable
,D/ActivityThread( 4361): Added TimaKeyStore provider
,E/Zygote  ( 4387): MountEmulatedStorage()
I/libpersona( 4387): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4387): v2
I/libpersona( 4387): KNOX_SDCARD not a persona
I/SELinux ( 4387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=4387 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4370): TimaSignature is unavailable
,D/ActivityThread( 4370): Added TimaKeyStore provider
,E/Zygote  ( 4405): MountEmulatedStorage()
E/Zygote  ( 4405): v2
I/libpersona( 4405): KNOX_SDCARD checking this for 10152
,I/libpersona( 4405): KNOX_SDCARD not a persona
,I/SELinux ( 4405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4405 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 4405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4405): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4387): TimaSignature is unavailable
D/ActivityThread( 4387): Added TimaKeyStore provider
,W/ResourcesManager( 4387): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4405): TimaSignature is unavailable
,D/ActivityThread( 4405): Added TimaKeyStore provider
,W/ResourcesManager( 4370): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4370): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4370): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4370): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4370): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4370): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4370): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4370): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/AASAservice-UpdateReceiver( 4361): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.example.hello, uid = -1
,I/AASAservice-TokenRule( 4361): parseToken()
,W/System.err( 4361): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4361): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 4361): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 4361): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 4361): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 4361): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 4361): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4361): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4361): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4361): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4361): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4361): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4361): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4361): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4361): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 4361): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4361): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4361): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 4361): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 4361): 	... 14 more
E/AASAservice-TokenRule( 4361): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 4361): AASARuleUpdateResult() : Rule file is not exist.
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4421 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/SQLiteLog( 4405): (284) automatic index on shooting_modes(title_id)
E/Zygote  ( 4421): MountEmulatedStorage()
E/Zygote  ( 4421): v2
I/libpersona( 4421): KNOX_SDCARD checking this for 10015
I/libpersona( 4421): KNOX_SDCARD not a persona
,I/SELinux ( 4421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 4421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4421): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4432): MountEmulatedStorage()
E/Zygote  ( 4432): v2
I/libpersona( 4432): KNOX_SDCARD checking this for 10156
I/libpersona( 4432): KNOX_SDCARD not a persona
,I/SELinux ( 4432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4432 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 4432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4432): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3617:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4421): TimaSignature is unavailable
,D/ActivityThread( 4421): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4432): TimaSignature is unavailable
,D/ActivityThread( 4432): Added TimaKeyStore provider
,W/ContextImpl( 3750): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4456): MountEmulatedStorage()
,E/Zygote  ( 4456): v2
I/libpersona( 4456): KNOX_SDCARD checking this for 1000,
,I/SELinux ( 4456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4456): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Killing 3609:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4432): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 4432): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,D/TimaKeyStoreProvider( 4456): TimaSignature is unavailable
D/ActivityThread( 4456): Added TimaKeyStore provider
I/TapandpayWidget:Utils( 4432): Clear T&P info.
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3617/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4432): Widget is not attached.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3609/cgroup.procs: No such file or directory
,W/ResourcesManager( 4456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4477): MountEmulatedStorage()
,E/Zygote  ( 4477): v2
I/libpersona( 4477): KNOX_SDCARD checking this for 1000
I/libpersona( 4477): KNOX_SDCARD not a persona
,I/SELinux ( 4477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast,
I/SELinux ( 4477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4477): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  306): Explicit concurrent mark sweep GC freed 8760(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 23.100ms
,D/TimaKeyStoreProvider( 4477): TimaSignature is unavailable
,D/ActivityThread( 4477): Added TimaKeyStore provider,
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 16.946ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 16.562ms
,E/Zygote  ( 4492): MountEmulatedStorage(),
E/Zygote  ( 4492): v2
I/libpersona( 4492): KNOX_SDCARD checking this for 10091
I/libpersona( 4492): KNOX_SDCARD not a persona,
I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4492 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Killing 3656:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,E/SELinux ( 4492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3772): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 28758(1758KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 3.293ms total 153.088ms
,E/Zygote  ( 4505): MountEmulatedStorage()
E/Zygote  ( 4505): v2
I/libpersona( 4505): KNOX_SDCARD checking this for 10010
I/libpersona( 4505): KNOX_SDCARD not a persona
,I/SELinux ( 4505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4505 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 4505): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3574:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4492): TimaSignature is unavailable
,D/ActivityThread( 4492): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3684:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4505): TimaSignature is unavailable
,D/ActivityThread( 4505): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 4477): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4477): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4477): new DMDBOpenHelper instance
,D/NearbySource( 4370): Nearby Source Create!
,D/NearbyContext( 4370): Nearby Context Create!
,I/PCWCLIENTTRACE_PushUtil( 4477): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4477): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4477): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4477): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4522): MountEmulatedStorage()
,E/Zygote  ( 4522): v2
I/libpersona( 4522): KNOX_SDCARD checking this for 10032
I/libpersona( 4522): KNOX_SDCARD not a persona
,I/SELinux ( 4522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4522 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 3183:com.google.android.youtube/u0a166 (adj 15): empty #31
,I/SELinux ( 4522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3656/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4370): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 4370): Samsung link source created
,D/TimaKeyStoreProvider( 4522): TimaSignature is unavailable
,D/ActivityThread( 4522): Added TimaKeyStore provider
,D/ContactProvider( 4370): getAllContactInfoList Start
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 4370): PackagesMonitor onReceive :com.example.hello
,D/ContactProvider( 4370): getAllContactInfoList End
,I/syncContacts( 4370): thread: 693, sync time = 39
,I/FeatureConfig( 4522): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/DBG_POLICYDM( 3074): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4541): MountEmulatedStorage()
E/Zygote  ( 4541): v2
I/libpersona( 4541): KNOX_SDCARD checking this for 10038
I/libpersona( 4541): KNOX_SDCARD not a persona
I/SELinux ( 4541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4541 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4541): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3643:com.google.android.gm/u0a101 (adj 15): empty #31
,W/ResourcesManager( 4522): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4541): TimaSignature is unavailable
,D/ActivityThread( 4541): Added TimaKeyStore provider
W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 4541): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4541): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_3574/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_3684/cgroup.procs: No such file or directory
,W/ResourcesManager( 4522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageBroadcastService( 3524): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3524): Loading module APK com.google.android.play.games
,W/ResourcesManager( 4522): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4522): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4522): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10166/pid_3183/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_3643/cgroup.procs: No such file or directory
,W/GalaxyFinderApplication( 4522): system/finder_cp/cpdata.xml file not found
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/PhotosPlugin( 4492): Loading PhotosPlugin
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  288): DCD OFF
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=4558 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 4558): MountEmulatedStorage(),
,E/Zygote  ( 4558): v2
,I/libpersona( 4558): KNOX_SDCARD checking this for 10032
I/libpersona( 4558): KNOX_SDCARD not a persona
,I/SELinux ( 4558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4558): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4558): TimaSignature is unavailable
,D/ActivityThread( 4558): Added TimaKeyStore provider
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4584): MountEmulatedStorage()
,E/Zygote  ( 4584): v2
I/libpersona( 4584): KNOX_SDCARD checking this for 10046
I/libpersona( 4584): KNOX_SDCARD not a persona
,I/SELinux ( 4584): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=4584 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 4584): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4584): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4584): TimaSignature is unavailable
,D/ActivityThread( 4584): Added TimaKeyStore provider
,I/SL_DEBUG( 4541): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 4541): isLoggable:: SL_DEBUG_EXIST = false
,W/ResourcesManager( 4584): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4584): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4584): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4584): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4584): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4584): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3524): Module APK com.google.android.play.games already loaded
,D/Mms/MmsApp( 4584): [start]    onCreate() consume time = 0.0
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3524): Submit a task: k
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3896:com.sec.android.soagent/u0a34 (adj 15): empty #31
,W/art     ( 3524): Suspending all threads took: 7.763ms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4541): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1016): lcd : 24 +
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/lights  ( 1016): lcd : 24 -
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1016): lcd : 19 +
,I/art     ( 3524): Background sticky concurrent mark sweep GC freed 17153(1390KB) AllocSpace objects, 22(352KB) LOS objects, 13% free, 12MB/14MB, paused 20.456ms total 149.471ms
,W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_3896/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/Icing   ( 3524): Storage manager: low false usage 1.73MB avail 10.18GB capacity 11.68GB
,D/lights  ( 1016): lcd : 19 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/k       ( 3524): Processing package: com.example.hello
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,D/GassUtils( 3524): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/k       ( 3524): Found info for package com.example.hello in db.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4541): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,W/art     ( 4584): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 164.154ms
,I/SA      ( 3945): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 3945): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 3945): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 3524): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,W/BaseAppContext( 3524): Using Auth Proxy for data requests.
,W/art     ( 4584): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 117.432ms
,D/Mms/ArtClassLoader( 4584): init before art
,D/Mms/TelephonyPermission( 4584): start operation mode monitor
,W/ResourcesManager( 4584): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 3970:com.samsung.helphub/1000 (adj 15): empty #31
,D/Mms/TelephonyPermission( 4584): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4584): isDefault true
,D/Mms/MmsApp( 4584): onCreate() com.android.mms
,D/Mms/MmsApp( 4584): [start]    initCountryIso consume time = 459.779114
,D/CountryDetector( 1016): The first listener is added
,D/Mms/MmsApp( 4584): [end]    initCountryIso consume time = 6.534427
D/Mms/MmsConfig( 4584): [start]    MmsConfig.init() consume time = 0.122188
,D/Mms/MmsConfig( 4584): before partial update
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/Mms/MmsConfig( 4584): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4584): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4584): isAuth is false
,D/Mms/MmsConfig( 4584): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1449): query,matched:2117, calling pid = 4584
,D/TP/MmsSmsProvider( 1449): match 2117:Elapsed time : 2.144 ms
,D/EasySignUpManager_1.0.1( 4584): isAuth is false
D/EasySignUpManager_1.0.1( 4584): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4584): mps_code.dat does not exist
E/CscParser( 4584): customer_path =/system/csc/customer.xml
E/CscParser( 4584): fileName + /system/csc/customer.xml
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3970/cgroup.procs: No such file or directory
,E/CscParser( 4584): mps_code.dat does not exist
,E/CscParser( 4584): customer_path =/system/csc/customer.xml
,E/CscParser( 4584): fileName + /system/csc/customer.xml
,D/CscParser( 4584): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4584):  enable multiwindow = true
,E/Mms/MessageUtils( 4584): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4584): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4584): [end]    init() consume time = 130.595625
,D/Mms/Contact( 4584): [start]    init() consume time = 0.808385
,D/TP/MmsSmsProvider( 1449): query,matched:13, calling pid = 4584
,D/TP/MmsSmsProvider( 1449): match 13:Elapsed time : 1.809 ms
,D/Mms/Contact( 4584): [end]    init consume time = 17.233334
,D/Mms/DraftCache( 4584): [start]    rebuildCache consume time = 20.533489
,D/TP/MmsSmsProvider( 1449): query,matched:12, calling pid = 4584
,D/TP/MmsSmsProvider( 1449): match 12:Elapsed time : 2.352 ms
,D/Mms/MethodReflector( 4584): getSubId is called
D/Mms/DraftCache( 4584): [end]    rebuildCache consume time = 11.992761
,D/Mms/TelephonyUtils( 4584): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4584): getTelephonyProperty is called
D/Mms/DownloadManager( 4584): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4584): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4584): auto download without roaming -> true
D/Mms/DownloadManager( 4584): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 4584): getSubId is called
,D/Mms/MethodReflector( 4584): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4584): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4584): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4584): getTelephonyProperty is called
D/Mms/DownloadManager( 4584): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4584): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4584): auto download without roaming -> true
D/Mms/DownloadManager( 4584): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4584): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4584): mAutoDownload ------> true
,D/ComposerPerformance( 4584): 1457533289484 ms / [DONE] Composer constructor
,E/CII     ( 4584): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4584): ReservationManager()
,I/Mms/ReservationManager( 4584): resetAfterConnected()
,D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 4584
,D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 3.329 ms
,I/Mms/ReservationManager( 4584): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 4584): [end]    onCreate() consume time = 70.334531
,D/Mms/Conversation( 4584): [start]    init() consume time = 1.470677
,D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1449): (284) automatic index on im_threads(normal_thread_id)
,W/GAV2    ( 4492): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
,D/Mms/DownloadManager( 4584): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4584): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4584): getSubId is called
D/Mms/TelephonyUtils( 4584): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4584): getTelephonyProperty is called
D/Mms/DownloadManager( 4584): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4584): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4584): auto download without roaming -> true
D/Mms/DownloadManager( 4584): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4584): mAutoDownload ------> true
,D/Mms/Conversation( 4584): [end]    init consume time = 35.805104
,D/Mms/FreeMessageStatusReceiver( 4584): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,D/Mms/MessagingNotification( 4584): [start]    init() consume time = 13.443229
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4645): MountEmulatedStorage(),
,I/libpersona( 4645): KNOX_SDCARD checking this for 10047
E/Zygote  ( 4645): v2
I/libpersona( 4645): KNOX_SDCARD not a persona
I/SELinux ( 4645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4645 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
E/SELinux ( 4645): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,D/Mms/MessagingNotification( 4584): [end]    init consume time = 27.475938
,D/Mms/SpamFilter( 4584): [start]    SpamFilter fill() begin consume time = 6.741979
,D/TP/MmsSmsProvider( 1449): query,matched:0, calling pid = 4584
V/TP/MmsSmsProvider( 1449): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1449): match 0:Elapsed time : 4.499 ms
,D/Mms/Synchronizer( 4584): [start]    doSync consume time = 12.759114
,D/Mms/FreeMessageReceiverService( 4584): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 4584): onHandleIntent: ACTION_PACKAGE_ADDED
,D/TP/MmsSmsProvider( 1449): query,matched:400, calling pid = 4584
,D/TP/MmsSmsProvider( 1449): update, matched:300, calling pid = 4584
,V/TP/MmsSmsProvider( 1449): syncDBData start
,D/TimaKeyStoreProvider( 4645): TimaSignature is unavailable
,D/ActivityThread( 4645): Added TimaKeyStore provider
,V/TP/MmsSmsProvider( 1449): syncDBData sms end
,V/TP/MmsSmsProvider( 1449): syncDBData mms end
,V/TP/MmsSmsProvider( 1449): syncDBData end
,I/ActivityManager( 1016): Killing 4006:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,D/Mms/Synchronizer( 4584): [end]    doSync consume time = 31.993282
,D/Mms/SpamFilter( 4584): [end]    SpamFilter fill() finished consume time = 12.885104
,W/ResourcesManager( 4645): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4645): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4645): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/ArtClassLoader( 4584): init [DONE] art
,D/Mms/MessagingNotification( 4584): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1449): query,matched:26, calling pid = 4584
,D/TP/SmsProvider( 1449): match 26:Elapsed time : 1.133 ms
,D/TP/MmsSmsProvider( 1449): query,matched:6, calling pid = 4584
,D/TP/MmsSmsProvider( 1449): match 6:Elapsed time : 2.803 ms
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4664): MountEmulatedStorage()
E/Zygote  ( 4664): v2
I/libpersona( 4664): KNOX_SDCARD checking this for 10025
I/libpersona( 4664): KNOX_SDCARD not a persona
,I/SELinux ( 4664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4664): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4664 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4006/cgroup.procs: No such file or directory
,W/ResourcesManager( 4558): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4664): TimaSignature is unavailable
,D/ActivityThread( 4664): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 4032:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,W/ResourcesManager( 4558): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4558): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4558): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MyFiles ( 4645): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,W/ResourcesManager( 4664): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4032/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Killing 4056:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
,I/TactileAssist( 1016): enable value -1
,I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/TactileAssist( 1016): List of disabled apps :
,E/Zygote  ( 4679): MountEmulatedStorage(),
E/Zygote  ( 4679): v2
I/libpersona( 4679): KNOX_SDCARD checking this for 10004,
I/SELinux ( 4679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4679): KNOX_SDCARD not a persona
,I/SELinux ( 4679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4679): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4679 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4679): TimaSignature is unavailable
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 4679): Added TimaKeyStore provider
,I/Icing   ( 3524): updateResources: need to parse f{com.google.android.gms},
,I/OMACP   ( 4664): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !,
,E/Zygote  ( 4696): MountEmulatedStorage(),
E/Zygote  ( 4696): v2
I/libpersona( 4696): KNOX_SDCARD checking this for 10053
I/libpersona( 4696): KNOX_SDCARD not a persona
,I/SELinux ( 4696): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ChimeraCfgMgr( 3524): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3524): Module APK com.google.android.play.games already loaded
,I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4696 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 4696): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4696): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/art     ( 4492): Suspending all threads took: 10.602ms
,D/Mms/Omacp( 4584): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/installd(  284): system dir 0 : /system/app/
E/installd(  284): system dir 1 : /system/priv-app/
E/installd(  284): system dir 2 : /vendor/app/
E/installd(  284): system dir 3 : /oem/app/
,D/TimaKeyStoreProvider( 4696): TimaSignature is unavailable,
D/ActivityThread( 4696): Added TimaKeyStore provider
,D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,W/ResourcesManager( 4696): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4664): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_4056/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4696): onReceive() it will make start service,
,E/Zygote  ( 4719): MountEmulatedStorage()
I/libpersona( 4719): KNOX_SDCARD checking this for 10100
E/Zygote  ( 4719): v2
I/libpersona( 4719): KNOX_SDCARD not a persona
,I/SELinux ( 4719): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4719): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4719 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3989:com.android.providers.calendar/u0a42 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
E/SELinux ( 4719): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
E/Watchdog( 1016): !@Sync 1
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,V/GLSActivity( 1788): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,D/Compatibility( 4696): onHandleIntent()
,D/Compatibility( 4696): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
,D/Compatibility( 4696): found: 2
,W/GAV2    ( 4492): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 4719): TimaSignature is unavailable
D/ActivityThread( 4719): Added TimaKeyStore provider
I/art     (  306): Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 32.201ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4696): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/SettingsProvider( 1016): name = audio_safe_volume_state
,D/Compatibility( 4696): skipping ResolveInfo{18e7c06d com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
,D/Compatibility( 4696): considering ResolveInfo{389c54a2 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,D/Compatibility( 4696): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 4696): enabling receiver ResolveInfo{13a59533 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 4696): enabling receiver ResolveInfo{296840f0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.212ms
,D/Compatibility( 4696): enabling receiver ResolveInfo{eccf669 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 4696): enabling receiver ResolveInfo{3e8f18ee com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 4696): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 16.848ms
,E/Zygote  ( 4740): MountEmulatedStorage()
,E/Zygote  ( 4740): v2
I/libpersona( 4740): KNOX_SDCARD checking this for 10057
I/libpersona( 4740): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4740 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 4740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4740): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{2f96c48b u0 com.samsung.android.providers.context/.ContextService}
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_3989/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4740): TimaSignature is unavailable
,D/ActivityThread( 4740): Added TimaKeyStore provider
,W/AccountFeatureHelper( 4492): Write apps_features disabled false
D/PackageIntentReceiver( 4719): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 4719): Not GearManger package! 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4756): MountEmulatedStorage()
I/libpersona( 4756): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4756): v2
I/libpersona( 4756): KNOX_SDCARD not a persona
,I/SELinux ( 4756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4119:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/SELinux ( 4756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4756): TimaSignature is unavailable
,D/ActivityThread( 4756): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4119/cgroup.procs: No such file or directory
,W/GAV2    ( 4492): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4773): MountEmulatedStorage()
E/Zygote  ( 4773): v2
I/libpersona( 4773): KNOX_SDCARD checking this for 1000
I/libpersona( 4773): KNOX_SDCARD not a persona
,I/SELinux ( 4773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4773 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Killing 4159:com.samsung.android.sconnect/u0a125 (adj 15): empty #31,
,E/SELinux ( 4773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4773): TimaSignature is unavailable
,D/ActivityThread( 4773): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 4740): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 4773): Received: android.intent.action.PACKAGE_ADDED
,E/Zygote  ( 4790): MountEmulatedStorage(),
,W/ContextImpl( 4773): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 4790): v2,
I/libpersona( 4790): KNOX_SDCARD checking this for 10120
I/libpersona( 4790): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4790 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4790): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4790): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4790): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4174:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{10384bd u0 com.android.settings/.wifi.WifiCredService}
,D/AcmsService( 4773): Enter Oncreate
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 22875(1371KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.693ms total 152.356ms
,D/AcmsServiceMonitor( 4773): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsService( 4773): creating AcmsCore
,D/AcmsCore( 4773): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 4773): AcmsCore
,D/TimaKeyStoreProvider( 4790): TimaSignature is unavailable
,D/ActivityThread( 4790): Added TimaKeyStore provider
,D/AcmsCore( 4773): init
D/AcmsCore( 4773): Looper handler is not null
D/AcmsCore( 4773): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4773): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4773): Incrementing - Counter value: 1
D/AcmsCore( 4773): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 4773): onStartCommand
D/AcmsService( 4773): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 4773): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 4773): Incrementing - Counter value: 2
D/AcmsService( 4773): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr( 4773): AcmsCertificateMngr
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 4773): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 4773): AcmsRevocationMngr
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4790): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AcmsService( 4773): Inside handle Intent
,D/AcmsService( 4773): App added - package name: com.example.hello
D/AcmsCore( 4773): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4773): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4773): Incrementing - Counter value: 3
D/AcmsCore( 4773): Incremented Counter Value: postToAcmsCoreHandler =>2
,D/AcmsService( 4773): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 4773): Decrementing - Counter value: 2
,D/LocationManagerService( 1016): getProviders()=[passive]
,W/libprocessgroup( 1016): failed to open /acct/uid_10125/pid_4159/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_4174/cgroup.procs: No such file or directory
,I/Icing   ( 3524): Internal init done: storage state 0
,I/Icing   ( 3524): Post-init done
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/UpdateIcingCorporaServi( 4740): UpdateCorporaTask done [took 85 ms] updated apps [took 85 ms] 
,I/ActivityManager( 1016): Killing 4193:com.android.calendar/u0a135 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_4193/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4822): MountEmulatedStorage(),
E/Zygote  ( 4822): v2
I/libpersona( 4822): KNOX_SDCARD checking this for 10142
,I/libpersona( 4822): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=4822 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 4822): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4822): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4822): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 4219:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4822): TimaSignature is unavailable
,D/ActivityThread( 4822): Added TimaKeyStore provider
,V/TaskCloserActivity( 4822): TaskCloserActivity enter()
,V/TaskCloserActivity( 4822): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/ActivityManager( 1016): Killing 4300:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_4219/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4300/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1788): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4838): MountEmulatedStorage()
E/Zygote  ( 4838): v2
I/libpersona( 4838): KNOX_SDCARD checking this for 1000
I/libpersona( 4838): KNOX_SDCARD not a persona
,I/SELinux ( 4838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4838 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
I/SELinux ( 4838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4838): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4838): TimaSignature is unavailable
,D/ActivityThread( 4838): Added TimaKeyStore provider
,D/Mms/Contact( 4584): sContactsObserver.onChange(),selfUpdate=false
I/ValidateNoPeople( 1016): mEvictionCount: 0
,D/Mms/Contact( 4584): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4584): [start]    invalidate() consume time = 1622.483593
D/Mms/ContactsCache( 4584): [end]    invalidate() consume time = 0.148021
E/MTPRx   ( 4838): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
D/ContactProvider( 4370): getAllContactInfoList Start
,V/MTPRx   ( 4838): sealedState: false
V/MTPRx   ( 4838): sealedUsbMassStorageState: false
E/MTPRx   ( 4838): check value of boot_completed is1
E/MTPRx   ( 4838): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4838): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4838): Status for mount/Unmount :removed
E/MTPRx   ( 4838): SDcard is not available
,W/MTPRx   ( 4838): value of connected istrue
,W/MTPRx   ( 4838): value of configured istrue
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
,D/ContactProvider( 4370): getAllContactInfoList End
,I/syncContacts( 4370): thread: 695, onChange
,D/SettingsProvider( 1016): name = boot_time_connected
,E/MTPRx   ( 4838): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4838): noti = 17
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4838): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MTPRx   ( 4838): else part ... so first time!!!
,E/MTPPlaObsrvr( 4838): inside setContext()
E/MTPPlaObsrvr( 4838):  inside createplafiles
,I/SecKeyguardClockSingleView( 1180): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4838): playlist count is0
,E/MTPPlaObsrvr( 4838):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4838):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4838): Inside registerContentObserver
,E/MtpAdbObserver( 4838): inside setContext()
,E/MtpAdbObserver( 4838): Inside registerContentObserver
,W/Settings( 4838): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MtpService( 4838): onCreate.
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,V/MtpMediaDBManager( 4838): inside deleteAllDB
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4838): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4838): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 4838): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4838): onStartCommand.
,W/MTPRx   ( 4838): calling native method
E/MTPJNIInterface( 4838): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 4838): handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4838): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4838): noti = 10
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/MtpService( 4838): onStartCommand.
,W/MTPRx   ( 4838): calling native method
,V/MtpMediaDBManager( 4838): inside Thread updateDB
E/MTPRx   ( 4838): Checking the driver time out
E/MTPJNIInterface( 4838): noti = 2
D/        ( 4838): deleting sockets before message queue initialization
D/        ( 4838): event handler thread is created, so set the flag
E/MTPRx   ( 4838): called native method
E/MTPJNIInterface( 4838): setting Media scanner status0
E/MTPJNIInterface( 4838): After setting Media scanner status0
E/SMD     (  288): DCD OFF
W/MTPRx   ( 4838): notification from stack 1
,E/        ( 4838): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594],
E/MTPJNIInterface( 4838): Getting media scanner status0
D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/MTPJNIInterface( 4838): DeviceName is A5-1
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/MtpService( 4838): handleMessage. msg= { when=-11ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1311): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1311): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1311): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457554860000
,D/daemonapp( 1311): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457533291401
D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/MtpMediaDBManager( 4838): count : 27
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1311): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1311): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1311): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1311): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4863): MountEmulatedStorage(),
E/Zygote  ( 4863): v2
I/libpersona( 4863): KNOX_SDCARD checking this for 10111
I/libpersona( 4863): KNOX_SDCARD not a persona
,I/SELinux ( 4863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4863 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 4863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4863): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/MtpMediaDBManager( 4838): sending db update complete noti to stack
E/MTPJNIInterface( 4838): noti = 29
,E/MTPJNIInterface( 4838): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4838): SDcard is not available
,E/        ( 4838): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,D/TimaKeyStoreProvider( 4863): TimaSignature is unavailable
,D/ActivityThread( 4863): Added TimaKeyStore provider
E/        ( 4838): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 4838): Status for mount/Unmount :removed
E/MTPJNIInterface( 4838): SDcard is not available
,E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
E/SQLiteLog( 4838): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
E/SQLiteLog( 4838): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
E/SQLiteLog( 4838): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4838): (21) API call with NULL database connection pointer
E/SQLiteLog( 4838): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4838): notification from stack 2
,D/        ( 4838): [mtp_init_device] Library open with 32 bits.
D/        ( 4838): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4838): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4838): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4838):  [sua_support_present:1287] returning false 
D/        ( 4838): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
