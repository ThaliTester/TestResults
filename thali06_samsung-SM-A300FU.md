#### Test 50388019c82294c_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,--------- beginning of main
D/AndroidRuntime( 5270): 
D/AndroidRuntime( 5270): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5270): CheckJNI is OFF
D/AndroidRuntime( 5270): readGMSProperty: start
D/AndroidRuntime( 5270): readGMSProperty: already setted!!
D/AndroidRuntime( 5270): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5270): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5270): readGMSProperty: end
D/AndroidRuntime( 5270): addProductProperty: start
E/AffinityControl( 5270): AffinityControl: registerfunction enter
D/AndroidRuntime( 5270): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
E/Zygote  ( 5283): MountEmulatedStorage()
E/Zygote  ( 5283): v2
I/libpersona( 5283): KNOX_SDCARD checking this for 10345
I/libpersona( 5283): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5283 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1479
D/AndroidRuntime( 5270): Shutting down VM
I/SELinux ( 5283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5283): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5283): TimaSignature is unavailable
D/ActivityThread( 5283): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1020): Display changed displayId=0
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{2a33537c token=android.os.BinderProxy@3d2feeb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/WebViewFactory( 5283): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5283): Time to load native libraries: 2 ms (timestamps 6823-6825)
I/LibraryLoader( 5283): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5283): Binding Chromium to main looper Looper (main, tid 1) {324e8ca2}
I/LibraryLoader( 5283): Expected native library version number "",actual native library version number ""
I/chromium( 5283): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5283): Initializing chromium process, singleProcess=true
W/art     ( 5283): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5283): ApplicationContext is null in ApplicationStatus
W/art     ( 5270): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5283): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5283): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5283): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5283): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5283): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5283): Local Branch: 
I/Adreno-EGL( 5283): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5283): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5283):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5283): 164735375: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5283): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5283): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5283): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5283): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5283): CordovaWebView is running on device made by: samsung
W/art     ( 5283): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5283): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{25811cd7 u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5283): Render dirty regions requested: true
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
W/chromium( 5283): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5283): updateVisibility : ActivityRecord{177f9c4c token=android.os.BinderProxy@3d65519e {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5283): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5283): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1020): Focus entered window: 5283
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5283): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5283): Initialized EGL, version 1.4
D/OpenGLRenderer( 5283): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5283): Enabling debug mode 0
D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5283): showStatusIcon on inactive InputConnection
I/Timeline( 5283): Timeline: Activity_idle id: android.os.BinderProxy@3d65519e time:87373
I/ActivityManager( 1020): Displayed Component not be shown by security: +643ms (total +722ms)
W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{25811cd7 u0 com.example.hello/.MainActivity t19} time:87378
I/SamsungIME( 1794): getCurrentCandidateView
I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
I/SurfaceFlinger(  259): id=11 Removed iello (-2/9)
W/BindingManager( 5283): Cannot call determinedVisibility() - never saw a connection for the pid: 5283
V/AlarmManager( 1020): waitForAlarm result :8
I/chromium( 5283): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SamsungIME( 1794): Dismiss ExpandCandiate
I/SamsungIME( 1794): getDebugLevel  : 0x4f4c
I/SamsungIME( 1794): getDebugLevel  : 0x4f4c
I/SamsungIME( 1794): KeybaordView init() : load resources
D/JsMessageQueue( 5283): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1794): getCurrentKeyboard
I/SamsungIME( 1794): getTextKeyboard
E/AndroidProtocolHandler( 5283): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SamsungIME( 1794): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 5283): JniHelper::setJavaVM(0xb7eea448), pthread_self() = -1203499744
D/JX-Cordova( 5283): jxcore cordova android initializing
W/jxcore-log( 5283): Initializing JXcore engine
W/jxcore-log( 5283): JXcore engine is ready
W/jxcore-log( 5283): Starting JXcore engine
E/audit   ( 1792): type=1400 msg=audit(1447782180.446:203): avc:  denied  { ioctl } for  pid=5283 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1792):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1792): type=1300 msg=audit(1447782180.446:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beccfd58 items=0 ppid=319 ppcomm=main pid=5283 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1792): type=1320 msg=audit(1447782180.446:203): 
W/jxcore-log( 5283): Platform android
W/jxcore-log( 5283): 
W/jxcore-log( 5283): Process ARCH arm
W/jxcore-log( 5283): 
I/jxcore-log( 5283): JXcore Cordova bridge is ready!
I/jxcore-log( 5283): 
W/jxcore-log( 5283): JXcore engine is started
E/jxcore-log( 5283): >> samsung-SM-A300FU
E/jxcore-log( 5283): 
I/jxcore-log( 5283): Total memory 1451114496
I/jxcore-log( 5283): 
I/jxcore-log( 5283): Free memory 27598848
I/jxcore-log( 5283): 
I/jxcore-log( 5283): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5283): 
I/jxcore-log( 5283): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5283): 
I/jxcore-log( 5283): userPath [ 'www' ]
I/jxcore-log( 5283): 
I/jxcore-log( 5283): Size 540 960
I/jxcore-log( 5283): 
I/jxcore-log( 5283): Screen Brightness 160
I/jxcore-log( 5283): 
E/jxcore-log( 5283): Dummy Error Log.
E/jxcore-log( 5283): 
E/SMD     (  299): DCD OFF
I/jxcore-log( 5283): getBuffer is called!!!!
I/jxcore-log( 5283): 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  299): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,D/BluetoothAdapter( 5283): disable()
,E/BluetoothManagerService( 1020): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1020): mCursor = null
,D/WifiService( 1020): setWifiEnabled: false pid=5283, uid=10345
,D/SettingsProvider( 1020): name = wifi_on
,I/jxcore-log( 5283): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 5283): 
,I/jxcore-log( 5283): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5283): 
,D/AndroidRuntime( 5333): ,
D/AndroidRuntime( 5333): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5333): CheckJNI is OFF,
D/AndroidRuntime( 5333): readGMSProperty: start
D/AndroidRuntime( 5333): readGMSProperty: already setted!!
D/AndroidRuntime( 5333): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 5333): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5333): readGMSProperty: end
D/AndroidRuntime( 5333): addProductProperty: start
,E/AffinityControl( 5333): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5333): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1020): START PACKAGE DELETE: observer{402735497}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 5283:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1020): Skipping PackageSetting{bfeba4e com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{25811cd7 u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1020): Focus left window: 5283
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focused application released
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3671): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 677us total 23.044ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1625): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1794): mOCRHelper is null
,I/art     ( 4134): Explicit concurrent mark sweep GC freed 22708(1679KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 3.225ms total 44.011ms
,I/KLMS-2.5.123: ( 3454): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:43:06 GMT+01:00 2015
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3454): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3454): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 5346): MountEmulatedStorage(),
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5346 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 5346): v2
I/libpersona( 5346): KNOX_SDCARD checking this for 10090
I/libpersona( 5346): KNOX_SDCARD not a persona
,I/SELinux ( 5346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5346): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3454): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 19408(1495KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 2.544ms total 150.404ms
,I/art     ( 1020): WaitForGcToComplete blocked for 149.027ms for cause Explicit
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): PACKAGE_REMOVED
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/TimaKeyStoreProvider( 5346): TimaSignature is unavailable
,D/ActivityThread( 5346): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5346): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5346): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5346): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5346): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 5346): ElmAgentService : onCreate()
,D/elm:15121( 5346): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5346): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5346): MDMBridge.getInstance()
D/elm:15121( 5346): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3454): KLMSIntentService(): onDestroy()
,D/elm:15121( 5346): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5346): ElmAgentService : onDestroy().
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10345
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
I/ActivityManager( 1020): Killing 4266:com.google.android.music:main/u0a108 (adj 15): empty #31
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10345
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
D/TaskPersister( 1020): removeObsoleteFile: deleting file=19_task.xml
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,I/PCWCLIENTTRACE_PushUtil( 5018): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5018): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5018): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5018): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5154): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5154): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4332): PackagesMonitor onReceive :com.example.hello
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 10473(582KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.892ms total 239.764ms
,D/Mms/FreeMessageStatusReceiver( 4194): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/SMD     (  299): DCD OFF
,I/TactileAssist( 1020): enable value -1
,I/TactileAssist( 1020): internal enable value -1
I/TactileAssist( 1020): intensity value -1
I/TactileAssist( 1020): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4194): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4194): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1020): List of disabled apps :
,D/PackageManager( 1020): delete codoeFile: 
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1020): UID=10345 Target=com.example.hello
,D/PackageManager( 1020): result of delete: 1{402735497}
,D/AndroidRuntime( 5333): Shutting down VM
,D/Compatibility( 5052): onReceive() it will make start service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5052): onHandleIntent()
,E/Zygote  ( 5366): MountEmulatedStorage()
E/Zygote  ( 5366): v2
I/libpersona( 5366): KNOX_SDCARD checking this for 10055,
I/libpersona( 5366): KNOX_SDCARD not a persona
I/SELinux ( 5366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 5052): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}],
D/Compatibility( 5052): found: 2
D/Compatibility( 5052): saved default: com.sec.android.app.soundalive.SAControlPanelActivity,
D/Compatibility( 5052): skipping ResolveInfo{d2cd0ee com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5052): considering ResolveInfo{9d1a98f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5052): default: com.sec.android.app.soundalive.SAControlPanelActivity,
I/SELinux ( 5366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Compatibility( 5052): enabling receiver ResolveInfo{388f41c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/SELinux ( 5366): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5366 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 5052): enabling receiver ResolveInfo{2558a825 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5052): enabling receiver ResolveInfo{1b990dfa com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5052): enabling receiver ResolveInfo{2bc94fab com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5052): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 5366): TimaSignature is unavailable
,D/ActivityThread( 5366): Added TimaKeyStore provider
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/UserAnalysis.PlaceProvider( 5366): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 5366): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5366): SecurePlaceDbHelper() 
,D/UserAnalysis( 5366): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5366): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5366): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/IntelligenceServiceApplication( 5366): no applications having user consent for prediction
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5383): MountEmulatedStorage()
,E/Zygote  ( 5383): v2
I/libpersona( 5383): KNOX_SDCARD checking this for 1000
I/libpersona( 5383): KNOX_SDCARD not a persona
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5383 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 4849:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false,
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false,
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false,
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.,
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false,
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/BluetoothAdapter( 5366): 894122887: getState() :  mService = null. Returning STATE_OFF,
V/PlaceDetection v1.0.19 ( 5366): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.,
D/TimaKeyStoreProvider( 5383): TimaSignature is unavailable
,V/PlaceDetection v1.0.19 ( 5366): [PlaceDetection::stopService] Service stopped.
D/ActivityThread( 5383): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 5366): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/ResourcesManager( 5383): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/art     ( 5333): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/RCPManager( 5383):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1020):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1020): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5102): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello,
,W/ContextImpl( 5102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FilterInstaller( 5102): FilterPackageService : ACTION_PACKAGE_REMOVED
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/FilterInstaller( 5102): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5102): before removeFromFS,
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5401 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 5401): MountEmulatedStorage()
E/Zygote  ( 5401): v2
I/libpersona( 5401): KNOX_SDCARD checking this for 1000
I/libpersona( 5401): KNOX_SDCARD not a persona
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/SELinux ( 5401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5401): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 5410): MountEmulatedStorage()
,E/Zygote  ( 5410): v2
I/libpersona( 5410): KNOX_SDCARD checking this for 10095
I/libpersona( 5410): KNOX_SDCARD not a persona,
,D/TimaKeyStoreProvider( 5401): TimaSignature is unavailable
I/SELinux ( 5410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/ActivityThread( 5401): Added TimaKeyStore provider
I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5410 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 5410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5410): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5410): TimaSignature is unavailable
,D/ActivityThread( 5410): Added TimaKeyStore provider
,W/ContextImpl( 5401): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5431): MountEmulatedStorage()
E/Zygote  ( 5431): v2
I/libpersona( 5431): KNOX_SDCARD checking this for 1000
I/libpersona( 5431): KNOX_SDCARD not a persona
,I/SELinux ( 5431): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1020): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5431 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5431): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PreloadFilterInstaller( 5410): uses FILTER_DB_VER_1
,E/SQLiteLog( 5410): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
,E/SELinux ( 5431): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteDatabase( 5410): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 5410): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5410): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5410): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5410): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5410): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 5410): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 5410): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 5410): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 5410): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 5410): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 5410): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 5410): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 5410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 5410): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 5410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 5410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5410): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5410): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5410): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5410): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 5410): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 5410): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5410): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 5410): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5410): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5410): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 5410): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 5410): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 5410): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 5410): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 5410): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 5410): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 5410): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 5410): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 5410): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 5410): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 5410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5410): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5410): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 5410): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5410): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5410): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5410): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 5410): Opened filter.db in read-only mode
,E/SQLiteLog( 5401): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)

```
