#### Test 50388019b17f598_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  291): DCD OFF
--------- beginning of system
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/HeadsetService( 2636): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2636): Disconnected process message: 10
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,D/AndroidRuntime( 5963): 
D/AndroidRuntime( 5963): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5963): CheckJNI is OFF
D/AndroidRuntime( 5963): readGMSProperty: start
D/AndroidRuntime( 5963): readGMSProperty: already setted!!
D/AndroidRuntime( 5963): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5963): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5963): readGMSProperty: end
D/AndroidRuntime( 5963): addProductProperty: start
E/AffinityControl( 5963): AffinityControl: registerfunction enter
D/AndroidRuntime( 5963): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1022): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5977 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 1487
E/Zygote  ( 5977): MountEmulatedStorage()
I/libpersona( 5977): KNOX_SDCARD checking this for 10345
E/Zygote  ( 5977): v2
I/libpersona( 5977): KNOX_SDCARD not a persona
D/AndroidRuntime( 5963): Shutting down VM
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5977): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5977): TimaSignature is unavailable
D/ActivityThread( 5977): Added TimaKeyStore provider
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1022): Display changed displayId=0
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
D/PersonaManager( 1022): isKioskContainerExistOnDevice
V/ActivityThread( 1487): updateVisibility : ActivityRecord{270a1853 token=android.os.BinderProxy@289339e9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1487): onTrimMemory. Level: 20
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/WebViewFactory( 5977): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5977): Time to load native libraries: 2 ms (timestamps 6928-6930)
I/LibraryLoader( 5977): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5977): Binding Chromium to main looper Looper (main, tid 1) {2104e78a}
I/LibraryLoader( 5977): Expected native library version number "",actual native library version number ""
I/chromium( 5977): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5977): Initializing chromium process, singleProcess=true
W/art     ( 5977): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5977): ApplicationContext is null in ApplicationStatus
W/art     ( 5963): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/chromium( 5977): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5977): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5977): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5977): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5977): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5977): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5977): Local Branch: 
I/Adreno-EGL( 5977): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5977): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5977):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 5977): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/AwContents( 5977): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5977): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5977): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5977): CordovaWebView is running on device made by: samsung
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 5977): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5977): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): Activity pause timeout for ActivityRecord{3ea3cd7f u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 5977): Render dirty regions requested: true
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
,W/chromium( 5977): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5977): updateVisibility : ActivityRecord{673dfc7 token=android.os.BinderProxy@219d1be1 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 5977): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5977): *FMB* isFloatingMenuEnabled return false
,D/SSRM:n  ( 1022): SIOP:: AP = 310
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1022): Focus entered window: 5977
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 5977): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5977): Initialized EGL, version 1.4
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 5977): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5977): Enabling debug mode 0,
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5977): showStatusIcon on inactive InputConnection
I/Timeline( 5977): Timeline: Activity_idle id: android.os.BinderProxy@219d1be1 time:87581
,I/SamsungIME( 1861): getCurrentCandidateView
,D/SamsungIME( 1861): Dismiss ExpandCandiate
,I/ActivityManager( 1022): Displayed Component not be shown by security: +785ms (total +872ms)
,W/ActivityManager( 1022): mDVFSHelper.release(),
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{3ea3cd7f u0 com.example.hello/.MainActivity t19} time:87632
,I/SurfaceFlinger(  257): id=12 Removed iello (7/9)
,I/SurfaceFlinger(  257): id=12 Removed iello (-2/9)
,W/BindingManager( 5977): Cannot call determinedVisibility() - never saw a connection for the pid: 5977
,I/chromium( 5977): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1861): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1861): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1861): KeybaordView init() : load resources
,I/SamsungIME( 1861): getCurrentKeyboard
,I/SamsungIME( 1861): getTextKeyboard
,D/SamsungIME( 1861): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5977): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5977): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5977): JniHelper::setJavaVM(0xb77fb448), pthread_self() = -1210769400
,D/JX-Cordova( 5977): jxcore cordova android initializing
,W/jxcore-log( 5977): Initializing JXcore engine
W/jxcore-log( 5977): JXcore engine is ready
,W/jxcore-log( 5977): Starting JXcore engine
,E/audit   ( 1859): type=1400 msg=audit(1448385997.540:205): avc:  denied  { ioctl } for  pid=5977 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1859):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1859): type=1300 msg=audit(1448385997.540:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beaf9d58 items=0 ppid=316 ppcomm=main pid=5977 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1859): type=1320 msg=audit(1448385997.540:205): 
,W/jxcore-log( 5977): Platform android
W/jxcore-log( 5977): 
W/jxcore-log( 5977): Process ARCH arm
W/jxcore-log( 5977): 
,I/jxcore-log( 5977): JXcore Cordova bridge is ready!
I/jxcore-log( 5977): 
W/jxcore-log( 5977): JXcore engine is started
,E/jxcore-log( 5977): >> samsung-SM-A300FU
E/jxcore-log( 5977): 
,I/jxcore-log( 5977): Total memory 1451114496
I/jxcore-log( 5977): 
,I/jxcore-log( 5977): Free memory 24203264
I/jxcore-log( 5977): 
I/jxcore-log( 5977): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5977): 
I/jxcore-log( 5977): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5977): 
,I/jxcore-log( 5977): userPath [ 'www' ]
I/jxcore-log( 5977): 
,I/jxcore-log( 5977): Size 540 960
I/jxcore-log( 5977): 
,I/jxcore-log( 5977): Screen Brightness 160
I/jxcore-log( 5977): 
,E/jxcore-log( 5977): Dummy Error Log.
E/jxcore-log( 5977): 
,E/SMD     (  291): DCD OFF
,I/jxcore-log( 5977): getBuffer is called!!!!
I/jxcore-log( 5977): 
,V/AlarmManager( 1022): waitForAlarm result :4
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6025): MountEmulatedStorage()
,E/Zygote  ( 6025): v2
I/libpersona( 6025): KNOX_SDCARD checking this for 10071
I/libpersona( 6025): KNOX_SDCARD not a persona
,I/SELinux ( 6025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1022): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6025 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6025): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6025): TimaSignature is unavailable
,D/ActivityThread( 6025): Added TimaKeyStore provider
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6025): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6025): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6025): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 39195(2MB) AllocSpace objects, 19(308KB) LOS objects, 33% free, 23MB/35MB, paused 2.095ms total 139.559ms
,E/SQLiteLog( 6025): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6025): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice,
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1181): isKioskContainerExistOnDevice,
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only,
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1739): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1739): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1739): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1739): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6025): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication,
,E/BooksSync( 6025): Soft error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6025): Sync error
E/BooksSync( 6025): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6025): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6025): Finished books sync
,I/ActivityManager( 1022): Killing 4968:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62508, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,W/libprocessgroup( 1022): failed to open /acct/uid_10035/pid_4968/cgroup.procs: No such file or directory
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 15s ago
,I/PowerManagerService( 1022): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1022): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1022): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2063, ws=null) (elapsedTime=56695)
,D/BluetoothAdapter( 5977): disable()
,D/SettingsProvider( 1022): name = bluetooth_on
,D/BluetoothAdapterState( 2636): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2636): Setting state to 13
,I/BluetoothAdapterState( 2636): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2636): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 2636): updateAdapterState state is 13
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2636): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 2636): Autoconnection is available 
D/BluetoothAdapterService( 2636): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2636): terminating service from this receiver
D/BluetoothSocket( 2636): close() in, this: android.bluetooth.BluetoothSocket@19322e4a, channel: 19, state: LISTENING
,D/BluetoothSocket( 2636): close() this: android.bluetooth.BluetoothSocket@19322e4a, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d6332f2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1bb471bbmSocket: android.net.LocalSocket@381d96d8 impl:android.net.LocalSocketImpl@2b9f3a31 fd:FileDescriptor[74]
D/BluetoothSocket( 2636): Closing mSocket: android.net.LocalSocket@381d96d8 impl:android.net.LocalSocketImpl@2b9f3a31 fd:FileDescriptor[74]
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterProperties( 2636): onBluetoothDisable()
D/BluetoothAdapterProperties( 2636): mDiscovering is false
D/SecContentProvider( 1022): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2636): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,W/InputMethodManagerService( 1022): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1022): [BT Setting State] State =13
,D/BluetoothTile( 1181):  onBluetoothStateChange:
,D/SecContentProvider( 1022): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1022): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1022): mCursor = null
,D/WifiService( 1022): setWifiEnabled: false pid=5977, uid=10345
,D/SettingsProvider( 1022): name = wifi_on
,D/BluetoothTile( 1181):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
D/BluetoothTile( 1181):  getBluetoothState : 13
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,E/WifiStateMachine( 1022): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1393): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1393): wlan0: Setting scan request: 0 sec 0 usec
,I/jxcore-log( 5977): ****TEST TOOK:  5085  ms ****
I/jxcore-log( 5977): 
,D/STATUSBAR-QSTileView( 1181): onStateChanged: Bluetooth
I/wpa_supplicant( 1393): P2P: Current p2p state = IDLE
I/jxcore-log( 5977): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5977): 
,I/wpa_supplicant( 1393): Scan requested (ret=0) - scan timeout 30 seconds
I/SamsungIME( 1861): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 1022): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/BluetoothEventManager( 1321): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService( 1022): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1181): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/BluetoothAdapterProperties( 2636): Scan Mode:20
,E/WifiNative-wlan0( 1022): do suspend true
,D/BluetoothAdapterState( 2636): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2636): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2636): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 2636): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 2636): cmd socket is not created
,D/btif_config_util( 2636): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2636): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2636): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/BluetoothSocket( 2636): close() in, this: android.bluetooth.BluetoothSocket@96ce516, channel: 5, state: LISTENING
D/BluetoothSocket( 2636): close() this: android.bluetooth.BluetoothSocket@96ce516, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5ee9d43, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@362e6e97mSocket: android.net.LocalSocket@17414884 impl:android.net.LocalSocketImpl@24fc486d fd:FileDescriptor[76]
D/BluetoothSocket( 2636): Closing mSocket: android.net.LocalSocket@17414884 impl:android.net.LocalSocketImpl@24fc486d fd:FileDescriptor[76]
,I/BtOppRfcommListener( 2636): stopping Accept Thread
D/BluetoothSocket( 2636): close() in, this: android.bluetooth.BluetoothSocket@eca3ca2, channel: 12, state: LISTENING
D/BluetoothSocket( 2636): close() this: android.bluetooth.BluetoothSocket@eca3ca2, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d3bd7b5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31e15d33mSocket: android.net.LocalSocket@2fcc68f0 impl:android.net.LocalSocketImpl@3ba1fe69 fd:FileDescriptor[79]
D/BluetoothSocket( 2636): Closing mSocket: android.net.LocalSocket@2fcc68f0 impl:android.net.LocalSocketImpl@3ba1fe69 fd:FileDescriptor[79]
,I/BtOppRfcommListener( 2636): BluetoothSocket listen thread finished
,W/ContextImpl( 1321): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,V/BluetoothOppManager( 2636): cleanUp...
,W/bt-l2cap( 2636): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x001b not found for deregistration
,D/BluetoothPbap( 1321): Proxy object disconnected
D/PbapServerProfile( 1321): Bluetooth service disconnected
,D/DockEventReceiver( 1321): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1321): onReceive
,V/BluetoothStatusReceiver( 1181): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1181): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6061): MountEmulatedStorage()
I/libpersona( 6061): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6061): v2
I/libpersona( 6061): KNOX_SDCARD not a persona
I/SELinux ( 6061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6061 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6061): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6061): TimaSignature is unavailable
D/ActivityThread( 6061): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6061): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 6061): Key for secure DB is newly created,
D/UserAnalysis.SecurePlaceDbHelper( 6061): SecurePlaceDbHelper() 
D/UserAnalysis( 6061): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6061): onCreate(),
,I/ActivityManager( 1022): Killing 4477:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/IntelligenceServiceApplication( 6061): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 6061): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6061): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/AuthorizationBluetoothService( 1739): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/bt-l2cap( 2636): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2636): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2636): ag scb idx 1 not allocated
W/bt-btif ( 2636): ag scb idx 2 not allocated
E/bt-btif ( 2636): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2636): exiting userial_read_thread
D/bt_userial_mct( 2636): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2636): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2636): hw_epilog_process
D/bt_userial_mct( 2636): userial_close
I/bt_vendor( 2636): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/AndroidRuntime( 6059): 
D/AndroidRuntime( 6059): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6059): CheckJNI is OFF,
D/AndroidRuntime( 6059): readGMSProperty: start
D/AndroidRuntime( 6059): readGMSProperty: already setted!!,
D/AndroidRuntime( 6059): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6059): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6059): readGMSProperty: end
D/AndroidRuntime( 6059): addProductProperty: start
,E/AffinityControl( 6059): AffinityControl: registerfunction enter,
,W/libprocessgroup( 1022): failed to open /acct/uid_10108/pid_4477/cgroup.procs: No such file or directory,
,D/AndroidRuntime( 6059): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1022): START PACKAGE DELETE: observer{428603333}
D/PackageManager( 1022): pkg{<packageName>}
D/PackageManager( 1022): user{0}
D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{3}
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1022): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1022): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1022): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1022): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1022): !@killApplicatoin: 10345, uninstall pkg
,I/ActivityManager( 1022): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 5977:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/bt_vendor( 2636): bt-vendor : BT_VND_OP_POWER_CTRL: Off,
I/bt_vendor( 2636): bluetooth satus is on
I/bt_vendor( 2636): bt-vendor : resetting BT status,
I/bt_vendor( 2636): Starting hciattach daemon,
D/WifiP2pService( 1022): InactiveState{ what=147461 }
I/bt_vendor( 2636): try to set false
D/WifiP2pService( 1022): P2pEnabledState{ what=147461 },
I/wpa_supplicant( 1393): nl80211: Received scan results (2 BSSes)
D/WifiP2pService( 1022): DefaultState{ what=147461 }
I/bt_vendor( 2636): Starting hciattach daemon
,I/bt_vendor( 2636): try to set false
I/bt_vendor( 2636): cleanup,
I/GKI_LINUX( 2636): gki_task task_id=0 [BTU] terminating
D/WifiP2pService( 1022): InactiveState{ what=143375 },
I/GKI_LINUX( 2636): GKI_exit_task 0 done
D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
I/GKI_LINUX( 2636): GKI_shutdown(): task [BTU] terminated
,W/PackageSettings( 1022): Skipping PackageSetting{3d167f8e com.test.thalitest/10338} due to missing metadata
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{3ea3cd7f u0 com.example.hello/.MainActivity t19}
,E/JavaBinder( 1022): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1022): Focus left window: 5977
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1022): Focused application released
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/BluetoothAdapterState( 2636): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2636): isSecureModeOn:false
D/BluetoothAdapterService( 2636): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.gatt.GattService
I/ActivityManager( 1022): Force stopping com.example.hello appid=10345 user=0: pkg removed
,W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2636): handleDebugAction() action=null
W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.GattService( 2636): Received stop request...Stopping profile...
D/BtGatt.GattService( 2636): stop()
,D/BtGatt.AdvertiseManager( 2636): advertise clients cleared
,I/art     ( 3928): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 913us total 43.707ms
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
V/NativeCrypto( 1739): Read error: ssl=0xb7c19938: I/O error during system call, Connection timed out
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService,
,D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1022): updateNetworkInfo()
E/ConnectivityService( 1022): updateNetworkInfo()
W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.a2dp.A2dpService
,V/NativeCrypto( 1739): SSL shutdown failed: ssl=0xb7c19938: I/O error during system call, Broken pipe
,D/HeadsetService( 2636): Received stop request...Stopping profile...,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1022): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false,
I/art     ( 5781): Explicit concurrent mark sweep GC freed 7701(361KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 847us total 83.760ms
I/art     ( 5268): Explicit concurrent mark sweep GC freed 9893(663KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 944us total 92.308ms
,I/qtaguid ( 1022): Tagging socket 350 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1022, getuid(): 1000
,I/qtaguid ( 1022): Untagging socket 350
I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1022): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1022): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1022): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1022): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1022): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524292
D/WIFI_P2P( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): ValidatedState{ when=-5ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/SamsungIME( 1861): mOCRHelper is null
D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
W/GeofencerStateMachine( 1839): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/WifiP2pService( 1022): InactiveState{ what=131204 }
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/WifiP2pService( 1022): P2pEnabledState{ what=131204 }
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/WifiNetworkAgent( 1022): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1022): sending p2p connection changed broadcast: FAILED
D/ConnectivityService( 1022): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): doQuit - quitNow()
D/WIFI    ( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.hid.HidService
,E/ConnectivityService( 1022): updateNetworkInfo()
,D/ConnectivityService( 1022): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
,I/KLMS-2.5.123: ( 3653): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 24 18:26:43 GMT+01:00 2015
,D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
,V/NetworkStats( 1022): updateIfacesLocked()
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/StatusBar.NetworkController( 1181): EthernetConnected: false
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,V/NetworkStats( 1022): performPollLocked() took 5ms
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.hdp.HealthService
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/HeadsetProfile( 1321): Bluetooth service disconnected
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiDisplayController( 1022): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1022): onP2pDisconnected
,D/RCPManagerService( 1022): PackageReceiver onReceive()
I/KLMS-2.5.123: ( 3653): KLMSAbstractReciever(): onReceive().END.
,I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1022): no available spell checker services found
,D/WifiP2pService( 1022): sending p2p connection changed broadcast: DISCONNECTED
,E/ConnectivityService( 1022): updateNetworkInfo()
,D/IpRemoteDisplayController( 1022): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1022): WfdBridgeServer is already null
,D/WifiP2pService( 1022): P2pDisablingState
,D/WifiP2pService( 1022): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1022): p2p socket connection lost
,D/WifiP2pService( 1022): P2pDisabledState
,E/WifiNative-wlan0( 1022): do suspend true
,I/KLMS-2.5.123: ( 3653): KLMSIntentService(): onCreate()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/KLMS-2.5.123: ( 3653): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.pan.PanService
I/KLMS-2.5.123: ( 3653): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3653): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3653): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3653): KLMSIntentService(): listeningToPackageRemoved().START
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/WifiDisplayController( 1022): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/WifiDisplayController( 1022): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1022): disconnect
D/WifiDisplayController( 1022): updateConnection
D/WifiDisplayController( 1022): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,I/KLMS-2.5.123: ( 3653): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 1022): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1022): DefaultState{ what=143375 }
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 29276(1996KB) AllocSpace objects, 7(116KB) LOS objects, 33% free, 24MB/36MB, paused 6.520ms total 256.812ms
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/WifiDisplayController( 1022): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1022): onP2pDisconnected
D/IpRemoteDisplayController( 1022): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1022): WfdBridgeServer is already null
,W/BluetoothAdapterService( 2636): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AllShareCastTile( 1181): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1181): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/splitIntent( 1022): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1022): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1022): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/RegisteredServicesCache( 1447): empty dynamic service
,I/wpa_supplicant( 1393): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 1022): delete codoeFile: 
,D/AASAuninstall( 1022): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello,
,I/AASA_removePackage( 1022): UID=10345 Target=com.example.hello
I/libpersona( 6096): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6096): MountEmulatedStorage()
I/libpersona( 6096): KNOX_SDCARD not a persona
E/Zygote  ( 6096): v2
I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6096 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/PackageManager( 1022): result of delete: 1{428603333}
I/SELinux ( 6096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AndroidRuntime( 6059): Shutting down VM
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,W/BluetoothAdapterService( 2636): Not skipping com.broadcom.bt.service.sap.SapService
,E/SMD     (  291): DCD OFF
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(0)
,D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,I/KLMS-2.5.123: ( 3653): KLMSIntentService(): listeningToPackageRemoved().END
,D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1181): onReceive : 0, 0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/WifiCredService( 1321): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/TimaKeyStoreProvider( 6096): TimaSignature is unavailable
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/ActivityThread( 6096): Added TimaKeyStore provider
,D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2636): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2636): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2636): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2636): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2636): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2636): Stopping profile services that were post enabled
E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/A2dpService( 2636): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2636): Exit Disconnected: -1
,I/KLMS-2.5.123: ( 3653): KLMSIntentService(): onDestroy()
,D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
,I/wpa_supplicant( 1393): Blacklist: Clear (all) 
,E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2636): Profile still running: com.android.bluetooth.hid.HidService
,D/HidService( 2636): Received stop request...Stopping profile...
D/HidService( 2636): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2636): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2636): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2636): Cleaning up Bluetooth GID callback object
,D/BluetoothA2dp( 1321): Proxy object disconnected
,D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
,D/A2dpProfile( 1321): Bluetooth service disconnected
,W/BluetoothHeadsetServiceJni( 2636): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2636): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2636): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
,D/BluetoothInputDevice( 1321): Proxy object disconnected
D/HidProfile( 1321): Bluetooth service disconnected
,D/PanService( 2636): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
,D/BluetoothMapService( 2636): Received stop request...Stopping profile...
,I/wpa_supplicant( 1393): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering( 1022): interfaceLinkStateChanged p2p0, false
D/Tethering( 1022): interfaceStatusChanged p2p0, false,
I/Nat464Xlat( 1022): interfaceLinkStateChanged p2p0, false
D/BluetoothPan( 1321): BluetoothPAN Proxy object disconnected
D/PanProfile( 1321): Bluetooth service disconnected
D/elm:15121( 6096): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6096): ELMEngine.ELMEngine( context ).
D/elm:15121( 6096): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6096): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
,D/SapService( 2636): Received stop request...Stopping profile...
,D/SapService( 2636): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2636): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b7c1218
D/BluetoothMap( 1321): Proxy object disconnected
D/MapProfile( 1321): Bluetooth service disconnected
D/elm:15121( 6096): ElmAgentService : onCreate()
,D/elm:15121( 6096): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6096): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 6096): MDMBridge.getInstance()
I/wpa_supplicant( 1393): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
D/elm:15121( 6096): MDMBridge.getAllLicenseInfoFromSDK()
I/wpa_supplicant( 1393): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1393): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1393): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1393): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1022): InitialState.processMessage what=4
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2636): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2636): Proxy object disconnected
D/BluetoothAdapterService( 2636): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2636): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2636): GKI_exit_task 2 done
I/GKI_LINUX( 2636): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
E/Tethering( 1022): No numeric data
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2636): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/elm:15121( 6096): MDMBridge.getAllLicenseInfoFromSDK()
,D/BluetoothAdapterService( 2636): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2636): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2636): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2636): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2636): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2636): Cleaning up Bluetooth PAN callback object
D/Bluetoothsap( 1321): BluetoothSAP Proxy object disconnected
D/SapProfile( 1321): Bluetooth service disconnected
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
,E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2636): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2636): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(729551384)( 2636): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2636): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2636): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
,W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1022): clearTetheredNotification()
D/Tethering( 1022): interfaceStatusChanged wlan0, false
D/BluetoothAdapterState( 2636): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2636): Setting state to 10
I/BluetoothAdapterState( 2636): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2636): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2636): updateAdapterState state is 10
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/BluetoothAdapterService( 2636): Autoconnection is available 
D/BluetoothAdapterService( 2636): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2636): Entering OffState
D/BluetoothA2dp( 1022): onBluetoothStateChange: up=false
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1181): updateTetherState():false, false
,D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked() took 5ms
,D/elm:15121( 6096): ElmAgentService : onDestroy().
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BluetoothAdapter( 1456): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1456): Bluetooth is turned off, stop adv and scan
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,I/ActivityManager( 1022): Killing 5227:com.google.android.gm/u0a99 (adj 15): empty #31
,D/BluetoothMap( 1321): onBluetoothStateChange: up=false
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothAdapter( 1438): onBluetoothStateChange: up=false
,W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 1438): Bluetooth is turned off, stop adv and scan
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothPbap( 1321): onBluetoothStateChange: up=false
,D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10345
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,D/BluetoothAdapter( 1181): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1181): Bluetooth is turned off, stop adv and scan
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1022): removeObsoleteFile: deleting file=19_task.xml
,V/EnterpriseBillingPolicy( 1022): uID is 10345
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
,D/WifiScanningService( 1022): SCAN_AVAILABLE : 1
D/RttService( 1022): SCAN_AVAILABLE : 1
,D/RttService( 1022): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService( 1022): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothInputDevice( 1321): onBluetoothStateChange: up=false
,D/Tethering( 1022): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/AudioService( 1022): onServiceDisconnected: Bluetooth profile: 1
D/Tethering( 1022): MasterInitialState.processMessage what=3
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothA2dp( 2636): onBluetoothStateChange: up=false
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1839): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1839): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1022): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1022): Bluetooth is turned off, stop adv and scan
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3,
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Bluetoothsap( 1321): onBluetoothStateChange: up=false
D/Bluetoothsap( 1321): Unbinding service...
,D/BluetoothA2dp( 1321): onBluetoothStateChange: up=false
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/BluetoothAdapter( 1321): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1321): Bluetooth is turned off, stop adv and scan
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 2636): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2636): Bluetooth is turned off, stop adv and scan
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/BluetoothAdapter( 1447): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1447): Bluetooth is turned off, stop adv and scan
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/UsbSettingsManager( 1022): clearDefaults: com.example.hello
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/BluetoothManagerService( 1022): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService( 1022): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/art     ( 6059): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/GKI_LINUX( 2636): gki_task task_id=1 [BTIF] terminating
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,I/GKI_LINUX( 2636): GKI_exit_task 1 done
I/GKI_LINUX( 2636): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2636): cleanupNative: return from cleanup
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1181): 1039214619: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1181):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1181): 1039214619: getState() :  mService = null. Returning STATE_OFF
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1181):  getBluetoothState : 10
,D/BluetoothAdapter( 1181): 1039214619: getState() :  mService = null. Returning STATE_OFF
,I/SamsungIME( 1861): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1181): 1039214619: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1181): 1039214619: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1022): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1022): setIconVisibility slot=bluetooth visible=false
D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/CrashAnrDetector( 1022): onPackageRemoved : com.example.hello
,V/BluetoothEventManager( 1321): Received android.bluetooth.adapter.action.STATE_CHANGED
W/libprocessgroup( 1022): failed to open /acct/uid_10099/pid_5227/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1181): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/art     ( 2636): System.exit called, status: 0
I/AndroidRuntime( 2636): VM exiting with result code 0, cleanup skipped.
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1393): Blacklist: Clear (all) 
,E/WifiStateMachine( 1022): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
,W/InputMethodManagerService( 1022): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1022): [BT Setting State] State =10
I/InputMethodManagerService( 1022): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/PCWCLIENTTRACE_PushUtil( 5677): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5677): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5677): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5677): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5792): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5792): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/wpa_supplicant( 1393): wlan0: CTRL-EVENT-TERMINATING 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,I/ActivityManager( 1022): Process com.android.bluetooth (pid 2636)(adj 0) has died(86,682)
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PackagesMonitor( 4987): PackagesMonitor onReceive :com.example.hello
,I/ApplicationPolicy( 1022): updateDataUsageMap
,D/GpsLocationProvider( 1022): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/Mms/FreeMessageStatusReceiver( 4740): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1022): enable value -1
,I/TactileAssist( 1022): internal enable value -1
I/TactileAssist( 1022): intensity value -1
I/TactileAssist( 1022): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4740): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4740): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1022): List of disabled apps :
,E/WifiStateMachine( 1022): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1022): callSECApiBoolean - ID [21]
,W/Settings( 5887): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1181): onReceive : 1, 0
,W/Settings( 1839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiCredService( 1321): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/Compatibility( 5743): onReceive() it will make start service
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 6061): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.

```
