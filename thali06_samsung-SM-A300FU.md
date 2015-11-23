#### Test 503880197c51433_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  289): DCD OFF
,D/AndroidRuntime( 5901): 
D/AndroidRuntime( 5901): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5901): CheckJNI is OFF
D/AndroidRuntime( 5901): readGMSProperty: start
D/AndroidRuntime( 5901): readGMSProperty: already setted!!
D/AndroidRuntime( 5901): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5901): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5901): readGMSProperty: end
D/AndroidRuntime( 5901): addProductProperty: start
E/AffinityControl( 5901): AffinityControl: registerfunction enter
D/AndroidRuntime( 5901): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
--------- beginning of system
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5914 uid=10345 gids={50345, 9997, 3003, 3001, 3002} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1483
D/AndroidRuntime( 5901): Shutting down VM
E/Zygote  ( 5914): MountEmulatedStorage()
E/Zygote  ( 5914): v2
I/libpersona( 5914): KNOX_SDCARD checking this for 10345
I/libpersona( 5914): KNOX_SDCARD not a persona
I/SELinux ( 5914): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, iello
I/SELinux ( 5914): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5914): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5914): TimaSignature is unavailable
D/ActivityThread( 5914): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1019): Display changed displayId=0
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1483): updateVisibility : ActivityRecord{2be7a4ec token=android.os.BinderProxy@2a159285 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1483): onTrimMemory. Level: 20
I/WebViewFactory( 5914): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5914): Time to load native libraries: 2 ms (timestamps 5979-5981)
I/LibraryLoader( 5914): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5914): Binding Chromium to main looper Looper (main, tid 1) {2be8a706}
I/LibraryLoader( 5914): Expected native library version number "",actual native library version number ""
I/chromium( 5914): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 5901): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/BrowserStartupController( 5914): Initializing chromium process, singleProcess=true
W/art     ( 5914): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5914): ApplicationContext is null in ApplicationStatus
W/chromium( 5914): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5914): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5914): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5914): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5914): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5914): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5914): Local Branch: 
I/Adreno-EGL( 5914): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5914): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5914):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2634): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2634): Disconnected process message: 10
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
W/art     ( 5914): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5914): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5914): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5914): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 5914): CordovaWebView is running on device made by: samsung
W/art     ( 5914): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5914): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{19f3531c u0 com.example.hello/.MainActivity t19}
D/OpenGLRenderer( 5914): Render dirty regions requested: true
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
W/chromium( 5914): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5914): updateVisibility : ActivityRecord{1f269b53 token=android.os.BinderProxy@756918d {com.example.hello/com.example.hello.MainActivity}} show : true
D/PhoneWindow( 5914): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5914): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1019): Focus entered window: 5914
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5914): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5914): Initialized EGL, version 1.4
D/OpenGLRenderer( 5914): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5914): Enabling debug mode 0
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5914): showStatusIcon on inactive InputConnection
I/Timeline( 5914): Timeline: Activity_idle id: android.os.BinderProxy@756918d time:86505
I/SamsungIME( 1894): getCurrentCandidateView
I/ActivityManager( 1019): Displayed Component not be shown by security: +635ms (total +714ms)
W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{19f3531c u0 com.example.hello/.MainActivity t19} time:86521
I/SurfaceFlinger(  258): id=12 Removed iello (7/9)
I/SurfaceFlinger(  258): id=12 Removed iello (-2/9)
D/SamsungIME( 1894): Dismiss ExpandCandiate
W/BindingManager( 5914): Cannot call determinedVisibility() - never saw a connection for the pid: 5914
I/SamsungIME( 1894): getDebugLevel  : 0x4f4c
I/chromium( 5914): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/SamsungIME( 1894): getDebugLevel  : 0x4f4c
I/SamsungIME( 1894): KeybaordView init() : load resources
I/SamsungIME( 1894): getCurrentKeyboard
I/SamsungIME( 1894): getTextKeyboard
D/SamsungIME( 1894): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5914): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 5914): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5914): JniHelper::setJavaVM(0xb7cdf448), pthread_self() = -1205632712
D/JX-Cordova( 5914): jxcore cordova android initializing
W/jxcore-log( 5914): Initializing JXcore engine
W/jxcore-log( 5914): JXcore engine is ready
W/jxcore-log( 5914): Starting JXcore engine
E/audit   ( 1889): type=1400 msg=audit(1448298983.244:205): avc:  denied  { ioctl } for  pid=5914 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1889):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1889): type=1300 msg=audit(1448298983.244:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beaa6d58 items=0 ppid=304 ppcomm=main pid=5914 auid=4294967295 uid=10345 gid=10345 euid=10345 suid=10345 fsuid=10345 egid=10345 sgid=10345 fsgid=10345 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1889): type=1320 msg=audit(1448298983.244:205): 
W/jxcore-log( 5914): Platform android
W/jxcore-log( 5914): 
W/jxcore-log( 5914): Process ARCH arm
W/jxcore-log( 5914): 
I/jxcore-log( 5914): JXcore Cordova bridge is ready!
I/jxcore-log( 5914): 
W/jxcore-log( 5914): JXcore engine is started
E/jxcore-log( 5914): >> samsung-SM-A300FU
E/jxcore-log( 5914): 
I/jxcore-log( 5914): Total memory 1451114496
I/jxcore-log( 5914): 
I/jxcore-log( 5914): Free memory 22736896
I/jxcore-log( 5914): 
I/jxcore-log( 5914): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5914): 
I/jxcore-log( 5914): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5914): 
I/jxcore-log( 5914): userPath [ 'www' ]
I/jxcore-log( 5914): 
I/jxcore-log( 5914): Size 540 960
I/jxcore-log( 5914): 
I/jxcore-log( 5914): Screen Brightness 160
I/jxcore-log( 5914): 
E/jxcore-log( 5914): Dummy Error Log.
E/jxcore-log( 5914): 
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/jxcore-log( 5914): getBuffer is called!!!!
I/jxcore-log( 5914): 
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5963): MountEmulatedStorage(),
E/Zygote  ( 5963): v2
,I/libpersona( 5963): KNOX_SDCARD checking this for 10071
I/libpersona( 5963): KNOX_SDCARD not a persona
,I/ActivityManager( 1019): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5963 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5963): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5963): TimaSignature is unavailable
,D/ActivityThread( 5963): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/GAV2    ( 5963): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 5963): Created application version: 3.6.9 (30609)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1709): Explicit concurrent mark sweep GC freed 21024(1251KB) AllocSpace objects, 3(60KB) LOS objects, 39% free, 7MB/12MB, paused 993us total 50.138ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BooksSync( 5963): Starting books sync for 61035162, extras: ade
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 5963): (284) automatic index on view_volumes(volume_id)
,I/BooksConfig( 5963): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1709): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1709): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1709): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1709): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 26088(1404KB) AllocSpace objects, 11(180KB) LOS objects, 33% free, 23MB/35MB, paused 2.068ms total 138.990ms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1709): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1709): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1709): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1709): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1709): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5963): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5963): Soft error
E/BooksSync( 5963): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5963): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5963): Sync error
E/BooksSync( 5963): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5963): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5963): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 62080, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1019): Killing 4934:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,W/libprocessgroup( 1019): failed to open /acct/uid_10035/pid_4934/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BluetoothAdapter( 5914): disable()
,D/SettingsProvider( 1019): name = bluetooth_on
,D/BluetoothAdapterState( 2634): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2634): Setting state to 13
,I/BluetoothAdapterState( 2634): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2634): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2634): updateAdapterState state is 13
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2634): Autoconnection is available 
D/BluetoothAdapterService( 2634): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2634): terminating service from this receiver
,I/BluetoothPbapService( 2634): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothSocket( 2634): close() in, this: android.bluetooth.BluetoothSocket@359fc9c6, channel: 19, state: LISTENING
D/BluetoothSocket( 2634): close() this: android.bluetooth.BluetoothSocket@359fc9c6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f1d4aee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19a76d87mSocket: android.net.LocalSocket@2d12f4b4 impl:android.net.LocalSocketImpl@2ed938dd fd:FileDescriptor[74]
D/BluetoothSocket( 2634): Closing mSocket: android.net.LocalSocket@2d12f4b4 impl:android.net.LocalSocketImpl@2ed938dd fd:FileDescriptor[74]
,D/BluetoothAdapterProperties( 2634): onBluetoothDisable(),
D/BluetoothAdapterProperties( 2634): mDiscovering is false
,D/SecContentProvider( 1019): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2634): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,W/InputMethodManagerService( 1019): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1019): [BT Setting State] State =13
,D/BluetoothTile( 1176):  onBluetoothStateChange:
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled,
D/WifiService( 1019): setWifiEnabled: false pid=5914, uid=10345
D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1019): mCursor = null
D/SettingsProvider( 1019): name = wifi_on
D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothTile( 1176):  handleUpdatestate:false name:null
,D/BluetoothTile( 1176): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1176):  getBluetoothState : 13
E/WifiStateMachine( 1019): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1389): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1389): wlan0: Setting scan request: 0 sec 0 usec
I/jxcore-log( 5914): ****TEST TOOK:  5088  ms ****
I/jxcore-log( 5914): 
I/wpa_supplicant( 1389): P2P: Current p2p state = IDLE
I/jxcore-log( 5914): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5914): 
I/wpa_supplicant( 1389): Scan requested (ret=0) - scan timeout 30 seconds
,I/SamsungIME( 1894): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/STATUSBAR-QSTileView( 1176): onStateChanged: Bluetooth
V/BluetoothEventManager( 1319): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService( 1019): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1019): setIconVisibility slot=bluetooth visible=false
D/BluetoothAdapterProperties( 2634): Scan Mode:20
D/PhoneStatusBar( 1176): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterState( 2634): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2634): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/BluetoothSocket( 2634): close() in, this: android.bluetooth.BluetoothSocket@39bebc52, channel: 5, state: LISTENING
D/BluetoothSocket( 2634): close() this: android.bluetooth.BluetoothSocket@39bebc52, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e619b8f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d035b23mSocket: android.net.LocalSocket@1044a820 impl:android.net.LocalSocketImpl@13585d9 fd:FileDescriptor[76]
D/BluetoothSocket( 2634): Closing mSocket: android.net.LocalSocket@1044a820 impl:android.net.LocalSocketImpl@13585d9 fd:FileDescriptor[76]
E/bt-btif ( 2634): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
I/BtOppRfcommListener( 2634): stopping Accept Thread
D/BluetoothSocket( 2634): close() in, this: android.bluetooth.BluetoothSocket@31684b9e, channel: 12, state: LISTENING
D/BluetoothSocket( 2634): close() this: android.bluetooth.BluetoothSocket@31684b9e, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36d103a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2aa6867fmSocket: android.net.LocalSocket@2b1c264c impl:android.net.LocalSocketImpl@196fa695 fd:FileDescriptor[81]
D/BluetoothSocket( 2634): Closing mSocket: android.net.LocalSocket@2b1c264c impl:android.net.LocalSocketImpl@196fa695 fd:FileDescriptor[81]
E/BtOppRfcommListener( 2634): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BtOppRfcommListener( 2634): BluetoothSocket listen thread finished
W/ContextImpl( 1319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
V/BluetoothOppManager( 2634): cleanUp...
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
E/bt-btif ( 2634): cmd socket is not created
D/btif_config_util( 2634): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothPbap( 1319): Proxy object disconnected
D/PbapServerProfile( 1319): Bluetooth service disconnected
E/bt-btm  ( 2634): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2634): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/DockEventReceiver( 1319): finishStartingService: stopping service
W/bt-l2cap( 2634): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2634): L2CAP - PSM: 0x001b not found for deregistration
,D/BluetoothNotiBroadcastReceiver( 1319): onReceive
,E/WifiNative-wlan0( 1019): do suspend true
,V/BluetoothStatusReceiver( 1176): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1176): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5998): MountEmulatedStorage()
I/libpersona( 5998): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5998): v2
I/libpersona( 5998): KNOX_SDCARD not a persona
I/SELinux ( 5998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5998 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 5998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1709): Read error: ssl=0xb81e4f48: I/O error during system call, Connection timed out,
D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
V/NativeCrypto( 1709): SSL shutdown failed: ssl=0xb81e4f48: I/O error during system call, Broken pipe
,D/ConnectivityService( 1019): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Forcing reevaluation
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1019): Tagging socket 96 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/WifiP2pService( 1019): InactiveState{ what=131204 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=131204 }
,D/TimaKeyStoreProvider( 5998): TimaSignature is unavailable
,D/ActivityThread( 5998): Added TimaKeyStore provider
D/WifiNetworkAgent( 1019): NetworkAgent: NetworkAgent channel lost
,I/qtaguid ( 1019): Untagging socket 96
,I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
,D/UserAnalysis.PlaceProvider( 5998): PlaceProvider onCreate(),
,D/WifiP2pService( 1019): sending p2p connection changed broadcast: FAILED
,D/UserAnalysis.SecureDbManager( 5998): Key for secure DB is newly created
W/ProcessCpuTracker( 1019): Skipping unknown process pid 6015
D/UserAnalysis.SecurePlaceDbHelper( 5998): SecurePlaceDbHelper() 
D/UserAnalysis( 5998): Create SecureDbHelper
I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiScanningService( 1019): SCAN_AVAILABLE : 1
D/RttService( 1019): SCAN_AVAILABLE : 1
D/RttService( 1019): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1019): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController( 1019): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1019): onP2pDisconnected
D/WifiP2pService( 1019): sending p2p connection changed broadcast: DISCONNECTED
D/IntelligenceServiceApplication( 5998): onCreate()
,E/WifiStateMachine( 1019): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 1019): P2pDisablingState
,V/AlarmManager( 1019): waitForAlarm result :4
,W/bt-l2cap( 2634): L2CAP - PSM: 0x0019 not found for deregistration
D/WifiP2pService( 1019): P2pDisablingState{ what=147458 }
W/bt-l2cap( 2634): L2CAP - PSM: 0x0017 not found for deregistration
D/WifiP2pService( 1019): p2p socket connection lost
W/bt-l2cap( 2634): L2CAP - PSM: 0x001b not found for deregistration
D/WifiP2pService( 1019): P2pDisabledState
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
E/WifiNative-wlan0( 1019): do suspend true
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/WifiP2pService( 1019): P2pDisabledState{ what=143375 }
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiP2pService( 1019): DefaultState{ what=143375 }
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/ActivityManager( 1019): Killing 4427:com.google.android.music:main/u0a108 (adj 15): empty #31
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/AuthorizationBluetoothService( 1709): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/IntelligenceServiceApplication( 5998): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 5998): [PlaceDetection::stopService] Service stopped.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1690): Starting #8
,I/Hs20UtilService( 1690): Message received 5007
D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
V/PlaceDetection v1.0.19 ( 5998): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,D/IpRemoteDisplayController( 1019): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 1019): WfdBridgeServer is already null
D/WifiDisplayController( 1019): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1019): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
D/WifiDisplayController( 1019): disconnect
D/WifiDisplayController( 1019): updateConnection
D/WifiDisplayController( 1019): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1019): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter( 1019): onP2pDisconnected
D/IpRemoteDisplayController( 1019): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1019): WfdBridgeServer is already null
D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/AllShareCastTile( 1176): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1176): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService( 1019): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityService( 1019): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/ConnectivityService( 1019): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1019): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1019): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/BroadcastQueue( 1019): Failure sending broadcast Intent { act=android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED flg=0x40000010 (has extras) }
W/BroadcastQueue( 1019): android.os.TransactionTooLargeException
W/BroadcastQueue( 1019): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1019): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1019): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1220)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:529)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:665)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:717)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1019): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1019): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1019): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1019): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1019): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): doQuit - quitNow()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1019): updateNetworkInfo()
E/ConnectivityService( 1019): updateNetworkInfo()
,D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
I/wpa_supplicant( 1389): p2p0: State: DISCONNECTED -> DISCONNECTED
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
,D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1019): MasterInitialState.processMessage what=3
,V/NetworkStats( 1019): updateIfacesLocked()
V/NetworkStats( 1019): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked() took 8ms
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1176): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1176): onStateChanged: Wi-Fi
D/HotspotTile( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1176): onReceive : 0, 0
D/WifiCredService( 1319): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/AndroidRuntime( 6008): 
D/AndroidRuntime( 6008): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6008): CheckJNI is OFF
D/AndroidRuntime( 6008): readGMSProperty: start
D/AndroidRuntime( 6008): readGMSProperty: already setted!!
D/AndroidRuntime( 6008): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6008): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6008): readGMSProperty: end
D/AndroidRuntime( 6008): addProductProperty: start
I/PowerManagerService( 1019): [PWL] Off : 30s ago
I/PowerManagerService( 1019): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1019): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=2038, ws=null) (elapsedTime=55967)
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1019, ws=WorkSource{10011}) (elapsedTime=117)
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1019, ws=null) (elapsedTime=48)
I/PowerManagerService( 1019): [PWL]       PARTIAL_WAKE_LOCK              'NetworkStats' (uid=1000, pid=1019, ws=null) (elapsedTime=38)
D/SSRM:n  ( 1019): SIOP:: AP = 330
E/Zygote  ( 6023): MountEmulatedStorage()
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD checking this for 10064
I/libpersona( 6023): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6023 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
I/wpa_supplicant( 1389): Blacklist: Clear (all) 
,D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
,D/ActivityThread( 6023): Added TimaKeyStore provider,
,I/wpa_supplicant( 1389): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1019): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged p2p0, false
D/Tethering( 1019): interfaceStatusChanged p2p0, false
,W/ResourcesManager( 6023): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,I/wpa_supplicant( 1389): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1389): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1389): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1389): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1389): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): InitialState.processMessage what=4
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
E/Tethering( 1019): No numeric data,
I/bt_vendor( 2634): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2634): bluetooth satus is on
,I/bt_vendor( 2634): bt-vendor : resetting BT status
I/bt_vendor( 2634): Starting hciattach daemon
I/bt_vendor( 2634): try to set false
D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1019): clearTetheredNotification()
I/bt_vendor( 2634): Starting hciattach daemon
,I/bt_vendor( 2634): try to set false
I/bt_vendor( 2634): cleanup
I/GKI_LINUX( 2634): gki_task task_id=0 [BTU] terminating
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/HotspotTile( 1176): updateTetherState():false, false
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/GKI_LINUX( 2634): GKI_exit_task 0 done
I/GKI_LINUX( 2634): GKI_shutdown(): task [BTU] terminated
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit,
V/NetworkStats( 1019): performPollLocked() took 5ms
D/BluetoothAdapterState( 2634): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2634): isSecureModeOn:false
D/BluetoothAdapterService( 2634): mProfilesStarted : true supportedProfileServices.length : 12
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.gatt.GattService
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/FileShare-Client( 6023): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/libprocessgroup( 1019): failed to open /acct/uid_10108/pid_4427/cgroup.procs: No such file or directory
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.hfp.HeadsetService
,D/BtGatt.DebugUtils( 2634): handleDebugAction() action=null
D/BtGatt.GattService( 2634): Received stop request...Stopping profile...
D/BtGatt.GattService( 2634): stop()
D/BtGatt.AdvertiseManager( 2634): advertise clients cleared
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/FileShare-Client( 6023): ClientBroadcastReceiver.onReceive - disconnected
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.hid.HidService
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.hdp.HealthService
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/AffinityControl( 6008): AffinityControl: registerfunction enter
,D/HeadsetService( 2634): Received stop request...Stopping profile...
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.pan.PanService
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 2634): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2634): Not skipping com.broadcom.bt.service.sap.SapService
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/AudioService( 1019): onServiceDisconnected: Bluetooth profile: 1
D/FileShare-Client( 6023): Outbound.stopDelayTimer - 
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/HeadsetProfile( 1319): Bluetooth service disconnected
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/A2dpService( 2634): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2634): Exit Disconnected: -1
W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2634): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 2634): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2634): Stopping profile services that were post enabled
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/AndroidRuntime( 6008): Calling main entry com.android.commands.pm.Pm
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/PackageManager( 1019): START PACKAGE DELETE: observer{856632119}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1019): deletePackage- pkg:com.example.hello, edmuserId:-1
,E/Zygote  ( 6061): MountEmulatedStorage()
E/Zygote  ( 6061): v2
I/libpersona( 6061): KNOX_SDCARD checking this for 10065,
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
I/libpersona( 6061): KNOX_SDCARD not a persona
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
I/SELinux ( 6061): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/SELinux ( 6061): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
E/SELinux ( 6061): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager( 1019): !@killApplicatoin: 10345, uninstall pkg
I/ActivityManager( 1019): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6061 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5163:com.google.android.gm/u0a99 (adj 15): empty #31
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 5914:com.example.hello/u0a345 (adj 0): stop com.example.hello cause uninstall pkg
,D/TimaKeyStoreProvider( 6061): TimaSignature is unavailable,
D/ActivityThread( 6061): Added TimaKeyStore provider
,W/PackageSettings( 1019): Skipping PackageSetting{cd278f2 com.test.thalitest/10338} due to missing metadata
,I/wpa_supplicant( 1389): Blacklist: Clear (all) 
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/WindowState( 1019): WIN DEATH: Window{359c654e u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1019): Focus left window: 5914
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{19f3531c u0 com.example.hello/.MainActivity t19}
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_5163/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): Spurious death for ProcessRecord{2a58a4 5914:com.example.hello/u0a345}, curProc for 5914: null
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10345 user=0: pkg removed
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{19f3531c u0 com.example.hello/.MainActivity t19 f}
W/ActivityManager( 1019): Duplicate finish request for ActivityRecord{19f3531c u0 com.example.hello/.MainActivity t19 f}
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,D/BluetoothA2dp( 1019): Proxy object disconnected
D/AudioService( 1019): onServiceDisconnected: Bluetooth profile: 2
,D/BluetoothA2dp( 1319): Proxy object disconnected
D/A2dpProfile( 1319): Bluetooth service disconnected
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HidService( 2634): Received stop request...Stopping profile...
D/HidService( 2634): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2634): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 2634): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2634): Cleaning up Bluetooth GID callback object
,D/InputDispatcher( 1019): Focused application released
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,D/BluetoothInputDevice( 1319): Proxy object disconnected
D/HidProfile( 1319): Bluetooth service disconnected
,D/HealthService( 2634): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,I/wpa_supplicant( 1389): wlan0: CTRL-EVENT-TERMINATING ,
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
I/art     ( 3959): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 701us total 32.383ms
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/art     ( 5204): Explicit concurrent mark sweep GC freed 9935(665KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 731us total 51.999ms
,E/SamsungIME( 1894): mOCRHelper is null
,W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,E/WifiStateMachine( 1019): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/PanService( 2634): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,D/WifiNative-wlan0( 1019): callSECApiBoolean - ID [21]
,D/FileShare-Server( 6061): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,D/BluetoothMapService( 2634): Received stop request...Stopping profile...
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BluetoothPan( 1319): BluetoothPAN Proxy object disconnected
D/PanProfile( 1319): Bluetooth service disconnected
,W/Settings( 5850): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/STATUSBAR-WifiQuickSettingButton( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1176): Wifi onReceive(1)
,D/STATUSBAR-QSTileView( 1176): onStateChanged: Wi-Fi
,D/HotspotTile( 1176): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,W/Settings( 1831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HotspotTile( 1176): onReceive : 1, 0
,D/WifiCredService( 1319): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager( 1019): Killing 4185:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.hid.HidService
,D/BluetoothMap( 1319): Proxy object disconnected
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
D/SapService( 2634): Received stop request...Stopping profile...
D/SapService( 2634): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2634): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88e33f4
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/MapProfile( 1319): Bluetooth service disconnected
,I/Hs20UtilService( 1690): Starting #9
,I/Hs20UtilService( 1690): Message received 5007
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
,D/Bluetoothsap( 1319): BluetoothSAP Proxy object disconnected
,D/SapProfile( 1319): Bluetooth service disconnected
,D/RegisteredServicesCache( 1445): empty dynamic service
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 42021(2MB) AllocSpace objects, 11(228KB) LOS objects, 33% free, 23MB/35MB, paused 10.708ms total 198.456ms
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/BluetoothHeadsetServiceJni( 2634): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2634): Cleaning up Bluetooth Handsfree callback object
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2634): Proxy object disconnected
D/BluetoothAdapterService( 2634): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 2634): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2634): GKI_exit_task 2 done
I/GKI_LINUX( 2634): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2634): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2634): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2634): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2634): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2634): Cleaning up Bluetooth PAN callback object
,D/PackageManager( 1019): delete codoeFile: 
,E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2634): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2634): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(143537140)( 2634): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,W/BluetoothSAPServiceJni( 2634): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2634): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterState( 2634): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2634): Setting state to 10
I/BluetoothAdapterState( 2634): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2634): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2634): updateAdapterState state is 10
D/BluetoothAdapterService( 2634): Autoconnection is available 
D/BluetoothAdapterService( 2634): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2634): Entering OffState
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10345, packageName = com.example.hello
,D/BluetoothAdapter( 1457): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1457): Bluetooth is turned off, stop adv and scan
I/AASA_removePackage( 1019): UID=10345 Target=com.example.hello
,D/PackageManager( 1019): result of delete: 1{856632119}
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BluetoothAdapter( 2634): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2634): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1426): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1426): Bluetooth is turned off, stop adv and scan
,D/AndroidRuntime( 6008): Shutting down VM
D/Bluetoothsap( 1319): onBluetoothStateChange: up=false
D/Bluetoothsap( 1319): Unbinding service...
D/BluetoothPbap( 1319): onBluetoothStateChange: up=false
D/BluetoothA2dp( 1019): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1319): onBluetoothStateChange: up=false
,D/BluetoothAdapter( 1319): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1019): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1019): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1176): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1176): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1831): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1831): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1445): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1445): Bluetooth is turned off, stop adv and scan
D/BluetoothA2dp( 1319): onBluetoothStateChange: up=false
,D/BluetoothMap( 1319): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2634): onBluetoothStateChange: up=false
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothInputDevice( 1319): onBluetoothStateChange: up=false
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService( 1019): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BluetoothAdapter( 1176): 641073639: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1176):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1176): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1176):  getBluetoothState : 10
D/BluetoothAdapter( 1176): 641073639: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1176): 641073639: getState() :  mService = null. Returning STATE_OFF
,I/SamsungIME( 1894): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothAdapter( 1176): 641073639: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1176): 641073639: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService( 1019): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,V/BluetoothEventManager( 1319): Received android.bluetooth.adapter.action.STATE_CHANGED
D/StatusBarManagerService( 1019): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1176): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/GKI_LINUX( 2634): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2634): GKI_exit_task 1 done
I/GKI_LINUX( 2634): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2634): cleanupNative: return from cleanup
,I/art     ( 2634): System.exit called, status: 0
,I/AndroidRuntime( 2634): VM exiting with result code 0, cleanup skipped.
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1019): uID is 10345
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10345
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
D/TaskPersister( 1019): removeObsoleteFile: deleting file=19_task.xml
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.example.hello
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1019): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1019): onPackageRemoved : com.example.hello
,I/ActivityManager( 1019): Process com.android.bluetooth (pid 2634)(adj 0) has died(81,677)
,I/ApplicationPolicy( 1019): updateDataUsageMap
W/InputMethodManagerService( 1019): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1019): [BT Setting State] State =10
I/InputMethodManagerService( 1019): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,W/art     ( 6008): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1690): Starting #10
,I/Hs20UtilService( 1690): Message received 5011
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6081): MountEmulatedStorage()
I/libpersona( 6081): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6081): v2
,I/libpersona( 6081): KNOX_SDCARD not a persona
I/SELinux ( 6081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6081): TimaSignature is unavailable
,D/ActivityThread( 6081): Added TimaKeyStore provider
,D/SecurityLogAgent( 6081): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6081): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6081): StateMachine : Current State = 1
,D/SecurityLogAgent( 6081): StateMachine : Changed Current State = 1
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4185/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
I/ActivityManager( 1019): Killing 5565:com.samsung.helphub/1000 (adj 15): empty #31
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Tethering( 1019): interfaceRemoved wlan0
,E/Tethering( 1019): attempting to remove unknown iface (wlan0), ignoring

```
