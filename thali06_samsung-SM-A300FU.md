#### Test 502422853393492_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  297): DCD OFF
,I/ServiceManager(  335): Waiting for service AtCmdFwd...
D/AndroidRuntime( 5397): 
D/AndroidRuntime( 5397): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5397): CheckJNI is OFF
D/AndroidRuntime( 5397): readGMSProperty: start
D/AndroidRuntime( 5397): readGMSProperty: already setted!!
D/AndroidRuntime( 5397): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5397): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5397): readGMSProperty: end
D/AndroidRuntime( 5397): addProductProperty: start
E/AffinityControl( 5397): AffinityControl: registerfunction enter
D/AndroidRuntime( 5397): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1022): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5409 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/libpersona( 5409): KNOX_SDCARD checking this for 10345
D/InputDispatcher( 1022): Focused application set to: xxxx
I/libpersona( 5409): KNOX_SDCARD not a persona
D/InputDispatcher( 1022): Focus left window: 1481
E/Zygote  ( 5409): MountEmulatedStorage()
E/Zygote  ( 5409): v2
I/SELinux ( 5409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 5397): Shutting down VM
I/SELinux ( 5409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5409): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5409): TimaSignature is unavailable
D/ActivityThread( 5409): Added TimaKeyStore provider
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1022): Display changed displayId=0
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1481): updateVisibility : ActivityRecord{26ddf8eb token=android.os.BinderProxy@172805d4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1481): onTrimMemory. Level: 20
I/WebViewFactory( 5409): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5409): Time to load native libraries: 2 ms (timestamps 2712-2714)
I/LibraryLoader( 5409): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5409): Binding Chromium to main looper Looper (main, tid 1) {e49c3c9}
I/LibraryLoader( 5409): Expected native library version number "",actual native library version number ""
I/chromium( 5409): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5397): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 5409): Initializing chromium process, singleProcess=true
W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5409): ApplicationContext is null in ApplicationStatus
,W/chromium( 5409): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5409): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5409): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5409): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5409): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5409): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5409): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5409): Local Branch: 
I/Adreno-EGL( 5409): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5409): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5409):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5409): 414696922: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5409): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5409): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5409): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5409): CordovaWebView is running on device made by: samsung
W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5409): Attempt to remove local handle scope entry from IRT, ignoring
W/Atfwd_Sendcmd(  335): AtCmdFwd service not published, waiting... retryCnt : 5
W/ActivityManager( 1022): Activity pause timeout for ActivityRecord{2e508a6c u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5409): Render dirty regions requested: true
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
W/chromium( 5409): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5409): updateVisibility : ActivityRecord{29e35bfb token=android.os.BinderProxy@2457a7f5 {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5409): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5409): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1022): Focus entered window: 5409
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5409): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5409): Initialized EGL, version 1.4
D/OpenGLRenderer( 5409): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5409): Enabling debug mode 0
D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
I/Timeline( 5409): Timeline: Activity_idle id: android.os.BinderProxy@2457a7f5 time:83285
W/IInputConnectionWrapper( 5409): showStatusIcon on inactive InputConnection
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1756): getCurrentCandidateView
I/ActivityManager( 1022): Displayed Component not be shown by security: +694ms (total +771ms)
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{2e508a6c u0 com.example.hello/.MainActivity t19} time:83311
W/ActivityManager( 1022): mDVFSHelper.release()
I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
I/SurfaceFlinger(  259): id=11 Removed iello (-2/9)
W/BindingManager( 5409): Cannot call determinedVisibility() - never saw a connection for the pid: 5409
I/chromium( 5409): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SamsungIME( 1756): Dismiss ExpandCandiate
I/SamsungIME( 1756): getDebugLevel  : 0x4f4c
I/SamsungIME( 1756): getDebugLevel  : 0x4f4c
I/SamsungIME( 1756): KeybaordView init() : load resources
D/JsMessageQueue( 5409): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1756): getCurrentKeyboard
I/SamsungIME( 1756): getTextKeyboard
E/AndroidProtocolHandler( 5409): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/SamsungIME( 1756): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 5409): JniHelper::setJavaVM(0xb8844448), pthread_self() = -1193615744
D/JX-Cordova( 5409): jxcore cordova android initializing
W/jxcore-log( 5409): Initializing JXcore engine
W/jxcore-log( 5409): JXcore engine is ready
W/jxcore-log( 5409): Starting JXcore engine
E/audit   ( 1800): type=1400 msg=audit(1449413997.982:203): avc:  denied  { ioctl } for  pid=5409 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1800):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1800): type=1300 msg=audit(1449413997.982:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=bec11d58 items=0 ppid=323 ppcomm=main pid=5409 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1800): type=1320 msg=audit(1449413997.982:203): 
W/jxcore-log( 5409): Platform android
W/jxcore-log( 5409): 
W/jxcore-log( 5409): Process ARCH arm
W/jxcore-log( 5409): 
I/jxcore-log( 5409): JXcore Cordova bridge is ready!
I/jxcore-log( 5409): 
W/jxcore-log( 5409): JXcore engine is started
E/jxcore-log( 5409): >> samsung-SM-A300FU
E/jxcore-log( 5409): 
I/jxcore-log( 5409): Total memory 1451114496
I/jxcore-log( 5409): 
I/jxcore-log( 5409): Free memory 24920064
I/jxcore-log( 5409): 
I/jxcore-log( 5409): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5409): 
I/jxcore-log( 5409): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5409): 
I/jxcore-log( 5409): userPath [ 'www' ]
I/jxcore-log( 5409): 
I/jxcore-log( 5409): Size 540 960
I/jxcore-log( 5409): 
I/jxcore-log( 5409): Screen Brightness 160
I/jxcore-log( 5409): 
E/jxcore-log( 5409): Dummy Error Log.
E/jxcore-log( 5409): 
I/jxcore-log( 5409): getBuffer is called!!!!
I/jxcore-log( 5409): 
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  297): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate,
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  297): DCD OFF
,D/BluetoothAdapter( 5409): disable()
,E/BluetoothManagerService( 1022): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1022): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1022): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1022): mCursor = null
,D/WifiService( 1022): setWifiEnabled: false pid=5409, uid=10345
,D/SettingsProvider( 1022): name = wifi_on
,I/jxcore-log( 5409): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 5409): 
,I/jxcore-log( 5409): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5409): 
,D/AndroidRuntime( 5459): ,
D/AndroidRuntime( 5459): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5459): CheckJNI is OFF
,D/AndroidRuntime( 5459): readGMSProperty: start
D/AndroidRuntime( 5459): readGMSProperty: already setted!!
,D/AndroidRuntime( 5459): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5459): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5459): readGMSProperty: end
D/AndroidRuntime( 5459): addProductProperty: start
,E/AffinityControl( 5459): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5459): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1022): START PACKAGE DELETE: observer{850490614}
D/PackageManager( 1022): pkg{<packageName>}
D/PackageManager( 1022): user{0}
,D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{3}
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true,
,D/PackageManager( 1022): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
D/PackageManager( 1022): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1022): !@killApplicatoin: 10345, uninstall pkg,
D/PackageManagerService( 1022): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1022): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1022): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 5409:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1022): Skipping PackageSetting{2b1a26a9 com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{2e508a6c u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1022): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1022): Focus left window: 5409
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1022): Focused application released
E/JavaBinder( 1022): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1022): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3595): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 674us total 21.273ms
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 5315): Explicit concurrent mark sweep GC freed 36(13KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 730us total 35.852ms
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1756): mOCRHelper is null
,W/GeofencerStateMachine( 1647): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3359): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sun Dec 06 16:00:03 GMT+01:00 2015
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3359): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1022): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1022): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1022): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5471): MountEmulatedStorage()
I/libpersona( 5471): KNOX_SDCARD checking this for 10090
E/Zygote  ( 5471): v2
I/libpersona( 5471): KNOX_SDCARD not a persona
,I/SELinux ( 5471): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5471): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5471 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 5471): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3359): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3359): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/TimaKeyStoreProvider( 5471): TimaSignature is unavailable
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): PACKAGE_REMOVED
,D/ActivityThread( 5471): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 27686(2008KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/34MB, paused 3.287ms total 177.299ms
,I/art     ( 1022): WaitForGcToComplete blocked for 112.251ms for cause Explicit
,D/RegisteredServicesCache( 1450): empty dynamic service
,D/elm:15121( 5471): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5471): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5471): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/RCPManagerService( 1022): PackageReceiver onReceive()
,I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:15121( 5471): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5471): ElmAgentService : onCreate()
,D/elm:15121( 5471): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5471): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5471): MDMBridge.getInstance()
,D/elm:15121( 5471): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5471): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3359): KLMSIntentService(): onDestroy()
,D/elm:15121( 5471): ElmAgentService : onDestroy().
,I/ActivityManager( 1022): Killing 4877:com.wssyncmldm/1000 (adj 15): empty #31
,D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10345
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1022): no available spell checker services found
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1022): removeObsoleteFile: deleting file=19_task.xml
,D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1022): uID is 10345
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 13027(744KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.972ms total 180.550ms
,I/PCWCLIENTTRACE_PushUtil( 5030): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5030): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5030): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5030): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5119): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5119): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4349): PackagesMonitor onReceive :com.example.hello
,D/Mms/FreeMessageStatusReceiver( 4978): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1022): enable value -1
,I/TactileAssist( 1022): internal enable value -1
I/TactileAssist( 1022): intensity value -1
I/TactileAssist( 1022): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4978): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4978): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1022): List of disabled apps :
,W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 5208): onReceive() it will make start service
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1022): delete codoeFile: 
,I/AASA_removePackage( 1022): UID=10345 Target=com.example.hello
D/AASAuninstall( 1022): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
D/PackageManager( 1022): result of delete: 1{850490614}
,D/AndroidRuntime( 5459): Shutting down VM
D/Compatibility( 5208): onHandleIntent()
,D/Compatibility( 5208): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5208): found: 2
D/Compatibility( 5208): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5208): skipping ResolveInfo{1621d385 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5208): considering ResolveInfo{18b7c5da com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5208): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5208): enabling receiver ResolveInfo{2523da0b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 5492): MountEmulatedStorage()
E/Zygote  ( 5492): v2
I/libpersona( 5492): KNOX_SDCARD checking this for 10055
I/libpersona( 5492): KNOX_SDCARD not a persona
,I/SELinux ( 5492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/SELinux ( 5492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5492 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 5208): enabling receiver ResolveInfo{2c3560e8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SELinux ( 5492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Compatibility( 5208): enabling receiver ResolveInfo{31b12301 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 5208): enabling receiver ResolveInfo{34dc65a6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Compatibility( 5208): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1022): clearDefaults: com.example.hello
I/CrashAnrDetector( 1022): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_4877/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 5492): TimaSignature is unavailable
,D/ActivityThread( 5492): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 5492): PlaceProvider onCreate()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/UserAnalysis.SecureDbManager( 5492): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5492): SecurePlaceDbHelper() 
D/UserAnalysis( 5492): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5492): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5492): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 5228): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/IntelligenceServiceApplication( 5492): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::stopService] Service stopped.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 5509): MountEmulatedStorage()
,E/Zygote  ( 5509): v2
I/libpersona( 5509): KNOX_SDCARD checking this for 1000
I/libpersona( 5509): KNOX_SDCARD not a persona
I/SELinux ( 5509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5509 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Killing 4898:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 5492): 626603570: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 5492): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 5492): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
I/art     (  323): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 624us total 28.275ms
D/TimaKeyStoreProvider( 5509): TimaSignature is unavailable
D/ActivityThread( 5509): Added TimaKeyStore provider
,W/ResourcesManager( 5509): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.821ms
,D/RCPManager( 5509):  in createShortcut() for packageName: com.example.hello userId0
,W/art     ( 5459): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.272ms total 18.942ms
,D/RCPManagerService( 1022):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1022): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5248): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,W/ContextImpl( 5248): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/FilterInstaller( 5248): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5248): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 5248): before removeFromFS
,I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5526 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 5526): MountEmulatedStorage()
I/libpersona( 5526): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5526): v2
I/libpersona( 5526): KNOX_SDCARD not a persona
I/SELinux ( 5526): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 5526): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5526): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 5540): MountEmulatedStorage()
,E/Zygote  ( 5540): v2
I/libpersona( 5540): KNOX_SDCARD checking this for 10095
,I/libpersona( 5540): KNOX_SDCARD not a persona
I/SELinux ( 5540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5540 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
D/TimaKeyStoreProvider( 5526): TimaSignature is unavailable
W/libprocessgroup( 1022): failed to open /acct/uid_10139/pid_4898/cgroup.procs: No such file or directory
,D/ActivityThread( 5526): Added TimaKeyStore provider
,I/SELinux ( 5540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5540): TimaSignature is unavailable
D/ActivityThread( 5540): Added TimaKeyStore provider
,W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/PreloadFilterInstaller( 5540): uses FILTER_DB_VER_1
,E/SQLiteLog( 5540): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteLog( 5526): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5540): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 5540): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 5540): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 5540): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 5540): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 5540): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 5540): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 5540): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 5540): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 5540): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 5540): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 5540): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 5540): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5540): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5540): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5540): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5540): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5540): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5540): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 5540): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 5540): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 5540): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 5540): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 5540): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 5540): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 5540): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 5540): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 5540): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 5540): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 5540): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 5540): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 5540): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 5540): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 5540): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 5540): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 5540): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 5540): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 5540): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 5540): Opened filter.db in read-only mode
E/Zygote  ( 5558): MountEmulatedStorage()
E/Zygote  ( 5558): v2
I/libpersona( 5558): KNOX_SDCARD checking this for 1000
I/libpersona( 5558): KNOX_SDCARD not a persona
I/SELinux ( 5558): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
E/SQLiteLog( 5540): (284) automatic index on titles(filter_id)
,E/SQLiteDatabase( 5526): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.,
E/SQLiteDatabase( 5526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5526): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5526): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5526): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5526): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 5526): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 5526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5526): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 5526): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5526): Process: com.android.keychain, PID: 5526
E/AndroidRuntime( 5526): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 5526): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 5526): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 5526): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5526): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5526): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 5526): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 5526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5526): 	at android.os.Looper.loop(Looper.java:145)
,E/AndroidRuntime( 5526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 5558): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5558 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 5558): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,I/Process ( 5526): Sending signal. PID: 5526 SIG: 9
,E/SQLiteLog( 5540): (284) automatic index on titles(filter_id)
,E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop162.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1022): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1022): 	... 5 more
,D/TimaKeyStoreProvider( 5558): TimaSignature is unavailable
,D/ActivityThread( 5558): Added TimaKeyStore provider

```
