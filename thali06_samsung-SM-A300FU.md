#### Test 563583788793eb6_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime( 6099): 
D/AndroidRuntime( 6099): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6099): CheckJNI is OFF
D/AndroidRuntime( 6099): readGMSProperty: start
D/AndroidRuntime( 6099): readGMSProperty: already setted!!
D/AndroidRuntime( 6099): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6099): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6099): readGMSProperty: end
D/AndroidRuntime( 6099): addProductProperty: start
E/AffinityControl( 6099): AffinityControl: registerfunction enter
D/AndroidRuntime( 6099): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6111 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1478
D/AndroidRuntime( 6099): Shutting down VM
E/Zygote  ( 6111): MountEmulatedStorage()
E/Zygote  ( 6111): v2
I/libpersona( 6111): KNOX_SDCARD checking this for 10338
I/libpersona( 6111): KNOX_SDCARD not a persona
I/SELinux ( 6111): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6111): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6111): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6111): TimaSignature is unavailable
D/ActivityThread( 6111): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
D/Launcher( 1478): onTrimMemory. Level: 20
V/ActivityThread( 1478): updateVisibility : ActivityRecord{307402b5 token=android.os.BinderProxy@2bbd432b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/WebViewFactory( 6111): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 6099): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/LibraryLoader( 6111): Time to load native libraries: 2 ms (timestamps 6339-6341)
I/LibraryLoader( 6111): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6111): Binding Chromium to main looper Looper (main, tid 1) {5d876d7}
I/LibraryLoader( 6111): Expected native library version number "",actual native library version number ""
I/chromium( 6111): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6111): Initializing chromium process, singleProcess=true
W/art     ( 6111): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6111): ApplicationContext is null in ApplicationStatus
W/chromium( 6111): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6111): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6111): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6111): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6111): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6111): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6111): Local Branch: 
I/Adreno-EGL( 6111): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6111): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6111):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
W/art     ( 6111): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{3897b1d0 u0 com.test.thalitest/.MainActivity t20}
W/AwContents( 6111): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6111): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6111): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6111): CordovaWebView is running on device made by: samsung
W/art     ( 6111): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6111): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6111): Render dirty regions requested: true
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
W/chromium( 6111): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6111): updateVisibility : ActivityRecord{26263560 token=android.os.BinderProxy@2425b792 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6111): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6111): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1019): Focus entered window: 6111
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6111): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6111): Initialized EGL, version 1.4
D/OpenGLRenderer( 6111): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6111): Enabling debug mode 0
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1019): Displayed Component not be shown by security: +696ms (total +40s674ms)
W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{3897b1d0 u0 com.test.thalitest/.MainActivity t20} time:156881
W/IInputConnectionWrapper( 6111): showStatusIcon on inactive InputConnection
I/Timeline( 6111): Timeline: Activity_idle id: android.os.BinderProxy@2425b792 time:156886
I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1839): getCurrentCandidateView
D/SamsungIME( 1839): Dismiss ExpandCandiate
W/BindingManager( 6111): Cannot call determinedVisibility() - never saw a connection for the pid: 6111
I/SamsungIME( 1839): getDebugLevel  : 0x4f4c
I/SamsungIME( 1839): getDebugLevel  : 0x4f4c
I/SamsungIME( 1839): KeybaordView init() : load resources
I/SamsungIME( 1839): getCurrentKeyboard
I/SamsungIME( 1839): getTextKeyboard
D/SamsungIME( 1839): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 6111): Set native->JS mode to OnlineEventsBridgeMode
,E/SMD     (  288): DCD OFF
D/jxcore_app_log( 6111): JniHelper::setJavaVM(0xb83b5448), pthread_self() = -1198470472
I/chromium( 6111): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/jxcore-log( 6111): Initializing JXcore engine
W/jxcore-log( 6111): JXcore engine is ready
,E/audit   ( 1826): type=1400 msg=audit(1453134287.888:205): avc:  denied  { ioctl } for  pid=6160 comm="Thread-1061" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1826):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1826): type=1300 msg=audit(1453134287.888:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9de008f8 items=0 ppid=306 ppcomm=main pid=6160 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1061" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1826): type=1320 msg=audit(1453134287.888:205): 
,W/jxcore-log( 6111): Starting JXcore engine
,W/jxcore-log( 6111): Platform android,
W/jxcore-log( 6111): 
W/jxcore-log( 6111): Process ARCH arm
W/jxcore-log( 6111): 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6111): JXcore Cordova bridge is ready!
I/jxcore-log( 6111): 
,W/jxcore-log( 6111): JXcore engine is started
,E/jxcore  ( 6111): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6111): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6111): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 6111
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019): Killing 5107:com.google.android.talk/u0a102 (adj 15): empty #31
,W/PluginManager( 6111): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1478): onRestart, Launcher: 399623337
,D/Launcher( 1478): onStart, Launcher: 399623337
,D/Launcher.HomeView( 1478): onStart
,D/Launcher( 1478): onResume, Launcher: 399623337
,D/SettingsProvider( 1019): name = kids_home_mode
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,D/Launcher.HomeView( 1478): onResume
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1478): onResume
,D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1478): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/GalleryCacheReady( 4953): Receive : home resume
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/Recents_RecreateReceiver( 2534): onReceive by home
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1019): handle home activity for 0
,I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
D/Launcher.HomeView( 1478): onPause
D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
,D/Launcher( 1478): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5652): ui event
,V/TaskCloserActivity( 5613): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6163): MountEmulatedStorage(),
,E/Zygote  ( 6163): v2
I/libpersona( 6163): KNOX_SDCARD checking this for 10135
I/libpersona( 6163): KNOX_SDCARD not a persona
I/SELinux ( 6163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6163 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_5107/cgroup.procs: No such file or directory
I/SELinux ( 6163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1478, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
E/SELinux ( 6163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/SurfaceFlinger(  257): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1019): Focus entered window: 1478
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 1478): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,V/ActivityThread( 1478): updateVisibility : ActivityRecord{307402b5 token=android.os.BinderProxy@2bbd432b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1478): onStop
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/TimaKeyStoreProvider( 6163): TimaSignature is unavailable
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ActivityThread( 6163): Added TimaKeyStore provider
,D/SamsungIME( 1839): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/IInputConnectionWrapper( 6111): showStatusIcon on inactive InputConnection
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,W/ResourcesManager( 6163): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6163): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6163): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6163): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6163): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1478): Timeline: Activity_idle id: android.os.BinderProxy@2bbd432b time:159904
,W/ActivityManager( 1019): mDVFSHelper.release()
,I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{38cdccf u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:159926
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 4202:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5613): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4202/cgroup.procs: No such file or directory
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/Watchdog( 1019): !@Sync 5,
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5355): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5355): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1662): Vacuum at: now=1453134332946 tag=VacuumService
,I/GoogleURLConnFactory( 1662): Using platform SSLCertificateSocketFactory
,W/Uploader( 1662): No account for auth token provided
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1662): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1662): (HTTPLog)-Static: isShipBuild true
I/System.out( 1662): (HTTPLog)-Thread-190-269826919: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1662): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,I/qtaguid ( 1662): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,W/Uploader( 1662): No account for auth token provided
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,W/Uploader( 1662): No account for auth token provided
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,W/Uploader( 1662): No account for auth token provided
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,W/Uploader( 1662):  no longer exists, so no auth token.
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,W/Uploader( 1662): No account for auth token provided
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,I/art     ( 1662): Explicit concurrent mark sweep GC freed 44303(2MB) AllocSpace objects, 36(2MB) LOS objects, 39% free, 7MB/13MB, paused 1.399ms total 69.571ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1662): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1662): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1662): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1662): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1662): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1662): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1662): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1662): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1662): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1662): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1662): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1662): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1662): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1662): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1662): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1662, getuid(): 10011
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/SQLiteLog( 1662): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 45264(2MB) AllocSpace objects, 59(953KB) LOS objects, 33% free, 23MB/35MB, paused 2.493ms total 157.504ms
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6030): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 280590, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE,
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 11
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
W/GLSActivity( 1662): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1662): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1662): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1662): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1662): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1662): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1662): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
E/PlayEventLogger( 5355): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5355): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5355): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5355): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5355): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5355): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5355): 	at android.os.Binder.execTransact(Binder.java:461)
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5355): Ignoring header User-Agent because its value was null.
,I/System.out( 5355): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5355): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5355): (HTTPLog)-Static: isShipBuild true
I/System.out( 5355): (HTTPLog)-Thread-913-893563846: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5355): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5355): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  288): DCD OFF,
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 12
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 330s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 13
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
D/SSRM:n  ( 1019): SIOP:: AP = 270
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 14
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 390s ago,
,E/Watchdog( 1019): !@Sync 15
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/bootchecker(  311): bootchecker wake up!!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 16
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=531087 batch.start=534590
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6030): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 534590, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 18
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/Atfwd_Daemon(  314): Stop the daemon....,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 19
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1019): Plugged
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 20,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 21
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 600s ago
,E/Watchdog( 1019): !@Sync 22
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 23
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 24
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 680s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 25,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/Finsky  ( 5355): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5355): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/Watchdog( 1019): !@Sync 26
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5355): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5355): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5355): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5355): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5355): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1818): client connected with version: 7571000
,I/art     ( 1818): Explicit concurrent mark sweep GC freed 16066(888KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 8MB/13MB, paused 1.066ms total 54.349ms
,E/DataBuffer( 1818): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@267ee650)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5355): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 27
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 57995(5MB) AllocSpace objects, 227(3MB) LOS objects, 33% free, 23MB/35MB, paused 2.921ms total 162.550ms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5355): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 765s ago
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5355): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 28
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,E/SMD     (  288): DCD OFF
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5355): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 29
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5355): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5355): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5355): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5355): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1019): !@Sync 30
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 855s ago
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,I/art     ( 1662): Explicit concurrent mark sweep GC freed 45024(2MB) AllocSpace objects, 18(670KB) LOS objects, 39% free, 7MB/13MB, paused 1.430ms total 70.883ms
,D/GCM     ( 1662): Message class com.google.f.a.a.i
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 31
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 32
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 33
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 951s ago
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 34
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/AlarmManager( 1019): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/BooksSync( 6030): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6030): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1662): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1662): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1662): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1662): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1662): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6030): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6030): Soft error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6030): Sync error
E/BooksSync( 6030): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6030): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6030): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1041964, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 35
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/AlarmManager( 1019): waitForAlarm result :8
,V/AlarmManager( 1019): waitForAlarm result :4
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 36
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1051s ago
,E/Watchdog( 1019): !@Sync 37
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,V/AlarmManager( 1019): waitForAlarm result :8
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 38,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,E/Watchdog( 1019): !@Sync 39
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1453135344828
,I/ApplicationPolicy( 1019): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1019): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1019): ::isTableExists: Table exists 
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1453135345200
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 40
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1156s ago,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 41
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 42
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 43
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,E/Watchdog( 1019): !@Sync 44
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 1266s ago
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  288): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),E/Watchdog( 1019): !@Sync 45
D/AndroidRuntime( 6695): 
D/AndroidRuntime( 6695): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6695): CheckJNI is OFF
D/AndroidRuntime( 6695): readGMSProperty: start
D/AndroidRuntime( 6695): readGMSProperty: already setted!!
D/AndroidRuntime( 6695): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6695): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6695): readGMSProperty: end
D/AndroidRuntime( 6695): addProductProperty: start
E/AffinityControl( 6695): AffinityControl: registerfunction enter
D/AndroidRuntime( 6695): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{993305263}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1019): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 6111:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{42eb290 com.example.hello/10346} due to missing metadata
W/ActivityManager( 1019): Spurious death for ProcessRecord{154c6bc 6111:com.test.thalitest/u0a338}, curProc for 6111: null
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4077): Explicit concurrent mark sweep GC freed 17919(1024KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 874us total 54.961ms
W/GeofencerStateMachine( 1818): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1839): mOCRHelper is null
I/KLMS-2.5.123: ( 3703): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 17:44:57 GMT+01:00 2016
I/art     ( 5985): Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 25.226ms total 100.646ms
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3703): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): onCreate()
E/Zygote  ( 6709): MountEmulatedStorage()
E/Zygote  ( 6709): v2
I/libpersona( 6709): KNOX_SDCARD checking this for 10090
I/libpersona( 6709): KNOX_SDCARD not a persona
I/SELinux ( 6709): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3703): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/SELinux ( 6709): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6709 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3703): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/art     (  306): Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 722us total 25.224ms
I/art     ( 1019): Explicit concurrent mark sweep GC freed 57195(5MB) AllocSpace objects, 222(3MB) LOS objects, 33% free, 24MB/36MB, paused 2.901ms total 218.885ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.537ms
I/art     ( 1019): WaitForGcToComplete blocked for 202.548ms for cause Explicit
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.764ms
D/TimaKeyStoreProvider( 6709): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ActivityThread( 6709): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): listeningToPackageRemoved().START
D/RegisteredServicesCache( 1441): empty dynamic service
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/RCPManagerService( 1019): PackageReceiver onReceive()
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 6709): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6709): ELMEngine.ELMEngine( context ).
D/elm:15121( 6709): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6709): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6709): ElmAgentService : onCreate()
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 6709): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6709): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6709): MDMBridge.getInstance()
D/elm:15121( 6709): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6709): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3703): KLMSIntentService(): onDestroy()
D/elm:15121( 6709): ElmAgentService : onDestroy().
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
I/art     ( 1019): Explicit concurrent mark sweep GC freed 12600(650KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.462ms total 181.106ms
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
D/TaskPersister( 1019): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/PackageManager( 1019): delete codoeFile: 
I/PCWCLIENTTRACE_PushUtil( 5694): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5694): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5694): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5694): [onReceive] - android.intent.action.PACKAGE_REMOVED
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10338 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{993305263}
D/AndroidRuntime( 6695): Shutting down VM
I/SA      ( 5785): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5785): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackagesMonitor( 4953): PackagesMonitor onReceive :com.test.thalitest
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Mms/FreeMessageStatusReceiver( 5652): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
D/Mms/FreeMessageReceiverService( 5652): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5652): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1019): List of disabled apps :
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5878): onReceive() it will make start service
W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5878): onHandleIntent()
D/Compatibility( 5878): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5878): found: 2
D/Compatibility( 5878): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5878): skipping ResolveInfo{7c3a973 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5878): considering ResolveInfo{2de26030 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5878): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5878): enabling receiver ResolveInfo{17d1c4a9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/Zygote  ( 6730): MountEmulatedStorage()
E/Zygote  ( 6730): v2
I/libpersona( 6730): KNOX_SDCARD checking this for 10055
I/libpersona( 6730): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6730 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 6730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5878): enabling receiver ResolveInfo{11f26a2e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 6730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Compatibility( 5878): enabling receiver ResolveInfo{e2569cf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1019): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1019): onPackageRemoved : com.test.thalitest
D/Compatibility( 5878): enabling receiver ResolveInfo{11454f5c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5878): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6730): TimaSignature is unavailable
D/ActivityThread( 6730): Added TimaKeyStore provider
W/art     ( 6695): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/UserAnalysis.PlaceProvider( 6730): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6730): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6730): SecurePlaceDbHelper() 
D/UserAnalysis( 6730): Create SecureDbHelper
D/IntelligenceServiceApplication( 6730): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6730): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
E/SQLiteLog( 6730): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6730): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6730): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6730): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6730): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6730): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6730): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6730): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6730): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6730): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6730): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6730): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
W/SQLiteOpenHelper( 6730): Opened privacy in read-only mode
D/IntelligenceServiceApplication( 6730): no applications having user consent for prediction
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 5898): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 5898): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5898): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5898): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5898): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5898): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5898): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Zygote  ( 6748): MountEmulatedStorage()
I/libpersona( 6748): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6748): v2
I/libpersona( 6748): KNOX_SDCARD not a persona
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5898): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5898): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5898): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5898): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5898): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6748): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/PlaceDetection v1.0.19 ( 6730): [PlaceDetection::stopService] Service stopped.
I/ActivityManager( 1019): Killing 5184:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
I/SELinux ( 6748): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6748): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/PlaceDetection v1.0.19 ( 6730): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/SQLiteLog( 6730): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6730): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6730): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6730): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6730): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6730): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6730): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6730): Shutting down VM
E/AndroidRuntime( 6730): FATAL EXCEPTION: main
E/AndroidRuntime( 6730): Process: com.samsung.android.intelligenceservice, PID: 6730
E/AndroidRuntime( 6730): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6730): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6730): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6730): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6730): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6730): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6730): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6730): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6730): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6730): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6730): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6730): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
I/Process ( 6730): Sending signal. PID: 6730 SIG: 9
D/TimaKeyStoreProvider( 6748): TimaSignature is unavailable
D/ActivityThread( 6748): Added TimaKeyStore provider

```
