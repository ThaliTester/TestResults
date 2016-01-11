#### Test 55634150e857e16_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  290): DCD OFF
,D/AndroidRuntime( 5942): 
D/AndroidRuntime( 5942): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5942): CheckJNI is OFF
D/AndroidRuntime( 5942): readGMSProperty: start
D/AndroidRuntime( 5942): readGMSProperty: already setted!!
D/AndroidRuntime( 5942): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5942): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5942): readGMSProperty: end
D/AndroidRuntime( 5942): addProductProperty: start
E/AffinityControl( 5942): AffinityControl: registerfunction enter
D/AndroidRuntime( 5942): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
E/Zygote  ( 5956): MountEmulatedStorage()
E/Zygote  ( 5956): v2
I/libpersona( 5956): KNOX_SDCARD checking this for 10346
I/libpersona( 5956): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5956 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1496
I/SELinux ( 5956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 5942): Shutting down VM
I/SELinux ( 5956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5956): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, iello
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1434): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1434): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/TimaKeyStoreProvider( 5956): TimaSignature is unavailable
D/ActivityThread( 5956): Added TimaKeyStore provider
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
V/ActivityManager( 1020): Display changed displayId=0
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1496): updateVisibility : ActivityRecord{34c9c281 token=android.os.BinderProxy@2c135dc7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1496): onTrimMemory. Level: 20
I/WebViewFactory( 5956): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5956): Time to load native libraries: 1 ms (timestamps 6252-6253)
I/LibraryLoader( 5956): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5956): Binding Chromium to main looper Looper (main, tid 1) {14485c33}
I/LibraryLoader( 5956): Expected native library version number "",actual native library version number ""
I/chromium( 5956): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5942): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 5956): Initializing chromium process, singleProcess=true
,W/art     ( 5956): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5956): ApplicationContext is null in ApplicationStatus
,W/chromium( 5956): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5956): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5956): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5956): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5956): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5956): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5956): Local Branch: 
I/Adreno-EGL( 5956): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5956): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5956):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 5956): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5956): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5956): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5956): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5956): CordovaWebView is running on device made by: samsung
,W/art     ( 5956): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5956): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{1e597374 u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 5956): Render dirty regions requested: true,
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
W/chromium( 5956): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5956): updateVisibility : ActivityRecord{d834f4c token=android.os.BinderProxy@31b70c9e {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5956): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5956): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit,
,D/InputDispatcher( 1020): Focus entered window: 5956
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5956): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5956): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5956): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5956): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1842): getCurrentCandidateView
W/IInputConnectionWrapper( 5956): showStatusIcon on inactive InputConnection
,I/Timeline( 5956): Timeline: Activity_idle id: android.os.BinderProxy@31b70c9e time:86806
,I/ActivityManager( 1020): Displayed Component not be shown by security: +688ms (total +786ms),
W/ActivityManager( 1020): mDVFSHelper.release()
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{1e597374 u0 com.example.hello/.MainActivity t19} time:86852
,I/SurfaceFlinger(  259): id=12 Removed iello (7/9),
,I/SurfaceFlinger(  259): id=12 Removed iello (-2/9)
,D/SamsungIME( 1842): Dismiss ExpandCandiate
,I/SamsungIME( 1842): getDebugLevel  : 0x4f4c
,W/BindingManager( 5956): Cannot call determinedVisibility() - never saw a connection for the pid: 5956
,I/chromium( 5956): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1842): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1842): KeybaordView init() : load resources
,I/SamsungIME( 1842): getCurrentKeyboard
I/SamsungIME( 1842): getTextKeyboard
,D/SamsungIME( 1842): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5956): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5956): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5956): JniHelper::setJavaVM(0xb8d69448), pthread_self() = -1188291168
,D/JX-Cordova( 5956): jxcore cordova android initializing
,W/jxcore-log( 5956): Initializing JXcore engine
W/jxcore-log( 5956): JXcore engine is ready
,W/jxcore-log( 5956): Starting JXcore engine
,E/audit   ( 1856): type=1400 msg=audit(1452528627.881:205): avc:  denied  { ioctl } for  pid=5956 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1856):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1856): type=1300 msg=audit(1452528627.881:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bed17d58 items=0 ppid=313 ppcomm=main pid=5956 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1856): type=1320 msg=audit(1452528627.881:205): 
,W/jxcore-log( 5956): Platform android
W/jxcore-log( 5956): 
W/jxcore-log( 5956): Process ARCH arm
W/jxcore-log( 5956): 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5956): JXcore Cordova bridge is ready!
I/jxcore-log( 5956): 
,W/jxcore-log( 5956): JXcore engine is started
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/jxcore-log( 5956): >> samsung-SM-A300FU
E/jxcore-log( 5956): 
,I/jxcore-log( 5956): Total memory 1451114496
I/jxcore-log( 5956): 
,I/jxcore-log( 5956): Free memory 25387008
I/jxcore-log( 5956): 
I/jxcore-log( 5956): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5956): 
I/jxcore-log( 5956): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5956): 
,I/jxcore-log( 5956): userPath [ 'www', 'www' ]
I/jxcore-log( 5956): 
I/jxcore-log( 5956): Size 540 960
I/jxcore-log( 5956): 
I/jxcore-log( 5956): Screen Brightness 160
I/jxcore-log( 5956): 
,E/jxcore-log( 5956): Dummy Error Log.
E/jxcore-log( 5956): 
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 20830(1245KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 7MB/12MB, paused 1.033ms total 44.800ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1020): SIOP:: AP = 310
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 5956): getBuffer is called!!!!
I/jxcore-log( 5956): 
,V/AlarmManager( 1020): waitForAlarm result :4
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6007): MountEmulatedStorage(),
E/Zygote  ( 6007): v2
,I/libpersona( 6007): KNOX_SDCARD checking this for 10071
I/libpersona( 6007): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6007 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6007): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6007): TimaSignature is unavailable
,D/ActivityThread( 6007): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6007): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6007): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6007): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 38263(2MB) AllocSpace objects, 20(324KB) LOS objects, 33% free, 23MB/35MB, paused 2.076ms total 139.430ms
,E/SQLiteLog( 6007): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6007): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6007): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6007): Soft error
E/BooksSync( 6007): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6007): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6007): Sync error
E/BooksSync( 6007): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6007): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6007): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64389, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/ActivityManager( 1020): Killing 4456:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,W/libprocessgroup( 1020): failed to open /acct/uid_10108/pid_4456/cgroup.procs: No such file or directory
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BluetoothAdapter( 5956): disable()
,D/SettingsProvider( 1020): name = bluetooth_on
,D/BluetoothAdapterState( 2632): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 2632): Setting state to 13
I/BluetoothAdapterState( 2632): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2632): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2632): updateAdapterState state is 13
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2632): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 2632): close() in, this: android.bluetooth.BluetoothSocket@1d4ef3f3, channel: 19, state: LISTENING
D/BluetoothSocket( 2632): close() this: android.bluetooth.BluetoothSocket@1d4ef3f3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a68f07b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29e418b0mSocket: android.net.LocalSocket@1dc45329 impl:android.net.LocalSocketImpl@38a416ae fd:FileDescriptor[74]
D/BluetoothSocket( 2632): Closing mSocket: android.net.LocalSocket@1dc45329 impl:android.net.LocalSocketImpl@38a416ae fd:FileDescriptor[74]
,D/BluetoothAdapterService( 2632): Autoconnection is available 
,D/BluetoothAdapterService( 2632): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2632): terminating service from this receiver
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2632): onBluetoothDisable(),
D/BluetoothAdapterProperties( 2632): mDiscovering is false
,D/SecContentProvider( 1020): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2632): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1020): [BT Setting State] State =13
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1020): mCursor = null
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/WifiService( 1020): setWifiEnabled: false pid=5956, uid=10346
,D/SettingsProvider( 1020): name = wifi_on
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 13
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,I/SamsungIME( 1842): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,I/jxcore-log( 5956): ****TEST TOOK:  5091  ms ****
I/jxcore-log( 5956): 
,I/jxcore-log( 5956): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5956): 
,D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
V/BluetoothEventManager( 1317): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
E/WifiStateMachine( 1020): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1398): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1398): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1398): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1398): Scan requested (ret=0) - scan timeout 30 seconds
D/BluetoothAdapterProperties( 2632): Scan Mode:20
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothAdapterState( 2632): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2632): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2632): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 2632): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothSocket( 2632): close() in, this: android.bluetooth.BluetoothSocket@155adc4f, channel: 5, state: LISTENING
D/BluetoothSocket( 2632): close() this: android.bluetooth.BluetoothSocket@155adc4f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22160e98, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3aea0fdcmSocket: android.net.LocalSocket@6a5f8e5 impl:android.net.LocalSocketImpl@c9eefba fd:FileDescriptor[76]
D/BluetoothSocket( 2632): Closing mSocket: android.net.LocalSocket@6a5f8e5 impl:android.net.LocalSocketImpl@c9eefba fd:FileDescriptor[76]
,I/BtOppRfcommListener( 2632): stopping Accept Thread
D/BluetoothSocket( 2632): close() in, this: android.bluetooth.BluetoothSocket@3092ee6b, channel: 12, state: LISTENING
D/BluetoothSocket( 2632): close() this: android.bluetooth.BluetoothSocket@3092ee6b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b28f662, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4f64dc8mSocket: android.net.LocalSocket@19423e61 impl:android.net.LocalSocketImpl@103c4d86 fd:FileDescriptor[80]
D/BluetoothSocket( 2632): Closing mSocket: android.net.LocalSocket@19423e61 impl:android.net.LocalSocketImpl@103c4d86 fd:FileDescriptor[80]
I/BtOppRfcommListener( 2632): BluetoothSocket listen thread finished
,W/ContextImpl( 1317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,E/bt-btif ( 2632): cmd socket is not created
,D/btif_config_util( 2632): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2632): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2632): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,V/BluetoothOppManager( 2632): cleanUp...
,D/BluetoothPbap( 1317): Proxy object disconnected
D/PbapServerProfile( 1317): Bluetooth service disconnected
,D/DockEventReceiver( 1317): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1317): onReceive
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/WifiNative-wlan0( 1020): do suspend true
,E/Zygote  ( 6043): MountEmulatedStorage()
,E/Zygote  ( 6043): v2
I/libpersona( 6043): KNOX_SDCARD checking this for 10055
I/libpersona( 6043): KNOX_SDCARD not a persona
,I/SELinux ( 6043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6043 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6043): TimaSignature is unavailable
,D/ActivityThread( 6043): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6043): PlaceProvider onCreate()
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,D/UserAnalysis.SecureDbManager( 6043): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6043): SecurePlaceDbHelper() 
D/UserAnalysis( 6043): Create SecureDbHelper
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/IntelligenceServiceApplication( 6043): onCreate()
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1739): Read error: ssl=0xb92a20f0: I/O error during system call, Connection timed out
V/NativeCrypto( 1739): SSL shutdown failed: ssl=0xb92a20f0: I/O error during system call, Broken pipe
,E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Forcing reevaluation
E/ConnectivityService( 1020): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/WifiP2pService( 1020): InactiveState{ what=131204 }
I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1020): Tagging socket 350 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
D/WifiNetworkAgent( 1020): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/WifiP2pService( 1020): P2pEnabledState{ what=131204 }
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiScanningService( 1020): SCAN_AVAILABLE : 1
D/IntelligenceServiceApplication( 6043): no applications having user consent for prediction
D/WifiScanningService( 1020): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1020): Killing 5209:com.google.android.gm/u0a99 (adj 15): empty #31
D/RttService( 1020): SCAN_AVAILABLE : 1
D/RttService( 1020): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService( 1020): sending p2p connection changed broadcast: FAILED,
I/qtaguid ( 1020): Untagging socket 350
I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,V/PlaceDetection v1.0.19 ( 6043): [PlaceDetection::stopService] Service stopped.
,D/WifiDisplayController( 1020): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1020): onP2pDisconnected
,D/WifiP2pService( 1020): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine( 1020): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/IpRemoteDisplayController( 1020): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1020): WfdBridgeServer is already null
,D/WifiDisplayController( 1020): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1020): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1020): disconnect
D/WifiDisplayController( 1020): updateConnection
D/WifiDisplayController( 1020): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AuthorizationBluetoothService( 1739): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/WifiP2pService( 1020): P2pDisablingState
D/WifiP2pService( 1020): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1020): p2p socket connection lost
,E/WifiNative-wlan0( 1020): do suspend true
D/WifiP2pService( 1020): P2pDisabledState
,D/WifiP2pService( 1020): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1020): DefaultState{ what=143375 }
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
I/bt_userial_mct( 2632): exiting userial_read_thread
D/bt_userial_mct( 2632): Leaving userial_evt_read_thread()
,W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2632): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2632): ag scb idx 1 not allocated
W/bt-btif ( 2632): ag scb idx 2 not allocated
E/bt-btif ( 2632): BTA AG is already disabled, ignoring ...
,V/PlaceDetection v1.0.19 ( 6043): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/bt_userial_mct( 2632): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2632): hw_epilog_process
,D/bt_userial_mct( 2632): userial_close,
I/bt_vendor( 2632): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/WifiDisplayController( 1020): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1020): onP2pDisconnected
D/IpRemoteDisplayController( 1020): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1020): WfdBridgeServer is already null
,D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #8
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  280): Clearing all IP addresses on wlan0
,I/Hs20UtilService( 1682): Message received 5007
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
D/ConnectivityService( 1020): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1020): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1020): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1020): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1020): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1471): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1471): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
I/wpa_supplicant( 1398): p2p0: State: DISCONNECTED -> DISCONNECTED
D/AndroidRuntime( 6044): 
D/AndroidRuntime( 6044): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/AndroidRuntime( 6044): CheckJNI is OFF
D/AndroidRuntime( 6044): readGMSProperty: start
D/AndroidRuntime( 6044): readGMSProperty: already setted!!
D/AndroidRuntime( 6044): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6044): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6044): readGMSProperty: end
D/AndroidRuntime( 6044): addProductProperty: start
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
D/ConnectivityService( 1020): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): doQuit - quitNow()
E/ConnectivityService( 1020): updateNetworkInfo()
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): updateIfacesLocked()
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
V/NetworkStats( 1020): performPollLocked() took 13ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(0)
D/HotspotTile( 1177): onReceive : 0, 0
D/WifiCredService( 1317): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
,I/wpa_supplicant( 1398): Blacklist: Clear (all) 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6075): MountEmulatedStorage()
,I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6075 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6075): v2
I/libpersona( 6075): KNOX_SDCARD checking this for 10064
I/libpersona( 6075): KNOX_SDCARD not a persona
,I/SELinux ( 6075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/PowerManagerService( 1020): [PWL] Off : 15s ago
I/PowerManagerService( 1020): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1020): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1020): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2055, ws=null) (elapsedTime=56672)
I/PowerManagerService( 1020): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1020, ws=null) (elapsedTime=104)
,I/wpa_supplicant( 1398): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1020): interfaceLinkStateChanged p2p0, false,
I/Nat464Xlat( 1020): interfaceLinkStateChanged p2p0, false
D/Tethering( 1020): interfaceStatusChanged p2p0, false
,D/TimaKeyStoreProvider( 6075): TimaSignature is unavailable
,D/ActivityThread( 6075): Added TimaKeyStore provider
,E/AffinityControl( 6044): AffinityControl: registerfunction enter
,W/ResourcesManager( 6075): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/wpa_supplicant( 1398): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1398): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1398): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1398): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1398): wlan0: State: DISCONNECTED -> DISCONNECTED
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/Tethering( 1020): InitialState.processMessage what=4
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,E/Tethering( 1020): No numeric data
D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1020): clearTetheredNotification()
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
V/NetworkStats( 1020): performPollLocked() took 4ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/AndroidRuntime( 6044): Calling main entry com.android.commands.pm.Pm
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/bt_vendor( 2632): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 2632): bluetooth satus is on
I/bt_vendor( 2632): bt-vendor : resetting BT status
I/bt_vendor( 2632): Starting hciattach daemon
,I/bt_vendor( 2632): try to set false
,I/bt_vendor( 2632): Starting hciattach daemon
I/bt_vendor( 2632): try to set false
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/bt_vendor( 2632): cleanup
,I/GKI_LINUX( 2632): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2632): GKI_exit_task 0 done
I/GKI_LINUX( 2632): GKI_shutdown(): task [BTU] terminated
D/FileShare-Client( 6075): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BluetoothAdapterState( 2632): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2632): isSecureModeOn:false
D/BluetoothAdapterService( 2632): mProfilesStarted : true supportedProfileServices.length : 12,
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.gatt.GattService
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2632): handleDebugAction() action=null
D/FileShare-Client( 6075): ClientBroadcastReceiver.onReceive - disconnected
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/BtGatt.GattService( 2632): Received stop request...Stopping profile...
D/BtGatt.GattService( 2632): stop()
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BtGatt.AdvertiseManager( 2632): advertise clients cleared
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/PackageManager( 1020): START PACKAGE DELETE: observer{832729296}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/PackageManager( 1020): !@killApplicatoin: 10346, uninstall pkg
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/HeadsetService( 2632): Received stop request...Stopping profile...
W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.hid.HidService
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/libprocessgroup( 1020): failed to open /acct/uid_10099/pid_5209/cgroup.procs: No such file or directory
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.hdp.HealthService
D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AudioService( 1020): onServiceDisconnected: Bluetooth profile: 1
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.pan.PanService
I/ActivityManager( 1020): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 5956:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
,D/HeadsetProfile( 1317): Bluetooth service disconnected
,D/FileShare-Client( 6075): Outbound.stopDelayTimer - 
,W/PackageSettings( 1020): Skipping PackageSetting{15143a8b com.test.thalitest/10338} due to missing metadata
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/WindowState( 1020): WIN DEATH: Window{47633e6 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{1e597374 u0 com.example.hello/.MainActivity t19}
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,D/PhoneApp( 1471): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1471): FileWriteThread : threadType = 3
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focus left window: 5956
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2632): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6109): MountEmulatedStorage(),
E/Zygote  ( 6109): v2
I/libpersona( 6109): KNOX_SDCARD checking this for 10065
I/libpersona( 6109): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6109 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Killing 4208:com.sec.spp.push/u0a32 (adj 15): empty #31
I/SELinux ( 6109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputDispatcher( 1020): Focused application released
I/wpa_supplicant( 1398): Blacklist: Clear (all) 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2632): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
I/ActivityManager( 1020): Force stopping com.example.hello appid=10346 user=0: pkg removed
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2632): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2632): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2632): Stopping profile services that were post enabled
E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 2632): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2632): Exit Disconnected: -1
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1398): wlan0: CTRL-EVENT-TERMINATING 
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,D/TimaKeyStoreProvider( 6109): TimaSignature is unavailable
,D/ActivityThread( 6109): Added TimaKeyStore provider
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4208/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
,I/art     ( 4031): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.064ms total 31.779ms
,I/art     ( 5247): Explicit concurrent mark sweep GC freed 9895(663KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 797us total 49.401ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1842): mOCRHelper is null
,W/GeofencerStateMachine( 1822): Ignoring removeGeofence because network location is disabled.
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,E/WifiStateMachine( 1020): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1020): callSECApiBoolean - ID [21]
,D/BluetoothA2dp( 1317): Proxy object disconnected
D/A2dpProfile( 1317): Bluetooth service disconnected
,D/HidService( 2632): Received stop request...Stopping profile...
,D/HidService( 2632): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2632): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2632): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2632): Cleaning up Bluetooth GID callback object
,W/Settings( 5866): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(1)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/WifiCredService( 1317): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 1, 0
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 1822): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothInputDevice( 1317): Proxy object disconnected
D/HidProfile( 1317): Bluetooth service disconnected
,E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.hid.HidService
,D/HealthService( 2632): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
,W/BluetoothHeadsetServiceJni( 2632): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2632): Cleaning up Bluetooth Handsfree callback object
D/PanService( 2632): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
D/BluetoothPan( 1317): BluetoothPAN Proxy object disconnected
D/PanProfile( 1317): Bluetooth service disconnected
D/FileShare-Server( 6109): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,D/BluetoothMapService( 2632): Received stop request...Stopping profile...
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10346
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10346
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
,D/SapService( 2632): Received stop request...Stopping profile...
D/BluetoothMap( 1317): Proxy object disconnected
D/MapProfile( 1317): Bluetooth service disconnected
,D/SapService( 2632): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2632): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b469569
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
,E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2632): Proxy object disconnected
D/BluetoothAdapterService( 2632): Bluetooth A2dp source service disconnected
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/GKI_LINUX( 2632): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2632): GKI_exit_task 2 done
I/GKI_LINUX( 2632): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/Bluetoothsap( 1317): BluetoothSAP Proxy object disconnected
D/SapProfile( 1317): Bluetooth service disconnected
,E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2632): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 2632): Cleaning up Bluetooth Health object
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
I/ActivityManager( 1020): Killing 4719:com.android.mms/u0a41 (adj 15): empty #31
,D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2632): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2632): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2632): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2632): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2632): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(726046057)( 2632): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2632): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2632): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/RegisteredServicesCache( 1462): empty dynamic service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/BluetoothAdapterState( 2632): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2632): Setting state to 10
I/BluetoothAdapterState( 2632): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2632): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2632): updateAdapterState state is 10
,D/BluetoothAdapterService( 2632): Autoconnection is available 
D/BluetoothAdapterService( 2632): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2632): Entering OffState
,D/BluetoothAdapter( 1462): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1462): Bluetooth is turned off, stop adv and scan
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=19_task.xml
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,I/Hs20UtilService( 1682): Starting #9
,I/Hs20UtilService( 1682): Message received 5007
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 43982(2MB) AllocSpace objects, 8(180KB) LOS objects, 33% free, 24MB/36MB, paused 16.746ms total 249.249ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothA2dp( 1020): Proxy object disconnected
D/AudioService( 1020): onServiceDisconnected: Bluetooth profile: 2
,D/BluetoothPan( 1020): BluetoothPAN Proxy object disconnected
,D/PackageManager( 1020): delete codoeFile: 
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
I/AASA_removePackage( 1020): UID=10346 Target=com.example.hello
,D/CountryDetector( 1020): No listener is left
,D/PackageManager( 1020): result of delete: 1{832729296}
,I/ApplicationPolicy( 1020): updateDataUsageMap
,D/AndroidRuntime( 6044): Shutting down VM,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/BluetoothA2dp( 1020): onBluetoothStateChange: up=false
,I/Hs20UtilService( 1682): Starting #10
,I/Hs20UtilService( 1682): Message received 5011
,D/Bluetoothsap( 1317): onBluetoothStateChange: up=false
D/Bluetoothsap( 1317): Unbinding service...
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6126): MountEmulatedStorage()
E/Zygote  ( 6126): v2
I/libpersona( 6126): KNOX_SDCARD checking this for 1000
I/libpersona( 6126): KNOX_SDCARD not a persona
,I/SELinux ( 6126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/BluetoothAdapter( 1445): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1445): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1020): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1020): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1471): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1471): Bluetooth is turned off, stop adv and scan
,D/BluetoothInputDevice( 1317): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1317): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2632): onBluetoothStateChange: up=false
,D/BluetoothPbap( 1317): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 2632): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2632): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1317): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1317): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1822): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1822): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1177): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1177): Bluetooth is turned off, stop adv and scan
,D/BluetoothMap( 1317): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1020): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/BluetoothAdapter( 1177): 394156944: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1177): 394156944: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1177):  getBluetoothState : 10
,D/BluetoothAdapter( 1177): 394156944: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1177): 394156944: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1177): 394156944: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/TimaKeyStoreProvider( 6126): TimaSignature is unavailable
,I/SamsungIME( 1842): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/ActivityThread( 6126): Added TimaKeyStore provider
,D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,V/BluetoothEventManager( 1317): Received android.bluetooth.adapter.action.STATE_CHANGED
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/GKI_LINUX( 2632): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2632): GKI_exit_task 1 done
,I/GKI_LINUX( 2632): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2632): cleanupNative: return from cleanup
,I/art     ( 2632): System.exit called, status: 0
,I/AndroidRuntime( 2632): VM exiting with result code 0, cleanup skipped.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SecurityLogAgent( 6126): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6126): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6126): StateMachine : Current State = 1
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SecurityLogAgent( 6126): StateMachine : Changed Current State = 1
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1020): Killing 5276:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/UsbSettingsManager( 1020): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1020): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_4719/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Process com.android.bluetooth (pid 2632)(adj 0) has died(92,678)
,W/art     ( 6044): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/Tethering( 1020): interfaceRemoved wlan0
,E/Tethering( 1020): attempting to remove unknown iface (wlan0), ignoring
,W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1020): [BT Setting State] State =10
I/InputMethodManagerService( 1020): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/KLMS-2.5.123: ( 3634): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 17:10:34 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3634): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
,I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3634): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3634): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/libpersona( 6145): KNOX_SDCARD checking this for 10090
I/KLMS-2.5.123: ( 3634): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/libpersona( 6145): KNOX_SDCARD not a persona
I/KLMS-2.5.123: ( 3634): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3634): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3634): KLMSIntentService(): listeningToPackageRemoved().START
E/Zygote  ( 6145): MountEmulatedStorage()
E/Zygote  ( 6145): v2
W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_5276/cgroup.procs: No such file or directory
I/KLMS-2.5.123: ( 3634): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6145 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
,D/ActivityThread( 6145): Added TimaKeyStore provider

```
