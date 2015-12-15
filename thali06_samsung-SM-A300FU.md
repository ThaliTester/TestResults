#### Test 5038801913f4183_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  288): DCD OFF
,--------- beginning of system
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1169): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1169): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/AndroidRuntime( 5946): 
D/AndroidRuntime( 5946): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5946): CheckJNI is OFF
D/AndroidRuntime( 5946): readGMSProperty: start
D/AndroidRuntime( 5946): readGMSProperty: already setted!!
D/AndroidRuntime( 5946): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5946): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5946): readGMSProperty: end
D/AndroidRuntime( 5946): addProductProperty: start
V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2652): Disconnected process message: 10
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1169): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1169): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1169): level :100 plugged : 2
E/AffinityControl( 5946): AffinityControl: registerfunction enter
D/AndroidRuntime( 5946): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5958 uid=10346 gids={50346, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/libpersona( 5958): KNOX_SDCARD checking this for 10346
E/Zygote  ( 5958): MountEmulatedStorage()
I/libpersona( 5958): KNOX_SDCARD not a persona
E/Zygote  ( 5958): v2
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1480
D/AndroidRuntime( 5946): Shutting down VM
I/SELinux ( 5958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 5958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, iello
E/SELinux ( 5958): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5958): TimaSignature is unavailable
D/ActivityThread( 5958): Added TimaKeyStore provider
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1017): Display changed displayId=0
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1480): updateVisibility : ActivityRecord{844b199 token=android.os.BinderProxy@18a3fa9f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/WebViewFactory( 5958): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5958): Time to load native libraries: 2 ms (timestamps 6435-6437)
I/LibraryLoader( 5958): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5958): Binding Chromium to main looper Looper (main, tid 1) {2749e08b}
I/LibraryLoader( 5958): Expected native library version number "",actual native library version number ""
I/chromium( 5958): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5958): Initializing chromium process, singleProcess=true
W/art     ( 5958): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5958): ApplicationContext is null in ApplicationStatus
W/art     ( 5946): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/chromium( 5958): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5958): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5958): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5958): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5958): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5958): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5958): Local Branch: 
I/Adreno-EGL( 5958): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5958): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5958):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 5958): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5958): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5958): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5958): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5958): CordovaWebView is running on device made by: samsung
,W/art     ( 5958): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5958): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{3daf4ef5 u0 com.example.hello/.MainActivity t19}
,D/OpenGLRenderer( 5958): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 5958): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 5958): updateVisibility : ActivityRecord{1830c644 token=android.os.BinderProxy@59f3cd6 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/PhoneWindow( 5958): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5958): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit,
,D/InputDispatcher( 1017): Focus entered window: 5958
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5958): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5958): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5958): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5958): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1169): Icon Only
,D/PanelView( 1169): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +673ms (total +742ms)
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{3daf4ef5 u0 com.example.hello/.MainActivity t19} time:87012
,W/ActivityManager( 1017): mDVFSHelper.release()
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 5958): showStatusIcon on inactive InputConnection
,I/Timeline( 5958): Timeline: Activity_idle id: android.os.BinderProxy@59f3cd6 time:87018
,I/SurfaceFlinger(  257): id=12 Removed iello (7/9)
,I/SamsungIME( 1888): getCurrentCandidateView
,W/BindingManager( 5958): Cannot call determinedVisibility() - never saw a connection for the pid: 5958
,I/chromium( 5958): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/SamsungIME( 1888): Dismiss ExpandCandiate
,I/SamsungIME( 1888): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1888): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 5958): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1888): KeybaordView init() : load resources
,E/AndroidProtocolHandler( 5958): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/SamsungIME( 1888): getCurrentKeyboard
,I/SamsungIME( 1888): getTextKeyboard
,D/SamsungIME( 1888): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 5958): JniHelper::setJavaVM(0xb880f448), pthread_self() = -1193904696
,D/JX-Cordova( 5958): jxcore cordova android initializing
,W/jxcore-log( 5958): Initializing JXcore engine
W/jxcore-log( 5958): JXcore engine is ready
,W/jxcore-log( 5958): Starting JXcore engine
,E/audit   ( 1880): type=1400 msg=audit(1450199020.330:205): avc:  denied  { ioctl } for  pid=5958 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1880):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1880): type=1300 msg=audit(1450199020.330:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bedacd58 items=0 ppid=307 ppcomm=main pid=5958 auid=4294967295 uid=10346 gid=10346 euid=10346 suid=10346 fsuid=10346 egid=10346 sgid=10346 fsgid=10346 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1880): type=1320 msg=audit(1450199020.330:205): 
,W/jxcore-log( 5958): Platform android
W/jxcore-log( 5958): 
W/jxcore-log( 5958): Process ARCH arm
W/jxcore-log( 5958): 
,I/jxcore-log( 5958): JXcore Cordova bridge is ready!
I/jxcore-log( 5958): 
,W/jxcore-log( 5958): JXcore engine is started
,E/jxcore-log( 5958): >> samsung-SM-A300FU
E/jxcore-log( 5958): 
,I/jxcore-log( 5958): Total memory 1451114496
I/jxcore-log( 5958): 
,I/jxcore-log( 5958): Free memory 24862720
I/jxcore-log( 5958): 
I/jxcore-log( 5958): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5958): 
I/jxcore-log( 5958): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5958): 
,I/jxcore-log( 5958): userPath [ 'www' ],
I/jxcore-log( 5958): 
,I/jxcore-log( 5958): Size 540 960
I/jxcore-log( 5958): 
,I/jxcore-log( 5958): Screen Brightness 160
I/jxcore-log( 5958): 
,E/jxcore-log( 5958): Dummy Error Log.
E/jxcore-log( 5958): 
,E/SMD     (  288): DCD OFF
,I/jxcore-log( 5958): getBuffer is called!!!!
I/jxcore-log( 5958): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1017): waitForAlarm result :4
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6008): MountEmulatedStorage(),
E/Zygote  ( 6008): v2
I/libpersona( 6008): KNOX_SDCARD checking this for 10071
I/libpersona( 6008): KNOX_SDCARD not a persona
,I/SELinux ( 6008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6008): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6008 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6008): TimaSignature is unavailable
,D/ActivityThread( 6008): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 6008): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 6008): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 17707(984KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.242ms total 57.856ms,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 6008): Starting books sync for 61035162, extras: ade
,E/SQLiteLog( 6008): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 6008): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1169): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
,D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
I/StatusBar( 1169): Icon Only
D/PanelView( 1169): There is/are notification(s) ,
,D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1169): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1169): Icon Only
I/StatusBar( 1169): Icon Only,
D/PanelView( 1169): There is/are notification(s) 
D/PanelView( 1169): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6008): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6008): Soft error
E/BooksSync( 6008): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6008): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6008): Sync error
E/BooksSync( 6008): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6008): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6008): Finished books sync
,D/PanelView( 1169): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 64101, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1017): Killing 5139:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  288): DCD OFF
,W/libprocessgroup( 1017): failed to open /acct/uid_10146/pid_5139/cgroup.procs: No such file or directory
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 5958): disable()
,D/SettingsProvider( 1017): name = bluetooth_on
,D/BluetoothAdapterState( 2652): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2652): Setting state to 13
,I/BluetoothAdapterState( 2652): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2652): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2652): updateAdapterState state is 13
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2652): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 2652): Autoconnection is available 
D/BluetoothAdapterService( 2652): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2652): terminating service from this receiver
,D/BluetoothSocket( 2652): close() in, this: android.bluetooth.BluetoothSocket@1f98904b, channel: 19, state: LISTENING
,D/BluetoothSocket( 2652): close() this: android.bluetooth.BluetoothSocket@1f98904b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@182fec0d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14ee7a28mSocket: android.net.LocalSocket@35b26341 impl:android.net.LocalSocketImpl@3c7840e6 fd:FileDescriptor[74]
,D/BluetoothSocket( 2652): Closing mSocket: android.net.LocalSocket@35b26341 impl:android.net.LocalSocketImpl@3c7840e6 fd:FileDescriptor[74]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2652): onBluetoothDisable()
D/BluetoothAdapterProperties( 2652): mDiscovering is false
,D/SecContentProvider( 1017): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2652): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothPbap( 1311): Proxy object disconnected
,D/PbapServerProfile( 1311): Bluetooth service disconnected
,D/BluetoothAdapterProperties( 2652): Scan Mode:20
,D/BluetoothAdapterState( 2652): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2652): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 2652): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/BtOppRfcommListener( 2652): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 2652): cmd socket is not created
,D/btif_config_util( 2652): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
E/bt-btm  ( 2652): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 2652): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=5958, uid=10346
,D/SettingsProvider( 1017): name = wifi_on
W/bt-l2cap( 2652): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x001b not found for deregistration
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1017): [BT Setting State] State =13
,D/BluetoothTile( 1169):  onBluetoothStateChange:
,E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
,D/BluetoothTile( 1169):  onBluetoothPairedDevicesChanged:
,I/wpa_supplicant( 1395): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1395): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1395): P2P: Current p2p state = IDLE
D/BluetoothTile( 1169):  handleUpdatestate:false name:null
I/wpa_supplicant( 1395): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 5958): ****TEST TOOK:  5116  ms ****
I/jxcore-log( 5958): 
,I/jxcore-log( 5958): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5958): 
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothTile( 1169):  handleUpdatestate:false name:null
D/BluetoothTile( 1169): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1169):  getBluetoothState : 13
D/STATUSBAR-QSTileView( 1169): onStateChanged: Bluetooth
D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
D/BluetoothSocket( 2652): close() in, this: android.bluetooth.BluetoothSocket@15c510d4, channel: 5, state: LISTENING
D/PhoneStatusBar( 1169): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/BluetoothSocket( 2652): close() this: android.bluetooth.BluetoothSocket@15c510d4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34989910, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2800f27dmSocket: android.net.LocalSocket@1bf78572 impl:android.net.LocalSocketImpl@3b38bdc3 fd:FileDescriptor[76]
D/BluetoothSocket( 2652): Closing mSocket: android.net.LocalSocket@1bf78572 impl:android.net.LocalSocketImpl@3b38bdc3 fd:FileDescriptor[76]
I/SamsungIME( 1888): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
E/WifiNative-wlan0( 1017): do suspend true
I/BtOppRfcommListener( 2652): stopping Accept Thread
D/BluetoothSocket( 2652): close() in, this: android.bluetooth.BluetoothSocket@8cc6640, channel: 12, state: LISTENING
D/BluetoothSocket( 2652): close() this: android.bluetooth.BluetoothSocket@8cc6640, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@506d1a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1baf3979mSocket: android.net.LocalSocket@19b486be impl:android.net.LocalSocketImpl@27df731f fd:FileDescriptor[79]
D/BluetoothSocket( 2652): Closing mSocket: android.net.LocalSocket@19b486be impl:android.net.LocalSocketImpl@27df731f fd:FileDescriptor[79]
I/BtOppRfcommListener( 2652): BluetoothSocket listen thread finished
V/BluetoothEventManager( 1311): Received android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothOppManager( 2652): cleanUp...
,W/ContextImpl( 1311): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/DockEventReceiver( 1311): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1311): onReceive
,V/BluetoothStatusReceiver( 1169): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1169): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6043): MountEmulatedStorage()
E/Zygote  ( 6043): v2
I/libpersona( 6043): KNOX_SDCARD checking this for 10055
I/libpersona( 6043): KNOX_SDCARD not a persona
,I/SELinux ( 6043): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6043 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6043): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6043): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6043): TimaSignature is unavailable,
D/ActivityThread( 6043): Added TimaKeyStore provider,
,D/UserAnalysis.PlaceProvider( 6043): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 6043): Key for secure DB is newly created,
D/UserAnalysis.SecurePlaceDbHelper( 6043): SecurePlaceDbHelper() 
D/UserAnalysis( 6043): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6043): onCreate()
,I/ActivityManager( 1017): Killing 5001:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,D/AuthorizationBluetoothService( 1667): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/IntelligenceServiceApplication( 6043): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 6043): [PlaceDetection::stopService] Service stopped.
,W/bt-l2cap( 2652): L2CAP - PSM: 0x0019 not found for deregistration,
W/bt-l2cap( 2652): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_mct( 2652): exiting userial_read_thread
W/bt-l2cap( 2652): L2CAP - PSM: 0x001b not found for deregistration
D/bt_userial_mct( 2652): Leaving userial_evt_read_thread()
W/bt-l2cap( 2652): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2652): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2652): ag scb idx 1 not allocated
W/bt-btif ( 2652): ag scb idx 2 not allocated
E/bt-btif ( 2652): BTA AG is already disabled, ignoring ...
,D/bt_userial_mct( 2652): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2652): hw_epilog_process
,D/bt_userial_mct( 2652): userial_close
I/bt_vendor( 2652): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,V/PlaceDetection v1.0.19 ( 6043): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/WifiP2pService( 1017): InactiveState{ what=143375 },
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1169): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  278): Clearing all IP addresses on wlan0
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1667): Read error: ssl=0xb8d6d348: I/O error during system call, Connection timed out
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling,
V/NativeCrypto( 1667): SSL shutdown failed: ssl=0xb8d6d348: I/O error during system call, Broken pipe,
,D/AndroidRuntime( 6054): 
D/AndroidRuntime( 6054): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6054): CheckJNI is OFF
D/AndroidRuntime( 6054): readGMSProperty: start
D/AndroidRuntime( 6054): readGMSProperty: already setted!!
,D/AndroidRuntime( 6054): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 6054): readGMSProperty: could not set the property(default)!!
D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/AndroidRuntime( 6054): readGMSProperty: end
D/AndroidRuntime( 6054): addProductProperty: start
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 337 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost,
D/WifiP2pService( 1017): InactiveState{ what=131204 }
D/WifiScanningService( 1017): SCAN_AVAILABLE : 1
D/WifiP2pService( 1017): P2pEnabledState{ what=131204 }
,D/WifiP2pService( 1017): sending p2p connection changed broadcast: FAILED
D/WifiScanningService( 1017): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,I/qtaguid ( 1017): Untagging socket 337,
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/RttService( 1017): SCAN_AVAILABLE : 1
D/RttService( 1017): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1017): onP2pDisconnected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
I/Hs20UtilService( 1726): Starting #8
I/Hs20UtilService( 1726): Message received 5007
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: IDLE
D/WifiP2pService( 1017): sending p2p connection changed broadcast: DISCONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
D/WifiP2pService( 1017): P2pDisablingState
D/WifiP2pService( 1017): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1017): p2p socket connection lost
E/WifiNative-wlan0( 1017): do suspend true
D/WifiP2pService( 1017): P2pDisabledState
V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
D/WifiP2pService( 1017): P2pDisabledState{ what=143375 }
E/WifiStateMachine( 1017): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 1017): DefaultState{ what=143375 }
D/WifiDisplayController( 1017): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1017): disconnect
D/WifiDisplayController( 1017): updateConnection
D/WifiDisplayController( 1017): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1455): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1455): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1169): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/bt_vendor( 2652): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2652): bluetooth satus is on
,I/bt_vendor( 2652): bt-vendor : resetting BT status
I/bt_vendor( 2652): Starting hciattach daemon
I/bt_vendor( 2652): try to set false
,I/bt_vendor( 2652): Starting hciattach daemon
I/bt_vendor( 2652): try to set false
I/bt_vendor( 2652): cleanup
I/GKI_LINUX( 2652): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2652): GKI_exit_task 0 done
I/GKI_LINUX( 2652): GKI_shutdown(): task [BTU] terminated
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6075 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6075): MountEmulatedStorage()
E/Zygote  ( 6075): v2
I/libpersona( 6075): KNOX_SDCARD checking this for 10064,
I/libpersona( 6075): KNOX_SDCARD not a persona
I/SELinux ( 6075): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/WifiDisplayController( 1017): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/WifiDisplayAdapter( 1017): onP2pDisconnected
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
,D/IpRemoteDisplayController( 1017): disconnectWfdBridgeServer
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
D/IpRemoteDisplayController( 1017): WfdBridgeServer is already null
E/ConnectivityService( 1017): updateNetworkInfo(),
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/SELinux ( 6075): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6075): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/BluetoothAdapterState( 2652): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2652): isSecureModeOn:false,
D/BluetoothAdapterService( 2652): mProfilesStarted : true supportedProfileServices.length : 12,
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/wpa_supplicant( 1395): p2p0: State: DISCONNECTED -> DISCONNECTED
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.gatt.GattService
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AllShareCastTile( 1169): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1169): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/Tethering( 1017): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1169): EthernetConnected: false
,D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1169): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1169): updateDataNetType()
D/StatusBar.NetworkController( 1169): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1169): updateLTEICONDataNetType:0
V/NetworkStats( 1017): performPollLocked() took 4ms
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1169): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1169): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2652): handleDebugAction() action=null
D/BtGatt.GattService( 2652): Received stop request...Stopping profile...
D/BtGatt.GattService( 2652): stop()
D/BtGatt.AdvertiseManager( 2652): advertise clients cleared
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.hfp.HeadsetService
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.a2dp.A2dpService
D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-QSTileView( 1169): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1169): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1169): Wifi onReceive(0)
D/HotspotTile( 1169): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1169): onReceive : 0, 0
D/WifiCredService( 1311): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/TimaKeyStoreProvider( 6075): TimaSignature is unavailable
D/ActivityThread( 6075): Added TimaKeyStore provider
D/HeadsetService( 2652): Received stop request...Stopping profile...
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.hdp.HealthService
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 1
D/HeadsetProfile( 1311): Bluetooth service disconnected
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.pan.PanService
E/AffinityControl( 6054): AffinityControl: registerfunction enter
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.pan.PanService
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2652): Not skipping com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ResourcesManager( 6075): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2652): Not skipping com.broadcom.bt.service.sap.SapService
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2652): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2652): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2652): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2652): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2652): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2652): Stopping profile services that were post enabled
E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
D/A2dpService( 2652): Received stop request...Stopping profile...
D/A2dpStateMachine( 2652): Exit Disconnected: -1
,D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
D/AndroidRuntime( 6054): Calling main entry com.android.commands.pm.Pm
E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2652): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 1017): Proxy object disconnected
D/AudioService( 1017): onServiceDisconnected: Bluetooth profile: 2
D/BluetoothA2dp( 1311): Proxy object disconnected
D/A2dpProfile( 1311): Bluetooth service disconnected
D/FileShare-Client( 6075): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/HidService( 2652): Received stop request...Stopping profile...
D/HidService( 2652): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2652): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2652): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2652): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
D/FileShare-Client( 6075): ClientBroadcastReceiver.onReceive - disconnected
D/BluetoothInputDevice( 1311): Proxy object disconnected
D/HidProfile( 1311): Bluetooth service disconnected
W/BluetoothHeadsetServiceJni( 2652): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2652): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2652): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
D/PanService( 2652): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
D/BluetoothPan( 1017): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 1311): BluetoothPAN Proxy object disconnected
D/PanProfile( 1311): Bluetooth service disconnected
D/BluetoothMapService( 2652): Received stop request...Stopping profile...
D/PackageManager( 1017): START PACKAGE DELETE: observer{983915718}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1017): !@killApplicatoin: 10346, uninstall pkg
I/wpa_supplicant( 1395): Blacklist: Clear (all) 
I/ActivityManager( 1017): Force stopping com.example.hello appid=10346 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 5958:com.example.hello/u0a346 (adj 0): stop com.example.hello cause uninstall pkg
,D/FileShare-Client( 6075): Outbound.stopDelayTimer - 
,I/wpa_supplicant( 1395): p2p0: CTRL-EVENT-TERMINATING 
I/Nat464Xlat( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceLinkStateChanged p2p0, false
D/Tethering( 1017): interfaceStatusChanged p2p0, false
,I/WindowState( 1017): WIN DEATH: Window{2de6f9bf u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1017): Focus left window: 5958
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,W/PackageSettings( 1017): Skipping PackageSetting{7fcfde3 com.test.thalitest/10338} due to missing metadata
,I/wpa_supplicant( 1395): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1395): wlan0: State: COMPLETED -> DISCONNECTED,
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1395): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1395): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false,
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/Tethering( 1017): No numeric data
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3daf4ef5 u0 com.example.hello/.MainActivity t19}
W/ActivityManager( 1017): Spurious death for ProcessRecord{21d10487 5958:com.example.hello/u0a346}, curProc for 5958: null
W/libprocessgroup( 1017): failed to open /acct/uid_10035/pid_5001/cgroup.procs: No such file or directory
I/ActivityManager( 1017): Force stopping com.example.hello appid=10346 user=0: pkg removed
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3daf4ef5 u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{3daf4ef5 u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3889): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 694us total 27.634ms
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
,I/art     ( 5278): Explicit concurrent mark sweep GC freed 9938(665KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 731us total 43.506ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1888): mOCRHelper is null
,D/HotspotTile( 1169): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1169): updateTetherState():false, false
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 6ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
E/Zygote  ( 6092): MountEmulatedStorage()
I/libpersona( 6092): KNOX_SDCARD checking this for 10065
E/Zygote  ( 6092): v2
I/libpersona( 6092): KNOX_SDCARD not a persona
I/SELinux ( 6092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6092 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 4475:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/SapService( 2652): Received stop request...Stopping profile...
,D/SapService( 2652): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2652): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1032cd81
,D/InputDispatcher( 1017): Focused application released
,D/BluetoothMap( 1311): Proxy object disconnected
,D/MapProfile( 1311): Bluetooth service disconnected
,E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2652): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2652): Proxy object disconnected
D/BluetoothAdapterService( 2652): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2652): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2652): GKI_exit_task 2 done
I/GKI_LINUX( 2652): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2652): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2652): Profile still running: com.android.bluetooth.map.BluetoothMapService,
W/BluetoothHealthServiceJni( 2652): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2652): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2652): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2652): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2652): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/BtSettings.ProfileConfig( 2652): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2652): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(271764865)( 2652): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2652): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2652): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/Bluetoothsap( 1311): BluetoothSAP Proxy object disconnected
D/SapProfile( 1311): Bluetooth service disconnected
,I/wpa_supplicant( 1395): Blacklist: Clear (all) 
,I/art     ( 1804): Explicit concurrent mark sweep GC freed 16109(905KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 8MB/13MB, paused 1.067ms total 77.363ms
,W/GeofencerStateMachine( 1804): Ignoring removeGeofence because network location is disabled.
,D/BluetoothAdapterState( 2652): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2652): Setting state to 10
I/BluetoothAdapterState( 2652): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2652): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2652): updateAdapterState state is 10
,D/BluetoothAdapterService( 2652): Autoconnection is available 
D/BluetoothAdapterService( 2652): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2652): Entering OffState
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/DataBuffer( 1804): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fe9ed21)
,D/BluetoothA2dp( 1017): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1439): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1439): Bluetooth is turned off, stop adv and scan
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothA2dp( 1311): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1311): onBluetoothStateChange: up=false
D/Bluetoothsap( 1311): Unbinding service...
,D/BluetoothAdapter( 1311): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1311): Bluetooth is turned off, stop adv and scan
,D/BluetoothPbap( 1311): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1430): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1430): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1804): onBluetoothStateChange: up=false
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1804): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1017): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1017): Bluetooth is turned off, stop adv and scan
,D/TimaKeyStoreProvider( 6092): TimaSignature is unavailable
D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityThread( 6092): Added TimaKeyStore provider
I/wpa_supplicant( 1395): wlan0: CTRL-EVENT-TERMINATING 
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false,
I/PowerManagerService( 1017): [PWL] Off : 15s ago
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/PowerManagerService( 1017): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1017): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1999, ws=null) (elapsedTime=55637)
I/PowerManagerService( 1017): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=460),
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
E/WifiStateMachine( 1017): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [21]
,D/BluetoothInputDevice( 1311): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/StatusBar.NetworkController( 1169): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1169): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1169): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/STATUSBAR-WifiQuickSettingButton( 1169): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1169): Wifi onReceive(1)
D/STATUSBAR-QSTileView( 1169): onStateChanged: Wi-Fi
,D/HotspotTile( 1169): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1169): onReceive : 1, 0
,D/WifiCredService( 1311): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/BluetoothAdapter( 1455): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1455): Bluetooth is turned off, stop adv and scan
,D/BluetoothMap( 1311): onBluetoothStateChange: up=false
,W/Settings( 1804): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 52095(3MB) AllocSpace objects, 12(244KB) LOS objects, 33% free, 23MB/35MB, paused 7.699ms total 249.834ms
,I/art     ( 1017): WaitForGcToComplete blocked for 227.126ms for cause Explicit
,V/AlarmManager( 1017): waitForAlarm result :4
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/BluetoothAdapter( 1169): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1169): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2652): onBluetoothStateChange: up=false
,D/FileShare-Server( 6092): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/RegisteredServicesCache( 1439): empty dynamic service
,D/BluetoothAdapter( 2652): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2652): Bluetooth is turned off, stop adv and scan
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1017): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1169): 976496904: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1169):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1169): 976496904: getState() :  mService = null. Returning STATE_OFF
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothTile( 1169): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1169):  getBluetoothState : 10
,D/BluetoothAdapter( 1169): 976496904: getState() :  mService = null. Returning STATE_OFF
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/BluetoothAdapter( 1169): 976496904: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1169): 976496904: getState() :  mService = null. Returning STATE_OFF
,D/StatusBarManagerService( 1017): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1017): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1169): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,V/BluetoothEventManager( 1311): Received android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 1888): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6124): MountEmulatedStorage(),
I/libpersona( 6124): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6124): v2
I/libpersona( 6124): KNOX_SDCARD not a persona
I/SELinux ( 6124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6124): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6124 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5230:com.google.android.gm/u0a99 (adj 15): empty #31
,I/GKI_LINUX( 2652): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2652): GKI_exit_task 1 done
,I/GKI_LINUX( 2652): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2652): cleanupNative: return from cleanup
,D/TimaKeyStoreProvider( 6124): TimaSignature is unavailable
,D/ActivityThread( 6124): Added TimaKeyStore provider
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 2652): System.exit called, status: 0
,I/AndroidRuntime( 2652): VM exiting with result code 0, cleanup skipped.
,W/ResourcesManager( 6124): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10346
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/TaskPersister( 1017): removeObsoleteFile: deleting file=19_task.xml
,V/EnterpriseBillingPolicy( 1017): uID is 10346
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,I/ActivityManager( 1017): Process com.android.bluetooth (pid 2652)(adj 0) has died(57,708)
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 12973(737KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 6.185ms total 199.160ms
,W/InputMethodManagerService( 1017): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1017): [BT Setting State] State =10
,I/InputMethodManagerService( 1017): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/ApplicationPolicy( 1017): updateDataUsageMap
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10346, packageName = com.example.hello
,I/AASA_removePackage( 1017): UID=10346 Target=com.example.hello
,D/PackageManager( 1017): result of delete: 1{983915718}
,D/AndroidRuntime( 6054): Shutting down VM,
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1017): failed to open /acct/uid_10108/pid_4475/cgroup.procs: No such file or directory
D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_5230/cgroup.procs: No such file or directory
,D/Tethering( 1017): interfaceRemoved wlan0
,E/Tethering( 1017): attempting to remove unknown iface (wlan0), ignoring
,I/Babel_SMS( 6124): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6124): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6124): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
E/SMD     (  288): DCD OFF
I/Babel_SMS( 6124): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6124): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6124): MmsConfig.loadFromResources
,E/Babel_SMS( 6124): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6124): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,D/Tethering( 1017): interfaceRemoved p2p0
,E/Tethering( 1017): attempting to remove unknown iface (p2p0), ignoring
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6124): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6124): startup - clean
,I/Babel   ( 6124): deleted: false for 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/art     ( 6054): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,D/FileShare-Client( 6075): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 6075): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 6075): Outbound.stopDelayTimer - 
,D/FileShare-Server( 6092): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,W/VideoCapabilities( 6124): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1726): Starting #9
,I/Hs20UtilService( 1726): Message received 5007
,W/AudioCapabilities( 6124): Unsupported mime audio/evrc
,W/AudioCapabilities( 6124): Unsupported mime audio/qcelp
,D/NearbySettings( 1311): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1311): DMSUtil.isNetworkConnected - flag-null, state-null,
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,W/AudioCapabilities( 6124): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6124): Unsupported mime audio/mpeg-L2
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1311): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1311): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1311): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6124): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6124): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6124): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/AudioCapabilities( 6124): Unsupported mime audio/evrc
,I/Hs20UtilService( 1726): Starting #10
,I/Hs20UtilService( 1726): Message received 5011
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6151): MountEmulatedStorage()
E/Zygote  ( 6151): v2
I/libpersona( 6151): KNOX_SDCARD checking this for 1000
I/libpersona( 6151): KNOX_SDCARD not a persona
I/SELinux ( 6151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 6124): Unsupported mime video/wvc1
,W/VideoCapabilities( 6124): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6124): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6124): Unsupported mime video/wvc1
W/VideoCapabilities( 6124): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6124): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6124): Unsupported mime video/x-ms-wmv8
,D/TimaKeyStoreProvider( 6151): TimaSignature is unavailable
W/VideoCapabilities( 6124): Unsupported mime video/mp43
D/ActivityThread( 6151): Added TimaKeyStore provider
,W/VideoCapabilities( 6124): Unsupported mime video/sorenson
,W/VideoCapabilities( 6124): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6124): Unsupported profile 4 for video/mp4v-es
,D/SecurityLogAgent( 6151): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6151): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6151): StateMachine : Current State = 1
,D/SecurityLogAgent( 6151): StateMachine : Changed Current State = 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ActivityManager( 1017): Killing 4236:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system

```
