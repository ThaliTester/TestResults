#### Test 50242285576d0b0_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
E/SMD     (  289): DCD OFF
,D/AndroidRuntime( 5396): 
D/AndroidRuntime( 5396): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5396): CheckJNI is OFF
D/AndroidRuntime( 5396): readGMSProperty: start
D/AndroidRuntime( 5396): readGMSProperty: already setted!!
D/AndroidRuntime( 5396): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5396): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5396): readGMSProperty: end
D/AndroidRuntime( 5396): addProductProperty: start
E/AffinityControl( 5396): AffinityControl: registerfunction enter
D/AndroidRuntime( 5396): Calling main entry com.android.commands.am.Am
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
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5408 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1478
E/Zygote  ( 5408): MountEmulatedStorage()
E/Zygote  ( 5408): v2
I/libpersona( 5408): KNOX_SDCARD checking this for 10345
D/AndroidRuntime( 5396): Shutting down VM
I/libpersona( 5408): KNOX_SDCARD not a persona
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
I/SELinux ( 5408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5408): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
D/TimaKeyStoreProvider( 5408): TimaSignature is unavailable
D/ActivityThread( 5408): Added TimaKeyStore provider
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1020): Display changed displayId=0
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1478): updateVisibility : ActivityRecord{3e09ddc5 token=android.os.BinderProxy@275b3ac6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1478): onTrimMemory. Level: 20
I/WebViewFactory( 5408): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5408): Time to load native libraries: 1 ms (timestamps 6246-6247)
I/LibraryLoader( 5408): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5408): Binding Chromium to main looper Looper (main, tid 1) {1fc7a4f3}
I/LibraryLoader( 5408): Expected native library version number "",actual native library version number ""
I/chromium( 5408): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5408): Initializing chromium process, singleProcess=true
W/art     ( 5408): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5408): ApplicationContext is null in ApplicationStatus
W/art     ( 5396): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5408): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5408): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5408): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5408): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5408): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5408): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5408): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5408): Local Branch: 
I/Adreno-EGL( 5408): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5408): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5408):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5408): 238100965: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5408): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5408): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5408): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5408): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5408): CordovaWebView is running on device made by: samsung
,W/art     ( 5408): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5408): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5408): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 5408): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5408): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5408): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 5408
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5408): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5408): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5408): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5408): Enabling debug mode 0
,V/ActivityThread( 5408): updateVisibility : ActivityRecord{9874e55 token=android.os.BinderProxy@3856783f {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): There is/are notification(s) 
,W/IInputConnectionWrapper( 5408): showStatusIcon on inactive InputConnection
I/Timeline( 5408): Timeline: Activity_idle id: android.os.BinderProxy@3856783f time:86767
,I/ActivityManager( 1020): Displayed Component not be shown by security: +627ms (total +706ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{2188ab26 u0 com.example.hello/.MainActivity t19} time:86782
,I/SurfaceFlinger(  257): id=11 Removed iello (7/9)
,I/SurfaceFlinger(  257): id=11 Removed iello (-2/9)
,I/SamsungIME( 1791): getCurrentCandidateView
,D/SamsungIME( 1791): Dismiss ExpandCandiate
,I/SamsungIME( 1791): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1791): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1791): KeybaordView init() : load resources
,W/BindingManager( 5408): Cannot call determinedVisibility() - never saw a connection for the pid: 5408
,I/SamsungIME( 1791): getCurrentKeyboard
I/SamsungIME( 1791): getTextKeyboard
,I/chromium( 5408): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/SamsungIME( 1791): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5408): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5408): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5408): JniHelper::setJavaVM(0xb8a01448), pthread_self() = -1191684672
,D/JX-Cordova( 5408): jxcore cordova android initializing
,W/jxcore-log( 5408): Initializing JXcore engine
W/jxcore-log( 5408): JXcore engine is ready
,W/jxcore-log( 5408): Starting JXcore engine
,E/audit   ( 1788): type=1400 msg=audit(1449410995.362:203): avc:  denied  { ioctl } for  pid=5408 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1788):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1788): type=1300 msg=audit(1449410995.362:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=becf9d58 items=0 ppid=304 ppcomm=main pid=5408 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1788): type=1320 msg=audit(1449410995.362:203): 
,W/jxcore-log( 5408): Platform android
W/jxcore-log( 5408): 
W/jxcore-log( 5408): Process ARCH arm
W/jxcore-log( 5408): 
,I/jxcore-log( 5408): JXcore Cordova bridge is ready!
I/jxcore-log( 5408): 
,W/jxcore-log( 5408): JXcore engine is started
,E/jxcore-log( 5408): >> samsung-SM-A300FU
E/jxcore-log( 5408): 
,I/jxcore-log( 5408): Total memory 1451114496
I/jxcore-log( 5408): 
,I/jxcore-log( 5408): Free memory 22867968
I/jxcore-log( 5408): 
I/jxcore-log( 5408): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5408): 
I/jxcore-log( 5408): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5408): 
,I/jxcore-log( 5408): userPath [ 'www' ]
I/jxcore-log( 5408): 
,I/jxcore-log( 5408): Size 540 960
I/jxcore-log( 5408): 
,I/jxcore-log( 5408): Screen Brightness 160
I/jxcore-log( 5408): 
,E/jxcore-log( 5408): Dummy Error Log.
E/jxcore-log( 5408): 
,I/jxcore-log( 5408): getBuffer is called!!!!
I/jxcore-log( 5408): 
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,D/BluetoothAdapter( 5408): disable()
,E/BluetoothManagerService( 1020): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1020): mCursor = null
,D/WifiService( 1020): setWifiEnabled: false pid=5408, uid=10345
,D/SettingsProvider( 1020): name = wifi_on
,I/jxcore-log( 5408): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 5408): 
,I/jxcore-log( 5408): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5408): 
,D/AndroidRuntime( 5460): ,
D/AndroidRuntime( 5460): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5460): CheckJNI is OFF,
D/AndroidRuntime( 5460): readGMSProperty: start
D/AndroidRuntime( 5460): readGMSProperty: already setted!!
D/AndroidRuntime( 5460): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5460): readGMSProperty: could not set the property(default)!!,
D/AndroidRuntime( 5460): readGMSProperty: end
D/AndroidRuntime( 5460): addProductProperty: start
,E/AffinityControl( 5460): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5460): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1020): START PACKAGE DELETE: observer{1034697952}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10345, uninstall pkg
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 5408:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/SurfaceFlinger(  257): id=12 Removed NainActivit (6/8),
I/WindowState( 1020): WIN DEATH: Window{2f409cc8 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  257): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focus left window: 5408,
,W/PackageSettings( 1020): Skipping PackageSetting{1aa0153c com.test.thalitest/10338} due to missing metadata
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{2188ab26 u0 com.example.hello/.MainActivity t19}
,W/ActivityManager( 1020): Spurious death for ProcessRecord{32225b99 5408:com.example.hello/u0a345}, curProc for 5408: null
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{2188ab26 u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{2188ab26 u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1020): Focused application released
,I/art     ( 3643): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 672us total 25.517ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5290): Explicit concurrent mark sweep GC freed 2162(125KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 655us total 37.248ms
,E/SamsungIME( 1791): mOCRHelper is null
,W/GeofencerStateMachine( 1636): Ignoring removeGeofence because network location is disabled.
,I/art     ( 4129): Explicit concurrent mark sweep GC freed 19593(1245KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.428ms total 52.931ms
,I/KLMS-2.5.123: ( 3382): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Dec 06 15:10:01 GMT+01:00 2015
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3382): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): onCreate()
,E/Zygote  ( 5473): MountEmulatedStorage()
E/Zygote  ( 5473): v2
I/libpersona( 5473): KNOX_SDCARD checking this for 10090
I/libpersona( 5473): KNOX_SDCARD not a persona
,I/SELinux ( 5473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3382): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5473 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/KLMS-2.5.123: ( 3382): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): PACKAGE_REMOVED
D/TimaKeyStoreProvider( 5473): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3382): KLMSIntentService(): listeningToPackageRemoved().START
D/ActivityThread( 5473): Added TimaKeyStore provider
I/art     ( 1020): Explicit concurrent mark sweep GC freed 25256(1900KB) AllocSpace objects, 18(288KB) LOS objects, 33% free, 23MB/34MB, paused 2.326ms total 170.056ms
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,I/art     ( 1020): WaitForGcToComplete blocked for 172.109ms for cause Explicit
,D/RegisteredServicesCache( 1441): empty dynamic service
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5473): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5473): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5473): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5473): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 5473): ElmAgentService : onCreate()
,D/elm:15121( 5473): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5473): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5473): MDMBridge.getInstance()
,D/elm:15121( 5473): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5473): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): onDestroy()
,D/elm:15121( 5473): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 4912:com.wssyncmldm/1000 (adj 15): empty #31
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
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10345
D/TaskPersister( 1020): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 9380(515KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.826ms total 164.961ms
I/PCWCLIENTTRACE_PushUtil( 5068): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5068): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5068): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5068): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/PackageManager( 1020): delete codoeFile: 
,I/SA      ( 5156): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5156): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1020): UID=10345 Target=com.example.hello
,D/PackageManager( 1020): result of delete: 1{1034697952},
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,D/AndroidRuntime( 5460): Shutting down VM
,I/PackagesMonitor( 4379): PackagesMonitor onReceive :com.example.hello
,D/Mms/FreeMessageStatusReceiver( 5012): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,D/Mms/FreeMessageReceiverService( 5012): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 5012): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1020): enable value -1
I/TactileAssist( 1020): internal enable value -1
I/TactileAssist( 1020): intensity value -1
I/TactileAssist( 1020): saveAppList value true
,I/TactileAssist( 1020): List of disabled apps :
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5246): onReceive() it will make start service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5246): onHandleIntent()
,D/Compatibility( 5246): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}],
,D/Compatibility( 5246): found: 2
,D/Compatibility( 5246): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5246): skipping ResolveInfo{52d9d4f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5246): considering ResolveInfo{14743cdc com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5246): default: com.sec.android.app.soundalive.SAControlPanelActivity
,E/Zygote  ( 5493): MountEmulatedStorage()
,D/Compatibility( 5246): enabling receiver ResolveInfo{e3121e5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 5493): v2
I/libpersona( 5493): KNOX_SDCARD checking this for 10055
I/libpersona( 5493): KNOX_SDCARD not a persona
,I/SELinux ( 5493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5493 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/SELinux ( 5493): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5246): enabling receiver ResolveInfo{1f5d64ba com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5246): enabling receiver ResolveInfo{3150bf6b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5246): enabling receiver ResolveInfo{11764ac8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 5493): TimaSignature is unavailable
,D/Compatibility( 5246): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/ActivityThread( 5493): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 5493): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 5493): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5493): SecurePlaceDbHelper() 
D/UserAnalysis( 5493): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5493): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5493): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ContextImpl( 5272): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 5493): no applications having user consent for prediction
,W/art     ( 5460): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 5510): MountEmulatedStorage()
,E/Zygote  ( 5510): v2
I/libpersona( 5510): KNOX_SDCARD checking this for 1000
I/libpersona( 5510): KNOX_SDCARD not a persona
,I/SELinux ( 5510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5510 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Killing 4935:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/SELinux ( 5510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/TimaKeyStoreProvider( 5510): TimaSignature is unavailable
,D/ActivityThread( 5510): Added TimaKeyStore provider
,D/BluetoothAdapter( 5493): 520702836: getState() :  mService = null. Returning STATE_OFF
,V/PlaceDetection v1.0.19 ( 5493): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 5493): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/ResourcesManager( 5510): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,D/RCPManager( 5510):  in createShortcut() for packageName: com.example.hello userId0,
,D/RCPManagerService( 1020):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1020): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5290): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5290): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5290): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5290): FilterPackageService : ACTION_REMOVED,
D/FilterUnInstaller( 5290): before removeFromFS
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5528): MountEmulatedStorage()
,E/Zygote  ( 5528): v2
I/libpersona( 5528): KNOX_SDCARD checking this for 10095
I/libpersona( 5528): KNOX_SDCARD not a persona
,I/SELinux ( 5528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
E/SELinux ( 5528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5528 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/Zygote  ( 5538): MountEmulatedStorage()
I/libpersona( 5538): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5538): v2
I/libpersona( 5538): KNOX_SDCARD not a persona
I/SELinux ( 5538): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 5528): TimaSignature is unavailable
,D/ActivityThread( 5528): Added TimaKeyStore provider
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5538 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5538): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5538): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,

```
