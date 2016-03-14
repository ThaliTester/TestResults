#### Test 6250909442642cd_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system,
D/SSRM:n  ( 1021): SIOP:: AP = 260
--------- beginning of main
D/AndroidRuntime( 6132): 
D/AndroidRuntime( 6132): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6132): CheckJNI is OFF
D/AndroidRuntime( 6132): readGMSProperty: start
D/AndroidRuntime( 6132): readGMSProperty: already setted!!
D/AndroidRuntime( 6132): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6132): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6132): readGMSProperty: end
D/AndroidRuntime( 6132): addProductProperty: start
E/SMD     (  295): DCD OFF
E/AffinityControl( 6132): AffinityControl: registerfunction enter
D/AndroidRuntime( 6132): Calling main entry com.android.commands.am.Am
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
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6144 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1484
E/Zygote  ( 6144): MountEmulatedStorage()
I/libpersona( 6144): KNOX_SDCARD checking this for 10167
E/Zygote  ( 6144): v2
I/libpersona( 6144): KNOX_SDCARD not a persona
D/AndroidRuntime( 6132): Shutting down VM
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6144): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6144): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6144): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6144): TimaSignature is unavailable
D/ActivityThread( 6144): Added TimaKeyStore provider
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1484): updateVisibility : ActivityRecord{577a04a token=android.os.BinderProxy@1d777cd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1484): onTrimMemory. Level: 20
I/WebViewFactory( 6144): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6144): Time to load native libraries: 2 ms (timestamps 667-669)
I/LibraryLoader( 6144): Expected native library version number "",actual native library version number ""
W/art     ( 6132): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6144): Binding Chromium to main looper Looper (main, tid 1) {2f9c5bbf}
,I/LibraryLoader( 6144): Expected native library version number "",actual native library version number ""
,I/chromium( 6144): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6144): Initializing chromium process, singleProcess=true
,W/art     ( 6144): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6144): ApplicationContext is null in ApplicationStatus
,W/chromium( 6144): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6144): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6144): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6144): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6144): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6144): Local Branch: 
I/Adreno-EGL( 6144): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6144): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6144):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6144): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6144): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6144): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6144): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 6144): CordovaWebView is running on device made by: samsung
,W/art     ( 6144): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6144): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{3be9da51 u0 com.test.thalitest/.MainActivity t23}
,D/OpenGLRenderer( 6144): Render dirty regions requested: true
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,W/chromium( 6144): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6144): updateVisibility : ActivityRecord{34f748a7 token=android.os.BinderProxy@98b61c1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6144): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6144): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1021): Focus entered window: 6144
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6144): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6144): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6144): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6144): Enabling debug mode 0
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,I/ActivityManager( 1021): Displayed Component not be shown by security: +670ms (total +1m43s553ms)
,W/ActivityManager( 1021): mDVFSHelper.release()
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{3be9da51 u0 com.test.thalitest/.MainActivity t23} time:221192
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6144): showStatusIcon on inactive InputConnection
I/Timeline( 6144): Timeline: Activity_idle id: android.os.BinderProxy@98b61c1 time:221207
,I/SamsungIME( 1812): getCurrentCandidateView
,D/SamsungIME( 1812): Dismiss ExpandCandiate
,I/SamsungIME( 1812): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1812): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1812): KeybaordView init() : load resources
,I/SamsungIME( 1812): getCurrentKeyboard
I/SamsungIME( 1812): getTextKeyboard
,W/BindingManager( 6144): Cannot call determinedVisibility() - never saw a connection for the pid: 6144,
,D/SamsungIME( 1812): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6144): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6144): JniHelper::setJavaVM(0xb807d448), pthread_self() = -1201829480
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d276784 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): setBluetoothMacAddress: 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6144): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6144): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6144): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6144): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f594833 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6144): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6144): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6144): setScanMode: 1 -> 2
,I/chromium( 6144): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6144): Initializing JXcore engine
W/jxcore-log( 6144): JXcore engine is ready
,E/audit   ( 1870): type=1400 msg=audit(1457937621.042:205): avc:  denied  { ioctl } for  pid=6196 comm="Thread-1059" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1870):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1870): type=1300 msg=audit(1457937621.042:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9e9fb8f8 items=0 ppid=320 ppcomm=main pid=6196 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1059" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1870): type=1320 msg=audit(1457937621.042:205): 
,W/jxcore-log( 6144): Starting JXcore engine
,W/jxcore-log( 6144): Platform android,
W/jxcore-log( 6144): 
W/jxcore-log( 6144): Process ARCH arm
W/jxcore-log( 6144): 
,E/SMD     (  295): DCD OFF,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6144): JXcore Cordova bridge is ready!
I/jxcore-log( 6144): 
,W/jxcore-log( 6144): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6144): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 6144): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 6144): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6144): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6144): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 6144): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1021): Set to : 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 6144
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1021): Killing 5107:com.google.android.talk/u0a102 (adj 15): empty #31
W/PluginManager( 6144): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1484): onRestart, Launcher: 808733162
,D/Launcher( 1484): onStart, Launcher: 808733162
D/Launcher.HomeView( 1484): onStart
,D/Launcher( 1484): onResume, Launcher: 808733162
,D/SettingsProvider( 1021): name = kids_home_mode
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10006
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,D/Launcher.HomeView( 1484): onResume
,D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1484): onResume
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/WallpaperManager( 1484): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1484): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1021): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/splitIntent( 1021): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,D/GalleryCacheReady( 4964): Receive : home resume
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/Recents_RecreateReceiver( 2531): onReceive by home
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1021): handle home activity for 0
,I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1021): post home show event for user 0,
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/Launcher.HomeView( 1484): onPause
D/Launcher( 1484): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5650): ui event
,V/TaskCloserActivity( 5622): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
I/SurfaceFlinger(  257): id=14 createSurf (540x960),1 flag=4, Mauncher
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
W/libprocessgroup( 1021): failed to open /acct/uid_10102/pid_5107/cgroup.procs: No such file or directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/InputDispatcher( 1021): Focus entered window: 1484
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101,
D/SRIB_DCS( 1484): log_dcs ThreadedRenderer::initialize entered! 
,E/Zygote  ( 6202): MountEmulatedStorage()
,I/libpersona( 6202): KNOX_SDCARD checking this for 10135
E/Zygote  ( 6202): v2
I/libpersona( 6202): KNOX_SDCARD not a persona
,I/SELinux ( 6202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6202 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/SELinux ( 6202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Launcher.HomeView( 1484): onStop
V/ActivityThread( 1484): updateVisibility : ActivityRecord{577a04a token=android.os.BinderProxy@1d777cd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/BroadcastQueue( 1021): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1484, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/StatusBar( 1180): Icon Only
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/PanelView( 1180): There is/are notification(s) 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,D/SamsungIME( 1812): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/IInputConnectionWrapper( 6144): showStatusIcon on inactive InputConnection
,D/TimaKeyStoreProvider( 6202): TimaSignature is unavailable
D/ActivityThread( 6202): Added TimaKeyStore provider
,I/Timeline( 1484): Timeline: Activity_idle id: android.os.BinderProxy@1d777cd time:223686
,W/ResourcesManager( 6202): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6202): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{34d2dd51 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:223706
W/ActivityManager( 1021): mDVFSHelper.release()
,I/splitIntent( 1021): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1021): Killing 4171:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 5622): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/AndroidRuntime( 6198): 
D/AndroidRuntime( 6198): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6198): CheckJNI is OFF
,D/AndroidRuntime( 6198): readGMSProperty: start
D/AndroidRuntime( 6198): readGMSProperty: already setted!!
D/AndroidRuntime( 6198): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6198): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6198): readGMSProperty: end
D/AndroidRuntime( 6198): addProductProperty: start
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4171/cgroup.procs: No such file or directory
,E/AffinityControl( 6198): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6198): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1021): START PACKAGE DELETE: observer{120332339},
D/PackageManager( 1021): pkg{<packageName>}
D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{2}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
,D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0,
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1021): !@killApplicatoin: 10167, uninstall pkg,
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 6144:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1021): Skipping PackageSetting{3278e2ec com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4070): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 832us total 40.359ms
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5984): Explicit concurrent mark sweep GC freed 405(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 1.149ms total 60.129ms
,E/SamsungIME( 1812): mOCRHelper is null
,W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
,W/ResourcesManager( 1460): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.5.123: ( 3742): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 07:40:22 GMT+01:00 2016
,D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
,V/NetworkStats( 1021): removeUidsLocked() for UIDs [10167]
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
V/NetworkStats( 1021): performPollLocked(flags=0x3)
,D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
W/TextServicesManagerService( 1021): no available spell checker services found
,V/NetworkStats( 1021): performPollLocked() took 15ms
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,I/KLMS-2.5.123: ( 3742): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): onCreate()
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3742): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 29946(2MB) AllocSpace objects, 16(260KB) LOS objects, 33% free, 23MB/35MB, paused 3.891ms total 196.562ms,
,I/art     ( 1021): WaitForGcToComplete blocked for 105.015ms for cause Explicit
,E/Zygote  ( 6231): MountEmulatedStorage()
E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD checking this for 10090
I/libpersona( 6231): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6231 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3742): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
,D/ActivityThread( 6231): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,D/RegisteredServicesCache( 1444): empty dynamic service
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): PACKAGE_REMOVED
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RCPManagerService( 1021): PackageReceiver onReceive()
,I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 6231): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6231): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6231): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6231): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6231): ElmAgentService : onCreate()
,D/elm:15121( 6231): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6231): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 6231): MDMBridge.getInstance()
,D/elm:15121( 6231): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6231): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): Notification App List is Null. Remove Notification.
,D/elm:15121( 6231): ElmAgentService : onDestroy().
,I/KLMS-2.5.123: ( 3742): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3742): KLMSIntentService(): onDestroy()
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 8701(431KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.490ms total 173.487ms
,W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1021): delete codoeFile: 
,D/AASAuninstall( 1021): userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10167 Target=com.test.thalitest
,D/PackageManager( 1021): result of delete: 1{120332339}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 6198): Shutting down VM
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1021): clearDefaults: com.test.thalitest
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10167
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,I/CrashAnrDetector( 1021): onPackageRemoved : com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10167
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1021): removeObsoleteFile: deleting file=23_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5698): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5698): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5698): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5698): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5868): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5868): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4964): PackagesMonitor onReceive :com.test.thalitest
,D/Mms/FreeMessageStatusReceiver( 5650): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1021): enable value -1
,I/TactileAssist( 1021): internal enable value -1
I/TactileAssist( 1021): intensity value -1
I/TactileAssist( 1021): saveAppList value true
,D/Mms/FreeMessageReceiverService( 5650): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 5650): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1021): List of disabled apps :
,W/art     ( 6198): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/PackageManager( 1021): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1021): userId{-1}
D/PackageManager( 1021): andCode{true}
,D/Compatibility( 5852): onReceive() it will make start service
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/Compatibility( 5852): onHandleIntent()
,D/Compatibility( 5852): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5852): found: 2
D/Compatibility( 5852): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5852): skipping ResolveInfo{1e41728c com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5852): considering ResolveInfo{370c9dd5 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5852): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5852): enabling receiver ResolveInfo{303449ea com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5852): enabling receiver ResolveInfo{9c4f4db com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  ( 6252): MountEmulatedStorage()
,E/Zygote  ( 6252): v2
I/libpersona( 6252): KNOX_SDCARD checking this for 10055
I/libpersona( 6252): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6252 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
I/SELinux ( 6252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5852): enabling receiver ResolveInfo{27d92b78 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5852): enabling receiver ResolveInfo{39864251 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 6252): TimaSignature is unavailable,
D/Compatibility( 5852): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/ActivityThread( 6252): Added TimaKeyStore provider
,I/art     (  320): Explicit concurrent mark sweep GC freed 8682(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 26.792ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 16.899ms
,D/UserAnalysis.PlaceProvider( 6252): PlaceProvider onCreate()
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 16.493ms
,D/UserAnalysis.SecureDbManager( 6252): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6252): SecurePlaceDbHelper() 
D/UserAnalysis( 6252): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6252): onCreate(),
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6252): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,E/SQLiteLog( 6252): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6252): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6252): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6252): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6252): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6252): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6252): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6252): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6252): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6252): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6252): 	at android.database.,sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6252): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6252): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6252): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6252): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6252): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6252): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6252): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/SQLiteOpenHelper( 6252): Opened privacy in read-only mode,
W/ContextImpl( 5884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/IntelligenceServiceApplication( 6252): no applications having user consent for prediction
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 6252): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 6252): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/SQLiteLog( 6252): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6252): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.,
E/SQLiteDatabase( 6252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228),
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,E/SQLiteDatabase( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6252): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6252): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6252): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6252): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6252): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6252): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6252): 	,at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6252): Shutting down VM
E/AndroidRuntime( 6252): FATAL EXCEPTION: main
E/AndroidRuntime( 6252): Process: com.samsung.android.intelligenceservice, PID: 6252
E/AndroidRuntime( 6252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6252): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6252): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6252): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6252): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6252): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6252): 	,at android.app.ActivityThread.main(ActivityThread.java:6145),
E/AndroidRuntime( 6252): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6252): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteLog( 5884): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
I/libpersona( 6270): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6270): MountEmulatedStorage()
,I/libpersona( 6270): KNOX_SDCARD not a persona

```
