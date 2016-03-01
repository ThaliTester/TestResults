#### Test 61248225a3bd1fe_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  289): DCD OFF
--------- beginning of system
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1427): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1427): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2664): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2664): Disconnected process message: 10
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1016): SIOP:: AP = 290
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/AndroidRuntime( 5955): 
D/AndroidRuntime( 5955): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5955): CheckJNI is OFF
D/AndroidRuntime( 5955): readGMSProperty: start
D/AndroidRuntime( 5955): readGMSProperty: already setted!!
D/AndroidRuntime( 5955): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5955): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5955): readGMSProperty: end
D/AndroidRuntime( 5955): addProductProperty: start
E/AffinityControl( 5955): AffinityControl: registerfunction enter
D/AndroidRuntime( 5955): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5967): MountEmulatedStorage()
E/Zygote  ( 5967): v2
I/libpersona( 5967): KNOX_SDCARD checking this for 10346
I/libpersona( 5967): KNOX_SDCARD not a persona
I/SELinux ( 5967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5967 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1016): Focused application set to: xxxx
I/SELinux ( 5967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/InputDispatcher( 1016): Focus left window: 1494
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5967): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5955): Shutting down VM
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5967): TimaSignature is unavailable
D/ActivityThread( 5967): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1016): Display changed displayId=0
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1494): updateVisibility : ActivityRecord{17f30c79 token=android.os.BinderProxy@3838b07f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1494): onTrimMemory. Level: 20
I/WebViewFactory( 5967): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5967): Time to load native libraries: 2 ms (timestamps 7034-7036)
I/LibraryLoader( 5967): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5967): Binding Chromium to main looper Looper (main, tid 1) {30bc6b}
I/LibraryLoader( 5967): Expected native library version number "",actual native library version number ""
I/chromium( 5967): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5967): Initializing chromium process, singleProcess=true
W/art     ( 5967): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5967): ApplicationContext is null in ApplicationStatus
W/art     ( 5955): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/chromium( 5967): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5967): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5967): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5967): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5967): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5967): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5967): Local Branch: 
I/Adreno-EGL( 5967): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5967): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5967):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 5967): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5967): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5967): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5967): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5967): CordovaWebView is running on device made by: samsung
,W/art     ( 5967): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5967): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5967): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/chromium( 5967): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5967): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5967): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 5967
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 5967): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5967): Initialized EGL, version 1.4
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/OpenGLRenderer( 5967): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5967): Enabling debug mode 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/ActivityThread( 5967): updateVisibility : ActivityRecord{bbc02a4 token=android.os.BinderProxy@39494a36 {com.example.hello/com.example.hello.MainActivity}} show : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,I/Timeline( 5967): Timeline: Activity_idle id: android.os.BinderProxy@39494a36 time:87562
,W/IInputConnectionWrapper( 5967): showStatusIcon on inactive InputConnection
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Displayed Component not be shown by security: +639ms (total +725ms)
W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{21fa3fbe u0 com.example.hello/.MainActivity t19} time:87587
I/SurfaceFlinger(  258): id=12 Removed iello (7/9)
I/SurfaceFlinger(  258): id=12 Removed iello (-2/9)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1884): getCurrentCandidateView
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1884): Dismiss ExpandCandiate
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SamsungIME( 1884): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BindingManager( 5967): Cannot call determinedVisibility() - never saw a connection for the pid: 5967
,I/chromium( 5967): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/SamsungIME( 1884): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1884): KeybaordView init() : load resources
,I/SamsungIME( 1884): getCurrentKeyboard
I/SamsungIME( 1884): getTextKeyboard
,D/SamsungIME( 1884): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5967): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5967): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5967): JniHelper::setJavaVM(0xb8c8d448), pthread_self() = -1189226856
,D/JX-Cordova( 5967): jxcore cordova android initializing
,W/jxcore-log( 5967): Initializing JXcore engine
,W/jxcore-log( 5967): JXcore engine is ready
,W/jxcore-log( 5967): Starting JXcore engine
,E/audit   ( 1907): type=1400 msg=audit(1456842828.249:205): avc:  denied  { ioctl } for  pid=5967 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1907):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1907): type=1300 msg=audit(1456842828.249:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=be8fdd58 items=0 ppid=306 ppcomm=main pid=5967 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1907): type=1320 msg=audit(1456842828.249:205): 
,E/SMD     (  289): DCD OFF
,W/jxcore-log( 5967): Platform android
W/jxcore-log( 5967): 
W/jxcore-log( 5967): Process ARCH arm
W/jxcore-log( 5967): 
,I/jxcore-log( 5967): JXcore Cordova bridge is ready!
I/jxcore-log( 5967): 
,W/jxcore-log( 5967): JXcore engine is started
,E/jxcore-log( 5967): >> samsung-SM-A300FU
E/jxcore-log( 5967): 
,I/jxcore-log( 5967): Total memory 1451114496
I/jxcore-log( 5967): 
,I/jxcore-log( 5967): Free memory 25165824
I/jxcore-log( 5967): 
I/jxcore-log( 5967): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5967): 
I/jxcore-log( 5967): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5967): 
,I/jxcore-log( 5967): userPath [ 'www', 'www' ]
I/jxcore-log( 5967): 
,I/jxcore-log( 5967): Size 540 960
I/jxcore-log( 5967): 
,I/jxcore-log( 5967): Screen Brightness 160
I/jxcore-log( 5967): 
,E/jxcore-log( 5967): Dummy Error Log.
E/jxcore-log( 5967): 
,I/jxcore-log( 5967): getBuffer is called!!!!
I/jxcore-log( 5967): 
,V/AlarmManager( 1016): waitForAlarm result :4
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6017): MountEmulatedStorage()
E/Zygote  ( 6017): v2
I/libpersona( 6017): KNOX_SDCARD checking this for 10071
I/libpersona( 6017): KNOX_SDCARD not a persona
I/SELinux ( 6017): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6017): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6017): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6017 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6017): TimaSignature is unavailable
D/ActivityThread( 6017): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6017): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6017): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 17235(959KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 941us total 48.920ms,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6017): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 6017): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6017): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6017): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6017): Soft error
E/BooksSync( 6017): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6017): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6017): Sync error
E/BooksSync( 6017): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6017): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6017): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63663, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1016): Killing 5157:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_10146/pid_5157/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 5967): disable()
,D/SettingsProvider( 1016): name = bluetooth_on
,D/BluetoothAdapterState( 2664): CURRENT_STATE=ON, MSG = USER_TURN_OFF,
D/BluetoothAdapterProperties( 2664): Setting state to 13
I/BluetoothAdapterState( 2664): Bluetooth adapter state changed: 12-> 13,
D/BluetoothAdapterService( 2664): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2664): updateAdapterState state is 13
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2664): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 2664): Autoconnection is available 
,D/BluetoothAdapterService( 2664): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 2664): terminating service from this receiver
,D/BluetoothSocket( 2664): close() in, this: android.bluetooth.BluetoothSocket@28ae4c2b, channel: 19, state: LISTENING
D/BluetoothSocket( 2664): close() this: android.bluetooth.BluetoothSocket@28ae4c2b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c7b59b3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1adb888mSocket: android.net.LocalSocket@26613221 impl:android.net.LocalSocketImpl@1b2e9646 fd:FileDescriptor[74]
D/BluetoothSocket( 2664): Closing mSocket: android.net.LocalSocket@26613221 impl:android.net.LocalSocketImpl@1b2e9646 fd:FileDescriptor[74]
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1016): [BT Setting State] State =13
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 13
,I/SamsungIME( 1884): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,V/BluetoothEventManager( 1315): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,D/WifiService( 1016): setWifiEnabled: false pid=5967, uid=10346
D/SettingsProvider( 1016): name = wifi_on
,D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2664): onBluetoothDisable()
,D/BluetoothAdapterProperties( 2664): mDiscovering is false
,D/SecContentProvider( 1016): uri = 3 selection = isDiscoverableEnabled
I/BluetoothAdapterState( 2664): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2664): Scan Mode:20
,D/BluetoothSocket( 2664): close() in, this: android.bluetooth.BluetoothSocket@4c38007, channel: 5, state: LISTENING
D/BluetoothSocket( 2664): close() this: android.bluetooth.BluetoothSocket@4c38007, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@194beb70, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@24a9d534mSocket: android.net.LocalSocket@357dcf5d impl:android.net.LocalSocketImpl@1aadd0d2 fd:FileDescriptor[76]
D/BluetoothSocket( 2664): Closing mSocket: android.net.LocalSocket@357dcf5d impl:android.net.LocalSocketImpl@1aadd0d2 fd:FileDescriptor[76]
,I/BtOppRfcommListener( 2664): stopping Accept Thread
D/BluetoothSocket( 2664): close() in, this: android.bluetooth.BluetoothSocket@260e15a3, channel: 12, state: LISTENING
D/BluetoothSocket( 2664): close() this: android.bluetooth.BluetoothSocket@260e15a3, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e3a2c7a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1da910a0mSocket: android.net.LocalSocket@1fcd0459 impl:android.net.LocalSocketImpl@3774281e fd:FileDescriptor[79]
D/BluetoothSocket( 2664): Closing mSocket: android.net.LocalSocket@1fcd0459 impl:android.net.LocalSocketImpl@3774281e fd:FileDescriptor[79]
,E/BtOppRfcommListener( 2664): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2664): BluetoothSocket listen thread finished
,D/BluetoothAdapterState( 2664): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2664): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 2664): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,V/BluetoothOppManager( 2664): cleanUp...
W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,E/bt-btif ( 2664): cmd socket is not created
,D/btif_config_util( 2664): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2664): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2664): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,I/jxcore-log( 5967): ****TEST TOOK:  5122  ms ****
I/jxcore-log( 5967): 
I/jxcore-log( 5967): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5967): 
E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1381): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1381): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1381): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1381): Scan requested (ret=0) - scan timeout 30 seconds
W/bt-l2cap( 2664): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x001b not found for deregistration
D/BluetoothPbap( 1315): Proxy object disconnected
D/PbapServerProfile( 1315): Bluetooth service disconnected
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/DockEventReceiver( 1315): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1315): onReceive
,V/BluetoothStatusReceiver( 1177): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1177): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/WifiNative-wlan0( 1016): do suspend true
,E/Zygote  ( 6051): MountEmulatedStorage()
,I/libpersona( 6051): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6051): v2
I/libpersona( 6051): KNOX_SDCARD not a persona
I/SELinux ( 6051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6051 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6051): TimaSignature is unavailable
,D/ActivityThread( 6051): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6051): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 6051): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6051): SecurePlaceDbHelper() 
D/UserAnalysis( 6051): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6051): onCreate()
,I/ActivityManager( 1016): Killing 5020:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,D/IntelligenceServiceApplication( 6051): no applications having user consent for prediction
,D/AuthorizationBluetoothService( 1684): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/bt-l2cap( 2664): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2664): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2664): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2664): ag scb idx 1 not allocated
W/bt-btif ( 2664): ag scb idx 2 not allocated
E/bt-btif ( 2664): BTA AG is already disabled, ignoring ...
,I/bt_userial_mct( 2664): exiting userial_read_thread
D/bt_userial_mct( 2664): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2664): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2664): hw_epilog_process
D/bt_userial_mct( 2664): userial_close
I/bt_vendor( 2664): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,W/libprocessgroup( 1016): failed to open /acct/uid_10035/pid_5020/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6066): 
D/AndroidRuntime( 6066): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6066): CheckJNI is OFF
,D/AndroidRuntime( 6066): readGMSProperty: start
D/AndroidRuntime( 6066): readGMSProperty: already setted!!
D/AndroidRuntime( 6066): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 6066): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6066): readGMSProperty: end
D/AndroidRuntime( 6066): addProductProperty: start
,I/bt_vendor( 2664): bt-vendor : BT_VND_OP_POWER_CTRL: Off,
I/bt_vendor( 2664): bluetooth satus is on,
I/bt_vendor( 2664): bt-vendor : resetting BT status
I/bt_vendor( 2664): Starting hciattach daemon
I/bt_vendor( 2664): try to set false
I/bt_vendor( 2664): Starting hciattach daemon,
I/bt_vendor( 2664): try to set false
I/bt_vendor( 2664): cleanup
I/GKI_LINUX( 2664): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2664): GKI_exit_task 0 done,
I/GKI_LINUX( 2664): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2664): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2664): isSecureModeOn:false
D/BluetoothAdapterService( 2664): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.gatt.GattService
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.DebugUtils( 2664): handleDebugAction() action=null
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 2664): Received stop request...Stopping profile...
D/BtGatt.GattService( 2664): stop()
D/BtGatt.AdvertiseManager( 2664): advertise clients cleared
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,D/HeadsetService( 2664): Received stop request...Stopping profile...
W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.hid.HidService
,E/AffinityControl( 6066): AffinityControl: registerfunction enter
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/AudioService( 1016): onServiceDisconnected: Bluetooth profile: 1
D/HeadsetProfile( 1315): Bluetooth service disconnected
,W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/A2dpService( 2664): Received stop request...Stopping profile...
D/A2dpStateMachine( 2664): Exit Disconnected: -1
,W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2664): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothA2dp( 1016): Proxy object disconnected
D/AudioService( 1016): onServiceDisconnected: Bluetooth profile: 2
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2664): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothA2dp( 1315): Proxy object disconnected
D/A2dpProfile( 1315): Bluetooth service disconnected
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2664): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2664): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2664): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2664): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2664): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2664): Stopping profile services that were post enabled
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HidService( 2664): Received stop request...Stopping profile...
D/HidService( 2664): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2664): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2664): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 2664): Cleaning up Bluetooth GID callback object
,D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
,E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2664): Profile still running: com.android.bluetooth.hid.HidService
D/AndroidRuntime( 6066): Calling main entry com.android.commands.pm.Pm
,D/BluetoothInputDevice( 1315): Proxy object disconnected
,D/HidProfile( 1315): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 2664): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2664): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2664): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
,D/PanService( 2664): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
,D/BluetoothPan( 1016): BluetoothPAN Proxy object disconnected
,D/BluetoothPan( 1315): BluetoothPAN Proxy object disconnected
D/PanProfile( 1315): Bluetooth service disconnected
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.hid.HidService,
D/BluetoothAdapterService( 2664): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothMapService( 2664): Received stop request...Stopping profile...
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{137345893}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
,D/BluetoothA2dp( 2664): Proxy object disconnected,
D/BluetoothAdapterService( 2664): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2664): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2664): GKI_exit_task 2 done
I/GKI_LINUX( 2664): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BluetoothMap( 1315): Proxy object disconnected
D/MapProfile( 1315): Bluetooth service disconnected
D/SapService( 2664): Received stop request...Stopping profile...
D/SapService( 2664): Stopping Bluetooth SapService
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/BluetoothAdapterService( 2664): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae7bc61
D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:0
,D/PackageManagerService( 1016): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2664): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2664): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2664): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2664): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2664): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/PackageManager( 1016): !@killApplicatoin: 10346, uninstall pkg
W/BluetoothPanServiceJni( 2664): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 2664): Cleaning up Bluetooth PAN callback object
D/Bluetoothsap( 1315): BluetoothSAP Proxy object disconnected
D/SapProfile( 1315): Bluetooth service disconnected
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2664): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2664): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(182959201)( 2664): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2664): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2664): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
I/ActivityManager( 1016): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 5967:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{13798e27 com.test.thalitest/10338} due to missing metadata
,I/WindowState( 1016): WIN DEATH: Window{82b55a0 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focus left window: 5967
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{21fa3fbe u0 com.example.hello/.MainActivity t19}
,W/ActivityManager( 1016): Spurious death for ProcessRecord{1c89c03a 5967:com.example.hello/u0a346}, curProc for 5967: null
,D/BluetoothAdapterState( 2664): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2664): Setting state to 10
I/BluetoothAdapterState( 2664): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2664): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2664): updateAdapterState state is 10
,I/ActivityManager( 1016): Force stopping com.example.hello appid=10346 user=0: pkg removed
,D/BluetoothAdapterService( 2664): Autoconnection is available 
D/BluetoothAdapterService( 2664): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2664): Entering OffState
,D/BluetoothAdapter( 1830): onBluetoothStateChange: up=false
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{21fa3fbe u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1016): Duplicate finish request for ActivityRecord{21fa3fbe u0 com.example.hello/.MainActivity t19 f}
D/BluetoothAdapter( 1830): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 2664): onBluetoothStateChange: up=false
I/wpa_supplicant( 1381): nl80211: Received scan results (16 BSSes)
,D/BluetoothAdapter( 2664): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1315): onBluetoothStateChange: up=false
,D/WifiP2pService( 1016): InactiveState{ what=147461 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=147461 }
D/BluetoothAdapter( 1315): Bluetooth is turned off, stop adv and scan
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1016): Focused application released
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1684): Read error: ssl=0xb91b8158: I/O error during system call, Connection timed out
I/art     ( 4077): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 888us total 38.363ms
,E/ConnectivityService( 1016): updateNetworkInfo()
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,I/art     ( 5290): Explicit concurrent mark sweep GC freed 11498(827KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 737us total 49.072ms
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/SamsungIME( 1884): mOCRHelper is null
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BluetoothAdapter( 1448): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1448): Bluetooth is turned off, stop adv and scan
D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
I/KLMS-2.5.123: ( 3762): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 01 15:33:54 GMT+01:00 2016
D/TelephonyNetworkFactory( 1473): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1473): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SMD     (  289): DCD OFF
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NetworkStats( 1016): updateIfacesLocked()
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/WifiP2pService( 1016): InactiveState{ what=131204 }
D/WifiP2pService( 1016): P2pEnabledState{ what=131204 }
D/WifiP2pService( 1016): sending p2p connection changed broadcast: FAILED
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkStats( 1016): performPollLocked() took 19ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
,D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1016): onP2pDisconnected
D/IpRemoteDisplayController( 1016): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1016): WfdBridgeServer is already null
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/art     ( 1830): Explicit concurrent mark sweep GC freed 16959(951KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.545ms total 77.634ms
D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
D/WifiP2pService( 1016): sending p2p connection changed broadcast: DISCONNECTED
E/ConnectivityService( 1016): updateNetworkInfo()
D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/DataBuffer( 1830): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@fddadd7)
D/WifiP2pService( 1016): P2pDisablingState
D/WifiP2pService( 1016): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1016): p2p socket connection lost
D/WifiP2pService( 1016): P2pDisabledState
E/WifiNative-wlan0( 1016): do suspend true
D/WifiDisplayController( 1016): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1016): disconnect
D/WifiDisplayController( 1016): updateConnection
D/WifiDisplayController( 1016): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiDisplayController( 1016): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1016): onP2pDisconnected
D/IpRemoteDisplayController( 1016): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1016): WfdBridgeServer is already null
D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 47898(2MB) AllocSpace objects, 19(308KB) LOS objects, 33% free, 23MB/35MB, paused 3.771ms total 211.621ms
I/art     ( 1016): WaitForGcToComplete blocked for 179.413ms for cause Explicit
D/WifiP2pService( 1016): P2pDisabledState{ what=143375 }
D/WifiP2pService( 1016): DefaultState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1381): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(0)
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : 0, 0
,D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,D/RegisteredServicesCache( 1459): empty dynamic service
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10346
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10346
D/TaskPersister( 1016): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::,
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/WifiScanningService( 1016): SCAN_AVAILABLE : 1
,D/RttService( 1016): SCAN_AVAILABLE : 1
,D/Tethering( 1016): MasterInitialState.processMessage what=3
D/WifiScanningService( 1016): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1016): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 12570(661KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.059ms total 166.316ms
,I/art     ( 1016): WaitForGcToComplete blocked for 346.192ms for cause Explicit
,V/NativeCrypto( 1684): SSL shutdown failed: ssl=0xb91b8158: I/O error during system call, Broken pipe
,D/BluetoothPbap( 1315): onBluetoothStateChange: up=false
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
E/WifiStateMachine( 1016): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
I/wpa_supplicant( 1381): Blacklist: Clear (all) 
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,W/GeofencerStateMachine( 1830): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3762): KLMSAbstractReciever(): onReceive().END.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothAdapter( 1459): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1459): Bluetooth is turned off, stop adv and scan
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1016): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3762): KLMSIntentService(): onCreate()
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3762): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6086): MountEmulatedStorage()
E/Zygote  ( 6086): v2
I/libpersona( 6086): KNOX_SDCARD checking this for 10090
I/libpersona( 6086): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1381): p2p0: CTRL-EVENT-TERMINATING 
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6086 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Tethering( 1016): interfaceLinkStateChanged p2p0, false
D/Tethering( 1016): interfaceStatusChanged p2p0, false
,I/SELinux ( 6086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/Nat464Xlat( 1016): interfaceLinkStateChanged p2p0, false
I/KLMS-2.5.123: ( 3762): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
E/SELinux ( 6086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothMap( 1315): onBluetoothStateChange: up=false
,D/TimaKeyStoreProvider( 6086): TimaSignature is unavailable
,D/BluetoothA2dp( 1315): onBluetoothStateChange: up=false
,D/ActivityThread( 6086): Added TimaKeyStore provider
,I/wpa_supplicant( 1381): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,I/wpa_supplicant( 1381): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1381): Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
I/wpa_supplicant( 1381): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 1381): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/Tethering( 1016): InitialState.processMessage what=4
E/Tethering( 1016): No numeric data
,I/KLMS-2.5.123: ( 3762): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/BluetoothAdapter( 1473): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1473): Bluetooth is turned off, stop adv and scan
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/BluetoothAdapter( 1177): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1177): Bluetooth is turned off, stop adv and scan
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,I/KLMS-2.5.123: ( 3762): KLMSIntentService(): PACKAGE_REMOVED
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,I/KLMS-2.5.123: ( 3762): KLMSIntentService(): listeningToPackageRemoved().START
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,I/KLMS-2.5.123: ( 3762): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,V/NetworkStats( 1016): performPollLocked() took 3ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/BluetoothA2dp( 1016): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1315): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1315): Unbinding service...
,D/BluetoothInputDevice( 1315): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1016): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1016): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2664): onBluetoothStateChange: up=false
,D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/elm:15121( 6086): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6086): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6086): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BluetoothManagerService( 1016): Broadcasting onBluetoothServiceUp() to 0 receivers.
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/elm:15121( 6086): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6086): ElmAgentService : onCreate()
,D/elm:15121( 6086): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6086): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 6086): MDMBridge.getInstance()
D/elm:15121( 6086): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6086): MDMBridge.getAllLicenseInfoFromSDK()
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 13443(772KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 4.259ms total 190.711ms
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,I/wpa_supplicant( 1381): Blacklist: Clear (all) 
,D/BluetoothAdapter( 1177): 116545384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BluetoothAdapter( 1177): 116545384: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 10
D/BluetoothAdapter( 1177): 116545384: getState() :  mService = null. Returning STATE_OFF
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BluetoothAdapter( 1177): 116545384: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1177): 116545384: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1016): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1016): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
I/KLMS-2.5.123: ( 3762): KLMSIntentService(): listeningToPackageRemoved().END
I/SamsungIME( 1884): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
V/BluetoothEventManager( 1315): Received android.bluetooth.adapter.action.STATE_CHANGED
I/GKI_LINUX( 2664): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2664): GKI_exit_task 1 done
I/GKI_LINUX( 2664): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2664): cleanupNative: return from cleanup
,W/InputMethodManagerService( 1016): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1016): [BT Setting State] State =10
I/InputMethodManagerService( 1016): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/KLMS-2.5.123: ( 3762): KLMSIntentService(): onDestroy()
,I/art     ( 2664): System.exit called, status: 0
I/AndroidRuntime( 2664): VM exiting with result code 0, cleanup skipped.
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5702): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5702): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5702): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5702): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/ApplicationPolicy( 1016): updateDataUsageMap
,D/PackageManager( 1016): delete codoeFile: 
,I/AASA_removePackage( 1016): UID=10346 Target=com.example.hello
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
,D/PackageManager( 1016): result of delete: 1{137345893}
,D/AndroidRuntime( 6066): Shutting down VM
,I/wpa_supplicant( 1381): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 5852): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5852): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10346 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6086): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Process com.android.bluetooth (pid 2664)(adj 0) has died(72,685)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 1016): Killing 4455:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackagesMonitor( 5035): PackagesMonitor onReceive :com.example.hello
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/UsbSettingsManager( 1016): clearDefaults: com.example.hello
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,I/CrashAnrDetector( 1016): onPackageRemoved : com.example.hello
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/Mms/FreeMessageStatusReceiver( 4795): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,E/WifiStateMachine( 1016): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-wlan0( 1016): callSECApiBoolean - ID [21]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(1)
,D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/HotspotTile( 1177): onReceive : 1, 0
,W/Settings( 1830): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Mms/FreeMessageReceiverService( 4795): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4795): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1016): failed to open /acct/uid_10108/pid_4455/cgroup.procs: No such file or directory
,I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
,I/TactileAssist( 1016): List of disabled apps :
,D/Compatibility( 5785): onReceive() it will make start service
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 6051): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,D/Compatibility( 5785): onHandleIntent()
,D/Compatibility( 5785): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10346, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,W/ContextImpl( 5142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/Compatibility( 5785): found: 2
D/Compatibility( 5785): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5785): skipping ResolveInfo{2b9cb447 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5785): considering ResolveInfo{6909474 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5785): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5785): enabling receiver ResolveInfo{1e82bd9d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5785): enabling receiver ResolveInfo{17dec212 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/art     ( 6066): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6124): MountEmulatedStorage()
I/libpersona( 6124): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6124): v2
I/libpersona( 6124): KNOX_SDCARD not a persona
D/Compatibility( 5785): enabling receiver ResolveInfo{34e64de3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SELinux ( 6124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,I/SELinux ( 6124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6124): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
D/Compatibility( 5785): enabling receiver ResolveInfo{125c83e0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5785): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
D/TimaKeyStoreProvider( 6124): TimaSignature is unavailable
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
D/ActivityThread( 6124): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false,
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/BluetoothAdapter( 6051): 57442666: getState() :  mService = null. Returning STATE_OFF
,V/PlaceDetection v1.0.19 ( 6051): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6051): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6051): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/ResourcesManager( 6124): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/RCPManager( 6124):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 1016):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5813): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
W/ContextImpl( 5813): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/FilterInstaller( 5813): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5813): FilterPackageService : ACTION_REMOVED
,D/FilterUnInstaller( 5813): before removeFromFS
,E/Zygote  ( 6141): MountEmulatedStorage()
,E/Zygote  ( 6141): v2
I/libpersona( 6141): KNOX_SDCARD checking this for 1000
I/libpersona( 6141): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6141 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 6141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 6150): MountEmulatedStorage(),
I/libpersona( 6150): KNOX_SDCARD checking this for 10095
E/Zygote  ( 6150): v2,
I/libpersona( 6150): KNOX_SDCARD not a persona
I/SELinux ( 6150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6150 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6141): TimaSignature is unavailable
,D/ActivityThread( 6141): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6150): TimaSignature is unavailable
,D/ActivityThread( 6150): Added TimaKeyStore provider

```
