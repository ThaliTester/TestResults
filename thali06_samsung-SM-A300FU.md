#### Test 57924002a578a80_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
I/ServiceManager(  321): Waiting for service AtCmdFwd...
--------- beginning of system
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2652): Disconnected process message: 10
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 290
D/AndroidRuntime( 6057): 
D/AndroidRuntime( 6057): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6057): CheckJNI is OFF
D/AndroidRuntime( 6057): readGMSProperty: start
D/AndroidRuntime( 6057): readGMSProperty: already setted!!
D/AndroidRuntime( 6057): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6057): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6057): readGMSProperty: end
D/AndroidRuntime( 6057): addProductProperty: start
E/AffinityControl( 6057): AffinityControl: registerfunction enter
D/AndroidRuntime( 6057): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6069 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 6069): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1016): Focused application set to: xxxx
I/libpersona( 6069): KNOX_SDCARD not a persona
D/InputDispatcher( 1016): Focus left window: 1494
E/Zygote  ( 6069): MountEmulatedStorage()
E/Zygote  ( 6069): v2
D/AndroidRuntime( 6057): Shutting down VM
I/SELinux ( 6069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6069): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6069): TimaSignature is unavailable
D/ActivityThread( 6069): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
V/ActivityThread( 1494): updateVisibility : ActivityRecord{e9bcde8 token=android.os.BinderProxy@56cdb6b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1494): onTrimMemory. Level: 20
I/WebViewFactory( 6069): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6069): Time to load native libraries: 2 ms (timestamps 7277-7279)
I/LibraryLoader( 6069): Expected native library version number "",actual native library version number ""
W/art     ( 6057): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6069): Binding Chromium to main looper Looper (main, tid 1) {33ed3b22}
,I/LibraryLoader( 6069): Expected native library version number "",actual native library version number ""
,I/chromium( 6069): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/SMD     (  290): DCD OFF,
,I/BrowserStartupController( 6069): Initializing chromium process, singleProcess=true,
,W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6069): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6069): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
I/Adreno-EGL( 6069): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6069): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6069): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6069): Local Branch: 
I/Adreno-EGL( 6069): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6069): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6069):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6069): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6069): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6069): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6069): CordovaWebView is running on device made by: samsung
W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6069): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{24ca855e u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6069): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/chromium( 6069): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6069): updateVisibility : ActivityRecord{37e7c8ff token=android.os.BinderProxy@73b6459 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6069): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6069): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 6069
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6069): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6069): Initialized EGL, version 1.4
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6069): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6069): Enabling debug mode 0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +754ms (total +10s353ms)
,W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{24ca855e u0 com.test.thalitest/.MainActivity t20} time:127889
,I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6069): showStatusIcon on inactive InputConnection
I/Timeline( 6069): Timeline: Activity_idle id: android.os.BinderProxy@73b6459 time:127902
,I/SamsungIME( 1840): getCurrentCandidateView
,D/SamsungIME( 1840): Dismiss ExpandCandiate
,W/BindingManager( 6069): Cannot call determinedVisibility() - never saw a connection for the pid: 6069
,I/SamsungIME( 1840): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1840): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1840): KeybaordView init() : load resources
,D/JsMessageQueue( 6069): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1840): getCurrentKeyboard
,I/SamsungIME( 1840): getTextKeyboard
,D/SamsungIME( 1840): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6069): JniHelper::setJavaVM(0xb88b0448), pthread_self() = -1193238416
,I/chromium( 6069): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,W/jxcore-log( 6069): Initializing JXcore engine
W/jxcore-log( 6069): JXcore engine is ready
,E/audit   ( 1835): type=1400 msg=audit(1454460145.505:205): avc:  denied  { ioctl } for  pid=6118 comm="Thread-1046" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1835):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1835): type=1300 msg=audit(1454460145.505:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=3 a3=9ec868f8 items=0 ppid=307 ppcomm=main pid=6118 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1046" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1835): type=1320 msg=audit(1454460145.505:205): 
,W/jxcore-log( 6069): Starting JXcore engine
,W/jxcore-log( 6069): Platform android
W/jxcore-log( 6069): 
W/jxcore-log( 6069): Process ARCH arm
W/jxcore-log( 6069): 
,I/jxcore-log( 6069): JXcore Cordova bridge is ready!
I/jxcore-log( 6069): 
,W/jxcore-log( 6069): JXcore engine is started
,E/jxcore  ( 6069): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6069): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6069): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1016): Set to : 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus left window: 6069
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1016): Killing 5262:com.google.android.gm/u0a99 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,V/WindowManager( 1016): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1494): onRestart, Launcher: 976105116
,D/Launcher( 1494): onStart, Launcher: 976105116
,D/Launcher.HomeView( 1494): onStart
,D/Launcher( 1494): onResume, Launcher: 976105116
,D/SettingsProvider( 1016): name = kids_home_mode
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10006
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/Launcher.HomeView( 1494): onResume
,D/Launcher( 1494): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1494): onResume
,D/ActivityManager( 1016): handle home activity for 0
I/WallpaperManagerService( 1016): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1016): post home show event for user 0
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1016):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1016): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/Launcher.HomeView( 1494): onPause
,D/Launcher( 1494): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/splitIntent( 1016): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1016): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/GalleryCacheReady( 5054): Receive : home resume
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2529): onReceive by home
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,I/SurfaceFlinger(  259): id=15 createSurf (540x960),1 flag=4, Mauncher
,V/TaskCloserActivity( 5932): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/Mms/UIEventReceiver( 4737): ui event
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/InputDispatcher( 1016): Focus entered window: 1494
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1494): log_dcs ThreadedRenderer::initialize entered! 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
V/ActivityThread( 1494): updateVisibility : ActivityRecord{e9bcde8 token=android.os.BinderProxy@56cdb6b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1016): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1494, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/Launcher.HomeView( 1494): onStop
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 6069): showStatusIcon on inactive InputConnection
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1840): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
V/TaskCloserActivity( 5932): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,I/Timeline( 1494): Timeline: Activity_idle id: android.os.BinderProxy@56cdb6b time:130094
,W/ActivityManager( 1016): mDVFSHelper.release(),
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{3391b10f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:130100
,W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_5262/cgroup.procs: No such file or directory
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,V/AlarmManager( 1016): waitForAlarm result :4
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 50751(2MB) AllocSpace objects, 31(500KB) LOS objects, 33% free, 24MB/36MB, paused 2.413ms total 171.307ms
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5424): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5424): [1] 5.onFinished: Installation state replication failed.,
,D/Finsky  ( 5424): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,I/BooksSync( 6000): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6000): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
,I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6000): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6000): Soft error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6000): Sync error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6000): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155041, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 50s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1713): Explicit concurrent mark sweep GC freed 23674(1377KB) AllocSpace objects, 5(101KB) LOS objects, 39% free, 7MB/12MB, paused 1.006ms total 44.503ms
,D/Finsky  ( 5424): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5424): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5424): [1] 5.onFinished: Scheduling replication attempt 5.
,E/Watchdog( 1016): !@Sync 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 6
,V/AlarmManager( 1016): waitForAlarm result :4
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1713): Vacuum at: now=1454460215128 tag=VacuumService
,I/GoogleURLConnFactory( 1713): Using platform SSLCertificateSocketFactory
,W/Uploader( 1713): No account for auth token provided
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1713): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1713): (HTTPLog)-Static: isShipBuild true
I/System.out( 1713): (HTTPLog)-Thread-199-1041347400: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1713): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1713): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,I/qtaguid ( 1713): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5424): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5424): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5424): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,W/Uploader( 1713): No account for auth token provided
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713): No account for auth token provided,
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713):  no longer exists, so no auth token.
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713): No account for auth token provided
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,E/SQLiteLog( 1713): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,E/SMD     (  290): DCD OFF
I/ServiceManager(  321): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :8,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2,
E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 8,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1016): Plugged,
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6000): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6000): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6000): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6000): Soft error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6000): Sync error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6000): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282855, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/Watchdog( 1016): !@Sync 9
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 180s ago,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
E/SMD     (  290): DCD OFF
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...,
I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15,
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed,
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/Watchdog( 1016): !@Sync 10,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged,
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 11
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  290): DCD OFF
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,W/GLSActivity( 1713): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1713): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1713): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5424): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5424): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5424): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5424): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5424): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5424): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5424): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5424): Ignoring header User-Agent because its value was null.
,I/System.out( 5424): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5424): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5424): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5424): (HTTPLog)-Thread-923-23658781: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5424): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5424): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): stay LED for fully charged
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate,
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 12
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 275s ago
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 13
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 14
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 330s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 15
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/bootchecker(  318): bootchecker wake up!!
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 16,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 390s ago
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,V/AlarmManager( 1016): No more alarm at this time.nowELAPSED=523883 batch.start=538385
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 17
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,I/ServiceManager(  321): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  321): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6000): Starting books sync for 61035162, extras: ade
D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 59166(4MB) AllocSpace objects, 164(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.898ms total 195.199ms
,I/BooksConfig( 6000): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,E/BooksAccountManager( 6000): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6000): Soft error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6000): Sync error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6000): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 538385, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 18
,I/Atfwd_Sendcmd(  321): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  321): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 455s ago
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  321): Stop the daemon....,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 19
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/Watchdog( 1016): !@Sync 20
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 21
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/Watchdog( 1016): !@Sync 22
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 23
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 600s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 24,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 25
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1016): [PWL] Off : 680s ago
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 26
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 27
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 28
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,I/PowerManagerService( 1016): [PWL] Off : 765s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 29
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1016): !@Sync 30
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/GCM     ( 1713): Message class com.google.f.a.a.i
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 31
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 855s ago,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 32
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 33,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 34
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate,
D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK,
,I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6000): Starting books sync for 61035162, extras: ade
,I/GoogleURLConnFactory( 1987): Using platform SSLCertificateSocketFactory
,I/BooksConfig( 6000): GmsCore Version = 7.8.99 (2134222-434)
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1713): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1713): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1713): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/SubscribedFeeds( 1987): Hard error
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1049761, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 1081252, reason: Periodic
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6523): MountEmulatedStorage(),
E/Zygote  ( 6523): v2
I/libpersona( 6523): KNOX_SDCARD checking this for 10100
I/libpersona( 6523): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6523 uid=10100 gids={50100, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6523): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6523): TimaSignature is unavailable
,D/ActivityThread( 6523): Added TimaKeyStore provider
D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6000): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6000): Soft error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6000): Sync error
E/BooksSync( 6000): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6000): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6000): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1049293, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/AbstractGoogleClient( 6523): Application name is not set. Call Builder#setApplicationName.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6540): MountEmulatedStorage(),
E/Zygote  ( 6540): v2
I/libpersona( 6540): KNOX_SDCARD checking this for 10037
I/libpersona( 6540): KNOX_SDCARD not a persona
I/SELinux ( 6540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6540 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6540): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6540): TimaSignature is unavailable
,D/ActivityThread( 6540): Added TimaKeyStore provider
,W/ResourcesManager( 6540): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 6540): CalendarProvider2.onCreate() called
,I/GCoreUlr( 1675): Uploading GCM registration ID for account#2#
,W/BaseAppContext( 1675): Using Auth Proxy for data requests.
,I/GLSUser ( 1675): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1675): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GCoreUlr( 1675): 
E/GCoreUlr( 1675): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1675): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1675): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1675): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1675): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1675): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1675): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1675): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1675): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1675): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1675): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1675): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1675): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1675): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1675): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1675): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1049769, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 1080643, reason: Periodic
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6565): MountEmulatedStorage()
I/libpersona( 6565): KNOX_SDCARD checking this for 10099
E/Zygote  ( 6565): v2
I/libpersona( 6565): KNOX_SDCARD not a persona
,I/SELinux ( 6565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1016): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6565 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6565): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/TimaKeyStoreProvider( 6565): TimaSignature is unavailable
,D/ActivityThread( 6565): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
,I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,E/CalendarSyncAdapter( 6523): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6523): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6523): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6523): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6523): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6523): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6523): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6523): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6523): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6523): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6523): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6523): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6523): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6523): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6523): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6523): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6523): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6523): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6523): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6523): 	... 12 more
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1049767, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 1080949, reason: Periodic
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,I/Gmail   ( 6565): getAccountsCursor
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6565): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6565): Observing account changes for notifications
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1016): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
W/Gmail   ( 6565): Sync started for account: account:61035162
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/Gmail   ( 6565): Error finding the version of the Email provider.....
E/Gmail   ( 6565): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6565): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 6565): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6565): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6565): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6565): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6565): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6565): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6565): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6565): getAccountsCursor
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/SQLiteLog( 6565): (283) recovered 119 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 66786(5MB) AllocSpace objects, 225(3MB) LOS objects, 33% free, 24MB/36MB, paused 2.828ms total 186.885ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,E/File    ( 6565): fail readDirectory() errno=2
,I/Gmail   ( 6565): notifyAccountChanged
,I/Gmail   ( 6565): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6565): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6565): notifyAccountChanged
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/Gmail   ( 6565): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6565): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1713): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1713): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1713): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
,D/ContactsSyncAdapter( 1713): innerSync failed
D/ContactsSyncAdapter( 1713): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1713): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1713): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1713): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1713): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1713): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1713): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1713): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/ContactsSyncAdapter( 1713): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1713): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
D/ContactsSyncAdapter( 1713): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1049775, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 1081506, reason: Periodic
,W/ResourcesManager( 2499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6565): getAccountsCursor
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6565): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5350, normalSync: true
,I/Gmail   ( 6565): getAccountsCursor
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6565): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6565): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6565): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6565): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6565): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a7dc3b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6565): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ReminderSync( 1987): AuthError [T SyncAdapterThread-1:id=290:priority=5:group=main]
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1049777, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 1081765, reason: Periodic
,W/GLSActivity( 1713): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1713): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1713): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
,D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2( 6540): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Zygote  ( 6611): MountEmulatedStorage(),
,E/Zygote  ( 6611): v2
I/libpersona( 6611): KNOX_SDCARD checking this for 10110
I/libpersona( 6611): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6611 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/SELinux ( 6611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6611): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     ( 1713): Explicit concurrent mark sweep GC freed 22850(1252KB) AllocSpace objects, 9(182KB) LOS objects, 39% free, 7MB/13MB, paused 1.115ms total 44.654ms
,E/Zygote  ( 6624): MountEmulatedStorage()
I/libpersona( 6624): KNOX_SDCARD checking this for 10130
E/Zygote  ( 6624): v2
I/libpersona( 6624): KNOX_SDCARD not a persona
,I/SELinux ( 6624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6624 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5666:com.samsung.helphub/1000 (adj 15): empty #31
,I/SELinux ( 6624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6624): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     (  307): Explicit concurrent mark sweep GC freed 8671(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 633us total 21.327ms
,D/TimaKeyStoreProvider( 6611): TimaSignature is unavailable
D/ActivityThread( 6611): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6624): TimaSignature is unavailable
,D/ActivityThread( 6624): Added TimaKeyStore provider,
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 16.990ms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1713): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1713): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1713): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
W/ResourcesManager( 6624): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/StatusBar( 1171): Icon Only
W/ResourcesManager( 6624): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 897us total 17.094ms
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5666/cgroup.procs: No such file or directory
,I/Gmail   ( 6565): notifyAccountChanged
,I/Gmail   ( 6565): getAccountsCursor
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6642): MountEmulatedStorage()
I/libpersona( 6642): KNOX_SDCARD checking this for 10131
E/Zygote  ( 6642): v2
I/libpersona( 6642): KNOX_SDCARD not a persona
I/SELinux ( 6642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6642 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4173:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6642): TimaSignature is unavailable
,D/ActivityThread( 6642): Added TimaKeyStore provider
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ResourcesManager( 6642): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6642): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6642): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6611): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 6611): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6611):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6611):   adb logcat -s GAv4
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6611): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_4173/cgroup.procs: No such file or directory
,I/Gmail   ( 6565): notifyAccountChanged
,D/daemonapp( 1658): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/Gmail   ( 6565): Sync complete for account: account:61035162
,W/GAv4    ( 6611): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Gmail   ( 6565): getAccountsCursor
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1049772, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6611): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 1082452, reason: Periodic
W/GAv4    ( 6611): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SMD     (  290): DCD OFF
,I/ActivityManager( 1016): Killing 5341:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6611): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6611): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager( 1016): Killing 5243:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_5341/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_5243/cgroup.procs: No such file or directory
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,W/BaseAppContext( 1987): Using Auth Proxy for data requests.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 28003(1316KB) AllocSpace objects, 5(92KB) LOS objects, 33% free, 23MB/35MB, paused 2.367ms total 151.039ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1987): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/WebViewFactory( 6611): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6611): Time to load native libraries: 2 ms (timestamps 2229-2231)
I/LibraryLoader( 6611): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6611): Binding Chromium to main looper Looper (main, tid 1) {369b22e}
,I/LibraryLoader( 6611): Expected native library version number "",actual native library version number ""
,I/chromium( 6611): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserStartupController( 6611): Initializing chromium process, singleProcess=true
,W/art     ( 6611): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6611): ApplicationContext is null in ApplicationStatus
,W/chromium( 6611): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6611): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/PicasaService( 5054): start picasa sync
E/libEGL  ( 6611): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6611): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6611): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6611): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6611): Local Branch: 
I/Adreno-EGL( 6611): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6611): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6611):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/PicasaService( 5054): end picasa sync
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.google.android.music:main for service com.google.android.music/.sync.SyncAdapterService: pid=6694 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6694): MountEmulatedStorage()
I/libpersona( 6694): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6694): v2
I/libpersona( 6694): KNOX_SDCARD not a persona
,I/SELinux ( 6694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6694): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6694): TimaSignature is unavailable
,D/ActivityThread( 6694): Added TimaKeyStore provider
,W/AudioManagerAndroid( 6611): Requires BLUETOOTH permission
,I/NSApplication( 6611): Starting up...
,I/SyncAdapterService( 6611): Ignoring sync request for non-current account
,I/MusicStore( 6694): Database version: 120
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/ActivityManager( 1016): Killing 5684:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6694): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6694): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5684/cgroup.procs: No such file or directory
,V/JNIHelp ( 6694): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/Auth.Api.Credentials( 1987): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityThread( 6694): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6694): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3876cbcb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6694): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6694): GMSCore installation verified
,I/ConfigStore( 6694): Config Database version: 1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 70
,I/MediaRouter( 6694): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 6694): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6694): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 6694): type=WIFI subType= reason=null isConnected=true
,I/MusicLifecycle( 6694): Sync started
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 6694): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6694): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6694): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1713): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1713): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1713): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1713): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1713): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
,I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLifecycle( 6694): Sync ended
,W/MusicSyncAdapter( 6694): Sync failed due to an authentication issue.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1049794, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SyncManager( 1016): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 1083510, reason: Periodic
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/File    ( 6694): fail readDirectory() errno=2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6694): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6694): Stop autocaching.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 6694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/WearableService( 4860): callingUid 10011, callindPid: 4860
,E/GmsUtils( 6694): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6694): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager( 1016): Killing 5700:com.sec.pcw.device/1000 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5700/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF,
,I/ActivityManager( 1016): Killing 5715:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10087/pid_5715/cgroup.procs: No such file or directory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6565): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6694): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6694): Stop autocaching.
,E/GmsUtils( 6694): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6694): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,I/PowerManagerService( 1016): [PWL] Off : 950s ago,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 35
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1713): Explicit concurrent mark sweep GC freed 6916(354KB) AllocSpace objects, 6(121KB) LOS objects, 39% free, 7MB/13MB, paused 990us total 51.621ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 36,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 37
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate,
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 38,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 39,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1016): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1016): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1016): Updating Usage Statistics in DB @ 1454461232040
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1016): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1016): ::isTableExists: Table exists 
,I/ApplicationUsage( 1016): Done Updating Usage Statistics in DB @ 1454461232413
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 40
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 41
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 1155s ago
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 42
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1016): !@Sync 43
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6877): 
D/AndroidRuntime( 6877): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6877): CheckJNI is OFF
D/AndroidRuntime( 6877): readGMSProperty: start
D/AndroidRuntime( 6877): readGMSProperty: already setted!!
D/AndroidRuntime( 6877): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6877): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6877): readGMSProperty: end
D/AndroidRuntime( 6877): addProductProperty: start
E/AffinityControl( 6877): AffinityControl: registerfunction enter
D/AndroidRuntime( 6877): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{771654219}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1016): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 6069:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1016): Skipping PackageSetting{1fd1bef com.example.hello/10346} due to missing metadata
W/ActivityManager( 1016): Spurious death for ProcessRecord{32128428 6069:com.test.thalitest/u0a338}, curProc for 6069: null
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3978): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 894us total 43.271ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5312): Explicit concurrent mark sweep GC freed 9908(664KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 904us total 50.063ms
W/GeofencerStateMachine( 1675): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1840): mOCRHelper is null
W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3701): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Feb 03 02:02:34 GMT+01:00 2016
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3701): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1016): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6892): MountEmulatedStorage()
E/Zygote  ( 6892): v2
I/libpersona( 6892): KNOX_SDCARD checking this for 10090
I/libpersona( 6892): KNOX_SDCARD not a persona
I/SELinux ( 6892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6892): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6892 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3701): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 6892): TimaSignature is unavailable
D/ActivityThread( 6892): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3701): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/art     ( 1016): Explicit concurrent mark sweep GC freed 51002(4MB) AllocSpace objects, 123(1973KB) LOS objects, 33% free, 24MB/36MB, paused 2.728ms total 222.041ms
I/art     ( 1016): WaitForGcToComplete blocked for 129.451ms for cause Explicit
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): PACKAGE_REMOVED
D/RegisteredServicesCache( 1451): empty dynamic service
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/Watchdog( 1016): !@Sync 44
D/elm:15121( 6892): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6892): ELMEngine.ELMEngine( context ).
D/elm:15121( 6892): MDMBridge.setEnterpriseBridge()
D/RCPManagerService( 1016): PackageReceiver onReceive()
I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3701): KLMSIntentService(): onDestroy()
I/art     ( 1016): Explicit concurrent mark sweep GC freed 10767(483KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 6.522ms total 198.789ms
I/art     ( 1016): WaitForGcToComplete blocked for 202.168ms for cause Explicit
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10338
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10338
D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
D/TaskPersister( 1016): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
D/PackageManager( 1016): delete codoeFile: 
D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10338 Target=com.test.thalitest
D/PackageManager( 1016): result of delete: 1{771654219}
D/AndroidRuntime( 6877): Shutting down VM
I/art     ( 1016): Explicit concurrent mark sweep GC freed 6099(395KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.500ms total 156.638ms
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
D/elm:15121( 6892): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6892): ElmAgentService : onCreate()
D/elm:15121( 6892): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6892): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6892): MDMBridge.getInstance()
D/elm:15121( 6892): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 6892): MDMBridge.getAllLicenseInfoFromSDK()
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6910): MountEmulatedStorage()
E/Zygote  ( 6910): v2
I/libpersona( 6910): KNOX_SDCARD checking this for 1000
I/libpersona( 6910): KNOX_SDCARD not a persona
I/SELinux ( 6910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6910 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 6910): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15121( 6892): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 6910): TimaSignature is unavailable
D/ActivityThread( 6910): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 6910): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6910): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6910): new DMDBOpenHelper instance
W/art     ( 6877): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/PCWCLIENTTRACE_PushUtil( 6910): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6910): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6910): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6910): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5865): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5865): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 5748:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/PackagesMonitor( 5054): PackagesMonitor onReceive :com.test.thalitest
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1016): failed to open /acct/uid_10148/pid_5748/cgroup.procs: No such file or directory
W/FileUtils( 5054): Failed to chmod(/data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/Mms/FreeMessageStatusReceiver( 4737): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
D/Mms/FreeMessageReceiverService( 4737): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4737): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1016): List of disabled apps :
D/Compatibility( 5782): onReceive() it will make start service
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
