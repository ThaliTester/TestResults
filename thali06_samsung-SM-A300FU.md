#### Test 613623660556c10_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
V/AlarmManager( 1021): waitForAlarm result :8
,--------- beginning of main
D/AndroidRuntime( 5386): 
D/AndroidRuntime( 5386): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5386): CheckJNI is OFF
D/AndroidRuntime( 5386): readGMSProperty: start
D/AndroidRuntime( 5386): readGMSProperty: already setted!!
D/AndroidRuntime( 5386): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5386): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5386): readGMSProperty: end
D/AndroidRuntime( 5386): addProductProperty: start
E/AffinityControl( 5386): AffinityControl: registerfunction enter
D/AndroidRuntime( 5386): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1021): mDVFSHelper.acquire()
D/FocusedStackFrame( 1021): Set to : 0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : -2122120936
E/Zygote  ( 5398): MountEmulatedStorage()
E/Zygote  ( 5398): v2
I/libpersona( 5398): KNOX_SDCARD checking this for 10338
I/libpersona( 5398): KNOX_SDCARD not a persona
I/SELinux ( 5398): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5398 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1496
D/AndroidRuntime( 5386): Shutting down VM
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 5398): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5398): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5398): TimaSignature is unavailable
D/ActivityThread( 5398): Added TimaKeyStore provider
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
D/PersonaManager( 1021): isKioskContainerExistOnDevice
V/ActivityThread( 1496): updateVisibility : ActivityRecord{94a42a token=android.os.BinderProxy@2c81e0f1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1496): onTrimMemory. Level: 20
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/WebViewFactory( 5398): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
W/art     ( 5386): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/LibraryLoader( 5398): Time to load native libraries: 1 ms (timestamps 546-547)
I/LibraryLoader( 5398): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5398): Binding Chromium to main looper Looper (main, tid 1) {2de34a79}
I/LibraryLoader( 5398): Expected native library version number "",actual native library version number ""
I/chromium( 5398): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5398): Initializing chromium process, singleProcess=true
W/art     ( 5398): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5398): ApplicationContext is null in ApplicationStatus
W/chromium( 5398): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5398): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5398): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5398): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5398): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5398): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5398): Local Branch: 
I/Adreno-EGL( 5398): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5398): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5398):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/BluetoothAdapter( 5398): 494775099: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5398): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5398): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5398): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5398): *FMB* installDecor flags : -2139027200
D/SystemWebViewEngine( 5398): CordovaWebView is running on device made by: samsung
W/art     ( 5398): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5398): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{18447479 u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 5398): Render dirty regions requested: true
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
W/chromium( 5398): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5398): updateVisibility : ActivityRecord{23ff4746 token=android.os.BinderProxy@1d98c188 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5398): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5398): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1021): Focus entered window: 5398
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5398): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5398): Initialized EGL, version 1.4
D/OpenGLRenderer( 5398): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5398): Enabling debug mode 0
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
I/Timeline( 5398): Timeline: Activity_idle id: android.os.BinderProxy@1d98c188 time:121016
W/IInputConnectionWrapper( 5398): showStatusIcon on inactive InputConnection
I/ActivityManager( 1021): Displayed Component not be shown by security: +641ms (total +14s574ms)
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{18447479 u0 com.test.thalitest/.MainActivity t20} time:121034
W/ActivityManager( 1021): mDVFSHelper.release()
I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/9)
I/SamsungIME( 1741): getCurrentCandidateView
D/SamsungIME( 1741): Dismiss ExpandCandiate
I/SamsungIME( 1741): getDebugLevel  : 0x4f4c
I/SamsungIME( 1741): getDebugLevel  : 0x4f4c
I/SamsungIME( 1741): KeybaordView init() : load resources
E/SMD     (  289): DCD OFF
I/SamsungIME( 1741): getCurrentKeyboard
I/SamsungIME( 1741): getTextKeyboard
W/BindingManager( 5398): Cannot call determinedVisibility() - never saw a connection for the pid: 5398
D/SamsungIME( 1741): [SwiftkeyWrapper] currentLangauge : 1701729619
D/SSRM:n  ( 1021): SIOP:: AP = 260
D/JsMessageQueue( 5398): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5398): JniHelper::setJavaVM(0xb6f71448), pthread_self() = -1219726520
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5398): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5398):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5398):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5398):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5398):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5398): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@124115f7 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14c51382 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5398): addListener: New listener added - the number of listeners is now 1
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5398): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5398): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5398): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5398): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5398): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 5398): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5398): Initializing JXcore engine
W/jxcore-log( 5398): JXcore engine is ready
,E/audit   ( 1781): type=1400 msg=audit(1456908902.960:203): avc:  denied  { ioctl } for  pid=5450 comm="Thread-943" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1781):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1781): type=1300 msg=audit(1456908902.960:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9eb018f8 items=0 ppid=307 ppcomm=main pid=5450 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-943" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1781): type=1320 msg=audit(1456908902.960:203): 
,W/jxcore-log( 5398): Starting JXcore engine
,W/jxcore-log( 5398): Platform android
W/jxcore-log( 5398): 
W/jxcore-log( 5398): Process ARCH arm
W/jxcore-log( 5398): 
,I/jxcore-log( 5398): JXcore Cordova bridge is ready!
I/jxcore-log( 5398): 
,W/jxcore-log( 5398): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5398): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5398): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5398): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5398): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,D/FocusedStackFrame( 1021): Set to : 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 5398
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ActivityManager( 1021): Killing 4844:com.wssyncmldm/1000 (adj 15): empty #31
,W/PluginManager( 5398): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1496): onRestart, Launcher: 558175541
,D/Launcher( 1496): onStart, Launcher: 558175541
,D/Launcher.HomeView( 1496): onStart
D/Launcher( 1496): onResume, Launcher: 558175541
,D/SettingsProvider( 1021): name = kids_home_mode
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10006
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,D/Launcher.HomeView( 1496): onResume
,D/Launcher( 1496): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1496): onResume
,D/WallpaperManager( 1496): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1021): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,D/WallpaperManager( 1496): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
I/splitIntent( 1021): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/GalleryCacheReady( 4320): Receive : home resume
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2272): onReceive by home
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4844/cgroup.procs: No such file or directory
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,V/TaskCloserActivity( 4866): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/ActivityManager( 1021): handle home activity for 0
,I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1021): post home show event for user 0
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,D/Launcher.HomeView( 1496): onPause
D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
,D/Launcher( 1496): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/Mms/UIEventReceiver( 4949): ui event
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5453): MountEmulatedStorage()
,I/libpersona( 5453): KNOX_SDCARD checking this for 10135
E/Zygote  ( 5453): v2
I/libpersona( 5453): KNOX_SDCARD not a persona
I/SELinux ( 5453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5453 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/BroadcastQueue( 1021): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1496, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/SELinux ( 5453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 5453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/SurfaceFlinger(  258): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1021): Focus entered window: 1496
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1496): log_dcs ThreadedRenderer::initialize entered! 
,D/TimaKeyStoreProvider( 5453): TimaSignature is unavailable
,D/Launcher.HomeView( 1496): onStop
V/ActivityThread( 1496): updateVisibility : ActivityRecord{94a42a token=android.os.BinderProxy@2c81e0f1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/ActivityThread( 5453): Added TimaKeyStore provider
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1741): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
W/IInputConnectionWrapper( 5398): showStatusIcon on inactive InputConnection
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,W/ResourcesManager( 5453): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5453): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5453): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5453): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 5453): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1496): Timeline: Activity_idle id: android.os.BinderProxy@2c81e0f1 time:123473
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{6c34b22 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t18} time:123494
W/ActivityManager( 1021): mDVFSHelper.release()
,I/splitIntent( 1021): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1021): Killing 3911:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 4866): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_3911/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,I/PowerManagerService( 1021): [PWL] Off : 75s ago
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 4
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,V/AlarmManager( 1021): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1021): <AppSync3 Whitelist>
,V/AlarmManagerEXT( 1021): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4690): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4690): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4690): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4690): [1] 5.onFinished: Scheduling replication attempt 5.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 5
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4690): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4690): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4690): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 140s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 6
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/NtpTrustedTime( 1021): forceRefresh() from cache miss
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
,D/NtpTrustedTime( 1021): forceRefresh Fail.
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged,
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/Watchdog( 1021): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 180s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1021): [PWL] Off : 225s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 9
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000,
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1021): initializing...,
I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 10
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 275s ago
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged,
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 46432(3MB) AllocSpace objects, 111(1777KB) LOS objects, 33% free, 23MB/35MB, paused 2.250ms total 172.787ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager( 1021): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ResourcesManager( 1180): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1180): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GLSActivity( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1666): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1666): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1666): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 4690): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893),
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4690): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4690): 	at android.os.Binder.execTransact(Binder.java:461)
,D/KnoxNotification( 1180): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1180): ----- inflateViews : modified KnoxViewLocal -----
,W/System  ( 4690): Ignoring header User-Agent because its value was null.
,D/PersonaManager( 1180): PersonaID is invalid or persona doesn't exists. : 0
,I/System.out( 4690): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4690): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4690): (HTTPLog)-Static: isShipBuild true
I/System.out( 4690): (HTTPLog)-Thread-793-1007737815: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4690): (HTTPLog)-Static: isSBSettingEnabled false
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10026
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2,
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Watchdog( 1021): !@Sync 11
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 12
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 330s ago,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 13,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 14,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 390s ago,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 15
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1021): waitForAlarm result :8
,V/AlarmManager( 1021): No more alarm at this time.nowELAPSED=479738 batch.start=523196
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/bootchecker(  313): bootchecker wake up!!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 16
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1021): [PWL] Off : 455s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1,
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 17
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 18
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1021): [PWL] Off : 525s ago
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/Atfwd_Daemon(  316): Stop the daemon....,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 19
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3,
I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 20
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1666): Explicit concurrent mark sweep GC freed 22920(1325KB) AllocSpace objects, 3(60KB) LOS objects, 39% free, 7MB/12MB, paused 1.534ms total 59.816ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1666): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1666): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1666): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 4690): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4690): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4690): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4690): Ignoring header User-Agent because its value was null.
,I/System.out( 4690): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10026
D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
,I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Watchdog( 1021): !@Sync 21
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 600s ago,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 22
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 23
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 24
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 25
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 26
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 765s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 27
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 28
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 29
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 856s ago,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1021): !@Sync 30
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
W/GLSActivity( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1666): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1666): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1666): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
E/PlayEventLogger( 4690): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4690): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4690): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4690): Ignoring header User-Agent because its value was null.
I/System.out( 4690): (HTTPLog)-Static: isSBSettingEnabled false
,I/PhoneStatusBar( 1180): Icon Only
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10026
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Watchdog( 1021): !@Sync 31
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 32
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 951s ago,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 33
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 34
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 35
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 36
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1021): [PWL] Off : 1051s ago,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1021): Plugged
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged,
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 37
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 38
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1021): !@Sync 39
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1156s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1021): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1021): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1021): Updating Usage Statistics in DB @ 1456909996195
,I/ApplicationUsage( 1021): Done Updating Usage Statistics in DB @ 1456909996208,
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 40
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Watchdog( 1021): !@Sync 41
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1666): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1666): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1666): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1666): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1666): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1666): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1666): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1666): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1666): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1666): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
E/PlayEventLogger( 4690): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4690): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 4690): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4690): 	at android.os.Binder.execTransact(Binder.java:461)
W/System  ( 4690): Ignoring header User-Agent because its value was null.
I/System.out( 4690): (HTTPLog)-Static: isSBSettingEnabled false
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10026
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 42
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1021): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
,I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1021): !@Sync 43
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,I/PowerManagerService( 1021): [PWL] Off : 1266s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5985): 
D/AndroidRuntime( 5985): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5985): CheckJNI is OFF
D/AndroidRuntime( 5985): readGMSProperty: start
D/AndroidRuntime( 5985): readGMSProperty: already setted!!
D/AndroidRuntime( 5985): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5985): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5985): readGMSProperty: end
D/AndroidRuntime( 5985): addProductProperty: start
E/AffinityControl( 5985): AffinityControl: registerfunction enter
D/AndroidRuntime( 5985): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1021): START PACKAGE DELETE: observer{452951290}
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1021): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 5398:com.test.thalitest/u0a338 (adj 15): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1021): Skipping PackageSetting{ea93acd com.example.hello/10346} due to missing metadata
W/ActivityManager( 1021): Spurious death for ProcessRecord{3a3892ab 5398:com.test.thalitest/u0a338}, curProc for 5398: null
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3611): Explicit concurrent mark sweep GC freed 2468(147KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 802us total 25.540ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/art     ( 5287): Explicit concurrent mark sweep GC freed 52(13KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 670us total 52.116ms
E/SamsungIME( 1741): mOCRHelper is null
W/GeofencerStateMachine( 1680): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3409): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 02 10:15:13 GMT+01:00 2016
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3409): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5998): MountEmulatedStorage()
E/Zygote  ( 5998): v2
I/libpersona( 5998): KNOX_SDCARD checking this for 10090
I/libpersona( 5998): KNOX_SDCARD not a persona
I/SELinux ( 5998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5998 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3409): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
D/TimaKeyStoreProvider( 5998): TimaSignature is unavailable
D/ActivityThread( 5998): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3409): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/art     ( 1021): Explicit concurrent mark sweep GC freed 23368(2MB) AllocSpace objects, 37(596KB) LOS objects, 33% free, 23MB/35MB, paused 2.681ms total 207.279ms
I/art     ( 1021): WaitForGcToComplete blocked for 203.097ms for cause Explicit
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): PACKAGE_REMOVED
D/RegisteredServicesCache( 1457): empty dynamic service
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/elm:15121( 5998): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 5998): ELMEngine.ELMEngine( context ).
D/elm:15121( 5998): MDMBridge.setEnterpriseBridge()
D/RCPManagerService( 1021): PackageReceiver onReceive()
W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 5998): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 5998): ElmAgentService : onCreate()
D/elm:15121( 5998): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 5998): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 5998): MDMBridge.getInstance()
D/elm:15121( 5998): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 5998): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3409): KLMSIntentService(): onDestroy()
D/elm:15121( 5998): ElmAgentService : onDestroy().
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1021): no available spell checker services found
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
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TaskPersister( 1021): removeObsoleteFile: deleting file=20_task.xml
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1021): Explicit concurrent mark sweep GC freed 12186(623KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 8.631ms total 198.146ms
I/PCWCLIENTTRACE_PushUtil( 5004): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5004): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5004): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5004): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SA      ( 5091): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5091): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
I/PackagesMonitor( 4320): PackagesMonitor onReceive :com.test.thalitest
W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Mms/FreeMessageStatusReceiver( 4949): onReceive, action : android.intent.action.PACKAGE_REMOVED
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/TactileAssist( 1021): enable value -1
I/TactileAssist( 1021): internal enable value -1
I/TactileAssist( 1021): intensity value -1
I/TactileAssist( 1021): saveAppList value true
D/Mms/FreeMessageReceiverService( 4949): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4949): onHandleIntent: ACTION_PACKAGE_REMOVED
I/TactileAssist( 1021): List of disabled apps :
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1021): delete codoeFile: 
D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10338 Target=com.test.thalitest
D/PackageManager( 1021): result of delete: 1{452951290}
D/AndroidRuntime( 5985): Shutting down VM
D/Compatibility( 5181): onReceive() it will make start service
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/Compatibility( 5181): onHandleIntent()
D/Compatibility( 5181): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10338, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/Compatibility( 5181): found: 2
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Compatibility( 5181): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5181): skipping ResolveInfo{33746c1f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5181): considering ResolveInfo{207dab6c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5181): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6018): MountEmulatedStorage()
I/libpersona( 6018): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6018): v2
I/libpersona( 6018): KNOX_SDCARD not a persona
I/SELinux ( 6018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/Compatibility( 5181): enabling receiver ResolveInfo{21451535 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/SELinux ( 6018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6018 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 6018): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5181): enabling receiver ResolveInfo{12de5dca com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/Compatibility( 5181): enabling receiver ResolveInfo{1d7dab3b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1021): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1021): onPackageRemoved : com.test.thalitest
D/Compatibility( 5181): enabling receiver ResolveInfo{3501258 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5181): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
D/TimaKeyStoreProvider( 6018): TimaSignature is unavailable
D/ActivityThread( 6018): Added TimaKeyStore provider
D/UserAnalysis.PlaceProvider( 6018): PlaceProvider onCreate()
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/UserAnalysis.SecureDbManager( 6018): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 6018): SecurePlaceDbHelper() 
D/UserAnalysis( 6018): Create SecureDbHelper
D/IntelligenceServiceApplication( 6018): onCreate()
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6018): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
W/ContextImpl( 5201): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/IntelligenceServiceApplication( 6018): no applications having user consent for prediction
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetection::stopService] Service stopped.
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
E/Zygote  ( 6035): MountEmulatedStorage()
I/libpersona( 6035): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6035): v2
I/libpersona( 6035): KNOX_SDCARD not a persona
I/SELinux ( 6035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
D/BluetoothAdapter( 6018): 98565124: getState() :  mService = null. Returning STATE_OFF
V/PlaceDetection v1.0.19 ( 6018): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetection::stopService] Service stopped.
V/PlaceDetection v1.0.19 ( 6018): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
I/ActivityManager( 1021): Killing 4554:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
I/art     (  307): Explicit concurrent mark sweep GC freed 8698(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 23.154ms
D/TimaKeyStoreProvider( 6035): TimaSignature is unavailable
D/ActivityThread( 6035): Added TimaKeyStore provider
W/ResourcesManager( 6035): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.850ms
D/RCPManager( 6035):  in createShortcut() for packageName: com.test.thalitest userId0
W/art     ( 5985): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.101ms total 19.032ms
D/RCPManagerService( 1021):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1021): queryAllProviders():  providerCallBack is not register for 0
D/FilterInstaller( 5223): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
W/ContextImpl( 5223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
I/FilterInstaller( 5223): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5223): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5223): before removeFromFS
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6051): MountEmulatedStorage()
E/Zygote  ( 6051): v2
I/libpersona( 6051): KNOX_SDCARD checking this for 1000
I/libpersona( 6051): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6051): TimaSignature is unavailable
D/ActivityThread( 6051): Added TimaKeyStore provider
I/ActivityManager( 1021): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6065 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 6065): MountEmulatedStorage()
I/libpersona( 6065): KNOX_SDCARD checking this for 10095
E/Zygote  ( 6065): v2
I/libpersona( 6065): KNOX_SDCARD not a persona
I/SELinux ( 6065): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6065): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6065): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4554/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6065): TimaSignature is unavailable
D/ActivityThread( 6065): Added TimaKeyStore provider
W/ContextImpl( 6051): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6085): MountEmulatedStorage()
E/Zygote  ( 6085): v2
I/libpersona( 6085): KNOX_SDCARD checking this for 1000
I/libpersona( 6085): KNOX_SDCARD not a persona
I/SELinux ( 6085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 6085): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4316, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
E/SQLiteLog( 6051): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
E/SQLiteDatabase( 6051): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6051): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6051): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6051): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6051): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6051): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6051): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6051): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6051): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6051): Process: com.android.keychain, PID: 6051
E/AndroidRuntime( 6051): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6051): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6051): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6051): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6051): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 6051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6051): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/EmergencyMode( 1402): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1402): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.android.keychain
D/PreloadFilterInstaller( 6065): uses FILTER_DB_VER_1
E/SQLiteLog( 6065): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
D/TimaKeyStoreProvider( 6085): TimaSignature is unavailable
D/ActivityThread( 6085): Added TimaKeyStore provider
E/SQLiteDatabase( 6065): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6065): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6065): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6065): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6065): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6065): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6065): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6065): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6065): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6065): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6065): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6065): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6065): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6065): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6065): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6065): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6065): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6065): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6065): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6065): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6065): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6065): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6065): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6065): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6065): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6065): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6065): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6065): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6065): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6065): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6065): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6065): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
W/SQLiteOpenHelper( 6065): Opened filter.db in read-only mode
E/SQLiteLog( 6065): (284) automatic index on titles(filter_id)
```
