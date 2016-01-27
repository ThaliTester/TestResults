#### Test 564496604206eac_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  290): DCD OFF
D/AndroidRuntime( 6139): 
D/AndroidRuntime( 6139): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6139): CheckJNI is OFF
D/AndroidRuntime( 6139): readGMSProperty: start
D/AndroidRuntime( 6139): readGMSProperty: already setted!!
D/AndroidRuntime( 6139): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6139): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6139): readGMSProperty: end
D/AndroidRuntime( 6139): addProductProperty: start
E/AffinityControl( 6139): AffinityControl: registerfunction enter
D/AndroidRuntime( 6139): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1021): mDVFSHelper.acquire()
D/FocusedStackFrame( 1021): Set to : 0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : 25362712
E/Zygote  ( 6152): MountEmulatedStorage()
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6152 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6152): v2
I/libpersona( 6152): KNOX_SDCARD checking this for 10338
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/libpersona( 6152): KNOX_SDCARD not a persona
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1499
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
D/AndroidRuntime( 6139): Shutting down VM
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6152): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6152): TimaSignature is unavailable
D/ActivityThread( 6152): Added TimaKeyStore provider
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1021): isKioskContainerExistOnDevice
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
V/ActivityThread( 1499): updateVisibility : ActivityRecord{350984ab token=android.os.BinderProxy@c63294 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1499): onTrimMemory. Level: 20
I/WebViewFactory( 6152): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6152): Time to load native libraries: 2 ms (timestamps 2046-2048)
I/LibraryLoader( 6152): Expected native library version number "",actual native library version number ""
W/art     ( 6139): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6152): Binding Chromium to main looper Looper (main, tid 1) {19bf3d89}
I/LibraryLoader( 6152): Expected native library version number "",actual native library version number ""
I/chromium( 6152): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6152): Initializing chromium process, singleProcess=true
W/art     ( 6152): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6152): ApplicationContext is null in ApplicationStatus
W/chromium( 6152): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6152): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6152): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6152): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6152): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6152): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6152): Local Branch: 
I/Adreno-EGL( 6152): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6152): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6152):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6152): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6152): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6152): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6152): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6152): CordovaWebView is running on device made by: samsung
W/art     ( 6152): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6152): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{12b2c7db u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6152): Render dirty regions requested: true
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
W/chromium( 6152): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6152): updateVisibility : ActivityRecord{195f8c4a token=android.os.BinderProxy@320e95ec {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6152): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6152): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1021): Focus entered window: 6152
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 6152): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6152): Initialized EGL, version 1.4
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 6152): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6152): Enabling debug mode 0
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1021): Displayed Component not be shown by security: +695ms (total +34s843ms)
W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{12b2c7db u0 com.test.thalitest/.MainActivity t20} time:152604
W/IInputConnectionWrapper( 6152): showStatusIcon on inactive InputConnection
I/Timeline( 6152): Timeline: Activity_idle id: android.os.BinderProxy@320e95ec time:152609
I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1878): getCurrentCandidateView
W/BindingManager( 6152): Cannot call determinedVisibility() - never saw a connection for the pid: 6152
D/SamsungIME( 1878): Dismiss ExpandCandiate
I/SamsungIME( 1878): getDebugLevel  : 0x4f4c
I/SamsungIME( 1878): getDebugLevel  : 0x4f4c
I/SamsungIME( 1878): KeybaordView init() : load resources
I/SamsungIME( 1878): getCurrentKeyboard
I/SamsungIME( 1878): getTextKeyboard
D/SamsungIME( 1878): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 6152): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6152): JniHelper::setJavaVM(0xb8545448), pthread_self() = -1196838320
I/chromium( 6152): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/jxcore-log( 6152): Initializing JXcore engine
,W/jxcore-log( 6152): JXcore engine is ready
,E/audit   ( 1899): type=1400 msg=audit(1453885557.423:205): avc:  denied  { ioctl } for  pid=6199 comm="Thread-1066" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3085 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1899):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1899): type=1300 msg=audit(1453885557.423:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9dc028f8 items=0 ppid=317 ppcomm=main pid=6199 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1066" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1899): type=1320 msg=audit(1453885557.423:205): 
W/jxcore-log( 6152): Starting JXcore engine
,W/jxcore-log( 6152): Platform android
W/jxcore-log( 6152): 
W/jxcore-log( 6152): Process ARCH arm
W/jxcore-log( 6152): 
,I/jxcore-log( 6152): JXcore Cordova bridge is ready!,
I/jxcore-log( 6152): 
W/jxcore-log( 6152): JXcore engine is started
,E/jxcore  ( 6152): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6152): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6152): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
D/FocusedStackFrame( 1021): Set to : 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 6152
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1021): Killing 5605:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1499): onRestart, Launcher: 398951883
,D/Launcher( 1499): onStart, Launcher: 398951883
D/Launcher.HomeView( 1499): onStart
D/Launcher( 1499): onResume, Launcher: 398951883
D/SettingsProvider( 1021): name = kids_home_mode
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10006
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
D/Launcher.HomeView( 1499): onResume
,D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1499): onResume
W/libprocessgroup( 1021): failed to open /acct/uid_10139/pid_5605/cgroup.procs: No such file or directory
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/splitIntent( 1021): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/splitIntent( 1021): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/WallpaperManager( 1499): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1499): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,D/GalleryCacheReady( 5043): Receive : home resume
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2535): onReceive by home
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5678): ui event
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6201): MountEmulatedStorage()
,I/libpersona( 6201): KNOX_SDCARD checking this for 10139
E/Zygote  ( 6201): v2
I/libpersona( 6201): KNOX_SDCARD not a persona
I/SELinux ( 6201): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6201 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6201): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1021): userId = 0, bbcId = -10000
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/SELinux ( 6201): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/art     (  317): Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 23.443ms
,D/TimaKeyStoreProvider( 6201): TimaSignature is unavailable
,D/ActivityThread( 6201): Added TimaKeyStore provider
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 16.424ms
,I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 563us total 16.171ms,
,E/Zygote  ( 6218): MountEmulatedStorage(),
E/Zygote  ( 6218): v2
I/libpersona( 6218): KNOX_SDCARD checking this for 10135
I/libpersona( 6218): KNOX_SDCARD not a persona,
I/SELinux ( 6218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6218 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,E/SELinux ( 6218): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1021): handle home activity for 0,
I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1021): post home show event for user 0
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/Launcher.HomeView( 1499): onPause
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/BroadcastQueue( 1021): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1499, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/TimaKeyStoreProvider( 6218): TimaSignature is unavailable
D/ActivityThread( 6218): Added TimaKeyStore provider
,V/TaskCloserActivity( 6201): TaskCloserActivity enter()
,I/SurfaceFlinger(  259): id=14 createSurf (540x960),1 flag=4, Mauncher
V/TaskCloserActivity( 6201): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/InputDispatcher( 1021): Focus entered window: 1499
I/ActivityManager( 1021): Killing 4171:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1499): log_dcs ThreadedRenderer::initialize entered! 
,W/ResourcesManager( 6218): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6218): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 6218): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/ActivityThread( 1499): updateVisibility : ActivityRecord{350984ab token=android.os.BinderProxy@c63294 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1499): onStop
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6152): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1878): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,I/Timeline( 1499): Timeline: Activity_idle id: android.os.BinderProxy@c63294 time:155539
,I/splitIntent( 1021): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
I/ActivityManager( 1021): Killing 5232:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6201): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{2c5706a7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:155560
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4171/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_5232/cgroup.procs: No such file or directory
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,V/AlarmManager( 1021): waitForAlarm result :8
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,I/BooksSync( 6076): Starting books sync for 61035162, extras: ade
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksConfig( 6076): GmsCore Version = 7.8.99 (2134222-434)
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6076): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6076): Soft error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6076): Sync error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6076): Finished books sync
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/AlarmManager( 1021): waitForAlarm result :4
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/SSRM:n  ( 1021): SIOP:: AP = 290
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1708): Explicit concurrent mark sweep GC freed 22826(1333KB) AllocSpace objects, 5(101KB) LOS objects, 39% free, 7MB/12MB, paused 1.215ms total 50.536ms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5408): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 5
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5408): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1021): !@Sync 6
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 140s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1708): Vacuum at: now=1453885606711 tag=VacuumService
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1021): waitForAlarm result :8,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/Watchdog( 1021): !@Sync 7
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 180s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 1021): !@Sync 8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 9
,I/PowerManagerService( 1021): [PWL] Off : 225s ago
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6076): Starting books sync for 61035162, extras: ade
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 46349(2MB) AllocSpace objects, 73(1173KB) LOS objects, 33% free, 23MB/35MB, paused 2.426ms total 152.358ms
,I/BooksConfig( 6076): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/BooksAccountManager( 6076): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6076): Soft error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6076): Sync error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6076): Finished books sync
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289610, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1021): initializing...
I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 10
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1021): [PWL] Off : 275s ago
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 11
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
W/GLSActivity( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1708): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1708): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1708): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1708): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,E/PlayEventLogger( 5408): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5408): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5408): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5408): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5408): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5408): 	at android.os.Binder.execTransact(Binder.java:461)
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5408): Ignoring header User-Agent because its value was null.
,I/System.out( 5408): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5408): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5408): (HTTPLog)-Static: isShipBuild true
,I/System.out( 5408): (HTTPLog)-Thread-918-456837760: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5408): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 5408): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 12
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 330s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 13
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1021): !@Sync 14
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 390s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 15,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/bootchecker(  324): bootchecker wake up!!,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1021): !@Sync 16
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
V/AlarmManager( 1021): No more alarm at this time.nowELAPSED=517164 batch.start=553662
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 455s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 17
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6076): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6076): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice,
D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6076): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6076): Soft error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6076): Sync error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6076): Finished books sync
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 553662, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1021): !@Sync 18
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :8
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  327): Stop the daemon....,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 19
,I/PowerManagerService( 1021): [PWL] Off : 525s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1021): !@Sync 20
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :8
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 21
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 600s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 22
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 23,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 24
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 680s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 25
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 26
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 27
,I/PowerManagerService( 1021): [PWL] Off : 765s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 28
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 29
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1021): !@Sync 30
,I/PowerManagerService( 1021): [PWL] Off : 855s ago
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/Finsky  ( 5408): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1708): Message class com.google.f.a.a.i
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1708): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1708): No account for auth token provided
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/System.out( 1708): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1708): (HTTPLog)-Static: isShipBuild true
I/System.out( 1708): (HTTPLog)-Thread-200-71622294: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,W/Finsky  ( 5408): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1708): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1708): Tagging socket 63 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5408): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Uploader( 1708): No account for auth token provided
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,W/Uploader( 1708): No account for auth token provided
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1708): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1708): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1708): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1708): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1708): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1708): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1708): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1708): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/Uploader( 1708): No account for auth token provided
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5408): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5408): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/Uploader( 1708): No account for auth token provided
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,D/Finsky  ( 5408): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,D/Finsky  ( 5408): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1820): client connected with version: 7571000
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1708): No account for auth token provided
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,W/Uploader( 1708):  no longer exists, so no auth token.
,I/System.out( 1708): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1708): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1708, getuid(): 10011
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :8,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 61942(5MB) AllocSpace objects, 267(4MB) LOS objects, 33% free, 23MB/35MB, paused 2.532ms total 166.882ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5408): [1] 5.onFinished: Scheduling replication attempt 1.
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 31
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2659): Disconnected process message: 10,
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5408): [1] 5.onFinished: Scheduling replication attempt 2.
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 32
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5408): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5408): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 33
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 950s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5408): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 34
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5408): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5408): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5408): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 35
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6076): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6076): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1708): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1708): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1708): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1708): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/GLSActivity( 1708): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6076): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6076): Soft error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6076): Sync error
E/BooksSync( 6076): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6076): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6076): Finished books sync
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1081119, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,E/SMD     (  290): DCD OFF
,E/SQLiteLog( 1708): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 36
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1437): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1437): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2659): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2659): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 1050s ago
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1021): !@Sync 37
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1021): !@Sync 38
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 39
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1021): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1021): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1021): Updating Usage Statistics in DB @ 1453886618689
,I/ApplicationPolicy( 1021): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1021): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1021): ::isTableExists: Table exists 
,I/ApplicationUsage( 1021): Done Updating Usage Statistics in DB @ 1453886619066
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 40
,I/PowerManagerService( 1021): [PWL] Off : 1155s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 41
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 42
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/Watchdog( 1021): !@Sync 43
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 1266s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/Watchdog( 1021): !@Sync 44
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6756): 
D/AndroidRuntime( 6756): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6756): CheckJNI is OFF
D/AndroidRuntime( 6756): readGMSProperty: start
D/AndroidRuntime( 6756): readGMSProperty: already setted!!
D/AndroidRuntime( 6756): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6756): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6756): readGMSProperty: end
D/AndroidRuntime( 6756): addProductProperty: start
E/AffinityControl( 6756): AffinityControl: registerfunction enter
D/AndroidRuntime( 6756): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1021): START PACKAGE DELETE: observer{137324042}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1021): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 6152:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1021): Skipping PackageSetting{1efeb7fa com.example.hello/10346} due to missing metadata
W/ActivityManager( 1021): Spurious death for ProcessRecord{2301ae7b 6152:com.test.thalitest/u0a338}, curProc for 6152: null
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
I/art     ( 6011): Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 830us total 63.711ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4064): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 908us total 42.259ms
I/art     ( 5937): Explicit concurrent mark sweep GC freed 3754(193KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 900us total 52.787ms
W/GeofencerStateMachine( 1820): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1878): mOCRHelper is null
I/KLMS-2.5.123: ( 3738): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 27 10:26:08 GMT+01:00 2016
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3738): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6768): MountEmulatedStorage()
I/libpersona( 6768): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6768): v2
I/libpersona( 6768): KNOX_SDCARD not a persona
I/SELinux ( 6768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6768 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3738): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/TimaKeyStoreProvider( 6768): TimaSignature is unavailable
D/ActivityThread( 6768): Added TimaKeyStore provider
D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
I/KLMS-2.5.123: ( 3738): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/RegisteredServicesCache( 1461): empty dynamic service
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
I/art     ( 1021): Explicit concurrent mark sweep GC freed 57965(5MB) AllocSpace objects, 179(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.838ms total 237.844ms
I/art     ( 1021): WaitForGcToComplete blocked for 172.456ms for cause Explicit
D/elm:15121( 6768): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 6768): ELMEngine.ELMEngine( context ).
D/elm:15121( 6768): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 6768): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 6768): ElmAgentService : onCreate()
D/elm:15121( 6768): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6768): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6768): MDMBridge.getInstance()
D/elm:15121( 6768): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 6768): MDMBridge.getAllLicenseInfoFromSDK()
D/RCPManagerService( 1021): PackageReceiver onReceive()
I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 6768): ElmAgentService : onDestroy().
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3738): KLMSIntentService(): onDestroy()
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
D/TaskPersister( 1021): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
I/PCWCLIENTTRACE_PushUtil( 5720): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5720): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5720): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5720): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5818): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5818): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 5043): PackagesMonitor onReceive :com.test.thalitest
I/art     ( 1021): Explicit concurrent mark sweep GC freed 14717(805KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.628ms total 214.625ms
D/Mms/FreeMessageStatusReceiver( 5678): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
I/TactileAssist( 1021): enable value -1
I/TactileAssist( 1021): internal enable value -1
I/TactileAssist( 1021): intensity value -1
I/TactileAssist( 1021): saveAppList value true
D/Mms/FreeMessageReceiverService( 5678): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
I/TactileAssist( 1021): List of disabled apps :
D/Mms/FreeMessageReceiverService( 5678): onHandleIntent: ACTION_PACKAGE_REMOVED
D/PackageManager( 1021): delete codoeFile: 
D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10338 Target=com.test.thalitest
D/PackageManager( 1021): result of delete: 1{137324042}
D/AndroidRuntime( 6756): Shutting down VM
D/Compatibility( 5898): onReceive() it will make start service
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1021): no available spell checker services found
D/Compatibility( 5898): onHandleIntent()
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5898): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5898): found: 2
D/Compatibility( 5898): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5898): skipping ResolveInfo{3ad52945 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5898): considering ResolveInfo{2fb3c89a com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5898): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5898): enabling receiver ResolveInfo{17c785cb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6789): MountEmulatedStorage()
I/libpersona( 6789): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6789): v2
I/libpersona( 6789): KNOX_SDCARD not a persona
I/SELinux ( 6789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6789 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5898): enabling receiver ResolveInfo{30ba01a8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/SELinux ( 6789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5898): enabling receiver ResolveInfo{1ba414c1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5898): enabling receiver ResolveInfo{1175d466 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5898): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6789): TimaSignature is unavailable
D/ActivityThread( 6789): Added TimaKeyStore provider
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/UserAnalysis.PlaceProvider( 6789): PlaceProvider onCreate()
D/UserAnalysis.SecureDbManager( 6789): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6789): SecurePlaceDbHelper() 
D/UserAnalysis( 6789): Create SecureDbHelper
W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/IntelligenceServiceApplication( 6789): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6789): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl( 5916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 6789): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6806): MountEmulatedStorage()
E/Zygote  ( 6806): v2
I/libpersona( 6806): KNOX_SDCARD checking this for 1000
I/libpersona( 6806): KNOX_SDCARD not a persona
I/SELinux ( 6806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 1021): Killing 5693:com.samsung.helphub/1000 (adj 15): empty #31
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
D/UsbSettingsManager( 1021): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1021): onPackageRemoved : com.test.thalitest
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
D/TimaKeyStoreProvider( 6806): TimaSignature is unavailable
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
D/ActivityThread( 6806): Added TimaKeyStore provider
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
W/art     ( 6756): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 6789): cancelDiscovery
D/BluetoothAdapterProperties( 2659): mDiscovering is false
W/ResourcesManager( 6806): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/BluetoothAdapterService( 2659): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6789): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6789): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6789): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/RCPManager( 6806):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5937): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 5937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5693/cgroup.procs: No such file or directory
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/FilterInstaller( 5937): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5937): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5937): before removeFromFS
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6823): MountEmulatedStorage()
E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD checking this for 1000
I/libpersona( 6823): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 6833): MountEmulatedStorage()
E/Zygote  ( 6833): v2
I/ActivityManager( 1021): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6833 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/libpersona( 6833): KNOX_SDCARD checking this for 10095
I/libpersona( 6833): KNOX_SDCARD not a persona
I/SELinux ( 6833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
D/ActivityThread( 6823): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 6833): TimaSignature is unavailable
D/ActivityThread( 6833): Added TimaKeyStore provider
D/PreloadFilterInstaller( 6833): uses FILTER_DB_VER_1
E/SQLiteLog( 6833): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6833): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6833): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6833): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6833): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6833): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6833): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6833): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6833): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6833): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6833): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6833): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6833): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6833): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6833): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6833): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteLog( 6823): (28) failed to open "/data/data/com.samsung.helphub/databases/search.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteOpenHelper( 6833): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6833): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6833): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6833): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6833): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6833): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6833): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6833): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6833): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6833): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6833): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6833): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6833): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6833): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6833): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6833): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6833): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6833): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6833): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteDatabase( 6823): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 6823): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6823): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6823): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6823): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6823): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 6823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6823): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6823): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6823): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6823): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6823): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6823): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6823): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6823): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6823): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 6823): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6823): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6823): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6823): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6823): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 6823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6823): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6823): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6823): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6823): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6823): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6823): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6823): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6823): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6823): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6823): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6823): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6823): Opened search.db in read-only mode
W/SQLiteOpenHelper( 6833): Opened filter.db in read-only mode
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6833): (284) automatic index on titles(filter_id)
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0

```
