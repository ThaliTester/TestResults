#### Test 58135655812b57f_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
E/SMD     (  289): DCD OFF
D/AndroidRuntime( 6047): 
D/AndroidRuntime( 6047): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6047): CheckJNI is OFF
D/AndroidRuntime( 6047): readGMSProperty: start
D/AndroidRuntime( 6047): readGMSProperty: already setted!!
D/AndroidRuntime( 6047): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6047): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6047): readGMSProperty: end
D/AndroidRuntime( 6047): addProductProperty: start
E/AffinityControl( 6047): AffinityControl: registerfunction enter
D/AndroidRuntime( 6047): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6059): MountEmulatedStorage()
I/libpersona( 6059): KNOX_SDCARD checking this for 10338
E/Zygote  ( 6059): v2
I/libpersona( 6059): KNOX_SDCARD not a persona
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
I/SELinux ( 6059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6059 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1482
D/AndroidRuntime( 6047): Shutting down VM
I/SELinux ( 6059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6059): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6059): TimaSignature is unavailable
D/ActivityThread( 6059): Added TimaKeyStore provider
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1020): Display changed displayId=0
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1482): updateVisibility : ActivityRecord{220b7161 token=android.os.BinderProxy@ae805a8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1482): onTrimMemory. Level: 20
I/WebViewFactory( 6059): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6059): Time to load native libraries: 2 ms (timestamps 4824-4826)
I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
W/art     ( 6047): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6059): Binding Chromium to main looper Looper (main, tid 1) {1e9d3b02}
,I/LibraryLoader( 6059): Expected native library version number "",actual native library version number ""
,I/chromium( 6059): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6059): Initializing chromium process, singleProcess=true
,W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6059): ApplicationContext is null in ApplicationStatus
,W/chromium( 6059): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6059): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6059): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6059): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6059): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6059): Local Branch: 
I/Adreno-EGL( 6059): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6059): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6059):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6059): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6059): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6059): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6059): CordovaWebView is running on device made by: samsung
,W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6059): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{3d725f71 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6059): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 6059): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6059): updateVisibility : ActivityRecord{170d995f token=android.os.BinderProxy@1910e5b9 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6059): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6059): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 6059
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6059): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6059): Initialized EGL, version 1.4
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6059): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6059): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +622ms (total +9s219ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{3d725f71 u0 com.test.thalitest/.MainActivity t20} time:125308
,W/IInputConnectionWrapper( 6059): showStatusIcon on inactive InputConnection
,I/Timeline( 6059): Timeline: Activity_idle id: android.os.BinderProxy@1910e5b9 time:125313,
I/SurfaceFlinger(  258): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (-2/9)
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/SamsungIME( 1812): getCurrentCandidateView
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SamsungIME( 1812): Dismiss ExpandCandiate
,I/SamsungIME( 1812): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1812): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1812): KeybaordView init() : load resources
,I/SamsungIME( 1812): getCurrentKeyboard
I/SamsungIME( 1812): getTextKeyboard
,D/SamsungIME( 1812): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/BindingManager( 6059): Cannot call determinedVisibility() - never saw a connection for the pid: 6059
,D/JsMessageQueue( 6059): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6059): JniHelper::setJavaVM(0xb86d8448), pthread_self() = -1195180328
,I/chromium( 6059): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,W/jxcore-log( 6059): Initializing JXcore engine
W/jxcore-log( 6059): JXcore engine is ready
,E/audit   ( 1870): type=1400 msg=audit(1454948686.837:205): avc:  denied  { ioctl } for  pid=6106 comm="Thread-1046" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1870):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1870): type=1300 msg=audit(1454948686.837:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d4008f8 items=0 ppid=313 ppcomm=main pid=6106 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1046" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1870): type=1320 msg=audit(1454948686.837:205): 
,W/jxcore-log( 6059): Starting JXcore engine
,W/jxcore-log( 6059): Platform android
W/jxcore-log( 6059): 
,W/jxcore-log( 6059): Process ARCH arm
W/jxcore-log( 6059): 
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/jxcore-log( 6059): JXcore Cordova bridge is ready!,
I/jxcore-log( 6059): 
W/jxcore-log( 6059): JXcore engine is started
,E/jxcore  ( 6059): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6059): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6059): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1020): Set to : 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 6059
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020): Killing 4165:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (6/8),
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1482): onRestart, Launcher: 332607356
,D/Launcher( 1482): onStart, Launcher: 332607356
,D/Launcher.HomeView( 1482): onStart
,D/Launcher( 1482): onResume, Launcher: 332607356
,D/SettingsProvider( 1020): name = kids_home_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
D/Launcher.HomeView( 1482): onResume
,D/Launcher( 1482): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1482): onResume
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1020): handle home activity for 0
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4165/cgroup.procs: No such file or directory
I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
,D/KnoxTimeoutHandler( 1020): post home show event for user 0
,D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,I/splitIntent( 1020): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/splitIntent( 1020): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,D/Launcher.HomeView( 1482): onPause
,D/Launcher( 1482): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4951): Receive : home resume
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2410): onReceive by home
,I/SurfaceFlinger(  258): id=15 createSurf (540x960),1 flag=4, Mauncher
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/Mms/UIEventReceiver( 5583): ui event
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/InputDispatcher( 1020): Focus entered window: 1482
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1482): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1020): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1482, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,V/TaskCloserActivity( 5939): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/SamsungIME( 1812): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/IInputConnectionWrapper( 6059): showStatusIcon on inactive InputConnection
,I/splitIntent( 1020): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
V/TaskCloserActivity( 5939): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,V/ActivityThread( 1482): updateVisibility : ActivityRecord{220b7161 token=android.os.BinderProxy@ae805a8 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/Launcher.HomeView( 1482): onStop
,I/Timeline( 1482): Timeline: Activity_idle id: android.os.BinderProxy@ae805a8 time:127656
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{cd1f75a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:127675
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 15s ago
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/SMD     (  289): DCD OFF
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/Watchdog( 1020): !@Sync 4
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1020): [PWL] Off : 30s ago,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5319): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5319): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5319): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4,
,I/BooksSync( 5992): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5992): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice,
,I/PhoneStatusBar( 1174): Icon Only,
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) ,
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only,
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5992): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5992): Soft error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5992): Sync error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5992): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 151793, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/PowerManagerService( 1020): [PWL] Off : 50s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,V/AlarmManager( 1020): waitForAlarm result :4
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5319): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5319): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5319): [1] 5.onFinished: Scheduling replication attempt 5.
,E/Watchdog( 1020): !@Sync 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 75s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/Watchdog( 1020): !@Sync 6,
,V/AlarmManager( 1020): waitForAlarm result :4,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 50299(2MB) AllocSpace objects, 47(756KB) LOS objects, 33% free, 24MB/36MB, paused 2.441ms total 163.423ms
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1685): Vacuum at: now=1454948759222 tag=VacuumService
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1685): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1685): No account for auth token provided
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1685): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1685): (HTTPLog)-Static: isShipBuild true
I/System.out( 1685): (HTTPLog)-Thread-192-140938193: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
,D/Finsky  ( 5319): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
D/Finsky  ( 5319): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5319): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD OFF
,I/System.out( 1685): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1685): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,I/qtaguid ( 1685): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,W/Uploader( 1685): No account for auth token provided
,I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1685): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,W/Uploader( 1685): No account for auth token provided
,I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1685): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,W/Uploader( 1685):  no longer exists, so no auth token.
,I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1685): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,W/Uploader( 1685): No account for auth token provided
,I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1685): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,V/AlarmManager( 1020): waitForAlarm result :8
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
E/Uploader( 1685): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1685): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1685): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1685): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1685): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1685): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1685): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1685, getuid(): 10011
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1020): stay LED for fully charged
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 105s ago
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 290,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/Watchdog( 1020): !@Sync 7
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,E/SMD     (  289): DCD OFF
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5992): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5992): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5992): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5992): Soft error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5992): Sync error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5992): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 274408, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1020): stay LED for fully charged
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1020): !@Sync 9
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1020): [PWL] Off : 180s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1020): initializing...
,I/TLC_TIMA_PKM_initialize( 1020): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1020): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1020): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1020): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1020): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1020): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 10
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/BatteryService( 1020): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1020): [PWL] Off : 225s ago,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 11
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2,
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:461)
D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5319): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5319): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5319): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5319): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5319): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5319): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5319): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5319): Ignoring header User-Agent because its value was null.
,I/System.out( 5319): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5319): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5319): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5319): (HTTPLog)-Thread-898-610372733: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5319): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5319): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 12
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 275s ago,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1020): !@Sync 13
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/Watchdog( 1020): !@Sync 14
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 330s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 15
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/bootchecker(  322): bootchecker wake up!!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 16
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
V/AlarmManager( 1020): No more alarm at this time.nowELAPSED=500073 batch.start=519556
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1020): [PWL] Off : 390s ago,
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5992): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 5992): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5992): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5992): Soft error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5992): Sync error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5992): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 519556, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 17
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,I/ServiceManager(  325): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  325): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 18
,I/Atfwd_Sendcmd(  325): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  325): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 455s ago
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/Atfwd_Daemon(  325): Stop the daemon....,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 19
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 20
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 525s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 21
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 22
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 23
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 600s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 24
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 25
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 680s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 26
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 27
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 28
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/PowerManagerService( 1020): [PWL] Off : 765s ago,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 29
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1020): !@Sync 30
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/GCM     ( 1685): Message class com.google.f.a.a.i
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2041): Aggregate from 1454947353484 (log), 1454947353484 (data)
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 31,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1020): [PWL] Off : 855s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 32
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 33
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,V/AlarmManager( 1020): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5992): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5992): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5992): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5992): Soft error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5992): Sync error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5992): Finished books sync
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1009438, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  289): DCD OFF,
,E/SQLiteLog( 1685): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/BatteryService( 1020): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 34,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 950s ago
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 35,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 36
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 37
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 38
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1050s ago
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 39
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1020): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1020): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1020): Updating Usage Statistics in DB @ 1454949775780
,I/ApplicationPolicy( 1020): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1020): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1020): ::isTableExists: Table exists 
,I/ApplicationUsage( 1020): Done Updating Usage Statistics in DB @ 1454949776146
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 40
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 41
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 1155s ago,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1020): !@Sync 42
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1020): !@Sync 43
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6626): 
D/AndroidRuntime( 6626): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6626): CheckJNI is OFF
D/AndroidRuntime( 6626): readGMSProperty: start
D/AndroidRuntime( 6626): readGMSProperty: already setted!!
D/AndroidRuntime( 6626): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6626): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6626): readGMSProperty: end
D/AndroidRuntime( 6626): addProductProperty: start
E/AffinityControl( 6626): AffinityControl: registerfunction enter
D/AndroidRuntime( 6626): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1020): START PACKAGE DELETE: observer{493968118}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): !@killApplicatoin: 10338, uninstall pkg
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 6059:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1020): Skipping PackageSetting{fb5c44f com.example.hello/10346} due to missing metadata
D/PersonaManager( 1020): isKioskContainerExistOnDevice
W/ActivityManager( 1020): Spurious death for ProcessRecord{233edef7 6059:com.test.thalitest/u0a338}, curProc for 6059: null
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4035): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 830us total 26.867ms
E/SamsungIME( 1812): mOCRHelper is null
I/art     ( 5902): Explicit concurrent mark sweep GC freed 42(13KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 697us total 41.691ms
W/GeofencerStateMachine( 1828): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3688): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Feb 08 17:44:55 GMT+01:00 2016
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3688): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): onCreate()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3688): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/Zygote  ( 6639): MountEmulatedStorage()
I/libpersona( 6639): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6639): v2
I/libpersona( 6639): KNOX_SDCARD not a persona
I/SELinux ( 6639): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3688): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/SELinux ( 6639): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6639): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6639 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): listeningToPackageRemoved().START
D/TimaKeyStoreProvider( 6639): TimaSignature is unavailable
D/ActivityThread( 6639): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
D/RegisteredServicesCache( 1443): empty dynamic service
D/elm:15121( 6639): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6639): ELMEngine.ELMEngine( context ).
D/elm:15121( 6639): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6639): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6639): ElmAgentService : onCreate()
D/elm:15121( 6639): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6639): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6639): MDMBridge.getInstance()
D/elm:15121( 6639): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6639): MDMBridge.getAllLicenseInfoFromSDK()
I/art     ( 1020): Explicit concurrent mark sweep GC freed 44050(4MB) AllocSpace objects, 149(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.912ms total 265.082ms
I/art     ( 1020): WaitForGcToComplete blocked for 219.788ms for cause Explicit
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 6639): ElmAgentService : onDestroy().
I/KLMS-2.5.123: ( 3688): KLMSIntentService(): onDestroy()
D/RCPManagerService( 1020): PackageReceiver onReceive()
I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1020): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5624): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5624): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5719): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5719): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4951): PackagesMonitor onReceive :com.test.thalitest
I/art     ( 1020): Explicit concurrent mark sweep GC freed 14029(740KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.097ms total 181.500ms
D/Mms/FreeMessageStatusReceiver( 5583): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1020): enable value -1
I/TactileAssist( 1020): internal enable value -1
I/TactileAssist( 1020): intensity value -1
I/TactileAssist( 1020): saveAppList value true
I/TactileAssist( 1020): List of disabled apps :
D/Mms/FreeMessageReceiverService( 5583): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5583): onHandleIntent: ACTION_PACKAGE_REMOVED
D/PackageManager( 1020): delete codoeFile: 
D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1020): UID=10338 Target=com.test.thalitest
D/PackageManager( 1020): result of delete: 1{493968118}
D/AndroidRuntime( 6626): Shutting down VM
D/Compatibility( 5823): onReceive() it will make start service
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5823): onHandleIntent()
D/Compatibility( 5823): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5823): found: 2
D/Compatibility( 5823): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5823): skipping ResolveInfo{1d28054e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5823): considering ResolveInfo{3fc366f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5823): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5823): enabling receiver ResolveInfo{13d32f7c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
E/Zygote  ( 6659): MountEmulatedStorage()
E/Zygote  ( 6659): v2
I/libpersona( 6659): KNOX_SDCARD checking this for 10055
I/libpersona( 6659): KNOX_SDCARD not a persona
I/SELinux ( 6659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/Compatibility( 5823): enabling receiver ResolveInfo{3f4b3005 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
E/SELinux ( 6659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6659 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/Compatibility( 5823): enabling receiver ResolveInfo{483285a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5823): enabling receiver ResolveInfo{31bfca8b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5823): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6659): TimaSignature is unavailable
D/ActivityThread( 6659): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6659): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6659): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6659): SecurePlaceDbHelper() 
D/UserAnalysis( 6659): Create SecureDbHelper
D/IntelligenceServiceApplication( 6659): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6659): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5841): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 6659): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6678): MountEmulatedStorage()
E/Zygote  ( 6678): v2
I/libpersona( 6678): KNOX_SDCARD checking this for 1000
I/libpersona( 6678): KNOX_SDCARD not a persona
I/SELinux ( 6678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6678): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5146:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
D/TimaKeyStoreProvider( 6678): TimaSignature is unavailable
D/ActivityThread( 6678): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
W/ResourcesManager( 6678): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/art     ( 6626): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/BluetoothAdapter( 6659): cancelDiscovery
D/BluetoothAdapterProperties( 2632): mDiscovering is false
E/BluetoothAdapterService( 2632): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6659): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6659): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6659): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/RCPManager( 6678):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1020):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1020): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5862): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 5862): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/FilterInstaller( 5862): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5862): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5862): before removeFromFS
D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6695 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6695): MountEmulatedStorage()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6695): v2
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6695): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/libpersona( 6695): KNOX_SDCARD checking this for 1000
I/libpersona( 6695): KNOX_SDCARD not a persona
I/SELinux ( 6695): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 6695): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 6659): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6659): (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
E/Zygote  ( 6710): MountEmulatedStorage()
E/Zygote  ( 6710): v2
I/libpersona( 6710): KNOX_SDCARD checking this for 10095
I/libpersona( 6710): KNOX_SDCARD not a persona
I/SELinux ( 6710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/SQLiteDatabase( 6659): Error inserting timestamp=1454949896411 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 6659): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6659): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6659): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6659): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6659): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6659): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6659): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6659): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 6659): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 6659): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6659): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6659): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6659): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6659): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6659): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6659): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6659): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 6659): It failed to insert to dump_log table
I/SELinux ( 6710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6710 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6695): TimaSignature is unavailable
D/ActivityThread( 6695): Added TimaKeyStore provider
I/art     (  313): Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 22.370ms
D/TimaKeyStoreProvider( 6710): TimaSignature is unavailable
D/ActivityThread( 6710): Added TimaKeyStore provider
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.966ms
W/ContextImpl( 6695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 16.869ms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PreloadFilterInstaller( 6710): uses FILTER_DB_VER_1
E/SQLiteLog( 6710): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 6695): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6710): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6710): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6710): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6710): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6710): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6710): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6710): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6710): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6710): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6710): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6710): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6710): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6710): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6710): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6710): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6710): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6710): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6710): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6710): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6710): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6710): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6710): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6710): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteDatabase( 6695): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6695): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6695): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6695): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 6710): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6710): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6710): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6710): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6710): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6710): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6710): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6710): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6710): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6710): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6710): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6710): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6710): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6710): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6710): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6710): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6710): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6710): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6710): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6710): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6710): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6710): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6710): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 6695): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6695): Process: com.android.keychain, PID: 6695
E/AndroidRuntime( 6695): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6695): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6695): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6695): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6695): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6695): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 6695): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6695): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6695): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6695): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 6710): Opened filter.db in read-only mode
E/Zygote  ( 6727): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6727 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6727): v2
E/SQLiteLog( 6710): (284) automatic index on titles(filter_id)
I/libpersona( 6727): KNOX_SDCARD checking this for 1000
I/libpersona( 6727): KNOX_SDCARD not a persona
I/SELinux ( 6727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
