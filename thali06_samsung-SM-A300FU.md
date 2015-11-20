#### Test 50388019aa1a16d_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
--------- beginning of main
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
D/AndroidRuntime( 5898): 
D/AndroidRuntime( 5898): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5898): CheckJNI is OFF
D/AndroidRuntime( 5898): readGMSProperty: start
D/AndroidRuntime( 5898): readGMSProperty: already setted!!
D/AndroidRuntime( 5898): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5898): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5898): readGMSProperty: end
D/AndroidRuntime( 5898): addProductProperty: start
E/AffinityControl( 5898): AffinityControl: registerfunction enter
D/AndroidRuntime( 5898): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
E/Zygote  ( 5910): MountEmulatedStorage()
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5910 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1015): Focused application set to: xxxx
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
D/InputDispatcher( 1015): Focus left window: 1480
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, iello
D/AndroidRuntime( 5898): Shutting down VM
E/Zygote  ( 5910): v2
I/libpersona( 5910): KNOX_SDCARD checking this for 10345
I/libpersona( 5910): KNOX_SDCARD not a persona
I/SELinux ( 5910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5910): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  307): Explicit concurrent mark sweep GC freed 8684(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 21.988ms
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5910): TimaSignature is unavailable
D/ActivityThread( 5910): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.591ms
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1015): Display changed displayId=0
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 18.574ms
D/PersonaManager( 1015): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1480): updateVisibility : ActivityRecord{21f9ea09 token=android.os.BinderProxy@10af2c33 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/WebViewFactory( 5910): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5910): Time to load native libraries: 1 ms (timestamps 6545-6546)
I/LibraryLoader( 5910): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5910): Binding Chromium to main looper Looper (main, tid 1) {1e143175}
I/LibraryLoader( 5910): Expected native library version number "",actual native library version number ""
I/chromium( 5910): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5898): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 5910): Initializing chromium process, singleProcess=true
W/art     ( 5910): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5910): ApplicationContext is null in ApplicationStatus
W/chromium( 5910): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5910): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5910): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5910): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5910): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5910): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5910): Local Branch: 
I/Adreno-EGL( 5910): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5910): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5910):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 5910): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5910): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5910): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5910): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5910): CordovaWebView is running on device made by: samsung
W/art     ( 5910): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5910): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{21f7936e u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5910): Render dirty regions requested: true
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
W/chromium( 5910): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5910): updateVisibility : ActivityRecord{16905286 token=android.os.BinderProxy@25178ac8 {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5910): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5910): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1015): Focus entered window: 5910
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5910): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5910): Initialized EGL, version 1.4
D/OpenGLRenderer( 5910): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5910): Enabling debug mode 0
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
I/SamsungIME( 1863): getCurrentCandidateView
W/IInputConnectionWrapper( 5910): showStatusIcon on inactive InputConnection
I/Timeline( 5910): Timeline: Activity_idle id: android.os.BinderProxy@25178ac8 time:87122
D/SamsungIME( 1863): Dismiss ExpandCandiate
I/ActivityManager( 1015): Displayed Component not be shown by security: +746ms (total +839ms)
W/ActivityManager( 1015): mDVFSHelper.release()
I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{21f7936e u0 com.example.hello/.MainActivity t19} time:87201
I/SurfaceFlinger(  259): id=12 Removed iello (7/9)
I/SurfaceFlinger(  259): id=12 Removed iello (-2/9)
I/SamsungIME( 1863): getDebugLevel  : 0x4f4c
I/SamsungIME( 1863): getDebugLevel  : 0x4f4c
I/SamsungIME( 1863): KeybaordView init() : load resources
I/SamsungIME( 1863): getCurrentKeyboard
I/SamsungIME( 1863): getTextKeyboard
D/SamsungIME( 1863): [SwiftkeyWrapper] currentLangauge : 1701729619
W/BindingManager( 5910): Cannot call determinedVisibility() - never saw a connection for the pid: 5910
I/chromium( 5910): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/SSRM:n  ( 1015): SIOP:: AP = 300
,D/JsMessageQueue( 5910): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5910): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 5910): JniHelper::setJavaVM(0xb7a55448), pthread_self() = -1208292496
D/JX-Cordova( 5910): jxcore cordova android initializing
W/jxcore-log( 5910): Initializing JXcore engine
W/jxcore-log( 5910): JXcore engine is ready
W/jxcore-log( 5910): Starting JXcore engine
E/audit   ( 1856): type=1400 msg=audit(1448020223.912:205): avc:  denied  { ioctl } for  pid=5910 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1856):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1856): type=1300 msg=audit(1448020223.912:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=befbdd58 items=0 ppid=307 ppcomm=main pid=5910 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1856): type=1320 msg=audit(1448020223.912:205): 
W/jxcore-log( 5910): Platform android
W/jxcore-log( 5910): 
W/jxcore-log( 5910): Process ARCH arm
W/jxcore-log( 5910): 
I/jxcore-log( 5910): JXcore Cordova bridge is ready!
I/jxcore-log( 5910): 
W/jxcore-log( 5910): JXcore engine is started
E/jxcore-log( 5910): >> samsung-SM-A300FU
E/jxcore-log( 5910): 
I/jxcore-log( 5910): Total memory 1451114496
I/jxcore-log( 5910): 
I/jxcore-log( 5910): Free memory 22007808
I/jxcore-log( 5910): 
I/jxcore-log( 5910): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5910): 
I/jxcore-log( 5910): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5910): 
I/jxcore-log( 5910): userPath [ 'www' ]
I/jxcore-log( 5910): 
I/jxcore-log( 5910): Size 540 960
I/jxcore-log( 5910): 
I/jxcore-log( 5910): Screen Brightness 160
I/jxcore-log( 5910): 
E/jxcore-log( 5910): Dummy Error Log.
E/jxcore-log( 5910): 
E/SMD     (  290): DCD OFF
I/jxcore-log( 5910): getBuffer is called!!!!
I/jxcore-log( 5910): 
,V/AlarmManager( 1015): waitForAlarm result :4
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5959): MountEmulatedStorage()
,E/Zygote  ( 5959): v2
I/libpersona( 5959): KNOX_SDCARD checking this for 10071
,I/libpersona( 5959): KNOX_SDCARD not a persona
,I/SELinux ( 5959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5959): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5959 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5959): TimaSignature is unavailable
,D/ActivityThread( 5959): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 5959): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 5959): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 5959): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5959): (284) automatic index on view_volumes(volume_id)
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 37859(2MB) AllocSpace objects, 19(308KB) LOS objects, 33% free, 23MB/35MB, paused 2.067ms total 155.232ms,
,I/BooksConfig( 5959): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1712): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1712): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1712): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1712): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1712): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1015): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1015): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice,
D/PersonaManager( 1176): isKioskContainerExistOnDevice,
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) ,
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1712): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1712): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1712): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1712): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1712): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5959): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5959): Soft error
E/BooksSync( 5959): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5959): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5959): Sync error
E/BooksSync( 5959): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5959): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5959): Finished books sync
,D/SyncManager( 1015): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 63200, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1015): Killing 4933:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1015): mCursor = null
,W/libprocessgroup( 1015): failed to open /acct/uid_10035/pid_4933/cgroup.procs: No such file or directory
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2093, ws=null) (elapsedTime=56644)
,D/BluetoothAdapter( 5910): disable()
,D/SettingsProvider( 1015): name = bluetooth_on
,D/BluetoothAdapterState( 2634): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2634): Setting state to 13
,I/BluetoothAdapterState( 2634): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2634): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2634): updateAdapterState state is 13
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2634): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothSocket( 2634): close() in, this: android.bluetooth.BluetoothSocket@2d92db35, channel: 19, state: LISTENING
,D/BluetoothSocket( 2634): close() this: android.bluetooth.BluetoothSocket@2d92db35, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2818f97d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@264fabcamSocket: android.net.LocalSocket@3e7fe13b impl:android.net.LocalSocketImpl@1b51058 fd:FileDescriptor[74]
,D/BluetoothSocket( 2634): Closing mSocket: android.net.LocalSocket@3e7fe13b impl:android.net.LocalSocketImpl@1b51058 fd:FileDescriptor[74]
D/BluetoothAdapterService( 2634): Autoconnection is available 
,D/BluetoothAdapterService( 2634): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2634): terminating service from this receiver
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2634): onBluetoothDisable()
D/BluetoothAdapterProperties( 2634): mDiscovering is false
,D/SecContentProvider( 1015): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2634): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothPbap( 1313): Proxy object disconnected
D/PbapServerProfile( 1313): Bluetooth service disconnected
,D/BluetoothAdapterProperties( 2634): Scan Mode:20
D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: false pid=5910, uid=10345
,D/SettingsProvider( 1015): name = wifi_on
W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1015): [BT Setting State] State =13
,D/BluetoothTile( 1176):  onBluetoothStateChange:
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothTile( 1176): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1176):  getBluetoothState : 13
,D/STATUSBAR-QSTileView( 1176): onStateChanged: Bluetooth
,E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
,I/jxcore-log( 5910): ****TEST TOOK:  5104  ms ****
I/jxcore-log( 5910): 
,I/wpa_supplicant( 1386): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1386): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1386): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1386): Scan requested (ret=0) - scan timeout 30 seconds
,I/SamsungIME( 1863): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
I/jxcore-log( 5910): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5910): 
,D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1176): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
V/BluetoothEventManager( 1313): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterState( 2634): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2634): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 2634): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/BtOppRfcommListener( 2634): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 2634): cmd socket is not created
E/bt-btm  ( 2634): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2634): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/btif_config_util( 2634): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 2634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x001b not found for deregistration
E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothSocket( 2634): close() in, this: android.bluetooth.BluetoothSocket@3aa4ba96, channel: 5, state: LISTENING
D/BluetoothSocket( 2634): close() this: android.bluetooth.BluetoothSocket@3aa4ba96, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22548072, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f015617mSocket: android.net.LocalSocket@3896da04 impl:android.net.LocalSocketImpl@31c03bed fd:FileDescriptor[76]
D/BluetoothSocket( 2634): Closing mSocket: android.net.LocalSocket@3896da04 impl:android.net.LocalSocketImpl@31c03bed fd:FileDescriptor[76]
I/BtOppRfcommListener( 2634): stopping Accept Thread
D/BluetoothSocket( 2634): close() in, this: android.bluetooth.BluetoothSocket@769ea22, channel: 12, state: LISTENING
D/BluetoothSocket( 2634): close() this: android.bluetooth.BluetoothSocket@769ea22, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35eec96c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25bb3cb3mSocket: android.net.LocalSocket@2a99270 impl:android.net.LocalSocketImpl@3f71a9e9 fd:FileDescriptor[79]
D/BluetoothSocket( 2634): Closing mSocket: android.net.LocalSocket@2a99270 impl:android.net.LocalSocketImpl@3f71a9e9 fd:FileDescriptor[79]
I/BtOppRfcommListener( 2634): BluetoothSocket listen thread finished
W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
E/WifiNative-wlan0( 1015): do suspend true
,V/BluetoothOppManager( 2634): cleanUp...
,D/DockEventReceiver( 1313): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1313): onReceive
,V/BluetoothStatusReceiver( 1176): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1176): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5993): MountEmulatedStorage()
I/libpersona( 5993): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5993): v2
I/libpersona( 5993): KNOX_SDCARD not a persona
I/SELinux ( 5993): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5993): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5993): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5993 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 5993): TimaSignature is unavailable
,D/ActivityThread( 5993): Added TimaKeyStore provider,
,D/UserAnalysis.PlaceProvider( 5993): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 5993): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5993): SecurePlaceDbHelper() 
D/UserAnalysis( 5993): Create SecureDbHelper
,D/IntelligenceServiceApplication( 5993): onCreate(),
,I/ActivityManager( 1015): Killing 4416:com.google.android.music:main/u0a108 (adj 15): empty #31
,D/AuthorizationBluetoothService( 1712): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
D/IntelligenceServiceApplication( 5993): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 5993): [PlaceDetection::stopService] Service stopped.,
,V/PlaceDetection v1.0.19 ( 5993): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,W/bt-l2cap( 2634): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2634): ag scb idx 1 not allocated
W/bt-btif ( 2634): ag scb idx 2 not allocated
E/bt-btif ( 2634): BTA AG is already disabled, ignoring ...
I/bt_userial_mct( 2634): exiting userial_read_thread
D/bt_userial_mct( 2634): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2634): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 2634): hw_epilog_process
D/bt_userial_mct( 2634): userial_close
I/bt_vendor( 2634): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,D/AndroidRuntime( 6002): ,
D/AndroidRuntime( 6002): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6002): CheckJNI is OFF,
D/AndroidRuntime( 6002): readGMSProperty: start
D/AndroidRuntime( 6002): readGMSProperty: already setted!!,
D/AndroidRuntime( 6002): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6002): readGMSProperty: could not set the property(default)!!,
D/AndroidRuntime( 6002): readGMSProperty: end
D/AndroidRuntime( 6002): addProductProperty: start
,W/libprocessgroup( 1015): failed to open /acct/uid_10108/pid_4416/cgroup.procs: No such file or directory,
,E/AffinityControl( 6002): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6002): Calling main entry com.android.commands.pm.Pm
,I/wpa_supplicant( 1386): nl80211: Received scan results (5 BSSes)
,D/WifiP2pService( 1015): InactiveState{ what=147461 },
D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 }
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 },
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PackageManager( 1015): START PACKAGE DELETE: observer{360995724}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
V/NativeCrypto( 1712): Read error: ssl=0xb7fafec0: I/O error during system call, Connection timed out
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/PackageManager( 1015): !@killApplicatoin: 10345, uninstall pkg
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NativeCrypto( 1712): SSL shutdown failed: ssl=0xb7fafec0: I/O error during system call, Broken pipe
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
E/ConnectivityService( 1015): updateNetworkInfo()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1015): Tagging socket 334 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/qtaguid ( 1015): Untagging socket 334
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/PackageSettings( 1015): Skipping PackageSetting{2f4dc2c5 com.test.thalitest/10338} due to missing metadata
,D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1452): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1452): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292,
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 5910:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{21f7936e u0 com.example.hello/.MainActivity t19}
,D/InputDispatcher( 1015): Focus left window: 5910
I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1015): Focused application released
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/bt_vendor( 2634): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 2634): bluetooth satus is on
I/bt_vendor( 2634): bt-vendor : resetting BT status
I/bt_vendor( 2634): Starting hciattach daemon
I/bt_vendor( 2634): try to set false
,I/bt_vendor( 2634): Starting hciattach daemon
,I/bt_vendor( 2634): try to set false
,I/bt_vendor( 2634): cleanup
,I/GKI_LINUX( 2634): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2634): GKI_exit_task 0 done
I/GKI_LINUX( 2634): GKI_shutdown(): task [BTU] terminated
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,D/WifiP2pService( 1015): InactiveState{ what=131204 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=131204 }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1688): Starting #8
,I/Hs20UtilService( 1688): Message received 5007
,I/art     ( 4042): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 669us total 21.398ms
,D/WifiP2pService( 1015): sending p2p connection changed broadcast: FAILED
,I/art     ( 5205): Explicit concurrent mark sweep GC freed 9935(665KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 706us total 37.020ms
,E/SamsungIME( 1863): mOCRHelper is null
,W/GeofencerStateMachine( 1817): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,D/BluetoothAdapterState( 2634): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/BtConfig.SecureMode( 2634): isSecureModeOn:false
D/BluetoothAdapterService( 2634): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.gatt.GattService
D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
E/ConnectivityService( 1015): updateNetworkInfo()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/RCPManagerService( 1015): PackageReceiver onReceive()
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BtGatt.DebugUtils( 2634): handleDebugAction() action=null
,D/BtGatt.GattService( 2634): Received stop request...Stopping profile...
D/BtGatt.GattService( 2634): stop()
D/BtGatt.AdvertiseManager( 2634): advertise clients cleared
,V/NetworkStats( 1015): updateIfacesLocked()
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,V/NetworkStats( 1015): performPollLocked() took 7ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/WifiDisplayAdapter( 1015): onP2pDisconnected
,D/IpRemoteDisplayController( 1015): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1015): WfdBridgeServer is already null
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
D/WifiP2pService( 1015): sending p2p connection changed broadcast: DISCONNECTED
E/ConnectivityService( 1015): updateNetworkInfo()
D/WifiDisplayController( 1015): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1015): disconnect
D/WifiDisplayController( 1015): updateConnection
D/WifiDisplayController( 1015): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/WifiP2pService( 1015): P2pDisablingState
,D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
,D/WifiP2pService( 1015): P2pDisablingState{ what=147458 }
,D/WifiP2pService( 1015): p2p socket connection lost
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/AllShareCastTile( 1176): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiP2pService( 1015): P2pDisabledState
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1176): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002,
D/WifiDisplayController( 1015): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1015): onP2pDisconnected
D/IpRemoteDisplayController( 1015): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1015): WfdBridgeServer is already null,
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): P2pDisabledState{ what=143375 }
,D/WifiP2pService( 1015): DefaultState{ what=143375 }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.hid.HidService
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.hdp.HealthService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.pan.PanService
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1386): p2p0: State: DISCONNECTED -> DISCONNECTED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2634): Not skipping com.broadcom.bt.service.sap.SapService
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=false enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10345
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,D/STATUSBAR-WifiQuickSettingButton( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.example.hello
D/HotspotTile( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1176): Wifi onReceive(0)
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
D/STATUSBAR-QSTileView( 1176): onStateChanged: Wi-Fi
,D/HotspotTile( 1176): onReceive : 0, 0
D/WifiCredService( 1313): Action received :android.net.wifi.WIFI_STATE_CHANGED
I/KLMS-2.5.123: ( 3667): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Nov 20 12:50:30 GMT+01:00 2015
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/WifiScanningService( 1015): SCAN_AVAILABLE : 1
D/RttService( 1015): SCAN_AVAILABLE : 1
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
,W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/RegisteredServicesCache( 1440): empty dynamic service
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,D/RttService( 1015): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2634): Stopping profile services that were post enabled
E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/WifiScanningService( 1015): DefaultState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/HeadsetService( 2634): Received stop request...Stopping profile...
D/TaskPersister( 1015): removeObsoleteFile: deleting file=19_task.xml
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1015): no available spell checker services found
,I/KLMS-2.5.123: ( 3667): KLMSAbstractReciever(): onReceive().END.
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3667): KLMSIntentService(): onCreate()
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/A2dpService( 2634): Received stop request...Stopping profile...
,D/HeadsetProfile( 1313): Bluetooth service disconnected
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/splitIntent( 1015): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1015): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1015): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/A2dpStateMachine( 2634): Exit Disconnected: -1
,I/KLMS-2.5.123: ( 3667): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3667): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/wpa_supplicant( 1386): Blacklist: Clear (all) 
,E/Zygote  ( 6029): MountEmulatedStorage()
E/Zygote  ( 6029): v2
I/libpersona( 6029): KNOX_SDCARD checking this for 10090
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
I/libpersona( 6029): KNOX_SDCARD not a persona
V/EnterpriseBillingPolicy( 1015): uID is 10345
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
,I/KLMS-2.5.123: ( 3667): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SELinux ( 6029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.example.hello
I/art     ( 1015): Explicit concurrent mark sweep GC freed 36372(2MB) AllocSpace objects, 9(196KB) LOS objects, 33% free, 24MB/36MB, paused 3.241ms total 245.112ms
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
E/WifiStateMachine( 1015): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6029 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3667): KLMSIntentService(): PACKAGE_REMOVED
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,I/SELinux ( 6029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 1
I/KLMS-2.5.123: ( 3667): KLMSIntentService(): listeningToPackageRemoved().START
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
,I/KLMS-2.5.123: ( 3667): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/PackageManager( 1015): delete codoeFile: 
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
I/AASA_removePackage( 1015): UID=10345 Target=com.example.hello
,I/wpa_supplicant( 1386): p2p0: CTRL-EVENT-TERMINATING 
I/Nat464Xlat( 1015): interfaceLinkStateChanged p2p0, false
D/BluetoothA2dp( 1015): Proxy object disconnected
D/AudioService( 1015): onServiceDisconnected: Bluetooth profile: 2
D/Tethering( 1015): interfaceLinkStateChanged p2p0, false
D/Tethering( 1015): interfaceStatusChanged p2p0, false
,D/BluetoothA2dp( 1313): Proxy object disconnected
D/A2dpProfile( 1313): Bluetooth service disconnected
,D/HidService( 2634): Received stop request...Stopping profile...
D/HidService( 2634): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2634): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2634): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2634): Cleaning up Bluetooth GID callback object
,D/PackageManager( 1015): result of delete: 1{360995724}
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
,D/HealthService( 2634): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
D/PanService( 2634): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
D/BluetoothPan( 1015): BluetoothPAN Proxy object disconnected
I/wpa_supplicant( 1386): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1386): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1386): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1386): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/BluetoothMapService( 2634): Received stop request...Stopping profile...
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/Tethering( 1015): InitialState.processMessage what=4
,D/BluetoothInputDevice( 1313): Proxy object disconnected
D/HidProfile( 1313): Bluetooth service disconnected
D/BluetoothPan( 1313): BluetoothPAN Proxy object disconnected
D/PanProfile( 1313): Bluetooth service disconnected
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,E/Tethering( 1015): No numeric data
,D/TimaKeyStoreProvider( 6029): TimaSignature is unavailable
,D/ActivityThread( 6029): Added TimaKeyStore provider
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,D/SapService( 2634): Received stop request...Stopping profile...
D/SapService( 2634): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5eec17b
,D/AndroidRuntime( 6002): Shutting down VM
D/BluetoothMap( 1313): Proxy object disconnected
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/MapProfile( 1313): Bluetooth service disconnected
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1015): clearTetheredNotification()
,E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.hid.HidService
,D/Bluetoothsap( 1313): BluetoothSAP Proxy object disconnected
D/SapProfile( 1313): Bluetooth service disconnected
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
,W/BluetoothHeadsetServiceJni( 2634): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2634): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2634): Proxy object disconnected
D/BluetoothAdapterService( 2634): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2634): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2634): GKI_exit_task 2 done
I/GKI_LINUX( 2634): GKI_shutdown(): task [A2DP-MEDIA] terminated
E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothHealthServiceJni( 2634): Cleaning up Bluetooth Health Interface...
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked() took 7ms
,W/BluetoothHealthServiceJni( 2634): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni( 2634): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2634): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2634): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(99533179)( 2634): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2634): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2634): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothAdapterState( 2634): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 2634): Setting state to 10
I/BluetoothAdapterState( 2634): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2634): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2634): updateAdapterState state is 10
,D/BluetoothAdapterService( 2634): Autoconnection is available 
D/BluetoothAdapterService( 2634): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2634): Entering OffState
D/BluetoothA2dp( 1313): onBluetoothStateChange: up=false
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/BluetoothAdapter( 1817): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1817): Bluetooth is turned off, stop adv and scan
E/SMD     (  290): DCD OFF
I/KLMS-2.5.123: ( 3667): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3667): KLMSIntentService(): onDestroy()
,D/Bluetoothsap( 1313): onBluetoothStateChange: up=false
D/Bluetoothsap( 1313): Unbinding service...
,D/BluetoothAdapter( 1313): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1313): Bluetooth is turned off, stop adv and scan
,D/elm:15121( 6029): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6029): ELMEngine.ELMEngine( context ).
D/BluetoothAdapter( 1452): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1452): Bluetooth is turned off, stop adv and scan
D/BluetoothInputDevice( 1313): onBluetoothStateChange: up=false
D/elm:15121( 6029): MDMBridge.setEnterpriseBridge()
,D/BluetoothAdapter( 1433): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1433): Bluetooth is turned off, stop adv and scan
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6029): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/BluetoothAdapter( 1440): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1440): Bluetooth is turned off, stop adv and scan
,D/BluetoothPbap( 1313): onBluetoothStateChange: up=false
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/BluetoothAdapter( 1176): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1176): Bluetooth is turned off, stop adv and scan
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1015): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1015): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 2634): onBluetoothStateChange: up=false
,D/BluetoothMap( 1313): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/elm:15121( 6029): ElmAgentService : onCreate()
,D/elm:15121( 6029): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6029): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6029): MDMBridge.getInstance()
D/elm:15121( 6029): MDMBridge.getAllLicenseInfoFromSDK()
,D/BluetoothAdapter( 2634): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2634): Bluetooth is turned off, stop adv and scan
,D/BluetoothA2dp( 1015): onBluetoothStateChange: up=false
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 6029): MDMBridge.getAllLicenseInfoFromSDK()
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/PCWCLIENTTRACE_PushUtil( 5604): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5604): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5604): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5604): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/BluetoothManagerService( 1015): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,I/wpa_supplicant( 1386): Blacklist: Clear (all) 
,W/InputMethodManagerService( 1015): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1015): [BT Setting State] State =10
I/InputMethodManagerService( 1015): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1176): 242450346: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,D/BluetoothAdapter( 1176): 242450346: getState() :  mService = null. Returning STATE_OFF
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/BluetoothTile( 1176): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1176):  getBluetoothState : 10
D/BluetoothAdapter( 1176): 242450346: getState() :  mService = null. Returning STATE_OFF
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1176): 242450346: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1015): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothAdapter( 1176): 242450346: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1015): setIconVisibility slot=bluetooth visible=false
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneStatusBar( 1176): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/BluetoothEventManager( 1313): Received android.bluetooth.adapter.action.STATE_CHANGED
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/SamsungIME( 1863): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1386): wlan0: CTRL-EVENT-TERMINATING 
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/elm:15121( 6029): ElmAgentService : onDestroy().
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
D/PhoneStatusBar( 1176): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SA      ( 5730): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/GKI_LINUX( 2634): gki_task task_id=1 [BTIF] terminating
,I/SA      ( 5730): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10345 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
I/GKI_LINUX( 2634): GKI_exit_task 1 done
I/GKI_LINUX( 2634): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2634): cleanupNative: return from cleanup
,I/ActivityManager( 1015): Killing 5160:com.google.android.gm/u0a99 (adj 15): empty #31
,V/AlarmManager( 1015): waitForAlarm result :4
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/art     ( 2634): System.exit called, status: 0
I/AndroidRuntime( 2634): VM exiting with result code 0, cleanup skipped.
,D/UsbSettingsManager( 1015): clearDefaults: com.example.hello
,I/PackagesMonitor( 4948): PackagesMonitor onReceive :com.example.hello
,I/CrashAnrDetector( 1015): onPackageRemoved : com.example.hello
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1015): updateDataUsageMap
,W/art     ( 6002): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager( 1015): Process com.android.bluetooth (pid 2634)(adj 0) has died(87,677)
W/libprocessgroup( 1015): failed to open /acct/uid_10099/pid_5160/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1015): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-wlan0( 1015): callSECApiBoolean - ID [21]
,W/Settings( 5822): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1176): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1176): onStateChanged: Wi-Fi
,D/HotspotTile( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1176): onReceive : 1, 0
,W/Settings( 1817): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiCredService( 1313): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/Mms/FreeMessageStatusReceiver( 4722): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1015): enable value -1
,I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
,D/Mms/FreeMessageReceiverService( 4722): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4722): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1015): List of disabled apps :
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5688): onReceive() it will make start service
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/Compatibility( 5688): onHandleIntent()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 5993): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/Compatibility( 5688): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10345, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5688): found: 2
,D/Compatibility( 5688): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5688): skipping ResolveInfo{9036ff1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5688): considering ResolveInfo{27f847d6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5688): default: com.sec.android.app.soundalive.SAControlPanelActivity
,W/ContextImpl( 5055): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
D/Compatibility( 5688): enabling receiver ResolveInfo{101dfa57 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/Compatibility( 5688): enabling receiver ResolveInfo{35544944 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 5993): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5993): (3850) statement aborts at 39: [DELETE FROM enabled_place_category WHERE package_id='com.example.hello' AND place_category IN (1, 2, 3, 0)] disk I/O error
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5688): enabling receiver ResolveInfo{11ce1a2d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5688): enabling receiver ResolveInfo{c890b62 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  ( 6068): MountEmulatedStorage()
,E/Zygote  ( 6068): v2
I/libpersona( 6068): KNOX_SDCARD checking this for 1000,
,I/libpersona( 6068): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6068 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SQLiteLog( 5055): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,D/Compatibility( 5688): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/SELinux ( 6068): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/AndroidRuntime( 5993): Shutting down VM,
,I/SELinux ( 6068): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6068): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/AndroidRuntime( 5993): FATAL EXCEPTION: main
E/AndroidRuntime( 5993): Process: com.samsung.android.intelligenceservice, PID: 5993
E/AndroidRuntime( 5993): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5993): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5993): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 5993): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5993): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5993): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
E/AndroidRuntime( 5993): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:66)
E/AndroidRuntime( 5993): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
E/AndroidRuntime( 5993): 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
E/AndroidRuntime( 5993): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
E/AndroidRuntime( 5993): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 5993): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 5993): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5993): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 5993): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5993): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5993): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 5993): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
D/TimaKeyStoreProvider( 6068): TimaSignature is unavailable
D/ActivityThread( 6068): Added TimaKeyStore provider
E/SQLiteDatabase( 5055): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5055): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5055): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5055): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5055): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5055): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5055): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5055): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5055): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5055): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5055): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5055): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5055): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5055): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5055): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5055): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5055): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5055): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5055): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5055): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5055): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5055): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5055): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 1015): Can't write: system_app_crash
E/DropBoxManagerService( 1015): java.io.FileNotFoundException: /data/system/dropbox/drop171.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1015): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1015): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1015): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1015): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1015): 	... 5 more
I/Process ( 5993): Sending signal. PID: 5993 SIG: 9
W/ResourcesManager( 6068): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.

```
