#### Test 625090943f585e4_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  288): DCD OFF
D/AndroidRuntime( 6202): 
D/AndroidRuntime( 6202): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6202): CheckJNI is OFF
D/AndroidRuntime( 6202): readGMSProperty: start
D/AndroidRuntime( 6202): readGMSProperty: already setted!!
D/AndroidRuntime( 6202): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6202): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6202): readGMSProperty: end
D/AndroidRuntime( 6202): addProductProperty: start
E/AffinityControl( 6202): AffinityControl: registerfunction enter
D/AndroidRuntime( 6202): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1014): inState():  stateMachine is null !!
I/PersonaManagerService( 1014): PersonaId don't exist
I/ActivityManager( 1014): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1014): mDVFSHelper.acquire()
D/FocusedStackFrame( 1014): Set to : 0
D/PhoneWindow( 1014): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1014): *FMB* installDecor flags : -2122120936
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6214): MountEmulatedStorage()
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1014): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6214 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 1475
E/Zygote  ( 6214): v2
I/libpersona( 6214): KNOX_SDCARD checking this for 10167
I/libpersona( 6214): KNOX_SDCARD not a persona
D/AndroidRuntime( 6202): Shutting down VM
I/SELinux ( 6214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1014): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
E/SELinux ( 6214): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  306): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 22.169ms
D/TimaKeyStoreProvider( 6214): TimaSignature is unavailable
D/ActivityThread( 6214): Added TimaKeyStore provider
V/WindowManager( 1014): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.388ms
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
D/PersonaManager( 1014): isKioskContainerExistOnDevice
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.367ms
D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/9)
V/ActivityThread( 1475): updateVisibility : ActivityRecord{cfd6154 token=android.os.BinderProxy@2c4bc3a0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1475): onTrimMemory. Level: 20
I/WebViewFactory( 6214): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6214): Time to load native libraries: 2 ms (timestamps 1105-1107)
I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
W/art     ( 6202): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6214): Binding Chromium to main looper Looper (main, tid 1) {19982d48}
,I/LibraryLoader( 6214): Expected native library version number "",actual native library version number ""
,I/chromium( 6214): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6214): Initializing chromium process, singleProcess=true
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6214): ApplicationContext is null in ApplicationStatus
,W/chromium( 6214): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6214): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6214): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6214): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6214): Local Branch: 
I/Adreno-EGL( 6214): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6214): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6214):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6214): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6214): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6214): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 6214): CordovaWebView is running on device made by: samsung
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6214): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1014): Activity pause timeout for ActivityRecord{2cd8bd23 u0 com.test.thalitest/.MainActivity t23}
,D/OpenGLRenderer( 6214): Render dirty regions requested: true
,D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
,W/chromium( 6214): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6214): updateVisibility : ActivityRecord{3baade90 token=android.os.BinderProxy@38521142 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6214): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6214): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1014): Focus entered window: 6214
,D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6214): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6214): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6214): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6214): Enabling debug mode 0
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
,W/IInputConnectionWrapper( 6214): showStatusIcon on inactive InputConnection,
W/ActivityManager( 1014): mDVFSHelper.release()
I/Timeline( 6214): Timeline: Activity_idle id: android.os.BinderProxy@38521142 time:221697
I/ActivityManager( 1014): Displayed Component not be shown by security: +739ms (total +1m42s754ms)
I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{2cd8bd23 u0 com.test.thalitest/.MainActivity t23} time:221699
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1820): getCurrentCandidateView
,W/BindingManager( 6214): Cannot call determinedVisibility() - never saw a connection for the pid: 6214
,D/SamsungIME( 1820): Dismiss ExpandCandiate
,I/SamsungIME( 1820): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1820): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1820): KeybaordView init() : load resources
,D/JsMessageQueue( 6214): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1820): getCurrentKeyboard
,I/SamsungIME( 1820): getTextKeyboard
,D/SamsungIME( 1820): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6214): JniHelper::setJavaVM(0xb8674448), pthread_self() = -1195551808
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b8b0f9 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): setBluetoothMacAddress: 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6214): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6214): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6214): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6214): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2523ec added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6214): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6214): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6214): setScanMode: 1 -> 2
,I/chromium( 6214): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6214): Initializing JXcore engine
W/jxcore-log( 6214): JXcore engine is ready
,E/audit   ( 1923): type=1400 msg=audit(1457972390.541:205): avc:  denied  { ioctl } for  pid=6265 comm="Thread-1074" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1923):  SEPF_SM-A300FU_5.0.2_0027
,E/audit   ( 1923): type=1300 msg=audit(1457972390.541:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9ebff8f8 items=0 ppid=306 ppcomm=main pid=6265 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1074" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1923): type=1320 msg=audit(1457972390.541:205): 
,W/jxcore-log( 6214): Starting JXcore engine
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,W/jxcore-log( 6214): Platform android,
W/jxcore-log( 6214): 
W/jxcore-log( 6214): Process ARCH arm
W/jxcore-log( 6214): 
,E/SMD     (  288): DCD OFF,
,I/jxcore-log( 6214): JXcore Cordova bridge is ready!
I/jxcore-log( 6214): 
,W/jxcore-log( 6214): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6214): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 6214): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 6214): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6214): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6214): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 6214): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1014): Set to : 0
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1014): Focused application set to: xxxx
D/InputDispatcher( 1014): Focus left window: 6214
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1014): Killing 5627:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,W/PluginManager( 6214): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 17ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1014): mDVFSHelper.acquire()
,V/WindowManager( 1014): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/Launcher( 1475): onRestart, Launcher: 486869959
,D/Launcher( 1475): onStart, Launcher: 486869959
,D/Launcher.HomeView( 1475): onStart
,D/Launcher( 1475): onResume, Launcher: 486869959
,D/SettingsProvider( 1014): name = kids_home_mode
,D/SettingsProvider( 1014): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1014): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1014): selectionArgs: false
D/SettingsProvider( 1014): selectionArgs: 10006
,D/SecContentProvider( 1014): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1014): ret = -1
,D/Launcher.HomeView( 1475): onResume
,D/Launcher( 1475): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,D/MenuAppsGridFragment( 1475): onResume
,D/WallpaperManager( 1475): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1475): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1014): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9,
I/splitIntent( 1014): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
D/GalleryCacheReady( 5051): Receive : home resume
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
D/Recents_RecreateReceiver( 2408): onReceive by home
,W/BroadcastQueue( 1014): Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.activeapplicationwidget/com.sec.android.widgetapp.activeapplicationwidget.ProgramMonitorProvider}
W/BroadcastQueue( 1014): android.os.DeadObjectException
W/BroadcastQueue( 1014): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1014): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1014): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1014): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1014): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1014): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6270): MountEmulatedStorage()
,E/Zygote  ( 6270): v2
I/libpersona( 6270): KNOX_SDCARD checking this for 10139
I/libpersona( 6270): KNOX_SDCARD not a persona
,I/SELinux ( 6270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6270 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
D/ActivityManager( 1014): handle home activity for 0
I/WallpaperManagerService( 1014): switchPersonaWallpaper is called for personaId-0
W/ActivityManager( 1014): Spurious death for ProcessRecord{ea36575 6270:com.sec.android.widgetapp.activeapplicationwidget/u0a139}, curProc for 5627: null
D/KnoxTimeoutHandler( 1014): post home show event for user 0
D/PersonaManagerService( 1014): getPersonasForUser(): returning null!
D/ActivityManager( 1014): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1014): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1014): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1014):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1014): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1014): handleActiveUserChange for user 0
D/Launcher.HomeView( 1475): onPause
D/Launcher( 1475): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/SELinux ( 6270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
E/SELinux ( 6270): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/UIEventReceiver( 5697): ui event
,W/libprocessgroup( 1014): failed to open /acct/uid_10139/pid_5627/cgroup.procs: No such file or directory
,W/ActivityManager( 1014): userId = 0, bbcId = -10000,
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  257): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 6270): TimaSignature is unavailable
,D/ActivityThread( 6270): Added TimaKeyStore provider
E/Zygote  ( 6286): MountEmulatedStorage()
E/Zygote  ( 6286): v2
I/libpersona( 6286): KNOX_SDCARD checking this for 10135
I/libpersona( 6286): KNOX_SDCARD not a persona
,I/SELinux ( 6286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1014): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6286 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 6286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/StatusBarManagerService( 1014): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/SELinux ( 6286): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InputDispatcher( 1014): Focus entered window: 1475
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/BroadcastQueue( 1014): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1475, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
D/SRIB_DCS( 1475): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1014): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1014): setMouseCustomIcon IconType is same.101
,V/ActivityThread( 1475): updateVisibility : ActivityRecord{cfd6154 token=android.os.BinderProxy@2c4bc3a0 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1475): onStop
,D/InputMethodManagerService( 1014): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1014): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6214): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1820): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/TimaKeyStoreProvider( 6286): TimaSignature is unavailable
,D/ActivityThread( 6286): Added TimaKeyStore provider
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
,V/TaskCloserActivity( 6270): TaskCloserActivity enter()
,W/ResourcesManager( 6286): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6286): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 6286): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
V/TaskCloserActivity( 6270): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1014): Killing 4167:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/Timeline( 1475): Timeline: Activity_idle id: android.os.BinderProxy@2c4bc3a0 time:224102
,I/Timeline( 1014): Timeline: Activity_windows_visible id: ActivityRecord{32a06d19 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:224132
W/ActivityManager( 1014): mDVFSHelper.release()
,I/splitIntent( 1014): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1014): Killing 5245:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6270): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/AndroidRuntime( 6268): 
D/AndroidRuntime( 6268): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6268): CheckJNI is OFF
,D/AndroidRuntime( 6268): readGMSProperty: start
D/AndroidRuntime( 6268): readGMSProperty: already setted!!
D/AndroidRuntime( 6268): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6268): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6268): readGMSProperty: end
D/AndroidRuntime( 6268): addProductProperty: start
,D/WindowOrientationListener( 1014):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/PersonaManager( 1014): isKioskContainerExistOnDevice
,W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_4167/cgroup.procs: No such file or directory,
W/libprocessgroup( 1014): failed to open /acct/uid_10032/pid_5245/cgroup.procs: No such file or directory
,I/ServiceManager(  315): Waiting for service AtCmdFwd...,
,E/AffinityControl( 6268): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6268): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1014): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1014): START PACKAGE DELETE: observer{838469898}
D/PackageManager( 1014): pkg{<packageName>}
D/PackageManager( 1014): user{0}
D/PackageManager( 1014): caller{2000}
D/PackageManager( 1014): flags{2}
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1014): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1014): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1014): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1014): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1014): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1014): !@killApplicatoin: 10167, uninstall pkg
,I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,I/ActivityManager( 1014): Killing 6214:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,D/SSRM:n  ( 1014): SIOP:: AP = 290
,W/PackageSettings( 1014): Skipping PackageSetting{13b2fcf9 com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1014): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,W/ActivityManager( 1014): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 3957): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.169ms total 46.053ms
,I/InputReader( 1014): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 6033): Explicit concurrent mark sweep GC freed 425(28KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 919us total 69.003ms
,E/SamsungIME( 1820): mOCRHelper is null
,W/ResourcesManager( 1452): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/NetworkStats( 1014): removeUidsLocked() for UIDs [10167]
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
V/NetworkStats( 1014): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1014): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1014): UpdateStatsForKnox main else ---
,V/NetworkStats( 1014): performPollLocked() took 13ms
D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,I/KLMS-2.5.123: ( 3658): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 17:19:51 GMT+01:00 2016
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1014): currentTimeMillis() cache hit
,D/RegisteredServicesCache( 1441): empty dynamic service
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 61425(3MB) AllocSpace objects, 56(905KB) LOS objects, 33% free, 24MB/36MB, paused 2.745ms total 235.101ms
,I/art     ( 1014): WaitForGcToComplete blocked for 152.639ms for cause Explicit
,D/RCPManagerService( 1014): PackageReceiver onReceive()
,I/HarmonyEASService( 1014): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1014): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1014): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 1014): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10167
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1014): uID is 10167
V/EnterpriseBillingPolicy( 1014): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1014): getProfileForApplication - exit null : containerId = 0
D/TaskPersister( 1014): removeObsoleteFile: deleting file=23_task.xml
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1014): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1014): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1014): MSG_TYPE_APP_REMOVED::
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 14609(835KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.816ms total 157.744ms
,I/art     ( 1014): WaitForGcToComplete blocked for 290.247ms for cause Explicit
D/SecContentProvider2( 1014): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1014): mCursor = null
,W/GeofencerStateMachine( 1775): Ignoring removeGeofence because network location is disabled.
,D/EnterpriseDeviceManagerService( 1014): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1014): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1014): no available spell checker services found
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3658): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1014): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1014): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1014): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1014): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3658): KLMSIntentService(): onCreate(),
,I/KLMS-2.5.123: ( 3658): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6316): MountEmulatedStorage()
I/libpersona( 6316): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6316): v2
I/libpersona( 6316): KNOX_SDCARD not a persona
,I/SELinux ( 6316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1014): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6316 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3658): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3658): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3658): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3658): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3658): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6316): TimaSignature is unavailable
,D/ActivityThread( 6316): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3658): KLMSIntentService(): Notification App List is Null. Remove Notification.
,D/elm:15121( 6316): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6316): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6316): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6316): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3658): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,I/KLMS-2.5.123: ( 3658): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6316): ElmAgentService : onCreate()
,I/PCWCLIENTTRACE_PushUtil( 5745): SPPPushClient is installed : true
,I/KLMS-2.5.123: ( 3658): KLMSIntentService(): onDestroy()
,I/PCWCLIENTTRACE_PushUtil( 5745): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5745): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5745): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 6316): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6316): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6316): MDMBridge.getInstance()
D/elm:15121( 6316): MDMBridge.getAllLicenseInfoFromSDK()
,I/SA      ( 5815): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5815): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,D/elm:15121( 6316): MDMBridge.getAllLicenseInfoFromSDK()
,W/ResourceType( 1014): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1014): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1014): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6316): ElmAgentService : onDestroy().
,I/PackagesMonitor( 5051): PackagesMonitor onReceive :com.test.thalitest
,I/art     ( 1014): Explicit concurrent mark sweep GC freed 4808(245KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.279ms total 215.276ms
,D/PackageManager( 1014): delete codoeFile: 
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAuninstall( 1014): userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,I/AASA_removePackage( 1014): UID=10167 Target=com.test.thalitest
D/PackageManager( 1014): result of delete: 1{838469898}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Mms/FreeMessageStatusReceiver( 5697): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/Mms/FreeMessageReceiverService( 5697): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 5697): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1014): enable value -1
I/TactileAssist( 1014): internal enable value -1
I/TactileAssist( 1014): intensity value -1
I/TactileAssist( 1014): saveAppList value true
,D/AndroidRuntime( 6268): Shutting down VM
,I/TactileAssist( 1014): List of disabled apps :
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PackageManager( 1014): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1014): userId{-1}
D/PackageManager( 1014): andCode{true}
,W/Resources( 1014): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1014): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1014): onPackageRemoved : com.test.thalitest
,D/Compatibility( 5920): onReceive() it will make start service
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5920): onHandleIntent()
,D/Compatibility( 5920): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5920): found: 2
,D/Compatibility( 5920): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5920): skipping ResolveInfo{114767e1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5920): considering ResolveInfo{1613f906 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5920): default: com.sec.android.app.soundalive.SAControlPanelActivity
,E/Zygote  ( 6337): MountEmulatedStorage()
I/libpersona( 6337): KNOX_SDCARD checking this for 10055
E/Zygote  ( 6337): v2
I/libpersona( 6337): KNOX_SDCARD not a persona
,I/SELinux ( 6337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6337 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
D/Compatibility( 5920): enabling receiver ResolveInfo{1d050bc7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/SELinux ( 6337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Compatibility( 5920): enabling receiver ResolveInfo{7a6d5f4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5920): enabling receiver ResolveInfo{5f1a11d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5920): enabling receiver ResolveInfo{20669f92 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5920): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 6337): TimaSignature is unavailable
,D/ActivityThread( 6337): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6337): PlaceProvider onCreate()
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/UserAnalysis.SecureDbManager( 6337): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6337): SecurePlaceDbHelper() 
D/UserAnalysis( 6337): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6337): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 6337): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,W/ContextImpl( 5941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/IntelligenceServiceApplication( 6337): no applications having user consent for prediction
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
,W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 6354): MountEmulatedStorage()
E/Zygote  ( 6354): v2
I/libpersona( 6354): KNOX_SDCARD checking this for 1000
I/libpersona( 6354): KNOX_SDCARD not a persona
,I/SELinux ( 6354): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1014): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6354 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 6354): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6354): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ServiceManager(  315): Waiting for service AtCmdFwd...
,I/ActivityManager( 1014): Killing 5342:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6354): TimaSignature is unavailable
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,D/ActivityThread( 6354): Added TimaKeyStore provider
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false,
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
W/art     ( 6268): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
W/ResourcesManager( 6354): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,D/BluetoothAdapter( 6337): cancelDiscovery
,D/BluetoothAdapterProperties( 2656): mDiscovering is false
E/BluetoothAdapterService( 2656): This is not a scanning status. cancelDiscovery() will be not called.
D/BluetoothAdapter( 6337): cancelDiscovery = true
,V/PlaceDetection v1.0.19 ( 6337): [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
V/PlaceDetection v1.0.19 ( 6337): [PlaceDetection::stopService] Service stopped.
,V/PlaceDetection v1.0.19 ( 6337): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/RCPManager( 6354):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 1014):  in createShortcut() for packageName: com.test.thalitest userId0,
D/RCPManagerService( 1014): queryAllProviders():  providerCallBack is not register for 0
,D/FilterInstaller( 5957): onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest,
W/ContextImpl( 5957): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,I/FilterInstaller( 5957): FilterPackageService : ACTION_PACKAGE_REMOVED
,I/FilterInstaller( 5957): FilterPackageService : ACTION_REMOVED
D/FilterUnInstaller( 5957): before removeFromFS
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6371): MountEmulatedStorage()
,E/Zygote  ( 6371): v2
I/libpersona( 6371): KNOX_SDCARD checking this for 10095
I/libpersona( 6371): KNOX_SDCARD not a persona
,I/ActivityManager( 1014): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6371 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6371): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6371): TimaSignature is unavailable,
,D/ActivityThread( 6371): Added TimaKeyStore provider
,E/Zygote  ( 6388): MountEmulatedStorage(),
I/libpersona( 6388): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6388): v2
I/libpersona( 6388): KNOX_SDCARD not a persona
I/SELinux ( 6388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1014): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup( 1014): failed to open /acct/uid_10014/pid_5342/cgroup.procs: No such file or directory,
,I/SELinux ( 6388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 6337): (10) unixWrite() File Descriptor : 26 gets errno : 9
,E/SQLiteDatabase( 6337): Error inserting timestamp=1457972392686 message=Predictor: service stopped by removePlaceCategories()
E/SQLiteDatabase( 6337): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6337): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6337): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
E/SQLiteDatabase( 6337): 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
E/SQLiteDatabase( 6337): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6337): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6337): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6337): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6337): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6337): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6337): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6337): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/UserAnalysis( 6337): It failed to insert to dump_log table
,D/TimaKeyStoreProvider( 6388): TimaSignature is unavailable
D/ActivityThread( 6388): Added TimaKeyStore provider
D/PreloadFilterInstaller( 6371): uses FILTER_DB_VER_1
E/SQLiteLog( 6371): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6371): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 6371): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6371): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6371): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6371): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteDatabase( 6371): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteDatabase( 6371): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteDatabase( 6371): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteDatabase( 6371): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6371): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6371): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6371): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6371): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6371): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6371): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6371): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6371): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6371): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6371): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/SQLiteOpenHelper( 6371): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 6371): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6371): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6371): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6371): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:423)
E/SQLiteOpenHelper( 6371): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.loadExternalFilters(PreloadFilterInstaller.java:122)
E/SQLiteOpenHelper( 6371): 	at com.samsung.android.provider.filterprovider.PreloadFilterInstaller.installFilters(PreloadFilterInstaller.java:100)
E/SQLiteOpenHelper( 6371): 	at com.samsung.android.provider.filterprovider.FilterProvider.onCreate(FilterProvider.java:179)
E/SQLiteOpenHelper( 6371): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteOpenHelper( 6371): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteOpenHelper( 6371): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteOpenHelper( 6371): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteOpenHelper( 6371): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteOpenHelper( 6371): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6371): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6371): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6371): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6371): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6371): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6371): Opened filter.db in read-only mode
E/SQLiteLog( 6371): (284) automatic index on titles(filter_id)
W/ContextImpl( 6388): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1014): userId = 0, bbcId = -10000
W/ActivityManager( 1014): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1014): NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1014): checkUser: useridlist=null, currentuser=0
E/SQLiteLog( 6388): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6388): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 6388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6388): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/SQLiteDatabase( 6388): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/SQLiteDatabase( 6388): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6388): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Zygote  ( 6404): MountEmulatedStorage()
I/libpersona( 6404): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6404): v2
I/libpersona( 6404): KNOX_SDCARD not a persona
E/AndroidRuntime( 6388): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 6388): Process: com.android.keychain, PID: 6388
E/AndroidRuntime( 6388): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6388): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6388): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6388): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6388): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:564)
E/AndroidRuntime( 6388): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:558)
E/AndroidRuntime( 6388): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6388): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 6404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1014): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6404 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SQLiteLog( 6371): (284) automatic index on titles(filter_id)
E/SELinux ( 6404): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1014): isApplicationStateBlocked userId 0 pkgname com.android.keychain
I/Process ( 6388): Sending signal. PID: 6388 SIG: 9
E/DropBoxManagerService( 1014): Can't write: system_app_crash
E/DropBoxManagerService( 1014): java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1014): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1014): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1014): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1014): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1014): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1014): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1014): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1014): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1014): 	... 5 more
,D/TimaKeyStoreProvider( 6404): TimaSignature is unavailable
,D/ActivityThread( 6404): Added TimaKeyStore provider

```
