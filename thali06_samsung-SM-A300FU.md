#### Test 52383621d5a0cb8_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,--------- beginning of main
D/AndroidRuntime( 6174): 
D/AndroidRuntime( 6174): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6174): CheckJNI is OFF
D/AndroidRuntime( 6174): readGMSProperty: start
D/AndroidRuntime( 6174): readGMSProperty: already setted!!
D/AndroidRuntime( 6174): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6174): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6174): readGMSProperty: end
D/AndroidRuntime( 6174): addProductProperty: start
E/AffinityControl( 6174): AffinityControl: registerfunction enter
D/AndroidRuntime( 6174): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6186 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1481
E/Zygote  ( 6186): MountEmulatedStorage()
E/Zygote  ( 6186): v2
I/libpersona( 6186): KNOX_SDCARD checking this for 10338
I/libpersona( 6186): KNOX_SDCARD not a persona
D/AndroidRuntime( 6174): Shutting down VM
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6186): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
E/SMD     (  296): DCD OFF
D/TimaKeyStoreProvider( 6186): TimaSignature is unavailable
D/ActivityThread( 6186): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
D/Launcher( 1481): onTrimMemory. Level: 20
V/ActivityThread( 1481): updateVisibility : ActivityRecord{39d98330 token=android.os.BinderProxy@95932f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/WebViewFactory( 6186): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6186): Time to load native libraries: 1 ms (timestamps 7454-7455)
I/LibraryLoader( 6186): Expected native library version number "",actual native library version number ""
W/art     ( 6174): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6186): Binding Chromium to main looper Looper (main, tid 1) {19d14d91}
I/LibraryLoader( 6186): Expected native library version number "",actual native library version number ""
I/chromium( 6186): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6186): Initializing chromium process, singleProcess=true
W/art     ( 6186): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6186): ApplicationContext is null in ApplicationStatus
W/chromium( 6186): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6186): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6186): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6186): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6186): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6186): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6186): Local Branch: 
I/Adreno-EGL( 6186): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6186): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6186):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/SSRM:n  ( 1019): SIOP:: AP = 260
W/art     ( 6186): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6186): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6186): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6186): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6186): CordovaWebView is running on device made by: samsung
W/art     ( 6186): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6186): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{284e4116 u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6186): Render dirty regions requested: true
D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
W/chromium( 6186): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6186): updateVisibility : ActivityRecord{373e832 token=android.os.BinderProxy@1cae8594 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6186): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6186): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1019): Focus entered window: 6186
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6186): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6186): Initialized EGL, version 1.4
D/OpenGLRenderer( 6186): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6186): Enabling debug mode 0
D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1175): Icon Only
I/Timeline( 6186): Timeline: Activity_idle id: android.os.BinderProxy@1cae8594 time:158002
D/PanelView( 1175): There is/are notification(s) 
W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 6186): showStatusIcon on inactive InputConnection
I/ActivityManager( 1019): Displayed Component not be shown by security: +695ms (total +40s454ms)
W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{284e4116 u0 com.test.thalitest/.MainActivity t20} time:158018
I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1795): getCurrentCandidateView
W/BindingManager( 6186): Cannot call determinedVisibility() - never saw a connection for the pid: 6186
D/SamsungIME( 1795): Dismiss ExpandCandiate
I/SamsungIME( 1795): getDebugLevel  : 0x4f4c
I/SamsungIME( 1795): getDebugLevel  : 0x4f4c
I/SamsungIME( 1795): KeybaordView init() : load resources
D/JsMessageQueue( 6186): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1795): getCurrentKeyboard
I/SamsungIME( 1795): getTextKeyboard
I/ServiceManager(  337): Waiting for service AtCmdFwd...
D/SamsungIME( 1795): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6186): JniHelper::setJavaVM(0xb7a1a448), pthread_self() = -1208545072
D/JX-Cordova( 6186): jxcore cordova android initializing
I/ServiceManager(  337): Waiting for service AtCmdFwd...
,W/jxcore-log( 6186): Initializing JXcore engine
W/jxcore-log( 6186): JXcore engine is ready
,W/jxcore-log( 6186): Starting JXcore engine
,E/audit   ( 1850): type=1400 msg=audit(1449056514.345:205): avc:  denied  { ioctl } for  pid=6186 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1850):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1850): type=1300 msg=audit(1449056514.345:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be862d58 items=0 ppid=323 ppcomm=main pid=6186 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1850): type=1320 msg=audit(1449056514.345:205): 
,W/jxcore-log( 6186): Platform android,
W/jxcore-log( 6186): 
W/jxcore-log( 6186): Process ARCH arm
W/jxcore-log( 6186): 
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/jxcore-log( 6186): JXcore Cordova bridge is ready!
I/jxcore-log( 6186): 
,W/jxcore-log( 6186): JXcore engine is started
,I/chromium( 6186): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 6186): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 6186): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 6186): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1019): Set to : 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1019): Focused application set to: xxxx
,D/InputDispatcher( 1019): Focus left window: 6186
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1019): Killing 5170:com.google.android.talk/u0a102 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8),
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1019): mDVFSHelper.acquire()
,V/WindowManager( 1019): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1481): onRestart, Launcher: 732681619
,D/Launcher( 1481): onStart, Launcher: 732681619
,D/Launcher.HomeView( 1481): onStart
D/Launcher( 1481): onResume, Launcher: 732681619
,D/SettingsProvider( 1019): name = kids_home_mode
,D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
,D/SettingsProvider( 1019): selectionArgs: 10006
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
D/Launcher.HomeView( 1481): onResume
,D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/MenuAppsGridFragment( 1481): onResume
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1481): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1019): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1019): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,D/GalleryCacheReady( 5023): Receive : home resume
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/Recents_RecreateReceiver( 2530): onReceive by home
,D/ActivityManager( 1019): handle home activity for 0
,I/WallpaperManagerService( 1019): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1019): post home show event for user 0
,D/WallpaperManagerService( 1019):  force update = false; persona id = 0; current user =0; current persona = 0
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/Launcher.HomeView( 1481): onPause
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/TaskCloserActivity( 5684): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,E/Zygote  ( 6238): MountEmulatedStorage()
I/libpersona( 6238): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6238): v2
I/libpersona( 6238): KNOX_SDCARD not a persona
,I/SELinux ( 6238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6238 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 6238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1019): failed to open /acct/uid_10102/pid_5170/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,I/SurfaceFlinger(  259): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/Mms/UIEventReceiver( 5719): ui event
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/BroadcastQueue( 1019): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/InputDispatcher( 1019): Focus entered window: 1481
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1481): log_dcs ThreadedRenderer::initialize entered! 
D/TimaKeyStoreProvider( 6238): TimaSignature is unavailable
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/ActivityThread( 6238): Added TimaKeyStore provider
,V/ActivityThread( 1481): updateVisibility : ActivityRecord{39d98330 token=android.os.BinderProxy@95932f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1481): onStop
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6186): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1795): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ResourcesManager( 6238): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6238): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6238): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6238): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,I/Timeline( 1481): Timeline: Activity_idle id: android.os.BinderProxy@95932f time:160825
,I/splitIntent( 1019): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1019): Killing 4157:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{8f87ccd u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:160849
,V/TaskCloserActivity( 5684): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1019): isKioskContainerExistOnDevice
,D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4157/cgroup.procs: No such file or directory
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,E/Watchdog( 1019): !@Sync 5
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5421): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5421): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5421): [1] 5.onFinished: Scheduling replication attempt 5.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  296): DCD OFF
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5421): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5421): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5421): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 6
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1714): Vacuum at: now=1449056558737 tag=VacuumService
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,W/Uploader( 1714): No account for auth token provided
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1714): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1714): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1714): (HTTPLog)-Thread-204-529854384: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1714): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,I/qtaguid ( 1714): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714):  no longer exists, so no auth token.
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1714): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1714): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,E/Uploader( 1714): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1714): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 39757(2MB) AllocSpace objects, 28(461KB) LOS objects, 33% free, 23MB/35MB, paused 3.014ms total 178.718ms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/SMD     (  296): DCD OFF
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/Uploader( 1714): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1714): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/qtaguid ( 1714): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/Atfwd_Sendcmd(  337): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  337): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,V/AlarmManager( 1019): waitForAlarm result :8
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1175): HomeTimezone(): 1
D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6102): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6102): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6102): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6102): Soft error
E/BooksSync( 6102): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6102): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6102): Sync error
E/BooksSync( 6102): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6102): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6102): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284905, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 9
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15,
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 10
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/Atfwd_Sendcmd(  337): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  337): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/Watchdog( 1019): !@Sync 11
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5421): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5421): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5421): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5421): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5421): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5421): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5421): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5421): Ignoring header User-Agent because its value was null.
,I/System.out( 5421): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5421): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5421): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5421): (HTTPLog)-Thread-908-346879912: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5421): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 5421): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 12
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 330s ago
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 13
,I/ServiceManager(  337): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 14,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  337): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  337): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 390s ago
,E/Watchdog( 1019): !@Sync 15,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/bootchecker(  333): bootchecker wake up!!,
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 16
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
V/AlarmManager( 1019): No more alarm at this time.nowELAPSED=525350 batch.start=544229
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 17
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,I/ServiceManager(  337): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  337): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6102): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6102): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6102): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6102): Soft error
E/BooksSync( 6102): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6102): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6102): Sync error
E/BooksSync( 6102): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6102): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6102): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 544229, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  296): DCD OFF
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 18,
,I/Atfwd_Sendcmd(  337): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  337): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,I/Atfwd_Daemon(  337): Stop the daemon....,
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8,
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 19,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 525s ago
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 20
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 21,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 600s ago
,E/Watchdog( 1019): !@Sync 22,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 23,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 24,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 25
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 26
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 27
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 765s ago
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 28
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 29
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1019): !@Sync 30
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 855s ago
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  296): DCD OFF
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2059): Aggregate from 1449055049840 (log), 1449055049840 (data)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/GCM     ( 1714): Message class com.google.f.a.a.i
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 2059): Message from null null
E/GCM     ( 2059): Dropping message from null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 31
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 32
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 33
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 950s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 34
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6102): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6102): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6102): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6102): Soft error
E/BooksSync( 6102): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6102): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6102): Sync error
E/BooksSync( 6102): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6102): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6102): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1062593, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 35
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 36
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1050s ago
,E/Watchdog( 1019): !@Sync 37
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 38,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 39
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
,I/UsageStatsService( 1019): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1019): handleMessage : MSG_UPDATE_USAGE_DB
I/ApplicationUsage( 1019): Updating Usage Statistics in DB @ 1449057570363
I/ApplicationPolicy( 1019): updateDataUsageMap
,I/NetworkDataUsageDb( 1019): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1019): ::isTableExists: Table exists 
,I/ApplicationUsage( 1019): Done Updating Usage Statistics in DB @ 1449057570748
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 40
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1155s ago,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 41
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 42
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 43
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 44
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 1266s ago
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 45
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 46
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 47
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF,
,I/PowerManagerService( 1019): [PWL] Off : 1381s ago
,E/Watchdog( 1019): !@Sync 48
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 49,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,E/SMD     (  296): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1019): !@Sync 50
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 51
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 1501s ago
,E/Watchdog( 1019): !@Sync 52
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 53
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 54
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 55
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 56
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 1626s ago
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 57
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 58
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/Watchdog( 1019): !@Sync 59
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 60
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2626): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2626): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1175): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1175): level :100 plugged : 2
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/PowerManagerService( 1019): [PWL] Off : 1756s ago
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,I/ActivityManager( 1019): Killing 5248:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
I/ActivityManager( 1019): Killing 1602:com.sec.android.widgetapp.ap.hero.accuweather/u0a62 (adj 15): SPC_empty #32
,I/ActivityManager( 1019): Killing 1630:com.sec.android.daemonapp/u0a157 (adj 15): SPC_empty #33
,I/ActivityManager( 1019): Killing 2679:com.sec.phone/1001 (adj 15): SPC_empty #34
I/ActivityManager( 1019): Killing 3882:com.sec.bcservice/1000 (adj 15): SPC_empty #35
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
I/ActivityManager( 1019): Killing 3316:com.sec.android.pagebuddynotisvc/u0a113 (adj 15): SPC_empty #36
,I/ActivityManager( 1019): Killing 2928:com.samsung.android.providers.context/u0a2 (adj 15): SPC_empty #37
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1,
,V/NetworkStats( 1019): performPollLocked(flags=0x3)
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked() took 17ms
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,I/ProcessStatsService( 1019): Prepared write state in 22ms
,I/ProcessStatsService( 1019): Prepared write state in 16ms
,I/ProcessStatsService( 1019): Prepared write state in 7ms
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 1000ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService in 10983ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20980ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.phone/.SecPhoneService in 30976ms
,D/GpsStatusListenerHelper( 1019): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@213b8b78
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): Scheduling restart of crashed service com.samsung.android.providers.context/.ContextService in 3611500ms
,W/ActivityManager( 1019): Scheduling restart of crashed service com.sec.bcservice/.BroadcastService in 30959ms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1175): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/BroadcastQueue( 1019): Skipping deliver [foreground] BroadcastRecord{2a59e724 u-1 android.intent.action.TIME_TICK} to ReceiverList{ba65a6e 1630 com.sec.android.daemonapp/10157/u0 remote:279a4de9}: filter unregistered
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-01-15-20-42.bin
,W/libprocessgroup( 1019): failed to open /acct/uid_10113/pid_3316/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_5248/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10062/pid_1602/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10157/pid_1630/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1001/pid_2679/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_10002/pid_2928/cgroup.procs: No such file or directory
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_3882/cgroup.procs: No such file or directory
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1714): Message class com.google.f.a.a.i
,E/SMD     (  296): DCD OFF
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6968): MountEmulatedStorage()
I/libpersona( 6968): KNOX_SDCARD checking this for 10113
E/Zygote  ( 6968): v2
I/libpersona( 6968): KNOX_SDCARD not a persona
I/SELinux ( 6968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.pagebuddynotisvc for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc: pid=6968 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/SELinux ( 6968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6968): TimaSignature is unavailable
,D/ActivityThread( 6968): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 6968): onCreate mCpBitFlag=0
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :8
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF
,E/Watchdog( 1019): !@Sync 61,
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6988): MountEmulatedStorage(),
I/libpersona( 6988): KNOX_SDCARD checking this for 10062
E/Zygote  ( 6988): v2
I/libpersona( 6988): KNOX_SDCARD not a persona
,I/SELinux ( 6988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.widgetapp.ap.hero.accuweather for service com.sec.android.widgetapp.ap.hero.accuweather/.WeatherClockScreenService: pid=6988 uid=10062 gids={50062, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 6988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6988): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  323): Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 698us total 35.492ms
,D/TimaKeyStoreProvider( 6988): TimaSignature is unavailable
D/ActivityThread( 6988): Added TimaKeyStore provider,
,I/ActivityManager( 1019): Killing 1694:com.samsung.hs20settings/1000 (adj 15): SPC_empty #31
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 676us total 19.889ms
,W/ResourcesManager( 6988): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6988): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6988): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 706us total 20.063ms
,D/comsamsunglog( 6988): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6988): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 1504301788142] [ 1 ] 
,D/comsamsunglog( 6988): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port A3 qHD
D/comsamsunglog( 6988): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6988): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 6988): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 1504301788142] [ 1 ] 
D/comsamsunglog( 6988): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port A3 qHD
D/comsamsunglog( 6988): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider( 1019): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider( 1019): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1019): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1019): selectionArgs: false
D/SettingsProvider( 1019): selectionArgs: 10062
D/SecContentProvider( 1019): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1019): ret = -1
,W/BackupManagerService( 1019): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,W/ActivityManager( 1019): Scheduling restart of crashed service com.samsung.hs20settings/.WifiHs20UtilityService in 29827ms
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,E/Zygote  ( 7005): MountEmulatedStorage(),
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_1694/cgroup.procs: No such file or directory
E/Zygote  ( 7005): v2
I/libpersona( 7005): KNOX_SDCARD checking this for 10157
I/libpersona( 7005): KNOX_SDCARD not a persona
,I/SELinux ( 7005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.android.daemonapp for content provider com.sec.android.daemonapp/.ap.common.WeatherContentProvider: pid=7005 uid=10157 gids={50157, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
I/SELinux ( 7005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 7005): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7005): TimaSignature is unavailable
,D/ActivityThread( 7005): Added TimaKeyStore provider
,W/ResourcesManager( 7005): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/comsamsungapp( 7005): [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 7005): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
D/comsamsungapp( 7005): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 7005): [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,D/comsamsungapp( 7005): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCP:1122 [0:0] Provider Created
,D/comsamsungapp( 7005): [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/comsamsungapp( 7005): [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCS:65 [0:0] selLocation : null
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/comsamsungapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 7005): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 7005): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 7005): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 7005): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 7005): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 7005): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 7005): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 7005): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.daemonapp, destAppInfo.processName = com.sec.android.daemonapp
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 7005): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 7005): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 7005): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:456 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 7005): [MSC_Daemon]>>> WU:1381 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 7005): [MSC_Daemon]>>> WU:1401 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:460 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:464 [0:0] selLocation : null
,D/daemonapp( 7005): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 7005): [MSC_Daemon]>>> WDSM:490 [0:0] today==null
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7029): MountEmulatedStorage()
I/libpersona( 7029): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7029): v2
I/libpersona( 7029): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.sec.bcservice for service com.sec.bcservice/.BroadcastService: pid=7029 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 7029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 7029): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7029): TimaSignature is unavailable
,D/ActivityThread( 7029): Added TimaKeyStore provider
,W/ResourcesManager( 7029): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/F_PHONE ( 7029): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 7029): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7044): MountEmulatedStorage(),
I/ActivityManager( 1019): Start proc com.sec.phone for service com.sec.phone/.SecPhoneService: pid=7044 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1035, 1023, 3006} abi=armeabi-v7a
E/Zygote  ( 7044): v2
I/libpersona( 7044): KNOX_SDCARD checking this for 1001
,I/libpersona( 7044): KNOX_SDCARD not a persona
,I/SELinux ( 7044): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 7044): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 7044): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7044): TimaSignature is unavailable
,D/ActivityThread( 7044): Added TimaKeyStore provider
,W/ResourcesManager( 7044): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/F_PHONE ( 7029): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 7029): default registerAction()
I/F_PHONE ( 7029): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 62
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7065): MountEmulatedStorage(),
E/Zygote  ( 7065): v2
I/libpersona( 7065): KNOX_SDCARD checking this for 1000
I/libpersona( 7065): KNOX_SDCARD not a persona
I/SELinux ( 7065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.samsung.hs20settings for service com.samsung.hs20settings/.WifiHs20UtilityService: pid=7065 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 7065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7065): TimaSignature is unavailable
,D/ActivityThread( 7065): Added TimaKeyStore provider
,I/Hs20UtilService( 7065): onCreate
,I/Hs20UtilService( 7065): Starting #8
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 63
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 64,
,E/SMD     (  296): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  296): DCD OFF,
,E/SMD     (  296): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 260,
,E/SMD     (  296): DCD OFF
,E/SMD     (  296): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1019): [PWL] Off : 1891s ago
,E/Watchdog( 1019): !@Sync 65
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7120): 
D/AndroidRuntime( 7120): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7120): CheckJNI is OFF
D/AndroidRuntime( 7120): readGMSProperty: start
D/AndroidRuntime( 7120): readGMSProperty: already setted!!
D/AndroidRuntime( 7120): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7120): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7120): readGMSProperty: end
D/AndroidRuntime( 7120): addProductProperty: start
E/AffinityControl( 7120): AffinityControl: registerfunction enter
D/AndroidRuntime( 7120): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{916593969}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): !@killApplicatoin: 10338, uninstall pkg
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 6186:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1019): Skipping PackageSetting{1cc97256 com.example.hello/10345} due to missing metadata
I/ActivityManager( 1019): Killing 6027:com.google.android.apps.plus/u0a117 (adj 15): empty for 1886s
I/ActivityManager( 1019): Killing 6000:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1886s
I/ActivityManager( 1019): Killing 5981:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1886s
I/ActivityManager( 1019): Killing 5960:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5941:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5924:com.wsomacp/u0a23 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5857:com.osp.app.signin/u0a36 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5909:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5890:com.sec.android.app.myfiles/u0a42 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 3457:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5840:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5816:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty for 1887s
I/ActivityManager( 1019): Killing 5799:com.policydm/1000 (adj 15): empty for 1888s
I/ActivityManager( 1019): Killing 5351:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty for 1888s
I/ActivityManager( 1019): Killing 5768:com.sec.pcw.device/1000 (adj 15): empty for 1888s
I/ActivityManager( 1019): Killing 5753:com.google.android.apps.docs/u0a87 (adj 15): empty for 1888s
I/ActivityManager( 1019): Killing 5726:com.samsung.helphub/1000 (adj 15): empty for 1888s
I/ActivityManager( 1019): Killing 5335:com.google.android.partnersetup/u0a14 (adj 15): empty for 1888s
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
I/art     ( 4033): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.032ms total 26.073ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1835): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 02 13:12:04 GMT+01:00 2015
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/art     ( 6057): Explicit concurrent mark sweep GC freed 432(29KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 730us total 77.516ms
I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1795): mOCRHelper is null
E/libprocessgroup( 1019): failed to kill 1 processes for processgroup 6186
D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onCreate()
E/Zygote  ( 7134): MountEmulatedStorage()
I/libpersona( 7134): KNOX_SDCARD checking this for 10090
I/KLMS-2.5.123: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/libpersona( 7134): KNOX_SDCARD not a persona
E/Zygote  ( 7134): v2
I/SELinux ( 7134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7134): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7134 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 7134): TimaSignature is unavailable
D/ActivityThread( 7134): Added TimaKeyStore provider
I/art     ( 1019): Explicit concurrent mark sweep GC freed 35236(2MB) AllocSpace objects, 61(1029KB) LOS objects, 33% free, 23MB/35MB, paused 2.820ms total 194.077ms
I/art     ( 1019): WaitForGcToComplete blocked for 155.306ms for cause Explicit
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): PACKAGE_REMOVED
D/RegisteredServicesCache( 1434): empty dynamic service
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/SMD     (  296): DCD OFF
D/RCPManagerService( 1019): PackageReceiver onReceive()
D/elm:15121( 7134): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:15121( 7134): ELMEngine.ELMEngine( context ).
D/elm:15121( 7134): MDMBridge.setEnterpriseBridge()
D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): listeningToPackageRemoved().END
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 7134): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 7134): ElmAgentService : onCreate()
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onDestroy()
D/elm:15121( 7134): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7134): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7134): MDMBridge.getInstance()
D/elm:15121( 7134): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7134): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7134): ElmAgentService : onDestroy().
I/ActivityManager( 1019): Killing 6057:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1886s
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
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10338
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1019): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/art     ( 1019): Explicit concurrent mark sweep GC freed 11071(608KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 4.340ms total 216.392ms
I/libpersona( 7151): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7151): MountEmulatedStorage()
I/libpersona( 7151): KNOX_SDCARD not a persona
E/Zygote  ( 7151): v2
I/SELinux ( 7151): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7151 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7151): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7151): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7151): TimaSignature is unavailable
D/ActivityThread( 7151): Added TimaKeyStore provider
D/PackageManager( 1019): delete codoeFile: 
D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10338 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{916593969}
D/AndroidRuntime( 7120): Shutting down VM
I/PCWCLIENTTRACE_LOG( 7151): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7151): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7151): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7151): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7151): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7151): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7151): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7166): MountEmulatedStorage()
E/Zygote  ( 7166): v2
I/libpersona( 7166): KNOX_SDCARD checking this for 10029
I/libpersona( 7166): KNOX_SDCARD not a persona
I/SELinux ( 7166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7166 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 6073:com.sec.android.app.samsungapps/u0a9 (adj 15): empty for 1886s
I/SELinux ( 7166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7166): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7166): TimaSignature is unavailable
D/ActivityThread( 7166): Added TimaKeyStore provider
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/FeatureConfig( 7166): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/Zygote  ( 7183): MountEmulatedStorage()
I/libpersona( 7183): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7183): v2
I/libpersona( 7183): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7183 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Killing 5656:com.android.defcontainer/u0a3 (adj 15): empty for 1877s
I/SELinux ( 7183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7183): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7166): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7183): TimaSignature is unavailable
D/ActivityThread( 7183): Added TimaKeyStore provider
W/ResourcesManager( 7166): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7183): [SSP] onCreated
W/ResourcesManager( 7166): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7183): [TPM] There is no property file
I/SA      ( 7183): [SCU] isHaveSA() - false
I/SA      ( 7183): [TPM] getModelProperty : null
I/SA      ( 7183): [TPM] getCSCProperty : null
W/ResourcesManager( 7166): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/SA      ( 7183): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7183): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7183): [DM] TFT FEATURE: false
I/SA      ( 7183): [DM] init START
W/art     ( 7120): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/SA      ( 7183): [DM] This device is not a Vodafone
W/ResourcesManager( 7166): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourceType( 7183): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourcesManager( 7166): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourceType( 7183): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7183): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7183): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourcesManager( 7166): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourceType( 7183): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7183): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 7183): [SCU] isHaveSA() - false
I/SA      ( 7183): support phone number id : false
I/SA      ( 7183): [DM] Supports Ref Jpn : true
I/SA      ( 7183): [DM] init END
I/SA      ( 7183): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
W/GalaxyFinderApplication( 7166): system/finder_cp/cpdata.xml file not found
I/SA      ( 7183): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1019): Killing 5023:com.sec.android.gallery3d/u0a39 (adj 15): empty for 1810s
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1019): Exception when sending broadcast to ComponentInfo{com.sec.android.gallery3d/com.sec.android.gallery3d.app.PackagesMonitor}
W/BroadcastQueue( 1019): android.os.TransactionTooLargeException
W/BroadcastQueue( 1019): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1019): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1019): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1019): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1019): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1019): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1019): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7204): MountEmulatedStorage()
E/Zygote  ( 7204): v2
I/libpersona( 7204): KNOX_SDCARD checking this for 10039
I/libpersona( 7204): KNOX_SDCARD not a persona
I/SELinux ( 7204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7204 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 7204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1019): Spurious death for ProcessRecord{1c0f1247 7204:com.sec.android.gallery3d/u0a39}, curProc for 5023: null
D/TimaKeyStoreProvider( 7204): TimaSignature is unavailable
D/ActivityThread( 7204): Added TimaKeyStore provider
W/ResourcesManager( 7204): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7204): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
