#### Test 50242285e132180_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  290): DCD OFF
I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 5297): 
D/AndroidRuntime( 5297): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5297): CheckJNI is OFF
D/AndroidRuntime( 5297): readGMSProperty: start
D/AndroidRuntime( 5297): readGMSProperty: already setted!!
D/AndroidRuntime( 5297): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5297): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5297): readGMSProperty: end
D/AndroidRuntime( 5297): addProductProperty: start
W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
E/AffinityControl( 5297): AffinityControl: registerfunction enter
D/AndroidRuntime( 5297): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 5309): MountEmulatedStorage()
E/Zygote  ( 5309): v2
I/libpersona( 5309): KNOX_SDCARD checking this for 10345
I/libpersona( 5309): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5309 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/SELinux ( 5309): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1477
D/AndroidRuntime( 5297): Shutting down VM
I/SELinux ( 5309): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5309): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, iello
D/TimaKeyStoreProvider( 5309): TimaSignature is unavailable
D/ActivityThread( 5309): Added TimaKeyStore provider
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=8 Removed Mauncher (-2/9)
D/Launcher( 1477): onTrimMemory. Level: 20
V/ActivityThread( 1477): updateVisibility : ActivityRecord{9fe5cfb token=android.os.BinderProxy@25a2cc37 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/WebViewFactory( 5309): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5309): Time to load native libraries: 1 ms (timestamps 3436-3437)
I/LibraryLoader( 5309): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5309): Binding Chromium to main looper Looper (main, tid 1) {6b22459}
I/LibraryLoader( 5309): Expected native library version number "",actual native library version number ""
I/chromium( 5309): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5309): Initializing chromium process, singleProcess=true
W/art     ( 5309): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5309): ApplicationContext is null in ApplicationStatus
W/chromium( 5309): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/art     ( 5297): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5309): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5309): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5309): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5309): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5309): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5309): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5309): Local Branch: 
I/Adreno-EGL( 5309): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5309): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5309):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5309): 256854058: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5309): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5309): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5309): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5309): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5309): CordovaWebView is running on device made by: samsung
W/art     ( 5309): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5309): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{2344d43c u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5309): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/chromium( 5309): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5309): updateVisibility : ActivityRecord{34b15c0b token=android.os.BinderProxy@39bf0585 {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5309): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5309): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 5309
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5309): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5309): Initialized EGL, version 1.4
D/OpenGLRenderer( 5309): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5309): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5309): showStatusIcon on inactive InputConnection
I/Timeline( 5309): Timeline: Activity_idle id: android.os.BinderProxy@39bf0585 time:84001
I/ActivityManager( 1018): Displayed Component not be shown by security: +658ms (total +729ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{2344d43c u0 com.example.hello/.MainActivity t19} time:84006
I/SurfaceFlinger(  259): id=11 Removed iello (7/9)
I/SurfaceFlinger(  259): id=11 Removed iello (-2/9)
I/SamsungIME( 1754): getCurrentCandidateView
D/SamsungIME( 1754): Dismiss ExpandCandiate
I/SamsungIME( 1754): getDebugLevel  : 0x4f4c
W/BindingManager( 5309): Cannot call determinedVisibility() - never saw a connection for the pid: 5309
I/chromium( 5309): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/SamsungIME( 1754): getDebugLevel  : 0x4f4c
I/SamsungIME( 1754): KeybaordView init() : load resources
I/SamsungIME( 1754): getCurrentKeyboard
I/SamsungIME( 1754): getTextKeyboard
D/SamsungIME( 1754): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5309): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5309): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 5309): JniHelper::setJavaVM(0xb8a6f448), pthread_self() = -1191406552
D/JX-Cordova( 5309): jxcore cordova android initializing
W/jxcore-log( 5309): Initializing JXcore engine
W/jxcore-log( 5309): JXcore engine is ready
W/jxcore-log( 5309): Starting JXcore engine
E/audit   ( 1813): type=1400 msg=audit(1449501119.107:203): avc:  denied  { ioctl } for  pid=5309 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1813):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1813): type=1300 msg=audit(1449501119.107:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be96dd58 items=0 ppid=307 ppcomm=main pid=5309 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1813): type=1320 msg=audit(1449501119.107:203): 
,W/jxcore-log( 5309): Platform android
W/jxcore-log( 5309): 
W/jxcore-log( 5309): Process ARCH arm
W/jxcore-log( 5309): 
,I/jxcore-log( 5309): JXcore Cordova bridge is ready!
I/jxcore-log( 5309): 
,W/jxcore-log( 5309): JXcore engine is started
,E/jxcore-log( 5309): >> samsung-SM-A300FU
E/jxcore-log( 5309): 
I/jxcore-log( 5309): Total memory 1451114496,
I/jxcore-log( 5309): 
I/jxcore-log( 5309): Free memory 18800640
I/jxcore-log( 5309): 
I/jxcore-log( 5309): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5309): 
I/jxcore-log( 5309): process.cwd /data/data/com.example.hello/files/www/jxcore,
I/jxcore-log( 5309): 
,I/jxcore-log( 5309): userPath [ 'www' ],
I/jxcore-log( 5309): 
,I/jxcore-log( 5309): Size 540 960
I/jxcore-log( 5309): 
,I/jxcore-log( 5309): Screen Brightness 160
I/jxcore-log( 5309): 
,E/jxcore-log( 5309): Dummy Error Log.
E/jxcore-log( 5309): 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 5309): getBuffer is called!!!!
I/jxcore-log( 5309): 
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
,V/EmergencyMode( 1415): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1415): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/BluetoothAdapter( 5309): disable()
,E/BluetoothManagerService( 1018): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/WifiService( 1018): setWifiEnabled: false pid=5309, uid=10345,
D/SettingsProvider( 1018): name = wifi_on
I/jxcore-log( 5309): ****TEST TOOK:  5055  ms ****
I/jxcore-log( 5309): 
I/jxcore-log( 5309): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5309): 
,D/AndroidRuntime( 5359): ,
D/AndroidRuntime( 5359): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5359): CheckJNI is OFF,
D/AndroidRuntime( 5359): readGMSProperty: start
,D/AndroidRuntime( 5359): readGMSProperty: already setted!!
D/AndroidRuntime( 5359): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5359): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5359): readGMSProperty: end
D/AndroidRuntime( 5359): addProductProperty: start
,E/AffinityControl( 5359): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 5359): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{115529798}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10345, uninstall pkg,
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5309:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{268a6c71 com.test.thalitest/10338} due to missing metadata
,I/WindowState( 1018): WIN DEATH: Window{3bb7096e u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 5309
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2344d43c u0 com.example.hello/.MainActivity t19},
,W/ActivityManager( 1018): Spurious death for ProcessRecord{189f9a07 5309:com.example.hello/u0a345}, curProc for 5309: null
I/ActivityManager( 1018): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2344d43c u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{2344d43c u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3641): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 807us total 34.267ms
,D/InputDispatcher( 1018): Focused application released
,I/art     ( 4143): Explicit concurrent mark sweep GC freed 22576(1674KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 1.195ms total 56.848ms
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1754): mOCRHelper is null
,W/GeofencerStateMachine( 1639): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3463): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 16:12:05 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3463): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5373): MountEmulatedStorage()
E/Zygote  ( 5373): v2
I/libpersona( 5373): KNOX_SDCARD checking this for 10090
I/libpersona( 5373): KNOX_SDCARD not a persona
,I/SELinux ( 5373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5373 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): onCreate(),
,I/KLMS-2.5.123: ( 3463): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3463): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): PACKAGE_REMOVED
,D/TimaKeyStoreProvider( 5373): TimaSignature is unavailable
,D/ActivityThread( 5373): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): listeningToPackageRemoved().START
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 18937(1490KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 2.728ms total 189.442ms
,I/art     ( 1018): WaitForGcToComplete blocked for 116.607ms for cause Explicit
,D/RegisteredServicesCache( 1439): empty dynamic service
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 5373): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 5373): ELMEngine.ELMEngine( context ).
,D/elm:15121( 5373): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 5373): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 5373): ElmAgentService : onCreate()
,D/elm:15121( 5373): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 5373): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5373): MDMBridge.getInstance()
D/elm:15121( 5373): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 5373): MDMBridge.getAllLicenseInfoFromSDK()
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10345
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,I/KLMS-2.5.123: ( 3463): KLMSIntentService(): onDestroy()
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10345
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1018): removeObsoleteFile: deleting file=19_task.xml
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,D/elm:15121( 5373): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 4858:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/PCWCLIENTTRACE_PushUtil( 5028): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5028): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5028): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5028): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5152): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5152): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 7699(466KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 3.714ms total 175.935ms
,I/PackagesMonitor( 4360): PackagesMonitor onReceive :com.example.hello
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1018): UID=10345 Target=com.example.hello
,D/PackageManager( 1018): result of delete: 1{115529798}
,D/AndroidRuntime( 5359): Shutting down VM
,D/Mms/FreeMessageStatusReceiver( 4219): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
,I/TactileAssist( 1018): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 4219): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 4219): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/Compatibility( 5109): onReceive() it will make start service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
,D/Compatibility( 5109): onHandleIntent()
,D/Compatibility( 5109): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5109): found: 2
D/Compatibility( 5109): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5109): skipping ResolveInfo{57ad15 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5109): considering ResolveInfo{f4f482a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5109): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5109): enabling receiver ResolveInfo{273ab61b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Compatibility( 5109): enabling receiver ResolveInfo{b5df3b8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000},
,E/Zygote  ( 5393): MountEmulatedStorage()
E/Zygote  ( 5393): v2
I/libpersona( 5393): KNOX_SDCARD checking this for 10055
I/libpersona( 5393): KNOX_SDCARD not a persona
I/SELinux ( 5393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5393 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/SELinux ( 5393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5393): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5109): enabling receiver ResolveInfo{2f930591 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5109): enabling receiver ResolveInfo{2c71bcf6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5109): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 5393): TimaSignature is unavailable
,D/ActivityThread( 5393): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/UserAnalysis.PlaceProvider( 5393): PlaceProvider onCreate()
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UserAnalysis.SecureDbManager( 5393): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5393): SecurePlaceDbHelper() 
D/UserAnalysis( 5393): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5393): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5393): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 4439): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/IntelligenceServiceApplication( 5393): no applications having user consent for prediction
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/art     ( 5359): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5409): MountEmulatedStorage()
E/Zygote  ( 5409): v2
I/libpersona( 5409): KNOX_SDCARD checking this for 1000
I/libpersona( 5409): KNOX_SDCARD not a persona
,I/SELinux ( 5409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=5409 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4858/cgroup.procs: No such file or directory
I/ActivityManager( 1018): Killing 4873:com.wssyncmldm/1000 (adj 15): empty #31
,I/SELinux ( 5409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetection::stopService] Service stopped.
,D/TimaKeyStoreProvider( 5409): TimaSignature is unavailable
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/ActivityThread( 5409): Added TimaKeyStore provider
,W/ResourcesManager( 5409): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/BluetoothAdapter( 5393): 410301058: getState() :  mService = null. Returning STATE_OFF
,V/PlaceDetection v1.0.19 ( 5393): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 5393): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4873/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
E/SQLiteLog( 5393): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5393): (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,E/SQLiteDatabase( 5393): Error inserting timestamp=1449501125687 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 5393): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 5393): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 5393): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 5393): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 5393): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 5393): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 5393): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 5393): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 5393): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 5393): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 5393): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5393): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5393): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 5393): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5393): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5393): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 5393): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/UserAnalysis( 5393): It failed to insert to dump_log table
,D/RCPManager( 5409):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1018):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5134): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,W/ContextImpl( 5134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5134): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5134): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 5134): before removeFromFS
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5428 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,E/Zygote  ( 5428): MountEmulatedStorage()
E/Zygote  ( 5428): v2
I/libpersona( 5428): KNOX_SDCARD checking this for 10095
I/libpersona( 5428): KNOX_SDCARD not a persona
,I/SELinux ( 5428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 5428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 5428): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 5438): MountEmulatedStorage(),
E/Zygote  ( 5438): v2
I/libpersona( 5438): KNOX_SDCARD checking this for 1000
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 5438): KNOX_SDCARD not a persona
,I/SELinux ( 5438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 5428): TimaSignature is unavailable
,E/SELinux ( 5438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
D/ActivityThread( 5428): Added TimaKeyStore provider

```
