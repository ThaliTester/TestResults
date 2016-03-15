#### Test 62509094058a2d4_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  291): DCD OFF
D/AndroidRuntime( 6136): 
D/AndroidRuntime( 6136): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6136): CheckJNI is OFF
D/AndroidRuntime( 6136): readGMSProperty: start
D/AndroidRuntime( 6136): readGMSProperty: already setted!!
D/AndroidRuntime( 6136): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6136): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6136): readGMSProperty: end
D/AndroidRuntime( 6136): addProductProperty: start
E/AffinityControl( 6136): AffinityControl: registerfunction enter
D/AndroidRuntime( 6136): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6148): MountEmulatedStorage()
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : -2122120936
E/Zygote  ( 6148): v2
I/libpersona( 6148): KNOX_SDCARD checking this for 10167
I/libpersona( 6148): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6148 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1479
I/SELinux ( 6148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 6136): Shutting down VM
I/SELinux ( 6148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6148): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6148): TimaSignature is unavailable
D/ActivityThread( 6148): Added TimaKeyStore provider
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{3facc052 token=android.os.BinderProxy@4061cdf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/WebViewFactory( 6148): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6148): Time to load native libraries: 2 ms (timestamps 1151-1153)
I/LibraryLoader( 6148): Expected native library version number "",actual native library version number ""
W/art     ( 6136): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6148): Binding Chromium to main looper Looper (main, tid 1) {5655966}
,I/LibraryLoader( 6148): Expected native library version number "",actual native library version number ""
,I/chromium( 6148): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6148): Initializing chromium process, singleProcess=true
,W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6148): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6148): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6148): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6148): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6148): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6148): Local Branch: 
I/Adreno-EGL( 6148): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6148): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6148):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6148): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6148): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6148): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 6148): CordovaWebView is running on device made by: samsung
,W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6148): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{b3425c1 u0 com.test.thalitest/.MainActivity t23}
,D/OpenGLRenderer( 6148): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 6148): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6148): updateVisibility : ActivityRecord{1550e3ee token=android.os.BinderProxy@22d453f0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6148): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6148): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 6148
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6148): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6148): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6148): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6148): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +668ms (total +1m44s588ms)
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{b3425c1 u0 com.test.thalitest/.MainActivity t23} time:221675
W/ActivityManager( 1017): mDVFSHelper.release()
W/IInputConnectionWrapper( 6148): showStatusIcon on inactive InputConnection
I/Timeline( 6148): Timeline: Activity_idle id: android.os.BinderProxy@22d453f0 time:221680
I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1828): getCurrentCandidateView
,W/BindingManager( 6148): Cannot call determinedVisibility() - never saw a connection for the pid: 6148
,D/SamsungIME( 1828): Dismiss ExpandCandiate
,I/SamsungIME( 1828): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1828): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1828): KeybaordView init() : load resources
,D/JsMessageQueue( 6148): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1828): getCurrentKeyboard
I/SamsungIME( 1828): getTextKeyboard
,D/SamsungIME( 1828): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6148): JniHelper::setJavaVM(0xb8370448), pthread_self() = -1198700328
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@358feb7f added. We now have 1 listener(s),
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): setBluetoothMacAddress: 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6148): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6148): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,V/AlarmManager( 1017): waitForAlarm result :8
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6148): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6148): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33b9ecaa added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6148): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6148): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6148): setScanMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6148): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6148): initialize: My bluetooth address is 08:EC:A9:50:75:41
,V/io.jxcore.node.ConnectivityMonitor( 6148): updateConnectivityInfo: FORCED notification:
V/io.jxcore.node.ConnectivityMonitor( 6148):     - is Wi-Fi Direct supported: true
V/io.jxcore.node.ConnectivityMonitor( 6148):     - is Bluetooth LE multiple advertisement supported: SUPPORTED
V/io.jxcore.node.ConnectivityMonitor( 6148):     - is Wi-Fi enabled: true
V/io.jxcore.node.ConnectivityMonitor( 6148):     - is Bluetooth enabled: true
V/io.jxcore.node.ConnectivityMonitor( 6148):     - BSSID name: f4:f2:6d:22:99:3e
V/io.jxcore.node.ConnectivityMonitor( 6148):     - is connected/connecting to active network: true
V/io.jxcore.node.ConnectivityMonitor( 6148):     - active network type is Wi-Fi: true
,D/io.jxcore.node.JXcoreExtension( 6148): notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
D/io.jxcore.node.ConnectivityMonitor( 6148): start: OK
,V/io.jxcore.node.ConnectivityMonitor( 6148): updateConnectivityInfo: No relevant state changes
,V/io.jxcore.node.ConnectivityMonitor( 6148): updateConnectivityInfo: No relevant state changes
,I/chromium( 6148): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,W/jxcore-log( 6148): Initializing JXcore engine
W/jxcore-log( 6148): JXcore engine is ready
,E/audit   ( 1890): type=1400 msg=audit(1458044341.135:205): avc:  denied  { ioctl } for  pid=6200 comm="Thread-1064" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1890):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1890): type=1300 msg=audit(1458044341.135:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9ebce8f8 items=0 ppid=313 ppcomm=main pid=6200 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1064" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1890): type=1320 msg=audit(1458044341.135:205): 
,W/jxcore-log( 6148): Starting JXcore engine
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/jxcore-log( 6148): Platform android
W/jxcore-log( 6148): 
W/jxcore-log( 6148): Process ARCH arm
W/jxcore-log( 6148): 
,I/jxcore-log( 6148): JXcore Cordova bridge is ready!
I/jxcore-log( 6148): 
,W/jxcore-log( 6148): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6148): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 6148): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,E/jxcore  ( 6148): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6148): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6148): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 6148): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 6148
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1017): Killing 5578:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
W/PluginManager( 6148): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,E/ActivityThread( 6148): Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@21c1c09b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6148): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@21c1c09b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6148): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
E/ActivityThread( 6148): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
E/ActivityThread( 6148): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
E/ActivityThread( 6148): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
E/ActivityThread( 6148): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
E/ActivityThread( 6148): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 6148): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
E/ActivityThread( 6148): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 6148): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 6148): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 6148): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 6148): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 6148): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 6148): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 6148): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 6148): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 6148): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6148): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6148): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityThread( 6148): Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3b106c38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6148): android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@3b106c38 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 6148): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
E/ActivityThread( 6148): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
E/ActivityThread( 6148): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
E/ActivityThread( 6148): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
E/ActivityThread( 6148): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
E/ActivityThread( 6148): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
E/ActivityThread( 6148): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
E/ActivityThread( 6148): 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
E/ActivityThread( 6148): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
E/ActivityThread( 6148): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
E/ActivityThread( 6148): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
E/ActivityThread( 6148): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
E/ActivityThread( 6148): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
E/ActivityThread( 6148): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
E/ActivityThread( 6148): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
E/ActivityThread( 6148): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
E/ActivityThread( 6148): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
E/ActivityThread( 6148): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
E/ActivityThread( 6148): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6148): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6148): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/Launcher( 1479): onRestart, Launcher: 203506941
,D/Launcher( 1479): onStart, Launcher: 203506941
,D/Launcher.HomeView( 1479): onStart
,D/Launcher( 1479): onResume, Launcher: 203506941,
D/SettingsProvider( 1017): name = kids_home_mode
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10006
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/Launcher.HomeView( 1479): onResume
,D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1479): onResume
D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
D/WallpaperManager( 1479): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 1017): Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
I/splitIntent( 1017): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,D/GalleryCacheReady( 4973): Receive : home resume
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,D/ActivityManager( 1017): handle home activity for 0
,I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/Recents_RecreateReceiver( 2536): onReceive by home
D/KnoxTimeoutHandler( 1017): post home show event for user 0
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/Launcher.HomeView( 1479): onPause
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/Launcher( 1479): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_5578/cgroup.procs: No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6204): MountEmulatedStorage(),
E/Zygote  ( 6204): v2
I/libpersona( 6204): KNOX_SDCARD checking this for 10139
I/libpersona( 6204): KNOX_SDCARD not a persona
,I/SELinux ( 6204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6204 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,D/Mms/UIEventReceiver( 5659): ui event
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  257): id=14 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/TimaKeyStoreProvider( 6204): TimaSignature is unavailable
,D/ActivityThread( 6204): Added TimaKeyStore provider
,E/Zygote  ( 6220): MountEmulatedStorage()
E/Zygote  ( 6220): v2
I/libpersona( 6220): KNOX_SDCARD checking this for 10135
I/libpersona( 6220): KNOX_SDCARD not a persona
,I/SELinux ( 6220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputDispatcher( 1017): Focus entered window: 1479
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1479): log_dcs ThreadedRenderer::initialize entered! 
,I/SELinux ( 6220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6220): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/ActivityThread( 1479): updateVisibility : ActivityRecord{3facc052 token=android.os.BinderProxy@4061cdf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1479): onStop
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6220 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,W/IInputConnectionWrapper( 6148): showStatusIcon on inactive InputConnection
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,I/art     (  313): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 22.847ms
,D/SamsungIME( 1828): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/TimaKeyStoreProvider( 6220): TimaSignature is unavailable
D/ActivityThread( 6220): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/BroadcastQueue( 1017): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.528ms
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.464ms
,I/Timeline( 1479): Timeline: Activity_idle id: android.os.BinderProxy@4061cdf time:224200
,W/ResourcesManager( 6220): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6220): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6220): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6220): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 6220): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{7d3e8c1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:224218
W/ActivityManager( 1017): mDVFSHelper.release()
,V/TaskCloserActivity( 6204): TaskCloserActivity enter()
,V/TaskCloserActivity( 6204): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,I/ActivityManager( 1017): Killing 5119:com.google.android.talk/u0a102 (adj 15): empty #31
,D/AndroidRuntime( 6201): 
D/AndroidRuntime( 6201): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6201): CheckJNI is OFF
D/AndroidRuntime( 6201): readGMSProperty: start
D/AndroidRuntime( 6201): readGMSProperty: already setted!!
D/AndroidRuntime( 6201): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6201): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6201): readGMSProperty: end
D/AndroidRuntime( 6201): addProductProperty: start
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,I/splitIntent( 1017): Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1017): Killing 4190:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,V/TaskCloserActivity( 6204): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,W/libprocessgroup( 1017): failed to open /acct/uid_10102/pid_5119/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_4190/cgroup.procs: No such file or directory
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/AffinityControl( 6201): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6201): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1017): START PACKAGE DELETE: observer{975055765},
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{2}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true,
,D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10167, uninstall pkg
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 6148:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1017): Skipping PackageSetting{34c4c2ab com.example.hello/10346} due to missing metadata
,W/ActivityManager( 1017): Spurious death for ProcessRecord{3a5e24aa 6148:com.test.thalitest/u0a167}, curProc for 6148: null
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4057): Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 803us total 28.139ms
,I/art     ( 5991): Explicit concurrent mark sweep GC freed 405(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 729us total 29.822ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1828): mOCRHelper is null
,I/KLMS-2.5.123: ( 3662): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 15 13:19:02 GMT+01:00 2016
,V/NetworkStats( 1017): removeUidsLocked() for UIDs [10167]
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x3)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,V/NetworkStats( 1017): performPollLocked() took 12ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3662): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1017): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1017): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     ( 1817): Explicit concurrent mark sweep GC freed 17333(944KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 8MB/13MB, paused 1.315ms total 84.695ms
,E/DataBuffer( 1817): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27aa60c2)
,E/Zygote  ( 6250): MountEmulatedStorage()
,E/Zygote  ( 6250): v2
I/libpersona( 6250): KNOX_SDCARD checking this for 10090
,I/libpersona( 6250): KNOX_SDCARD not a persona
,W/GeofencerStateMachine( 1817): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6250 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/KLMS-2.5.123: ( 3662): KLMSIntentService(): onCreate()
,E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3662): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3662): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): PACKAGE_REMOVED
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 50427(3MB) AllocSpace objects, 46(745KB) LOS objects, 33% free, 23MB/35MB, paused 6.532ms total 199.911ms
,D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
,D/ActivityThread( 6250): Added TimaKeyStore provider
,I/art     ( 1017): WaitForGcToComplete blocked for 117.813ms for cause Explicit
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): listeningToPackageRemoved().START
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1439): empty dynamic service
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 6250): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6250): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6250): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6250): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6250): ElmAgentService : onCreate()
,D/elm:15121( 6250): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6250): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6250): MDMBridge.getInstance()
D/elm:15121( 6250): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): Notification App List is Null. Remove Notification.
,D/elm:15121( 6250): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3662): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3662): KLMSIntentService(): onDestroy()
,D/elm:15121( 6250): ElmAgentService : onDestroy().
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 12798(657KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.030ms total 171.874ms
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
D/PackageManager( 1017): delete codoeFile: 
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10167
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10167 Target=com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
D/PackageManager( 1017): result of delete: 1{975055765}
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/AndroidRuntime( 6201): Shutting down VM
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10167
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,D/PackageManager( 1017): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1017): userId{-1}
D/PackageManager( 1017): andCode{true}
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1017): removeObsoleteFile: deleting file=23_task.xml
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest,
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest,
,I/PCWCLIENTTRACE_PushUtil( 5691): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5691): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5691): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5691): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5797): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5797): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4973): PackagesMonitor onReceive :com.test.thalitest
,D/Mms/FreeMessageStatusReceiver( 5659): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1017): enable value -1
I/TactileAssist( 1017): internal enable value -1
I/TactileAssist( 1017): intensity value -1
I/TactileAssist( 1017): saveAppList value true
,I/TactileAssist( 1017): List of disabled apps :
,D/Mms/FreeMessageReceiverService( 5659): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService( 5659): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/Compatibility( 5881): onReceive() it will make start service
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,D/Compatibility( 5881): onHandleIntent()
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Compatibility( 5881): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5881): found: 2
D/Compatibility( 5881): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5881): skipping ResolveInfo{384854a7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5881): considering ResolveInfo{20c11d54 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5881): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5881): enabling receiver ResolveInfo{c2144fd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000},
,W/art     ( 6201): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/Zygote  ( 6274): MountEmulatedStorage()
,E/Zygote  ( 6274): v2
I/libpersona( 6274): KNOX_SDCARD checking this for 10055
I/libpersona( 6274): KNOX_SDCARD not a persona
,I/SELinux ( 6274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 5881): enabling receiver ResolveInfo{25dda5f2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6274 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility( 5881): enabling receiver ResolveInfo{331b9443 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5881): enabling receiver ResolveInfo{18bcbac0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5881): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/TimaKeyStoreProvider( 6274): TimaSignature is unavailable
,D/ActivityThread( 6274): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 6274): PlaceProvider onCreate()
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/UserAnalysis.SecureDbManager( 6274): Key for secure DB is newly created,
D/UserAnalysis.SecurePlaceDbHelper( 6274): SecurePlaceDbHelper() 
D/UserAnalysis( 6274): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6274): onCreate(),
D/UserAnalysis.UserAnalysisBroadcastReceiver( 6274): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,E/SQLiteLog( 6274): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6274): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187),
E/SQLiteDatabase( 6274): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6274): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6274): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6274): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6274): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6274): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6274): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6274): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6274): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519),
E/SQLiteOpenHelper( 6274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6274): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6274): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
,E/SQLiteOpenHelper( 6274): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6274): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6274): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6274): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6274): 	at java.lang.reflect.Method.invoke(Native Method)
,E/SQLiteOpenHelper( 6274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/ContextImpl( 5898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/SQLiteOpenHelper( 6274): Opened privacy in read-only mode,
D/IntelligenceServiceApplication( 6274): no applications having user consent for prediction
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 6274): [PlaceDetection::stopService] Service stopped.,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 6274): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.,
E/SQLiteLog( 6274): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6274): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.,
E/SQLiteDatabase( 6274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6274): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6274): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6274): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6274): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6274): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6274): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6274): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6274): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime( 6274): Shutting down VM
I/libpersona( 6292): KNOX_SDCARD checking this for 1000
E/AndroidRuntime( 6274): FATAL EXCEPTION: main
E/AndroidRuntime( 6274): Process: com.samsung.android.intelligenceservice, PID: 6274
E/AndroidRuntime( 6274): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
,E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6274): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6274): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6274): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6274): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6274): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6274): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6274): 	,at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6274): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6274): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6274): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/libpersona( 6292): KNOX_SDCARD not a persona
,E/SQLiteLog( 5898): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6292 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6292): MountEmulatedStorage()
E/Zygote  ( 6292): v2
I/SELinux ( 6292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteDatabase( 5898): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5898): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5898): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5898): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5898): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5898): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5898): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5898): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5898): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5898): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5898): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5898): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5898): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
I/ActivityManager( 1017): Killing 5283:com.google.android.partnersetup/u0a14 (adj 15): empty #31
W/System.err( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5898): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 5898): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5898): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5898): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,I/Process ( 6274): Sending signal. PID: 6274 SIG: 9
,D/TimaKeyStoreProvider( 6292): TimaSignature is unavailable
,D/ActivityThread( 6292): Added TimaKeyStore provider
,E/DropBoxManagerService( 1017): Can't write: system_app_crash
E/DropBoxManagerService( 1017): java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1017): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1017): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1017): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1017): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1017): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1017): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1017): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1017): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1017): 	... 5 more

```
