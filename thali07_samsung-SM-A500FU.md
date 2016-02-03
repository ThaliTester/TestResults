#### Test 58135655c662d33_thali07_samsung-SM-A500FU Logs


```
--------- beginning of system
I/PowerManagerService( 1018): [PWL] Off : 15s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1911, ws=null) (elapsedTime=31235)
,--------- beginning of main
E/SMD     (  287): DCD OFF
D/AndroidRuntime( 5473): 
D/AndroidRuntime( 5473): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5473): CheckJNI is OFF
D/AndroidRuntime( 5473): readGMSProperty: start
D/AndroidRuntime( 5473): readGMSProperty: already setted!!
D/AndroidRuntime( 5473): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5473): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5473): readGMSProperty: end
D/AndroidRuntime( 5473): addProductProperty: start
E/AffinityControl( 5473): AffinityControl: registerfunction enter
D/AndroidRuntime( 5473): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5485): MountEmulatedStorage()
E/Zygote  ( 5485): v2
I/libpersona( 5485): KNOX_SDCARD checking this for 10174
I/libpersona( 5485): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5485 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1491
D/AndroidRuntime( 5473): Shutting down VM
I/SELinux ( 5485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  256): id=11 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 5485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 5485): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5485): TimaSignature is unavailable
D/ActivityThread( 5485): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/9)
V/ActivityThread( 1491): updateVisibility : ActivityRecord{ebb6c2b token=android.os.BinderProxy@1c94264d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1491): onTrimMemory. Level: 20
I/WebViewFactory( 5485): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5485): Time to load native libraries: 2 ms (timestamps 7967-7969)
I/LibraryLoader( 5485): Expected native library version number "",actual native library version number ""
W/art     ( 5473): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/WebViewChromiumFactoryProvider( 5485): Binding Chromium to main looper Looper (main, tid 1) {2a3a712}
I/LibraryLoader( 5485): Expected native library version number "",actual native library version number ""
I/chromium( 5485): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5485): Initializing chromium process, singleProcess=true
,W/art     ( 5485): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5485): ApplicationContext is null in ApplicationStatus
,W/chromium( 5485): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5485): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5485): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5485): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5485): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5485): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5485): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5485): Local Branch: 
I/Adreno-EGL( 5485): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5485): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5485):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5485): 445365004: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5485): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5485): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5485): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5485): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5485): CordovaWebView is running on device made by: samsung
,W/art     ( 5485): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5485): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5485): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 5485): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 5485): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5485): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 5485
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5485): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 5485): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5485): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 5485): Enabling debug mode 0
,V/ActivityThread( 5485): updateVisibility : ActivityRecord{cf9ff3c token=android.os.BinderProxy@af8df0e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1181): There is/are notification(s) 
,I/ActivityManager( 1018): Displayed Component not be shown by security: +571ms (total +650ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{1bf9a45a u0 com.test.thalitest/.MainActivity t233} time:68412
,I/SamsungIME( 1783): getCurrentCandidateView
,W/IInputConnectionWrapper( 5485): showStatusIcon on inactive InputConnection
,I/Timeline( 5485): Timeline: Activity_idle id: android.os.BinderProxy@af8df0e time:68417
,I/SurfaceFlinger(  256): id=11 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=11 Removed uhalitest (-2/9)
,D/SamsungIME( 1783): Dismiss ExpandCandiate
,I/SamsungIME( 1783): getDebugLevel  : 0x4f4c
,W/BindingManager( 5485): Cannot call determinedVisibility() - never saw a connection for the pid: 5485
,I/SamsungIME( 1783): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1783): KeybaordView init() : load resources
,I/SamsungIME( 1783): getCurrentKeyboard
I/SamsungIME( 1783): getTextKeyboard
,D/SamsungIME( 1783): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 5485): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5485): JniHelper::setJavaVM(0xb73d0450), pthread_self() = -1215168008
,I/chromium( 5485): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5485): Initializing JXcore engine
W/jxcore-log( 5485): JXcore engine is ready
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/audit   ( 1844): type=1400 msg=audit(1454523110.032:203): avc:  denied  { ioctl } for  pid=5534 comm="Thread-937" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1844):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1844): type=1300 msg=audit(1454523110.032:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d8c28f8 items=0 ppid=305 ppcomm=main pid=5534 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-937" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1844): type=1320 msg=audit(1454523110.032:203): 
,W/jxcore-log( 5485): Starting JXcore engine
,W/jxcore-log( 5485): Platform android
W/jxcore-log( 5485): 
,W/jxcore-log( 5485): Process ARCH arm
W/jxcore-log( 5485): 
,E/SMD     (  287): DCD OFF
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{1fa94730 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService},
,I/jxcore-log( 5485): JXcore Cordova bridge is ready!
I/jxcore-log( 5485): 
,W/jxcore-log( 5485): JXcore engine is started
,E/jxcore  ( 5485): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5485): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5485): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus left window: 5485
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018): Killing 5016:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,W/PluginManager( 5485): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  256): id=12 Removed NainActivit (6/8)
I/SurfaceFlinger(  256): id=12 Removed NainActivit (-2/8)
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1491): onRestart, Launcher: 445365004
,D/Launcher( 1491): onStart, Launcher: 445365004
,D/Launcher.HomeView( 1491): onStart
D/Launcher( 1491): onResume, Launcher: 445365004
,D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/Launcher.HomeView( 1491): onResume
,D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1491): onResume
,I/splitIntent( 1018): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1018): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,D/WallpaperManager( 1491): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1491): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/GalleryCacheReady( 4600): Receive : home resume
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/Recents_RecreateReceiver( 2300): onReceive by home
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5537): MountEmulatedStorage()
I/libpersona( 5537): KNOX_SDCARD checking this for 10142
E/Zygote  ( 5537): v2
I/libpersona( 5537): KNOX_SDCARD not a persona
I/SELinux ( 5537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5537 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!,
D/ActivityManager( 1018): handle home activity for 0
W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5016/cgroup.procs: No such file or directory
E/SELinux ( 5537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,D/Launcher.HomeView( 1491): onPause
D/Launcher( 1491): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 4491): ui event
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5551): MountEmulatedStorage()
,I/libpersona( 5551): KNOX_SDCARD checking this for 10139
E/Zygote  ( 5551): v2
I/libpersona( 5551): KNOX_SDCARD not a persona
I/SELinux ( 5551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5551 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 5551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/BroadcastQueue( 1018): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1491, uid=10007) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/TimaKeyStoreProvider( 5537): TimaSignature is unavailable
,D/ActivityThread( 5537): Added TimaKeyStore provider
,I/SurfaceFlinger(  256): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1018): Focus entered window: 1491
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1491): log_dcs ThreadedRenderer::initialize entered! 
,D/TimaKeyStoreProvider( 5551): TimaSignature is unavailable
,V/ActivityThread( 1491): updateVisibility : ActivityRecord{ebb6c2b token=android.os.BinderProxy@1c94264d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1491): onStop
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityThread( 5551): Added TimaKeyStore provider
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1783): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
W/IInputConnectionWrapper( 5485): showStatusIcon on inactive InputConnection
,V/TaskCloserActivity( 5537): TaskCloserActivity enter()
,V/TaskCloserActivity( 5537): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/PanelView( 1181): There is/are notification(s) 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1018): Killing 5048:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,W/ResourcesManager( 5551): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5551): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5551): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5551): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5551): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1491): Timeline: Activity_idle id: android.os.BinderProxy@1c94264d time:70768
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3a5d4f9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t232} time:70792
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 3980:com.sec.spp.push/u0a35 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5537): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5048/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_3980/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1018): !@Sync 2
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  277): uids 10012
,D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5579): MountEmulatedStorage()
,E/Zygote  ( 5579): v2
I/libpersona( 5579): KNOX_SDCARD checking this for 10104
I/libpersona( 5579): KNOX_SDCARD not a persona
,I/SELinux ( 5579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5579 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 5579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 5579): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5579): TimaSignature is unavailable
,D/ActivityThread( 5579): Added TimaKeyStore provider
,W/ResourcesManager( 5579): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5579): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5579): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5579): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 5579): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5579): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5579): MmsConfig.loadFromResources
,E/Babel_SMS( 5579): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5579): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  282): getCameraInfo: X
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  282): getCameraInfo: X
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Settings( 5579): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5579): startup - clean
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5579): deleted: false for 0
,D/Finsky  ( 5064): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5064): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5064): [1] 5.onFinished: Scheduling replication attempt 1.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 5579): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5579): Unsupported mime audio/evrc
,W/AudioCapabilities( 5579): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5579): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 5579): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 5579): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5579): Unsupported mime audio/x-ima
,W/AudioCapabilities( 5579): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5579): Unsupported mime audio/evrc
,W/VideoCapabilities( 5579): Unsupported mime video/wvc1
,W/VideoCapabilities( 5579): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5579): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 5579): Unsupported mime video/wvc1
,W/VideoCapabilities( 5579): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 5579): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 5579): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 5579): Unsupported mime video/mp43
,W/VideoCapabilities( 5579): Unsupported mime video/sorenson
,W/VideoCapabilities( 5579): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5579): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5579): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5579): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5579): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5579): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1018): Killing 4828:com.sec.spp.push:RemoteNotiProcess/u0a35 (adj 15): empty #31
,I/vclib   ( 5579): onServiceConnected
,W/Babel   ( 5579): Attempted to change video mute state without an active call.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10035/pid_4828/cgroup.procs: No such file or directory
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,E/SQLiteLog( 1650): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager( 1018): waitForAlarm result :8
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 320,
,I/PowerManagerService( 1018): [PWL] Off : 30s ago,
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1,
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1911, ws=null) (elapsedTime=46240)
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4282, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for charging
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5064): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5064): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5064): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4287, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/Watchdog( 1018): !@Sync 3
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,D/FactoryTest( 4868): Not factory mode
,D/FactoryTest( 4868): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 4868): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 4868): still no open session command from host, so toast
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 4868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 4868): Timeline: Activity_launch_request id:com.android.settings time:110611
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
,I/PersonaManagerService( 1018): PersonaId don't exist
,I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1018): Set to : 0
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1491
,E/MTPRx   ( 4868): started activity for popup
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 4868): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 4868): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4868): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4868): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 4868): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 1491
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@28c29d70 attribute=null, token = android.os.BinderProxy@15c61288
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SettingsReceiverActivity( 4868): dev.kiessupport is : TRUE
,D/PhoneWindow( 4868): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 4868): *FMB* installDecor flags : 8388610
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/ActivityManager( 1018): mDVFSHelper.release(),
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5064): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5064): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5064): [1] 5.onFinished: Scheduling replication attempt 3.
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for charging
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 4
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5064): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5064): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5064): [1] 5.onFinished: Scheduling replication attempt 4.
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4288, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 280
,E/SMD     (  287): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate,
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5064): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5064): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5064): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 43425(2MB) AllocSpace objects, 51(816KB) LOS objects, 33% free, 27MB/40MB, paused 2.379ms total 149.456ms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1650): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1650): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1650): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1650): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5064): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5064): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5064): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4293, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for charging
D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  277): uids 1000
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10012
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  287): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  287): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate,
V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  287): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  287): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  287): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  287): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  287): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  287): DCD OFF
,E/SMD     (  287): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0

```
