#### Test 62509094cfda267_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  290): DCD OFF
D/AndroidRuntime( 6070): 
D/AndroidRuntime( 6070): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6070): CheckJNI is OFF
D/AndroidRuntime( 6070): readGMSProperty: start
D/AndroidRuntime( 6070): readGMSProperty: already setted!!
D/AndroidRuntime( 6070): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6070): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6070): readGMSProperty: end
D/AndroidRuntime( 6070): addProductProperty: start
E/AffinityControl( 6070): AffinityControl: registerfunction enter
D/AndroidRuntime( 6070): Calling main entry com.android.commands.am.Am
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
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : -2122120936
E/Zygote  ( 6082): MountEmulatedStorage()
E/Zygote  ( 6082): v2
I/libpersona( 6082): KNOX_SDCARD checking this for 10167
I/libpersona( 6082): KNOX_SDCARD not a persona
I/SELinux ( 6082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6082 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1484
D/AndroidRuntime( 6070): Shutting down VM
I/SELinux ( 6082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6082): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6082): TimaSignature is unavailable
D/ActivityThread( 6082): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1484): updateVisibility : ActivityRecord{35c3e938 token=android.os.BinderProxy@3b53ba56 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1484): onTrimMemory. Level: 20
I/WebViewFactory( 6082): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6082): Time to load native libraries: 1 ms (timestamps 3059-3060)
I/LibraryLoader( 6082): Expected native library version number "",actual native library version number ""
W/art     ( 6070): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6082): Binding Chromium to main looper Looper (main, tid 1) {3cd1693e}
I/LibraryLoader( 6082): Expected native library version number "",actual native library version number ""
I/chromium( 6082): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6082): Initializing chromium process, singleProcess=true
,W/art     ( 6082): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6082): ApplicationContext is null in ApplicationStatus
,W/chromium( 6082): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6082): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6082): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6082): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6082): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6082): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6082): Local Branch: 
I/Adreno-EGL( 6082): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6082): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6082):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6082): Attempt to remove local handle scope entry from IRT, ignoring
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/AwContents( 6082): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6082): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6082): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 6082): CordovaWebView is running on device made by: samsung
,W/art     ( 6082): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6082): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{593fe33 u0 com.test.thalitest/.MainActivity t23}
,D/OpenGLRenderer( 6082): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 6082): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6082): updateVisibility : ActivityRecord{30027cc6 token=android.os.BinderProxy@3c749b08 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6082): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6082): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 6082
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6082): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6082): Initialized EGL, version 1.4
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6082): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6082): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +738ms (total +1m55s198ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{593fe33 u0 com.test.thalitest/.MainActivity t23} time:233659
,I/SamsungIME( 1879): getCurrentCandidateView
,W/IInputConnectionWrapper( 6082): showStatusIcon on inactive InputConnection
,I/Timeline( 6082): Timeline: Activity_idle id: android.os.BinderProxy@3c749b08 time:233666
,I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
,D/SamsungIME( 1879): Dismiss ExpandCandiate
,W/BindingManager( 6082): Cannot call determinedVisibility() - never saw a connection for the pid: 6082
,I/SamsungIME( 1879): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1879): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1879): KeybaordView init() : load resources
,I/SamsungIME( 1879): getCurrentKeyboard
,I/SamsungIME( 1879): getTextKeyboard
,D/SamsungIME( 1879): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6082): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6082): JniHelper::setJavaVM(0xb7eb7448), pthread_self() = -1203608288
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ecbd77 added. We now have 1 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): setBluetoothMacAddress: 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6082): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6082): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6082): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6082): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10a48102 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6082): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6082): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): setAdvertiseTxPowerLevel: 2 -> 3,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6082): setScanMode: 1 -> 2
,I/chromium( 6082): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/art     ( 6082): Suspending all threads took: 7.903ms,
,W/jxcore-log( 6082): Initializing JXcore engine
,W/jxcore-log( 6082): JXcore engine is ready
,I/art     ( 6082): Background sticky concurrent mark sweep GC freed 43501(4MB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 9.148ms total 52.746ms
,E/audit   ( 1878): type=1400 msg=audit(1457945687.645:205): avc:  denied  { ioctl } for  pid=6133 comm="Thread-1034" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1878):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1878): type=1300 msg=audit(1457945687.645:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9edb18f8 items=0 ppid=307 ppcomm=main pid=6133 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1034" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1878): type=1320 msg=audit(1457945687.645:205): ,
,W/jxcore-log( 6082): Starting JXcore engine
,W/jxcore-log( 6082): Platform android
W/jxcore-log( 6082): 
W/jxcore-log( 6082): Process ARCH arm
W/jxcore-log( 6082): 
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/jxcore-log( 6082): JXcore Cordova bridge is ready!
I/jxcore-log( 6082): 
,W/jxcore-log( 6082): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6082): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 6082): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 6082): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6082): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6082): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 6082): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 6082
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020): Killing 4461:com.google.android.music:main/u0a108 (adj 15): empty #31
W/PluginManager( 6082): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8)
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1484): onRestart, Launcher: 329455797
,D/Launcher( 1484): onStart, Launcher: 329455797
,D/Launcher.HomeView( 1484): onStart
,D/Launcher( 1484): onResume, Launcher: 329455797
,D/SettingsProvider( 1020): name = kids_home_mode
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/Launcher.HomeView( 1484): onResume
,D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1484): onResume
,D/ActivityManager( 1020): handle home activity for 0
,I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1020): post home show event for user 0
D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,D/Launcher.HomeView( 1484): onPause,
,D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,I/splitIntent( 1020): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,I/splitIntent( 1020): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4974): Receive : home resume
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/SurfaceFlinger(  259): id=15 createSurf (540x960),1 flag=4, Mauncher
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2534): onReceive by home,
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/InputDispatcher( 1020): Focus entered window: 1484
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,V/TaskCloserActivity( 5909): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
D/SRIB_DCS( 1484): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
D/Mms/UIEventReceiver( 4729): ui event
W/ActivityManager( 1020): userId = 0, bbcId = -10000
V/ActivityThread( 1484): updateVisibility : ActivityRecord{35c3e938 token=android.os.BinderProxy@3b53ba56 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
D/Launcher.HomeView( 1484): onStop
D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/IInputConnectionWrapper( 6082): showStatusIcon on inactive InputConnection
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
D/SamsungIME( 1879): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
,D/PersonaManager( 1020): isKioskContainerExistOnDevice
W/libprocessgroup( 1020): failed to open /acct/uid_10108/pid_4461/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
W/BroadcastQueue( 1020): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1484, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,I/splitIntent( 1020): Queue : backgroundsplit_0 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/Timeline( 1484): Timeline: Activity_idle id: android.os.BinderProxy@3b53ba56 time:235941
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
V/TaskCloserActivity( 5909): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{2b4ae116 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:235964
W/ActivityManager( 1020): mDVFSHelper.release()
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AndroidRuntime( 6136): 
D/AndroidRuntime( 6136): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6136): CheckJNI is OFF
,D/AndroidRuntime( 6136): readGMSProperty: start
D/AndroidRuntime( 6136): readGMSProperty: already setted!!
D/AndroidRuntime( 6136): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6136): readGMSProperty: could not set the property(default)!!
,D/AndroidRuntime( 6136): readGMSProperty: end
D/AndroidRuntime( 6136): addProductProperty: start
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
,E/AffinityControl( 6136): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6136): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1020): START PACKAGE DELETE: observer{424257029}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{2}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10167, uninstall pkg,
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 6082:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1020): Skipping PackageSetting{54f7e9b com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4027): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 809us total 25.154ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SamsungIME( 1879): mOCRHelper is null
,I/KLMS-2.5.123: ( 3668): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 09:54:48 GMT+01:00 2016
,V/NetworkStats( 1020): removeUidsLocked() for UIDs [10167]
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x3)
,I/art     ( 5257): Explicit concurrent mark sweep GC freed 11523(827KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 958us total 94.700ms
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,V/NetworkStats( 1020): performPollLocked() took 7ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/RegisteredServicesCache( 1453): empty dynamic service
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 58323(3MB) AllocSpace objects, 56(905KB) LOS objects, 33% free, 24MB/36MB, paused 2.848ms total 197.478ms
,I/art     ( 1020): WaitForGcToComplete blocked for 156.531ms for cause Explicit
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10167
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10167
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
D/TaskPersister( 1020): removeObsoleteFile: deleting file=23_task.xml
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 15098(855KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.288ms total 159.534ms
I/art     ( 1020): WaitForGcToComplete blocked for 268.405ms for cause Explicit
,W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1020): no available spell checker services found
,I/KLMS-2.5.123: ( 3668): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3668): KLMSIntentService(): onCreate()
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3668): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3668): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6154): MountEmulatedStorage()
I/libpersona( 6154): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6154): v2
I/libpersona( 6154): KNOX_SDCARD not a persona
,I/SELinux ( 6154): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6154): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6154 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
I/KLMS-2.5.123: ( 3668): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/SELinux ( 6154): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3668): KLMSIntentService(): PACKAGE_REMOVED,
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3668): KLMSIntentService(): listeningToPackageRemoved().START
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3668): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6154): TimaSignature is unavailable
,D/ActivityThread( 6154): Added TimaKeyStore provider
,D/elm:15121( 6154): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6154): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6154): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/KLMS-2.5.123: ( 3668): KLMSIntentService(): Notification App List is Null. Remove Notification.
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6154): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6154): ElmAgentService : onCreate()
,D/elm:15121( 6154): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6154): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6154): MDMBridge.getInstance()
D/elm:15121( 6154): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6154): MDMBridge.getAllLicenseInfoFromSDK()
,I/PCWCLIENTTRACE_PushUtil( 5677): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5677): sales region : global
,I/KLMS-2.5.123: ( 3668): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/KLMS-2.5.123: ( 3668): KLMSIntentService(): listeningToPackageRemoved().END
,I/PCWCLIENTTRACE_PushUtil( 5677): getPushTypeList : [SPP, GCM]
I/KLMS-2.5.123: ( 3668): KLMSIntentService(): onDestroy()
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5677): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1020): stay LED for fully charged
,D/elm:15121( 6154): ElmAgentService : onDestroy().
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 5627(335KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 4.377ms total 223.623ms
,V/HeadsetService( 2635): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2635): Disconnected process message: 10
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 5781): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5781): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackagesMonitor( 4974): PackagesMonitor onReceive :com.test.thalitest
,D/Mms/FreeMessageStatusReceiver( 4729): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PackageManager( 1020): delete codoeFile: 
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,I/AASA_removePackage( 1020): UID=10167 Target=com.test.thalitest
,D/Mms/FreeMessageReceiverService( 4729): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 4729): onHandleIntent: ACTION_PACKAGE_REMOVED
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/TactileAssist( 1020): enable value -1
D/PackageManager( 1020): result of delete: 1{424257029}
I/TactileAssist( 1020): internal enable value -1
I/TactileAssist( 1020): intensity value -1
I/TactileAssist( 1020): saveAppList value true
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/AndroidRuntime( 6136): Shutting down VM
,I/TactileAssist( 1020): List of disabled apps :
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1020): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1020): userId{-1}
D/PackageManager( 1020): andCode{true}
,D/UsbSettingsManager( 1020): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1020): onPackageRemoved : com.test.thalitest
,D/Compatibility( 5739): onReceive() it will make start service
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5739): onHandleIntent()
,D/Compatibility( 5739): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,E/Zygote  ( 6175): MountEmulatedStorage()
,E/Zygote  ( 6175): v2
I/libpersona( 6175): KNOX_SDCARD checking this for 10055
I/libpersona( 6175): KNOX_SDCARD not a persona
,I/SELinux ( 6175): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6175): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6175): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6175 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 5739): found: 2
D/Compatibility( 5739): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5739): skipping ResolveInfo{172ee39f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5739): considering ResolveInfo{144b8cec com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5739): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5739): enabling receiver ResolveInfo{13a318b5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5739): enabling receiver ResolveInfo{1ef6db4a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5739): enabling receiver ResolveInfo{b281abb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5739): enabling receiver ResolveInfo{1fda8bd8 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5739): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 6175): TimaSignature is unavailable
,D/ActivityThread( 6175): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/UserAnalysis.PlaceProvider( 6175): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 6175): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6175): SecurePlaceDbHelper() 
D/UserAnalysis( 6175): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6175): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 6175): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 5083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/IntelligenceServiceApplication( 6175): no applications having user consent for prediction
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 6192): MountEmulatedStorage()
,E/Zygote  ( 6192): v2
,I/libpersona( 6192): KNOX_SDCARD checking this for 1000
I/libpersona( 6192): KNOX_SDCARD not a persona
,I/SELinux ( 6192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 6192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6192): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 5121:com.google.android.talk/u0a102 (adj 15): empty #31,
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,D/TimaKeyStoreProvider( 6192): TimaSignature is unavailable
,D/ActivityThread( 6192): Added TimaKeyStore provider,
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
W/art     ( 6136): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false,
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,W/ResourcesManager( 6192): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 6175): cancelDiscovery
,D/BluetoothAdapterProperties( 2635): mDiscovering is false
,E/BluetoothAdapterService( 2635): This is not a scanning status. cancelDiscovery() will be not called.
,D/BluetoothAdapter( 6175): cancelDiscovery = true
V/PlaceDetection v1.0.19 ( 6175): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6175): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/RCPManager( 6192):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 1020):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 1020): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5796): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,W/ContextImpl( 5796): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5796): FilterPackageService : ACTION_PACKAGE_REMOVED
I/FilterInstaller( 5796): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5796): before removeFromFS
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6209): MountEmulatedStorage()
,E/Zygote  ( 6209): v2
I/libpersona( 6209): KNOX_SDCARD checking this for 10095
I/libpersona( 6209): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6209 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 6209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
,I/SELinux ( 6209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/Zygote  ( 6219): MountEmulatedStorage()
,W/libprocessgroup( 1020): failed to open /acct/uid_10102/pid_5121/cgroup.procs: No such file or directory
E/Zygote  ( 6219): v2
I/libpersona( 6219): KNOX_SDCARD checking this for 1000
I/libpersona( 6219): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 6209): TimaSignature is unavailable
D/ActivityThread( 6209): Added TimaKeyStore provider
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6219 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6219): TimaSignature is unavailable
,D/ActivityThread( 6219): Added TimaKeyStore provider
,D/PreloadFilterInstaller( 6209): uses FILTER_DB_VER_1,
,E/SQLiteLog( 6209): (284) automatic index on titles(filter_id)
,W/ContextImpl( 6219): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,E/SQLiteLog( 6209): (284) automatic index on titles(filter_id)
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 6219): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6219): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.,
E/SQLiteDatabase( 6219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6219): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6219): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6219): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6219): 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6219): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 6219): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6219): Process: com.android.keychain, PID: 6219
E/AndroidRuntime( 6219): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699),
E/AndroidRuntime( 6219): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6219): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6219): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6219): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6219): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558),
E/AndroidRuntime( 6219): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6219): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6219): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6219): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Zygote  ( 6240): MountEmulatedStorage()
E/Zygote  ( 6240): v2
I/libpersona( 6240): KNOX_SDCARD checking this for 1000
I/libpersona( 6240): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/SELinux ( 6240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,I/SELinux ( 6240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/Process ( 6219): Sending signal. PID: 6219 SIG: 9
,E/SELinux ( 6240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6240): TimaSignature is unavailable
,D/ActivityThread( 6240): Added TimaKeyStore provider
,E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1020): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1020): 	... 5 more
,I/ActivityManager( 1020): Killing 4197:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/FilterUnInstaller( 5796): FilterUninstaller.java : removeFromDB()
,D/FilterProvider( 6209): delete when PACKAGE_NAME : 2002 
D/FilterProvider( 6209): packageName : com.test.thalitest
,W/ContextImpl( 5796): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
,I/ActivityManager( 1020): Process com.android.keychain (pid 6219)(adj 5) has died(127,633),
W/ActivityManager( 1020): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
,I/ActivityManager( 1020): Killing 5286:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0

```
