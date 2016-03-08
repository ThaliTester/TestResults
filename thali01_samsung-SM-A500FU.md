#### Test 617033519c823d7_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/System.out( 2145): Reading bundled version for services.json
I/System.out( 2145): Reading bundled version for dynamicStrings.json
I/System.out( 2145): Parsed section Cover Stories, private: false
--------- beginning of system
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2194): MountEmulatedStorage()
E/Zygote  ( 2194): v2
I/libpersona( 2194): KNOX_SDCARD checking this for 10113
I/libpersona( 2194): KNOX_SDCARD not a persona
I/SELinux ( 2194): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2194): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.audio.MediaButtonIntentReceiver: pid=2194 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 2194): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2194): TimaSignature is unavailable
D/ActivityThread( 2194): Added TimaKeyStore provider
I/System.out( 2091): INFO:Resource not found:/Common.properties Using default values
E/USB_UICC(  298): Timeout! No signal received. Retry num = 20
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2194): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2194): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2194): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2194): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
I/WebViewFactory( 2194): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
I/LibraryLoader( 2194): Time to load native libraries: 11 ms (timestamps 7080-7091)
I/LibraryLoader( 2194): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2194): Binding Chromium to main looper Looper (main, tid 1) {191c1fe6}
I/LibraryLoader( 2194): Expected native library version number "",actual native library version number ""
I/chromium( 2194): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2194): Initializing chromium process, singleProcess=true
W/art     ( 2194): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2194): ApplicationContext is null in ApplicationStatus
W/chromium( 2194): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 2194): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 2194): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 2194): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
I/Adreno-EGL( 2194): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2194): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2194): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2194): Local Branch: 
I/Adreno-EGL( 2194): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2194): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2194):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/AndroidRuntime( 2230): 
D/AndroidRuntime( 2230): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2230): CheckJNI is OFF
D/AndroidRuntime( 2230): readGMSProperty: start
D/AndroidRuntime( 2230): readGMSProperty: already setted!!
D/AndroidRuntime( 2230): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2230): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2230): readGMSProperty: end
D/AndroidRuntime( 2230): addProductProperty: start
W/AudioManagerAndroid( 2194): Requires BLUETOOTH permission
I/NSApplication( 2194): Starting up...
D/SettingsProvider( 1014): name = vibrate_in_silent
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/CscReceiver( 1443): onReceive android.intent.action.SIM_STATE_CHANGED
W/ResourcesManager( 1443): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/CscReceiver( 1443): Recieve Sim State Changed : ABSENT
I/splitIntent( 1014): Split this intent : android.intent.action.SIM_STATE_CHANGED, mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10, mBgSplitQueueNum=3 divideNum= 3 r.nextReceiver= 1 receivers.size=13
I/splitIntent( 1014): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
E/AffinityControl( 2230): AffinityControl: registerfunction enter
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1443, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.fmm.dm
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.settings
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2258): MountEmulatedStorage()
E/Zygote  ( 2258): v2
I/libpersona( 2258): KNOX_SDCARD checking this for 1000
I/libpersona( 2258): KNOX_SDCARD not a persona
I/SELinux ( 2258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/AndroidRuntime( 2230): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=2258 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/WifiApBroadcastReceiver( 1282): onReceive: action android.intent.action.SIM_STATE_CHANGED
I/SELinux ( 2258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.SecSetupWizard
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
E/Zygote  ( 2271): MountEmulatedStorage()
E/Zygote  ( 2271): v2
I/libpersona( 2271): KNOX_SDCARD checking this for 1000
I/libpersona( 2271): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=2271 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.google.android.partnersetup
I/SELinux ( 2271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TimaKeyStoreProvider( 2258): TimaSignature is unavailable
E/SELinux ( 2271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 2258): Added TimaKeyStore provider
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1014): mDVFSHelper.acquire()
D/FocusedStackFrame( 1014): Set to : 0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1466): onPause
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1014): Focused application set to: xxxx
D/Launcher( 1466): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/InputDispatcher( 1014): Focus left window: 1466
D/AndroidRuntime( 2230): Shutting down VM
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/TimaKeyStoreProvider( 2271): TimaSignature is unavailable
D/ActivityThread( 2271): Added TimaKeyStore provider
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=10 createSurf (1x1),1 flag=404, iello
D/BootupListener( 1443): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider( 1014): name = internet_call_settings_visibility
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=1001
D/PhoneUtilsCommon( 1443): isSupportVoLTE is false.
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2292): MountEmulatedStorage()
E/Zygote  ( 2292): v2
I/libpersona( 2292): KNOX_SDCARD checking this for 10174
I/libpersona( 2292): KNOX_SDCARD not a persona
I/SELinux ( 2292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2292 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2292): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.mms
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
V/ActivityThread( 1466): updateVisibility : ActivityRecord{1b3adc5b token=android.os.BinderProxy@41aaeec {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/Zygote  ( 2303): MountEmulatedStorage()
I/libpersona( 2303): KNOX_SDCARD checking this for 10046
E/Zygote  ( 2303): v2
I/libpersona( 2303): KNOX_SDCARD not a persona
I/SELinux ( 2303): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2303): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.transaction.SmsReceiver: pid=2303 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 2303): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/StatusChecker( 2258): onReceive : android.intent.action.SIM_STATE_CHANGED
D/TimaKeyStoreProvider( 2292): TimaSignature is unavailable
D/ActivityThread( 2292): Added TimaKeyStore provider
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1014): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1466): onStop
D/TimaKeyStoreProvider( 2303): TimaSignature is unavailable
D/ActivityThread( 2303): Added TimaKeyStore provider
V/ActivityThread( 1466): updateVisibility : ActivityRecord{1b3adc5b token=android.os.BinderProxy@41aaeec {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/StatusChecker( 2258): onReceive : net.mt.init : 
D/StatusChecker( 2258): onReceive : preference initializing
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1014): isKioskContainerExistOnDevice
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.omc
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.omc, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2303): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 2303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2303): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2303): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2303): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 2303): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
E/Zygote  ( 2324): MountEmulatedStorage()
E/Zygote  ( 2324): v2
I/libpersona( 2324): KNOX_SDCARD checking this for 1000
I/libpersona( 2324): KNOX_SDCARD not a persona
I/SELinux ( 2324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=2324 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.modem.settings, hostingType: broadcast
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.modem.settings
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/Launcher( 1466): onTrimMemory. Level: 20
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2337): MountEmulatedStorage()
E/Zygote  ( 2337): v2
I/libpersona( 2337): KNOX_SDCARD checking this for 1000
I/libpersona( 2337): KNOX_SDCARD not a persona
I/SELinux ( 2337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/USB_UICC(  298): Timeout! No signal received. Retry num = 21
I/SELinux ( 2337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=2337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 2230): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/art     (  307): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 690us total 46.134ms
D/TimaKeyStoreProvider( 2324): TimaSignature is unavailable
D/ActivityThread( 2324): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2337): TimaSignature is unavailable
,D/ActivityThread( 2337): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 17.481ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 18.140ms
,I/Omc:Receiver( 2324): onReceive : android.intent.action.SIM_STATE_CHANGED
,I/WebViewFactory( 2292): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.tcpdumpservice
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.tcpdumpservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 2292): Time to load native libraries: 2 ms (timestamps 7744-7746)
I/LibraryLoader( 2292): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 2355): MountEmulatedStorage()
,E/Zygote  ( 2355): v2
I/libpersona( 2355): KNOX_SDCARD checking this for 1000
I/libpersona( 2355): KNOX_SDCARD not a persona
,I/SELinux ( 2355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=2355 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 2355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2355): TimaSignature is unavailable
,D/ActivityThread( 2355): Added TimaKeyStore provider
,V/WebViewChromiumFactoryProvider( 2292): Binding Chromium to main looper Looper (main, tid 1) {2b51d24e}
,I/LibraryLoader( 2292): Expected native library version number "",actual native library version number ""
I/chromium( 2292): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2292): Initializing chromium process, singleProcess=true
,W/art     ( 2292): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2292): ApplicationContext is null in ApplicationStatus
,W/chromium( 2292): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Omc:OmcData( 2324): omc.xml not exist
,I/Omc:Receiver( 2324): OM Customize disabled
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.sbrowser
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/chromium( 2292): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 2292): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 2292): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
E/Zygote  ( 2374): MountEmulatedStorage()
E/Zygote  ( 2374): v2
I/libpersona( 2374): KNOX_SDCARD checking this for 10131
I/libpersona( 2374): KNOX_SDCARD not a persona
I/SELinux ( 2374): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=2374 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2374): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2374): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/Adreno-EGL( 2292): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2292): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2292): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2292): Local Branch: 
I/Adreno-EGL( 2292): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2292): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2292):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/TimaKeyStoreProvider( 2374): TimaSignature is unavailable
,D/ActivityThread( 2374): Added TimaKeyStore provider
,W/ResourcesManager( 2374): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 2374): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2374): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 2374): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 2303): [start]    onCreate() consume time = 0.0
,D/BluetoothAdapter( 2292): 943008872: getState() :  mService = null. Returning STATE_OFF
,I/SurfaceFlinger(  256): id=9 Removed Mauncher (5/8)
,I/SurfaceFlinger(  256): id=9 Removed Mauncher (-2/8)
,W/art     ( 2303): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 110.067ms
,W/chromium( 2292): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/art     ( 2292): Attempt to remove local handle scope entry from IRT, ignoring
,D/SBrowserFeatureFlag( 2374): initialized in static block : loadCscFeatureValue() succeed! 
,D/Mms/ArtClassLoader( 2303): init before art
,D/Mms/TelephonyPermission( 2303): start operation mode monitor
,W/ResourcesManager( 2303): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 2303): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 2303): isDefault true
,D/Mms/MmsApp( 2303): onCreate() com.android.mms
,D/ManifestProvider( 2374): onCreate()
,W/AwContents( 2292): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2292): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2292): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2292): CordovaWebView is running on device made by: samsung
,W/art     ( 2292): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2292): Attempt to remove local handle scope entry from IRT, ignoring
,E/OperatorBookmarksSIMReceiver( 2374): onReceive runs..android.intent.action.SIM_STATE_CHANGED
,D/Mms/MmsApp( 2303): [start]    initCountryIso consume time = 596.626511
,D/OpenGLRenderer( 2292): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,D/PhoneWindow( 2292): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2292): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 2292
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2292): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2292): Initialized EGL, version 1.4
D/OpenGLRenderer( 2292): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2292): Enabling debug mode 0
,D/CountryDetector( 1014): The first listener is added
,D/Mms/MmsApp( 2303): [end]    initCountryIso consume time = 76.691927
,D/Mms/MmsConfig( 2303): [start]    MmsConfig.init() consume time = 0.386093
,D/Mms/MmsConfig( 2303): before partial update
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 22
,E/SMD     (  286): DCD OFF
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/Mms/MmsConfig( 2303): Load Resize quality : 80
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 2292): Timeline: Activity_idle id: android.os.BinderProxy@38c95575 time:28824
,I/SamsungIME( 1904): getCurrentCandidateView
,I/ActivityManager( 1014): Displayed Component not be shown by security: +1s366ms
,W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{a09b677 u0 com.example.hello/.MainActivity t10} time:28830
,D/EasySignUpManager_1.0.1( 2303): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 2303): isAuth is false
,D/Mms/MmsConfig( 2303): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1443): query,matched:2117, calling pid = 2303,
,D/TP/MmsSmsProvider( 1443): match 2117:Elapsed time : 31.922 ms
,D/EasySignUpManager_1.0.1( 2303): isAuth is false
,D/EasySignUpManager_1.0.1( 2303): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 2303): mps_code.dat does not exist
,E/CscParser( 2303): customer_path =/system/csc/customer.xml
E/CscParser( 2303): fileName + /system/csc/customer.xml
,E/CscParser( 2303): mps_code.dat does not exist
E/CscParser( 2303): customer_path =/system/csc/customer.xml
E/CscParser( 2303): fileName + /system/csc/customer.xml
,D/CscParser( 2303): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 2303):  enable multiwindow = true
,E/Mms/MessageUtils( 2303): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 2303): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 2303): [end]    init() consume time = 427.984896
,D/Mms/Contact( 2303): [start]    init() consume time = 4.606042
,D/Mms/ArtClassLoader( 2303): init [DONE] art
,I/SurfaceFlinger(  256): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  256): id=10 Removed iello (-2/8)
,D/SamsungIME( 1904): Dismiss ExpandCandiate
,D/TP/MmsSmsProvider( 1443): query,matched:13, calling pid = 2303
,W/BindingManager( 2292): Cannot call determinedVisibility() - never saw a connection for the pid: 2292
,D/TP/MmsSmsProvider( 1443): match 13:Elapsed time : 4.632 ms
,D/Mms/Contact( 2303): [end]    init consume time = 36.677395
,D/Mms/DraftCache( 2303): [start]    rebuildCache consume time = 8.741563
D/TP/MmsSmsProvider( 1443): query,matched:12, calling pid = 2303
D/TP/MmsSmsProvider( 1443): match 12:Elapsed time : 1.630 ms
D/Mms/MethodReflector( 2303): getSubId is called
D/Mms/TelephonyUtils( 2303): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 2303): getTelephonyProperty is called
D/Mms/DownloadManager( 2303): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2303): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 2303): auto download without roaming -> true
D/Mms/DownloadManager( 2303): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 2303): getSubId is called
D/Mms/MethodReflector( 2303): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 2303): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 2303): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 2303): getTelephonyProperty is called
D/Mms/DownloadManager( 2303): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 2303): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 2303): auto download without roaming -> true
D/Mms/DownloadManager( 2303): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 2303): auto download during roaming secondary -> false
D/Mms/DownloadManager( 2303): mAutoDownload ------> true
D/Mms/DraftCache( 2303): [end]    rebuildCache consume time = 15.508385
,I/chromium( 2292): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/ComposerPerformance( 2303): 1457426564837 ms / [DONE] Composer constructor
,E/CII     ( 2303): CommonIMSInterface: VoLTE CSC feature disabled.
,D/Mms/Conversation( 2303): [start]    init() consume time = 71.585521
I/Mms/ReservationManager( 2303): ReservationManager()
,I/Mms/ReservationManager( 2303): resetAfterConnected()
,D/TP/MmsSmsDatabaseHelper( 1443): [MmsSmsDb] tableName: threads hasAutoIncrement: CREATE TABLE threads (_id INTEGER PRIMARY KEY AUTOINCREMENT,date INTEGER DEFAULT 0,message_count INTEGER DEFAULT 0,recipient_ids TEXT,snippet TEXT,snippet_cs INTEGER DEFAULT 0,read INTEGER DEFAULT 1,archived INTEGER DEFAULT 0,type INTEGER DEFAULT 0,error INTEGER DEFAULT 0,has_attachment INTEGER DEFAULT 0,unread_count INTEGER DEFAULT 0,alert_expired INTEGER DEFAULT 1,reply_all INTEGER DEFAULT -1,group_snippet TEXT,message_type INTEGER DEFAULT 0,display_recipient_ids TEXT,translate_mode TEXT default 'off',secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0,classification INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 1443): [MmsSmsDb] tableName: canonical_addresses hasAutoIncrement: CREATE TABLE canonical_addresses (_id INTEGER PRIMARY KEY AUTOINCREMENT,address TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1443): [MmsSmsDb] tableName: part hasAutoIncrement: CREATE TABLE part (_id INTEGER PRIMARY KEY AUTOINCREMENT,mid INTEGER,seq INTEGER DEFAULT 0,ct TEXT,name TEXT,chset INTEGER,cd TEXT,fn TEXT,cid TEXT,cl TEXT,ctt_s INTEGER,ctt_t TEXT,_data TEXT,text TEXT) result: true
,D/TP/MmsSmsDatabaseHelper( 1443): [MmsSmsDb] tableName: pdu hasAutoIncrement: CREATE TABLE pdu (_id INTEGER PRIMARY KEY AUTOINCREMENT,thread_id INTEGER,date INTEGER,date_sent INTEGER DEFAULT 0,msg_box INTEGER,read INTEGER DEFAULT 0,m_id TEXT,sub TEXT,sub_cs INTEGER,ct_t TEXT,ct_l TEXT,exp INTEGER,m_cls TEXT,m_type INTEGER,v INTEGER,m_size INTEGER,pri INTEGER,rr INTEGER,rpt_a INTEGER,resp_st INTEGER,st INTEGER,tr_id TEXT,retr_st INTEGER,retr_txt TEXT,retr_txt_cs INTEGER,read_status INTEGER,ct_cls INTEGER,resp_txt TEXT,d_tm INTEGER,d_rpt INTEGER,locked INTEGER DEFAULT 0,sub_id INTEGER DEFAULT -1, seen INTEGER DEFAULT 0,creator TEXT,sim_slot INTEGER DEFAULT 0,sim_imsi TEXT,deletable INTEGER DEFAULT 0,hidden INTEGER DEFAULT 0,app_id INTEGER DEFAULT 0,msg_id INTEGER DEFAULT 0,callback_set INTEGER DEFAULT 0,reserved INTEGER DEFAULT 0,text_only INTEGER DEFAULT 0,spam_report INTEGER DEFAULT 0,secret_mode INTEGER DEFAULT 0,safe_message INTEGER DEFAULT 0) result: true
,D/TP/MmsSmsDatabaseHelper( 1443): [getWritableDatabase] hasAutoIncrementThreads: true hasAutoIncrementAddresses: true hasAutoIncrementPart: true hasAutoIncrementPdu: true
,D/TP/MmsSmsProvider( 1443): query,matched:7, calling pid = 2303
,D/TP/MmsSmsProvider( 1443): match 7:Elapsed time : 3.079 ms
,D/TP/MmsSmsProvider( 1443): deleteConversation threadId: 9223372036854775807
,I/Mms/ReservationManager( 2303): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MmsApp( 2303): [end]    onCreate() consume time = 18.155573
,D/Mms/SmsReceiver( 2303): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
,D/TP/MmsSmsProvider( 1443): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1443): updateThread(), thread_id = 9223372036854775807
,D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,V/TP/MmsSmsDatabaseHelper( 1443): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/TP/MmsSmsProvider( 1443): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
,I/splitIntent( 1014): Queue : background intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/DownloadManager( 2303): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 2303): roaming ------> false, mSimSlot = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/Mms/MethodReflector( 2303): getSubId is called
D/Mms/TelephonyUtils( 2303): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 2303): getTelephonyProperty is called
D/Mms/DownloadManager( 2303): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 2303): [NotificationTransaction] getAutoDownloadState simSlot : 0
,D/Mms/DownloadManager( 2303): auto download without roaming -> true
D/Mms/DownloadManager( 2303): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/Conversation( 2303): [end]    init consume time = 24.103333
D/Mms/DownloadManager( 2303): mAutoDownload ------> true
,D/BootupListener( 1443): intent.getAction() = android.intent.action.SERVICE_STATE
,D/SettingsProvider( 1014): name = internet_call_settings_visibility
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/PhoneUtilsCommon( 1443): isSupportVoLTE is false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt,
,D/StatusChecker( 2258): onReceive : android.intent.action.SERVICE_STATE
,I/StatusChecker( 2258): onReceive : net.mt.init : DONE
,D/Mms/MessagingNotification( 2303): [start]    init() consume time = 13.499532
,D/Mms/MessagingNotification( 2303): [end]    init consume time = 2.073698
,D/StatusChecker( 2258): Service state changed : 3 mSub-1
,D/Mms/SmsReceiverService( 2303): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SamsungIME( 1904): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/TelephonyPermission( 2303): isDefault true
,D/Mms/SmsReceiverService( 2303): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
,D/Mms/SmsReceiverService( 2303): handleSIMStatus()
D/Mms/SmsReceiverService( 2303): handleSIMStatus(): SIM_STATUS = ABSENT
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/JsMessageQueue( 2292): Set native->JS mode to OnlineEventsBridgeMode
,D/Mms/SpamFilter( 2303): [start]    SpamFilter fill() begin consume time = 20.276406
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/Synchronizer( 2303): [start]    doSync consume time = 12.314479
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1443): query,matched:0, calling pid = 2303
,V/TP/MmsSmsProvider( 1443): getSimpleConversations entered.
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1443): match 0:Elapsed time : 1.620 ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/AndroidProtocolHandler( 2292): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1443): update, matched:300, calling pid = 2303
,V/TP/MmsSmsProvider( 1443): syncDBData start
,V/TP/MmsSmsProvider( 1443): syncDBData sms end
,V/TP/MmsSmsProvider( 1443): syncDBData mms end
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/TP/MmsSmsProvider( 1443): syncDBData end
,D/Mms/Synchronizer( 2303): [end]    doSync consume time = 28.58875
,I/SamsungIME( 1904): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1443): query,matched:400, calling pid = 2303
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/SamsungIME( 1904): KeybaordView init() : load resources
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/MessagingNotification( 2303): checkBadgeCount unreadCount=0 badgeCount=0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Mms/SpamFilter( 2303): [end]    SpamFilter fill() finished consume time = 32.488437
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/SmsProvider( 1443): query,matched:26, calling pid = 2303
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/SmsProvider( 1443): match 26:Elapsed time : 4.438 ms
,I/SamsungIME( 1904): getCurrentKeyboard
I/SamsungIME( 1904): getTextKeyboard
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SamsungIME( 1904): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1443): query,matched:6, calling pid = 2303
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/TP/MmsSmsProvider( 1443): match 6:Elapsed time : 2.749 ms
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
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1744): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/jxcore_app_log( 2292): JniHelper::setJavaVM(0xb7132450), pthread_self() = -1217876712
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 1744): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1744): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1744): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1744): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1744): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1744): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2435): MountEmulatedStorage()
E/Zygote  ( 2435): v2
I/libpersona( 2435): KNOX_SDCARD checking this for 10025
,I/libpersona( 2435): KNOX_SDCARD not a persona
,I/SELinux ( 2435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=2435 uid=10025 gids={50025, 9997} abi=armeabi-v7a,
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,I/SELinux ( 2435): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/jxcore-log( 2292): Initializing JXcore engine
W/jxcore-log( 2292): JXcore engine is ready
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2435): TimaSignature is unavailable
,D/ActivityThread( 2435): Added TimaKeyStore provider
,D/accuweather( 1744): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 1744): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1744): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 09 42
,W/ResourcesManager( 2435): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/accuweather( 1744): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1744): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1744): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1744): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1744): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
,D/accuweather( 1744): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1744): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1744): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,E/audit   ( 1910): type=1400 msg=audit(1457426565.259:203): avc:  denied  { ioctl } for  pid=2434 comm="Thread-230" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1910):  SEPF_SM-A500FU_5.0.2-1_0038
,E/audit   ( 1910): type=1300 msg=audit(1457426565.259:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=5 a3=9d62f8f8 items=0 ppid=307 ppcomm=main pid=2434 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-230" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1910): type=1320 msg=audit(1457426565.259:203): 
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1744): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,W/jxcore-log( 2292): Starting JXcore engine
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1744): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1744): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 23
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/jxcore-log( 2292): Platform android
W/jxcore-log( 2292): 
,W/jxcore-log( 2292): Process ARCH arm
W/jxcore-log( 2292): 
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 33094(1761KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 2.028ms total 131.898ms
,I/jxcore-log( 2292): JXcore Cordova bridge is ready!
I/jxcore-log( 2292): 
,W/jxcore-log( 2292): JXcore engine is started
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,I/OMACP   ( 2435): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1298): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1298): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,E/jxcore  ( 2292): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2292): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/Mms/Omacp( 2303): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/PhoneWindow( 2292): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 2292): *FMB* installDecor flags : 8388610
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,D/InputDispatcher( 1014): Focus left window: 2292
D/InputDispatcher( 1014): Focus entered window: 2292
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/PhoneWindow( 2292): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2292): *FMB* isFloatingMenuEnabled return false
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=4, NainActivit
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 2435): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
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
,D/SRIB_DCS( 2292): log_dcs ThreadedRenderer::initialize entered! 
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
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.contacts, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2452): MountEmulatedStorage()
E/Zygote  ( 2452): v2
I/libpersona( 2452): KNOX_SDCARD checking this for 10020
I/libpersona( 2452): KNOX_SDCARD not a persona
I/SELinux ( 2452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.android.contacts for broadcast com.android.contacts/com.samsung.contacts.util.ContactsReceiver: pid=2452 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
I/SELinux ( 2452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2452): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2452): TimaSignature is unavailable
,D/ActivityThread( 2452): Added TimaKeyStore provider
,W/ResourcesManager( 2452): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 2452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2452): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/SamsungIME( 1904): [SwiftkeyWrapper] currentLangauge : 1701729619
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,D/EasySignUpManager_1.15.0305( 2452): serviceId : 0, features : -1
,I/splitIntent( 1014): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=6, mSplitNum[2]=8, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=10
,I/splitIntent( 1014): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,D/SecContentProvider2( 1014): uri = 18 selection = isCopyContactToSimAllowed
D/SecContentProvider2( 1014): mCursor = null
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1014): isCopyContactToSimAllowed = true
,E/Zygote  ( 2470): MountEmulatedStorage()
E/Zygote  ( 2470): v2
,I/libpersona( 2470): KNOX_SDCARD checking this for 10044
I/libpersona( 2470): KNOX_SDCARD not a persona
,I/SELinux ( 2470): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2470): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=2470 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 2470): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2470): TimaSignature is unavailable
,D/ActivityThread( 2470): Added TimaKeyStore provider
,E/Zygote  ( 2485): MountEmulatedStorage()
,E/Zygote  ( 2485): v2
I/libpersona( 2485): KNOX_SDCARD checking this for 10088
I/libpersona( 2485): KNOX_SDCARD not a persona
,I/SELinux ( 2485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=2485 uid=10088 gids={50088, 9997} abi=armeabi-v7a
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 2485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2485): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 2495): MountEmulatedStorage()
,E/Zygote  ( 2495): v2
I/libpersona( 2495): KNOX_SDCARD checking this for 10142
I/libpersona( 2495): KNOX_SDCARD not a persona
,I/SELinux ( 2495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=2495 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 2495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2495): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 2485): TimaSignature is unavailable
,D/ActivityThread( 2485): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 2495): TimaSignature is unavailable
,D/ActivityThread( 2495): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1466, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ResourcesManager( 2470): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2470): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2470): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2470): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 2470): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 2470): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.systemui, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 2485): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 2516): MountEmulatedStorage(),
E/Zygote  ( 2516): v2
I/libpersona( 2516): KNOX_SDCARD checking this for 10054
I/libpersona( 2516): KNOX_SDCARD not a persona,
I/SELinux ( 2516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.android.systemui.recentsactivity for broadcast com.android.systemui/.recents.RecreateReceiver: pid=2516 uid=10054 gids={50054, 9997, 1028, 1015, 1035, 3002, 3001, 3006} abi=armeabi-v7a
E/SELinux ( 2516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2528): MountEmulatedStorage()
I/libpersona( 2528): KNOX_SDCARD checking this for 10139
E/Zygote  ( 2528): v2
I/libpersona( 2528): KNOX_SDCARD not a persona
I/SELinux ( 2528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=2528 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,V/TaskCloserActivity( 2495): TaskCloserActivity enter()
,V/TaskCloserActivity( 2495): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/TimaKeyStoreProvider( 2516): TimaSignature is unavailable
,D/ActivityThread( 2516): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1014): mCursor = null
,D/TimaKeyStoreProvider( 2528): TimaSignature is unavailable
D/ActivityThread( 2528): Added TimaKeyStore provider
,W/ResourcesManager( 2516): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 2528): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2528): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2528): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 2528): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 2528): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Recents_RecreateReceiver( 2516): onReceive by home
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 24
,W/art     ( 2452): Verification of void com.android.contacts.common.list.l.P() took 101.507ms
,D/NearbySource( 2470): Nearby Source Create!
,D/NearbyContext( 2470): Nearby Context Create!
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2470): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 2470): Samsung link source created
,D/AbsListView( 2452): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady( 2470): Receive : home resume
,D/ContactProvider( 2470): getAllContactInfoList Start
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 2303): ui event
,I/splitIntent( 1014): Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SIP     ( 1443): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/File    ( 1443): fail readDirectory() errno=2
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
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
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
,E/SQLiteLog( 1224): (283) recovered 10 frames from WAL file /data/data/com.android.providers.media/databases/person.db-wal
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
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/ContactProvider( 2470): getAllContactInfoList End
,I/syncContacts( 2470): thread: 253, sync time = 120
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1866): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.sec.android.daemonapp
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1298): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1298): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:165 [0:0] app on 
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/Mms/MmsApp( 2303):  start initViewCache mms
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:381 [0:0] [sendPak] PakNme size = 5
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/ComposeMessageFragment( 2303): [start]    fillCache consume time = 1868.380521
,D/Mms/ComposeMessageFragment( 2303): fillCache, easy = false
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:385 [0:0] selLocation : null
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:409 [0:0] citylistsize: 0, checkcurrent: 0
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidsystemui
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:459 [0:0] todayInfo == null 
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = sviewcover
,E/daemonapp( 1298): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comandroidcalendar
,D/AdaptiveEventManager( 1174): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205
D/AdaptiveEventManager( 1174): currentCityId is null
,D/AdaptiveEventManager( 1174): NetWork disabled : Don't refresh weather info : 205
D/AdaptiveEventManager( 1174): WeatherInfo [icon, temp, scale] = [0, 0.0, 1]
D/AdaptiveEventManager( 1174): Weather Visibility: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1174): Widget Count: Previous= 0 >> Now= 0
D/AdaptiveEventManager( 1174): mWeatherInfo is not reliable
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
,E/daemonapp( 1298): [MSC_Daemon]>>> WU:512 [0:0] [NameNotFoundException] sandPakage !!!!!,
W/ActivityManager( 1014): userId = 0, bbcId = -10000,
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.android.calendar,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1298): [MSC_Daemon]>>> WU:415 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:498 [0:0] sendBroadcast -> resultcode = 205,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2560): MountEmulatedStorage()
E/Zygote  ( 2560): v2
I/libpersona( 2560): KNOX_SDCARD checking this for 10135
I/libpersona( 2560): KNOX_SDCARD not a persona
I/SELinux ( 2560): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2560): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.weather.WeatherActionReceiver: pid=2560 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:176 [0:0] getDmCL,
E/SELinux ( 2560): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1856 [0:0] CnclAtRftAl
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1926 [0:0] [setARfAam]now :1457426566974
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1928 [0:0] [setARfAam]LUT :1457448166966
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1930 [0:0] [setARfAam]interval       :3
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1932 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
D/daemonapp( 1298): [MSC_Daemon]>>> WU:1662 [0:0] util getnext by config 1457448120000
,D/daemonapp( 1298): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457448120000
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1937 [0:0] [dbset]NT :1457448120000
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2560): TimaSignature is unavailable
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 2560): Added TimaKeyStore provider
,E/Zygote  ( 2575): MountEmulatedStorage()
E/Zygote  ( 2575): v2
I/libpersona( 2575): KNOX_SDCARD checking this for 1000
I/libpersona( 2575): KNOX_SDCARD not a persona
,I/SELinux ( 2575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=2575 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 2575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AbsListView( 2303): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,W/ResourcesManager( 2560): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2560): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2560): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.097ms total 32.395ms
,D/Mms/ComposeMessageFragment( 2303): [end]    fillCache consume time = 191.515625
D/TimaKeyStoreProvider( 2575): TimaSignature is unavailable
,D/ActivityThread( 2575): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 18.560ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 17.204ms
,D/SecurityLogAgent( 2575):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 2575):  SeDenialReceiver : File path = /data/misc/audit/audit.old
D/SecurityLogAgent( 2575):  SeDenialReceiver : Start file Zipping Service 
W/ContextImpl( 2575): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.securitylogagent, calleePkgName: com.samsung.android.securitylogagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.services.FileZippingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sysscope, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/art     ( 2303): Suspending all threads took: 18.010ms
D/SecurityLogAgent( 2575): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 2575): FileZippingService : file path =  /data/misc/audit/audit.old
,E/Zygote  ( 2593): MountEmulatedStorage()
E/Zygote  ( 2593): v2
I/libpersona( 2593): KNOX_SDCARD checking this for 1000
I/libpersona( 2593): KNOX_SDCARD not a persona
,I/SELinux ( 2593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/SecurityLogAgent( 2575): FileZippingService : onPremise disabled. Zipping..  
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2593): TimaSignature is unavailable
,D/ActivityThread( 2593): Added TimaKeyStore provider
,D/SecurityLogAgent( 2575): DenialLogFileZipCreator : createZip
,D/SecurityLogAgent( 2575): DenialLogFileZipCreator : Not empty 
,D/SecurityLogAgent( 2575): DenialLogFileZipCreator File existence : true audit.old file size 1335
,D/SecurityLogAgent( 2575): DenialLogFileZipCreator : denied strings found . Starts zipping . 
D/SecurityLogAgent( 2575): ProcessFileZipCreator : File name = denialLog
,D/SecurityLogAgent( 2575): ProcessFileZipCreator : Created temp file 
,D/SecurityLogAgent( 2575): ProcessFileZipCreator br.readline() has read  12 lines. 
D/SecurityLogAgent( 2575): ProcessFileZipCreator denialxxx.txt file file existence : true size after copying : 0
,D/SecurityLogAgent( 2575): ProcessFileZipCreator : Source = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog752163150.txt
D/SecurityLogAgent( 2575): ProcessFileZipCreator : Destination = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog752163150.txt.zip
,I/Scheduler( 1866): Use legacy PeriodicScheduler
D/SecurityLogAgent( 2575): ProcessFileZipCreator : File compressed.
D/SecurityLogAgent( 2575): ProcessFileZipCreatordenialLog752163150.txt has been deleted after compression. 
,D/SecurityLogAgent( 2575): FileCipher : getKey Called 
,I/SecureStorage( 2575): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,W/InstanceID/Rpc( 1866): Found 10012
,W/ContextImpl( 2593): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.sysscope, calleePkgName: com.sec.android.app.sysscope
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.factory, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2613): MountEmulatedStorage(),
E/Zygote  ( 2613): v2
I/libpersona( 2613): KNOX_SDCARD checking this for 1000
I/libpersona( 2613): KNOX_SDCARD not a persona
,I/SELinux ( 2613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2613): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecureStorage( 2575): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  366): [INFO]: SPID(0x00000000)Credentials: uid 1000, gid 1000, pid 2575
I/SecureStorage(  366): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2575): [INFO]: SPID(0x00000000)SS Daemon is running
D/SecurityLogAgent( 2575): FileCipher : Secure Storage Supported 
I/SecureStorage( 2575): [INFO]: SPID(0x00000000)Processing data
,I/ActivityManager( 1014): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=2613 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SecureStorage(  366): [INFO]: SPID(0x00000000)Credentials: uid 1000, gid 1000, pid 2575
I/SecureStorage(  366): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
,D/TimaKeyStoreProvider( 2613): TimaSignature is unavailable
D/ActivityThread( 2613): Added TimaKeyStore provider
,W/ResourcesManager( 2613): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/Mms/BubbleViewCache( 2303): fillCache bubble = 1
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 25
,E/SMD     (  286): DCD OFF
,D/FactoryTestApp( 2613): [FactoryTestBroadcastReceiver$onReceive](2613) onReceive action=android.intent.action.BOOT_COMPLETED
,W/ActivityThread( 2613): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/FactoryTestApp( 2613): [XMLDataStorage$parseXML](2613) is Live Demo : false
,D/FactoryTestApp( 2613): [XMLDataStorage$parseXML](2613) modelXML=sm-a500fu.dat
,D/FactoryTestApp( 2613): [XMLDataStorage$parseXML](2613) deviceXML=a5ulte.dat
D/FactoryTestApp( 2613): [XMLDataStorage$parseXML](2613) nameXML=a5ultexx.dat
,D/FactoryTestApp( 2613): [XMLDataStorage$parseAsset](2613) parseAsset Is Started
,I/FactoryTestApp( 2613): [XMLDataStorage$parseAsset](2613) Convert dat file: sm-a500fu.dat
,D/FactoryTestApp( 2613): [XMLDataStorage$parseAsset](2613) Decode base file: factory.dat
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FACTORY_TEST_APP
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FAILHIST_VERSION
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=MODEL_NAME
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=MODEL_NUMBER
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=CHIPSET_MANUFACTURE
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=CHIPSET_NAME
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=DEVICE_TYPE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=BATT_TYPE
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PANEL_TYPE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SENSOR_NAME_MAGNETIC
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SENSOR_NAME_GYROSCOPE
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=REAR_CAMERA_TYPE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FRONT_CAMERA_TYPE
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=ISP_FLASH_TEST_SMD
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SPEAKER_COUNT
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=MIC_COUNT,
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SVC_LED_TEST_BRIGHTNESS
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_LTE
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_DUAL_STANBY_ONE_CP
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_QWERTY_KEY
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_RCV
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FACTORY_TEST_APO
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_BOOST_MEDIASCAN
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_EPEN
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_SENSORHUB
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_CAM_FRONT_NOT_ISP
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_SECOND_MIC_TEST
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_IRLED_FEEDBACK_IC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=NEED_CAMDRIVER_OPEN
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HW_VER_EFS
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_BOOK_COVER
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_AUTO_WAKELOCK
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_MULTI_SIM_FRAMEWORK
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_DSDS_MSIMM_CHECK
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FONT_SIZE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=RAM_SIZE_IF
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=MULTI_TSK_THD
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=NEED_LPA_MODE_SET
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_FM_RADIO
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=BOOT_CHECK_TOUCHKEY_WO_SVCLED
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=FEATURE_ENABLE_DYNAMIC_MULTI_SIM
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_GRAPHIC_ACCLETOR
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_DISABLE_SCROLLING_CACHE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_SELFTEST_DISPLAY_DELAY
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_POWER
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_APP_SWITCH,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_HOME,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_BACK,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_TOUCH_KEY_ODER
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_TEST_VIEW_TABLE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SEMI_KEY_TEST_VOLUME_UP
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SEMI_KEY_TEST_VOLUME_DOWN,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SEMI_KEY_TEST_HOME,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_KEY_TEST_THRESHOLD,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_TSP_STANDARD_CHANNEL,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_SENSOR_TEST_ACC_REVERSE,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_GEOMAGNETIC_ALPS_CAL,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=GEOMAGNETIC_IC_POINT,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SENSOR_TEST_ACC_BIT,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=G_VECTOR_SUM_ACC_BIT,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_VIBETONZ_UNSUPPORTED,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=AT_GPSSTEST,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=AT_BATTEST_RESET_WHEN_READ,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SUPPORT_CHARGE_COUNT,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PA0_TEMP_ADC,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PA1_TEMP_ADC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=NEED_ACK_FOR_CAMERA_STOP,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HALL_IC_TEST,
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START,
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=READ_TARGET_GEOMAGNETIC
,I/GAV4    ( 2194): Thread[GAThread,5,main]: No campaign data found.
D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SYS_INFO_MODEL_NAME
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_SELFTEST_MIN_MELFAS
,I/GAv4-SVC( 2044): Google Analytics 8.4.89 is starting up.
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_SELFTEST_MAX_MELFAS
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TOUCH_KEY_SPEC_MIN
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TOUCH_KEY_SPEC_MAX
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=BOOTLOADER_VERSION
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=BATTERY_TEST_MODE,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=BATTERY_VF_OCV,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=SEC_EXT_THERMISTER_TEMP
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PA1_THERMISTER_ADC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PA0_THERMISTER_CELCIUS
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_COMMAND_CMD
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=TSP_COMMAND_RESULT
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=KEY_PRESSED_POWER,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HUMITEMP_THERMISTER_PAM
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HUMITEMP_THERMISTER_BATT_CELCIUS,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=LPA_MODE_SET,
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=GEOMAGNETIC_SENSOR_ADC
,D/FactoryTestApp( 2613): [XMLDataStorage$redefinitionById](2613) id=GEOMAGNETIC_SENSOR_POWER
,D/FactoryTestApp( 2613): [XMLDataStorage$parseAsset](2613) SemiFunctionMenu
,D/FactoryTestApp( 2613): [XMLDataStorage$parseAsset](2613) parseAsset Is Completed
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=CHIPSET_MANUFACTURE, value=Qualcomm
,I/FactoryTestApp( 2613): [ModuleCommon$ModuleCommon](2613) Create ModuleCommon
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 2613): [Support$Kernel.read](2613) path=/efs/FactoryApp/factorymode, value=ON
,I/FactoryTestApp( 2613): [ModuleCommon$readFactoryMode](2613) mode: ON
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2613): [FactoryTestBroadcastReceiver$onReceive](2613) KEYSTRING_BLOCK is already existed...
D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
,D/FactoryTestApp( 2613): [Support$Values.getBoolean](2613) id=INBATT_SAVE_SOC, value=false
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 2613): [Support$Properties.get](2613) property=ro.factory.factory_binary
D/FactoryTestApp( 2613): [FactoryTestBroadcastReceiver$onReceive](2613) Boot completed, IS_FACTORY_BINARY = USER MODE
,I/FactoryTestApp( 2613): [ModuleCommon$getFtClientEnableState](2613) result : false
I/FactoryTestApp( 2613): [ModuleCommon$connectedJIG](2613) ...
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 2613): [ModuleCommon$connectedJIG](2613) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 2613): [Support$Kernel.read](2613) path=/sys/class/sec/switch/adc, value=1f,
I/FactoryTestApp( 2613): [ModuleCommon$connectedJIG](2613) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2613): [ModuleCommon$isConnectionModeNone](2613) mConnectionMode = gsm
,I/FactoryTestApp( 2613): [ModuleCommon$isRunningFtClient](2613) RUNNING_FTCLIENT : false
I/FactoryTestApp( 2613): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](2613) start DummyFtClient service for APO
,W/ContextImpl( 2613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:300 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:147 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.factory, calleePkgName: com.sec.factory
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.factory/com.sec.factory.aporiented.DummyFtClient; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.factory
,D/FactoryTest( 2613): User mode
,I/FactoryTestApp( 2613): [ModuleCommon$disableFtClient](2613) ...
,D/FactoryTestApp( 2613): [DummyFtClient$onCreate](2613) Create DummyFtClient service
,I/FactoryTestApp( 2613): [XMLDataStorage$parsingXML](2613) FtClient => data parsing was completed.
,D/FactoryTestApp( 2613): [DummyFtClient$onReceive](2613) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2613): [ModuleCommon$isConnectionModeNone](2613) mConnectionMode = gsm,
,D/FactoryTestApp( 2613): [Support$Values.getBoolean](2613) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 2613): [DummyFtClient$onStartCommand](2613) ...
,I/WifiService( 1014): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager( 1014): boot completed
,D/UsbDeviceManager( 1014): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager( 1014): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/UsbDeviceManager( 1014): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager( 1014): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.keychain, action: android.security.IKeyChainService
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2640): MountEmulatedStorage(),
,E/Zygote  ( 2640): v2
I/libpersona( 2640): KNOX_SDCARD checking this for 1000
I/libpersona( 2640): KNOX_SDCARD not a persona
,I/SELinux ( 2640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2640 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/KeyguardEffectViewUtil( 1174): set resource id,
D/SettingsProvider( 1014): name = keyguard_default_wallpaper_res_id
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
,D/SettingsProvider( 1014): selectionArgs: 10054,
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BOOT_COMPLETED,
D/KeyguardUpdateMonitor( 1174): handleBootCompleted()
D/KeyguardUpdateMonitor( 1174): handleBootCompleted(),
I/SELinux ( 2640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PalmMotion( 1014): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,E/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/PalmMotion( 1014): [PALM] SURFACE_PALM_SWIPE: 1
D/LightsService( 1014): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1014) 
D/PalmMotion( 1014): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true],
D/LightsService( 1014): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/PalmMotion( 1014): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1014): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1014): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/NfcService( 1429): call the applyRouting,
,D/SamsungIME( 1904): showDlgMsgBox : false true true
I/RecoverySystem( 1014): !@RecoverySystem handleAftermath
I/RecoverySystem( 1014): No recovery log file
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.android.dialer.calllog.CallLogNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TimaKeyStoreProvider( 2640): TimaSignature is unavailable
D/ActivityThread( 2640): Added TimaKeyStore provider
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory),
E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem( 1014): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/OtaStartupReceiver( 1443): onOtaspChanged: mOtaspMode=1
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.phone, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Reset_Reason( 1014): resetString = NPON,
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 2662): MountEmulatedStorage(),
E/Zygote  ( 2662): v2
I/libpersona( 2662): KNOX_SDCARD checking this for 1001
I/libpersona( 2662): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=2662 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
,I/SELinux ( 2662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecureStorage(  366): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,I/BootReceiver( 1014): Copying audit failures to DropBox
I/BootReceiver( 1014): Checking for fsck errors
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/File    ( 2640): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 2662): TimaSignature is unavailable
,D/ActivityThread( 2662): Added TimaKeyStore provider
,W/ResourcesManager( 2662): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SecureStorage( 2575): [INFO]: SPID(0x00000001)Processing data has been completed
I/SecureStorage( 2575): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 2575): FileCipher : Got the key bytes 
D/SecurityLogAgent( 2575): FileCipher : Saving Key to SecureStorage.  
I/SecureStorage( 2575): [INFO]: SPID(0x00000001)Processing data
I/SecureStorage(  366): [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 2575
I/SecureStorage(  366): [INFO]: SPID(0x00000001)Received function mask & code: 0x00000104
,D/ActivityManager( 1014): startService callerProcessName:com.sec.phone, calleePkgName: com.sec.phone
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.RilTracker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.phone
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.phone, destAppInfo.processName = com.sec.factory
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FactoryTestApp( 2613): [ProtectedFactoryTestBroadcastReceiver$onReceive](2613) onReceive action=com.samsung.intent.action.SECPHONE_READY
,I/FactoryTestApp( 2613): [ProtectedFactoryTestBroadcastReceiver$onReceive](2613) com.samsung.intent.action.SECPHONE_READY
D/FactoryTest( 2613): User mode
,D/Mms/NotificationReceiver( 2303): MMS NotificationReceiver onReceive: android.intent.action.BOOT_COMPLETED
D/Mms/NotificationReceiver( 2303): handleBootCompleted()
,D/Mms/RcsOwnCapsManager( 2303): queue Uri = content://im/queue-messages?box=pending
,D/TP/ImProvider( 1443): im query match24
,D/TP/ImProvider( 1443): URI_IM_QUEUED_MESSAGES
,D/TP/ImProvider( 1443): ftSesstionId must be a long.
,D/TP/ImProvider( 1443): getQueuedImMessages
,D/TP/ImProvider( 1443): uriString = SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=1 AND (status=1 or status=2) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=4 AND (status!=4 AND status!=12) UNION SELECT ft._id as _id, ft.session_id as session_id, ft.chat_session_id as chat_session_id, thread_id, 'ft' as transport_type, address as recipients, ft.type as type, ft.status as status, ft.service_type as service_type, ft.ext_info as ext_info FROM ft LEFT JOIN im_threads ON ft.thread_id=im_threads.normal_thread_id WHERE ft.hidden=0 AND type=6 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=4 UNION SELECT im._id as _id, im.session_id as session_id, null as chat_session_id, thread_id, 'chat' as transport_type, address as recipients, im.type as type, im.status as status, im.service_type as service_type, im.ext_info as ext_info FROM im LEFT JOIN im_threads ON im.thread_id=im_threads.normal_thread_id WHERE im.hidden=0 AND type=6
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/NotificationReceiver( 2303):  getPendingMessageIds: no pending messages.
,D/Mms/ActionsFactory( 2303): Call to GET_LAST_MESSAGES_SENT
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=com.samsung.rcs.framework.instantmessaging.action.GET_LAST_MESSAGES_SENT cat=[com.samsung.rcs.framework.instantmessaging.category.ACTION] pkg=com.sec.ims.android (has extras) } U=0: not found
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
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
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
D/SettingsProvider( 1014): name = db_smartlock_supported
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/AccessibilityManagerService( 1014): setmDNIeNegative (false)
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
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
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
I/BootReceiver( 1014): Copying /data/tombstones/tombstone_05 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
W/Settings( 1282): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CrashAnrDetector( 1014): Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
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
D/CrashAnrDetector( 1014):          9c90bfc4  00000000  
D/CrashAnrDetector( 1014):          9c90bfc8  00000000  
D/CrashAnrDetector( 1014):          9c90bfcc  00000000  
D/CrashAnrDetector( 1014):          9c90bfd0  7106dc38  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector( 1014):          9c90bfd4  00000000  
D/CrashAnrDetect,or( 1014):          9c90bfd8  00000000  
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
D/CrashAnrDetector( 1014): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/SettingsProvider( 1014): name = block_emergency_message
,D/SettingsProvider( 1014): name = safetycare_geolookout_registering
,I/BootReceiver( 1014): Copying /data/tombstones/tombstone_06 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl( 1014): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 26
,D/PackageManager( 1014): [MSG] MCS_UNBIND
,I/ActivityManager( 1014): Killing 1188:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,W/CursorWrapperInner( 2303): Cursor finalized without prior close()
,D/[LPC]   ( 1014): CFMS ACTION_BOOT_COMPLETED - startRawDataGathering for analyzing usage stats
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 c.aB.dE:-1 c.t.a:-1 c.t.b:-1 com.android.server.ssrm.ad.c:-1 
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2682): MountEmulatedStorage(),
E/Zygote  ( 2682): v2
I/libpersona( 2682): KNOX_SDCARD checking this for 1000
I/libpersona( 2682): KNOX_SDCARD not a persona,
I/SELinux ( 2682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_1188/cgroup.procs: No such file or directory
,I/SELinux ( 2682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2682): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.lowpowercontext.LowpowerContextProvider: pid=2682 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 2682): TimaSignature is unavailable
D/ActivityThread( 2682): Added TimaKeyStore provider
,W/ResourcesManager( 2682): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/SecureStorage(  366): [WARN]: SPID(0x00000002)Trying update data block to DB
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 ,
,I/SecureStorage(  366): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
,I/i       ( 1014): No model
,D/FactoryTest( 1014): Not factory mode
D/FactoryTest( 1014): Not factory mode. isFactoryMode() returend false
D/w       ( 1014): isUserBuild = true
,I/SecureStorage( 2575): [INFO]: SPID(0x00000002)Processing data has been completed
,I/SecureStorage( 2575): [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
D/SecurityLogAgent( 2575): FileCipher : Key loaded. 
,D/SecurityLogAgent( 2575): ProcessFileZipCreator : source file  :  file existence : true size after compression : 160
D/SecurityLogAgent( 2575): FileCipher : File ciphering 
D/SecurityLogAgent( 2575): FileCipher : Source file name = denialLog752163150.txt.zip source file size 160
,E/SmartFaceService( 1014): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator( 1014): no icon
E/SmartFaceService( 1014): mActiveServiceType: 0
E/SmartFaceService( 1014): mLightIntensityEnough: true mLux: 0.0
,D/Stay/Rotation Worker( 1014): updateClientsDone. def. do nothing.
E/SmartFaceService( 1014): Service Type to Worker: 0
E/SmartFaceService( 1014): Last Active clients:0 Current Active clients: 0
,E/SmartFaceService( 1014): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/SSRM:aZ ( 1014): Alarm set to refresh battery stats
,D/SSRM:aZ ( 1014): Updating Threshold Value.. isSystemReady: true
,D/SecurityLogAgent( 2575): FileCipher : Destination file name = denialLog-2008610575.zip dest file Size 176
D/SecurityLogAgent( 2575): FileCipher : File ciphered successful 
D/SecurityLogAgent( 2575): ProcessFileZipCreator : source after encryption :  file existence : true file size:176
D/SecurityLogAgent( 2575): ProcessFileZipCreator : File ciphered 
D/SecurityLogAgent( 2575): ProcessFileZipCreatordenialLog752163150.txt.zip has been deleted after encryption. 
,D/SecurityLogAgent( 2575): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 2575): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 2575): StateMachine : Current State = 1
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1014): [SO] activate (ident=0xb7896570, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SecurityLogAgent( 2575): FileZippingService : completed task. Returning wakelock . 
,I/ActivityManager( 1014): Killing 1389:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1014): [SO] changed settle time [0]
D/SensorService( 1014): [SO] setDelay [200000000]
D/SensorService( 1014): [SO] activate (ident=0xb79a9c90, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
V/AlarmManagerEXT( 1014): mGmsLocationBundling: false
,D/SSRM:n  ( 1014): SIOP:: AP = 360
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
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
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
,I/ActivityManager( 1014): Killing 1552:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/RCPManagerService( 1014): ACTION_BOOT_COMPLETED
E/RCPManagerService( 1014):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/RCPManagerService( 1014): BootReceiver.onReceive(): Starting RCP Proxy for user = null
E/RCPManagerService( 1014):  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1014): [SO] activate (ident=0xb79a9c90, enabled=0)
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1014): unregisterListener ::   
,I/Sensors ( 1014): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1014): [SO] changed settle time [1]
D/SensorService( 1014): [SO] setDelay [66000000]
D/SensorService( 1014): [SO] activate (ident=0xb79a9c90, enabled=1)
D/SensorService( 1014): [SO] AR_init
I/Sensors ( 1014): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1014): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/MotionRecognitionService( 1014):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,W/libprocessgroup( 1014): failed to open /acct/uid_10096/pid_1389/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_1552/cgroup.procs: No such file or directory
,D/EnterpriseDeviceManagerService( 1014): android.intent.action.BOOT_COMPLETED
,D/EnterpriseDeviceManagerService( 1014): runAdminUpdate
,D/EnterpriseUtils( 1014): File Not Found : /data/system/selfUpdateAdmin.conf
,V/ApplicationPolicy( 1014): boot completed - refreshWidgetStatus
V/ApplicationPolicy( 1014): refresh widget status for user 0
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.music
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
,D/EnterpriseDeviceManagerService( 1014): nothing to selfUpdate
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.chrome
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,D/SensorService( 1014): [SO] Reset Rotation Old [100], Init [1],
,W/PhoneRestrictionPolicy( 1014): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/KnoxMUMContainerPolicy( 1014): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy( 1014): MSG_REMOVE_ORPHANED_CONTAINERS received
,W/PhoneRestrictionPolicy( 1014):  >>>> deliveryBlockedMsgs
,W/PhoneRestrictionPolicy( 1014): cvList size 0
,W/PhoneRestrictionPolicy( 1014):  >>>> deliveryBlockedMsgs
,D/WifiP2pService( 1014): P2pDisabledState{ what=143415 }
,D/WifiP2pService( 1014): DefaultState{ what=143415 }
,E/WifiStateMachine( 1014): Blacklist file delete
,D/Tethering( 1014): Boot complete.
D/ConnectivityService( 1014): Got NetworkFactory Messenger for WIFI
D/WIFI_P2P( 1014): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/ConnectivityService( 1014): Got NetworkFactory Messenger for WIFI_P2P
D/WIFI_P2P( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,W/PhoneRestrictionPolicy( 1014): cvList size 0
,V/EnterpriseBillingEngine( 1014): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1014): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1014): getCurrentActiveProfiles - start - 
,V/EnterpriseBillingPolicyStorage( 1014): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1014): handleAllprofiles - end
,D/UsbHostNotification( 1014): boot completed
,D/UsbHostRestrictor( 1014): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1014): initSetUsbBlock STARTED
,D/UsbHostRestrictor( 1014): SIM was never inserted
,D/UsbHostRestrictor( 1014): writableHostSysNode[false]
D/UsbHostRestrictor( 1014): Can NOT Write Disable Sys Node to [ON]
,D/SensorService( 1014): [SO] 0.134 0.383 10.113
,D/SensorService( 1014): [SO] [100 -> 255]
,D/PersonaManagerService( 1014): ACTION_BOOT_COMPLETED
,E/PersonaManagerServiceHandler( 1014):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,D/WIFI    ( 1014): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,D/WIFI    ( 1014): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/KnoxKeyguardUpdateMonitor( 1014): onBootComplete
,D/UsbStorageNotification( 1014): boot completed
,D/GpsLocationProvider( 1014): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
,D/GpsLocationProvider_ex( 1014): BOOT_COMPLETED native_init 
,D/GpsLocationProvider( 1014): set_capabilities_callback: 55u
,I/KnoxKeyguardUpdateMonitor( 1014): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1014): onTrustChanged user:0, enable:false
,D/KeyguardViewMediator( 1174): onTrustChanged( Showing = false , userId = 0 )
I/libmdmdetect( 1014): ESOC framework not supported
,D/qmi_secgps_clnt( 1014): qmi_secgps_client_init()
I/libmdmdetect( 1014): Found internal modem: modem
,E/PerMgrLib( 1014): Peripheral manager is not supported on this device
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,E/Geofence_Adapter( 1014): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1014): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1014): BOOT_COMPLETED native_cleanup 
,D/StorageNotification( 1174): boot completed
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,D/qmi_secgps_clnt( 1014): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,D/StatusBarManagerService( 1014): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/PhoneStatusBar( 1174): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,D/ActivityManager( 1014): startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2716 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 2716): MountEmulatedStorage()
I/libpersona( 2716): KNOX_SDCARD checking this for 10099
,E/Zygote  ( 2716): v2
I/libpersona( 2716): KNOX_SDCARD not a persona
,I/SELinux ( 2716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2716): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2716): TimaSignature is unavailable
,D/ActivityThread( 2716): Added TimaKeyStore provider
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
,I/qmi_secgps_clnt( 1014): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt( 1014): SECGPS: send a qmi message to secgps_server OK
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02( 1014): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02( 1014): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02( 1014): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,E/ActivityThread( 2716): Failed to find provider info for flipboard.auth.internal.debug
,E/ActivityThread( 2716): Failed to find provider info for flipboard.auth.internal
,I/splitIntent( 1014): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,I/splitIntent( 1014): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!,
,I/ActivityManager( 1014): Killing 1530:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/DrmEventReceiver( 1014): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1014): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,I/DrmEventReceiver( 1014): DrmEventReceiver : beginStartingService
I/System.out( 1014): start Service
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,D/ActivityManager( 1014): startService callerProcessName:android, calleePkgName: android
D/ActivityManager( 1014): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
,V/DownloadManager( 1224): onReceive intent + android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/WVMDrmPlugIn(  280): WVMDrmPlugin::onInitialize : 2976
,D/WVMDrmPlugIn(  280): WVMDrmPlugin::onSetOnInfoListener : add 2976
,E/Zygote  ( 2735): MountEmulatedStorage()
E/Zygote  ( 2735): v2
I/libpersona( 2735): KNOX_SDCARD checking this for 1000
I/libpersona( 2735): KNOX_SDCARD not a persona
,I/SELinux ( 2735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2735 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/SELinux ( 2735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2749): MountEmulatedStorage()
,E/Zygote  ( 2749): v2
I/libpersona( 2749): KNOX_SDCARD checking this for 10152
I/libpersona( 2749): KNOX_SDCARD not a persona
I/SELinux ( 2749): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2749): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2749 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/DrmEventService( 1014): action event :android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/SELinux ( 2749): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/SensorService( 1014): [SO] 0.134 0.383 10.094
I/TimaServiceEventReceiver( 1014): TimaServiceEventReceiver : onReceive
,D/TimaKeyStoreProvider( 2735): TimaSignature is unavailable
,D/ActivityThread( 2735): Added TimaKeyStore provider
,D/SecContentProvider2( 1014): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1014): mCursor = null
,I/ANDROID_DRM_FRWORKS_DrmManager(  280): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,D/MediaScannerReceiver( 1224): action: android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 2735): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/CscReceiver( 1443): onReceive android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/TimaKeyStoreProvider( 2749): TimaSignature is unavailable
,D/ActivityThread( 2749): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_1530/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/BluetoothBDAdrressReceiver( 2735): onReceive(), action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,D/CscUpdateService( 1443): onStart
E/CscUpdateService( 1443): costomer file is exists : it has been preconfiged.
W/ContextImpl( 2735): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,I/CscUpdateService( 1443): set_CSC_version
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/CscParser( 1443): update(): xml file exist
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2768): MountEmulatedStorage(),
I/libpersona( 2768): KNOX_SDCARD checking this for 10003
E/Zygote  ( 2768): v2
I/libpersona( 2768): KNOX_SDCARD not a persona
,I/SELinux ( 2768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2768 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/SELinux ( 2768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,E/SELinux ( 2768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
I/CscUtil ( 1443): isWifiOnly = false
,I/System.out( 1443): HandDataNode = null
,I/CscUpdateService( 1443): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1443): This is normal boot : CSC not updated
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/CscParser( 1443): update(): xml file exist
,E/SQLiteLog( 2749): (284) automatic index on shooting_modes(title_id)
,I/CscUpdateService( 1443): same CSC Version
,D/CscUtil ( 1443): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,E/Zygote  ( 2785): MountEmulatedStorage()
,I/libpersona( 2785): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2785): v2
I/libpersona( 2785): KNOX_SDCARD not a persona
I/SELinux ( 2785): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2785 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 1782:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,I/SELinux ( 2785): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 2785): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 2768): TimaSignature is unavailable
D/CscGPS  ( 1443): CSCGPS.updateParameters
D/CscGPS  ( 1443): supl host : null
,D/ActivityThread( 2768): Added TimaKeyStore provider
D/CscGPS  ( 1443): SUPL Host is null or invalid
W/ResourcesManager( 1443): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/CscGPS  ( 1443): supl_ver : null
D/CscGPS  ( 1443): SUPL Ver is null or invalid,
D/CscGPS  ( 1443): supl port : null
D/CscGPS  ( 1443): SUPL PORT is null or invalid
D/CscGPS  ( 1443): LPP : null,
,D/CscGPS  ( 1443): LPP is null or invalid
D/CscGPS  ( 1443): CSC don't have any AGPS value.
E/USB_UICC(  298): Timeout! No signal received. Retry num = 27
D/BluetoothBDTestService( 1443): onCreate()
E/BluetoothBDTestService( 1443): onStart(), extra_type: BOOT_COMPLETED
,E/BluetoothBDTestService( 1443): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1443): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 2785): TimaSignature is unavailable
,D/ActivityThread( 2785): Added TimaKeyStore provider
,E/Zygote  ( 2803): MountEmulatedStorage()
,E/Zygote  ( 2803): v2
,I/libpersona( 2803): KNOX_SDCARD checking this for 1101
I/libpersona( 2803): KNOX_SDCARD not a persona
I/SELinux ( 2803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2803 uid=1101 gids={41101, 9997} abi=armeabi-v7a
I/ServiceManager(  315): Waiting for service AtCmdFwd...
D/MediaScannerService( 1224): !@start scanning volume internal: [/system/media, /oem/media]
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/art     (  307): Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 683us total 22.604ms
,D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
,D/TimaKeyStoreProvider( 2803): TimaSignature is unavailable
D/ActivityThread( 2803): Added TimaKeyStore provider
,W/ResourcesManager( 2785): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 17.475ms
,D/TP/MmsProvider( 1443): Update uri=content://mms, match=0
,D/TP/MmsProvider( 1443): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
,I/Mms:transaction( 2303): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2303): [start]    nonBlockingUpdateMessageIndicator() consume time = 2371.350676
,I/Mms/ReservationManager( 2303): resetAfterConnected()
,D/Mms/MessagingNotification( 2303): sDisableVibrateForCamera = false
,D/Mms/TelephonyPermission( 2303): isDefault true
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.130ms,
,D/TP/MmsProvider( 1443): Query uri=content://mms, match=0, calling pid = 2303
,D/TP/MmsSmsProvider( 1443): query,matched:7, calling pid = 2303
,D/TP/MmsSmsProvider( 1443): match 7:Elapsed time : 1.429 ms
,W/ResourcesManager( 2803): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,W/libprocessgroup( 1014): failed to open /acct/uid_10138/pid_1782/cgroup.procs: No such file or directory
,I/Mms/ReservationManager( 2303): getReservedSendMessageCount(): retMessageCount=0
,D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,I/KnoxUsageLogPro( 2785): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/TP/MmsSmsProvider( 1443): query,matched:200, calling pid = 2303
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1443): match 200:Elapsed time : 1.401 ms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
V/SmartcardService( 2803): main Received broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
V/SmartcardService( 2803): Starting smartcard service after boot completed
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 2785): premStatus:2
I/KnoxUsageLogPro( 2785): savePreference: key = previous_sys_time value = 1457426569457
,I/KnoxUsageLogPro( 2785): isEulaShown : false
I/KnoxUsageLogPro( 2785): KnoxUsageReceiver onReceive : not Processible, just return
,D/SSRM:a  ( 1014): DeviceInfo:: 000000000000
D/SSRM:a  ( 1014): SettingsAirViewInfo:: 000000000
E/Zygote  ( 2824): MountEmulatedStorage(),
E/Zygote  ( 2824): v2
I/libpersona( 2824): KNOX_SDCARD checking this for 10048
,I/libpersona( 2824): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2824 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/SELinux ( 2824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SecureStorage( 2768): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,I/SELinux ( 2824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 2824): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1224): (283) recovered 140 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,E/Zygote  ( 2840): MountEmulatedStorage(),
,D/TimaKeyStoreProvider( 2824): TimaSignature is unavailable,
I/libpersona( 2840): KNOX_SDCARD checking this for 10085
E/Zygote  ( 2840): v2
I/libpersona( 2840): KNOX_SDCARD not a persona
,D/ActivityThread( 2824): Added TimaKeyStore provider,
I/SELinux ( 2840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2840 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 1583:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,I/SELinux ( 2840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
E/SELinux ( 2840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,I/KnoxUsageLogPro( 2785): savePreference: key = previous_elapsed_time value = 33759
,D/ActivityManager( 1014): startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
D/ActivityManager( 1014): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,I/SecureStorage( 2768): [INFO]: SPID(0x00000000)This device supports Secure Storage
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,I/SecureStorage(  366): [INFO]: SPID(0x00000002)Credentials: uid 10003, gid 10003, pid 2768
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SecureStorage(  366): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SecureStorage( 2768): [INFO]: SPID(0x00000000)SS Daemon is running
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SecureStorage( 2768): [INFO]: SPID(0x00000000)Processing data
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SecureStorage(  366): [INFO]: SPID(0x00000002)Credentials: uid 10003, gid 10003, pid 2768
I/SecureStorage(  366): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,W/ResourcesManager( 2824): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 2824): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2824): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 2840): TimaSignature is unavailable
,D/ActivityThread( 2840): Added TimaKeyStore provider
,E/Zygote  ( 2856): MountEmulatedStorage()
,E/Zygote  ( 2856): v2,
,I/libpersona( 2856): KNOX_SDCARD checking this for 1000
,I/libpersona( 2856): KNOX_SDCARD not a persona
I/SELinux ( 2856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 2856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2856 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 2856): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScanner( 1224): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/ActivityManager( 1014): Killing 2091:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/TP/SmsProvider( 1443): query,matched:0, calling pid = 2303
,D/TP/SmsProvider( 1443): match 0:Elapsed time : 1.658 ms
,D/Mms/SmsReceiverService( 2303): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,D/Mms/TelephonyPermission( 2303): isDefault true
D/Mms/SmsReceiverService( 2303): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Mms/SmsReceiverService( 2303): [start]    handleBootCompleted() consume time = 156.819583
,D/TimaKeyStoreProvider( 2856): TimaSignature is unavailable
,W/ResourcesManager( 2840): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2840): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 2840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2840): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 2840): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/Zygote  ( 2873): MountEmulatedStorage()
E/Zygote  ( 2873): v2
I/libpersona( 2873): KNOX_SDCARD checking this for 10157
I/libpersona( 2873): KNOX_SDCARD not a persona
I/SELinux ( 2873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2873 uid=10157 gids={50157, 9997} abi=armeabi-v7a
E/SELinux ( 2873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityThread( 2856): Added TimaKeyStore provider
,D/SettingsProvider( 1014): name = block_emergency_message
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10048
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,W/ActivityManager( 1014): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,D/TP/MmsSmsProvider( 1443): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1443): deleteConversation threadId: 9223372036854775806
,D/TP/SmsProvider( 1443): query,matched:51, calling pid = 2303
,W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_1583/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10031/pid_2091/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 2873): TimaSignature is unavailable
,D/ActivityThread( 2873): Added TimaKeyStore provider
,D/TP/SmsProvider( 1443): match 51:Elapsed time : 16.553 ms
,W/ResourcesManager( 2873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/MediaScanner( 1224): processDirectory :  /system/media
,D/TP/MmsSmsProvider( 1443): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1443): updateThread(), thread_id = 9223372036854775806
,D/Mms/MessagingNotification( 2303): isBlockingModeEnabled() = false, Zen mode = 0
,V/TP/MmsSmsDatabaseHelper( 1443): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1443): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
,E/Zygote  ( 2888): MountEmulatedStorage(),
I/libpersona( 2888): KNOX_SDCARD checking this for 10159
E/Zygote  ( 2888): v2
I/libpersona( 2888): KNOX_SDCARD not a persona
,I/SELinux ( 2888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=2888 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 1489:com.android.printspooler/u0a136 (adj 15): empty #31
,I/SELinux ( 2888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 2888): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/Mms/Conversation( 2303): deleteTempConversation(),deleted=0
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 2899): MountEmulatedStorage()
E/Zygote  ( 2899): v2
I/libpersona( 2899): KNOX_SDCARD checking this for 10072
I/libpersona( 2899): KNOX_SDCARD not a persona
,I/SELinux ( 2899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2899): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=2899 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 2888): TimaSignature is unavailable
D/ActivityThread( 2888): Added TimaKeyStore provider
,D/SmsProvider( 1443): Update uri=content://sms/outbox, match=8
,D/TimaKeyStoreProvider( 2899): TimaSignature is unavailable
,D/ActivityThread( 2899): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
,I/WifiCredService( 1282): onCreate
,D/Mms/SmsReceiverService( 2303): moveOutboxMessagesToFailedBox messageCount: 0
,I/Intent to TravelDirActivity( 2888): inside TravelBroadcastReceiver
,D/Mms/SmsReceiverService( 2303): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2303): [SIM-1]sendFirstQueuedMessage()
,D/TP/SmsProvider( 1443): query,matched:26, calling pid = 2303
,V/MediaScanner( 1224):  prescan time: 201ms (DB items: 141)
V/MediaScanner( 1224):     scan time: 137ms (Caching mode: true), (makeEntry time: 85ms ~62%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1224): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1224):    total time: 338ms
V/MediaScanner( 1224): checked files: 133  directories : 6  (I: 0, U: 0)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,D/MediaScanner( 1224): checkDefaultSounds
D/MediaScanner( 1224): system alarm_alert  : Vwiurug_etwofi5wgg
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1443): match 26:Elapsed time : 6.683 ms
,D/BadgeProvider( 2899): onCreate
,D/BadgeProvider( 2899): DatabaseHelper
,E/SQLiteLog( 2856): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal,
,E/Zygote  ( 2921): MountEmulatedStorage()
,E/Zygote  ( 2921): v2
I/libpersona( 2921): KNOX_SDCARD checking this for 1000
I/libpersona( 2921): KNOX_SDCARD not a persona
I/SELinux ( 2921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2921 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 2921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Killing 2129:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,E/SELinux ( 2921): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MediaScanner( 1224): OK. alarm_alert is already exist in setting DB.
,D/WifiTimerReceiver( 1282): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1282): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1282): Action boot completed received
,D/MediaScanner( 1224): system notification_sound  : K_Oprkltf5wgg
,D/MediaScanner( 1224): OK. notification_sound is already exist in setting DB.
,D/MediaScanner( 1224): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/DSM     ( 2856): [Lines:107] Normal booted
,D/DSM     ( 2856): [Lines:114] Boot completed
D/MediaScanner( 1224): OK. ringtone is already exist in setting DB.
,D/Mms/SmsReceiver( 2303): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2303): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2303): isDefault true
,D/FactoryTestApp( 2613): [DummyFtClient$mBroadcastReceiver](2613) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
D/FactoryTestApp( 2613): [DummyFtClient$mBroadcastReceiver](2613) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2613): [DummyFtClient$mBroadcastReceiver](2613) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/TimaKeyStoreProvider( 2921): TimaSignature is unavailable
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/MediaScannerService( 1224): !@done scanning volume internal
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 2921): Added TimaKeyStore provider
,D/NearbySettings( 1282): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1282): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1282): MountReceiver.onReceive - Create mPrefHandler
,D/TP/MmsProvider( 1443): Query uri=content://mms, match=0, calling pid = 2303
,D/NearbySettings( 1282): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1014): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,E/Zygote  ( 2938): MountEmulatedStorage()
E/Zygote  ( 2938): v2
I/libpersona( 2938): KNOX_SDCARD checking this for 1000
I/libpersona( 2938): KNOX_SDCARD not a persona
I/SELinux ( 2938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 2938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 2938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 2194:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,D/MediaScannerService( 1224): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,V/NearbySettings( 1282): MountReceiver.mPrefHandler - 7002
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/NearbySettings( 1282): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1282): MountReceiver.onReceive - Internal Path
,D/TimaKeyStoreProvider( 2938): TimaSignature is unavailable
,D/ActivityThread( 2938): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10136/pid_1489/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10050/pid_2129/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10113/pid_2194/cgroup.procs: No such file or directory
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 38531(2MB) AllocSpace objects, 34(2MB) LOS objects, 33% free, 25MB/38MB, paused 2.183ms total 151.854ms
,D/BadgeProvider( 2899): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/SettingsProvider( 1014): name = next_alarm_formatted
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10085
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/SettingsProvider( 1014): name = personal_mode_enabled
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/Launcher.Model( 1466): reloadBadges entered.
,D/BadgeProvider( 2899): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2899): sendNotify, [notify] : null
D/BadgeProvider( 2899): update, [uri] : content://com.sec.badge/apps/2
,D/BadgeProvider( 2899): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2899): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 2303): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2303): remove alarm
W/ResourcesManager( 2938): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1443): query,matched:0, calling pid = 2303
,I/ActivityManager( 1014): Killing 1634:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/TP/SmsProvider( 1443): match 0:Elapsed time : 4.341 ms
,W/ResourcesManager( 1443): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 2303): [end]    nonBlockingUpdateMessageIndicator() consume time = 483.034271
W/ResourcesManager( 1443): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1443): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1443): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1443): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,I/SmartcardBootCompleteReceiver( 1282): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1282): Received intent with action - android.intent.action.BOOT_COMPLETED
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1224): savePlaylistTableInBulkDeleter finished
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,I/SmartcardBootCompleteReceiver( 1282): Broadcast sent with current lockscreen type
,D/MediaScanner( 1224): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/Mms/MessagingNotification( 2303): updateAllHistoryAsRead()
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_1634/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1443): query,matched:200, calling pid = 2303
,D/TP/MmsSmsProvider( 1443): match 200:Elapsed time : 3.452 ms
,E/Zygote  ( 2956): MountEmulatedStorage(),
,E/Zygote  ( 2956): v2
I/libpersona( 2956): KNOX_SDCARD checking this for 10160
I/SELinux ( 2956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 2956): KNOX_SDCARD not a persona
,I/SELinux ( 2956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 2956): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2956 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2271:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31,
,V/MediaScanner( 1224): processDirectory :  /storage/emulated/0
,D/TimaKeyStoreProvider( 2956): TimaSignature is unavailable
D/ActivityThread( 2956): Added TimaKeyStore provider
,D/MediaScanner( 1224): Skipping:
D/MediaScanner( 1224): 7klwibgf7fvntblfd7(75ebcf7
,D/[SBeam] ( 1282): SBeamEnabler.initPreferenceForSbeam : 0
I/SecureStorage(  366): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,D/TP/SmsProvider( 1443): query,matched:0, calling pid = 2303
D/MediaScanner( 1224): Skipping:
D/MediaScanner( 1224): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,W/ActivityThread( 2938): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/MediaScanner( 1224): processDirectory :  /storage/extSdCard
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
W/MediaScanner( 1224): Error opening directory, reason : Permission denied.
W/MediaScanner( 1224): 7klwibgf7fxlKdCbid7
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,I/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
V/MediaScanner( 1224):  prescan time: 86ms (DB items: 27)
V/MediaScanner( 1224):     scan time: 79ms (Caching mode: true), (makeEntry time: 74ms ~93%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1224): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1224):    total time: 167ms
V/MediaScanner( 1224): checked files: 10  directories : 17  (I: 0, U: 0)
W/ResourcesManager( 2956): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/MediaScannerService( 1224): !@done scanning volume external
,D/FactoryTestApp( 2613): [DummyFtClient$mBroadcastReceiver](2613) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2613): [DummyFtClient$mBroadcastReceiver](2613) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2613): [DummyFtClient$sendBootCompletedAndFinish](2613) ...
D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2613): [ModuleCommon$isConnectionModeNone](2613) mConnectionMode = gsm
,D/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$ResponseWriter](2613) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$connectToSecPhoneService](2613)  
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ContextImpl( 2613): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1014): bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/art     ( 2840): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 240.196ms
,I/SettingSearch/SearchIntentReceiver( 1282): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1282): search setting db init!!
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,I/SettingSearch/SearchIntentReceiver( 1282): BOOT_COMPLETED call InitSerachDBThread thread start!
,D/TP/SmsProvider( 1443): match 0:Elapsed time : 66.075 ms
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2271/cgroup.procs: No such file or directory
,D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,I/SecureStorage( 2768): [INFO]: SPID(0x00000003)Processing data has been completed
,I/SecureStorage( 2768): [INFO]: SPID(0x00000003)Skip using SecureStorageExceptionJNI
,D/TP/SmsProvider( 1443): query,matched:51, calling pid = 2303
,D/TP/SmsProvider( 1443): match 51:Elapsed time : 0.944 ms
,I/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$onServiceConnected](2613) connected done
D/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$write](2613) Send Response Message to SecPhone
D/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$write](2613) Response ��
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 28
,E/Zygote  ( 2977): MountEmulatedStorage(),
E/Zygote  ( 2977): v2
I/libpersona( 2977): KNOX_SDCARD checking this for 1000
I/libpersona( 2977): KNOX_SDCARD not a persona
,I/SELinux ( 2977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 2977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2977 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SMD     (  286): DCD OFF
E/SELinux ( 2977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/AT_Distributor(  311): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/Mms/MessagingNotification( 2303): isBlockingModeEnabled() = false, Zen mode = 0
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$handleMessage](2613) Send BOOTING COMPLETED done
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4,
I/libpersona( 2991): KNOX_SDCARD checking this for 10150
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
I/libpersona( 2991): KNOX_SDCARD not a persona
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
E/Zygote  ( 2991): MountEmulatedStorage()
,E/Zygote  ( 2991): v2
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
I/SELinux ( 2991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/LcdtestApp( 2938): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,I/ActivityManager( 1014): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2991 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,I/LcdtestApp( 2938): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,I/SELinux ( 2991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 2991): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
D/TimaKeyStoreProvider( 2977): TimaSignature is unavailable
I/ServiceManager(  315): Waiting for service AtCmdFwd...
D/ActivityThread( 2977): Added TimaKeyStore provider,
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/art     (  307): Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 25.824ms
,D/TimaKeyStoreProvider( 2991): TimaSignature is unavailable
D/ActivityThread( 2991): Added TimaKeyStore provider
,D/[0]UMC:UMCContentProvider( 2956): @onCreate
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 594us total 18.155ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 16.610ms
,E/Zygote  ( 3008): MountEmulatedStorage(),
E/Zygote  ( 3008): v2
,I/libpersona( 3008): KNOX_SDCARD checking this for 1000
I/libpersona( 3008): KNOX_SDCARD not a persona
,I/SELinux ( 3008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/AT_Distributor(  311): SetAtdStatus(), 1_1_0
D/AT_Distributor(  311): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,I/SELinux ( 3008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 2899): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 3008): TimaSignature is unavailable
,D/ActivityThread( 3008): Added TimaKeyStore provider
,W/ResourcesManager( 2977): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/[0]UMC:Core( 2956): onCreate(): 
D/[0]UMC:Core( 2956): @isManagedProfileUser
D/[0]UMC:Core( 2956): userId: 0
,D/[0]UMC:Core( 2956): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2956): userInfo.isManagedProfile() : false
,D/[0]UMC:DeviceInfo( 2956): USA==US==
,I/FOTA    ( 2977): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/Launcher.Model( 1466): reloadBadges entered.
D/BadgeProvider( 2899): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2899): sendNotify, [notify] : null
D/BadgeProvider( 2899): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 2899): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 2899): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 2303): setBadgeCount(), count=0
,D/Mms/MessagingNotification( 2303): remove alarm
,D/Mms/MessagingNotification( 2303): updateAllHistoryAsRead()
,D/TP/SmsProvider( 1443): query,matched:0, calling pid = 2303
,D/TP/SmsProvider( 1443): match 0:Elapsed time : 1.593 ms
,D/Mms/SmsReceiverService( 2303): [end]    handleBootCompleted() consume time = 564.731614
,I/ActivityManager( 1014): Killing 2324:com.sec.android.omc/1000 (adj 15): empty #31
,E/BluetoothHeadset( 2768): BTStateChangeCB is registed
,D/BluetoothHeadset( 2768): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2768): BluetoothHeadset service is binded
,I/DIAGMON_AGENT( 3008): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/BluetoothA2dp( 2768): doBind(): CallingUid(myUserHandle) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapter( 2768): 763202717: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2768): 763202717: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2768): 763202717: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2768): 763202717: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2768): 763202717: getState() :  mService = null. Returning STATE_OFF
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2324/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3027): MountEmulatedStorage()
E/Zygote  ( 3027): v2
I/libpersona( 3027): KNOX_SDCARD checking this for 1000
I/libpersona( 3027): KNOX_SDCARD not a persona
,I/SELinux ( 3027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 2355:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3027): TimaSignature is unavailable
,D/ActivityThread( 3027): Added TimaKeyStore provider
,W/ResourcesManager( 3027): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/USER_AGENT( 2956): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US,
,E/Zygote  ( 3042): MountEmulatedStorage()
,E/Zygote  ( 3042): v2
I/libpersona( 3042): KNOX_SDCARD checking this for 10086
I/libpersona( 3042): KNOX_SDCARD not a persona
I/SELinux ( 3042): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3042): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3042 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3042): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Killing 2374:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/[0]UMC:AdminManager( 2956): init - start
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1014): startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DIAGMON_AGENT( 3008): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1014): Killing 2258:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/DIAGMON_AGENT( 3008): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 3008): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,D/[0]UMC:AdminManager( 2956): loadAdmins
,I/DIAGMON_AGENT( 3008): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DIAGMON_AGENT( 3008): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
I/DIAGMON_AGENT( 3008): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/TimaKeyStoreProvider( 3042): TimaSignature is unavailable
,D/ActivityThread( 3042): Added TimaKeyStore provider
,D/OverheatReceiver( 1174): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1174): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1174): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1174): isSafeMode = false
,D/[0]UMC:AdminManager( 2956): init - end
D/BootupListener( 1443): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1014): name = internet_call_settings_visibility
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 1001
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
D/PhoneUtilsCommon( 1443): isSupportVoLTE is false.
D/GSLBManager( 2956): migrateStoredUrlFromOldPref
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/Telecom ( 1419): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,I/DBG_DM  ( 2977): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
D/ActivityManager( 1014): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 2977): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,D/ActivityManager( 1014): bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,I/DBG_DM  ( 2977): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 2977): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 2977): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/GSLBManager( 2956): migrateStoredUrlFromOldPref : Migration Not Needed
,I/DBG_DM  ( 2977): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
W/ContextImpl( 2977): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,D/[0]UMC:UMCAdmin( 2956): deactivateUMCAdminIfNotRequired : -1,
,E/[0]UMC:Utils( 2956): Admin not found in package com.samsung.knoxpb.mdm
,I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,E/[0]UMC:Utils( 2956): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox,
D/[0]UMC:UMCAdmin( 2956): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2956): isContainer : 0
I/DBG_DM  ( 2977): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2956): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2956): isContainer : 0
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,D/[0]UMC:UMCAdmin( 2956): deactivateUMCAdmin - UMC App Admin deactivated
,E/Zygote  ( 3062): MountEmulatedStorage()
E/Zygote  ( 3062): v2
I/libpersona( 3062): KNOX_SDCARD checking this for 10057
I/libpersona( 3062): KNOX_SDCARD not a persona
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2355/cgroup.procs: No such file or directory
,I/SELinux ( 3062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/Tethering( 1014): No numeric data,
I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3062 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 3062): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/libprocessgroup( 1014): failed to open /acct/uid_10131/pid_2374/cgroup.procs: No such file or directory
,E/Tethering( 1014): No numeric data
E/SELinux ( 3062): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,I/Telecom ( 1419): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,E/Tethering( 1014): No numeric data
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Tethering( 1014): No numeric data
,D/TimaKeyStoreProvider( 3062): TimaSignature is unavailable
,D/ActivityThread( 3062): Added TimaKeyStore provider
,E/Zygote  ( 3077): MountEmulatedStorage()
I/libpersona( 3077): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3077): v2
I/libpersona( 3077): KNOX_SDCARD not a persona
,I/SELinux ( 3077): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3077 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1014): startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
I/SELinux ( 3077): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3077): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[0]UMC:GuardService( 2956): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,D/[0]UMC:CoreReceiver( 2956): Intent : android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2258/cgroup.procs: No such file or directory
D/[0]UMC:CoreReceiver( 2956):  check PreETag 
,D/ActivityManager( 1014): bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2977): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,D/TimaKeyStoreProvider( 3077): TimaSignature is unavailable
,D/ActivityThread( 3077): Added TimaKeyStore provider
,D/[SBeam] ( 1282): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1282): SBeamEnabler.isSBeamSupported : EXIST
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,E/Tethering( 1014): No numeric data
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/[0]UMC:CoreReceiver( 2956): bulk enrolled package: null
,V/[0]UMC:ProfileStorage( 2956): Enter loadList
,D/[0]UMC:CoreReceiver( 2956): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2956): deactivateUMCAdminIfNotRequired : -1
,E/UpdateRequestReceiver( 3042): ignoring update request
,E/[0]UMC:Utils( 2956): Admin not found in package com.samsung.knoxpb.mdm
,E/[0]UMC:Utils( 2956): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2956): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2956): isContainer : 0
,V/audio_hw_primary(  281): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  281): audio_extn_get_parameters: returns 
V/msm8974_platform(  281): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  281): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  281): key: 'call_forwarding' value: ''
,V/InCall  ( 1940): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1940): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1940): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
D/EnterpriseDeviceManagerService( 1014): isManagedProfileUser(): userId = 0
,E/[0]UMC:UMCAdmin( 2956): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2956): isContainer : 0
,D/ScoverManager( 1940): serviceVersion : 16908288,
D/[0]UMC:UMCAdmin( 2956): deactivateUMCAdmin - UMC App Admin deactivated
I/Telecom ( 1419): ProximitySensorManager: Proximity wake lock already released,
D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1940): InCallUtils - isCoverClosed false
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1940): InCallUtils - isCoverClosed false
,I/InCall  ( 1940): InCallPresenter -  - InCallState = NO_CALLS
,D/[0]UMC:ByodSetupStarter( 2956): Container ID : 0
,I/InCall  ( 1940): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,D/InCall  ( 1940): InCallPresenter -  - dismissCoverDialog()...
V/[0]UMC:Utils( 2956): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2956): shutdown
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/[0]UMC:GuardService( 2956): @GuardService - stopService Result = true
,E/UpdateRequestReceiver( 3042): ignoring update request
,I/InCall  ( 1940): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1940): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,I/art     ( 2956): System.exit called, status: 0
I/AndroidRuntime( 2956): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager( 1014): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3105 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 3105): MountEmulatedStorage()
I/libpersona( 3105): KNOX_SDCARD checking this for 10009
E/Zygote  ( 3105): v2
I/libpersona( 3105): KNOX_SDCARD not a persona
,I/SELinux ( 3105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,D/PhoneStatusBarView( 1174): setCallBackground:0
,I/SELinux ( 3105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3105): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/NotificationAccessSettings( 1282): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
,E/UpdateRequestReceiver( 3042): ignoring update request
,V/VibratorService( 1014): hasVibrator - useVibetonz: true
I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1940): InCallUtils - isCoverClosed false
,E/UpdateRequestReceiver( 3042): ignoring update request
,D/TimaKeyStoreProvider( 3105): TimaSignature is unavailable
,D/ActivityThread( 3105): Added TimaKeyStore provider
E/USB_UICC(  298): Timeout! No signal received. Retry num = 29
I/DBG_POLICYDM( 3077): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3077): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,E/UpdateRequestReceiver( 3042): ignoring update request
,I/DBG_DM  ( 2977): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,W/ResourcesManager( 1282): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/UpdateRequestReceiver( 3042): ignoring update request
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3077): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,E/Zygote  ( 3131): MountEmulatedStorage()
,E/Zygote  ( 3131): v2
I/libpersona( 3131): KNOX_SDCARD checking this for 10092,
I/libpersona( 3131): KNOX_SDCARD not a persona
I/SELinux ( 3131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3131): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3131 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ServiceManager(  315): Waiting for service AtCmdFwd...,
I/DBG_POLICYDM( 3077): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0,
,I/ActivityManager( 1014): Killing 2435:com.wsomacp/u0a25 (adj 15): empty #31
,I/ActivityManager( 1014): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2956)(adj 0) has died(296,988)
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/DBG_POLICYDM( 3077): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3077): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/TimaKeyStoreProvider( 3131): TimaSignature is unavailable
,I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
D/ActivityThread( 3131): Added TimaKeyStore provider
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1406): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1406): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1174): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1174): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1298): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1298): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,I/DBG_DM  ( 2977): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/VideoCallManager( 1940): Instantiating VideoCallManager
,D/SettingsProvider( 1014): name = aw_daemon_service_key_version_check
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10162
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
I/GFX construct_block_size_descriptor_2d second part( 1940): took 2.278177ms for 0*0 texture 0
,W/libprocessgroup( 1014): failed to open /acct/uid_10025/pid_2435/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3077): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/GFX generate_partition_tables( 1940): took 5.145104ms for 0*0 texture 0
,I/GFX raster( 1940): took 11.475989ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb74fd420 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7515630 counterpartCT=4 counterpartW=176 counterparth=144
W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1940): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1940): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1940): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1940): Local Branch: 
I/Adreno-EGL( 1940): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1940): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1940):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 2977): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/GFX GPU raster( 1940): eglCreateImageKHR: EGL_SUCCESS
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,I/glCompressedTexImage2D( 1940): took 0.308385ms for 320*61440 texture 37809
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/draw setup( 1940): took 10.793906ms for 320*240 texture 37809
E/GFX GPU raster( 1940): drawn
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/GFX GPU raster ASTC( 1940): took 40.113750ms for 320*240 texture 12
I/GFX raster( 1940): took 40.198698ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb7515630 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7517970 counterpartCT=4 counterpartW=320 counterparth=240
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename,
D/LocationManagerService( 1014): getProviders()=[passive]
,E/Zygote  ( 3153): MountEmulatedStorage()
,I/libpersona( 3153): KNOX_SDCARD checking this for 10015
E/Zygote  ( 3153): v2
I/libpersona( 3153): KNOX_SDCARD not a persona,
,I/SELinux ( 3153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,E/daemonapp( 1298): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1940): eglCreateImageKHR: EGL_SUCCESS
I/ActivityManager( 1014): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3153 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/glCompressedTexImage2D( 1940): took 0.405521ms for 480*122880 texture 37813
I/draw setup( 1940): took 0.776406ms for 480*640 texture 37813
,E/GFX GPU raster( 1940): drawn
,E/SELinux ( 3153): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ScoverManager( 1282): serviceVersion : 16908288
,I/GFX GPU raster ASTC( 1940): took 7.423646ms for 480*640 texture 12
I/GFX raster( 1940): took 7.544844ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb7517970 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7745e00 counterpartCT=4 counterpartW=480 counterparth=640
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457426571546
D/daemonapp( 1298): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457448120000
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1298): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1298): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457448120000
,D/TimaKeyStoreProvider( 3153): TimaSignature is unavailable
,D/ActivityThread( 3153): Added TimaKeyStore provider
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457448120000
,E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
I/GFX GPU raster( 1940): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1940): took 0.391458ms for 440*116864 texture 37809
I/draw setup( 1940): took 0.770729ms for 440*330 texture 37809
E/GFX GPU raster( 1940): drawn
,I/GFX GPU raster ASTC( 1940): took 4.801979ms for 440*330 texture 12
I/GFX raster( 1940): took 4.877239ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb7745e00 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb775a1f0 counterpartCT=4 counterpartW=440 counterparth=330
,E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1940): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1940): took 0.442917ms for 480*163840 texture 37811
,I/draw setup( 1940): took 0.818803ms for 480*640 texture 37811
E/GFX GPU raster( 1940): drawn
,I/GFX GPU raster ASTC( 1940): took 5.809271ms for 480*640 texture 12
I/GFX raster( 1940): took 5.890677ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb774a000 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7759d28 counterpartCT=4 counterpartW=480 counterparth=640
,D/comdaemonstockapp( 1298): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1298): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3178): MountEmulatedStorage(),
,E/Zygote  ( 3178): v2
,I/libpersona( 3178): KNOX_SDCARD checking this for 10166,
I/ActivityManager( 1014): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3178 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 3178): KNOX_SDCARD not a persona
,I/SELinux ( 3178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3178): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1940): took 2.191094ms for 0*0 texture 0
,D/TimaKeyStoreProvider( 3178): TimaSignature is unavailable
,D/ActivityThread( 3178): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 1940): took 7.577136ms for 0*0 texture 0
,I/GFX raster( 1940): took 11.777813ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb77436c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb77437e0 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1940): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1940): took 2.201718ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1940): took 6.212553ms for 0*0 texture 0
,I/GFX raster( 1940): took 10.590209ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1940): Bitmap=0xb7743a00 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb77439a0 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1940): registerListener
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,D/CoverManagerWhiteLists( 1014): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1014): registerListenerCallback : binder = android.os.BinderProxy@3e8ff9c9, pid : 1940, uid : 1001, type : 1
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/DBG_POLICYDM( 3077): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/ActivityManager( 1014): Killing 2470:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
I/DBG_POLICYDM( 3077): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/InCall  ( 1940): InCallPresenter -  - Finished InCallPresenter.setUp
,E/DBG_POLICYDM( 3077): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3196): MountEmulatedStorage()
E/Zygote  ( 3196): v2
I/libpersona( 3196): KNOX_SDCARD checking this for 1000
I/libpersona( 3196): KNOX_SDCARD not a persona
,I/SELinux ( 3196): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3196 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3196): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 2528:com.sec.android.app.camera/u0a139 (adj 15): empty #31
E/SELinux ( 3196): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Killing 2495:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
I/ActivityManager( 1014): Killing 2485:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #33
,I/ActivityManager( 1014): Killing 2575:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3196): TimaSignature is unavailable
,D/ActivityThread( 3196): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
,W/libprocessgroup( 1014): failed to open /acct/uid_10142/pid_2495/cgroup.procs: No such file or directory
,D/Settings_Utils( 1282): isSupportVNFestival SM-A500FU XEO
,E/Zygote  ( 3212): MountEmulatedStorage()
I/libpersona( 3212): KNOX_SDCARD checking this for 10003
E/Zygote  ( 3212): v2
I/libpersona( 3212): KNOX_SDCARD not a persona
,I/SELinux ( 3212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3212 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/SELinux ( 3212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3212): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1014): failed to open /acct/uid_10044/pid_2470/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2575/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10088/pid_2485/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10139/pid_2528/cgroup.procs: No such file or directory
,I/art     (  307): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 22.791ms
,D/TimaKeyStoreProvider( 3212): TimaSignature is unavailable
D/ActivityThread( 3212): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.746ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 16.891ms
,D/UserAnalysis.PlaceProvider( 3212): PlaceProvider onCreate()
,I/DBG_FMMDM( 3196): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_FMMDM( 3196): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3196): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3196): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3227): MountEmulatedStorage()
,E/Zygote  ( 3227): v2
I/libpersona( 3227): KNOX_SDCARD checking this for 1000
,I/libpersona( 3227): KNOX_SDCARD not a persona
,I/SELinux ( 3227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3227 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
D/ActivityManager( 1014): startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
E/SELinux ( 3227): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.SecureDbManager( 3212): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3212): SecurePlaceDbHelper() ,
D/UserAnalysis( 3212): Create SecureDbHelper
,E/Zygote  ( 3237): MountEmulatedStorage()
I/libpersona( 3237): KNOX_SDCARD checking this for 10092
E/Zygote  ( 3237): v2
I/libpersona( 3237): KNOX_SDCARD not a persona
,I/SELinux ( 3237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3237 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3237): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3227): TimaSignature is unavailable
,D/ActivityThread( 3227): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 3212): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3212): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3178): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3178): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3237): TimaSignature is unavailable
D/ActivityThread( 3237): Added TimaKeyStore provider
,E/Zygote  ( 3259): MountEmulatedStorage()
E/Zygote  ( 3259): v2
I/libpersona( 3259): KNOX_SDCARD checking this for 10060
I/libpersona( 3259): KNOX_SDCARD not a persona
,I/SELinux ( 3259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3259 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2044:com.google.android.gms/u0a12 (adj 15): empty #31
,I/SELinux ( 3259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3259): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/IntelligenceServiceApplication( 3212): no applications having user consent for prediction
,W/art     ( 1282): Suspending all threads took: 5.363ms
,D/TimaKeyStoreProvider( 3259): TimaSignature is unavailable
,D/ActivityThread( 3259): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 3212): [PlaceDetection::stopService] Service stopped.
,I/PCWCLIENTTRACE_LOG( 3227): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3227): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3227): new DMDBOpenHelper instance
,V/JNIHelp ( 3178): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/PlaceDetection v1.0.19 ( 3212): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3212): Constructor Preference
,V/AlarmManager( 1014): waitForAlarm result :8
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3131): Setting receiver enabled: false
,D/PCWCLIENTTRACE_DMContentProvider( 3227): [URIMatcher] - result : 2
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 30
,W/libprocessgroup( 1014): failed to open /acct/uid_10012/pid_2044/cgroup.procs: No such file or directory
,I/DBG_FMMDM( 3196): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3196): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3196): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
I/ActivityManager( 1014): Killing 2560:com.android.calendar/u0a135 (adj 15): empty #31
,W/ActivityThread( 3178): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3178): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d7fd70d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3178): Installed default security provider GmsCore_OpenSSL
,E/USB_UICC(  298): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  298): usb_uicc_init_qmi failed ! 
I/USB_UICC(  298): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  298): usb_uicc_cleanup, Issuing QMI deinit ... 
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 17993(1015KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 25MB/38MB, paused 2.343ms total 156.268ms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_2560/cgroup.procs: No such file or directory
,E/Zygote  ( 3288): MountEmulatedStorage()
,E/Zygote  ( 3288): v2
I/libpersona( 3288): KNOX_SDCARD checking this for 1000
,I/SELinux ( 3288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3288): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3288 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Killing 2640:com.android.keychain/1000 (adj 15): empty #31
E/SELinux ( 3288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 1699:com.android.defcontainer/u0a4 (adj 15): empty #31
,E/ActivityThread( 3131): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/TimaKeyStoreProvider( 3288): TimaSignature is unavailable
,D/ActivityThread( 3288): Added TimaKeyStore provider
,I/dbxyzptlk.db240408.D.h( 3131): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/dbxyzptlk.db240408.D.h( 3131): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2640/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10004/pid_1699/cgroup.procs: No such file or directory
,I/DBG_FMMDS( 3288): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3288): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/dbxyzptlk.db240408.D.h( 3131): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/sCloudBackupApp( 3259): sCloudBackupApp Version Info : 4.04.8.KK_APP
,D/PCWCLIENTTRACE_DMContentProvider( 3227): [URIMatcher] - result : 2
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3307): MountEmulatedStorage()
E/Zygote  ( 3307): v2
I/libpersona( 3307): KNOX_SDCARD checking this for 10062
I/libpersona( 3307): KNOX_SDCARD not a persona
,I/SELinux ( 3307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3307 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/DBG_FMMDS( 3288): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/dbxyzptlk.db240408.D.h( 3131): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/DBG_FMMDS( 3288): [50.18.150420][Line:43][xdbDBInit] 
,D/TimaKeyStoreProvider( 3307): TimaSignature is unavailable
,D/ActivityThread( 3307): Added TimaKeyStore provider
,D/breakpad( 3131): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/com.dropbox.sync.android.a( 3131): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/com.dropbox.sync.android.ad( 3131): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,I/LockPatternUtils( 1282): isSmartCardAuthenticationAvailable: false
,I/DBG_FMMDS( 3288): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,W/ResourcesManager( 3178): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3178): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/DBG_FMMDS( 3288): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3288): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3288): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3288): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3288): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3288): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/ExternalOEMControlProvider( 3307): onCreate
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3335): MountEmulatedStorage()
E/Zygote  ( 3335): v2
I/libpersona( 3335): KNOX_SDCARD checking this for 1000
I/libpersona( 3335): KNOX_SDCARD not a persona
,I/SELinux ( 3335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3335 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/SettingsProvider( 1014): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10062
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
E/SELinux ( 3335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1014): name = PREVIOUS_ELAPSED_TIME
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10062
D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/TimaKeyStoreProvider( 3335): TimaSignature is unavailable
,D/ActivityThread( 3335): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/ActivityManager( 1014): Killing 2682:com.samsung.android.sm/1000 (adj 15): empty #31
,W/ResourcesManager( 3335): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/ServiceMode( 3335): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3335): setReferenceIsDumpState : 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2682/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3353): MountEmulatedStorage()
E/Zygote  ( 3353): v2
I/libpersona( 3353): KNOX_SDCARD checking this for 1000
I/libpersona( 3353): KNOX_SDCARD not a persona
I/SELinux ( 3353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3353 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/SELinux ( 3353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/FOTA_Client( 3105): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3105): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,D/TimaKeyStoreProvider( 3353): TimaSignature is unavailable
,D/ActivityThread( 3353): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3369): MountEmulatedStorage()
,I/libpersona( 3369): KNOX_SDCARD checking this for 10094
E/Zygote  ( 3369): v2
I/libpersona( 3369): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3369 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Killing 2716:flipboard.boxer.app/u0a99 (adj 15): empty #31
E/SELinux ( 3369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/FOTA_Client( 3105): [IlIlIIllllIllIIIIIll(86/llllIIIllIlIIIIllllI)] Polling time is not vaild
,D/TimaKeyStoreProvider( 3369): TimaSignature is unavailable
D/ActivityThread( 3369): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3353): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3353): [] Service onCreate!!
,E/Zygote  ( 3388): MountEmulatedStorage()
E/Zygote  ( 3388): v2
I/libpersona( 3388): KNOX_SDCARD checking this for 1000
I/libpersona( 3388): KNOX_SDCARD not a persona
,W/FOTA_Client( 3105): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
I/SELinux ( 3388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 3369): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,E/Zygote  ( 3404): MountEmulatedStorage()
I/libpersona( 3404): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3404): v2
I/libpersona( 3404): KNOX_SDCARD not a persona
,I/System.out( 3131): Thread-434(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/elm:15183( 3369): ELMEngine.ELMEngine( context ).
,I/SELinux ( 3404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/TimaKeyStoreProvider( 3388): TimaSignature is unavailable
,D/ActivityThread( 3388): Added TimaKeyStore provider
I/SELinux ( 3404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3404): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/elm:15183( 3369): MDMBridge.setEnterpriseBridge()
,I/ActivityManager( 1014): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3404 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2145:flipboard.app/u0a98 (adj 15): empty #31
,I/System.out( 3131): Thread-434(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3131): Thread-434(ApacheHTTPLog):isShipBuild true
D/ActivityManager( 1014): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/System.out( 3131): Thread-434(ApacheHTTPLog):SMARTBONDING_ENABLED is false
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/System.out( 3131): Thread-434(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,D/elm:15183( 3369): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/ActivityManager( 1014): Killing 2735:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1282): InitSerachDBThread thread end!
I/dex2oat ( 3393): ----------------------------------------------------
I/dex2oat ( 3393): <SS>: S T A R T I N G . . .
I/dex2oat ( 3393): <SS>: Zip is absent. Canceled.
I/dex2oat ( 3393): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads752163150.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads752163150.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/EnterpriseController(  276): uids 10092
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10092
,D/TimaKeyStoreProvider( 3404): TimaSignature is unavailable
,D/ActivityThread( 3404): Added TimaKeyStore provider
,D/elm:15183( 3369): ElmAgentService : onCreate()
,V/EmergencyMode( 1406): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15183( 3369): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3369): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3369): BootCompletedState : startBootCompleted() call
,I/System.out( 3131): pool-10-thread-1 calls detatch()
,D/NPS_WSSNPS( 3353): [50.150621] NpsServiceTask Start
W/ResourcesManager( 3388): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:15183( 3369): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3369): Get License : 0
D/elm:15183( 3369): ElmAgentService : onDestroy().
,I/ActivityManager( 1014): Killing 2749:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/NPS_WSSNPS( 3353): [50.150621] smlDBHelper
,W/System.err( 3178): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,V/OneTimeInitializerReceiver( 3404): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,V/OneTimeService( 3404): OneTimeService.onHandleIntent
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,V/EmergencyMode( 1406): [EmergencyBase] setBootTime
V/EmergencyMode( 1406): [EmergencyFactory] No Recovery State, kill my self.
,I/System.out( 3178): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 3178): YouTube MDX: MDX video player state moved to UNSTARTED
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/System.out( 3178): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/NPS_WSSNPS( 3353): [50.150621] AsyncBulkFlagCheck
,E/Zygote  ( 3441): MountEmulatedStorage(),
E/Zygote  ( 3441): v2
I/libpersona( 3441): KNOX_SDCARD checking this for 1000
,I/libpersona( 3441): KNOX_SDCARD not a persona
I/SELinux ( 3441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3441 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/dex2oat ( 3393): dex2oat took 132.839ms (threads: 4)
,W/libprocessgroup( 1014): failed to open /acct/uid_10099/pid_2716/cgroup.procs: No such file or directory
,I/NPS_WSSNPS( 3353): [50.150621] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 3353): [50.150621] IsRemain_Asyncing nothing
W/ContextImpl( 3353): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/libprocessgroup( 1014): failed to open /acct/uid_10152/pid_2749/cgroup.procs: No such file or directory
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2735/cgroup.procs: No such file or directory
E/SELinux ( 3441): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,I/art     (  307): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 759us total 27.353ms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/FactoryTestApp( 2613): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2976)  
D/NPS_WSSNPS( 3353): [50.150621] Service onDestroy
,I/NPS_WSSNPS( 3353): [50.150621] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3353): [50.150621] smlBRMessageDelete
,D/TimaKeyStoreProvider( 3441): TimaSignature is unavailable
,D/ActivityThread( 3441): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3353): [50.150621] smlBREmailDelete
,I/NPS_WSSNPS( 3353): [50.150621] smlBRNetworkDelete
,I/NPS_WSSNPS( 3353): [50.150621] smlBRCallLogDelete
,I/ActivityManager( 1014): Killing 2337:com.sec.modem.settings/1000 (adj 15): empty #31
,I/NPS_WSSNPS( 3353): [50.150621] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3353): [50.150621] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3353): [50.150621] smlBRSMemoDelete
I/NPS_WSSNPS( 3353): [50.150621] verifier installed? false
,I/NPS_WSSNPS( 3353): [50.150621] cpuBooster release : false
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 814us total 23.910ms
,E/SMD     (  286): DCD OFF
D/NPS_WSSNPS( 3353): [50.150621] dsServerSocket close
,I/ActivityManager( 1014): Killing 2803:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 19.002ms
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3466): MountEmulatedStorage()
,E/Zygote  ( 3466): v2
I/libpersona( 3466): KNOX_SDCARD checking this for 1000
I/libpersona( 3466): KNOX_SDCARD not a persona
I/SELinux ( 3466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3466 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3466): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
W/libprocessgroup( 1014): failed to open /acct/uid_10098/pid_2145/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1101/pid_2803/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2337/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3466): TimaSignature is unavailable
,D/ActivityThread( 3466): Added TimaKeyStore provider
,I/CameraApp( 3441): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3441): Feature.Feature(context)
I/testFeature( 3441): Feature.readInternalDefaultXml()
I/testFeature( 3441): ResetFeatureValue
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,I/CameraFirmware_broadcast( 3441): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3441): CameraApp.getAppFeature()...
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3487): MountEmulatedStorage()
E/Zygote  ( 3487): v2
I/libpersona( 3487): KNOX_SDCARD checking this for 1000
I/libpersona( 3487): KNOX_SDCARD not a persona
,I/SELinux ( 3487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2785:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,I/SELinux ( 3487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3502): MountEmulatedStorage(),
E/Zygote  ( 3502): v2
I/libpersona( 3502): KNOX_SDCARD checking this for 10100
I/libpersona( 3502): KNOX_SDCARD not a persona,
,I/SELinux ( 3502): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3502): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3502): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3502 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 2303:com.android.mms/u0a46 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3487): TimaSignature is unavailable
D/ActivityThread( 3487): Added TimaKeyStore provider
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3518): MountEmulatedStorage()
E/Zygote  ( 3518): v2
,D/TimaKeyStoreProvider( 3502): TimaSignature is unavailable
I/libpersona( 3518): KNOX_SDCARD checking this for 10012,
I/SELinux ( 3518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 3518): KNOX_SDCARD not a persona
D/ActivityThread( 3502): Added TimaKeyStore provider,
I/ActivityManager( 1014): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3518 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 3518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,E/SELinux ( 3518): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3466): onCreate
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,I/Hs20UtilService( 3466): Starting #1
,I/Hs20UtilService( 3466): Message received 5003
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3518): TimaSignature is unavailable
D/ActivityThread( 3518): Added TimaKeyStore provider
,E/Zygote  ( 3537): MountEmulatedStorage()
,E/Zygote  ( 3537): v2
I/libpersona( 3537): KNOX_SDCARD checking this for 10019
I/libpersona( 3537): KNOX_SDCARD not a persona
,I/SELinux ( 3537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3537 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/CountryDetector( 1014): No listener is left
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2785/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10046/pid_2303/cgroup.procs: No such file or directory
,D/SettingsProvider( 1014): name = access_control_enabled
,D/TimaKeyStoreProvider( 3537): TimaSignature is unavailable
,I/ActivityManager( 1014): Killing 2824:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,D/ActivityThread( 3537): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/PackageIntentReceiver( 3502): ACTION_BOOT_COMPLETED
,W/ResourcesManager( 3518): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3518): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 3554): MountEmulatedStorage()
E/Zygote  ( 3554): v2
I/libpersona( 3554): KNOX_SDCARD checking this for 10069
I/libpersona( 3554): KNOX_SDCARD not a persona
,D/PackageIntentReceiver( 3502): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..,
I/SELinux ( 3554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3554): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3554 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3554): TimaSignature is unavailable,
,E/Zygote  ( 3569): MountEmulatedStorage(),
E/Zygote  ( 3569): v2
D/ActivityThread( 3554): Added TimaKeyStore provider
I/ActivityManager( 1014): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3569 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 3569): KNOX_SDCARD checking this for 10101
I/libpersona( 3569): KNOX_SDCARD not a persona,
I/ActivityManager( 1014): Killing 2873:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,I/SELinux ( 3569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3569): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3569): TimaSignature is unavailable
,I/RlzPingService( 3153): Setting next ping for 1458031373839
,D/ActivityThread( 3569): Added TimaKeyStore provider
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.183: ( 3537): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 08 09:42:53 GMT+01:00 2016
,I/MultiDex( 3518): VM with version 2.1.0 has multidex support
I/MultiDex( 3518): install
I/MultiDex( 3518): VM has multidex support, MultiDex support library is disabled.
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3537): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,D/FileShare-Server( 3554): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3586): MountEmulatedStorage(),
I/KLMS-2.5.183: ( 3537): KLMSIntentService(): onCreate()
E/Zygote  ( 3586): v2
,I/SELinux ( 3586): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3586): KNOX_SDCARD checking this for 10022
I/ActivityManager( 1014): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3586 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
I/libpersona( 3586): KNOX_SDCARD not a persona
,I/SELinux ( 3586): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 3586): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3537): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3537): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3537): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3537): KLMSIntentService(): BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3586): TimaSignature is unavailable
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityThread( 3586): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10048/pid_2824/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10157/pid_2873/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Killing 2888:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3537): KLMSIntentService(): onDestroy()
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3178): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,V/JNIHelp ( 3518): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3610): MountEmulatedStorage(),
E/Zygote  ( 3610): v2
,I/libpersona( 3610): KNOX_SDCARD checking this for 1000
I/libpersona( 3610): KNOX_SDCARD not a persona
,I/SELinux ( 3610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3610 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 2899:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3610): TimaSignature is unavailable
,D/ActivityThread( 3610): Added TimaKeyStore provider
,W/ActivityThread( 3518): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3518): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3fcb8458: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3518): Installed default security provider GmsCore_OpenSSL
,E/MTPRx   ( 3610): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 3610): sealedState: false
,V/MTPRx   ( 3610): sealedUsbMassStorageState: false
,D/SettingsProvider( 1014): name = mtp_usb_connection_status
,W/libprocessgroup( 1014): failed to open /acct/uid_10159/pid_2888/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_10072/pid_2899/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SettingsProvider( 1014): name = media_player_mode
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = media_mount_count
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/AudioService( 1014): getStreamVolume 3 index 0
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/NativeLibraryUtils( 3518): Install completed successfully. count=14 extracted=0
,D/SettingsProvider( 1014): name = mtp_sync_alive
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1014): name = boot_time_connected
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3178): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3178): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3178): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/ActivityManager( 1014): Killing 2856:com.sec.dsm.system/1000 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1014): name = mtp_open_session
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1014): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3641): MountEmulatedStorage()
I/libpersona( 3641): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3641): v2
I/libpersona( 3641): KNOX_SDCARD not a persona
I/SELinux ( 3641): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3641 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3641): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3641): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,D/TimaKeyStoreProvider( 3641): TimaSignature is unavailable
,D/ActivityThread( 3641): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2856/cgroup.procs: No such file or directory
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 22757(1266KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 26MB/39MB, paused 2.207ms total 154.975ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/PCWCLIENTTRACE_PushUtil( 3227): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3227): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3227): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3227): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3227): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3227): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/PCWCLIENTTRACE_PCWHandler( 3227): [ensureRegistration] - netwrok is not available. action ignored
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3676): MountEmulatedStorage()
,E/Zygote  ( 3676): v2
I/libpersona( 3676): KNOX_SDCARD checking this for 10031
I/libpersona( 3676): KNOX_SDCARD not a persona
,I/SELinux ( 3676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3676 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a,
I/ActivityManager( 1014): Killing 2921:com.sec.usbsettings/1000 (adj 15): empty #31,
I/SELinux ( 3676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3676): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/ActivityManager( 1014): Killing 2938:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/art     (  307): Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 25.865ms
,D/TimaKeyStoreProvider( 3676): TimaSignature is unavailable
,D/ActivityThread( 3676): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 17.335ms
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.133ms
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ResourcesManager( 3676): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3702): MountEmulatedStorage()
,I/libpersona( 3702): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3702): v2
I/libpersona( 3702): KNOX_SDCARD not a persona
I/SELinux ( 3702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3702 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
W/ActivityManager( 1014): userId = 0, bbcId = -10000,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2938/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_2921/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/TimaKeyStoreProvider( 3702): TimaSignature is unavailable
,D/ActivityThread( 3702): Added TimaKeyStore provider
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ResourcesManager( 3702): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ContextImpl( 1928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,I/Gmail   ( 3569): getAccountsCursor
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
D/SecUISvc( 1928): Service started flags 0 startId 1
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/SecUISvc( 1928): Thread created.
,E/Zygote  ( 3726): MountEmulatedStorage()
E/Zygote  ( 3726): v2
I/ActivityManager( 1014): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3726 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 3726): KNOX_SDCARD checking this for 10028
I/libpersona( 3726): KNOX_SDCARD not a persona
,I/SELinux ( 3726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SELinux ( 3726): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3726): TimaSignature is unavailable
,D/ActivityThread( 3726): Added TimaKeyStore provider
,W/GAV2    ( 3569): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1014): Killing 2991:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/VlingoApplication( 3676): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,D/BluetoothAdapter( 3676): 788359934: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3676): 788359934: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3676): 788359934: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3676): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/VlingoApplication( 3676): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,I/ActivityManager( 1014): Killing 2840:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/VlingoApplication( 3676): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/libprocessgroup( 1014): failed to open /acct/uid_10150/pid_2991/cgroup.procs: No such file or directory
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 3569): Error finding the version of the Email provider.....
E/Gmail   ( 3569): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3569): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3569): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 3569): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3569): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3569): We do not support migrating this version of the Email provider.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3569): getAccountsCursor
,D/DialogFlow( 3676): initQueue()
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1014): failed to open /acct/uid_10085/pid_2840/cgroup.procs: No such file or directory
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/GoogleHttpClient( 1643): GMS http client unavailable, use old client
,E/Zygote  ( 3759): MountEmulatedStorage(),
I/libpersona( 3759): KNOX_SDCARD checking this for 10032
E/Zygote  ( 3759): v2
I/libpersona( 3759): KNOX_SDCARD not a persona
,I/SELinux ( 3759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 3759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3759 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/TimaService( 1014): TIMA: in getTimaVersion
D/TimaService( 1014): TIMA3: KeyStore3_init
E/TLC_TZ_KEYSTORE: ( 1014): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1014): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1014): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1014): initializing ccm context...
I/TLC_TZ_KEYSTORE: ( 1014): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1014): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1014): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1014): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1014): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1014): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1014): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1014): App is not loaded in QSEE
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3641): Resource data:2131165186
,E/SELinux ( 3759): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3641): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3641): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3641): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
W/ResourcesManager( 3641): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/Zygote  ( 3768): MountEmulatedStorage()
E/Zygote  ( 3768): v2
,I/libpersona( 3768): KNOX_SDCARD checking this for 10104
I/libpersona( 3768): KNOX_SDCARD not a persona
,I/SELinux ( 3768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 3768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3768 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 3768): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/QSEECOMAPI: ( 1014): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1014): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1014): ctx = 0xb7958b90, comm = 0xb7904940, sendmsg = 0xa0a0d000, recvmsg = 0xa0a0d440
I/TZ_init: ( 1014): TZ_init: sending initialization request...
,I/AMMetaDataParserService( 3641): Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,E/TZ_init: ( 1014): TZ_init Process: Secure memory is not initialized!
,E/TZ_init: ( 1014): trustlet initialization failed
I/TZ_init: ( 1014): TZ_init_START...
,D/TimaKeyStoreProvider( 3759): TimaSignature is unavailable
,D/ActivityThread( 3759): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 3569): Observing account changes for notifications
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3569): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1bc36b that was originally bound here
E/ActivityThread( 3569): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1bc36b that was originally bound here
E/ActivityThread( 3569): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3569): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3569): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3569): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3569): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3569): 	at com.android.emailcommon.service.ah.a(SourceFile:181)
E/ActivityThread( 3569): 	at com.android.emailcommon.service.ah.e(SourceFile:224)
E/ActivityThread( 3569): 	at com.android.email.service.n.c(SourceFile:161)
E/ActivityThread( 3569): 	at com.android.email.provider.b.a(SourceFile:173)
E/ActivityThread( 3569): 	at com.android.email.provider.b.a(SourceFile:117)
E/ActivityThread( 3569): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
E/ActivityThread( 3569): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
E/ActivityThread( 3569): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3569): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3569): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3569): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1014): Unbind failed: could not find connection for android.os.BinderProxy@166967bd
,I/TZ_init: ( 1014): TZ_init_with_data: sending initialization request...
,I/TZ_init: ( 1014): TZ_init: successful initialization
D/QSEECOMAPI: ( 1014): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1014): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1014): Count : 1, Ret : 0
,D/TimaKeyStoreProvider( 3768): TimaSignature is unavailable
,D/ActivityThread( 3768): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3641): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3641): Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3768): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 3726): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/FactoryTestApp( 2613): [DummyFtClient$onDestroy](2613) Destroy DummyFtClient service
,D/FactoryTestApp( 2613): [Support$Values.getString](2613) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2613): [ModuleCommon$isConnectionModeNone](2613) mConnectionMode = gsm
I/FactoryTestApp( 2613): [ModuleCommon$isRunningFtClient](2613) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2613): [DummyFtClient$onDestroy](2613) kill process
I/Process ( 2613): Sending signal. PID: 2613 SIG: 9
,I/ActivityManager( 1014): Process com.sec.factory (pid 2613)(adj 0) has died(192,1061)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3802): MountEmulatedStorage(),
E/Zygote  ( 3802): v2
I/libpersona( 3802): KNOX_SDCARD checking this for 10033
I/libpersona( 3802): KNOX_SDCARD not a persona
,I/SELinux ( 3802): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3802 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3802): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Killing 3008:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,E/SELinux ( 3802): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.fir,efox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,D/TimaKeyStoreProvider( 3802): TimaSignature is unavailable
,D/ActivityThread( 3802): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131034113
,W/ResourcesManager( 3641): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3641): took 2.179375ms for 0*0 texture 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3008/cgroup.procs: No such file or directory
,I/GFX generate_partition_tables( 3641): took 6.204479ms for 0*0 texture 0
,I/GFX raster( 3641): took 9.653956ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508fa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7508f70 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/SQLiteLog( 3569): (283) recovered 123 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/Finsky  ( 3726): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/ContextImpl( 3702): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3833): MountEmulatedStorage()
E/Zygote  ( 3833): v2
I/libpersona( 3833): KNOX_SDCARD checking this for 1000
I/libpersona( 3833): KNOX_SDCARD not a persona
,I/SELinux ( 3833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3833 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3833): TimaSignature is unavailable
,D/ActivityThread( 3833): Added TimaKeyStore provider
,W/ResourcesManager( 3833): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/Settings( 3726): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3726): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ContextImpl( 3833): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,I/F_PHONE ( 3833): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3833): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1014): bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.845730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508fa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7508f70 counterpartCT=4 counterpartW=96 counterparth=96
,E/File    ( 3569): fail readDirectory() errno=2
,W/ResourcesManager( 3802): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3802): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3802): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/Gmail   ( 3569): notifyAccountChanged
,W/SEAMService( 1014):  hashset_to_int_array returning null
D/F_PHONE ( 3833): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3833): default registerAction()
I/F_PHONE ( 3833): [[com.sec.bcservice]] sendPendingMessage()
,I/Gmail   ( 3569): getAccountsCursor
,W/SEAMService( 1014):  hashset_to_int_array returning null
,E/SQLiteLog( 3702): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3702): (284) automatic index on seams_container_info(sp_id)
,D/Volley  ( 3726): [571] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3726): [578] DiskBasedCache.clear: Cache cleared.
,W/ResourcesManager( 3802): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/Gmail   ( 3569): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/GFX construct_block_size_descriptor_2d second part( 3641): took 2.320573ms for 0*0 texture 0
,W/ResourcesManager( 3802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/SEAMService( 1014):  hashset_to_int_array returning null
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ResourcesManager( 3802): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
I/GFX generate_partition_tables( 3641): took 7.364792ms for 0*0 texture 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3641): took 10.626718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508f70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb750da60 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,I/AMMetaDataParserService( 3641): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,D/Finsky  ( 3726): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3726): [1] Libraries$2.run: Finished loading 1 libraries.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3802): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3802): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3802): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/Ads     ( 3726): Skipping gmscore version check
,I/Babel   ( 3768): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3768): MmsConfig.loadMmsSettings
,I/Babel   ( 3768): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 3768): MmsConfig.loadFromDatabase
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Babel   ( 3768): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3768): MmsConfig.loadFromResources
,E/Babel   ( 3768): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3768): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.622500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7512608 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7512760 counterpartCT=4 counterpartW=96 counterparth=96
,I/Gmail   ( 3569): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/AMMetaDataParserService( 3641): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.826980ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750f010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb750f168 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1014): Killing 3027:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3641): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/Gmail   ( 3569): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3569): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.626875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb75093f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb750daf0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3027/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Settings( 3768): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.807759ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b068 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb750b150 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/Finsky  ( 3726): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/Finsky  ( 3726): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/WearableService( 1866): callingUid 10012, callindPid: 1866
,E/GmsWearableNodeHelper( 1866): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.523698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb713a9b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c6a18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/Babel_StickerModule( 3768): App launched.
,I/Babel_StickerModule( 3768): Sticker update initiated. last:1456825783062 empty:false
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131034113
,I/AMMetaDataParserService( 3641): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.802604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74d4628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7448e80 counterpartCT=4 counterpartW=96 counterparth=96
,E/SMD     (  286): DCD OFF
,I/AMMetaDataParserService( 3641): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.970886ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74d4628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74f0f18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.776926ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74c6a18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7448e80 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3641): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,V/Babel   ( 3768): babel boot account: SMS
,W/Babel   ( 3768): EsDatabaseHelper.static should not be called on main thread [called on main thread]
,W/Babel   ( 3768): java.lang.Exception
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3768): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 3768): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3768): 	at ckh.a(SourceFile:67)
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3768): 	at bhn.a(SourceFile:301)
W/Babel   ( 3768): 	at bhn.a(SourceFile:137)
W/Babel   ( 3768): 	at bhn.a(SourceFile:126)
W/Babel   ( 3768): 	at bhn.a(SourceFile:159)
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3768): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3768): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3768): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3768): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3768): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3768): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/Babel   ( 3768): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3768): java.lang.Exception
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3768): 	at aes.a(SourceFile:145)
W/Babel   ( 3768): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3768): 	at ckh.a(SourceFile:67)
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3768): 	at bhn.a(SourceFile:301)
W/Babel   ( 3768): 	at bhn.a(SourceFile:137)
W/Babel   ( 3768): 	at bhn.a(SourceFile:126)
W/Babel   ( 3768): 	at bhn.a(SourceFile:159)
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3768): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3768): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3768): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3768): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3768): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3768): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 23695(1519KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.317ms total 175.613ms
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1014): Got CLOSE_WRITE Event sk.log
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.601614ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f0f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/FileApkUtils( 3518): Spent 106ms computing apk sha1.
,D/FileApkUtils( 3518): Module already staged or being staged:chimera-modules/MapsModule.apk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 3518): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.822969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7448e80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/DexOptUtils( 3518): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 3518): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 3518): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 3518): Primary ABI of odexing process is armeabi-v7a
,I/AMMetaDataParserService( 3641): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,V/Babel   ( 3768): babel boot account: thalitester@gmail.com
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.634062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb75093f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/Process ( 3802): Sending signal. PID: 3802 SIG: 9
,W/Babel   ( 3768): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,W/Babel   ( 3768): java.lang.Exception
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3768): 	at aes.a(SourceFile:145)
W/Babel   ( 3768): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3768): 	at ckh.a(SourceFile:67)
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3768): 	at bhn.a(SourceFile:301)
W/Babel   ( 3768): 	at bhn.a(SourceFile:137)
W/Babel   ( 3768): 	at bhn.a(SourceFile:126)
W/Babel   ( 3768): 	at bhn.a(SourceFile:159)
W/Babel   ( 3768): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3768): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3768): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3768): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3768): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3768): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3768): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3768): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3768): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3768): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3768): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/InstanceID/Rpc( 3518): Found 10012
,I/System.out( 3726): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 3726): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3726): (HTTPLog)-Static: isShipBuild true
I/System.out( 3726): (HTTPLog)-Thread-583-885762480: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3726): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.746720ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b068 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,I/dex2oat ( 3885): ----------------------------------------------------
I/dex2oat ( 3885): <SS>: S T A R T I N G . . .
I/dex2oat ( 3885): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3885): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk --oat-fd=38 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3759): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.525677ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb713a9b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/Zygote  ( 3893): MountEmulatedStorage()
,E/Zygote  ( 3893): v2,
I/libpersona( 3893): KNOX_SDCARD checking this for 1000
,I/libpersona( 3893): KNOX_SDCARD not a persona
,I/SELinux ( 3893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3893 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 3077:com.policydm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/ActivityManager( 1014): Process com.sec.android.app.sns3 (pid 3802)(adj 0) has died(156,1085)
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3641): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3641): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131034112
,I/SELinux ( 3893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/AMMetaDataParserService( 3641): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.611875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f0f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,E/SELinux ( 3893): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  281): getCameraInfo: X
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
W/ResourcesManager( 3759): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/QCamera2Factory(  281): getCameraInfo: X
W/ResourcesManager( 3759): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3759): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 3904): MountEmulatedStorage()
I/libpersona( 3904): KNOX_SDCARD checking this for 10034
E/Zygote  ( 3904): v2
I/libpersona( 3904): KNOX_SDCARD not a persona
I/SELinux ( 3904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 3904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
I/ActivityManager( 1014): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3904 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3893): TimaSignature is unavailable
,D/ActivityThread( 3893): Added TimaKeyStore provider
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3904): TimaSignature is unavailable
D/ActivityThread( 3904): Added TimaKeyStore provider
W/VideoCapabilities( 3768): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3768): Unsupported mime audio/evrc
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3077/cgroup.procs: No such file or directory
,W/AudioCapabilities( 3768): Unsupported mime audio/qcelp
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 3768): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3768): Unsupported mime audio/mpeg-L2
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.625260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f0f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0478 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3768): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3768): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3768): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3768): Unsupported mime audio/evrc
,I/AMMetaDataParserService( 3641): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/VideoCapabilities( 3768): Unsupported mime video/wvc1
,W/VideoCapabilities( 3768): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3768): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3768): Unsupported mime video/wvc1
,W/VideoCapabilities( 3768): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3768): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3768): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3768): Unsupported mime video/mp43
,I/art     ( 1643): Explicit concurrent mark sweep GC freed 3354(143KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 812us total 233.768ms
,W/VideoCapabilities( 3768): Unsupported mime video/sorenson
,W/SQLiteConnectionPool( 1643): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.641510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f0478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74efcb0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3768): Unsupported mime video/mp4v-esdp
,I/Gmail   ( 3569): getAccountsCursor
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3641): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.629114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb75093f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74d33b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/VideoCapabilities( 3768): Unsupported profile 4 for video/mp4v-es
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3927): MountEmulatedStorage(),
E/Zygote  ( 3927): v2
I/libpersona( 3927): KNOX_SDCARD checking this for 1000,
I/SELinux ( 3927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 3927): KNOX_SDCARD not a persona
,I/SELinux ( 3927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ChimeraCfgMgr( 3518): Reading stored module config
I/ActivityManager( 1014): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3927 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131034113
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3641): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3641): getResourceTypeNamexml
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.816406ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74d4628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb750e390 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3927): TimaSignature is unavailable
,D/ActivityThread( 3927): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3641): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/Zygote  ( 3946): MountEmulatedStorage()
I/libpersona( 3946): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3946): v2
I/libpersona( 3946): KNOX_SDCARD not a persona
I/SELinux ( 3946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 3042:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/SELinux ( 3946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 3946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3641): took 0.986875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74d4628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74fd460 counterpartCT=4 counterpartW=96 counterparth=96
,D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3641): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/TimaKeyStoreProvider( 3946): TimaSignature is unavailable
,D/ActivityThread( 3946): Added TimaKeyStore provider
,D/BootCompletedReceiver( 3518): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 3518): Got an BootCompleted event.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.738697ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74c6a18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74efcb0 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 3518): COMPAT: Multi user not supported
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,D/PowerManagerService( 1014): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1174 (0x0)
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3641): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/libprocessgroup( 1014): failed to open /acct/uid_10086/pid_3042/cgroup.procs: No such file or directory
,D/GCM     ( 1866): COMPAT: Multi user not supported
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,I/Babel   ( 3768): Creating RTCS
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BootCompletedReceiver( 3518): Will NOT schedule AdAttestation signal task because it's disabled.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.607135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f0f18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74d33b8 counterpartCT=4 counterpartW=96 counterparth=96,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,D/KnoxSetupWizardDbHelper( 3946): dbMigrationFlag : false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3641): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/GCoreUlr( 3518): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ShortcutReceiver( 3946):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!,
,I/DBG_POLICYDM( 3927): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED,
,I/DBG_POLICYDM( 3927): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0,
,I/DBG_POLICYDM( 3927): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 3927): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/CheckinService( 3518): Checkin interval check for package: unspecified last checkin: 1456600236354 min interval config: 0 actual interval: 826341067
,D/KnoxShortcutUtil( 3946): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3946):  KnoxContainerVersion 2.4.0
,D/ShortcutReceiver( 3946):  shortcut migration not required 
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/GFX raster( 3641): took 0.867552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7448e80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7511db8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3641): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/SQLiteLog( 3768): (284) automatic index on conversation_participants_view(conversation_id),
,E/Zygote  ( 3978): MountEmulatedStorage()
I/libpersona( 3978): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3978): v2
I/libpersona( 3978): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3978 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3131:com.dropbox.android/u0a92 (adj 15): empty #31
I/SELinux ( 3978): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3641): took 0.658906ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb75093f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7511db8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 3978): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 3978): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/art     (  307): Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 22.694ms
,I/DBG_POLICYDM( 3927): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3927): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,D/TimaKeyStoreProvider( 3978): TimaSignature is unavailable
D/ActivityThread( 3978): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3927): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 33.431ms
,D/SystemUpdateService( 3518): onCreate
,I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,E/SQLiteLog( 3768): (284) automatic index on conversation_participants_view(conversation_id)
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 25.160ms
,I/GFX raster( 3641): took 0.845988ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b068 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb713a5d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3768): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/ResourcesManager( 3768): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3768): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/KnoxSetupWizardClient( 3978): isShipMode : 1,
I/KnoxSetupWizardClient( 3978): onReceive : android.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3997): MountEmulatedStorage(),
I/libpersona( 3997): KNOX_SDCARD checking this for 10035
E/Zygote  ( 3997): v2
I/libpersona( 3997): KNOX_SDCARD not a persona
,I/SELinux ( 3997): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3997 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1014): Killing 3062:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/SELinux ( 3997): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 3997): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.529896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb713a9b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4014): MountEmulatedStorage(),
,D/TimaKeyStoreProvider( 3997): TimaSignature is unavailable
I/libpersona( 4014): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4014): v2
I/libpersona( 4014): KNOX_SDCARD not a persona
D/ActivityThread( 3997): Added TimaKeyStore provider
I/SELinux ( 4014): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4014): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4014): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3641): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/CheckinService( 3518): Disabling old GoogleServicesFramework version,
I/ActivityManager( 1014): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4014 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/ActivityManager( 1014): Killing 3196:com.fmm.dm/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/SystemUpdateService( 3518): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 3518): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 3518): Handling event: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/DBG_POLICYDM( 3927): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.Debug
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3641): Resource data:2131165203
,W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3131/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3196/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,W/ResourcesManager( 3641): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/JNIHelp ( 3768): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup( 1014): failed to open /acct/uid_10057/pid_3062/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3641): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 3927): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/TimaKeyStoreProvider( 4014): TimaSignature is unavailable
,D/ActivityThread( 4014): Added TimaKeyStore provider
,E/DBG_POLICYDM( 3927): [com.policydm.agent.XDMTask(173/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized,
,I/GFX construct_block_size_descriptor_2d second part( 3641): took 2.644010ms for 0*0 texture 0
,W/System.err( 3978): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3978): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3978): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3978): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 3978): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 3978): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3978): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/SQLiteLog( 3768): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3641): took 10.314478ms for 0*0 texture 0
,I/GFX raster( 3641): took 13.759374ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b388 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74ec420 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3768): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3641): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.
,I/SystemUpdateService( 3518): cancelUpdate (empty URL)
I/SystemUpdateService( 3518): active receiver: disabled
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 1.088905ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74dfaa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74dfb50 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 3997): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 3997): [PushClientApplication] Push log off : This is Ship build version
,I/AMMetaDataParserService( 3641): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/SPPClientService( 3997): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/ActivityThread( 3768): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3768): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3515f442: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3768): Installed default security provider GmsCore_OpenSSL
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.867342ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74dfaa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74d4628 counterpartCT=4 counterpartW=96 counterparth=96
,D/SPPClientService( 3997): PushLog.txt file is not deleted.
D/SPPClientService( 3997): PushLog.txt file is not deleted.
D/SPPClientService( 3997): ============PushLog. stop!
,I/AMMetaDataParserService( 3641): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/Babel   ( 3768): Destroying RTCS
,I/CheckinService( 3518): Checking schedule, now: 1457426578183 next: 1457139499243
,I/CheckinService( 3518): active receiver: enabled
,E/BaseAppContext( 3518): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4049): MountEmulatedStorage()
I/libpersona( 4049): KNOX_SDCARD checking this for 10041
E/Zygote  ( 4049): v2
I/libpersona( 4049): KNOX_SDCARD not a persona
,I/SELinux ( 4049): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 1.104011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74dfaa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb748f090 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1014): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4049 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SELinux ( 4049): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4049): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 3212:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/AMMetaDataParserService( 3641): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4049): TimaSignature is unavailable
,D/ActivityThread( 4049): Added TimaKeyStore provider
,I/AuthZen ( 3518): Fetching signing key...
,I/art     ( 3518): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 3518): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_10003/pid_3212/cgroup.procs: No such file or directory
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.591094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb75093f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c6a18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/AuthZen ( 3518): Signing key fetched successfully!
,D/SystemUpdateService( 3518): onDestroy
W/BaseAppContext( 3518): Using Auth Proxy for data requests.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/a       ( 3518): Opening database auth.proximity.permit_store...
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.598802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb75093f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0328 counterpartCT=4 counterpartW=96 counterparth=96
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10012
,D/GCM     ( 1866): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3641): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/AuthZenTransactionCache( 3518): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 3518): Clearing transaction cache
,I/art     ( 1643): Explicit concurrent mark sweep GC freed 3441(133KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 793us total 35.379ms
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/SA      ( 4049): [SSP] onCreated
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,W/ResourcesManager( 3641): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.672292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f8f80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/GCoreUlr( 1866): DispatchingService.onCreate()
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3641): took 2.598698ms for 0*0 texture 0
,D/SSRM:n  ( 1014): SIOP:: AP = 380
,I/GFX generate_partition_tables( 3641): took 8.776511ms for 0*0 texture 0
,I/GFX raster( 3641): took 12.388541ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f8a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74f8a78 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4049): [TPM] There is no property file
,W/art     ( 3676): Suspending all threads took: 22.339ms
,I/AMMetaDataParserService( 3641): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.616094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a059d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7a05a78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4049): [SCU] isHaveSA() - false
,I/SA      ( 4049): [TPM] getModelProperty : null
,I/SA      ( 4049): [TPM] getCSCProperty : null
,I/SA      ( 4049): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4049): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4049): [DM] TFT FEATURE: false
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.641510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a08b18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a08b50 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4049): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4049): [DM] init START
,I/AMMetaDataParserService( 3641): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/SA      ( 4049): [DM] This device is not a Vodafone
,W/ResourceType( 4049): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4049): No package identifier when getting value for resource number 0x00000000
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ResourceType( 4049): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
I/GFX raster( 3641): took 0.620052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0a0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a0a118 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourceType( 4049): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75),
W/ResourceType( 4049): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4049): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4049): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/GCoreUlr( 1866): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SA      ( 4049): [SCU] isHaveSA() - false
I/SA      ( 4049): support phone number id : false
I/SA      ( 4049): [DM] Supports Ref Jpn : true
,I/SA      ( 4049): [DM] init END
,I/SA      ( 4049): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4049): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/ActivityManager( 1014): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/art     ( 1866): Explicit concurrent mark sweep GC freed 20134(1409KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 11MB/19MB, paused 1.109ms total 86.216ms
,D/StrictMode( 4014): StrictMode policy violation; ~duration=756 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4014): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4014): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4014): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4014): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4014): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4014): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=749 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4014): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4014): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4014): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4014): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4014): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=632 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4014): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4014): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4014): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4014): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4014): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4014): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=631 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4014): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4014): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4014): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrume,ntation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=630 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4014): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4014): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4014): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4014): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=628 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4014): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4014): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4014): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4014): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4014): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4014): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4014): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4014): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4014): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4014): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4014): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4014): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=626 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4014): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4014): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4014): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4014): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4014): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4014): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4014): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4014): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4014): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4014): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4014): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4014): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4014): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4014): StrictMode policy violation; ~duration=557 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4014): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4014): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4014): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4014): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4014): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4014): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/StrictMode( 4014): StrictMode policy violation; ~duration=557 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4014): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4014): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4014): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4014): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4014): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4014): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4014): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4014): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4014): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4014): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4014): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4014): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4014): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4014): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/System.out( 3676): INFO:Resource not found:/Common.properties Using default values
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SA      ( 4049): [OR] onReceive END
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SA      ( 4049): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4049): [ODM] queryOpenData(key= GEO_IP )
,I/SA      ( 4049): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4049): [LBE] REF_JPN : true
E/Zygote  ( 4085): MountEmulatedStorage()
I/libpersona( 4085): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4085): v2
I/libpersona( 4085): KNOX_SDCARD not a persona
I/SELinux ( 4085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 3237:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
D/ActivityManager( 1014): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/SA      ( 4049): [BDC] create
I/SELinux ( 4085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SELinux ( 4085): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4085): TimaSignature is unavailable
,D/ActivityThread( 4085): Added TimaKeyStore provider
,E/Zygote  ( 4101): MountEmulatedStorage()
E/Zygote  ( 4101): v2
I/libpersona( 4101): KNOX_SDCARD checking this for 10042
I/libpersona( 4101): KNOX_SDCARD not a persona
,I/SELinux ( 4101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3641): took 0.778542ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0b698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a0b6d0 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 4101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4101 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4101): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 4049): [DBMV2] getEmailID
,I/SA      ( 4049): [DBMV2] getDataV02ForItems
,I/SA      ( 4049): [SSP] query invoked
,I/SA      ( 4049): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3641): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4101): TimaSignature is unavailable
I/SA      ( 4049): [SCU] get signed id from samsung account1.0 DB.
,D/ActivityThread( 4101): Added TimaKeyStore provider
,I/SA      ( 4049): [BDC] destroy
,I/ActivityManager( 1014): Killing 3259:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,I/AMMetaDataParserService( 3641): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.684687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7136620 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4101): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/StatusChecker( 4085): onReceive : android.intent.action.BOOT_COMPLETED
,W/com.google.a.a.b.d.a( 4014): Application name is not set. Call Builder#setApplicationName.
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/StatusChecker( 4085): onReceive : net.mt.init : DONE,
I/ActivityManager( 1014): Killing 3288:com.fmm.ds/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4124): MountEmulatedStorage()
I/libpersona( 4124): KNOX_SDCARD checking this for 10116
E/Zygote  ( 4124): v2
I/libpersona( 4124): KNOX_SDCARD not a persona
I/SELinux ( 4124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4124): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4124 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3307:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10092/pid_3237/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10060/pid_3259/cgroup.procs: No such file or directory
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.662864ms for 96*96 texture 0
,E/SQLiteLog( 3518): (10) POSIX Error : 11 SQLite Error : 3850
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb74f8a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7136620 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4124): TimaSignature is unavailable
,D/ActivityThread( 4124): Added TimaKeyStore provider
,W/Auth    ( 1866): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.815938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a059d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7136620 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 4101): CalendarProvider2.onCreate() called
,I/PageBuddyNotiSvc( 4124): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3288/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10062/pid_3307/cgroup.procs: No such file or directory
,I/GCoreUlr( 1866): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ContextImpl( 4124): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4124): onCreate mCpBitFlag=0,
,E/Zygote  ( 4142): MountEmulatedStorage()
,E/Zygote  ( 4142): v2
I/libpersona( 4142): KNOX_SDCARD checking this for 10125
I/libpersona( 4142): KNOX_SDCARD not a persona
I/SELinux ( 4142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4142 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SMD     (  286): DCD OFF
E/SELinux ( 4142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3641): took 0.730104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a08b18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7136620 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4142): TimaSignature is unavailable
,I/GCoreUlr( 1866): Unbound from all location providers
I/GCoreUlr( 1866): Place inference reporting - stopped
,D/ActivityThread( 4142): Added TimaKeyStore provider
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.670207ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0a0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7136620 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/PersistentNotificationBroadcastReceiver( 1866): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/ResourcesManager( 4142): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4142): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4142): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QuickConnect( 4142): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 32440(1911KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 26MB/39MB, paused 2.274ms total 170.320ms
,D/QuickConnect( 4142): Util.setSCRunningSetting - [value]0
,D/SettingsProvider( 1014): name = scon_is_running
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10125
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1014): ret = -1
,W/BackupManagerService( 1014): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 4142): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/GCoreUlr( 1866): DispatchingService.onDestroy()
I/GCoreUlr( 1866): Stopping handler for UlrDispSvcFast
,I/QuickConnect( 4142): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/Zygote  ( 4163): MountEmulatedStorage()
E/Zygote  ( 4163): v2
I/libpersona( 4163): KNOX_SDCARD checking this for 10131
I/libpersona( 4163): KNOX_SDCARD not a persona
,I/SELinux ( 4163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 1866): Unbound from all location providers
I/ActivityManager( 1014): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4163 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
I/GCoreUlr( 1866): Place inference reporting - stopped
,W/GCoreFlp( 1866): No location to return for getLastLocation()
W/FusedLocationProvider( 1866): location=null
,I/ActivityManager( 1014): Killing 3335:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,W/GCoreFlp( 1866): No location to return for getLastLocation()
,W/FusedLocationProvider( 1866): location=null
,D/TimaKeyStoreProvider( 4163): TimaSignature is unavailable
,D/ActivityThread( 4163): Added TimaKeyStore provider
,W/ResourcesManager( 4163): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4163): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4163): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4163): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3335/cgroup.procs: No such file or directory
,D/SensorService( 1014): [SO] 0.153 0.383 10.113
,W/dex2oat ( 3885): Verification of void com.google.maps.api.android.lib6.gmm6.m.cv.f() took 125.531ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3641): took 0.737396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0b3b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7a0a1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1014): Killing 3105:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/SBrowserFeatureFlag( 4163): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3641): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/ActivityManager( 1014): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/dex2oat ( 3885): Verification of void com.google.maps.api.android.lib6.gmm6.m.cj.g() took 113.773ms
,W/dex2oat ( 3885): Verification of void com.google.maps.api.android.lib6.gmm6.m.l.a(javax.microedition.khronos.opengles.GL10) took 140.268ms
,D/ManifestProvider( 4163): onCreate()
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,E/NetworkSettingsReceiver( 4163): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity,
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,I/AMMetaDataParserService( 3641): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.709114ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb76c14a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7508ca8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/SBrowserFeatureFlag( 4163): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@229bc881
,I/GAV2    ( 3569): Thread[GAThread,5,main]: No campaign data found.
,W/libprocessgroup( 1014): failed to open /acct/uid_10009/pid_3105/cgroup.procs: No such file or directory
,D/SBrowserFeatureFlag( 4163): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4163): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/GAv4-SVC( 3518): Google Analytics 8.4.89 is starting up.
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.624948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7503560 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3641): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4190): MountEmulatedStorage()
I/libpersona( 4190): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4190): v2
I/libpersona( 4190): KNOX_SDCARD not a persona
I/GFX raster( 3641): took 0.638750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74f0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4190 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4190): TimaSignature is unavailable
,D/ActivityThread( 4190): Added TimaKeyStore provider
,V/AlarmManager( 1014): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,W/ResourcesManager( 4190): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4190): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4190): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/accuweather( 1744): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.636198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b680 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a0a1a0 counterpartCT=4 counterpartW=96 counterparth=96
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1744): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1744): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1744): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,I/AMMetaDataParserService( 3641): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/accuweather( 1744): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 09 43
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.627656ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0a0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/dex2oat ( 3885): dex2oat took 3.454s (threads: 4)
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.717292ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0b3b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74b5e90 counterpartCT=4 counterpartW=96 counterparth=96
,D/DexOptUtils( 3518): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.dex
,D/DexOptUtils( 3518): Set odex to world readable.
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DexOptUtils( 3518): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/arm/MapsModule.odex
,D/FileApkUtils( 3518): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,I/AMMetaDataParserService( 3641): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/GmsModuleFndr( 3518): Beginning GMS chimera module scan
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,D/ActivityManager( 1014): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
I/AMMetaDataParserService( 3641): getResourceName:com.android.mms:xml/assistant_messaging
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.689010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb76c14a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SecDataIO(  255): Write to block
,D/GmsModuleFndr( 3518): Module pkg com.google.android.apps.kids.familylink not installed, skipping
D/ChimeraCfgMgr( 3518): Beginning module configuration check
,E/Zygote  ( 4214): MountEmulatedStorage()
,E/Zygote  ( 4214): v2
I/libpersona( 4214): KNOX_SDCARD checking this for 10139
I/libpersona( 4214): KNOX_SDCARD not a persona
D/ChimeraCfgMgr( 3518): Module APKs unchanged, check complete
,I/SELinux ( 4214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4214 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/SELinux ( 4214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl( 2593): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/ActivityManager( 1014): Killing 3353:com.wssnps/1000 (adj 15): empty #31
,I/DBG_DM  ( 2977): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,D/TimaKeyStoreProvider( 4214): TimaSignature is unavailable
,D/ActivityThread( 4214): Added TimaKeyStore provider
,I/DBG_DM  ( 2977): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 2977): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/Process ( 2593): Sending signal. PID: 2593 SIG: 9
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.662916ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7503560 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74f0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,I/AMMetaDataParserService( 3641): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.636302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb750b620 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4214): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4214): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4214): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4214): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4214): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Process com.sec.android.app.sysscope (pid 2593)(adj 0) has died(125,1112)
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.648437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b680 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74dfb18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/ActivityManager( 1014): Killing 3369:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3641): took 0.627031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0a0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3353/cgroup.procs: No such file or directory,
,E/Zygote  ( 4234): MountEmulatedStorage()
,I/libpersona( 4234): KNOX_SDCARD checking this for 10145
,E/Zygote  ( 4234): v2,
I/libpersona( 4234): KNOX_SDCARD not a persona,
I/SELinux ( 4234): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4234): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4234): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4234 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10094/pid_3369/cgroup.procs: No such file or directory
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.847656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0b3b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb713a5b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4234): TimaSignature is unavailable
,D/ActivityThread( 4234): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 44.931ms
,I/AMMetaDataParserService( 3641): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/ActivityManager( 1014): Killing 3404:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,I/AMMetaDataParserService( 3641): getResourceName:com.android.mms:xml/assistant_messaging
W/ResourcesManager( 4234): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
W/ResourcesManager( 4234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ResourcesManager( 4234): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/GFX raster( 3641): took 0.706459ms for 96*96 texture 0
W/ResourcesManager( 4234): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb76c14a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7511db8 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 4234): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.939ms
I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.836ms
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.629636ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7503560 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7a0a1a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.699010ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7185e08 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.677447ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b680 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74b5e90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/libprocessgroup( 1014): failed to open /acct/uid_10014/pid_3404/cgroup.procs: No such file or directory
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.786562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0a0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb713a9b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.793646ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0b3b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,I/AMMetaDataParserService( 3641): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3641): getResourceTypeNamexml
E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.678333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb76c14a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 2977): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.704323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7503560 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74f0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,E/DBG_DM  ( 2977): [IlIIlIIlIllllIlllIII(226/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
I/AMMetaDataParserService( 3641): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/DBG_DM  ( 2977): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.example.hello.MainActivity
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.636613ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7508ca8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.727188ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb750b680 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74f0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3641): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.622291ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0a0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0580 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.908750ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7a0b3b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74f0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$Servi,ceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity,
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131165197
,W/ResourcesManager( 3641): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,I/AMMetaDataParserService( 3641): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3641): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,E/Zygote  ( 4256): MountEmulatedStorage()
I/libpersona( 4256): KNOX_SDCARD checking this for 10072
E/Zygote  ( 4256): v2
I/libpersona( 4256): KNOX_SDCARD not a persona
,I/SELinux ( 4256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4256): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3641): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622,
,I/ActivityManager( 1014): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4256 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/CalendarProvider2( 4101): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1014): Killing 3441:com.sec.factory.camera/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4256): TimaSignature is unavailable
,D/ActivityThread( 4256): Added TimaKeyStore provider
I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131165197
,I/AMMetaDataParserService( 3641): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3641): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/BadgeProvider( 4256): onCreate
,D/BadgeProvider( 4256): DatabaseHelper
,D/ActivityManager( 1014): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3441/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3641): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/BadgeProvider( 4256): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 3641): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/BadgeProvider( 4256): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4256): sendNotify, [notify] : null
D/BadgeProvider( 4256): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4256): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4256): update, [UpdateCount] : 1
,D/Launcher.Model( 1466): reloadBadges entered.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4278): MountEmulatedStorage()
,E/Zygote  ( 4278): v2
I/libpersona( 4278): KNOX_SDCARD checking this for 10146
I/libpersona( 4278): KNOX_SDCARD not a persona
,I/SELinux ( 4278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/ActivityManager( 1014): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4278 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4278): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Killing 3388:com.samsung.android.sm/1000 (adj 15): empty #31
,I/ActivityManager( 1014): Killing 3487:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/TimaKeyStoreProvider( 4278): TimaSignature is unavailable
,D/ActivityThread( 4278): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131165197
,I/AMMetaDataParserService( 3641): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,W/ResourcesManager( 4278): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3641): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/RCPManagerService( 1014): exchangeData() failure , invalid userId
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/AMMetaDataParserService( 3641): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/Process ( 4234): Sending signal. PID: 4234 SIG: 9
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3388/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3487/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3641): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/ActivityManager( 1014): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android,.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,E/Zygote  ( 4294): MountEmulatedStorage()
,E/Zygote  ( 4294): v2
I/libpersona( 4294): KNOX_SDCARD checking this for 1000
I/libpersona( 4294): KNOX_SDCARD not a persona
,I/SELinux ( 4294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4294 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131099648
,I/ActivityManager( 1014): Killing 3502:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/ResourcesManager( 3641): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,E/JavaBinder( 4278): !!! FAILED BINDER TRANSACTION !!!
,I/AMMetaDataParserService( 3641): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ActivityManager( 1014): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/TimaKeyStoreProvider( 4294): TimaSignature is unavailable
,D/ActivityThread( 4294): Added TimaKeyStore provider
,I/Process ( 4278): Sending signal. PID: 4278 SIG: 9
,I/ActivityManager( 1014): Process com.android.email (pid 4234)(adj 9) has died(115,1126)
,I/AMMetaDataParserService( 3641): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4311): MountEmulatedStorage()
,E/Zygote  ( 4311): v2
,I/libpersona( 4311): KNOX_SDCARD checking this for 1000
I/libpersona( 4311): KNOX_SDCARD not a persona
,I/SELinux ( 4311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4311 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4311): TimaSignature is unavailable
,D/ActivityThread( 4311): Added TimaKeyStore provider
,I/ActivityManager( 1014): Process com.android.exchange (pid 4278)(adj 9) has died(115,1126)
,W/libprocessgroup( 1014): failed to open /acct/uid_10100/pid_3502/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 4311): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4311): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4311): StateMachine : Current State = 1
D/SecurityLogAgent( 4311): BootReceiver : completed task. Failed to return wakelock . 
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:assistant
I/AMMetaDataParserService( 3641): Resource data:2131165220
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3641): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3641): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3641): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3641): getResourceTypeNamexml
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.699687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7c0bfb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c0bce0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3641): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3641): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3641): took 0.594480ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3641): Bitmap=0xb7c0be00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c1f0c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3641): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1866): [220] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity,
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$Vpn,SettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DisplaySettings
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity,
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.MediaFormat
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.UsbSettings
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.andro,id.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity,
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.MagazineCard
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
W/ActivityManager( 1014): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
,I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3641): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3641): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
,I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3641): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/LocationInitializer( 3518): Restart initialization of location
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1443): query,matched:0, calling pid = 3518
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/TP/SmsProvider( 1443): match 0:Elapsed time : 1.525 ms
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1443): Query uri=content://mms, match=0, calling pid = 3518
,D/TP/SmsProvider( 1443): query,matched:0, calling pid = 3518
,D/TP/SmsProvider( 1443): match 0:Elapsed time : 1.069 ms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsProvider( 1443): Query uri=content://mms, match=0, calling pid = 3518
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1014): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1014): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1014): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1014): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1014): Plugged
,I/MotionRecognitionService( 1014): mGripSensorEnabled= false
,W/IcingInternalCorpora( 3518): getNumBytesRead when not calculated.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1406): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1406): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1866): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1866): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1014): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1014): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1014): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/GCoreFlp( 1866): No location to return for getLastLocation()
,W/FusedLocationProvider( 1866): location=null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 3518): Restart initialization of location
,E/MDM     ( 1866): [235] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1866): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/HomeSyncInstallReceiver( 1429): This pkg do not need BT addr. Do nothing
,I/splitIntent( 1014): Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=14, mSplitNum[1]=23, mSplitNum[2]=36, mBgSplitQueueNum=3 divideNum= 11 r.nextReceiver= 2 receivers.size=47
,I/splitIntent( 1014): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,W/GCoreFlp( 1866): No location to return for getLastLocation()
,W/FusedLocationProvider( 1866): location=null
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4355): MountEmulatedStorage()
I/libpersona( 4355): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4355): v2
I/libpersona( 4355): KNOX_SDCARD not a persona
I/SELinux ( 4355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=4355 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/SELinux ( 4355): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4367): MountEmulatedStorage()
,E/Zygote  ( 4367): v2
I/libpersona( 4367): KNOX_SDCARD checking this for 10044
I/libpersona( 4367): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=4367 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 4367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
I/SELinux ( 4367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4355): TimaSignature is unavailable,
D/ActivityThread( 4355): Added TimaKeyStore provider
,I/ActivityManager( 1014): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=4378 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4378): MountEmulatedStorage()
I/libpersona( 4378): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4378): v2
I/libpersona( 4378): KNOX_SDCARD not a persona
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
I/SELinux ( 4378): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 4378): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4378): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4367): TimaSignature is unavailable
,D/ActivityThread( 4367): Added TimaKeyStore provider
,E/Zygote  ( 4396): MountEmulatedStorage()
E/Zygote  ( 4396): v2
I/libpersona( 4396): KNOX_SDCARD checking this for 10152
I/libpersona( 4396): KNOX_SDCARD not a persona
,I/SELinux ( 4396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4378): TimaSignature is unavailable
I/ActivityManager( 1014): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4396 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,D/ActivityThread( 4378): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4396): TimaSignature is unavailable
,D/ActivityThread( 4396): Added TimaKeyStore provider
W/ResourcesManager( 4367): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4367): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4367): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4367): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4367): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4367): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4367): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4367): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Killing 3153:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/AASAservice-UpdateReceiver( 4355): AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.example.hello, uid = -1
I/AASAservice-TokenRule( 4355): parseToken()
W/System.err( 4355): java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
W/System.err( 4355): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 4355): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 4355): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 4355): 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:80)
W/System.err( 4355): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:52)
W/System.err( 4355): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4355): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4355): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4355): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4355): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4355): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4355): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4355): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4355): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/System.err( 4355): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 4355): 	at libcore.io.Posix.open(Native Method)
W/System.err( 4355): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 4355): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 4355): 	... 14 more
E/AASAservice-TokenRule( 4355): parseToken() : TokenFile is null
,E/AASAservice-UpdateReceiver( 4355): AASARuleUpdateResult() : Rule file is not exist.
,I/ActivityManager( 1014): Killing 3554:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
W/ResourcesManager( 4378): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 4396): (284) automatic index on shooting_modes(title_id)
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4415): MountEmulatedStorage(),
E/Zygote  ( 4415): v2,
I/libpersona( 4415): KNOX_SDCARD checking this for 10156
,I/libpersona( 4415): KNOX_SDCARD not a persona
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=4415 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 3586:com.android.managedprovisioning/u0a22 (adj 15): empty #31
I/SELinux ( 4415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4415): TimaSignature is unavailable
,D/ActivityThread( 4415): Added TimaKeyStore provider
,E/Zygote  ( 4433): MountEmulatedStorage()
E/Zygote  ( 4433): v2
I/libpersona( 4433): KNOX_SDCARD checking this for 10015
I/libpersona( 4433): KNOX_SDCARD not a persona
I/SELinux ( 4433): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.AppInstalledReceiver: pid=4433 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 4433): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4433): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 3641): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/TimaKeyStoreProvider( 4433): TimaSignature is unavailable
,D/ActivityThread( 4433): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/TapandpayWidget:TapandpayAppWidgetProvider( 4415): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 4415): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils( 4415): Clear T&P info.
,W/libprocessgroup( 1014): failed to open /acct/uid_10069/pid_3554/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10015/pid_3153/cgroup.procs: No such file or directory
,D/TapandpayWidget:TapandpayAppWidgetProvider( 4415): Widget is not attached.
,E/Zygote  ( 4452): MountEmulatedStorage(),
E/Zygote  ( 4452): v2
I/libpersona( 4452): KNOX_SDCARD checking this for 1000,
I/SELinux ( 4452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4452): KNOX_SDCARD not a persona,
,I/SELinux ( 4452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=4452 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,W/libprocessgroup( 1014): failed to open /acct/uid_10022/pid_3586/cgroup.procs: No such file or directory
,I/art     (  307): Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 22.956ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 4452): TimaSignature is unavailable
,D/ActivityThread( 4452): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 17.408ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.801ms
,I/PCWCLIENTTRACE_PushUtil( 3227): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3227): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3227): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3227): [onReceive] - android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
W/ResourcesManager( 4452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/NearbySource( 4367): Nearby Source Create!
,D/NearbyContext( 4367): Nearby Context Create!
,E/Zygote  ( 4469): MountEmulatedStorage()
,E/Zygote  ( 4469): v2
,I/libpersona( 4469): KNOX_SDCARD checking this for 10032
I/libpersona( 4469): KNOX_SDCARD not a persona,
I/SELinux ( 4469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=4469 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3610:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,I/SELinux ( 4469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 28590(1716KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.525ms total 163.323ms
,I/ActivityManager( 1014): Killing 3178:com.google.android.youtube/u0a166 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/,
D/Finsky  ( 3726): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4367): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache,
,D/SLinkSource( 4367): Samsung link source created
,E/Zygote  ( 4486): MountEmulatedStorage(),
I/ActivityManager( 1014): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4486 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 4486): v2
,D/TimaKeyStoreProvider( 4469): TimaSignature is unavailable
I/ActivityManager( 1014): Killing 3569:com.google.android.gm/u0a101 (adj 15): empty #31
D/ActivityThread( 4469): Added TimaKeyStore provider
,I/libpersona( 4486): KNOX_SDCARD checking this for 10091
I/libpersona( 4486): KNOX_SDCARD not a persona
,I/SELinux ( 4486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4486): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4501): MountEmulatedStorage()
E/Zygote  ( 4501): v2
I/libpersona( 4501): KNOX_SDCARD checking this for 10010
I/libpersona( 4501): KNOX_SDCARD not a persona
,I/SELinux ( 4501): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/TimaKeyStoreProvider( 4486): TimaSignature is unavailable
,D/ActivityThread( 4486): Added TimaKeyStore provider
,I/ActivityManager( 1014): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=4501 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4501): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4501): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4501): TimaSignature is unavailable
,D/ActivityThread( 4501): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10166/pid_3178/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3610/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10101/pid_3569/cgroup.procs: No such file or directory
,D/ContactProvider( 4367): getAllContactInfoList Start
,I/FeatureConfig( 4469): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_POLICYDM( 3927): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.example.hello
,D/WifiDisplayAdapter( 1014): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/PackagesMonitor( 4367): PackagesMonitor onReceive :com.example.hello
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/SMD     (  286): DCD OFF
,E/Zygote  ( 4520): MountEmulatedStorage()
I/libpersona( 4520): KNOX_SDCARD checking this for 10038
E/Zygote  ( 4520): v2
I/libpersona( 4520): KNOX_SDCARD not a persona
I/SELinux ( 4520): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ResourcesManager( 4469): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SELinux ( 4520): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/ActivityManager( 1014): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=4520 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 4520): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 3676:com.vlingo.midas/u0a31 (adj 15): empty #31
,W/ResourcesManager( 4469): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4520): TimaSignature is unavailable
,D/ActivityThread( 4520): Added TimaKeyStore provider
,D/ContactProvider( 4367): getAllContactInfoList End
,I/syncContacts( 4367): thread: 698, sync time = 89
,W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4520): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4520): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4469): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4535): MountEmulatedStorage(),
I/libpersona( 4535): KNOX_SDCARD checking this for 10046
E/Zygote  ( 4535): v2
I/libpersona( 4535): KNOX_SDCARD not a persona
I/SELinux ( 4535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,W/ResourcesManager( 4469): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 4469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SELinux ( 4535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4535): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4469): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 1014): Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=4535 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3759:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,W/libprocessgroup( 1014): failed to open /acct/uid_10031/pid_3676/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4535): TimaSignature is unavailable
,D/ActivityThread( 4535): Added TimaKeyStore provider
,W/ResourcesManager( 4469): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4469): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4469): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4535): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4535): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 4535): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4535): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4535): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4535): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_3759/cgroup.procs: No such file or directory
,W/GalaxyFinderApplication( 4469): system/finder_cp/cpdata.xml file not found
,D/Mms/MmsApp( 4535): [start]    onCreate() consume time = 0.0
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4551): MountEmulatedStorage(),
I/libpersona( 4551): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4551): v2,
I/libpersona( 4551): KNOX_SDCARD not a persona
I/SELinux ( 4551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1014): Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=4551 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 4551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Killing 3893:com.samsung.helphub/1000 (adj 15): empty #31
,D/PowerManagerService( 1014): [s] UserActivityState : 1 -> 2,
D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1014): [s] DisplayPowerCallbacks : onStateChanged()
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1014): lcd : 41 +
,D/PackageBroadcastService( 3518): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3518): Loading module APK com.google.android.play.games
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1014): lcd : 41 -
D/lights  ( 1014): lcd : 19 +
,D/TimaKeyStoreProvider( 4551): TimaSignature is unavailable
,D/ActivityThread( 4551): Added TimaKeyStore provider
,D/lights  ( 1014): lcd : 19 -
,D/DisplayPowerController( 1014): getFinalBrightness : Summary is 19 -> 19
D/DisplayPowerController( 1014): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/art     ( 4535): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 132.004ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3893/cgroup.procs: No such file or directory
,D/Mms/ArtClassLoader( 4535): init before art
,D/Mms/TelephonyPermission( 4535): start operation mode monitor
,W/ResourcesManager( 4535): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4535): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4535): isDefault true
,D/Mms/MmsApp( 4535): onCreate() com.android.mms
,D/Mms/MmsApp( 4535): [start]    initCountryIso consume time = 357.000833
,D/CountryDetector( 1014): The first listener is added
,D/Mms/MmsApp( 4535): [end]    initCountryIso consume time = 8.260365
,D/Mms/MmsConfig( 4535): [start]    MmsConfig.init() consume time = 0.689166
,I/SL_DEBUG( 4520): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 4520): isLoggable:: SL_DEBUG_EXIST = false
,D/Mms/MmsConfig( 4535): before partial update
,E/PhotosPlugin( 4486): Loading PhotosPlugin
,D/Mms/MmsConfig( 4535): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4535): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4535): isAuth is false
,D/Mms/MmsConfig( 4535): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1443): query,matched:2117, calling pid = 4535
,D/TP/MmsSmsProvider( 1443): match 2117:Elapsed time : 1.789 ms
,D/EasySignUpManager_1.0.1( 4535): isAuth is false
D/EasySignUpManager_1.0.1( 4535): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4535): mps_code.dat does not exist
E/CscParser( 4535): customer_path =/system/csc/customer.xml
E/CscParser( 4535): fileName + /system/csc/customer.xml
,E/CscParser( 4535): mps_code.dat does not exist
E/CscParser( 4535): customer_path =/system/csc/customer.xml
E/CscParser( 4535): fileName + /system/csc/customer.xml
,D/CscParser( 4535): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4535):  enable multiwindow = true
,E/Mms/MessageUtils( 4535): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4535): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4535): [end]    init() consume time = 159.94599
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/Contact( 4535): [start]    init() consume time = 9.543906
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4520): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/TP/MmsSmsProvider( 1443): query,matched:13, calling pid = 4535
,D/TP/MmsSmsProvider( 1443): match 13:Elapsed time : 1.856 ms
,D/Mms/Contact( 4535): [end]    init consume time = 23.657604
,D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3518): Module APK com.google.android.play.games already loaded
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/Mms/DraftCache( 4535): [start]    rebuildCache consume time = 19.147084
,D/TP/MmsSmsProvider( 1443): query,matched:12, calling pid = 4535
,D/TP/MmsSmsProvider( 1443): match 12:Elapsed time : 1.948 ms
D/Mms/MethodReflector( 4535): getSubId is called
D/Mms/TelephonyUtils( 4535): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4535): getTelephonyProperty is called
D/Mms/DraftCache( 4535): [end]    rebuildCache consume time = 11.33276
,D/Mms/DownloadManager( 4535): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4535): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4535): auto download without roaming -> true
D/Mms/DownloadManager( 4535): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 4535): getSubId is called
,D/Mms/MethodReflector( 4535): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4535): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4535): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 4535): getTelephonyProperty is called
D/Mms/DownloadManager( 4535): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4535): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4535): auto download without roaming -> true
D/Mms/DownloadManager( 4535): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4535): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4535): mAutoDownload ------> true
,I/Icing   ( 3518): Storage manager: low false usage 1.72MB avail 10.18GB capacity 11.68GB
,D/ComposerPerformance( 4535): 1457426583175 ms / [DONE] Composer constructor
,E/CII     ( 4535): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4535): ReservationManager()
,I/Mms/ReservationManager( 4535): resetAfterConnected()
,D/TP/MmsSmsProvider( 1443): query,matched:7, calling pid = 4535
,D/TP/MmsSmsProvider( 1443): match 7:Elapsed time : 6.466 ms
,D/Mms/Conversation( 4535): [start]    init() consume time = 61.705469
,D/TP/MmsSmsProvider( 1443): deleteConversation threadId: 9223372036854775807
,I/Mms/ReservationManager( 4535): getReservedSendMessageCount(): retMessageCount=0
,D/TP/MmsSmsProvider( 1443): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1443): updateThread(), thread_id = 9223372036854775807
,D/Mms/MmsApp( 4535): [end]    onCreate() consume time = 6.808489
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.
,V/TP/MmsSmsDatabaseHelper( 1443): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1443): (284) automatic index on im_threads(normal_thread_id)
,D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TP/MmsSmsProvider( 1443): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1443): need read changed broadcast:false
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,D/AsyncTaskServiceImpl( 3518): Submit a task: k
,W/ContextImpl( 4520): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,D/Mms/Conversation( 4535): [end]    init consume time = 31.159271
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Mms/MessagingNotification( 4535): [start]    init() consume time = 5.669948
,D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/Mms/MessagingNotification( 4535): [end]    init consume time = 18.922709
,D/Mms/SpamFilter( 4535): [start]    SpamFilter fill() begin consume time = 3.952708
,D/TP/MmsSmsProvider( 1443): query,matched:0, calling pid = 4535
V/TP/MmsSmsProvider( 1443): getSimpleConversations entered.
D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/TP/MmsSmsProvider( 1443): match 0:Elapsed time : 1.928 ms
,D/k       ( 3518): Processing package: com.example.hello
,D/TP/MmsSmsProvider( 1443): query,matched:400, calling pid = 4535
,D/Mms/Synchronizer( 4535): [start]    doSync consume time = 10.406562
,D/Mms/SpamFilter( 4535): [end]    SpamFilter fill() finished consume time = 5.431823
,D/TP/MmsSmsProvider( 1443): update, matched:300, calling pid = 4535
V/TP/MmsSmsProvider( 1443): syncDBData start
,V/TP/MmsSmsProvider( 1443): syncDBData sms end
D/Mms/ArtClassLoader( 4535): init [DONE] art
,V/TP/MmsSmsProvider( 1443): syncDBData mms end
,V/TP/MmsSmsProvider( 1443): syncDBData end
,D/Mms/Synchronizer( 4535): [end]    doSync consume time = 8.817084
,D/Mms/DownloadManager( 4535): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4535): roaming ------> false, mSimSlot = 0
,D/Mms/MethodReflector( 4535): getSubId is called
,D/Mms/TelephonyUtils( 4535): getLongSubId from simSlot 0, return Value = -1
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.
D/Mms/MethodReflector( 4535): getTelephonyProperty is called
D/Mms/MessagingNotification( 4535): checkBadgeCount unreadCount=0 badgeCount=0
D/Mms/DownloadManager( 4535): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4535): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4535): auto download without roaming -> true
D/Mms/DownloadManager( 4535): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4535): mAutoDownload ------> true
,D/Mms/FreeMessageStatusReceiver( 4535): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/TP/SmsProvider( 1443): query,matched:26, calling pid = 4535
,D/GassUtils( 3518): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/ActivityManager( 1014): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/TP/SmsProvider( 1443): match 26:Elapsed time : 1.464 ms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/k       ( 3518): Found info for package com.example.hello in db.
,D/ActivityManager( 1014): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4611): MountEmulatedStorage()
I/libpersona( 4611): KNOX_SDCARD checking this for 10047
E/Zygote  ( 4611): v2
I/libpersona( 4611): KNOX_SDCARD not a persona
D/Mms/FreeMessageReceiverService( 4535): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 4535): onHandleIntent: ACTION_PACKAGE_ADDED
,I/SELinux ( 4611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=4611 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a,
,I/SELinux ( 4611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4611): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/TP/MmsSmsProvider( 1443): query,matched:6, calling pid = 4535
,D/TP/MmsSmsProvider( 1443): match 6:Elapsed time : 1.600 ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.,
W/BaseAppContext( 3518): Using Auth Proxy for data requests.
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4611): TimaSignature is unavailable
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityThread( 4611): Added TimaKeyStore provider
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1014): Killing 3904:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 4611): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4611): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4611): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 4633): MountEmulatedStorage()
I/libpersona( 4633): KNOX_SDCARD checking this for 10025
E/Zygote  ( 4633): v2
I/libpersona( 4633): KNOX_SDCARD not a persona
,I/SELinux ( 4633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,W/BaseAppContext( 3518): Using Auth Proxy for data requests.,
I/SELinux ( 4633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1014): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4633 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4633): TimaSignature is unavailable
,D/ActivityThread( 4633): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10034/pid_3904/cgroup.procs: No such file or directory
,W/ResourcesManager( 4633): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/SA      ( 4049): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4049): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4049): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10174 extra.user_handle.:0 ]
,I/PeopleDatabaseHelper( 3518): cleanUpNonGplusAccounts done.
,I/ActivityManager( 1014): Killing 3946:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/OMACP   ( 4633): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 4535): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/MyFiles ( 4611): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false,
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369,
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false,
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false,
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false,
,E/Zygote  ( 4649): MountEmulatedStorage(),
E/Zygote  ( 4649): v2
I/libpersona( 4649): KNOX_SDCARD checking this for 10004
I/libpersona( 4649): KNOX_SDCARD not a persona
,I/SELinux ( 4649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4649 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 3978:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
D/TimaKeyStoreProvider( 4649): TimaSignature is unavailable
I/TactileAssist( 1014): List of disabled apps :
D/ActivityThread( 4649): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,E/Zygote  ( 4664): MountEmulatedStorage()
E/Zygote  ( 4664): v2
I/libpersona( 4664): KNOX_SDCARD checking this for 10053
I/libpersona( 4664): KNOX_SDCARD not a persona
,I/SELinux ( 4664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1014): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=4664 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 4664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4664): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/OMACP   ( 4633): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3946/cgroup.procs: No such file or directory
E/installd(  282): system dir 2 : /vendor/app/
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_3978/cgroup.procs: No such file or directory
E/installd(  282): system dir 3 : /oem/app/
,I/ActivityManager( 1014): Killing 4014:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/PackageManager( 1014): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/TimaKeyStoreProvider( 4664): TimaSignature is unavailable
,D/ActivityThread( 4664): Added TimaKeyStore provider
,W/ResourcesManager( 4664): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 4664): onReceive() it will make start service
,D/ActivityManager( 1014): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 4664): onHandleIntent()
D/Compatibility( 4664): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10174, android.intent.extra.user_handle=0}]
,E/Zygote  ( 4683): MountEmulatedStorage(),
E/Zygote  ( 4683): v2
I/libpersona( 4683): KNOX_SDCARD checking this for 10057
I/libpersona( 4683): KNOX_SDCARD not a persona
,I/SELinux ( 4683): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/Compatibility( 4664): found: 2,
,I/SELinux ( 4683): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4683): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1014): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4683 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,D/Compatibility( 4664): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 4664): skipping ResolveInfo{24dc4350 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 4664): considering ResolveInfo{2e2b3949 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 4664): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/TimaKeyStoreProvider( 4683): TimaSignature is unavailable
,D/ActivityThread( 4683): Added TimaKeyStore provider
,D/Compatibility( 4664): enabling receiver ResolveInfo{2b51d24e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/art     (  307): Explicit concurrent mark sweep GC freed 8709(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 39.571ms
,W/libprocessgroup( 1014): failed to open /acct/uid_10107/pid_4014/cgroup.procs: No such file or directory
,D/Compatibility( 4664): enabling receiver ResolveInfo{163e7f6f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 17.212ms
,D/Compatibility( 4664): enabling receiver ResolveInfo{24a447c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 4664): enabling receiver ResolveInfo{e652105 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 4664): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/ActivityManager( 1014): Killing 4085:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 27.648ms
,E/Watchdog( 1014): !@Sync 1
,W/ResourcesManager( 4551): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SettingsProvider( 1014): name = audio_safe_volume_state
,W/ResourcesManager( 4551): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4551): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4551): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 3518): Background sticky concurrent mark sweep GC freed 10501(879KB) AllocSpace objects, 8(128KB) LOS objects, 7% free, 12MB/13MB, paused 3.717ms total 160.316ms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4085/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4683): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/LocationManagerService( 1014): getProviders()=[passive]
,I/Icing   ( 3518): updateResources: need to parse f{com.google.android.gms}
D/ChimeraCfgMgr( 3518): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3518): Module APK com.google.android.play.games already loaded
,I/art     ( 3518): Background sticky concurrent mark sweep GC freed 5706(488KB) AllocSpace objects, 5(80KB) LOS objects, 3% free, 13MB/13MB, paused 6.360ms total 34.275ms
,I/UpdateIcingCorporaServi( 4683): UpdateCorporaTask done [took 106 ms] updated apps [took 105 ms] 
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 21384(1288KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.195ms total 150.747ms
,I/ActivityManager( 1014): Killing 4142:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,W/GAV2    ( 4486): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/libprocessgroup( 1014): failed to open /acct/uid_10125/pid_4142/cgroup.procs: No such file or directory
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{350f1ae5 u0 com.samsung.android.providers.context/.ContextService}
,I/art     ( 1643): Explicit concurrent mark sweep GC freed 3216(130KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 728us total 26.010ms
,I/Icing   ( 3518): Internal init done: storage state 0
,I/Icing   ( 3518): Post-init done
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 4486): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 4726): MountEmulatedStorage()
,I/ActivityManager( 1014): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4726 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/Zygote  ( 4726): v2
I/libpersona( 4726): KNOX_SDCARD checking this for 10100
I/libpersona( 4726): KNOX_SDCARD not a persona
,I/SELinux ( 4726): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SELinux ( 4726): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4726): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1866): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4726): TimaSignature is unavailable
,D/ActivityThread( 4726): Added TimaKeyStore provider
,W/AccountFeatureHelper( 4486): Write apps_features disabled false
,D/PackageIntentReceiver( 4726): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 4726): Not GearManger package! 
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4743): MountEmulatedStorage(),
E/Zygote  ( 4743): v2
I/libpersona( 4743): KNOX_SDCARD checking this for 1000
I/libpersona( 4743): KNOX_SDCARD not a persona
I/SELinux ( 4743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=4743 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1014): Killing 4163:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,E/SELinux ( 4743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4743): TimaSignature is unavailable
,D/ActivityThread( 4743): Added TimaKeyStore provider
,I/ActivityManager( 1014): Waited long enough for: ServiceRecord{12d96786 u0 com.android.settings/.wifi.WifiCredService}
,V/AlarmManager( 1014): waitForAlarm result :4
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4758): MountEmulatedStorage(),
,E/Zygote  ( 4758): v2,
,I/libpersona( 4758): KNOX_SDCARD checking this for 1000
I/libpersona( 4758): KNOX_SDCARD not a persona
,I/SELinux ( 4758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=4758 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1014): Killing 4101:com.android.providers.calendar/u0a42 (adj 15): empty #31
,I/SELinux ( 4758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4758): TimaSignature is unavailable
,D/ActivityThread( 4758): Added TimaKeyStore provider
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 4758): Received: android.intent.action.PACKAGE_ADDED
,W/libprocessgroup( 1014): failed to open /acct/uid_10131/pid_4163/cgroup.procs: No such file or directory
,W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 4775): MountEmulatedStorage()
E/Zygote  ( 4775): v2
I/libpersona( 4775): KNOX_SDCARD checking this for 10120
I/libpersona( 4775): KNOX_SDCARD not a persona
,I/SELinux ( 4775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1014): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4775 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1014): Killing 4190:com.android.calendar/u0a135 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
E/SELinux ( 4775): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 4758): Enter Oncreate
,D/AcmsServiceMonitor( 4758): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 4758): creating AcmsCore
,D/AcmsCore( 4758): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 4758): AcmsCore
,D/AcmsCore( 4758): init
D/AcmsCore( 4758): Looper handler is not null
D/AcmsCore( 4758): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4758): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 4758): Incrementing - Counter value: 1
D/AcmsCore( 4758): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 4758): onStartCommand
D/AcmsService( 4758): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 4758): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 4758): Incrementing - Counter value: 2
D/AcmsService( 4758): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1014): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 4758): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 4758): AcmsCertificateMngr
,W/GAV2    ( 4486): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/TimaKeyStoreProvider( 4775): TimaSignature is unavailable
,D/ActivityThread( 4775): Added TimaKeyStore provider
,D/AcmsRevocationMngr( 4758): AcmsRevocationMngr
,D/AcmsService( 4758): Inside handle Intent
D/AcmsService( 4758): App added - package name: com.example.hello
D/AcmsCore( 4758): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 4758): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 4758): Incrementing - Counter value: 3
D/AcmsCore( 4758): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 4758): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 4758): Decrementing - Counter value: 2
,W/ResourcesManager( 4775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1014): failed to open /acct/uid_10042/pid_4101/cgroup.procs: No such file or directory
,W/libprocessgroup( 1014): failed to open /acct/uid_10135/pid_4190/cgroup.procs: No such file or directory
,I/Mms/MmsApp( 4535):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 4535): [start]    fillCache consume time = 1917.090051
,D/Mms/ComposeMessageFragment( 4535): fillCache, easy = false
,D/AbsListView( 4535): Get MotionRecognitionManager
,D/MotionRecognitionService( 1014):  ssp status : false
,D/Mms/ComposeMessageFragment( 4535): [end]    fillCache consume time = 103.299375
,E/SMD     (  286): DCD OFF,
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1014): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/Mms/BubbleViewCache( 4535): fillCache bubble = 1
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/ActivityManager( 1014): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4800): MountEmulatedStorage()
,I/libpersona( 4800): KNOX_SDCARD checking this for 10142
E/Zygote  ( 4800): v2
I/libpersona( 4800): KNOX_SDCARD not a persona
,I/SELinux ( 4800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=4800 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4800): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1014): Killing 4214:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4800): TimaSignature is unavailable
D/ActivityThread( 4800): Added TimaKeyStore provider
,V/TaskCloserActivity( 4800): TaskCloserActivity enter()
,V/TaskCloserActivity( 4800): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,I/ActivityManager( 1014): Killing 4294:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/ActivityManager( 1014): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1014): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4817 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4817): MountEmulatedStorage()
I/libpersona( 4817): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4817): v2
I/libpersona( 4817): KNOX_SDCARD not a persona
I/SELinux ( 4817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4817): TimaSignature is unavailable
,D/ActivityThread( 4817): Added TimaKeyStore provider
,W/libprocessgroup( 1014): failed to open /acct/uid_10139/pid_4214/cgroup.procs: No such file or directory
W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4294/cgroup.procs: No such file or directory
,I/Icing   ( 3518): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
,E/MTPRx   ( 4817): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1014): mCursor = null
,D/SecContentProvider2( 1014): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1014): mCursor = null
,V/MTPRx   ( 4817): sealedState: false
V/MTPRx   ( 4817): sealedUsbMassStorageState: false
,E/MTPRx   ( 4817): check value of boot_completed is1
E/MTPRx   ( 4817): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4817): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4817): Status for mount/Unmount :removed
E/MTPRx   ( 4817): SDcard is not available
,W/MTPRx   ( 4817): value of connected istrue
W/MTPRx   ( 4817): value of configured istrue
W/MTPRx   ( 4817): value of mtpEnabled istrue
W/MTPRx   ( 4817): value of ptpEnabled isfalse
,E/MTPRx   ( 4817): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4817): mFirstTime: false
,D/        ( 4817): MTP: reading debug level property
,E/MTPJNIInterface( 4817): Getting CryptionKey from JAVA
,E/MTPRx   ( 4817): currentUserId is 0
,E/MTPRx   ( 4817): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4817): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4817): is_Privatemode is NOT 1
,D/SettingsProvider( 1014): name = boot_time_connected
,E/MTPRx   ( 4817): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4817): noti = 17
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,D/SecContentProvider( 1014): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4817): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,E/MTPRx   ( 4817): else part ... so first time!!!
,E/MTPPlaObsrvr( 4817): inside setContext()
,E/MTPPlaObsrvr( 4817):  inside createplafiles
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/Icing   ( 3518): Loaded CLD2 Version V2.0 - 20141016
,E/MTPPlaObsrvr( 4817): playlist count is0
,E/MTPPlaObsrvr( 4817):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4817):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4817): Inside registerContentObserver
I/Icing   ( 3518): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,E/MtpAdbObserver( 4817): inside setContext()
E/MtpAdbObserver( 4817): Inside registerContentObserver
W/Settings( 4817): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/ActivityManager( 1014): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1014): name = mtp_running_status
,D/ActivityManager( 1014): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
V/MtpMediaDBManager( 4817): inside deleteAllDB
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ValidateNoPeople( 1014): mEvictionCount: 0
,D/SettingsProvider( 1014): name = mtp_usb_conditions_met
,I/ActivityManager( 1014): Killing 4311:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,E/MtpService( 4817): onCreate.
,E/MtpService( 4817): < MTP > Registering BroadCast receiver :::::
,D/Mms/Contact( 4535): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4535): performUpdate:widgetCount=0
,E/MtpService( 4817): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
D/ActivityManager( 1014): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
D/ActivityManager( 1014): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4817): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/Mms/ContactsCache( 4535): [start]    invalidate() consume time = 471.823073
,D/Mms/ContactsCache( 4535): [end]    invalidate() consume time = 0.438125
,E/MtpService( 4817): onStartCommand.
,W/MTPRx   ( 4817): calling native method
E/MTPJNIInterface( 4817): < MTP > Registering BroadCast receiver :::::
,D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
,E/MTPJNIInterface( 4817): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 4817): noti = 10
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MtpService( 4817): handleMessage. msg= { when=-10ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MtpService( 4817): onStartCommand.
W/MTPRx   ( 4817): calling native method
,E/MTPRx   ( 4817): Checking the driver time out
E/MTPJNIInterface( 4817): noti = 2
D/        ( 4817): deleting sockets before message queue initialization
,D/        ( 4817): event handler thread is created, so set the flag
,D/ContactProvider( 4367): getAllContactInfoList Start
,E/MTPRx   ( 4817): called native method
E/MtpService( 4817): handleMessage. msg= { when=-4ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 4817): setting Media scanner status0
E/MTPJNIInterface( 4817): After setting Media scanner status0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/MTPRx   ( 4817): notification from stack 1
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/MtpMediaDBManager( 4817): inside Thread updateDB
,E/        ( 4817): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4817): Getting media scanner status0
,E/MTPJNIInterface( 4817): DeviceName is A5-1
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,V/UserPresentBroadcastReceiver( 1866): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1014): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1014): failed to open /acct/uid_1000/pid_4311/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MtpMediaDBManager( 4817): count : 27
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/MtpMediaDBManager( 4817): sending db update complete noti to stack
E/MTPJNIInterface( 4817): noti = 29
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ContactProvider( 4367): getAllContactInfoList End
,I/syncContacts( 4367): thread: 700, onChange
D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/MTPJNIInterface( 4817): Status for mount/Unmount :removed
E/MTPJNIInterface( 4817): SDcard is not available
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1298): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1298): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1298): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/        ( 4817): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457448120000
,D/daemonapp( 1298): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457426585894
D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,E/        ( 4817): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1298): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/MTPJNIInterface( 4817): Status for mount/Unmount :removed
E/MTPJNIInterface( 4817): SDcard is not available
,E/SQLiteLog( 4817): (21) API call with NULL database connection pointer
E/SQLiteLog( 4817): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4817): (21) API call with NULL database connection pointer
E/SQLiteLog( 4817): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4817): (21) API call with NULL database connection pointer
E/SQLiteLog( 4817): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4817): (21) API call with NULL database connection pointer
E/SQLiteLog( 4817): (21) misuse at line 106108 of [9491ba7d73]
,D/        ( 4817): [mtp_init_device] Library open with 32 bits.
,W/MTPRx   ( 4817): notification from stack 2
D/        ( 4817): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4817): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,D/        ( 4817): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4817):  [sua_support_present:1287] returning false 
E/daemonapp( 1298): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/        ( 4817): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1014): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0

```
