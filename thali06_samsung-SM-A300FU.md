#### Test 58135655c662d33_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/SSRM:n  ( 1022): SIOP:: AP = 290
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
--------- beginning of main
E/SMD     (  293): DCD OFF
I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6171): 
D/AndroidRuntime( 6171): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6171): CheckJNI is OFF
D/AndroidRuntime( 6171): readGMSProperty: start
D/AndroidRuntime( 6171): readGMSProperty: already setted!!
D/AndroidRuntime( 6171): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6171): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6171): readGMSProperty: end
D/AndroidRuntime( 6171): addProductProperty: start
E/AffinityControl( 6171): AffinityControl: registerfunction enter
D/AndroidRuntime( 6171): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6183 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 6183): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1022): Focused application set to: xxxx
I/libpersona( 6183): KNOX_SDCARD not a persona
D/InputDispatcher( 1022): Focus left window: 1484
E/Zygote  ( 6183): MountEmulatedStorage()
E/Zygote  ( 6183): v2
D/AndroidRuntime( 6171): Shutting down VM
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6183): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6183): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6183): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6183): TimaSignature is unavailable
D/ActivityThread( 6183): Added TimaKeyStore provider
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1484): updateVisibility : ActivityRecord{3bf169ff token=android.os.BinderProxy@2e2e2df1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1484): onTrimMemory. Level: 20
I/WebViewFactory( 6183): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6183): Time to load native libraries: 2 ms (timestamps 8044-8046)
I/LibraryLoader( 6183): Expected native library version number "",actual native library version number ""
W/art     ( 6171): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/WebViewChromiumFactoryProvider( 6183): Binding Chromium to main looper Looper (main, tid 1) {11c666e6}
I/LibraryLoader( 6183): Expected native library version number "",actual native library version number ""
I/chromium( 6183): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6183): Initializing chromium process, singleProcess=true
W/art     ( 6183): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6183): ApplicationContext is null in ApplicationStatus
W/chromium( 6183): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6183): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6183): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6183): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6183): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6183): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6183): Local Branch: 
I/Adreno-EGL( 6183): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6183): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6183):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
W/art     ( 6183): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6183): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6183): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6183): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6183): CordovaWebView is running on device made by: samsung
W/art     ( 6183): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6183): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1022): Activity pause timeout for ActivityRecord{424a3c3 u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6183): Render dirty regions requested: true
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
W/chromium( 6183): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6183): updateVisibility : ActivityRecord{1d632bb3 token=android.os.BinderProxy@3134d2ed {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6183): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6183): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1022): Focus entered window: 6183
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6183): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6183): Initialized EGL, version 1.4
D/OpenGLRenderer( 6183): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6183): Enabling debug mode 0
D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1180): Icon Only
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1180): There is/are notification(s) 
I/ActivityManager( 1022): Displayed Component not be shown by security: +708ms (total +12s228ms)
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{424a3c3 u0 com.test.thalitest/.MainActivity t20} time:128617
W/ActivityManager( 1022): mDVFSHelper.release()
W/IInputConnectionWrapper( 6183): showStatusIcon on inactive InputConnection
I/Timeline( 6183): Timeline: Activity_idle id: android.os.BinderProxy@3134d2ed time:128626
I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
I/SamsungIME( 1838): getCurrentCandidateView
W/BindingManager( 6183): Cannot call determinedVisibility() - never saw a connection for the pid: 6183
D/SamsungIME( 1838): Dismiss ExpandCandiate
I/SamsungIME( 1838): getDebugLevel  : 0x4f4c
I/SamsungIME( 1838): getDebugLevel  : 0x4f4c
I/SamsungIME( 1838): KeybaordView init() : load resources
I/SamsungIME( 1838): getCurrentKeyboard
I/SamsungIME( 1838): getTextKeyboard
D/JsMessageQueue( 6183): Set native->JS mode to OnlineEventsBridgeMode
D/SamsungIME( 1838): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6183): JniHelper::setJavaVM(0xb8945448), pthread_self() = -1192640336
,I/chromium( 6183): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6183): Initializing JXcore engine
W/jxcore-log( 6183): JXcore engine is ready
,E/audit   ( 1860): type=1400 msg=audit(1454523173.770:205): avc:  denied  { ioctl } for  pid=6230 comm="Thread-1061" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1860):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1860): type=1300 msg=audit(1454523173.770:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ea328f8 items=0 ppid=309 ppcomm=main pid=6230 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-1061" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1860): type=1320 msg=audit(1454523173.770:205): 
,W/jxcore-log( 6183): Starting JXcore engine
,E/SMD     (  293): DCD OFF
,W/jxcore-log( 6183): Platform android
W/jxcore-log( 6183): 
,W/jxcore-log( 6183): Process ARCH arm
W/jxcore-log( 6183): 
,I/jxcore-log( 6183): JXcore Cordova bridge is ready!,
I/jxcore-log( 6183): 
W/jxcore-log( 6183): JXcore engine is started
,E/jxcore  ( 6183): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6183): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6183): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1022): Set to : 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 6183
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1022): Killing 4201:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1022): mDVFSHelper.acquire()
,V/WindowManager( 1022): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1484): onRestart, Launcher: 951671872
,D/Launcher( 1484): onStart, Launcher: 951671872
,D/Launcher.HomeView( 1484): onStart
,D/Launcher( 1484): onResume, Launcher: 951671872
D/SettingsProvider( 1022): name = kids_home_mode
,D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10006
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
D/Launcher.HomeView( 1484): onResume
,D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1484): onResume
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/ActivityManager( 1022): handle home activity for 0
,I/WallpaperManagerService( 1022): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1022): post home show event for user 0
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1022):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1022): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
D/Launcher.HomeView( 1484): onPause
,D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/splitIntent( 1022): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1022): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 5022): Receive : home resume
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/SurfaceFlinger(  259): id=15 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/Recents_RecreateReceiver( 2544): onReceive by home
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/InputDispatcher( 1022): Focus entered window: 1484
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1484): log_dcs ThreadedRenderer::initialize entered! 
,V/TaskCloserActivity( 6057): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
V/ActivityThread( 1484): updateVisibility : ActivityRecord{3bf169ff token=android.os.BinderProxy@2e2e2df1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1484): onStop
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/IInputConnectionWrapper( 6183): showStatusIcon on inactive InputConnection
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/SamsungIME( 1838): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/Mms/UIEventReceiver( 5678): ui event
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1022): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1484, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_4201/cgroup.procs: No such file or directory
,I/splitIntent( 1022): Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
,I/Timeline( 1484): Timeline: Activity_idle id: android.os.BinderProxy@2e2e2df1 time:130862
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6057): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,W/ActivityManager( 1022): mDVFSHelper.release()
,I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{8768404 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:130885
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,I/PowerManagerService( 1022): [PWL] Off : 15s ago
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1022): waitForAlarm result :8
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/Watchdog( 1022): !@Sync 4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD OFF,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1022): [PWL] Off : 30s ago
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/SSRM:n  ( 1022): SIOP:: AP = 270
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5410): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5410): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5410): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,I/BooksSync( 6109): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6109): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 50716(2MB) AllocSpace objects, 33(532KB) LOS objects, 33% free, 24MB/36MB, paused 2.340ms total 171.778ms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6109): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6109): Soft error
E/BooksSync( 6109): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6109): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6109): Sync error
E/BooksSync( 6109): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6109): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6109): Finished books sync
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 154575, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1022): SIOP:: AP = 270
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2650): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,I/PowerManagerService( 1022): [PWL] Off : 50s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,V/AlarmManager( 1022): waitForAlarm result :4
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5410): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5410): [1] 5.onFinished: Installation state replication failed.
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5410): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SQLiteLog( 1705): (10) POSIX Error : 11 SQLite Error : 3850
,E/Watchdog( 1022): !@Sync 5
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2650): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2650): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 75s ago
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :8,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/Watchdog( 1022): !@Sync 6
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1705): Vacuum at: now=1454523243897 tag=VacuumService
,I/GoogleURLConnFactory( 1705): Using platform SSLCertificateSocketFactory
,W/Uploader( 1705): No account for auth token provided
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1705): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1705): (HTTPLog)-Static: isShipBuild true
I/System.out( 1705): (HTTPLog)-Thread-197-372892376: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/System.out( 1705): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1705): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5410): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5410): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5410): [1] 5.onFinished: Giving up after 6 failures.
,W/Uploader( 1705): No account for auth token provided
,I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,W/Uploader( 1705): No account for auth token provided
,I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,W/Uploader( 1705):  no longer exists, so no auth token.
,I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,W/Uploader( 1705): No account for auth token provided
,I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1705): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1705): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1705): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1705): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true,
I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1705): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1705): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1705): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1705): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1705): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1705): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1705): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1705): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1705): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1705): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/System.out( 1705): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1705): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1705, getuid(): 10011
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,E/SQLiteLog( 1705): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2650): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD OFF,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2650): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2650): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 105s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog( 1022): !@Sync 7,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1022): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1022): !@Sync 8
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6109): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6109): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1705): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1705): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1705): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1705): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1705): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,E/BooksAccountManager( 6109): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6109): Soft error
E/BooksSync( 6109): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6109): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6109): Sync error
E/BooksSync( 6109): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6109): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6109): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282529, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 9
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1022): [PWL] Off : 180s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1022): waitForAlarm result :4
,E/SMD     (  293): DCD OFF
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1022): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1022): initializing...,
I/TLC_TIMA_PKM_initialize( 1022): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1022): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication( 1022): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 11
,I/TZ: qc_tlc_communication( 1022): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1022): Trustlet response is completed
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1022): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1022): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1022): !@Sync 10

```
