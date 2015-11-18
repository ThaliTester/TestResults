#### Test 50388019f4ce509_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  290): DCD OFF
--------- beginning of system
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/AndroidRuntime( 5335): 
D/AndroidRuntime( 5335): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5335): CheckJNI is OFF
D/AndroidRuntime( 5335): readGMSProperty: start
D/AndroidRuntime( 5335): readGMSProperty: already setted!!
D/AndroidRuntime( 5335): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5335): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5335): readGMSProperty: end
D/AndroidRuntime( 5335): addProductProperty: start
E/AffinityControl( 5335): AffinityControl: registerfunction enter
D/AndroidRuntime( 5335): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5347 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
E/Zygote  ( 5347): MountEmulatedStorage()
D/InputDispatcher( 1020): Focus left window: 1476
E/Zygote  ( 5347): v2
D/AndroidRuntime( 5335): Shutting down VM
I/libpersona( 5347): KNOX_SDCARD checking this for 10345
I/libpersona( 5347): KNOX_SDCARD not a persona
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5347): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5347): TimaSignature is unavailable
D/ActivityThread( 5347): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1020): Display changed displayId=0
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1476): updateVisibility : ActivityRecord{a4b35cf token=android.os.BinderProxy@14de6341 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1476): onTrimMemory. Level: 20
I/WebViewFactory( 5347): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5347): Time to load native libraries: 1 ms (timestamps 7170-7171)
I/LibraryLoader( 5347): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5347): Binding Chromium to main looper Looper (main, tid 1) {35bd6b82}
I/LibraryLoader( 5347): Expected native library version number "",actual native library version number ""
I/chromium( 5347): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5335): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 5347): Initializing chromium process, singleProcess=true
W/art     ( 5347): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5347): ApplicationContext is null in ApplicationStatus
W/chromium( 5347): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5347): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5347): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5347): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5347): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5347): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5347): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5347): Local Branch: 
I/Adreno-EGL( 5347): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5347): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5347):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5347): 348898543: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5347): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5347): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5347): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5347): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5347): CordovaWebView is running on device made by: samsung
,W/art     ( 5347): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5347): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{22d1357d u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 5347): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 5347): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5347): updateVisibility : ActivityRecord{190e3c2c token=android.os.BinderProxy@4d8367e {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 5347): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5347): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1020): Focus entered window: 5347
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5347): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5347): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5347): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5347): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +648ms (total +734ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{22d1357d u0 com.example.hello/.MainActivity t19} time:87736
,W/IInputConnectionWrapper( 5347): showStatusIcon on inactive InputConnection
,I/Timeline( 5347): Timeline: Activity_idle id: android.os.BinderProxy@4d8367e time:87739
,I/SamsungIME( 1790): getCurrentCandidateView
,I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  259): id=11 Removed iello (-2/9)
,W/BindingManager( 5347): Cannot call determinedVisibility() - never saw a connection for the pid: 5347
,I/chromium( 5347): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/SamsungIME( 1790): Dismiss ExpandCandiate
,I/SamsungIME( 1790): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1790): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1790): KeybaordView init() : load resources
,I/SamsungIME( 1790): getCurrentKeyboard
I/SamsungIME( 1790): getTextKeyboard
,D/JsMessageQueue( 5347): Set native->JS mode to OnlineEventsBridgeMode
,D/SamsungIME( 1790): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/AndroidProtocolHandler( 5347): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/SMD     (  290): DCD OFF,
,D/jxcore_app_log( 5347): JniHelper::setJavaVM(0xb7975448), pthread_self() = -1210323104
,D/JX-Cordova( 5347): jxcore cordova android initializing
,W/jxcore-log( 5347): Initializing JXcore engine
W/jxcore-log( 5347): JXcore engine is ready
,W/jxcore-log( 5347): Starting JXcore engine
,E/audit   ( 1801): type=1400 msg=audit(1447834372.597:203): avc:  denied  { ioctl } for  pid=5347 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1801):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1801): type=1300 msg=audit(1447834372.597:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=bee36d58 items=0 ppid=308 ppcomm=main pid=5347 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1801): type=1320 msg=audit(1447834372.597:203): 
,W/jxcore-log( 5347): Platform android
W/jxcore-log( 5347): 
W/jxcore-log( 5347): Process ARCH arm
W/jxcore-log( 5347): 
,I/jxcore-log( 5347): JXcore Cordova bridge is ready!
I/jxcore-log( 5347): 
,W/jxcore-log( 5347): JXcore engine is started
,E/jxcore-log( 5347): >> samsung-SM-A300FU
E/jxcore-log( 5347): 
I/jxcore-log( 5347): Total memory 1451114496
I/jxcore-log( 5347): 
,I/jxcore-log( 5347): Free memory 25505792
I/jxcore-log( 5347): 
I/jxcore-log( 5347): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5347): 
I/jxcore-log( 5347): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5347): 
,I/jxcore-log( 5347): userPath [ 'www' ]
I/jxcore-log( 5347): 
,I/jxcore-log( 5347): Size 540 960
I/jxcore-log( 5347): 
,I/jxcore-log( 5347): Screen Brightness 160
I/jxcore-log( 5347): 
,E/jxcore-log( 5347): Dummy Error Log.
E/jxcore-log( 5347): 
,I/jxcore-log( 5347): getBuffer is called!!!!
I/jxcore-log( 5347): 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,D/BluetoothAdapter( 5347): disable()
,E/BluetoothManagerService( 1020): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1020): mCursor = null
,D/WifiService( 1020): setWifiEnabled: false pid=5347, uid=10345
,D/SettingsProvider( 1020): name = wifi_on
,I/jxcore-log( 5347): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 5347): 
,I/jxcore-log( 5347): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5347): 
,D/AndroidRuntime( 5397): ,
D/AndroidRuntime( 5397): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5397): CheckJNI is OFF,
D/AndroidRuntime( 5397): readGMSProperty: start
D/AndroidRuntime( 5397): readGMSProperty: already setted!!
D/AndroidRuntime( 5397): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 5397): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5397): readGMSProperty: end
D/AndroidRuntime( 5397): addProductProperty: start
,E/AffinityControl( 5397): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5397): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1020): START PACKAGE DELETE: observer{622630911}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true,
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 5347:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1020): Skipping PackageSetting{31325e06 com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{22d1357d u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,W/InputDispatcher( 1020): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1020): channel ~ Channel is unrecoverably broken and will be disposed!
,D/InputDispatcher( 1020): Focus left window: 5347
W/InputDispatcher( 1020): Attempted to unregister already unregistered input channel,
I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focused application released
,W/WindowManager( 1020): Failed looking up window
W/WindowManager( 1020): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@2fedc146 does not exist
W/WindowManager( 1020): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
W/WindowManager( 1020): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
W/WindowManager( 1020): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
W/WindowManager( 1020): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
,I/WindowState( 1020): WIN DEATH: null
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,E/SMD     (  290): DCD OFF
,I/art     ( 5205): Explicit concurrent mark sweep GC freed 9280(428KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 727us total 32.359ms
,I/art     ( 5061): Explicit concurrent mark sweep GC freed 16291(903KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 758us total 38.067ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4114): Explicit concurrent mark sweep GC freed 21064(1402KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 2.675ms total 52.743ms
,E/SamsungIME( 1790): mOCRHelper is null
,W/GeofencerStateMachine( 1627): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3392): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 18 09:12:58 GMT+01:00 2015
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3392): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5410): MountEmulatedStorage()
E/Zygote  ( 5410): v2
I/libpersona( 5410): KNOX_SDCARD checking this for 10090
I/libpersona( 5410): KNOX_SDCARD not a persona
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): onCreate()
,I/SELinux ( 5410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3392): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux ( 5410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 3392): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/SELinux ( 5410): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5410 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5410): TimaSignature is unavailable
,D/ActivityThread( 5410): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/elm:15121( 5410): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/art     ( 1020): Explicit concurrent mark sweep GC freed 29544(2MB) AllocSpace objects, 18(288KB) LOS objects, 33% free, 23MB/35MB, paused 2.382ms total 194.818ms
D/RegisteredServicesCache( 1443): empty dynamic service
,I/art     ( 1020): WaitForGcToComplete blocked for 184.756ms for cause Explicit
D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,D/elm:15121( 5410): ELMEngine.ELMEngine( context ).
D/elm:15121( 5410): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5410): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:15121( 5410): ElmAgentService : onCreate()
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5410): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5410): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5410): MDMBridge.getInstance()
,D/elm:15121( 5410): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5410): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3392): KLMSIntentService(): onDestroy()
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/elm:15121( 5410): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 4842:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10345
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=19_task.xml
,D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10345
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,I/PCWCLIENTTRACE_PushUtil( 4972): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4972): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 4972): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 4972): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5077): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5077): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 9861(557KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.045ms total 171.956ms
,I/PackagesMonitor( 4345): PackagesMonitor onReceive :com.example.hello
,D/PackageManager( 1020): delete codoeFile: 
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1020): UID=10345 Target=com.example.hello
,D/PackageManager( 1020): result of delete: 1{622630911}
,D/AndroidRuntime( 5397): Shutting down VM
,D/Mms/FreeMessageStatusReceiver( 4919): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1020): enable value -1
,I/TactileAssist( 1020): internal enable value -1
,I/TactileAssist( 1020): intensity value -1
I/TactileAssist( 1020): saveAppList value true
,I/TactileAssist( 1020): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4919): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4919): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/Compatibility( 5164): onReceive() it will make start service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5164): onHandleIntent()
,D/Compatibility( 5164): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5164): found: 2
,D/Compatibility( 5164): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5164): skipping ResolveInfo{15abdce com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5164): considering ResolveInfo{14cbc4ef com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5164): default: com.sec.android.app.soundalive.SAControlPanelActivity
,E/Zygote  ( 5430): MountEmulatedStorage()
I/libpersona( 5430): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5430): v2
I/libpersona( 5430): KNOX_SDCARD not a persona
I/SELinux ( 5430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 5164): enabling receiver ResolveInfo{309ddbfc com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5430 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5164): enabling receiver ResolveInfo{2d25a285 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5164): enabling receiver ResolveInfo{2868e8da com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5164): enabling receiver ResolveInfo{1e39c10b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 5430): TimaSignature is unavailable
,D/ActivityThread( 5430): Added TimaKeyStore provider
,D/Compatibility( 5164): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/UserAnalysis.PlaceProvider( 5430): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 5430): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 5430): SecurePlaceDbHelper() 
D/UserAnalysis( 5430): Create SecureDbHelper
D/IntelligenceServiceApplication( 5430): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 5430): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5186): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/IntelligenceServiceApplication( 5430): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
,I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/art     ( 5397): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,E/Zygote  ( 5447): MountEmulatedStorage(),
I/libpersona( 5447): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5447): v2
I/libpersona( 5447): KNOX_SDCARD not a persona
I/SELinux ( 5447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
I/SELinux ( 5447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
E/SELinux ( 5447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
I/ActivityManager( 1020): Killing 3907:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/BluetoothAdapter( 5430): 1061249767: getState() :  mService = null. Returning STATE_OFF
,V/PlaceDetection v1.0.19 ( 5430): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5430): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5430): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/TimaKeyStoreProvider( 5447): TimaSignature is unavailable
,D/ActivityThread( 5447): Added TimaKeyStore provider
,W/ResourcesManager( 5447): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManager( 5447):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1020):  in createShortcut() for packageName: com.example.hello userId0,
,D/RCPManagerService( 1020): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5205): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5205): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
W/TextServicesManagerService( 1020): no available spell checker services found
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/SQLiteLog( 5430): (10) unixWrite() File Descriptor : 25 gets errno : 9
,E/SQLiteLog( 5430): (10) unixWrite() File Descriptor : 25 gets errno : 9
,E/SQLiteDatabase( 5430): Error inserting timestamp=1447834379069 message=Predictor: service is stopped by Application.onCreate
E/SQLiteDatabase( 5430): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 5430): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 5430): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5430): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5430): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5430): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5430): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5430): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5430): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5430): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5430): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5430): It failed to insert to dump_log table
,E/SQLiteLog( 5430): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5430): (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,E/SQLiteDatabase( 5430): Error inserting timestamp=1447834379122 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 5430): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 5430): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 5430): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 5430): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5430): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5430): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5430): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5430): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5430): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5430): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5430): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5430): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5430): It failed to insert to dump_log table
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/FilterInstaller( 5205): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5205): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 5205): before removeFromFS
,E/Zygote  ( 5464): MountEmulatedStorage(),
E/Zygote  ( 5464): v2
I/libpersona( 5464): KNOX_SDCARD checking this for 1000
I/libpersona( 5464): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5464 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5464): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 5464): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5464): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 5476): MountEmulatedStorage()
E/Zygote  ( 5476): v2
I/libpersona( 5476): KNOX_SDCARD checking this for 10095
I/libpersona( 5476): KNOX_SDCARD not a persona
,I/SELinux ( 5476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5476 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5464): TimaSignature is unavailable,
,D/ActivityThread( 5464): Added TimaKeyStore provider
,I/SELinux ( 5476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
