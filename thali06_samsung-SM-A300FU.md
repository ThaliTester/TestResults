#### Test 503880196dc97cd_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4801/cgroup.procs: No such file or directory
,--------- beginning of main
D/AndroidRuntime( 5341): 
D/AndroidRuntime( 5341): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5341): CheckJNI is OFF
D/AndroidRuntime( 5341): readGMSProperty: start
D/AndroidRuntime( 5341): readGMSProperty: already setted!!
D/AndroidRuntime( 5341): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5341): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5341): readGMSProperty: end
D/AndroidRuntime( 5341): addProductProperty: start
E/SQLiteLog( 1604): (10) POSIX Error : 11 SQLite Error : 3850
E/AffinityControl( 5341): AffinityControl: registerfunction enter
D/AndroidRuntime( 5341): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5353): MountEmulatedStorage()
E/Zygote  ( 5353): v2
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5353 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1016): Focused application set to: xxxx
I/libpersona( 5353): KNOX_SDCARD checking this for 10345
D/InputDispatcher( 1016): Focus left window: 1473
I/libpersona( 5353): KNOX_SDCARD not a persona
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, iello
D/AndroidRuntime( 5341): Shutting down VM
I/SELinux ( 5353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5353): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5353): TimaSignature is unavailable
D/ActivityThread( 5353): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1016): Display changed displayId=0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1473): updateVisibility : ActivityRecord{2358af9f token=android.os.BinderProxy@42cdf1b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1473): onTrimMemory. Level: 20
I/WebViewFactory( 5353): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5353): Time to load native libraries: 1 ms (timestamps 3716-3717)
I/LibraryLoader( 5353): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5353): Binding Chromium to main looper Looper (main, tid 1) {32bf77f4}
I/LibraryLoader( 5353): Expected native library version number "",actual native library version number ""
I/chromium( 5353): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5341): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 5353): Initializing chromium process, singleProcess=true
W/art     ( 5353): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5353): ApplicationContext is null in ApplicationStatus
W/chromium( 5353): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5353): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5353): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5353): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5353): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5353): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5353): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5353): Local Branch: 
I/Adreno-EGL( 5353): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5353): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5353):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
D/BluetoothAdapter( 5353): 729467929: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5353): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5353): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5353): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5353): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5353): CordovaWebView is running on device made by: samsung
W/art     ( 5353): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5353): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{29b9f3ef u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5353): Render dirty regions requested: true
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
W/chromium( 5353): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5353): updateVisibility : ActivityRecord{900118e token=android.os.BinderProxy@27602090 {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5353): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5353): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1016): Focus entered window: 5353
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5353): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5353): Initialized EGL, version 1.4
D/OpenGLRenderer( 5353): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5353): Enabling debug mode 0
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5353): showStatusIcon on inactive InputConnection
I/SamsungIME( 1801): getCurrentCandidateView
I/Timeline( 5353): Timeline: Activity_idle id: android.os.BinderProxy@27602090 time:84253
I/ActivityManager( 1016): Displayed Component not be shown by security: +657ms (total +730ms)
W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{29b9f3ef u0 com.example.hello/.MainActivity t19} time:84273
I/SurfaceFlinger(  258): id=11 Removed iello (7/9)
I/SurfaceFlinger(  258): id=11 Removed iello (-2/9)
D/SamsungIME( 1801): Dismiss ExpandCandiate
I/SamsungIME( 1801): getDebugLevel  : 0x4f4c
I/SamsungIME( 1801): getDebugLevel  : 0x4f4c
I/SamsungIME( 1801): KeybaordView init() : load resources
W/BindingManager( 5353): Cannot call determinedVisibility() - never saw a connection for the pid: 5353
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1801): getCurrentKeyboard
I/SamsungIME( 1801): getTextKeyboard
I/chromium( 5353): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SamsungIME( 1801): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5353): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5353): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 5353): JniHelper::setJavaVM(0xb825a448), pthread_self() = -1199908336
D/JX-Cordova( 5353): jxcore cordova android initializing
W/jxcore-log( 5353): Initializing JXcore engine
W/jxcore-log( 5353): JXcore engine is ready
W/jxcore-log( 5353): Starting JXcore engine
E/audit   ( 1798): type=1400 msg=audit(1448460707.225:203): avc:  denied  { ioctl } for  pid=5353 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1798):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1798): type=1300 msg=audit(1448460707.225:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bea58d58 items=0 ppid=314 ppcomm=main pid=5353 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1798): type=1320 msg=audit(1448460707.225:203): 
W/jxcore-log( 5353): Platform android
W/jxcore-log( 5353): 
W/jxcore-log( 5353): Process ARCH arm
W/jxcore-log( 5353): 
I/jxcore-log( 5353): JXcore Cordova bridge is ready!
I/jxcore-log( 5353): 
W/jxcore-log( 5353): JXcore engine is started
E/jxcore-log( 5353): >> samsung-SM-A300FU
E/jxcore-log( 5353): 
I/jxcore-log( 5353): Total memory 1451114496
I/jxcore-log( 5353): 
I/jxcore-log( 5353): Free memory 21381120
I/jxcore-log( 5353): 
I/jxcore-log( 5353): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5353): 
I/jxcore-log( 5353): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5353): 
I/jxcore-log( 5353): userPath [ 'www' ]
I/jxcore-log( 5353): 
I/jxcore-log( 5353): Size 540 960
I/jxcore-log( 5353): 
I/jxcore-log( 5353): Screen Brightness 160
I/jxcore-log( 5353): 
E/jxcore-log( 5353): Dummy Error Log.
E/jxcore-log( 5353): 
E/SMD     (  289): DCD OFF
,I/jxcore-log( 5353): getBuffer is called!!!!
I/jxcore-log( 5353): 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 5353): disable()
,E/BluetoothManagerService( 1016): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: false pid=5353, uid=10345
,D/SettingsProvider( 1016): name = wifi_on
,I/jxcore-log( 5353): ****TEST TOOK:  5071  ms ****
I/jxcore-log( 5353): 
,I/jxcore-log( 5353): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5353): 
,D/AndroidRuntime( 5404): ,
D/AndroidRuntime( 5404): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5404): CheckJNI is OFF,
D/AndroidRuntime( 5404): readGMSProperty: start,
D/AndroidRuntime( 5404): readGMSProperty: already setted!!
D/AndroidRuntime( 5404): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5404): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5404): readGMSProperty: end
,D/AndroidRuntime( 5404): addProductProperty: start
,E/AffinityControl( 5404): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5404): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{291613665}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1016): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 5353:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{868c9c0 com.test.thalitest/10338} due to missing metadata
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/8),
,I/WindowState( 1016): WIN DEATH: Window{212990a9 u0 com.example.hello/com.example.hello.MainActivity},
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focus left window: 5353
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{29b9f3ef u0 com.example.hello/.MainActivity t19}
,W/ActivityManager( 1016): Spurious death for ProcessRecord{39faed06 5353:com.example.hello/u0a345}, curProc for 5353: null
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{29b9f3ef u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1016): Duplicate finish request for ActivityRecord{29b9f3ef u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1016): Focused application released
,I/art     ( 3649): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 796us total 28.084ms
,I/art     ( 5254): Explicit concurrent mark sweep GC freed 347(25KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 859us total 50.034ms
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1801): mOCRHelper is null
,W/GeofencerStateMachine( 1513): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3405): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 25 15:11:53 GMT+01:00 2015
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3405): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1016): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5418): MountEmulatedStorage()
E/Zygote  ( 5418): v2
I/libpersona( 5418): KNOX_SDCARD checking this for 10090
I/libpersona( 5418): KNOX_SDCARD not a persona
I/SELinux ( 5418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5418 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 5418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5418): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3405): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3405): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/TimaKeyStoreProvider( 5418): TimaSignature is unavailable
,D/ActivityThread( 5418): Added TimaKeyStore provider
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 29543(2MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 2.276ms total 176.949ms
,I/art     ( 1016): WaitForGcToComplete blocked for 171.770ms for cause Explicit
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): listeningToPackageRemoved().START
,D/RegisteredServicesCache( 1436): empty dynamic service
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/elm:15121( 5418): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:15121( 5418): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5418): MDMBridge.setEnterpriseBridge()
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5418): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 5418): ElmAgentService : onCreate()
,D/elm:15121( 5418): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5418): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5418): MDMBridge.getInstance()
D/elm:15121( 5418): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5418): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5418): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Killing 4819:com.wssyncmldm/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3405): KLMSIntentService(): onDestroy()
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10345
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10345
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
D/TaskPersister( 1016): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 11100(664KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.773ms total 185.907ms
,I/PCWCLIENTTRACE_PushUtil( 4973): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 4973): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4973): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4973): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5062): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5062): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/PackageManager( 1016): delete codoeFile: 
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1016): UID=10345 Target=com.example.hello
,D/PackageManager( 1016): result of delete: 1{291613665}
,D/AndroidRuntime( 5404): Shutting down VM
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4308): PackagesMonitor onReceive :com.example.hello
,D/Mms/FreeMessageStatusReceiver( 4918): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4918): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4918): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1016): List of disabled apps :
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5144): onReceive() it will make start service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD OFF
,D/Compatibility( 5144): onHandleIntent()
,E/Zygote  ( 5438): MountEmulatedStorage()
D/Compatibility( 5144): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/libpersona( 5438): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5438): v2
I/libpersona( 5438): KNOX_SDCARD not a persona
I/SELinux ( 5438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/Compatibility( 5144): found: 2
,D/Compatibility( 5144): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5144): skipping ResolveInfo{19561f60 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5144): considering ResolveInfo{2b7acc19 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5144): default: com.sec.android.app.soundalive.SAControlPanelActivity
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5438 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5144): enabling receiver ResolveInfo{21ceb4de com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
W/TextServicesManagerService( 1016): no available spell checker services found
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,D/Compatibility( 5144): enabling receiver ResolveInfo{21d2d6bf com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 5144): enabling receiver ResolveInfo{3aedd18c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 5144): enabling receiver ResolveInfo{2b6310d5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 5438): TimaSignature is unavailable
,D/ActivityThread( 5438): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/Compatibility( 5144): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/UserAnalysis.PlaceProvider( 5438): PlaceProvider onCreate(),
,W/art     ( 5404): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/UserAnalysis.SecureDbManager( 5438): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5438): SecurePlaceDbHelper() 
D/UserAnalysis( 5438): Create SecureDbHelper
,D/SSRM:n  ( 1016): SIOP:: AP = 310
,D/IntelligenceServiceApplication( 5438): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5438): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/ContextImpl( 5169): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/IntelligenceServiceApplication( 5438): no applications having user consent for prediction
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 5456): MountEmulatedStorage(),
W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/Zygote  ( 5456): v2
I/SELinux ( 5456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 5456): KNOX_SDCARD checking this for 1000
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 5456): KNOX_SDCARD not a persona
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 5456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 5456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
I/ActivityManager( 1016): Killing 4840:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 5438): 139519313: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 5438): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5438): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5438): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/TimaKeyStoreProvider( 5456): TimaSignature is unavailable
,D/ActivityThread( 5456): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ResourcesManager( 5456): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/CrashAnrDetector( 1016): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 1016): clearDefaults: com.example.hello
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4819/cgroup.procs: No such file or directory
,E/SQLiteLog( 5438): (10) unixWrite() File Descriptor : 26 gets errno : 9
,E/SQLiteDatabase( 5438): Error inserting timestamp=1448460713787 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 5438): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 5438): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5438): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5438): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5438): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5438): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 5438): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 5438): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 5438): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5438): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5438): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5438): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5438): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5438): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5438): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5438): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5438): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 5438): It failed to insert to dump_log table
,D/RCPManager( 5456):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1016):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5187): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5187): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5187): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5187): before removeFromFS
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5474): MountEmulatedStorage()
,E/Zygote  ( 5474): v2
I/libpersona( 5474): KNOX_SDCARD checking this for 10095
I/libpersona( 5474): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5474 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_4840/cgroup.procs: No such file or directory
,I/SELinux ( 5474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 5474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5474): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5474): TimaSignature is unavailable,
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/ActivityThread( 5474): Added TimaKeyStore provider
,E/Zygote  ( 5484): MountEmulatedStorage()
I/libpersona( 5484): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5484): v2
I/libpersona( 5484): KNOX_SDCARD not a persona
,I/SELinux ( 5484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5484): TimaSignature is unavailable
,D/ActivityThread( 5484): Added TimaKeyStore provider
,D/PreloadFilterInstaller( 5474): uses FILTER_DB_VER_1

```
