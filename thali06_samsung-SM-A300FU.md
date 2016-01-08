#### Test 5024228542a63d7_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  289): DCD OFF
--------- beginning of system
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1019): stay LED for fully charged
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2627): Disconnected process message: 10
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,D/AndroidRuntime( 5962): 
D/AndroidRuntime( 5962): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5962): CheckJNI is OFF
D/AndroidRuntime( 5962): readGMSProperty: start
D/AndroidRuntime( 5962): readGMSProperty: already setted!!
D/AndroidRuntime( 5962): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5962): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5962): readGMSProperty: end
D/AndroidRuntime( 5962): addProductProperty: start
E/AffinityControl( 5962): AffinityControl: registerfunction enter
D/AndroidRuntime( 5962): Calling main entry com.android.commands.am.Am
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
E/Zygote  ( 5975): MountEmulatedStorage()
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5975 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 5975): v2
I/libpersona( 5975): KNOX_SDCARD checking this for 10346
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/libpersona( 5975): KNOX_SDCARD not a persona
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1494
I/SELinux ( 5975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 5962): Shutting down VM
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5975): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5975): TimaSignature is unavailable
D/ActivityThread( 5975): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
V/ActivityThread( 1494): updateVisibility : ActivityRecord{101cf6dc token=android.os.BinderProxy@12e6c1bc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1494): onTrimMemory. Level: 20
I/WebViewFactory( 5975): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5975): Time to load native libraries: 2 ms (timestamps 7287-7289)
I/LibraryLoader( 5975): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5975): Binding Chromium to main looper Looper (main, tid 1) {105e6777}
I/LibraryLoader( 5975): Expected native library version number "",actual native library version number ""
I/chromium( 5975): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5975): Initializing chromium process, singleProcess=true
W/art     ( 5975): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5975): ApplicationContext is null in ApplicationStatus
W/art     ( 5962): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5975): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5975): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5975): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5975): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5975): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5975): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5975): Local Branch: 
I/Adreno-EGL( 5975): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5975): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5975):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 5975): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5975): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5975): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5975): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5975): CordovaWebView is running on device made by: samsung
W/art     ( 5975): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5975): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{36492bd2 u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 5975): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 5975): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5975): updateVisibility : ActivityRecord{166f5380 token=android.os.BinderProxy@1628e0b2 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 5975): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5975): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 5975
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5975): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5975): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5975): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 5975): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
,W/IInputConnectionWrapper( 5975): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 1019): Displayed Component not be shown by security: +634ms (total +718ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{36492bd2 u0 com.example.hello/.MainActivity t19} time:87834
,I/SurfaceFlinger(  258): id=12 Removed iello (7/9)
,I/SurfaceFlinger(  258): id=12 Removed iello (-2/9)
,I/Timeline( 5975): Timeline: Activity_idle id: android.os.BinderProxy@1628e0b2 time:87843
,I/SamsungIME( 1817): getCurrentCandidateView
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,D/SamsungIME( 1817): Dismiss ExpandCandiate
,W/BindingManager( 5975): Cannot call determinedVisibility() - never saw a connection for the pid: 5975
,I/chromium( 5975): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1817): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1817): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1817): KeybaordView init() : load resources
,I/SamsungIME( 1817): getCurrentKeyboard
,I/SamsungIME( 1817): getTextKeyboard
,D/SamsungIME( 1817): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5975): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5975): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 5975): JniHelper::setJavaVM(0xb78ef448), pthread_self() = -1209764448
,D/JX-Cordova( 5975): jxcore cordova android initializing
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/jxcore-log( 5975): Initializing JXcore engine
W/jxcore-log( 5975): JXcore engine is ready
,E/audit   ( 1865): type=1400 msg=audit(1452276648.941:205): avc:  denied  { ioctl } for  pid=6023 comm="Thread-1031" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1865):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1865): type=1300 msg=audit(1452276648.941:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ee898e8 items=0 ppid=309 ppcomm=main pid=6023 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="Thread-1031" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1865): type=1320 msg=audit(1452276648.941:205): 
,W/jxcore-log( 5975): Starting JXcore engine
,W/jxcore-log( 5975): Platform android
W/jxcore-log( 5975): 
W/jxcore-log( 5975): Process ARCH arm
W/jxcore-log( 5975): 
,I/jxcore-log( 5975): JXcore Cordova bridge is ready!
I/jxcore-log( 5975): 
,W/jxcore-log( 5975): JXcore engine is started
,E/jxcore  ( 5975): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5975): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:267:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,D/PhoneWindow( 5975): *FMB* installDecor mIsFloating : true,
D/PhoneWindow( 5975): *FMB* installDecor flags : 8388610
,D/InputDispatcher( 1019): Focus left window: 5975
,D/InputDispatcher( 1019): Focus entered window: 5975
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/PhoneWindow( 5975): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5975): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, NainActivit
,D/SRIB_DCS( 5975): log_dcs ThreadedRenderer::initialize entered! 
,V/AlarmManager( 1019): waitForAlarm result :4
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6026): MountEmulatedStorage(),
E/Zygote  ( 6026): v2
I/libpersona( 6026): KNOX_SDCARD checking this for 10071
I/libpersona( 6026): KNOX_SDCARD not a persona
,I/SELinux ( 6026): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6026 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6026): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6026): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6026): TimaSignature is unavailable
,D/ActivityThread( 6026): Added TimaKeyStore provider,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6026): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6026): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/BooksSync( 6026): Starting books sync for 61035162, extras: ade
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6026): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6026): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1695): Explicit concurrent mark sweep GC freed 15952(955KB) AllocSpace objects, 3(60KB) LOS objects, 39% free, 7MB/12MB, paused 1.006ms total 40.277ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/PersonaManager( 1170): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1170): Icon Only
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/StatusBar( 1170): Icon Only
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6026): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6026): Soft error
E/BooksSync( 6026): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6026): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6026): Sync error
E/BooksSync( 6026): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6026): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6026): Finished books sync
,I/ActivityManager( 1019): Killing 4929:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64863, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1170): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,W/libprocessgroup( 1019): failed to open /acct/uid_10108/pid_4929/cgroup.procs: No such file or directory
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 15s ago
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2036, ws=null) (elapsedTime=56901)
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6026): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1170): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,V/AlarmManager( 1019): waitForAlarm result :8
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,D/Finsky  ( 5398): [894] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5398): [894] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1019): stay LED for fully charged
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1170): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,V/AlarmManager( 1019): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1019): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1019): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/SecKeyguardClockView( 1170): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1170): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1170): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1019): [PWL] Off : 30s ago
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog( 1019): !@Sync 3
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 31811(1701KB) AllocSpace objects, 18(292KB) LOS objects, 33% free, 23MB/35MB, paused 2.116ms total 142.585ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5398): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5398): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5398): [1] 5.onFinished: Scheduling replication attempt 2.
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1170): level :100 plugged : 2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/FactoryTest( 5480): Not factory mode
,D/FactoryTest( 5480): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5480): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5480): still no open session command from host, so toast
,W/ContextImpl( 5480): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5480): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5480): Timeline: Activity_launch_request id:com.android.settings time:117027
,E/PersonaManagerService( 1019): inState():  stateMachine is null !!
,I/PersonaManagerService( 1019): PersonaId don't exist
,I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,D/PersonaManager( 1019): isKioskContainerExistOnDevice,
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 5975,
E/MTPRx   ( 5480): started activity for popup
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5480): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5480): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5480): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5480): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5480): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5480): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus entered window: 5975
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 5480): dev.kiessupport is : TRUE
,D/PhoneWindow( 5480): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 5480): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
,D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,V/ActivityThread( 5975): updateVisibility : ActivityRecord{166f5380 token=android.os.BinderProxy@1628e0b2 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/Timeline( 5975): Timeline: Activity_idle id: android.os.BinderProxy@1628e0b2 time:117203
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): mDVFSHelper.release()
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1170): level :100 plugged : 2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/PowerManagerService( 1019): [PWL] Off : 50s ago
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5398): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5398): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5398): [1] 5.onFinished: Scheduling replication attempt 3.
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate,
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1170): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 4,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5398): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5398): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5398): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 75s ago
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4,
,I/BooksSync( 6026): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6026): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
D/PersonaManager( 1170): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1170): Icon Only
,I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6026): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6026): Soft error
E/BooksSync( 6026): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6026): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6026): Sync error
E/BooksSync( 6026): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6026): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6026): Finished books sync
,D/PanelView( 1170): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155735, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 5
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/SecKeyguardClockView( 1170): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1170): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1170): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5398): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5398): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5398): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 105s ago,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :4
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1695): Vacuum at: now=1452276749994 tag=VacuumService
,I/GoogleURLConnFactory( 1695): Using platform SSLCertificateSocketFactory
,W/Uploader( 1695): No account for auth token provided
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1695): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1695): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1695): (HTTPLog)-Thread-203-394944368: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1695): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011
,I/qtaguid ( 1695): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5398): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5398): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5398): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1695): No account for auth token provided
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011
,W/Uploader( 1695): No account for auth token provided
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011
,W/Uploader( 1695): No account for auth token provided
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011,
,W/Uploader( 1695):  no longer exists, so no auth token.
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011,
,W/Uploader( 1695): No account for auth token provided
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  289): DCD OFF
,I/GLSUser ( 1695): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1695): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1695): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1695): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1695): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/Uploader( 1695): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1695): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1695): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1695): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1695): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1695): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1695): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1695): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1695): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1695): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1695): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1695): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1695): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1170): Icon Only
,I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1695): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1695): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1695, getuid(): 10011
,D/PanelView( 1170): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1695): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1170): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 6,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 6133): 
D/AndroidRuntime( 6133): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6133): CheckJNI is OFF
D/AndroidRuntime( 6133): readGMSProperty: start
D/AndroidRuntime( 6133): readGMSProperty: already setted!!
D/AndroidRuntime( 6133): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6133): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6133): readGMSProperty: end
D/AndroidRuntime( 6133): addProductProperty: start
E/AffinityControl( 6133): AffinityControl: registerfunction enter
D/AndroidRuntime( 6133): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{335312960}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1019): !@killApplicatoin: 10346, uninstall pkg
I/ActivityManager( 1019): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 5975:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{78a5c4f com.test.thalitest/10338} due to missing metadata
I/WindowState( 1019): WIN DEATH: Window{10b4a094 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (5/9)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/9)
I/ActivityManager( 1019):   Force finishing activity ActivityRecord{36492bd2 u0 com.example.hello/.MainActivity t19}
I/WindowState( 1019): WIN DEATH: Window{123c94e2 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  258): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1019): Focus left window: 5975
W/ActivityManager( 1019): Spurious death for ProcessRecord{30a2e379 5975:com.example.hello/u0a346}, curProc for 5975: null
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/InputDispatcher( 1019): Focused application released
I/ActivityManager( 1019): Force stopping com.example.hello appid=10346 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4047): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 684us total 27.915ms
I/art     ( 5285): Explicit concurrent mark sweep GC freed 9943(665KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 863us total 39.936ms
E/SamsungIME( 1817): mOCRHelper is null
W/GeofencerStateMachine( 1846): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3739): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 19:13:28 GMT+01:00 2016
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3739): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6146): MountEmulatedStorage()
E/Zygote  ( 6146): v2
I/libpersona( 6146): KNOX_SDCARD checking this for 10090
I/libpersona( 6146): KNOX_SDCARD not a persona
I/SELinux ( 6146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): onCreate()
I/SELinux ( 6146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3739): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6146 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3739): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): PACKAGE_REMOVED
D/TimaKeyStoreProvider( 6146): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): listeningToPackageRemoved().START
D/ActivityThread( 6146): Added TimaKeyStore provider
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
D/RegisteredServicesCache( 1453): empty dynamic service
D/elm:15121( 6146): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6146): ELMEngine.ELMEngine( context ).
D/elm:15121( 6146): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/art     ( 1019): Explicit concurrent mark sweep GC freed 49636(3MB) AllocSpace objects, 62(1001KB) LOS objects, 33% free, 24MB/36MB, paused 4.772ms total 200.119ms
I/art     ( 1019): WaitForGcToComplete blocked for 150.208ms for cause Explicit
D/elm:15121( 6146): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6146): ElmAgentService : onCreate()
D/elm:15121( 6146): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6146): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6146): MDMBridge.getInstance()
D/elm:15121( 6146): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6146): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6146): ElmAgentService : onDestroy().
D/RCPManagerService( 1019): PackageReceiver onReceive()
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/ActivityManager( 1019): Killing 5244:com.google.android.gm/u0a99 (adj 15): empty #31
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3739): KLMSIntentService(): onDestroy()
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SSRM:n  ( 1019): SIOP:: AP = 260
I/art     ( 1019): Explicit concurrent mark sweep GC freed 13610(731KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 2.986ms total 159.763ms
W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10346
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10346
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
D/TaskPersister( 1019): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
D/PackageManager( 1019): delete codoeFile: 
I/PCWCLIENTTRACE_PushUtil( 5680): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5680): sales region : global
I/AASA_removePackage( 1019): UID=10346 Target=com.example.hello
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
I/PCWCLIENTTRACE_PushUtil( 5680): getPushTypeList : [SPP, GCM]
D/PackageManager( 1019): result of delete: 1{335312960}
I/PCWCLIENTTRACE_SYSTEMReceiver( 5680): [onReceive] - android.intent.action.PACKAGE_REMOVED
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SA      ( 5796): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5796): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10346 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6133): Shutting down VM
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_5244/cgroup.procs: No such file or directory
I/PackagesMonitor( 5002): PackagesMonitor onReceive :com.example.hello
D/Mms/FreeMessageStatusReceiver( 4717): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/Mms/FreeMessageReceiverService( 4717): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
D/Mms/FreeMessageReceiverService( 4717): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1019): List of disabled apps :
D/Compatibility( 5775): onReceive() it will make start service
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5775): onHandleIntent()
D/Compatibility( 5775): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10346, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5775): found: 2
D/Compatibility( 5775): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5775): skipping ResolveInfo{10c80413 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5775): considering ResolveInfo{1019b650 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5775): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5775): enabling receiver ResolveInfo{25f3049 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5775): enabling receiver ResolveInfo{24b3fd4e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/Zygote  ( 6166): MountEmulatedStorage()
E/Zygote  ( 6166): v2
I/libpersona( 6166): KNOX_SDCARD checking this for 10055
I/libpersona( 6166): KNOX_SDCARD not a persona
I/SELinux ( 6166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6166 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 6166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/Compatibility( 5775): enabling receiver ResolveInfo{3024ce6f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5775): enabling receiver ResolveInfo{f6be77c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5775): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6166): TimaSignature is unavailable
D/ActivityThread( 6166): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6166): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6166): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6166): SecurePlaceDbHelper() 
D/UserAnalysis( 6166): Create SecureDbHelper
D/IntelligenceServiceApplication( 6166): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6166): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/art     ( 6133): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/IntelligenceServiceApplication( 6166): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetection::stopService] Service stopped.
W/ContextImpl( 5079): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6183): MountEmulatedStorage()
I/libpersona( 6183): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6183): v2
I/libpersona( 6183): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6183): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
I/ActivityManager( 1019): Killing 5144:com.google.android.talk/u0a102 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/TimaKeyStoreProvider( 6183): TimaSignature is unavailable
D/ActivityThread( 6183): Added TimaKeyStore provider
W/ResourcesManager( 6183): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BluetoothAdapter( 6166): cancelDiscovery
D/BluetoothAdapterProperties( 2627): mDiscovering is false
E/BluetoothAdapterService( 2627): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6166): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6166): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6166): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/RCPManager( 6183):  in createShortcut() for packageName: com.example.hello userId0
E/SQLiteLog( 6166): (10) unixWrite() File Descriptor : 25 gets errno : 9
D/RCPManagerService( 1019):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1019): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5814): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5814): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
E/SQLiteLog( 6166): (10) unixWrite() File Descriptor : 25 gets errno : 9
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/SQLiteDatabase( 6166): Error inserting timestamp=1452276809060 message=Predictor: service is stopped by Application.onCreate
E/SQLiteDatabase( 6166): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6166): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 6166): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 6166): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6166): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6166): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6166): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6166): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6166): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6166): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6166): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 6166): It failed to insert to dump_log table
E/SQLiteLog( 6166): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6166): (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6166): Error inserting timestamp=1452276809129 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 6166): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6166): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6166): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 6166): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 6166): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6166): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6166): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6166): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6166): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6166): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6166): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6166): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 6166): It failed to insert to dump_log table
I/FilterInstaller( 5814): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5814): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5814): before removeFromFS
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6200): MountEmulatedStorage()
E/Zygote  ( 6200): v2
I/libpersona( 6200): KNOX_SDCARD checking this for 10095
I/libpersona( 6200): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6200 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/SELinux ( 6200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_5144/cgroup.procs: No such file or directory
E/Zygote  ( 6212): MountEmulatedStorage()
E/Zygote  ( 6212): v2
I/libpersona( 6212): KNOX_SDCARD checking this for 1000
I/libpersona( 6212): KNOX_SDCARD not a persona
I/SELinux ( 6212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6212 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6212): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6200): TimaSignature is unavailable
D/ActivityThread( 6200): Added TimaKeyStore provider

```
