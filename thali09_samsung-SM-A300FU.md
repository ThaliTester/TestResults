#### Test 757892685041341_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-06 14:35:10.703   297   297 E SMD     : DCD OFF
,07-06 14:35:11.243  6721  6721 D AndroidRuntime: 
07-06 14:35:11.243  6721  6721 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-06 14:35:11.243  6721  6721 D AndroidRuntime: CheckJNI is OFF
07-06 14:35:11.243  6721  6721 D AndroidRuntime: readGMSProperty: start
07-06 14:35:11.243  6721  6721 D AndroidRuntime: readGMSProperty: already setted!!
07-06 14:35:11.243  6721  6721 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-06 14:35:11.243  6721  6721 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-06 14:35:11.243  6721  6721 D AndroidRuntime: readGMSProperty: end
07-06 14:35:11.243  6721  6721 D AndroidRuntime: addProductProperty: start
07-06 14:35:11.373  6721  6721 E AffinityControl: AffinityControl: registerfunction enter
07-06 14:35:11.403  6721  6721 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-06 14:35:11.413  1015  1134 E PersonaManagerService: inState():  stateMachine is null !!
07-06 14:35:11.413  1015  1134 I PersonaManagerService: PersonaId don't exist
07-06 14:35:11.413  1015  1134 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-06 14:35:11.413  1015  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-06 14:35:11.423  1015  1134 W ActivityManager: mDVFSHelper.acquire()
07-06 14:35:11.433  1015  1134 D FocusedStackFrame: Set to : 0
07-06 14:35:11.433  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-06 14:35:11.433  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-06 14:35:11.443  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:35:11.443  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:35:11.443  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:35:11.443  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-06 14:35:11.453  6732  6732 E Zygote  : MountEmulatedStorage()
07-06 14:35:11.453  6732  6732 E Zygote  : v2
07-06 14:35:11.453  6732  6732 I libpersona: KNOX_SDCARD checking this for 10170
07-06 14:35:11.453  6732  6732 I libpersona: KNOX_SDCARD not a persona
07-06 14:35:11.453  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-06 14:35:11.453  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-06 14:35:11.453  1015  1134 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6732 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-06 14:35:11.453  1015  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-06 14:35:11.453  1015  1134 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-06 14:35:11.453   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-06 14:35:11.453  6732  6732 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-06 14:35:11.463  6732  6732 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:35:11.463  6732  6732 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-06 14:35:11.473  1015  1134 D InputDispatcher: Focused application set to: xxxx
07-06 14:35:11.483  1015  1134 D InputDispatcher: Focus left window: 1477
07-06 14:35:11.483  6721  6721 D AndroidRuntime: Shutting down VM
07-06 14:35:11.483  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 14:35:11.483  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 14:35:11.483  6732  6732 D TimaKeyStoreProvider: TimaSignature is unavailable
07-06 14:35:11.483  6732  6732 D ActivityThread: Added TimaKeyStore provider
07-06 14:35:11.483  1015  1470 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-06 14:35:11.493  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-06 14:35:11.503  1015  1470 D PersonaManager: isKioskContainerExistOnDevice
07-06 14:35:11.533  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-06 14:35:11.553   258   451 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-06 14:35:11.563   258  1095 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-06 14:35:11.563  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{31cb21d3 token=android.os.BinderProxy@36088b4a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-06 14:35:11.563  1477  1477 D Launcher: onTrimMemory. Level: 20
07-06 14:35:11.633  6732  6732 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-06 14:35:11.643  6732  6732 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1752-1754)
07-06 14:35:11.643  6732  6732 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 14:35:11.673  6732  6732 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bf3098b}
07-06 14:35:11.673  6732  6732 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 14:35:11.673  6732  6732 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 14:35:11.683  6721  6721 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-06 14:35:11.713  6732  6732 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-06 14:35:11.713  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:11.713  6732  6732 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-06 14:35:11.733  6732  6732 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-06 14:35:11.733  6732  6732 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-06 14:35:11.733  6732  6732 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-06 14:35:11.743  6732  6732 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-06 14:35:11.743  6732  6732 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-06 14:35:11.743  6732  6732 I Adreno-EGL: Build Date: 04/06/15 Mon
07-06 14:35:11.743  6732  6732 I Adreno-EGL: Local Branch: 
07-06 14:35:11.743  6732  6732 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-06 14:35:11.743  6732  6732 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-06 14:35:11.743  6732  6732 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-06 14:35:11.943  6732  6758 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-06 14:35:11.993  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:12.003  6732  6732 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-06 14:35:12.013  6732  6732 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-06 14:35:12.013  6732  6732 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-06 14:35:12.023  6732  6732 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-06 14:35:12.023  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:12.023  6732  6732 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-06 14:35:12.033  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{14ea8509 u0 com.test.thalitest/.MainActivity t44}
,07-06 14:35:12.093  6732  6771 D OpenGLRenderer: Render dirty regions requested: true
07-06 14:35:12.103  1015  5109 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-06 14:35:12.103  1015  5109 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-06 14:35:12.103  1015  5109 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-06 14:35:12.103  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
07-06 14:35:12.103  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-06 14:35:12.133  1015  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-06 14:35:12.163  6732  6732 V ActivityThread: updateVisibility : ActivityRecord{5105d62 token=android.os.BinderProxy@3ac2cb44 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-06 14:35:12.163  6732  6732 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-06 14:35:12.163  6732  6732 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-06 14:35:12.163   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-06 14:35:12.173  1015  1219 D InputDispatcher: Focus entered window: 6732
07-06 14:35:12.173  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-06 14:35:12.173  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
07-06 14:35:12.173  6732  6732 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-06 14:35:12.173  6732  6771 I OpenGLRenderer: Initialized EGL, version 1.4
07-06 14:35:12.183  6732  6771 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-06 14:35:12.183  6732  6771 D OpenGLRenderer: Enabling debug mode 0
07-06 14:35:12.203  1015  1470 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-06 14:35:12.203  1169  1169 I StatusBar: Icon Only
07-06 14:35:12.203  1169  1169 D PanelView: There is/are notification(s) 
07-06 14:35:12.203  1015  6774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-06 14:35:12.213  6732  6732 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-06 14:35:12.213  6732  6732 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ac2cb44 time:282324
07-06 14:35:12.233  1015  1045 I ActivityManager: Displayed Component not be shown by security: +699ms (total +2m49s340ms)
07-06 14:35:12.233  1015  1045 W ActivityManager: mDVFSHelper.release()
07-06 14:35:12.233  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14ea8509 u0 com.test.thalitest/.MainActivity t44} time:282340
07-06 14:35:12.233   258   451 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-06 14:35:12.233   258   453 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-06 14:35:12.263  1863  1863 I SamsungIME: getCurrentCandidateView
07-06 14:35:12.293  6732  6732 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6732
07-06 14:35:12.363  1863  1863 D SamsungIME: Dismiss ExpandCandiate
07-06 14:35:12.503  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
07-06 14:35:12.523  6732  6732 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-06 14:35:12.543  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
07-06 14:35:12.553  1863  1863 I SamsungIME: KeybaordView init() : load resources
07-06 14:35:12.583  1863  1863 I SamsungIME: getCurrentKeyboard
07-06 14:35:12.583  1863  1863 I SamsungIME: getTextKeyboard
07-06 14:35:12.583  6732  6732 I chromium: [INFO:CONSOLE(90)] "Uncaught SyntaxError: Unexpected token function", source: file:///android_asset/www/js/thali_main.js (90)
07-06 14:35:12.603  1863  1863 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
07-06 14:35:12.633  6732  6776 D jxcore_app_log: JniHelper::setJavaVM(0xb7fd02f0), pthread_self() = -1202539416
07-06 14:35:12.633  6732  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 14:35:12.633  6732  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 14:35:12.633  6732  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 14:35:12.633  6732  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 14:35:12.633  6732  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-06 14:35:12.633  6732  6776 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0ee312 added. We now have 1 listener(s)
07-06 14:35:12.643  6732  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
07-06 14:35:12.643  6732  6776 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
07-06 14:35:12.643  6732  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-06 14:35:12.643  6732  6776 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c15eb99 added. We now have 1 listener(s)
07-06 14:35:12.653  6732  6776 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-06 14:35:12.653  6732  6776 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
07-06 14:35:12.653  6732  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-06 14:35:12.653  6732  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-06 14:35:12.653  6732  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-06 14:35:12.653  6732  6776 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-06 14:35:12.663  6732  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-06 14:35:12.663  6732  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 14:35:12.663  6732  6776 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-06 14:35:12.663  6732  6776 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 14:35:12.663  6732  6776 D io.jxcore.node.ConnectivityMonitor: start: OK
07-06 14:35:12.673  6732  6776 I io.jxcore.node.LifeCycleMonitor: start: OK
07-06 14:35:12.673  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-06 14:35:12.673  6732  6732 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-06 14:35:12.693  6732  6732 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-06 14:35:13.243  6732  6784 W jxcore-log: Initializing JXcore engine
07-06 14:35:13.243  6732  6784 W jxcore-log: JXcore engine is ready
,07-06 14:35:13.293  2003  2003 E audit   : type=1400 msg=audit(1467808513.293:205): avc:  denied  { ioctl } for  pid=6784 comm="Thread-1213" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-06 14:35:13.293  2003  2003 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-06 14:35:13.293  2003  2003 E audit   : type=1300 msg=audit(1467808513.293:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9ee008f8 items=0 ppid=322 ppcomm=main pid=6784 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1213" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-06 14:35:13.293  2003  2003 E audit   : type=1320 msg=audit(1467808513.293:205): 
,07-06 14:35:13.303  6732  6784 W jxcore-log: Starting JXcore engine
,07-06 14:35:13.403  6732  6784 W jxcore-log: Platform android
07-06 14:35:13.403  6732  6784 W jxcore-log: 
07-06 14:35:13.403  6732  6784 W jxcore-log: Process ARCH arm
07-06 14:35:13.403  6732  6784 W jxcore-log: 
,07-06 14:35:13.603  6732  6784 I jxcore-log: JXcore Cordova bridge is ready!,
07-06 14:35:13.603  6732  6784 I jxcore-log: 
07-06 14:35:13.603  6732  6784 W jxcore-log: JXcore engine is started
,07-06 14:35:13.693   297   297 E SMD     : DCD OFF
,07-06 14:35:14.463  1015  3503 D SSRM:n  : SIOP:: AP = 290
,07-06 14:35:16.703   297   297 E SMD     : DCD OFF
,07-06 14:35:17.163  1015  1537 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:35:17.163  1015  1537 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:35:17.163  1015  1537 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:35:17.163  1015  1537 D BatteryService: stay LED for fully charged
07-06 14:35:17.163  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-06 14:35:17.173  1015  1015 I MotionRecognitionService: Plugged
07-06 14:35:17.173  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,07-06 14:35:17.173  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-06 14:35:17.173  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:35:17.173  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,07-06 14:35:17.173  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:35:17.193  3381  3381 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:35:17.193  3381  3472 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:35:17.213  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-06 14:35:17.213  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:35:17.213  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:35:17.723  1015  1319 E Watchdog: !@Sync 9
,07-06 14:35:18.663  1015  1047 I PowerManagerService: [PWL] Off : 225s ago
,07-06 14:35:19.693   297   297 E SMD     : DCD OFF
,07-06 14:35:21.443  1015  1053 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-06 14:35:22.703   297   297 E SMD     : DCD OFF
,07-06 14:35:23.693   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 14:35:24.503  1015  3503 D SSRM:n  : SIOP:: AP = 290
,07-06 14:35:24.683   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 14:35:25.683   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 14:35:25.713   297   297 E SMD     : DCD OFF,
,07-06 14:35:26.693   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,07-06 14:35:27.233  1015  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:35:27.233  1015  1488 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-06 14:35:27.233  1015  1488 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
07-06 14:35:27.233  1015  1488 D BatteryService: stay LED for fully charged
,07-06 14:35:27.233  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-06 14:35:27.233  1015  1015 I MotionRecognitionService: Plugged
07-06 14:35:27.233  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
07-06 14:35:27.243  1169  1169 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-06 14:35:27.243  1169  1169 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-06 14:35:27.243  1406  1406 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-06 14:35:27.243  1406  1406 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,07-06 14:35:27.253  3381  3381 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-06 14:35:27.253  3381  3472 D HeadsetStateMachine: Disconnected process message: 10
,07-06 14:35:27.263  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:35:27.263  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-06 14:35:27.263  1169  1169 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-06 14:35:27.683   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,07-06 14:35:28.683   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-06 14:35:28.713   297   297 E SMD     : DCD OFF,
,07-06 14:35:31.703   297   297 E SMD     : DCD OFF,
,07-06 14:35:32.133  1015  3561 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-06 14:35:34.543  1015  3503 D SSRM:n  : SIOP:: AP = 290,
,07-06 14:35:34.703   297   297 E SMD     : DCD OFF
,07-06 14:35:37.293  1015  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-06 14:35:37.703   297   297 E SMD     : DCD OFF
,07-06 14:35:40.713   297   297 E SMD     : DCD OFF,
,07-06 14:35:43.713   297   297 E SMD     : DCD OFF
,07-06 14:35:44.553  1015  3503 D SSRM:n  : SIOP:: AP = 290
,07-06 14:35:44.963  1015  1084 D TimaService: TIMA: TimaService scheduler is intialized. ,
07-06 14:35:44.963  1015  1084 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-06 14:35:44.963  1015  1083 D TimaService: TimaServiceHandler.handleMessage what =1
,07-06 14:35:44.973  1015  1084 I TLC_TIMA_PKM_initialize: initializing...
,07-06 14:35:44.973  1015  1084 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-06 14:35:44.973  1015  1084 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-06 14:35:44.973  1015  1084 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-06 14:35:44.973  1015  1084 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-06 14:35:44.973  1015  1084 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
07-06 14:35:44.973  1015  1084 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-06 14:35:44.973  1015  1084 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-06 14:35:44.973  1015  1084 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-06 14:35:44.973  1015  1084 D QSEECOMAPI: : App is not loaded in QSEE,
,07-06 14:35:45.003  1015  1084 D QSEECOMAPI: : Loaded image: APP id = 11
,07-06 14:35:45.013  1015  1084 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-06 14:35:45.013  1015  1084 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-06 14:35:46.713   297   297 E SMD     : DCD OFF
,07-06 14:35:46.883  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-06 14:35:46.883  1015  1084 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-06 14:35:46.893  1015  1084 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-06 14:35:46.893  1015  1084 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;

```
