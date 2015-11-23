#### Test 5038801932cd575_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  290): DCD OFF
,D/AndroidRuntime( 5304): 
D/AndroidRuntime( 5304): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5304): CheckJNI is OFF
D/AndroidRuntime( 5304): readGMSProperty: start
D/AndroidRuntime( 5304): readGMSProperty: already setted!!
D/AndroidRuntime( 5304): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5304): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5304): readGMSProperty: end
D/AndroidRuntime( 5304): addProductProperty: start
E/AffinityControl( 5304): AffinityControl: registerfunction enter
D/AndroidRuntime( 5304): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/Zygote  ( 5317): MountEmulatedStorage()
E/Zygote  ( 5317): v2
I/libpersona( 5317): KNOX_SDCARD checking this for 10345
I/libpersona( 5317): KNOX_SDCARD not a persona
I/SELinux ( 5317): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5317 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5317): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5317): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1019): Focused application set to: xxxx
D/TimaKeyStoreProvider( 5317): TimaSignature is unavailable
D/InputDispatcher( 1019): Focus left window: 1477
D/ActivityThread( 5317): Added TimaKeyStore provider
D/AndroidRuntime( 5304): Shutting down VM
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1477): updateVisibility : ActivityRecord{b3695fb token=android.os.BinderProxy@34dc1537 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1477): onTrimMemory. Level: 20
I/WebViewFactory( 5317): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5317): Time to load native libraries: 2 ms (timestamps 5997-5999)
I/LibraryLoader( 5317): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5317): Binding Chromium to main looper Looper (main, tid 1) {128be559}
I/LibraryLoader( 5317): Expected native library version number "",actual native library version number ""
I/chromium( 5317): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5317): Initializing chromium process, singleProcess=true
W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5317): ApplicationContext is null in ApplicationStatus
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
W/chromium( 5317): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1398): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1398): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
W/chromium( 5317): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5317): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5317): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5317): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5317): Local Branch: 
I/Adreno-EGL( 5317): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5317): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5317):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 5304): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/BluetoothAdapter( 5317): 178155291: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5317): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5317): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5317): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5317): CordovaWebView is running on device made by: samsung
,W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5317): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5317): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 5317): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5317): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5317): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5317
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5317): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5317): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5317): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5317): Enabling debug mode 0
,V/ActivityThread( 5317): updateVisibility : ActivityRecord{28f5550b token=android.os.BinderProxy@234a1685 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1765): getCurrentCandidateView
,W/IInputConnectionWrapper( 5317): showStatusIcon on inactive InputConnection,
I/Timeline( 5317): Timeline: Activity_idle id: android.os.BinderProxy@234a1685 time:86532
,I/ActivityManager( 1019): Displayed Component not be shown by security: +657ms (total +738ms)
W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{220f2037 u0 com.example.hello/.MainActivity t19} time:86571
D/SamsungIME( 1765): Dismiss ExpandCandiate
,I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
,I/SamsungIME( 1765): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1765): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1765): KeybaordView init() : load resources
,W/BindingManager( 5317): Cannot call determinedVisibility() - never saw a connection for the pid: 5317
,I/SamsungIME( 1765): getCurrentKeyboard
I/SamsungIME( 1765): getTextKeyboard
,I/chromium( 5317): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/SamsungIME( 1765): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5317): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5317): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5317): JniHelper::setJavaVM(0xb8da8448), pthread_self() = -1188039984
,D/JX-Cordova( 5317): jxcore cordova android initializing
,W/jxcore-log( 5317): Initializing JXcore engine
,W/jxcore-log( 5317): JXcore engine is ready
,W/jxcore-log( 5317): Starting JXcore engine
,E/audit   ( 1810): type=1400 msg=audit(1448315202.593:203): avc:  denied  { ioctl } for  pid=5317 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1810):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1810): type=1300 msg=audit(1448315202.593:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be8cdd58 items=0 ppid=307 ppcomm=main pid=5317 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1810): type=1320 msg=audit(1448315202.593:203): 
,W/jxcore-log( 5317): Platform android
W/jxcore-log( 5317): 
W/jxcore-log( 5317): Process ARCH arm
W/jxcore-log( 5317): 
,I/jxcore-log( 5317): JXcore Cordova bridge is ready!
I/jxcore-log( 5317): 
,W/jxcore-log( 5317): JXcore engine is started
,E/jxcore-log( 5317): >> samsung-SM-A300FU
E/jxcore-log( 5317): 
,I/jxcore-log( 5317): Total memory 1451114496
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): Free memory 23871488
I/jxcore-log( 5317): 
I/jxcore-log( 5317): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5317): 
I/jxcore-log( 5317): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): userPath [ 'www' ]
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): Size 540 960
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): Screen Brightness 160
I/jxcore-log( 5317): 
,E/jxcore-log( 5317): Dummy Error Log.
E/jxcore-log( 5317): 
,I/jxcore-log( 5317): getBuffer is called!!!!
I/jxcore-log( 5317): 
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,D/BluetoothAdapter( 5317): disable()
,E/BluetoothManagerService( 1019): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1019): mCursor = null
,D/WifiService( 1019): setWifiEnabled: false pid=5317, uid=10345
,D/SettingsProvider( 1019): name = wifi_on
,I/jxcore-log( 5317): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 5317): 
,I/jxcore-log( 5317): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5317): 
,D/AndroidRuntime( 5369): 
D/AndroidRuntime( 5369): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5369): CheckJNI is OFF
,D/AndroidRuntime( 5369): readGMSProperty: start
D/AndroidRuntime( 5369): readGMSProperty: already setted!!
D/AndroidRuntime( 5369): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5369): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5369): readGMSProperty: end
D/AndroidRuntime( 5369): addProductProperty: start
,E/AffinityControl( 5369): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5369): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1019): START PACKAGE DELETE: observer{379836905}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
,D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0,
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 5317:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{37cdb6f5 com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{220f2037 u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1019): Focus left window: 5317
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1019): Focused application released
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3736): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 923us total 40.582ms
,E/SamsungIME( 1765): mOCRHelper is null
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010,
,W/GeofencerStateMachine( 1638): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4114): Explicit concurrent mark sweep GC freed 22584(1675KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 5.298ms total 93.095ms
,I/KLMS-2.5.123: ( 3477): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 22:46:48 GMT+01:00 2015
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3477): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5382 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,E/Zygote  ( 5382): MountEmulatedStorage(),
,E/Zygote  ( 5382): v2
I/libpersona( 5382): KNOX_SDCARD checking this for 10090
I/libpersona( 5382): KNOX_SDCARD not a persona
,I/SELinux ( 5382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/KLMS-2.5.123: ( 3477): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3477): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/SELinux ( 5382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3477): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3477): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
I/KLMS-2.5.123: ( 3477): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3477): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 5382): TimaSignature is unavailable
D/ActivityThread( 5382): Added TimaKeyStore provider
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 22407(1743KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/34MB, paused 8.283ms total 202.761ms
,I/art     ( 1019): WaitForGcToComplete blocked for 189.663ms for cause Explicit
,I/KLMS-2.5.123: ( 3477): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/RegisteredServicesCache( 1437): empty dynamic service
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5382): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5382): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5382): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5382): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3477): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 5382): ElmAgentService : onCreate()
I/KLMS-2.5.123: ( 3477): KLMSIntentService(): onDestroy()
,D/elm:15121( 5382): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5382): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5382): MDMBridge.getInstance()
D/elm:15121( 5382): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5382): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5382): ElmAgentService : onDestroy().
,I/ActivityManager( 1019): Killing 4850:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10345
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10345
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,D/TaskPersister( 1019): removeObsoleteFile: deleting file=19_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5032): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5032): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5032): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5032): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5120): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5120): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 9021(525KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.753ms total 190.952ms
,I/PackagesMonitor( 4336): PackagesMonitor onReceive :com.example.hello
,D/PackageManager( 1019): delete codoeFile: 
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1019): UID=10345 Target=com.example.hello
,D/PackageManager( 1019): result of delete: 1{379836905}
,D/Mms/FreeMessageStatusReceiver( 4192): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/AndroidRuntime( 5369): Shutting down VM
,I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4192): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4192): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1019): List of disabled apps :
,D/Compatibility( 5100): onReceive() it will make start service
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5100): onHandleIntent()
D/Compatibility( 5100): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5100): found: 2
,D/Compatibility( 5100): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5100): skipping ResolveInfo{168c7e15 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5100): considering ResolveInfo{17a452a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5100): default: com.sec.android.app.soundalive.SAControlPanelActivity
,E/Zygote  ( 5402): MountEmulatedStorage()
I/libpersona( 5402): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5402): v2
I/libpersona( 5402): KNOX_SDCARD not a persona
,I/SELinux ( 5402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 5100): enabling receiver ResolveInfo{a9e6f1b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5402 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5402): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5100): enabling receiver ResolveInfo{1531b8b8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5100): enabling receiver ResolveInfo{2c3e691 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5100): enabling receiver ResolveInfo{2cf89f6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 5402): TimaSignature is unavailable
,D/ActivityThread( 5402): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5100): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/UserAnalysis.PlaceProvider( 5402): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 5402): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5402): SecurePlaceDbHelper() 
D/UserAnalysis( 5402): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5402): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5402): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 5139): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/IntelligenceServiceApplication( 5402): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 5419): MountEmulatedStorage()
E/Zygote  ( 5419): v2
I/libpersona( 5419): KNOX_SDCARD checking this for 1000
I/libpersona( 5419): KNOX_SDCARD not a persona
,I/SELinux ( 5419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5419 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 5419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5419): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Killing 4865:com.wssyncmldm/1000 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 5402): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/TimaKeyStoreProvider( 5419): TimaSignature is unavailable
,D/ActivityThread( 5419): Added TimaKeyStore provider
D/BluetoothAdapter( 5402): 727863170: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 5402): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
W/TextServicesManagerService( 1019): no available spell checker services found
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetection::stopService] Service stopped.
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/art     ( 5369): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/PlaceDetection v1.0.19 ( 5402): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/ResourcesManager( 5419): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManager( 5419):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1019):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5165): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello,
,W/ContextImpl( 5165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5165): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5165): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5165): before removeFromFS
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,E/Zygote  ( 5436): MountEmulatedStorage()
,E/Zygote  ( 5436): v2
I/libpersona( 5436): KNOX_SDCARD checking this for 10095
I/libpersona( 5436): KNOX_SDCARD not a persona
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/SELinux ( 5436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/SELinux ( 5436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SELinux ( 5436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5436 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 5436): TimaSignature is unavailable
,D/ActivityThread( 5436): Added TimaKeyStore provider
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 5450): MountEmulatedStorage()
I/libpersona( 5450): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5450): v2
I/libpersona( 5450): KNOX_SDCARD not a persona
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 5450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5450): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello,
D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
,W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4850/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_4865/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5450): TimaSignature is unavailable
,D/ActivityThread( 5450): Added TimaKeyStore provider

```
