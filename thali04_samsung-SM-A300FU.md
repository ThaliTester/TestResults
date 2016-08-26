#### Test 8286536244f8192_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main,
08-26 14:59:41.074   291   291 E SMD     : DCD OFF
08-26 14:59:41.344  6807  6807 D AndroidRuntime: 
08-26 14:59:41.344  6807  6807 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:59:41.354  6807  6807 D AndroidRuntime: CheckJNI is OFF
08-26 14:59:41.354  6807  6807 D AndroidRuntime: readGMSProperty: start
08-26 14:59:41.354  6807  6807 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:59:41.354  6807  6807 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:59:41.354  6807  6807 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 14:59:41.354  6807  6807 D AndroidRuntime: readGMSProperty: end
08-26 14:59:41.354  6807  6807 D AndroidRuntime: addProductProperty: start
08-26 14:59:41.504  6807  6807 E AffinityControl: AffinityControl: registerfunction enter
08-26 14:59:41.524  6807  6807 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 14:59:41.544  1017  4338 E PersonaManagerService: inState():  stateMachine is null !!
08-26 14:59:41.544  1017  4338 I PersonaManagerService: PersonaId don't exist
08-26 14:59:41.544  1017  4338 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 14:59:41.544  1017  4338 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-26 14:59:41.564  1017  4338 W ActivityManager: mDVFSHelper.acquire()
08-26 14:59:41.574   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-26 14:59:41.574   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-26 14:59:41.584  1017  4338 D FocusedStackFrame: Set to : 0
08-26 14:59:41.584  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 14:59:41.584  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 14:59:41.594  1017  4338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:41.594  1017  4338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:41.594  1017  4338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:41.594  1017  4338 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:41.594  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:59:41.594  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 14:59:41.604   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-26 14:59:41.604  6820  6820 E Zygote  : MountEmulatedStorage()
08-26 14:59:41.604  6820  6820 E Zygote  : v2
08-26 14:59:41.604  6820  6820 I libpersona: KNOX_SDCARD checking this for 10171
08-26 14:59:41.604  6820  6820 I libpersona: KNOX_SDCARD not a persona
08-26 14:59:41.604  6820  6820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 14:59:41.614  6820  6820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:41.614  1017  4338 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6820 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:59:41.614  1017  4338 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 14:59:41.614  1017  4338 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:59:41.614  1017  4338 D InputDispatcher: Focused application set to: xxxx
08-26 14:59:41.614  6820  6820 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 14:59:41.614  1017  4338 D InputDispatcher: Focus left window: 1497
08-26 14:59:41.614  6807  6807 D AndroidRuntime: Shutting down VM
08-26 14:59:41.634  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:59:41.634  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:41.644  6820  6820 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:59:41.644  6820  6820 D ActivityThread: Added TimaKeyStore provider
08-26 14:59:41.644  1017  3262 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 14:59:41.644  1017  1017 V ActivityManager: Display changed displayId=0
08-26 14:59:41.654  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:59:41.664  1017  3262 D PersonaManager: isKioskContainerExistOnDevice
08-26 14:59:41.674  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 14:59:41.714   258  1039 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-26 14:59:41.714   258   443 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-26 14:59:41.714  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{37d9e80 token=android.os.BinderProxy@297a593a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 14:59:41.724  1497  1497 D Launcher: onTrimMemory. Level: 20
08-26 14:59:41.774  6820  6820 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 14:59:41.794  6820  6820 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7720-7722)
08-26 14:59:41.794  6820  6820 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 14:59:41.824  6807  6807 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 14:59:41.834  6820  6820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10fce5d8}
08-26 14:59:41.834  6820  6820 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 14:59:41.844  6820  6820 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 14:59:41.884  6820  6820 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
08-26 14:59:41.894  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:41.904  6820  6820 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 14:59:41.934  6820  6820 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:59:41.934  6820  6820 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:59:41.934  6820  6820 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:59:41.934  6820  6820 I Adreno-EGL: Local Branch: 
08-26 14:59:41.934  6820  6820 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:59:41.934  6820  6820 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:59:41.934  6820  6820 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 14:59:42.034  6820  6820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 14:59:42.044  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 14:59:42.044  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
08-26 14:59:42.054  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 14:59:42.054  6820  6820 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
08-26 14:59:42.164  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{38896a62 u0 com.test.thalitest/.MainActivity t2}
08-26 14:59:42.184  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:42.204  6820  6820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 14:59:42.214  6820  6820 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 14:59:42.214  6820  6820 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-26 14:59:42.224  6820  6820 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-26 14:59:42.224  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:42.224  6820  6820 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 14:59:42.354  6820  6860 D OpenGLRenderer: Render dirty regions requested: true
08-26 14:59:42.354  1017  1221 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 14:59:42.354  1017  1221 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 14:59:42.354  1017  1221 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 14:59:42.354  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 14:59:42.354  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 14:59:42.364  6820  6847 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
08-26 14:59:42.374  6820  6820 V ActivityThread: updateVisibility : ActivityRecord{a603038 token=android.os.BinderProxy@1cdb4795 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 14:59:42.374  6820  6820 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:59:42.374  6820  6820 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 14:59:42.384  1017  1320 E Watchdog: !@Sync 3
08-26 14:59:42.394   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-26 14:59:42.394  1017  4338 D InputDispatcher: Focus entered window: 6820
08-26 14:59:42.404  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:59:42.404  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:59:42.404  6820  6820 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 14:59:42.404  6820  6860 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 14:59:42.404  6820  6860 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-26 14:59:42.404  6820  6860 D OpenGLRenderer: Enabling debug mode 0
08-26 14:59:42.434  1017  4339 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 14:59:42.434  1017  6865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-26 14:59:42.434  1176  1176 I StatusBar: Icon Only
08-26 14:59:42.434  1176  1176 D PanelView: There is/are notification(s) 
08-26 14:59:42.444  1017  1048 I ActivityManager: Displayed Component not be shown by security: +780ms (total +864ms)
08-26 14:59:42.444  1017  1048 W ActivityManager: mDVFSHelper.release()
08-26 14:59:42.444  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{38896a62 u0 com.test.thalitest/.MainActivity t2} time:108379
08-26 14:59:42.454   258  1039 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-26 14:59:42.454   258   446 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-26 14:59:42.464  6820  6820 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-26 14:59:42.464  6820  6820 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1cdb4795 time:108391
08-26 14:59:42.464  1868  1868 I SamsungIME: getCurrentCandidateView
08-26 14:59:42.494  6820  6820 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6820
08-26 14:59:42.564  1868  1868 D SamsungIME: Dismiss ExpandCandiate
,08-26 14:59:42.694  6820  6820 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:59:42.714  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:59:42.764  1868  1868 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:59:42.774  1868  1868 I SamsungIME: KeybaordView init() : load resources
,08-26 14:59:42.774  6820  6864 D jxcore_app_log: JniHelper::setJavaVM(0xb87f42b0), pthread_self() = -1193820848
,08-26 14:59:42.784  6820  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:59:42.784  6820  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:59:42.784  6820  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:59:42.784  6820  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:59:42.784  6820  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 14:59:42.784  6820  6864 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e28d54e added. We now have 1 listener(s)
,08-26 14:59:42.794  6820  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-26 14:59:42.794  6820  6864 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 14:59:42.794  6820  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:59:42.794  6820  6864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:59:42.794  1868  1868 I SamsungIME: getCurrentKeyboard
08-26 14:59:42.794  1868  1868 I SamsungIME: getTextKeyboard
,08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 14:59:42.804  6820  6864 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d9e4005 added. We now have 1 listener(s)
08-26 14:59:42.804  6820  6864 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:59:42.804  6820  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:59:42.804  6820  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:59:42.804  6820  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 14:59:42.814  6820  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 14:59:42.814  6820  6864 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 14:59:42.814  6820  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:59:42.814  6820  6864 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-26 14:59:42.824  6820  6864 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:59:42.824  6820  6864 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:59:42.824  6820  6864 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 14:59:42.824  6820  6864 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:59:42.824  1868  1868 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 14:59:42.824  6820  6864 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:59:42.824  6820  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:42.824  6820  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:59:42.854  6820  6820 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:59:43.454  6820  6873 W jxcore-log: Initializing JXcore engine
08-26 14:59:43.454  6820  6873 W jxcore-log: JXcore engine is ready
,08-26 14:59:43.514  2007  2007 E audit   : type=1400 msg=audit(1472216383.514:205): avc:  denied  { ioctl } for  pid=6873 comm="Thread-1265" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 14:59:43.514  2007  2007 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:43.514  2007  2007 E audit   : type=1300 msg=audit(1472216383.514:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f6ed8f8 items=0 ppid=312 ppcomm=main pid=6873 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1265" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 14:59:43.514  2007  2007 E audit   : type=1320 msg=audit(1472216383.514:205): 
,08-26 14:59:43.524  6820  6873 W jxcore-log: Starting JXcore engine
,08-26 14:59:43.634  6820  6873 W jxcore-log: Platform android
08-26 14:59:43.634  6820  6873 W jxcore-log: 
08-26 14:59:43.634  6820  6873 W jxcore-log: Process ARCH arm
08-26 14:59:43.634  6820  6873 W jxcore-log: 
,08-26 14:59:43.694   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 14:59:43.694   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 14:59:43.844  6820  6873 I jxcore-log: JXcore Cordova bridge is ready!,
08-26 14:59:43.844  6820  6873 I jxcore-log: 
08-26 14:59:43.844  6820  6873 W jxcore-log: JXcore engine is started
,08-26 14:59:43.844  6820  6864 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 14:59:43.854  6820  6820 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:59:44.074   291   291 E SMD     : DCD OFF,
,08-26 14:59:47.074  1017  1050 I PowerManagerService: [PWL] Off : 50s ago,
,08-26 14:59:47.074   291   291 E SMD     : DCD OFF,
,08-26 14:59:47.204  1017  3332 D SSRM:n  : SIOP:: AP = 340,
,08-26 14:59:48.694   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:59:49.694   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:59:50.084   291   291 E SMD     : DCD OFF,
,08-26 14:59:50.284  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:59:50.284  1017  3262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 14:59:50.284  1017  3262 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 14:59:50.284  1017  3262 D BatteryService: stay LED for fully charged
,08-26 14:59:50.284  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:59:50.284  1017  1017 I MotionRecognitionService: Plugged
,08-26 14:59:50.294  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:59:50.294  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 14:59:50.294  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 14:59:50.294  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:59:50.294  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 14:59:50.314  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:59:50.314  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:59:50.324  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:59:50.324  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:59:50.324  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 14:59:50.564  5660  5660 D FactoryTest: Not factory mode
,08-26 14:59:50.564  5660  5660 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 14:59:50.564  5660  5660 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-26 14:59:50.564  5660  5660 D MTPRx   : still no open session command from host, so toast
,08-26 14:59:50.564  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-26 14:59:50.564  5660  5660 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 14:59:50.564  5660  5660 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:116499,
,08-26 14:59:50.574  1017  1135 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 14:59:50.574  1017  1135 I PersonaManagerService: PersonaId don't exist
08-26 14:59:50.574  1017  1135 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 14:59:50.574  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-26 14:59:50.574  1017  1135 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:59:50.574  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:59:50.574  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 14:59:50.584  1017  1135 W ActivityManager: mDVFSHelper.acquire()
,08-26 14:59:50.604  1017  1135 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:59:50.604  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:59:50.604  1017  1135 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 14:59:50.604  1017  1135 D InputDispatcher: Focused application set to: xxxx
08-26 14:59:50.604  1017  1135 D InputDispatcher: Focus left window: 6820
,08-26 14:59:50.614  5660  5660 E MTPRx   : started activity for popup
,08-26 14:59:50.624  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:59:50.624  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:59:50.634  5660  5660 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 14:59:50.634  5660  5660 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-26 14:59:50.644  5660  5660 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 14:59:50.644  5660  5660 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:59:50.644  5660  5660 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:59:50.644  5660  5660 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:59:50.664  5660  5660 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 14:59:50.664  1017  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 14:59:50.664  1017  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 14:59:50.664  1017  1495 D InputDispatcher: Focused application set to: xxxx
,08-26 14:59:50.674  1017  1495 D InputDispatcher: Focus entered window: 6820
,08-26 14:59:50.674  1017  4337 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:59:50.674  1017  4337 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@9c1b47d attribute=null, token = android.os.BinderProxy@d5c2e0d
,08-26 14:59:50.674  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:59:50.674  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:59:50.694   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:59:50.714  5660  5660 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 14:59:50.724  5660  5660 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-26 14:59:50.724  5660  5660 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 14:59:50.744  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 14:59:50.754  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 14:59:50.754  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 14:59:50.754  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 14:59:50.754  1017  1536 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 14:59:50.754  1017  1536 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 14:59:50.754  1017  1536 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 14:59:50.754  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 14:59:50.754  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 14:59:50.764  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:59:50.764  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 14:59:50.774  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@20d774a1 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@136ff48e, 16908290=android.view.AbsSavedState$1@136ff48e}, android:focusedViewId=100}]}],
08-26 14:59:50.774  6820  6820 V ActivityThread: updateVisibility : ActivityRecord{a603038 token=android.os.BinderProxy@1cdb4795 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 14:59:50.774  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 14:59:50.774  6820  6820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 14:59:50.774  6820  6820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-26 14:59:50.774  6820  6820 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1cdb4795 time:116705
,08-26 14:59:50.784  1017  1322 D PersonaManager: isKioskContainerExistOnDevice,
,08-26 14:59:51.634  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 14:59:51.694   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:59:52.694   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:59:53.084   291   291 E SMD     : DCD OFF
,08-26 14:59:53.584  1017  1043 W ActivityManager: mDVFSHelper.release()
,08-26 14:59:53.704   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 14:59:54.074  1017  1096 V AlarmManager: waitForAlarm result :4
,08-26 14:59:54.074  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.114  1999  1999 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 14:59:54.144  1017  3262 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:59:54.144  1017  3262 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.144  1017  3262 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:54.144  1017  3262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.144  1017  3262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.194  4748  4748 D ConnectivityManager: CallingUid : 10011, CallingPid : 4748
,08-26 14:59:54.204  1017  1135 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 14:59:54.204  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-26 14:59:54.204  1017  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 14:59:54.204  1017  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-26 14:59:54.204  4748  6881 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:59:54.254  4748  6882 W DriveInitializer: Background init thread started
,08-26 14:59:54.294   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 14:59:54.294   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:59:54.294  4748  6882 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 14:59:54.334  1999  1999 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-26 14:59:54.384  1017  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:59:54.384  1017  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.384  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:54.384  1017  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.384  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.394  4748  6882 W DriveInitializer: Background init thread ended
,08-26 14:59:54.564  1017  3262 I art     : Explicit concurrent mark sweep GC freed 35353(1981KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.514ms total 154.338ms
,08-26 14:59:54.564  1017  3262 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-26 14:59:54.564  1017  3262 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.584  1017  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:59:54.584  1017  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.584  1017  1322 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:54.584  1017  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.584  1017  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.614  4748  6890 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-26 14:59:54.614  4748  6890 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 14:59:54.654  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:59:54.694  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:54.694  1017  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.694  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.784  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:59:54.784  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.794  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:54.794  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.794  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.824  1017  4339 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:59:54.824  1017  4339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 14:59:54.824  1017  4339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:54.824  1017  4339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.824  1017  4339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.874  1017  1221 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:54.874  1017  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:54.874  1017  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.874  1017  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.894  1017  4337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:54.904  1017  4337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:54.904  1017  4337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.904  1017  4337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:54.954  1017  1512 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:54.964  1017  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:54.964  1017  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:54.964  1017  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-26 14:59:54.964  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:59:54.964  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:59:54.964  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 14:59:54.964  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:59:54.974  6895  6895 E Zygote  : MountEmulatedStorage()
08-26 14:59:54.974  6895  6895 E Zygote  : v2
08-26 14:59:54.974  6895  6895 I libpersona: KNOX_SDCARD checking this for 10011
,08-26 14:59:54.974  6895  6895 I libpersona: KNOX_SDCARD not a persona
,08-26 14:59:54.974  6895  6895 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 14:59:54.984  6895  6895 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 14:59:54.984  6895  6895 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 14:59:54.984  1017  1512 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6895 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 14:59:55.034  6895  6895 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:59:55.034  6895  6895 D ActivityThread: Added TimaKeyStore provider
,08-26 14:59:55.054  6895  6895 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 14:59:55.054  6895  6895 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 14:59:55.084  6895  6895 I MultiDex: VM with version 2.1.0 has multidex support
08-26 14:59:55.084  6895  6895 I MultiDex: install
08-26 14:59:55.084  6895  6895 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 14:59:55.124  6895  6895 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...,
,08-26 14:59:55.184  6895  6895 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 14:59:55.184  6895  6895 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@198f4214: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 14:59:55.184  6895  6895 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 14:59:55.204  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 14:59:55.214  6895  6895 D ChimeraCfgMgr: Reading stored module config
,08-26 14:59:55.214  1017  3262 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:55.214  1017  3262 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.214  1017  3262 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:55.214  1017  3262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.244  1017  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:55.244  1017  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.244  1017  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:55.244  1017  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.304  1017  4337 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 14:59:55.304  1017  4337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 14:59:55.304  1017  4337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.304  1017  4337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:59:55.304  1017  4337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.304  1999  1999 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=296a0bd1-03d6-412e-a19f-62146cb821e9
,08-26 14:59:55.314  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:59:55.314  1999  1999 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:59:55.324  6895  6913 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 14:59:55.334  6895  6895 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 14:59:55.334  6895  6895 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 14:59:55.354  1017  4338 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:55.354  1017  4338 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.364  1017  4338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:59:55.364  1017  4338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.424   286   707 D WVCdm   : Instantiating CDM.
,08-26 14:59:55.424   286   807 I WVCdm   : CdmEngine::OpenSession
,08-26 14:59:55.424   286   807 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 14:59:55.454   286   807 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 14:59:55.464  4293  4913 I art     : Explicit concurrent mark sweep GC freed 1424(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 685us total 26.157ms
,08-26 14:59:55.474   286   807 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-26 14:59:55.534   286   807 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 14:59:55.534   286   286 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-26 14:59:55.534   286   286 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,08-26 14:59:55.534   286   286 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-26 14:59:55.544   286   286 D WVCdm   : PrepareKeyRequest: nonce=841043706
,08-26 14:59:55.574  6895  6908 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 14:59:55.574  6895  6908 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 14:59:55.574  6895  6908 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 14:59:55.574  6895  6908 I System.out: (HTTPLog)-Thread-1245-1035248369: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 14:59:55.574  6895  6908 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:55.574   281   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:59:55.574   281   975 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 14:59:55.594  1999  2148 W GCoreFlp: No location to return for getLastLocation()
,08-26 14:59:55.624  6895  6908 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:59:55.634  6895  6908 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6895, getuid(): 10011,
,08-26 14:59:55.634  1017  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:55.634  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:55.634  1017  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:55.634  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.634  1017  1221 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:55.644  1017  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.644  1017  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:55.644  1017  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.644  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:55.644  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.644  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:55.644  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.654  4748  6891 D UdcContextInitService: registered all accounts: true
,08-26 14:59:55.654  1999  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:59:55.664  1999  2167 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 14:59:55.904  1999  2167 I art     : Explicit concurrent mark sweep GC freed 52354(2MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.409ms total 67.839ms
,08-26 14:59:55.924  1017  4338 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:59:55.924  1017  4338 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-26 14:59:55.924  1017  4338 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:55.924  1017  4338 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:55.924  1017  4338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:55.944  6895  6908 I qtaguid : Untagging socket 30
,08-26 14:59:56.084   291   291 E SMD     : DCD OFF
,08-26 14:59:56.154  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 14:59:56.584  6925  6925 I dex2oat : ----------------------------------------------------
08-26 14:59:56.584  6925  6925 I dex2oat : <SS>: S T A R T I N G . . .
08-26 14:59:56.584  6925  6925 I dex2oat : <SS>: Zip is absent. Canceled.
08-26 14:59:56.584  6925  6925 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 14:59:56.644  6925  6925 I dex2oat : dex2oat took 59.671ms (threads: 4)
,08-26 14:59:56.654  6895  6908 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:59:56.654  6895  6908 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:59:56.654  6895  6908 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:59:56.654  6895  6908 I Adreno-EGL: Local Branch: 
08-26 14:59:56.654  6895  6908 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:59:56.654  6895  6908 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:59:56.654  6895  6908 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:59:56.724  6895  6908 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:59:56.724  6895  6908 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:59:56.724  6895  6908 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:59:56.724  6895  6908 I Adreno-EGL: Local Branch: 
08-26 14:59:56.724  6895  6908 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:59:56.724  6895  6908 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:59:56.724  6895  6908 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:59:56.794  6895  6908 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-26 14:59:56.794  6895  6908 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:59:56.794  6895  6908 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:59:56.794  6895  6908 I Adreno-EGL: Local Branch: 
08-26 14:59:56.794  6895  6908 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:59:56.794  6895  6908 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:59:56.794  6895  6908 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:59:56.914  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:59:56.914  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 14:59:56.914  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:56.924  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:56.924  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:56.944  1999  6893 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 14:59:56.944  1999  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:56.944  1999  6893 I System.out: (HTTPLog)-Static: isShipBuild true
,08-26 14:59:56.954  1999  6893 I System.out: (HTTPLog)-Thread-270-397264683: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 14:59:56.954  1999  6893 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:56.954   281   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:59:56.954   281   975 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 14:59:56.954  1999  6893 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:59:56.954  1999  6893 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1999, getuid(): 10011
,08-26 14:59:57.004  1999  6893 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1999, getuid(): 10011
,08-26 14:59:57.104   286   707 I WVCdm   : CdmEngine::CloseSession
,08-26 14:59:57.104   286   707 I WVCdm   : L3 Terminate.
,08-26 14:59:57.224  1017  3332 D SSRM:n  : SIOP:: AP = 380
,08-26 14:59:57.234  1999  2167 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 14:59:57.234  1999  2167 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 14:59:57.244  1999  2167 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 14:59:55.771+0200, stopTime=2016-08-26 14:59:57.248+0200, duration=1477ms
,08-26 14:59:57.244  1999  6938 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:57.254   281   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:59:57.254   281   975 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 14:59:57.254  1999  6938 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:59:57.254  1999  6938 I qtaguid : Tagging socket 65 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1999, getuid(): 10011
,08-26 14:59:57.294  1017  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 14:59:57.304  1999  6938 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1999, getuid(): 10011
,08-26 14:59:57.674  1999  6938 I qtaguid : Untagging socket 65
,08-26 14:59:57.704  1017  1484 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:59:57.704  1017  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-26 14:59:57.714  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.714  1017  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.714  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.734  1999  2167 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 14:59:57.794  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.804  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.804  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.804  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.824  1017  1221 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.824  1017  1221 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.824  1017  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.824  1017  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.884  1017  4337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.884  1017  4337 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.884  1017  4337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.884  1017  4337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.884  1999  6943 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-26 14:59:57.884  1999  6941 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 14:59:57.884  1017  1135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.884  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.894  1017  1135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.894  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.914  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.914  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.914  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.914  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.914  1999  6943 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 14:59:57.914  1999  6941 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 14:59:57.914  1017  1495 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.914  1017  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:59:57.914  1017  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:59:57.914  1017  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.944  1017  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:59:57.944  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:59:57.944  1017  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:59:57.944  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:59:57.944  1999  6943 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 14:59:57.944  1999  6941 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 14:59:57.944  1999  6941 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-26 14:59:57.964  1999  6941 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 14:59:58.014  1017  1030 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:59:58.044  1999  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:58.054   281   975 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 14:59:58.054   281   975 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 14:59:58.054  1999  6941 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:59:58.054  1999  6941 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1999, getuid(): 10011
,08-26 14:59:58.094  1999  6941 I qtaguid : Tagging socket 80 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1999, getuid(): 10011
,08-26 14:59:58.374  1017  1512 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:59:58.384  1999  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:58.384  1999  6941 I qtaguid : Tagging socket 77 with tag 1106541400000000{285627412,0} for uid -1, pid: 1999, getuid(): 10011
,08-26 14:59:58.544  1017  1135 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:59:58.554  1999  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:58.554  1999  6941 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1999, getuid(): 10011
,08-26 14:59:58.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:59:58.724  1017  1536 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:59:58.744  1999  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:58.744  1999  6941 I qtaguid : Tagging socket 77 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1999, getuid(): 10011
,08-26 14:59:58.934  1017  1496 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:59:58.944  1999  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:58.944  1999  6941 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1999, getuid(): 10011
,08-26 14:59:59.084   291   291 E SMD     : DCD OFF
,08-26 14:59:59.364  1999  6937 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:59:59.364  1999  6937 I qtaguid : Tagging socket 65 with tag 1000310200000000{268448002,0} for uid 10011, pid: 1999, getuid(): 10011
,08-26 14:59:59.564  1999  6937 I qtaguid : Untagging socket 65
,08-26 14:59:59.564  1999  2167 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-26 14:59:59.594  1017  4339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 14:59:59.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:59:59.994  1017  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:00:00.334  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:00.344  1017  3262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:00:00.344  1017  3262 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:00:00.344  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:00:00.344  1017  3262 D BatteryService: stay LED for fully charged
08-26 15:00:00.344  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:00:00.344  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:00.344  1017  1017 I MotionRecognitionService: Plugged
08-26 15:00:00.344  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:00:00.344  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:00:00.344  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:00.364  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:00:00.364  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:00.374  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:00.374  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:00.374  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:00.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:01.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:01.904  1017  1221 I ActivityManager: Killing 6519:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 15:00:02.084   291   291 E SMD     : DCD OFF
,08-26 15:00:02.254  6820  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:00:02.254  6820  6873 I jxcore-log: 
,08-26 15:00:02.254  6820  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-26 15:00:02.254  6820  6873 I jxcore-log: 
,08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:00:02.264  6820  6873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:00:02.264  6820  6873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:00:02.264  6820  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:00:02.264  6820  6873 I jxcore-log: 
,08-26 15:00:02.264  6820  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:00:02.264  6820  6873 I jxcore-log: 
,08-26 15:00:02.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:02.724  6820  6873 I jxcore-log: Running unit tests
08-26 15:00:02.724  6820  6873 I jxcore-log: 
,08-26 15:00:02.724  6820  6873 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-26 15:00:02.724  6820  6873 I jxcore-log: Failed to execute UT.
08-26 15:00:02.724  6820  6873 I jxcore-log: 
,08-26 15:00:02.724  6820  6873 I jxcore-log: Unit Test app is loaded
08-26 15:00:02.724  6820  6873 I jxcore-log: 
,08-26 15:00:02.734  6820  6873 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:00:02.734  6820  6873 I jxcore-log: 
,08-26 15:00:02.734  6820  6820 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-26 15:00:02.744  6820  6873 I jxcore-log: My device name is: samsung-SM-A300FU
08-26 15:00:02.744  6820  6873 I jxcore-log: 
,08-26 15:00:03.374  6820  6873 W jxcore-log: !!! js_ReportOverRecursed called !!!
,08-26 15:00:03.504  6949  6949 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----
08-26 15:00:03.504  6949  6949 W google-breakpad: V WebView:45.0.2454.95
,08-26 15:00:03.504  6949  6949 W google-breakpad: O A arm 04 samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys
08-26 15:00:03.504  6949  6949 W google-breakpad: S 0 9F66F038 9F66F000 00008000
,08-26 15:00:03.534  6949  6949 W google-breakpad: S 9F66F000 905DF3B80000000085FFFFFF28C3F3B86CF0669F2069059E0000000030F0669F905DF3B8000000006C375F9E80F0669F74375F9E6CF0669F07000000000000000000000090B8E0E6E02EB29C85FFFFFFE01DA19D905DF3B8F0F0669F9CF0669F74F0669F85FFFFFF94F0669F204E249EE02EB29CE01DA19D0000000060F1669F9CF0669FF0F0669F74375F9EE02EB29CBCF0669F58F7459E041F3CBA000000000000000082FFFFFFF0F0669F60F1669FE0F0669F905DF3B824F1669F1C8B3E9EE4F85E9E50FC5E9E58FB749E22000000041F3CBAEC1E3CBA00000000F4F0669FE02EB29C85FFFFFF905DF3B800000000E02EB29C85FFFFFFA8F1669F78F2669F18E1759E70F1669F000000000100000060F1669F50F1669F22000000905DF3B8B4F2669F28B4419EC01E3CBA00000000905DF3B840F1669F0200000088F1669FE01CF09CA8F1669F3081B99C88FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFF905DF3B80000000000000000905DF3B801000000D8F2669F
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66F180 E8F2669F01000000C01E3CBA070000000700000001000000502DB29C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF00000000D01E3CBA22000000582DB29C0700000000000000010000001800A09DC84098B981FFFFFF14F2669FE0CA2E9E07000000502DB29C905DF3B8000000001000A09D20F2669F54F2669FE80C2F9E0000000000000000000000000CD40E9F88F2669F0100000000000000B085B99CE01BA19D502DB29C00000000FFFFFFFFC84098B981FFFFFFF0F2669FB0D40E9F48F3669F64F2669FB0F2669F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFF502DB29C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF384198B981FFFFFFF0F2669F382F409F00000000C4F2669F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFF502DB29C85FFFFFF4CF3669F384198B9882C439F01050000
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66F300 502DB29C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFF7CF3669F94F3669F0000000070F3669F8C39409F820100008086969D010000000000000082FFFFFF502DB29C85FFFFFF1CF4669FA029A5B92CDC379F010A0000502DB29C85FFFFFF0000000082FFFFFF8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF18DD839D020000000000000048F4669F8C39409F02020000C04C969D02000000A0C6959D88FFFFFF502DB29C85FFFFFFC0B7C29C88FFFFFFBCF4669F18B242B9EC1D849D81060000F0D9A19D85FFFFFF502DB29C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66F480 0000000082FFFFFF0000000082FFFFFFC1030000A0F4669F0000000083FFFFFF6800000060CA329B582DB29C010000003000000060CA329B00000000E0F4669F8C39409F8201000040D59D9C010000000000000082FFFFFF502DB29C85FFFFFF64F5669F00D494B92C16849D81070000502DB29C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF80F5669F78F5669F70F5669FE4F5669F7800000060CA329B000000006638D3BA58FB749E905DF3B80000000088F5669F8C39409F8201000080D59D9C010000000000000082FFFFFF502DB29C85FFFFFFF4F5669FC00146B90C0C849D01060000502DB29C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000000F6669F18F6669F040000006000000060CA329B904E65BA81FFFFFF84F6669FF8EF3F9F0000000018F6669F8C39409F82010000
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66F600 A0D59D9C010000000000000082FFFFFF502DB29C85FFFFFF84F6669F280683B91003849D01060000502DB29C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000005085B99C0000000068C88A9B600000008085B99C0400000018DD839D94F6669F7824119E04000000A8F6669F8C39409F82010000C0D59D9C010000000000000082FFFFFF5085B99C88FFFFFF24F7669F60C371BA24FA839D010700005085B99C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013A19D85FFFFFF502DB29C85FFFFFF0000000018F7669F14F7669F88FFFFFF700000002085B99C20DECE9C8401249E00000000000000000400000048F7669F8C39409F8201000040D69D9C010000001023DB9A88FFFFFF9081B99C88FFFFFFA4F7669F90FD5CBA90F3839D010500009081B99C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFF20DECE9C01000000
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66F780 D4F7669FECF7669F50000000509E6A9B02000000E0A393BAC4F7669FC823119E00000000D8F7669FDC8D079F820200008016099D030000000000000082FFFFFF9081B99C88FFFFFF0000000081FFFFFF20DECE9C88FFFFFF74F8669F38D932B9E8F20A9F0109000020DECE9C88FFFFFF0000000081FFFFFF9081B99C88FFFFFF0000000082FFFFFF8016099D88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF10351B9C88FFFFFF0000000082FFFFFF0900000081FFFFFF20DECE9C88FFFFFF70DECE9C00000000A4F8669FC0D6929D9000000020C0929D18DD839D0200000090C5A9B981FFFFFF0000000098F8669F8C39409F82010000B002939D0100000020DECE9C88FFFFFF8016099D88FFFFFF1CF9669F48C1A9B900ED839D810700008016099D88FFFFFF20DECE9C88FFFFFFB002939D88FFFFFF70DECE9C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFF70DECE9C88FFFFFF0000000082FFFFFF40F9669F382F409F0000000004F9669F
08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66F900 78000000509E6A9B0000000054E3839D42030000030000000000000048F9669F8C39409F02020000A016099D02000000B068EE9A88FFFFFFE01CF09C88FFFFFF20DECE9C88FFFFFFB4F9669F2032BAB920E8839D0106000020DECE9C88FFFFFFE01CF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFF78F9669FA035949D802EB29C4011A19D60000000509E6A9B85FFFFFFDC16879D85FFFFFFB4F9669F000000000037949DE821879D800B0000E016099D020000000037949D88FFFFFFE01CF09C88FFFFFF30D8CE9C88FFFFFF902EB29C85FFFFFFD0DDCE9C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFB082B99C30D8CE9CA035949DB079B79C8A0000006084B99C902EB29CD0DDCE9C30D8CE9CA035949D802EB29C8018A09D107AB79C0900000060B7C29CD0B0929DD0B0929D30D8CE9C88FFFFFF090000004011A19D090000000037949DE01CF09C6081B99C60B7C29C88FFFFFF0000000064FD069F
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66FA80 08FF069F000400008036949D010000000037949D88FFFFFFE01CF09C88FFFFFF0000000082FFFFFFF04A7E9EE01CF09C3081B99C0081B99C0000000087FFFFFFA00F939DD080B99C0081B99C40B7C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFFD080B99C88FFFFFF30FB669FD080B99C7080B99CA080B99CFC000F9F800200000037949D000000007080B99C88FFFFFF50A5C59C8A0000000700000060A5C59C905DF3B840B0929DA079B79C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFFA079B79C85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB608FD669F0100000081FFFFFF60FC669FCCFC669F14E4169E603F979D000000000000000030FC669FE4FB669F38673F9F58FB749E905DF3B8682CF9B84C0D679F00000000000000000000000001000000
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66FC00 3404679F905DF3B80001000000000000B0FF0E9F00000000603F979DC000679F020000000100000000000000000000000100000081FFFFFF00000000000000009800679FF6FFFFFF9C5DF3B801000000905DF3B860FC669F00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000008FD669F905DF3B8785B7E9E80829A9D00000000181A3CBACCFC669F667ADB3600000000905DF3B808FD669FD0FC669F603F979D80829A9D00000000181A3CBAF4FC669F2C85349E000000000000000000000000E44DFCB601000000905DF3B8C800679F00FD669F7C00679F2486349E423A77B9EB3B77B9C800679F01000000E82C749E0100000080829A9D00FD669F00000000003C77B90200000002000000010000000000000080DA739E5C0000000600000000000000380C679F000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66FD80 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F03177B900000000000000000100000002000000A0B6C29C80839A9D8D0317B90000000000000000667ADB3600000000E44DFCB600000000905DF3B8C8DA269E98FE669F1402679FA886349E0000000000000000B802679F00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F66FF00 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB36E44DFCB6B800679F905DF3B86801679FC800679F181A3CBA2401679FE48A349E
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670080 00000000000000000000000040B0929DC800679F01000000A80D679FF6FFFFFF9C5DF3B800000000905DF3B8B800679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFFA079B79C85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB3613000000905DF3B87801679F6801679F7001679F6401679F82FFFFFF101A3CBA5401679F3875249E101A3CBA7001679F40B0929D88FFFFFFB401679FE801679FC802679F010000008001679F00000000B401679F200B469E7001679F000000000000000040B0929D603F979D88FFFFFF0000000082FFFFFF01000000101A3CBA0000000082FFFFFF905DF3B8000000006C375F9EE801679FD801679F38CDBAB8D0CFBAB8905DF3B8C802679F6C375F9E2402679FB81A3D9EE801679F000000C0B8193CBA5052AFBA3C02679F8D61F9B6C4193CBA0000000040B0929D88FFFFFF905DF3B800000000A079B79C85FFFFFF905DF3B8000000003802679F1890609E
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670200 E5193CBA5802679FC802679F4802679F905DF3B83C02679F2200000038CDBAB88C02679FEC8A3E9EE4F85E9E50FC5E9E58FB749E22000000C4193CBAAC193CBA000000005C02679F2200000000000000E003679F000000007402679F1455FC9D1003679FE003679F18E1759ED802679F0000000001000000C802679FB802679F22000000905DF3B81C04679F28B4419E80193CBA00000000905DF3B8A802679F02000000F002679F901CF09C1003679FB0BBC39C88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000905DF3B8010000004004679F5004679F0100000080193CBA0700000007000000010000004078B79C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF0000000090193CBA220000004878B79C0700000000000000010000001800A09DC84098B981FFFFFF7C03679FE0CA2E9E070000004078B79C905DF3B8000000001000A09D8803679FBC03679FE80C2F9E
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670380 0000000000000000000000000CD40E9FF003679F01000000000000004080B99CE01BA19D4078B79C00000000FFFFFFFFC84098B981FFFFFF5804679FB0D40E9FB004679FCC03679F1804679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFF4078B79C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF384198B981FFFFFF5804679F382F409F000000002C04679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFF4078B79C85FFFFFFB404679F384198B9882C439F010500004078B79C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFFE404679FFC04679F00000000D804679F8C39409F820100008086969D010000000000000082FFFFFF4078B79C85FFFFFF8405679FA029A5B92CDC379F010A00004078B79C85FFFFFF0000000082FFFFFF8086969D88FFFFFF
08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670500 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF18DD839D0200000000000000B005679F8C39409F02020000C04C969D02000000A0C6959D88FFFFFF4078B79C85FFFFFF20B7C29C88FFFFFF2406679F18B242B9EC1D849D81060000F0D9A19D85FFFFFF4078B79C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300000806679F0000000083FFFFFF6800000060CA329B4878B79C010000003000000060CA329B000000004806679F8C39409F8201000040D59D9C010000000000000082FFFFFF4078B79C85FFFFFFCC06679F00D494B92C16849D810700004078B79C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670680 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFE806679FE006679FD806679F4C07679F7800000060CA329B000000006638D3BA58FB749E905DF3B800000000F006679F8C39409F8201000080D59D9C010000000000000082FFFFFF4078B79C85FFFFFF5C07679FC00146B90C0C849D010600004078B79C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000006807679F8007679F040000006000000060CA329B904E65BA81FFFFFFEC07679FF8EF3F9F000000008007679F8C39409F82010000A0D59D9C010000000000000082FFFFFF4078B79C85FFFFFFEC07679F280683B91003849D010600004078B79C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D0BFC39C0000000068C88A9B600000001080B99C0400000018DD839DFC07679F7824119E040000001008679F8C39409F82010000C0D59D9C01000000
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670800 0000000082FFFFFFD0BFC39C88FFFFFF8C08679F60C371BA24FA839D01070000D0BFC39C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013A19D85FFFFFF4078B79C85FFFFFF000000008008679F7C08679F88FFFFFF70000000A0BFC39C90D7CE9C8401249E000000000000000004000000B008679F8C39409F8201000040D69D9C010000001023DB9A88FFFFFF10BCC39C88FFFFFF0C09679F90FD5CBA90F3839D0105000010BCC39C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFF90D7CE9C010000003C09679F5409679F50000000509E6A9B02000000E0A393BA2C09679FC823119E000000004009679FDC8D079F820200008016099D030000000000000082FFFFFF10BCC39C88FFFFFF0000000081FFFFFF90D7CE9C88FFFFFFDC09679F38D932B9E8F20A9F0109000090D7CE9C88FFFFFF0000000081FFFFFF10BCC39C88FFFFFF0000000082FFFFFF8016099D88FFFFFF0900000084FFFFFF
,08-26 15:00:03.544  6949  6949 W google-breakpad: S 9F670980 0000000082FFFFFF0000000081FFFFFF30341B9C88FFFFFF0000000082FFFFFF0900000081FFFFFF90D7CE9C88FFFFFFE0D7CE9C000000000C0A679FC0D6929D9000000020C0929D18DD839D0200000090C5A9B981FFFFFF00000000000A679F8C39409F82010000B002939D0100000090D7CE9C88FFFFFF8016099D88FFFFFF840A679F48C1A9B900ED839D810700008016099D88FFFFFF90D7CE9C88FFFFFFB002939D88FFFFFFE0D7CE9C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFFE0D7CE9C88FFFFFF0000000082FFFFFFA80A679F382F409F000000006C0A679F78000000509E6A9B0000000054E3839D420300000300000000000000B00A679F8C39409F02020000A016099D02000000B068EE9A88FFFFFF901CF09C88FFFFFF90D7CE9C88FFFFFF1C0B679F2032BAB920E8839D0106000090D7CE9C88FFFFFF901CF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFFE00A679FA035949D7079B79C4011A19D
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F670B00 60000000509E6A9B85FFFFFFDC16879D85FFFFFF1C0B679F000000000037949DE821879D800B0000E016099D020000000037949D88FFFFFF901CF09C88FFFFFFA0D1CE9C88FFFFFF8079B79C85FFFFFF40D7CE9C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF30BDC39CA0D1CE9CA035949D50A5C59C8A000000E0BEC39C8079B79C40D7CE9CA0D1CE9CA035949D7079B79C8018A09DB0A5C59C09000000C0B6C29CD0B0929DD0B0929DA0D1CE9C88FFFFFF090000004011A19D090000000037949D901CF09CE0BBC39CC0B6C29C88FFFFFF0000000064FD069F08FF069F000400008036949D010000000037949D88FFFFFF901CF09C88FFFFFF0000000082FFFFFFF04A7E9E901CF09CB0BBC39C80BBC39C0000000087FFFFFFA00F939D50BBC39C80BBC39CA0B6C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFF50BBC39C88FFFFFF980C679F50BBC39CF0BAC39C20BBC39CFC000F9F800200000037949D00000000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F670C80 F0BAC39C88FFFFFFA051C79C8A00000007000000B051C79C905DF3B840B0929D40A5C59C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFF40A5C59C85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB6700E679F0100000081FFFFFFC80D679F340E679F14E4169E603F979D0000000000000000980D679F4C0D679F38673F9F58FB749E905DF3B8682CF9B8B41E679F000000000000000000000000010000009C15679F905DF3B80001000000000000B0FF0E9F00000000603F979D2812679F020000000100000000000000000000000100000081FFFFFF00000000000000000012679FF6FFFFFF9C5DF3B801000000905DF3B8C80D679F000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000700E679F905DF3B8785B7E9E80829A9D
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F670E00 00000000D8143CBA340E679F667ADB3600000000905DF3B8700E679F380E679F603F979D80829A9D00000000D8143CBA5C0E679F2C85349E000000000000000000000000E44DFCB601000000905DF3B83012679F680E679FE411679F2486349E423A77B9EB3B77B93012679F01000000E82C749E0100000080829A9D680E679F00000000003C77B90200000002000000010000000000000080DA739E5C0000000600000000000000A01D679F0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F670F80 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F03177B90000000000000000010000000200000000B6C29C80839A9D8D0317B90000000000000000667ADB3600000000E44DFCB600000000905DF3B8C8DA269E0010679F7C13679FA886349E00000000000000002014679F000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671100 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB36E44DFCB62012679F905DF3B8D012679F3012679FD8143CBA8C12679FE48A349E00000000000000000000000040B0929D3012679F01000000101F679FF6FFFFFF9C5DF3B800000000905DF3B82012679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFF40A5C59C85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB3613000000905DF3B8E012679FD012679FD812679FCC12679F
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671280 82FFFFFFD0143CBABC12679F3875249ED0143CBAD812679F40B0929D88FFFFFF1C13679F5013679F3014679F01000000E812679F000000001C13679F200B469ED812679F000000000000000040B0929D603F979D88FFFFFF0000000082FFFFFF01000000D0143CBA0000000082FFFFFF905DF3B8000000006C375F9E5013679F4013679F38CDBAB8D0CFBAB8905DF3B83014679F6C375F9E8C13679FB81A3D9E5013679F000000C078143CBA5052AFBAA413679F8D61F9B684143CBA0000000040B0929D88FFFFFF905DF3B80000000040A5C59C85FFFFFF905DF3B800000000A013679F1890609EA5143CBAC013679F3014679FB013679F905DF3B8A413679F2200000038CDBAB8F413679FEC8A3E9EE4F85E9E50FC5E9E58FB749E2200000084143CBAC4011CBA00000000C413679F22000000000000004815679F00000000DC13679F1455FC9D7814679F4815679F18E1759E4014679F00000000010000003014679F2014679F22000000905DF3B88415679F28B4419E58143CBA00000000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671400 905DF3B81014679F020000005814679F401CF09C7814679F40B6C39C88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000905DF3B801000000A815679FB815679F0100000058143CBA070000000700000001000000E0A3C59C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF0000000068143CBA22000000E8A3C59C0700000000000000010000001800A09DC84098B981FFFFFFE414679FE0CA2E9E07000000E0A3C59C905DF3B8000000001000A09DF014679F2415679FE80C2F9E0000000000000000000000000CD40E9F5815679F0100000000000000C0BAC39CE01BA19DE0A3C59C00000000FFFFFFFFC84098B981FFFFFFC015679FB0D40E9F1816679F3415679F8015679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFFE0A3C59C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF384198B981FFFFFF
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671580 C015679F382F409F000000009415679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFFE0A3C59C85FFFFFF1C16679F384198B9882C439F01050000E0A3C59C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFF4C16679F6416679F000000004016679F8C39409F820100008086969D010000000000000082FFFFFFE0A3C59C85FFFFFFEC16679FA029A5B92CDC379F010A0000E0A3C59C85FFFFFF0000000082FFFFFF8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF18DD839D02000000000000001817679F8C39409F02020000C04C969D02000000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671700 A0C6959D88FFFFFFE0A3C59C85FFFFFF80B6C29C88FFFFFF8C17679F18B242B9EC1D849D81060000F0D9A19D85FFFFFFE0A3C59C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC10300007017679F0000000083FFFFFF6800000060CA329BE8A3C59C010000003000000060CA329B00000000B017679F8C39409F8201000040D59D9C010000000000000082FFFFFFE0A3C59C85FFFFFF3418679F00D494B92C16849D81070000E0A3C59C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF5018679F4818679F4018679FB418679F7800000060CA329B000000006638D3BA58FB749E905DF3B8000000005818679F8C39409F8201000080D59D9C010000000000000082FFFFFFE0A3C59C85FFFFFFC418679FC00146B90C0C849D01060000E0A3C59C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671880 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D018679FE818679F040000006000000060CA329B904E65BA81FFFFFF5419679FF8EF3F9F00000000E818679F8C39409F82010000A0D59D9C010000000000000082FFFFFFE0A3C59C85FFFFFF5419679F280683B91003849D01060000E0A3C59C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000060BAC39C0000000068C88A9B6000000090BAC39C0400000018DD839D6419679F7824119E040000007819679F8C39409F82010000C0D59D9C010000000000000082FFFFFF60BAC39C88FFFFFFF419679F60C371BA24FA839D0107000060BAC39C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013A19D85FFFFFFE0A3C59C85FFFFFF00000000E819679FE419679F88FFFFFF7000000030BAC39C00D1CE9C8401249E000000000000000004000000181A679F8C39409F82010000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671A00 40D69D9C010000001023DB9A88FFFFFFA0B6C39C88FFFFFF741A679F90FD5CBA90F3839D01050000A0B6C39C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFF00D1CE9C01000000A41A679FBC1A679F50000000509E6A9B02000000E0A393BA941A679FC823119E00000000A81A679FDC8D079F820200008016099D030000000000000082FFFFFFA0B6C39C88FFFFFF0000000081FFFFFF00D1CE9C88FFFFFF441B679F38D932B9E8F20A9F0109000000D1CE9C88FFFFFF0000000081FFFFFFA0B6C39C88FFFFFF0000000082FFFFFF8016099D88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFC0331B9C88FFFFFF0000000082FFFFFF0900000081FFFFFF00D1CE9C88FFFFFF50D1CE9C00000000741B679FC0D6929D9000000020C0929D18DD839D0200000090C5A9B981FFFFFF00000000681B679F8C39409F82010000B002939D0100000000D1CE9C88FFFFFF8016099D88FFFFFFEC1B679F48C1A9B900ED839D810700008016099D88FFFFFF
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671B80 00D1CE9C88FFFFFFB002939D88FFFFFF50D1CE9C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFF50D1CE9C88FFFFFF0000000082FFFFFF101C679F382F409F00000000D41B679F78000000509E6A9B0000000054E3839D420300000300000000000000181C679F8C39409F02020000A016099D02000000B068EE9A88FFFFFF401CF09C88FFFFFF00D1CE9C88FFFFFF841C679F2032BAB920E8839D0106000000D1CE9C88FFFFFF401CF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFF481C679FA035949D10A5C59C4011A19D60000000509E6A9B85FFFFFFDC16879D85FFFFFF841C679F000000000037949DE821879D800B0000E016099D020000000037949D88FFFFFF401CF09C88FFFFFF002BC29C88FFFFFF20A5C59C85FFFFFFB0D0CE9C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFC0B7C39C002BC29CA035949DA051C79C8A00000070B9C39C20A5C59CB0D0CE9C002BC29C
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671D00 A035949D10A5C59C8018A09D0052C79C0900000020B6C29CD0B0929DD0B0929D002BC29C88FFFFFF090000004011A19D090000000037949D401CF09C70B6C39C20B6C29C88FFFFFF0000000064FD069F08FF069F000400008036949D010000000037949D88FFFFFF401CF09C88FFFFFF0000000082FFFFFFF04A7E9E401CF09C40B6C39C10B6C39C0000000087FFFFFFA00F939DE0B5C39C10B6C39C00B6C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFFE0B5C39C88FFFFFF001E679FE0B5C39C80B5C39CB0B5C39CFC000F9F800200000037949D0000000080B5C39C88FFFFFF905ECC9C8A00000007000000A05ECC9C905DF3B840B0929D9051C79C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFF9051C79C85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB6
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F671E80 D81F679F0100000081FFFFFF301F679F9C1F679F14E4169E603F979D0000000000000000001F679FB41E679F38673F9F58FB749E905DF3B8682CF9B81C30679F000000000000000000000000010000000427679F905DF3B80001679F00000000B0FF0E9F00000000603F979D9023679F0200000001000000241F679F000000000100000081FFFFFF0021679F000000056823679FF6FFFFFF9C5DF3B801000000905DF3B8301F679F0000000008000000541F679F14C43A9E0000800020000000D821679FF87B9A9D0000100000000000A41F679F01000000D81F679F905DF3B8785B7E9E80829A9D0000000028001CBA9C1F679F667ADB3600000000905DF3B8D81F679FA01F679F603F979D80829A9D0000000028001CBAC41F679F2C85349E00000000B4283C9E02000000E44DFCB601000000905DF3B89823679FD01F679F4C23679F2486349EDC1F679F0C293C9E9823679F01000000E82C749E0100000080829A9DD01F679F0000000000BB3A9E02000000380000009CEBB6B92CBA3A9E
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F672000 1120679F38000000D023679F1121679F3C000000000000E0E44DFCB6D821679F7020679FF87B9A9DF01BF09C000000006CEBB6B9F0D73A9EB0EBB6B94C20679F010000005C20679F5C20679FFFFFFF00010000006C20679F08000000B4EBB6B988EBB6B97C29849D8829849D20A03A9E6029849DF0FFFFFFFFFFFFFF00000000D821679F6C144946240000009029849DD821679FB420679F10000000B420679F8421679FD820679F8421679FB820679FD420679FE0261A9E7029849D8829849D8421679F8421679F207E839B0821679FFC20679F48281A9ED0EAB6B9000000C078AE35BAD8EAB6B9B8FE1BBA000000C078AE35BAC0FE1BBAF01BF09C8D61F9B6D821679F0100000078AE35BA905DF3B8F01BF09C4DCFF7B6D022679F2CE3069E0829679FD821679F3C21679F248B159E00000000E44DFCB6C42C679F5C5D1A9E00A135BABCE05F9E0D000000AC74F6B903000000000000000000000000CB1A9E00A135BA64E35F9E1835879DD821679F0100000000A135BA9021679FF87B9A9D
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F672180 F01BF09C28EB729E41B0929D0821879D10000000280000001C0000002C0000000000000078AE35BA0D000000AC74F6B903000000000000000D000000CC9A3A9E0200000001000000D821679F000000000000000000000000E821679F00000000000000000000000000000000000000000022679F00000000000000000000000000000000000000001822679F00000000000000000000000000000000000000003022679F0000000000000000000000004022679F0000000001000000000000005022679F00000000000000000000000008000000000000006822679F0000000008000000000000007822679F0000000008000000000000008822679F0000000008000000000000009822679F000000000000000000000000A822679F000000000000000005000000B822679F0000000000000000020000000200000000000000C0FE1BBA0100000001000000000000000000000000000000E822679F00000000000000000000000020000000000000000023679F000000002000000000000000
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F672300 0123679F000000001823679F0500000001000000050000002823679F0200000001000000D00000003823679F667ADB36E44DFCB68823679F905DF3B83824679F9823679F28001CBAF423679FE48A349E6023679F000000000100000040B0929D9823679F010000007830679FF6FFFFFF9C5DF3B800000000905DF3B88823679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFF9051C79C85FFFFFF20000000000000000123679F00000000704A729E88EBB6B901EFB6B90000B6B9704A729E88EBB6B901EFB6B9667ADB3613000000905DF3B84824679F3824679F4024679F3424679F82FFFFFF20001CBA2424679F3875249E20001CBA4024679F40B0929D88FFFFFF8424679FB824679F9825679F010000005024679F000000008424679F200B469E4024679F0800000028F8B6B940B0929D603F979D88FFFFFF0000000082FFFFFF0100000020001CBA0000000082FFFFFF905DF3B8000000006C375F9EB824679FA824679F38CDBAB8D0CFBAB8905DF3B89825679F6C375F9E
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F672480 F424679FB81A3D9EB824679F000000C0C8FF1BBA5052AFBA0C25679F8D61F9B6D4FF1BBA0000000040B0929D88FFFFFF905DF3B8000000009051C79C85FFFFFF905DF3B8000000000825679F1890609EF5FF1BBA2825679F9825679F1825679F905DF3B80C25679F2200000038CDBAB85C25679FEC8A3E9EE4F85E9E50FC5E9E58FB749E22000000D4FF1BBABCFF1BBA000000002C25679F2200000000000000B026679F000000004425679F1455FC9DE025679FB026679F18E1759EA825679F00000000010000009825679F8825679F22000000905DF3B8EC26679F28B4419E90FF1BBA00000000905DF3B87825679F02000000C025679FF01BF09CE025679FD0B0C39C88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000905DF3B8010000001027679F2027679F0100000090FF1BBA0700000007000000010000003050C79C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF
08-26 15:00:03.554  6949  6949 W google-breakpad: S 9F672600 00000000A0FF1BBA220000003850C79C0700000000000000010000001800A09DC84098B981FFFFFF4C26679FE0CA2E9E070000003050C79C905DF3B8000000001000A09D5826679F8C26679FE80C2F9E0000000000000000000000000CD40E9FC026679F010000000000000050B5C39CE01BA19D3050C79C00000000FFFFFFFFC84098B981FFFFFF2827679FB0D40E9F8027679F9C26679FE826679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFF3050C79C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF384198B981FFFFFF2827679F382F409F00000000FC26679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFF3050C79C85FFFFFF8427679F384198B9882C439F010500003050C79C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFFB427679FCC27679F
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F672780 00000000A827679F8C39409F820100008086969D010000000000000082FFFFFF3050C79C85FFFFFF5428679FA029A5B92CDC379F010A00003050C79C85FFFFFF0000000082FFFFFF8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF18DD839D02000000000000008028679F8C39409F02020000C04C969D02000000A0C6959D88FFFFFF3050C79C85FFFFFFE0B5C29C88FFFFFFF428679F18B242B9EC1D849D81060000F0D9A19D85FFFFFF3050C79C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000D828679F0000000083FFFFFF6800000060CA329B3850C79C010000003000000060CA329B000000001829679F8C39409F82010000
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F672900 40D59D9C010000000000000082FFFFFF3050C79C85FFFFFF9C29679F00D494B92C16849D810700003050C79C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFB829679FB029679FA829679F1C2A679F7800000060CA329B000000006638D3BA58FB749E905DF3B800000000C029679F8C39409F8201000080D59D9C010000000000000082FFFFFF3050C79C85FFFFFF2C2A679FC00146B90C0C849D010600003050C79C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000382A679F502A679F040000006000000060CA329B904E65BA81FFFFFFBC2A679FF8EF3F9F00000000502A679F8C39409F82010000A0D59D9C010000000000000082FFFFFF3050C79C85FFFFFFBC2A679F280683B91003849D010600003050C79C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F672A80 0000000082FFFFFF0000000082FFFFFF00000000F0B4C39C0000000068C88A9B6000000020B5C39C0400000018DD839DCC2A679F7824119E04000000E02A679F8C39409F82010000C0D59D9C010000000000000082FFFFFFF0B4C39C88FFFFFF5C2B679F60C371BA24FA839D01070000F0B4C39C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013A19D85FFFFFF3050C79C85FFFFFF00000000502B679F4C2B679F88FFFFFF70000000C0B4C39C602AC29C8401249E000000000000000004000000802B679F8C39409F8201000040D69D9C010000001023DB9A88FFFFFF30B1C39C88FFFFFFDC2B679F90FD5CBA90F3839D0105000030B1C39C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFF602AC29C010000000C2C679F242C679F50000000509E6A9B02000000E0A393BAFC2B679FC823119E00000000102C679FDC8D079F820200008016099D030000000000000082FFFFFF30B1C39C88FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F672C00 0000000081FFFFFF602AC29C88FFFFFFAC2C679F38D932B9E8F20A9F01090000602AC29C88FFFFFF0000000081FFFFFF30B1C39C88FFFFFF0000000082FFFFFF8016099D88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF50331B9C88FFFFFF0000000082FFFFFF0900000081FFFFFF602AC29C88FFFFFFB02AC29C00000000DC2C679FC0D6929D9000000020C0929D18DD839D0200000090C5A9B981FFFFFF00000000D02C679F8C39409F82010000B002939D01000000602AC29C88FFFFFF8016099D88FFFFFF542D679F48C1A9B900ED839D810700008016099D88FFFFFF602AC29C88FFFFFFB002939D88FFFFFFB02AC29C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFFB02AC29C88FFFFFF0000000082FFFFFF782D679F382F409F000000003C2D679F78000000509E6A9B0000000054E3839D420300000300000000000000802D679F8C39409F02020000A016099D02000000B068EE9A88FFFFFFF01BF09C88FFFFFF602AC29C88FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F672D80 EC2D679F2032BAB920E8839D01060000602AC29C88FFFFFFF01BF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFFB02D679FA035949D6051C79C4011A19D60000000509E6A9B85FFFFFFDC16879D85FFFFFFEC2D679F000000000037949DE821879D800B0000E016099D020000000037949D88FFFFFFF01BF09C88FFFFFF7024C29C88FFFFFF7051C79C85FFFFFF102AC29C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF50B2C39C7024C29CA035949D905ECC9C8A00000000B4C39C7051C79C102AC29C7024C29CA035949D6051C79C8018A09DF05ECC9C0900000080B5C29CD0B0929DD0B0929D7024C29C88FFFFFF090000004011A19D090000000037949DF01BF09C00B1C39C80B5C29C88FFFFFF0000000064FD069F08FF069F000400008036949D010000000037949D88FFFFFFF01BF09C88FFFFFF0000000082FFFFFFF04A7E9EF01BF09CD0B0C39CA0B0C39C0000000087FFFFFFA00F939D70B0C39C
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F672F00 A0B0C39C60B5C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFF70B0C39C88FFFFFF9C30679F70B0C39C10B0C39C40B0C39CFC000F9F800200000037949D0000000010B0C39C88FFFFFF3039679F48000000742F679F4037679F4800000040B0929D805ECC9C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFF805ECC9C85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB64031679F0100000081FFFFFF9830679F0431679F14E4169E603F979D00000000000000006830679F1C30679F38673F9F58FB749E905DF3B8682CF9B88441679F000000000000000000000000010000006C38679F905DF3B80001CFB900000000B0FF0E9F00000000603F979DF834679F0200000001000000B0AD2CBB000000000100000081FFFFFF00CF1C9E607FF6B9D034679FF6FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673080 9C5DF3B801000000905DF3B89830679F00000000080000006845CFB94845CFB900AE2CBB9A010000F0A32CBB4845CFB9B845CFB91804000088F61BBA010000004031679F905DF3B8785B7E9E80829A9D00000000E8FA1BBA0431679F667ADB3600000000905DF3B84031679F0831679F603F979D80829A9D00000000E8FA1BBA2C31679F2C85349E000000002880F6B900000000E44DFCB601000000905DF3B80035679F3831679FB434679F2486349E423A77B9EB3B77B90035679F01000000E82C749E0100000080829A9D3831679F00000000003C77B90200000002000000010000000000000080DA739E5C00000006000000000000007040679F000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673200 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F03177B900000000000000000100000002000000C0B4C29C80839A9D8D0317B90000000000000000667ADB3600000000E44DFCB600000000905DF3B8C8DA269ED032679F4C36679FA886349E0000000000000000F036679F00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673380 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB36E44DFCB6F034679F905DF3B8A035679F0035679FE8FA1BBA5C35679FE48A349E00000000000000000000000040B0929D0035679F01000000E041679FF6FFFFFF9C5DF3B800000000905DF3B8F034679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673500 805ECC9C85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB3613000000905DF3B8B035679FA035679FA835679F9C35679F82FFFFFFE0FA1BBA8C35679F3875249EE0FA1BBAA835679F40B0929D88FFFFFFEC35679F2036679F0037679F01000000B835679F00000000EC35679F200B469EA835679F000000000000000040B0929D603F979D88FFFFFF0000000082FFFFFF01000000E0FA1BBA0000000082FFFFFF905DF3B8000000006C375F9E2036679F1036679F38CDBAB8D0CFBAB8905DF3B80037679F6C375F9E5C36679FB81A3D9E2036679F000000C088FA1BBA5052AFBA7436679F8D61F9B694FA1BBA0000000040B0929D88FFFFFF905DF3B800000000805ECC9C85FFFFFF905DF3B8000000007036679F1890609EB5FA1BBA9036679F0037679F8036679F905DF3B87436679F2200000038CDBAB8C436679FEC8A3E9EE4F85E9E50FC5E9E58FB749E2200000094FA1BBA7CFA1BBA000000009436679F
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673680 22000000000000001838679F00000000AC36679F1455FC9D4837679F1838679F18E1759E1037679F00000000010000000037679FF036679F22000000905DF3B85438679F28B4419E50FA1BBA0000000050B507BA00000000000000002837679F4437679F4837679F6037679F000000000000000082FFFFFF0000000000010000220000000000000000000000000000000037679F905DF3B8010000007838679F8838679F01D3A19D50FA1BBA070000000700000001000000205DCC9C00000020905DF3B8F430679FC03E74B9060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF0000000060FA1BBA22000000285DCC9C0700000000000000010000001800A09DC84098B901000000B437679FE0CA2E9E07000000205DCC9C905DF3B8000000001000A09DC037679FF437679FE80C2F9E6865AABAC065AABA1866AABA0CD40E9F2838679F010000007867AABAD06FC69CE01BA19D205DCC9C00000000FFFFFFFFC84098B9010000009038679FB0D40E9FE838679F0438679F
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673800 5038679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFF205DCC9C85FFFFFF1000A09D85FFFFFFB86FAABA6049969D88FFFFFF882C439F00000000FFFFFFFF384198B9010000009038679F382F409F000000006438679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFF205DCC9C85FFFFFFEC38679F384198B9882C439F01050000205DCC9C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFF1C39679F3439679F000000001039679F8C39409F820100008086969D010000000000000082FFFFFF205DCC9C85FFFFFFBC39679FA029A5B92CDC379F010A0000205DCC9C85FFFFFF0000000082FFFFFF8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673980 3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF806EC69C0302000000000000E839679F8C39409F02020000C04C969D02000000A0C6959D88FFFFFF205DCC9C85FFFFFF40B5C29C88FFFFFF5C3A679F18B242B9EC1D849D81060000F0D9A19D85FFFFFF205DCC9C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000403A679F0000000083FFFFFF6800000060CA329B285DCC9C010000003000000060CA329B00000000803A679F8C39409F8201000040D59D9C010000000000000082FFFFFF205DCC9C85FFFFFF043B679F00D494B92C16849D81070000205DCC9C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF203B679F183B679F103B679F843B679F7800000060CA329B000000006638D3BA58FB749E905DF3B8
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673B00 00000000283B679F8C39409F8201000080D59D9C010000000000000082FFFFFF205DCC9C85FFFFFF943B679FC00146B90C0C849D01060000205DCC9C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A03B679FB83B679F040000006000000060CA329B904E65BA01000000243C679FF8EF3F9F00000000B83B679F8C39409F82010000A0D59D9C010000000000000082FFFFFF205DCC9C85FFFFFF243C679F280683B91003849D01060000205DCC9C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000706FC69C0000000068C88A9B60000000A06FC69C04000000806EC69C343C679F7824119E04000000483C679F8C39409F82010000C0D59D9C010000000000000082FFFFFF706FC69C88FFFFFFC43C679F60C371BA24FA839D01070000706FC69C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673C80 0700000081FFFFFF8013A19D85FFFFFF205DCC9C85FFFFFF00000000B83C679FB43C679F88FFFFFF70000000406FC69CD023C29C8401249E000000000000000004000000E83C679F8C39409F8201000040D69D9C010000001023DB9A88FFFFFFB06BC69C88FFFFFF443D679F90FD5CBA90F3839D01050000B06BC69C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFFD023C29C01000000743D679F8C3D679F50000000509E6A9B03020000E0A393BA643D679FC823119E00000000783D679FDC8D079F820200008016099D030000000000000082FFFFFFB06BC69C88FFFFFF0000000081FFFFFFD023C29C88FFFFFF143E679F38D932B9E8F20A9F01090000D023C29C88FFFFFF0000000081FFFFFFB06BC69C88FFFFFF0000000082FFFFFF8016099D88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFE0321B9C88FFFFFF0000000082FFFFFF0900000081FFFFFFD023C29C88FFFFFF2024C29C00000000443E679FC0D6929D9000000020C0929D
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673E00 806EC69C0302000090C5A9B90100000000000000383E679F8C39409F82010000B002939D01000000D023C29C88FFFFFF8016099D88FFFFFFBC3E679F48C1A9B900ED839D810700008016099D88FFFFFFD023C29C88FFFFFFB002939D88FFFFFF2024C29C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFF2024C29C88FFFFFF0000000082FFFFFFE03E679F382F409F00000000A43E679F78000000509E6A9B0000000054E3839D420300000300000000000000E83E679F8C39409F02020000A016099D02000000B068EE9A88FFFFFFA01BF09C88FFFFFFD023C29C88FFFFFF543F679F2032BAB920E8839D01060000D023C29C88FFFFFFA01BF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFFCC51409F9C3F679FA03F679F0000000060000000509E6A9B883F679F00000000806EC69C0302000000000000803F679F8C39409F02020000E016099D020000000037949D88FFFFFFA01BF09C88FFFFFFD00DC59C88FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F673F80 1C40679F70C5E2B9FC64429F01090000D00DC59C88FFFFFFA01BF09C88FFFFFF0037949D88FFFFFFE016099D88FFFFFF0000000082FFFFFF0000000082FFFFFF605ECC9C85FFFFFF8023C29C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFE0B4C29C88FFFFFF806EC69C88FFFFFF603F979D0100000090000000806BC69C2440679F1440679F08457E9E00000000040000006C42679F08FF069F000400008036949D010000000037949D88FFFFFFA01BF09C88FFFFFF0000000082FFFFFFF04A7E9EA01BF09C506BC69C206BC69C0000000087FFFFFFA00F939DF06AC69C206BC69CC0B4C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFFF06AC69C88FFFFFFD040679FF06AC69C906AC69CC06AC69CFC000F9F800200000037949D00000000906AC69C88FFFFFFA05AC99C8A00000007000000B05AC99C905DF3B840B0929D309CCF9C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFF309CCF9C85FFFFFF
08-26 15:00:03.564  6949  6949 W google-breakpad: S 9F674100 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB6A842679F0100000081FFFFFF0042679F6C42679F14E4169E603F979D0000000000000000D041679F8441679F38673F9F58FB749E905DF3B8682CF9B8EC52679F00000000000000000000000001000000D449679F905DF3B80001000000000000B0FF0E9F00000000603F979D6046679F020000000100000000000000000000000100000081FFFFFF00000000000000003846679FF6FFFFFF9C5DF3B801000000905DF3B80042679F000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000A842679F905DF3B8785B7E9E80829A9D00000000A8F51BBA6C42679F667ADB3600000000905DF3B8A842679F7042679F603F979D80829A9D00000000A8F51BBA9442679F2C85349E000000000000000000000000E44DFCB6
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674280 01000000905DF3B86846679FA042679F1C46679F2486349E423A77B9EB3B77B96846679F01000000E82C749E0100000080829A9DA042679F00000000003C77B90200000002000000010000000000000080DA739E5C0000000600000000000000D851679F00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F03177B90000000000000000010000000200000020B4C29C80839A9D
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674400 8D0317B90000000000000000667ADB3600000000E44DFCB600000000905DF3B8C8DA269E3844679FB447679FA886349E00000000000000005848679F000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674580 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB36E44DFCB65846679F905DF3B80847679F6846679FA8F51BBAC446679FE48A349E00000000000000000000000040B0929D6846679F010000004853679FF6FFFFFF9C5DF3B800000000905DF3B85846679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFF309CCF9C85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB3613000000905DF3B81847679F0847679F1047679F0447679F82FFFFFFA0F51BBAF446679F3875249EA0F51BBA1047679F40B0929D88FFFFFF5447679F8847679F6848679F010000002047679F000000005447679F200B469E1047679F00000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674700 0000000040B0929D603F979D88FFFFFF0000000082FFFFFF01000000A0F51BBA0000000082FFFFFF905DF3B8000000006C375F9E8847679F7847679F38CDBAB8D0CFBAB8905DF3B86848679F6C375F9EC447679FB81A3D9E8847679F000000C048F51BBA5052AFBADC47679F8D61F9B654F51BBA0000000040B0929D88FFFFFF905DF3B800000000309CCF9C85FFFFFF905DF3B800000000D847679F1890609E75F51BBAF847679F6848679FE847679F905DF3B8DC47679F2200000038CDBAB82C48679FEC8A3E9EE4F85E9E50FC5E9E58FB749E2200000054F51BBA3CF51BBA00000000FC47679F22000000000000008049679F000000001448679F1455FC9DB048679F8049679F18E1759E7848679F00000000010000006848679F5848679F22000000905DF3B8BC49679F28B4419E10F51BBA00000000905DF3B84848679F020000009048679F501BF09CB048679FE065C69C88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000905DF3B8
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674880 01000000E049679FF049679F0100000010F51BBA070000000700000001000000D09ACF9C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF0000000020F51BBA22000000D89ACF9C0700000000000000010000001800A09DC84098B9010000001C49679FE0CA2E9E07000000D09ACF9C905DF3B8000000001000A09D2849679F5C49679FE80C2F9E0000000000000000000000000CD40E9F9049679F0100000000000000606AC69CE01BA19DD09ACF9C00000000FFFFFFFFC84098B901000000F849679FB0D40E9F504A679F6C49679FB849679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFFD09ACF9C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF384198B901000000F849679F382F409F00000000CC49679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFFD09ACF9C85FFFFFF544A679F384198B9
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674A00 882C439F01050000D09ACF9C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFF844A679F9C4A679F00000000784A679F8C39409F820100008086969D010000000000000082FFFFFFD09ACF9C85FFFFFF244B679FA029A5B92CDC379F010A0000D09ACF9C85FFFFFF0000000082FFFFFF8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF1069C69C0302000000000000504B679F8C39409F02020000C04C969D02000000A0C6959D88FFFFFFD09ACF9C85FFFFFFA0B4C29C88FFFFFFC44B679F18B242B9EC1D849D81060000F0D9A19D85FFFFFFD09ACF9C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674B80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000A84B679F0000000083FFFFFF6800000060CA329BD89ACF9C010000003000000060CA329B00000000E84B679F8C39409F8201000040D59D9C010000000000000082FFFFFFD09ACF9C85FFFFFF6C4C679F00D494B92C16849D8107000,0D09ACF9C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF884C679F804C679F784C679FEC4C679F7800000060CA329B000000006638D3BA58FB749E905DF3B800000000904C679F8C39409F8201000080D59D9C010000000000000082FFFFFFD09ACF9C85FFFFFFFC4C679FC00146B90C0C849D01060000D09ACF9C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000084D679F204D679F040000006000000060CA329B904E65BA010000008C4D679FF8EF3F9F00000000204D679F
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674D00 8C39409F82010000A0D59D9C010000000000000082FFFFFFD09ACF9C85FFFFFF8C4D679F280683B91003849D01060000D09ACF9C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000006AC69C0000000068C88A9B60000000306AC69C040000001069C69C9C4D679F7824119E04000000B04D679F8C39409F82010000C0D59D9C010000000000000082FFFFFF006AC69C88FFFFFF2C4E679F60C371BA24FA839D01070000006AC69C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013A19D85FFFFFFD09ACF9C85FFFFFF00000000204E679F1C4E679F88FFFFFF70000000D069C69C300DC59C8401249E000000000000000004000000504E679F8C39409F8201000040D69D9C010000001023DB9A88FFFFFF4066C69C88FFFFFFAC4E679F90FD5CBA90F3839D010500004066C69C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFF
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F674E80 300DC59C01000000DC4E679FF44E679F50000000509E6A9B03020000E0A393BACC4E679FC823119E00000000E04E679FDC8D079F820200008016099D030000000000000082FFFFFF4066C69C88FFFFFF0000000081FFFFFF300DC59C88FFFFFF7C4F679F38D932B9E8F20A9F01090000300DC59C88FFFFFF0000000081FFFFFF4066C69C88FFFFFF0000000082FFFFFF8016099D88FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF70321B9C88FFFFFF0000000082FFFFFF0900000081FFFFFF300DC59C88FFFFFF800DC59C00000000AC4F679FC0D6929D9000000020C0929D1069C69C0302000090C5A9B90100000000000000A04F679F8C39409F82010000B002939D01000000300DC59C88FFFFFF8016099D88FFFFFF2450679F48C1A9B900ED839D810700008016099D88FFFFFF300DC59C88FFFFFFB002939D88FFFFFF800DC59C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFF800DC59C88FFFFFF0000000082FFFFFF4850679F382F409F
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675000 000000000C50679F78000000509E6A9B0000000054E3839D4203000003000000000000005050679F8C39409F02020000A016099D02000000B068EE9A88FFFFFF501BF09C88FFFFFF300DC59C88FFFFFFBC50679F2032BAB920E8839D01060000300DC59C88FFFFFF501BF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFFCC51409F0451679F0851679F0000000060000000509E6A9BF050679F000000001069C69C0302000000000000E850679F8C39409F02020000E016099D020000000037949D88FFFFFF501BF09C88FFFFFF4007C59C88FFFFFF8451679F70C5E2B9FC64429F010900004007C59C88FFFFFF501BF09C88FFFFFF0037949D88FFFFFFE016099D88FFFFFF0000000082FFFFFF0000000082FFFFFF109CCF9C85FFFFFFE00CC59C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF40B4C29C88FFFFFF1069C69C88FFFFFF603F979D01000000900000001066C69C8C51679F7C51679F08457E9E00000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675180 04000000D453679F08FF069F000400008036949D010000000037949D88FFFFFF501BF09C88FFFFFF0000000082FFFFFFF04A7E9E501BF09CE065C69CB065C69C0000000087FFFFFFA00F939D8065C69CB065C69C20B4C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFF8065C69C88FFFFFF3852679F8065C69C2065C69C5065C69CFC000F9F800200000037949D000000002065C69C88FFFFFFB009C19C8A00000007000000C009C19C905DF3B840B0929D905AC99C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFF905AC99C85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB61054679F0100000081FFFFFF6853679FD453679F14E4169E603F979D00000000000000003853679FEC52679F38673F9F58FB749E905DF3B8682CF9B85464679F0000000000000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675300 00000000010000003C5B679F905DF3B80001000000000000B0FF0E9F00000000603F979DC857679F020000000100000000000000000000000100000081FFFFFF0000000000000000A057679FF6FFFFFF9C5DF3B801000000905DF3B86853679F0000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000001054679F905DF3B8785B7E9E80829A9D000000003056B8BAD453679F667ADB3600000000905DF3B81054679FD853679F603F979D80829A9D000000003056B8BAFC53679F2C85349E000000000000000000000000E44DFCB601000000905DF3B8D057679F0854679F8457679F2486349E423A77B9EB3B77B9D057679F01000000E82C749E0100000080829A9D0854679F00000000003C77B90200000002000000010000000000000080DA739E5C00000006000000000000004063679F00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F03177B90000000000000000010000000200000080B3C29C80839A9D8D0317B90000000000000000667ADB3600000000E44DFCB600000000905DF3B8C8DA269EA055679F1C59679FA886349E0000000000000000C059679F0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675600 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB36E44DFCB6C057679F905DF3B87058679FD057679F3056B8BA
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675780 2C58679FE48A349E00000000000000000000000040B0929DD057679F01000000B064679FF6FFFFFF9C5DF3B800000000905DF3B8C057679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFF905AC99C85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB3613000000905DF3B88058679F7058679F7858679F6C58679F82FFFFFF2856B8BA5C58679F3875249E2856B8BA7858679F40B0929D88FFFFFFBC58679FF058679FD059679F010000008858679F00000000BC58679F200B469E7858679F000000000000000040B0929D603F979D88FFFFFF0000000082FFFFFF010000002856B8BA0000000082FFFFFF905DF3B8000000006C375F9EF058679FE058679F38CDBAB8D0CFBAB8905DF3B8D059679F6C375F9E2C59679FB81A3D9EF058679F000000C0D055B8BA5052AFBA4459679F8D61F9B6DC55B8BA0000000040B0929D88FFFFFF905DF3B800000000905AC99C85FFFFFF905DF3B800000000
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675900 4059679F1890609EFD55B8BA6059679FD059679F5059679F905DF3B84459679F2200000038CDBAB89459679FEC8A3E9EE4F85E9E50FC5E9E58FB749E22000000DC55B8BAC455B8BA000000006459679F2200000000000000E85A679F000000007C59679F1455FC9D185A679FE85A679F18E1759EE059679F0000000001000000D059679FC059679F22000000905DF3B8245B679F28B4419E9855B8BA00000000905DF3B8B059679F02000000F859679F001BF09C185A679F7060C69C88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000905DF3B801000000485B679F585B679F010000009855B8BA0700000007000000010000003059C99C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF00000000A855B8BA220000003859C99C0700000000000000010000001800A09DC84098B901000000845A679FE0CA2E9E070000003059C99C905DF3B8000000001000A09D905A679F
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675A80 C45A679FE80C2F9E0000000000000000000000000CD40E9FF85A679F0100000000000000F064C69CE01BA19D3059C99C00000000FFFFFFFFC84098B901000000605B679FB0D40E9FB85B679FD45A679F205B679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFF3059C99C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF384198B901000000605B679F382F409F00000000345B679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFF3059C99C85FFFFFFBC5B679F384198B9882C439F010500003059C99C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFFEC5B679F045C679F00000000E05B679F8C39409F820100008086969D010000000000000082FFFFFF3059C99C85FFFFFF8C5C679FA029A5B92CDC379F010A00003059C99C85FFFFFF0000000082FFFFFF
08-26 15:00:03.574  6949  6949 W google-breakpad: S 9F675C00 8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFFA063C69C0302000000000000B85C679F8C39409F02020000C04C969D02000000A0C6959D88FFFFFF3059C99C85FFFFFF00B4C29C88FFFFFF2C5D679F18B242B9EC1D849D81060000F0D9A19D85FFFFFF3059C99C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000105D679F0000000083FFFFFF6800000060CA329B3859C99C010000003000000060CA329B00000000505D679F8C39409F8201000040D59D9C010000000000000082FFFFFF3059C99C85FFFFFFD45D679F00D494B92C16849D810700003059C99C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F675D80 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFF05D679FE85D679FE05D679F545E679F7800000060CA329B000000006638D3BA58FB749E905DF3B800000000F85D679F8C39409F8201000080D59D9C010000000000000082FFFFFF3059C99C85FFFFFF645E679FC00146B90C0C849D010600003059C99C85FFFFFF0000000082FFFFFF80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000705E679F885E679F040000006000000060CA329B904E65BA01000000F45E679FF8EF3F9F00000000885E679F8C39409F82010000A0D59D9C010000000000000082FFFFFF3059C99C85FFFFFFF45E679F280683B91003849D010600003059C99C85FFFFFF0000000082FFFFFFA0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF000000009064C69C0000000068C88A9B60000000C064C69C04000000A063C69C045F679F7824119E04000000185F679F8C39409F82010000
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F675F00 C0D59D9C010000000000000082FFFFFF9064C69C88FFFFFF945F679F60C371BA24FA839D010700009064C69C88FFFFFF0000000082FFFFFFC0D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013A19D85FFFFFF3059C99C85FFFFFF00000000885F679F845F679F88FFFFFF700000006064C69CA006C59C8401249E000000000000000004000000B85F679F8C39409F8201000040D69D9C010000001023DB9A88FFFFFFD060C69C88FFFFFF1460679F90FD5CBA90F3839D01050000D060C69C88FFFFFF1023DB9A88FFFFFF40D69D9C88FFFFFFC0D3A19D85FFFFFFA006C59C010000004460679F5C60679F50000000509E6A9B03020000E0A393BA3460679FC823119E000000004860679FDC8D079F820200008016099D030000000000000082FFFFFFD060C69C88FFFFFF0000000081FFFFFFA006C59C88FFFFFFE460679F38D932B9E8F20A9F01090000A006C59C88FFFFFF0000000081FFFFFFD060C69C88FFFFFF0000000082FFFFFF8016099D88FFFFFF
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676080 0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF00321B9C88FFFFFF0000000082FFFFFF0900000081FFFFFFA006C59C88FFFFFFF006C59C000000001461679FC0D6929D9000000020C0929DA063C69C0302000090C5A9B901000000000000000861679F8C39409F82010000B002939D01000000A006C59C88FFFFFF8016099D88FFFFFF8C61679F48C1A9B900ED839D810700008016099D88FFFFFFA006C59C88FFFFFFB002939D88FFFFFFF006C59C88FFFFFFC0D6929D88FFFFFFC0D0929D88FFFFFF0000000082FFFFFFF006C59C88FFFFFF0000000082FFFFFFB061679F382F409F000000007461679F78000000509E6A9B0000000054E3839D420300000300000000000000B861679F8C39409F02020000A016099D02000000B068EE9A88FFFFFF001BF09C88FFFFFFA006C59C88FFFFFF2462679F2032BAB920E8839D01060000A006C59C88FFFFFF001BF09C88FFFFFFB068EE9A88FFFFFFA016099D88FFFFFF0000000082FFFFFF0000000082FFFFFFCC51409F6C62679F
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676200 7062679F0000000060000000509E6A9B5862679F00000000A063C69C03020000000000005062679F8C39409F02020000E016099D020000000037949D88FFFFFF001BF09C88FFFFFFB000C59C88FFFFFFEC62679F70C5E2B9FC64429F01090000B000C59C88FFFFFF001BF09C88FFFFFF0037949D88FFFFFFE016099D88FFFFFF0000000082FFFFFF0000000082FFFFFF705AC99C85FFFFFF5006C59C88FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFA0B3C29C88FFFFFFA063C69C88FFFFFF603F979D0100000090000000A060C69CF462679FE462679F08457E9E00000000040000003C65679F08FF069F000400008036949D010000000037949D88FFFFFF001BF09C88FFFFFF0000000082FFFFFFF04A7E9E001BF09C7060C69C4060C69C0000000087FFFFFFA00F939D1060C69C4060C69C80B3C29CE0DD0E9F80020000C036949D020000000000000082FFFFFFA00F939D88FFFFFF1060C69C88FFFFFFA063679F1060C69CA0DFC69CD0DFC69CFC000F9F80020000
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676380 0037949D00000000A0DFC69C88FFFFFF7039C89C8A000000070000008039C89C905DF3B840B0929DA009C19C0037949D20683F9F03020000603F979D0100000040B0929D88FFFFFFA009C19C85FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000905DF3B8E44DFCB67865679F0100000081FFFFFFD064679F3C65679F14E4169E603F979D0000000000000000A064679F5464679F38673F9F58FB749E905DF3B8682CF9B8BC75679F00000000000000000000000001000000A46C679F905DF3B80001000000000000B0FF0E9F00000000603F979D3069679F020000000100000000000000000000000100000081FFFFFF00000000000000000869679FF6FFFFFF9C5DF3B801000000905DF3B8D064679F0000000008000000000000000000000000000000000000000000000000000000000000000000000000000000010000007865679F905DF3B8
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676500 785B7E9E80829A9D00000000F050B8BA3C65679F667ADB3600000000905DF3B87865679F4065679F603F979D80829A9D00000000F050B8BA6465679F2C85349E000000000000000000000000E44DFCB601000000905DF3B83869679F7065679FEC68679F2486349E423A77B9EB3B77B93869679F01000000E82C749E0100000080829A9D7065679F00000000003C77B90200000002000000010000000000000080DA739E5C0000000600000000000000A874679F000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676680 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000F03177B900000000000000000100000002000000E0B2C29C80839A9D8D0317B90000000000000000667ADB3600000000E44DFCB600000000905DF3B8C8DA269E0867679F846A679FA886349E0000000000000000286B679F00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676800 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB36E44DFCB62869679F905DF3B8D869679F3869679FF050B8BA9469679FE48A349E00000000000000000000000040B0929D3869679F010000001876679FF6FFFFFF9C5DF3B800000000905DF3B82869679F0300000008000000603F979D88FFFFFF40B0929D88FFFFFFA009C19C85FFFFFF0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000667ADB3613000000905DF3B8E869679FD869679F
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676980 E069679FD469679F82FFFFFFE850B8BAC469679F3875249EE850B8BAE069679F40B0929D88FFFFFF246A679F586A679F386B679F01000000F069679F00000000246A679F200B469EE069679F000000000000000040B0929D603F979D88FFFFFF0000000082FFFFFF01000000E850B8BA0000000082FFFFFF905DF3B8000000006C375F9E586A679F486A679F38CDBAB8D0CFBAB8905DF3B8386B679F6C375F9E946A679FB81A3D9E586A679F000000C09050B8BA5052AFBAAC6A679F8D61F9B69C50B8BA0000000040B0929D88FFFFFF905DF3B800000000A009C19C85FFFFFF905DF3B800000000A86A679F1890609EBD50B8BAC86A679F386B679FB86A679F905DF3B8AC6A679F2200000038CDBAB8FC6A679FEC8A3E9EE4F85E9E50FC5E9E58FB749E220000009C50B8BA8450B8BA00000000CC6A679F2200000000000000506C679F00000000E46A679F1455FC9D806B679F506C679F18E1759E486B679F0000000001000000386B679F286B679F22000000905DF3B88C6C679F28B4419E
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676B00 5850B8BA00000000905DF3B8186B679F02000000606B679FB01AF09C806B679FF0DAC69C88FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000905DF3B801000000B06C679FC06C679F010000005850B8BA0700000007000000010000004008C19C00000000905DF3B80000000000000000060000003CE1759E3CE1759E0600000018E1759E00000000FFFFFFFF000000006850B8BA220000004808C19C0700000000000000010000001800A09DC84098B901000000EC6B679FE0CA2E9E070000004008C19C905DF3B8000000001000A09DF86B679F2C6C679FE80C2F9E0000000000000000000000000CD40E9F606C679F010000000000000070DFC69CE01BA19D4008C19C00000000FFFFFFFFC84098B901000000C86C679FB0D40E9F206D679F3C6C679F886C679F000000000000000078D40E9F4003000001000000FFFFFFFF81FFFFFF4008C19C85FFFFFF1000A09D85FFFFFF000000006049969D88FFFFFF882C439F00000000FFFFFFFF
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676C80 384198B901000000C86C679F382F409F000000009C6C679F8C39409F0000000000000000882C439F42020000010000006049969D88FFFFFF00EA929D88FFFFFF4008C19C85FFFFFF246D679F384198B9882C439F010500004008C19C85FFFFFF00EA929D88FFFFFF6049969D88FFFFFF0000000082FFFFFF0000000028D1869D40020000000000005000000030BD929DF0D9A19D85FFFFFF546D679F6C6D679F00000000486D679F8C39409F820100008086969D010000000000000082FFFFFF4008C19C85FFFFFFF46D679FA029A5B92CDC379F010A00004008C19C85FFFFFF0000000082FFFFFF8086969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007A09D85FFFFFFF0D9A19D85FFFFFF82FFFFFF58387E9EF0FBA19D1CDC839DA000000030BD929D0000000083FFFFFF20DEC69C0302000000000000206E679F8C39409F02020000
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676E00 C04C969D02000000A0C6959D88FFFFFF4008C19C85FFFFFF60B3C29C88FFFFFF946E679F18B242B9EC1D849D81060000F0D9A19D85FFFFFF4008C19C85FFFFFFA0C6959D88FFFFFFC04C969D88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000786E679F0000000083FFFFFF6800000060CA329B4808C19C010000003000000060CA329B00000000B86E679F8C39409F8201000040D59D9C010000000000000082FFFFFF4008C19C85FFFFFF3C6F679F00D494B92C16849D810700004008C19C85FFFFFF0000000082FFFFFF40D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF586F679F506F679F486F679FBC6F679F7800000060CA329B000000006638D3BA58FB749E905DF3B800000000606F679F8C39409F8201000080D59D9C010000000000000082FFFFFF4008C19C85FFFFFFCC6F679FC00146B90C0C849D010600004008C19C85FFFFFF0000000082FFFFFF
08-26 15:00:03.584  6949  6949 W google-breakpad: S 9F676F80 80D59D9C88FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D86F679FF06F679F040000006000000060CA329B904E65BA010000005C70679FF8EF3F9F00000000F06F679F8C39409F82010000A0D59D9C010000000000000082FFFFFF4008C19C85FFFFFF5C70679F280683B91003849D01060000
08-26 15:00:03.584  6949  6949 W google-breakpad: C 060000402883F3B80000000074F0669FF0F0669F48F0669F9CF0669F905DF3B874F0669FE02EB29C85FFFFFF38CDBAB86CF0669F30F0669F38F0669F7849249E7C49249E10000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,08-26 15:00:03.584  6949  6949 W google-breakpad: M B6FE6000 00000000 00003000 C076D4C24C77979D0F88BE887CB5F0160 app_process32
08-26 15:00:03.584  6949  6949 W google-breakpad: M 9DCFD000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A0652000 00000000 0000A000 22DE2F7A850976271F596FD7120471AC0 libqservice.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A065C000 00000000 00009000 EC3B3774E5CB032EE6BC192244EC0E1A0 libqdutils.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A0665000 00000000 00006000 91673970C17AB2DD7AB97FE633A7CC7F0 libmemalloc.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A066B000 00000000 00007000 FA30956B63451E4E9F4B6C7001FBD0F90 gralloc.msm8916.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A0BE1000 00000000 00003000 C92C8D5B6B698181A7DD1FB7E563E88A0 libqdMetaData.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A2554000 00000000 0046A000 F1E6740F7B2AC1EADD232024D3726E350 libsc-a3xx.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M A4E58000 00000000 01AEE000 6DC83C69BA92FC15D9BFC15CAA444FA30 libwebviewchromium.so
08-26 15:00:03.584  6949  6949 W google-breakpad: M AD715000 00000000 00009000 15E68926F10C52B9E1C918455B33395D0 librs_jni.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEE52000 00000000 00006000 DCD8843E6E58F548A2F9F918E0F2250C0 libaudioeffect_jni.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEE58000 00000000 00004000 430912DAAB9CCB0652C6C67ED71BD34A0 libsoundpool.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEEBF000 00000000 0000E000 65B4EE8C28DFCF943EF3BAB5CE2CF57E0 libstagefright_amrnb_common.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEECD000 00000000 0001A000 F596654166444B073C7B57DA85DDA86F0 libvorbisidec.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEEE7000 00000000 00004000 840EEE8827F765C9EEB69A82A5385D860 libstagefright_yuv.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEEEB000 00000000 00020000 6A5DDC8F80D9496F56416E0CDC30C7860 libstagefright_omx.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEF0B000 00000000 00003000 03B0255D304C04BA1CB893EF055C0D880 libstagefright_enc_common.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEF0E000 00000000 00007000 BE9998F628EA6A5C32345D001998B9DE0 libstagefright_avc_common.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEF15000 00000000 0000B000 E431EED302BEFED523DB8D7341DEEFBD0 libsfextcp.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEF20000 00000000 0000A000 BBE7244283F7E662D7E34D745C8451F80 libsecuibc.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEF2A000 00000000 0005F000 098C11FE4C1E5783837B86006532FAB50 libsavsff.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEF8D000 00000000 0004E000 DF97B63F6B72A8BB76A1D8FBA29896010 libsavscmn.so
08-26 15:00:03.594  6949  6949 W google-breakpad: M AEFDC000 00000000 00005000 89B5E9B7BF6412D458C721055A152C4A0 libpowermanager.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AEFE1000 00000000 00039000 34D438FC59A243B4B79B29B3300A98C30 libopus.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF01A000 00000000 0001C000 1DA76B6D81AB593736F5F89F03BB089E0 libdrmframework.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF036000 00000000 003B4000 BD3C4CE5F3F0FA413707AB0A9757E0830 libMMFW_scone_stub.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF3F5000 00000000 00164000 4320EC321DE6EADC7528366646D5CA740 libstagefright.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF559000 00000000 00014000 C2FFC5B6A88CE765BBB0762DF08836520 libmtp.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF56D000 00000000 0000B000 F8D7FA4760673A60E9A957A1FF0991BD0 libjhead.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF579000 00000000 0002C000 7FE1E6C0CA754D8F79E50A1CB5A2F4AF0 libexif.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF5A6000 00000000 0003C000 07D5EEA8D30C78E1DBD86B63E0447FA50 libmedia_jni.so
08-26 15:00:03.604  6949  6949 W google-breakpad: M AF5E2000 00000000 0001B000 409A264B865DAA353D92FE1A41BA42010 libjavacrypto.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M AF6B1000 00000000 00141000 A2F46E5CA0880CEF1C04E302488BB4E60 libGLESv2_adreno.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M AF7F3000 00000000 00034000 684DED99CC59C3906C82B7457EDB45F00 libGLESv1_CM_adreno.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M AF827000 00000000 00035000 D4318DD5004755DA26AE6B0BBAF281DE0 libgsl.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M AF85C000 00000000 0002A000 020C64D887DAD39ADBA1263F72513FED0 libEGL_adreno.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0A77000 00000000 00010000 C7EB647818605F38532F9A290DDB69010 libandroid.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0A8E000 00000000 00004000 7969E81D0F5763BFDBC09C2B6D2F08250 libadreno_utils.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0C99000 00000000 00003000 07E50F790CF258618C54CBF3C74A6A1E0 libwebviewchromium_loader.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0C9C000 00000000 00003000 1042592D6A7B2C021C7008CB35D370AA0 libjnigraphics.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0C9F000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0CA7000 00000000 00003000 B4D861A3F3ACFD7D321C59CB7177B7ED0 libqti-perfd-client.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0CAA000 00000000 00003000 900F180B6ED1813B019148541FEBC4850 memtrack.msm8916.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B0CC2000 00000000 0000B000 77FE3A801397BE328D22A2C6CEDD5D190 eglsubAndroid.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B23D0000 00000000 00038000 032BBF3A646CEC0E92F02F2607486BCA0 libjavacore.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B4923000 00000000 00004000 D8D9004A312C20C7AEAEE0BE3D460C970 libwebviewchromium_plat_support.so
08-26 15:00:03.614  6949  6949 W google-breakpad: M B4EB0000 00000000 00008000 BABBF80B8FC90D8583D80A696A57B2130 libbacktrace_libc++.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B4EB8000 00000000 002FE000 E28D8FF4E9F5563C0B0777FF0B95B6720 libart.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B51D8000 00000000 00004000 62EFD3D29964E6B599D4FAE01272421C0 libusbhost.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B51DC000 00000000 0003F000 8F93763230E70AC1012CE2797EBDCD180 libssl.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B521B000 00000000 0000E000 5531DBDE929DBC5D9C2D2973F0ACB63E0 libsoundtrigger.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5229000 00000000 00012000 F53050926856F9ED174D0B9FB54900510 libpcre.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B523B000 00000000 00012000 094A62A7F00C732AD95FB394CA44D7300 libselinux.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B524D000 00000000 00004000 099B10F2EAA0144B6769F0BF764BE16D0 libprocessgroup.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5251000 00000000 00447000 F96B93C6164BBEFDAF535E909BE475720 libpdfium.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B569D000 00000000 00004000 2C94DBD2926E0C0A51C840F6C94B0A120 libnetd_client.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56A1000 00000000 00007000 8870FC1A3B0A0C618D77747DF2C5239F0 libnativehelper.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56A8000 00000000 00004000 BF30FE88A9C8EE464CC8F0BB519494960 libnativebridge.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56AC000 00000000 0000B000 0984D19CFFD7280D6559EA579517C0560 libminikin.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56B7000 00000000 00003000 E8D81805B27BF1C2BADC1C385C9D44110 libmemtrack.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56BA000 00000000 00014000 AB30B4F28663E54089CB0393F16EC42A0 libstagefright_foundation.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56CE000 00000000 00009000 DF257BF35EC3333D10EF36A5C95A55CE0 libsec_km.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56D8000 00000000 00007000 09E0E8E3AC05172EE6B3DC26270D49F70 libsdp_crypto.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56DF000 00000000 00004000 678D29883C80386905E16BBCE7CF2E570 libpersona.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B56E4000 00000000 00085000 176AE350351B5C616895DE24B70FE7570 libsqlite.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B576B000 00000000 00050000 2FF9202116C3611BE6EFBD00407235750 libomafldrm.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B57BC000 00000000 00050000 F8171C0B0A8FBD6C5438EA18037AAFE80 libsonivox.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5811000 00000000 00005000 B928740DB1DCEFFD56EE67AE84B8EFC10 libsecnativefeature.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5816000 00000000 00008000 C04C622FA1AEFB29F88FEED961B34D680 lib_SamsungVAD_v01007.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5820000 00000000 00003000 E8AD41C2097B7B0A26463F3E900952FE0 libsamsungvad.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5823000 00000000 0000F000 0F206C184F10DAF8B580B1CA47FA6EC80 libcommon_time_client.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5832000 00000000 0000A000 ADDFBB302FF2440C1B86D12D70317C8F0 libnbaio.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B583C000 00000000 000BD000 BE2C9C97A647438CAB5EE6F3F9C6EB610 libmedia.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B58FA000 00000000 00040000 E7102D00C0372AA9E97071DD4BF6FDCC0 libinputflinger.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B593A000 00000000 0001B000 BB5BED8E5ADF4A119D5B2DA31DBAEC580 libinput.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5955000 00000000 0000D000 C17942DF5B7EBECE9049E849149CA1120 libimg_utils.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5962000 00000000 0001E000 18C32F00634AB7BB4010F2D59861567F0 libquramimagecodec.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5980000 00000000 00032000 8F255D73F53B095B1764C82186FE28FC0 libjpeg.so
,08-26 15:00:03.624  6949  6949 W google-breakpad: M B59B2000 00000000 00264000 4DCD73A518FC633987387494509BE53D0 libskia.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5C1C000 00000000 00011000 5F14FC290F6EBD6AFCC7BDA3F439C3E90 libsamsungeffect.so,
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5C2D000 00000000 0001D000 90BC6412D2B13FFD96428D1B517BEDD00 libRScpp.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5C4B000 00000000 00027000 CA02F8123591B96EE9266BAA11675EEA0 libpng.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5C73000 00000000 00059000 54828C4F4B56D81127BD1BAF9A48D64E0 libft2.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5CCC000 00000000 0003C000 A0A13C2D329CE4F443247914FBF76EA40 libbcinfo.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5D08000 00000000 00022000 E421E96697C14EB985E7F06B412DFB2B0 libbcc.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5D4A000 00000000 0008C000 D2E4B8E2C12DFE9B2752E15EF016991E0 libc++.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B5DD7000 00000000 008FE000 1E521DDD13333E86CCC3043C7BB1C7EF0 libLLVM.so
,08-26 15:00:03.624  6949  6949 W google-breakpad: M B66DC000 00000000 00036000 2F058C02160C453D2C194C7A4498C7510 libRS.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6712000 00000000 00051000 7A9A46F8FEF9C704ACEEEFE03C2F36DE0 libhwui.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6763000 00000000 000FF000 24D205C2C90637FA33CF50299F7199690 libicuuc.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6866000 00000000 00006000 6AC3328D55BE7167DD1549E59E88D8420 libgabi++.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B686C000 00000000 0014A000 30D014A51C507F017588CD57CC7ABDAD0 libicui18n.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B69B6000 00000000 00048000 58C7C20B9121CD68E9A3B78D8C6CF7190 libharfbuzz_ng.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B69FE000 00000000 00005000 1AB401385CC88F656E0CB80273DA89860 libwpa_client.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6A03000 00000000 00007000 ACC103A77586F28DE7F6DA309DF82D320 libnetutils.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6A0A000 00000000 00007000 67762CE3DAA2297C6E0F58843AAAB3910 libhardware_legacy.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6A12000 00000000 00017000 D1B3203E3493EE80553E5CF9C9905E320 libexpat.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6A29000 00000000 00142000 2727DE264BD767080C4068EDB1F581960 libcrypto.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6B6D000 00000000 00003000 6E72A700CCC315909A66D3E4D2AAAE410 libcc_manager.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6B70000 00000000 00003000 7C24A254F6B1768D1FF8ADFB9A8A11500 libsync.so
,08-26 15:00:03.624  6949  6949 W google-breakpad: M B6B73000 00000000 00003000 0C360DD265129CA1197EE36C44A162570 libhardware.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6B77000 00000000 0000C000 AB61E5F34C506C41C8ACF65F1DF7A7690 libui.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6B83000 00000000 0000B000 3EBFA8F358F7A386E377C708170C6A0B0 libremotedesktop_client.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6B8E000 00000000 0004C000 D41F8C8CDABD00A9D5F6E03D9131C6FE0 libgui.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6BDA000 00000000 00008000 D86968593275725A009907DF162762E60 libcamera_metadata.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6BE2000 00000000 00041000 8F4B2C50A29960551F2159E0DAB20E260 libcamera_client.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6C23000 00000000 00006000 20E951BEE083EAAC8A0EC8C9659BC90C0 libspeexresampler.so
08-26 15:00:03.624  6949  6949 W google-breakpad: M B6C29000 00000000 00006000 556F9F9B6E57A78532BC16CE0DAFDB920 libaudioutils.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6C2F000 00000000 00019000 6FF245A929534129A0A09E804082C1F90 libz.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6C48000 00000000 0002D000 10C485FADAF2C720FDA5625DC38ABF2A0 libbinder.so
,08-26 15:00:03.634  6949  6949 W google-breakpad: M B6C75000 00000000 00026000 65C138E33F598CC3AF5D7A6804A6293D0 libandroidfw.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6C9B000 00000000 0000D000 FE94ED4BD906E283008A8207B21F731F0 libGLESv2.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6CA8000 00000000 00008000 E20B832545D307124FB21DEB3AFA1EFA0 libGLESv1_CM.so,
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6CB0000 00000000 00004000 C10A3FF24BC314BDB4276E3588B5CFEF0 libETC1.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6CB4000 00000000 00004000 9A82E5E5DC0FF6464E020C95D6C265430 libunwind-ptrace.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6CB8000 00000000 0000E000 FCC4CF7B44EE2AEE89CCE84DDB0A34E30 libunwind.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6D0C000 00000000 00007000 9AD603917CEBD0A26C5300A4455555250 libgccdemangle.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6D15000 00000000 00008000 809C179831A89482ABAEF5D7DAE451C00 libbacktrace.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6D1E000 00000000 00016000 F1EB1C81CF043EF6ACD6D977257B90FA0 libutils.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6D34000 00000000 00036000 A86B4524AFE0B8B31C00A4A9DA14FB720 libstlport.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6D6A000 00000000 0000D000 C5A05BA0312495F273F4D3DF9ECCA8830 libcutils.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6D78000 00000000 0006B000 0003812AEBDD6FD4750BAB0D29164BB90 libGLES_trace.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6DE3000 00000000 0006A000 7F16035A8648874F086D60A0C922D76C0 libEGL.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6E50000 00000000 000F5000 C5F797DCDC70EF17BB357C3E2C8A5E4C0 libandroid_runtime.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6F4A000 00000000 00004000 D44FDF94BA8D734E5BC46C426F7316DE0 libstdc++.so
,08-26 15:00:03.634  6949  6949 W google-breakpad: M B6F4E000 00000000 00018000 3D2BCD0A8F5E726801091CC87EA86DCC0 libm.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6F67000 00000000 00006000 D777457560B88DEC8383D062CA85BD860 liblog.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6F6E000 00000000 00056000 D779447DA8EFA50115E42F43400903DD0 libc.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6FCE000 00000000 00003000 6942576880529816BD6C80C55563D51C0 libsigchain.so
08-26 15:00:03.634  6949  6949 W google-breakpad: M B6FD6000 00000000 0000F000 1A12EEA227DCC44493A0CB9F6FAD897C0 linker
08-26 15:00:03.634  6949  6949 W google-breakpad: -----END BREAKPAD MICRODUMP-----
,08-26 15:00:03.654  6820  6873 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:03.654  6820  6873 W google-breakpad: Chrome build fingerprint:
,08-26 15:00:03.654  6820  6873 W google-breakpad: 0.0.1
08-26 15:00:03.654  6820  6873 W google-breakpad: 19
08-26 15:00:03.654  6820  6873 W google-breakpad: 3287cb47-323f-452a-9071-08e954855982
08-26 15:00:03.654  6820  6873 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:00:03.654  6820  6873 F libc    : Fatal signal 11 (SIGSEGV), code 1, fault addr 0x4 in tid 6873 (Thread-1265)
,08-26 15:00:03.664   282   282 I DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-26 15:00:03.664   282   282 I DEBUG   : Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys'
08-26 15:00:03.664   282   282 I DEBUG   : Revision: '1'
08-26 15:00:03.664   282   282 I DEBUG   : ABI: 'arm'
08-26 15:00:03.664   282   282 I DEBUG   : pid: 6820, tid: 6873, name: Thread-1265  >>> com.test.thalitest <<<
08-26 15:00:03.664   282   282 I DEBUG   : signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
,08-26 15:00:03.684   282   282 I DEBUG   :     r0 b8f38328  r1 00000000  r2 9f66f074  r3 9f66f0f0,
,08-26 15:00:03.684   282   282 I DEBUG   :     r4 9f66f048  r5 9f66f09c  r6 b8f35d90  r7 9f66f074
08-26 15:00:03.684   282   282 I DEBUG   :     r8 9cb22ee0  r9 ffffff85  sl b8bacd38  fp 9f66f06c
,08-26 15:00:03.684   282   282 I DEBUG   :     ip 9f66f030  sp 9f66f038  lr 9e244978  pc 9e24497c  cpsr 200f0010
08-26 15:00:03.684   282   282 I DEBUG   : 
08-26 15:00:03.684   282   282 I DEBUG   : backtrace:
,08-26 15:00:03.684   282   282 I DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-26 15:00:03.684   282   282 I DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
08-26 15:00:03.684   282   282 I DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
,08-26 15:00:03.704   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:00:04.574   282   282 I DEBUG   : 
08-26 15:00:04.574   282   282 I DEBUG   : Tombstone written to: /data/tombstones/tombstone_04
,08-26 15:00:04.574   282   282 E         : ro.product_ship = true
08-26 15:00:04.574   282   282 E         : ro.debug_level = 0x4f4c
08-26 15:00:04.584  2007  2007 E audit   : type=1701 msg=audit(1472216404.584:206): auid=4294967295 uid=10171 gid=10171 ses=4294967295 subj=u:r:untrusted_app:s0 pid=6873 comm="Thread-1265" reason="memory violation" sig=11
,08-26 15:00:04.594  1017  3255 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
08-26 15:00:04.594  1017  1044 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,08-26 15:00:04.634  1017  6950 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,08-26 15:00:04.634  1017  6950 D FocusedStackFrame: Set to : 0
,08-26 15:00:04.634  1017  6950 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 15:00:04.634  1017  6950 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,08-26 15:00:04.634  1017  6950 D InputDispatcher: Focused application set to: xxxx
,08-26 15:00:04.644  1017  6950 D InputDispatcher: Focus left window: 6820
,08-26 15:00:04.644  1017  1048 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:00:04.644   255   255 E lowmemorykiller: Error writing /proc/6820/oom_score_adj; errno=22
08-26 15:00:04.644  1017  6950 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:00:04.644  1017  6950 I ActivityManager: Killing 6555:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 15:00:04.654  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:00:04.654  1017  6950 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-26 15:00:04.654  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:00:04.654  1017  6950 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:00:04.654  1017  6950 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:00:04.654   258  1039 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-26 15:00:04.654   258   443 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-26 15:00:04.674  1017  6950 W ActivityManager: mDVFSHelper.acquire()
,08-26 15:00:04.684   312   312 I Zygote  : Process 6820 exited due to signal (11)
,08-26 15:00:04.684  1017  6950 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 15:00:04.694  1017  1512 I ActivityManager: Process com.test.thalitest (pid 6820)(adj 9) has died(139,710)
,08-26 15:00:04.694  1017  1512 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.am.SmartAdjustManager.SPCMLocked:1235 com.android.server.am.ActivityManagerService.updateOomAdjLocked:22618 com.android.server.am.ActivityManagerService.appDiedLocked:6728 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1579 
,08-26 15:00:04.714  1497  1497 D Launcher: onRestart, Launcher: 487934359
,08-26 15:00:04.714  1497  1497 D Launcher: onStart, Launcher: 487934359
,08-26 15:00:04.714  1497  1497 D Launcher.HomeView: onStart
,08-26 15:00:04.714  1497  1497 D Launcher: onResume, Launcher: 487934359
,08-26 15:00:04.714  1017  1030 D SettingsProvider: name = kids_home_mode
,08-26 15:00:04.714  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:00:04.714  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:00:04.714  1017  1030 D SettingsProvider: selectionArgs: false
08-26 15:00:04.714  1017  1030 D SettingsProvider: selectionArgs: 10006
,08-26 15:00:04.714  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:00:04.714  1017  1030 D SettingsProvider: ret = -1
,08-26 15:00:04.714  1497  1497 D Launcher.HomeView: onResume
,08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Hardware: MSM8916
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Revision: 1
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Bootloader: A300FUXXS1BPE1
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Radio: unknown
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Kernel: Linux version 3.10.49-6027881 (dpi@SWDD6014) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 6 21:20:10 KST 2016
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: 
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXS1BPE1:user/release-keys'
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: Revision: '1'
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: ABI: 'arm'
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: pid: 6820, tid: 6873, name: Thread-1265  >>> com.test.thalitest <<<
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x4
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     r0 b8f38328  r1 00000000  r2 9f66f074  r3 9f66f0f0
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     r4 9f66f048  r5 9f66f09c  r6 b8f35d90  r7 9f66f074
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     r8 9cb22ee0  r9 ffffff85  sl b8bacd38  fp 9f66f06c
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     ip 9f66f030  sp 9f66f038  lr 9e244978  pc 9e24497c  cpsr 200f0010
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d0  9e5f3c4c9da12200  d1  b939ae909f660000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d2  b8f35d90b6fc4d00  d3  9e36af509f66e400
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d4  9f66e39c9d92a640  d5  9f66e3ac9f66e3ac
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d6  9f66e3ac9f66e740  d7  9e1af9849f66e3f4
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d16 0000000000000000  d17 746e65746e6f4365
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     scr 20000012
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: 
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: backtrace:
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z18JS_SetPropertyByIdP9JSContextN2JS6HandleIP8JSObjectEENS2_I4jsidEENS2_INS1_5ValueEEE+44)
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_Z14JS_SetPropertyP9JSContextN2JS6HandleIP8JSObjectEEPKcNS2_INS1_5ValueEEE+132)
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN5MozJS5Value11SetPropertyEPKcN2JS6HandleINS3_5ValueEEE+88)
08-26 15:00:04.724 , 1017  1017 D CrashAnrDetector: 
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: stack:
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efb8  ba3c1f48  [heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efbc  c0000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efc0  00000001  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efc4  ba3c1f50  [heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efc8  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efcc  00000969  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efd0  b8f36cb0  [heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efd4  96917010  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efd8  9f66f014  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efdc  9e056410  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZNK2js6detail9HashTableIKNS_14AtomStateEntryENS_7HashSetIS2_NS_10AtomHasherENS_17SystemAllocPolicyEE6SetOpsES6_E6lookupERKNS5_6LookupEjj+252)
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efe0  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efe4  9f66f080  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efe8  9f66f04c  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66efec  9f66f030  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66eff0  9f66f008  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66eff4  00000007  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66eff8  9e74fb58  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66effc  9e5f3774  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f000  b8f35d90  [heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f004  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f008  ffffff85  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f00c  b8f3c328  [heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f010  9f66f06c  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f014  9e056920  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (_ZN2js7AtomizeEPNS_16ExclusiveContextEPKcjNS_14InternBehaviorE+460)
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f018  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f01c  9f66f030  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f020  b8f35d90  [heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f024  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f028  9e5f376c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f02c  9f66f080  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f030  9e5f3774  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f034  9f66f06c  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:     #00  9f66f038  00000007  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f03c  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f040  00000000  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f044  e6e0b890  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f048  9cb22ee0  [anon:js-gc-heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f04c  ffffff85  
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f050  9da11de0  [anon:js-gc-heap]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f054  b8f35d90  [heap]
08-26 15:00:04.724  ,1017  1017 D CrashAnrDetector:          9f66f058  9f66f0f0  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66f05c  9f66f09c  [stack:6873]
08-26 15:00:04.724  1017  1017 D CrashAnrDetector:          9f66
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: processName:com.test.thalitest
08-26 15:00:04.724  1017  1017 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
08-26 15:00:04.724  6605  6605 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.sm.common.SmartManagerReceiver.b:199 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:93 
08-26 15:00:04.724  1017  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
08-26 15:00:04.724  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-26 15:00:04.724  1017  1221 D ActivityManager: startService callerProcessName:com.samsung.android.sm, calleePkgName: com.samsung.android.sm
08-26 15:00:04.724  1017  1221 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.sm/com.samsung.android.sm.common.notification.CrashedAppLoggingService; callingUser = 0; userId(target) = 0
,08-26 15:00:04.724  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 15:00:04.724  1017  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.724  1017  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.724  1017  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.sm, destAppInfo.processName = com.samsung.android.sm
,08-26 15:00:04.734  1497  1497 D MenuAppsGridFragment: onResume
,08-26 15:00:04.734  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
,08-26 15:00:04.734  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 15:00:04.744  1017  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:00:04.744  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.744  1017  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:00:04.744  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:00:04.754  1017  1495 D ActivityManager: handle home activity for 0
08-26 15:00:04.754  1017  1495 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-26 15:00:04.754  1017  1495 D KnoxTimeoutHandler: post home show event for user 0
08-26 15:00:04.754  1017  1495 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 15:00:04.754  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-26 15:00:04.754  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 15:00:04.754  1017  1495 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:00:04.754  1017  1495 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 15:00:04.754  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 15:00:04.754  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:00:04.754  1497  1497 D Launcher.HomeView: onPause
,08-26 15:00:04.754  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 15:00:04.764  1017  1221 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:00:04.774   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,08-26 15:00:04.774  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 15:00:04.774  1017  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:00:04.774  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.774  1017  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:00:04.774  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:00:04.784  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 15:00:04.784  1017  1135 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.784  1017  1135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.784  1017  1135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-26 15:00:04.784  1017  1029 D InputDispatcher: Focus entered window: 1497
,08-26 15:00:04.784  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:00:04.784  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:00:04.784  1497  1497 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 15:00:04.794  1017  1322 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,08-26 15:00:04.794  1017  1322 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-26 15:00:04.794  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.794  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.794  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-26 15:00:04.794  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.794  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.794  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-26 15:00:04.804  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,08-26 15:00:04.804  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.804  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.804  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.804  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:04.814  6956  6956 E Zygote  : MountEmulatedStorage(),
08-26 15:00:04.814  6956  6956 I libpersona: KNOX_SDCARD checking this for 10089
08-26 15:00:04.814  6956  6956 E Zygote  : v2
08-26 15:00:04.814  6956  6956 I libpersona: KNOX_SDCARD not a persona
08-26 15:00:04.814  1497  1497 D Launcher.HomeView: onStop
08-26 15:00:04.814  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{37d9e80 token=android.os.BinderProxy@297a593a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true,
,08-26 15:00:04.814  6956  6956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:04.824  1017  1221 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
,08-26 15:00:04.824  1017  6961 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
08-26 15:00:04.824  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6956 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a,
08-26 15:00:04.824  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.824  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
08-26 15:00:04.824  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-26 15:00:04.824  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-26 15:00:04.824  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.824  6956  6956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:00:04.824  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:04.824  6956  6956 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-26 15:00:04.824  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.824  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 15:00:04.824  1017  1221 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6820 uid 10171
08-26 15:00:04.834  1176  1176 I StatusBar: Icon Only
08-26 15:00:04.834  1176  1176 D PanelView: There is/are notification(s) 
,08-26 15:00:04.834  6969  6969 E Zygote  : MountEmulatedStorage()
08-26 15:00:04.834  6969  6969 I libpersona: KNOX_SDCARD checking this for 10139
08-26 15:00:04.834  6969  6969 E Zygote  : v2
08-26 15:00:04.834  6969  6969 I libpersona: KNOX_SDCARD not a persona
08-26 15:00:04.834  6969  6969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 15:00:04.844  1868  1868 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 15:00:04.844  6969  6969 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:00:04.844  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6969 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
08-26 15:00:04.844  6969  6969 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:00:04.844  1017  1322 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.844  1017  1322 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-26 15:00:04.844  1017  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.844  1017  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-26 15:00:04.844  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.844  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.844  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:04.844  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:04.854  1497  1497 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@297a593a time:130785
,08-26 15:00:04.864  6956  6956 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:04.864  6982  6982 E Zygote  : MountEmulatedStorage()
08-26 15:00:04.864  6982  6982 E Zygote  : v2
08-26 15:00:04.864  6982  6982 I libpersona: KNOX_SDCARD checking this for 10039
08-26 15:00:04.864  6982  6982 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:04.864  6982  6982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:04.874  6982  6982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 15:00:04.874  6956  6956 D ActivityThread: Added TimaKeyStore provider,
,08-26 15:00:04.874  6982  6982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:00:04.874  1017  1322 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6982 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-26 15:00:04.874  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:00:04.884  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.884  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:00:04.884  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:00:04.884  6969  6969 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:04.894  6969  6969 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:04.894  6982  6982 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:00:04.894  1017  1322 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1497, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
08-26 15:00:04.894  1017  1322 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.894  1017  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.894  1017  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
08-26 15:00:04.894  6982  6982 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:04.894  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.894  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.894  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-26 15:00:04.904  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:00:04.904  2545  2545 D Recents_RecreateReceiver: onReceive by home
08-26 15:00:04.904  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.904  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:00:04.904  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:00:04.904  6956  6956 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:00:04.904  6956  6956 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-26 15:00:04.914  1017  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:00:04.914  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.914  1017  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:00:04.914  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:00:04.924  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{399979ff u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:130855
08-26 15:00:04.924  1017  1048 W ActivityManager: mDVFSHelper.release()
,08-26 15:00:04.924  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.924  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.924  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
08-26 15:00:04.924  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-26 15:00:04.934  6969  6969 V TaskCloserActivity: TaskCloserActivity enter()
,08-26 15:00:04.934  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.934  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.934  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.934  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 15:00:04.944  6982  6982 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 15:00:04.954  7004  7004 E Zygote  : MountEmulatedStorage()
08-26 15:00:04.954  7004  7004 E Zygote  : v2
08-26 15:00:04.954  7004  7004 I libpersona: KNOX_SDCARD checking this for 10084
08-26 15:00:04.954  7004  7004 I libpersona: KNOX_SDCARD not a persona
08-26 15:00:04.954  6969  6969 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-26 15:00:04.954  7004  7004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 15:00:04.954  7004  7004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:00:04.954  7004  7004 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,08-26 15:00:04.954  1017  1029 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7004 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-26 15:00:04.964  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:04.964  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.964  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-26 15:00:04.964  4748  6954 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-26 15:00:04.984  7004  7004 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:04.984  1017  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:00:04.984  1017  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:04.984  1017  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
08-26 15:00:04.984  1017  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,08-26 15:00:04.984  7004  7004 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:04.984  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:04.984  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.984  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:00:04.984  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:00:05.004  7020  7020 E Zygote  : MountEmulatedStorage(),
08-26 15:00:05.004  7020  7020 E Zygote  : v2
08-26 15:00:05.004  7020  7020 I libpersona: KNOX_SDCARD checking this for 10135
08-26 15:00:05.004  7020  7020 I libpersona: KNOX_SDCARD not a persona
,08-26 15:00:05.004  1017  1221 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7020 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,08-26 15:00:05.004  7020  7020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 15:00:05.004  7020  7020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 15:00:05.004  7020  7020 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:00:05.024  7020  7020 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:00:05.024  7020  7020 D ActivityThread: Added TimaKeyStore provider
,08-26 15:00:05.034   312   312 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 765us total 30.131ms
,08-26 15:00:05.034  7004  7004 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:00:05.044  4748  6954 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,08-26 15:00:05.044   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 17.299ms
08-26 15:00:05.044  7020  7020 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-26 15:00:05.044  7020  7020 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:00:05.044  7020  7020 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-26 15:00:05.044  7020  7020 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-26 15:00:05.044  7020  7020 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 15:00:05.054  1017  1536 I ActivityManager: Killing 6578:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 15:00:05.064  1017  4337 I ActivityManager: Killing 6431:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-26 15:00:05.064   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 571us total 16.706ms
,08-26 15:00:05.084   291   291 E SMD     : DCD OFF
,08-26 15:00:05.094  1017  3262 I ActivityManager: Killing 6623:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-26 15:00:05.114  6982  6982 D NearbySource: Nearby Source Create!,
08-26 15:00:05.114  6982  6982 D NearbyContext: Nearby Context Create!
,08-26 15:00:05.154   257   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-26 15:00:05.154   257   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:00:05.154  6982  6982 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache,
,08-26 15:00:05.154  6982  6982 D SLinkSource: Samsung link source created
,08-26 15:00:05.214  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:00:05.214  6982  7037 D ContactProvider: getAllContactInfoList Start
,08-26 15:00:05.214  1017  4337 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:00:05.224  6982  6982 D GalleryCacheReady: Receive : home resume
,08-26 15:00:05.224  1017  1322 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:05.224  1017  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:05.224  1017  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-26 15:00:05.244  6136  6136 D Mms/UIEventReceiver: ui event
,08-26 15:00:05.244  1017  1030 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-26 15:00:05.244  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:00:05.244  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:00:05.244  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-26 15:00:05.254  6969  6969 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,08-26 15:00:05.254  1017  4339 I ActivityManager: Killing 6654:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 15:00:05.384  1017  1536 I art     : Explicit concurrent mark sweep GC freed 33769(1979KB) AllocSpace objects, 20(1479KB) LOS objects, 33% free, 24MB/36MB, paused 2.394ms total 153.714ms
,08-26 15:00:05.404  6982  7037 D ContactProvider: getAllContactInfoList End
,08-26 15:00:05.404  6982  7037 I syncContacts: thread: 1263, sync time = 204
,08-26 15:00:07.254  1017  3332 D SSRM:n  : SIOP:: AP = 370
,08-26 15:00:08.094   291   291 E SMD     : DCD OFF
,08-26 15:00:10.404  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:10.404  1017  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:00:10.404  1017  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:00:10.414  1017  1484 D BatteryService: stay LED for fully charged
08-26 15:00:10.414  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:00:10.414  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:00:10.414  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:00:10.414  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:00:10.414  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:10.424  1017  1017 I MotionRecognitionService: Plugged
08-26 15:00:10.424  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:00:10.434  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:00:10.434  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:10.444  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:10.444  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:10.444  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:11.094   291   291 E SMD     : DCD OFF
,08-26 15:00:12.084  1017  1050 I PowerManagerService: [PWL] Off : 75s ago,
,08-26 15:00:12.384  1017  1320 E Watchdog: !@Sync 4
,08-26 15:00:13.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:14.094   291   291 E SMD     : DCD OFF,
,08-26 15:00:14.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:15.704   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:00:16.154  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:00:16.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:16.814  1017  2068 V SAMP_SPCM_test: CSC File load.. ,
,08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi,
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control,
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings,
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 15:00:16.824  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control,
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:00:16.874  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts,
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption,
,08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 15:00:16.884  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 15:00:16.894  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 15:00:16.894  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminRe,ceiver}: mdm-phone-restriction
08-26 15:00:16.894  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 15:00:16.894  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:00:16.894  1017  2068 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-26 15:00:16.924  1017  2068 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 15:00:17.094   291   291 E SMD     : DCD OFF
,08-26 15:00:17.284  1017  3332 D SSRM:n  : SIOP:: AP = 330
,08-26 15:00:17.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:18.704   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:00:20.094   291   291 E SMD     : DCD OFF,
,08-26 15:00:20.464  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:20.474  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 15:00:20.474  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:00:20.474  1017  1512 D BatteryService: stay LED for fully charged
08-26 15:00:20.474  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:00:20.474  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-26 15:00:20.474  1017  1017 I MotionRecognitionService: Plugged
08-26 15:00:20.474  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:00:20.474  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:00:20.474  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:00:20.474  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:00:20.494  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:00:20.494  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:00:20.504  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:20.504  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:00:20.504  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:00:23.094   291   291 E SMD     : DCD OFF,
,08-26 15:00:26.094   291   291 E SMD     : DCD OFF
,08-26 15:00:27.324  1017  3332 D SSRM:n  : SIOP:: AP = 320,
,08-26 15:00:29.104   291   291 E SMD     : DCD OFF,
,08-26 15:00:30.534  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:32.094   291   291 E SMD     : DCD OFF,
,08-26 15:00:33.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:34.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:35.104   291   291 E SMD     : DCD OFF,
,08-26 15:00:35.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:36.154  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:00:36.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:37.354  1017  3332 D SSRM:n  : SIOP:: AP = 310,
,08-26 15:00:37.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:38.104   291   291 E SMD     : DCD OFF,
,08-26 15:00:38.714   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:00:40.594  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:41.104   291   291 E SMD     : DCD OFF
,08-26 15:00:42.084  1017  1050 I PowerManagerService: [PWL] Off : 105s ago,
,08-26 15:00:42.384  1017  1320 E Watchdog: !@Sync 5,
,08-26 15:00:42.694  4748  5082 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,08-26 15:00:44.104   291   291 E SMD     : DCD OFF,
,08-26 15:00:47.114   291   291 E SMD     : DCD OFF,
,08-26 15:00:47.394  1017  3332 D SSRM:n  : SIOP:: AP = 300,
,08-26 15:00:50.114   291   291 E SMD     : DCD OFF,
,08-26 15:00:50.654  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:00:53.114   291   291 E SMD     : DCD OFF,
,08-26 15:00:56.114   291   291 E SMD     : DCD OFF,
,08-26 15:00:56.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:00:57.424  1017  3332 D SSRM:n  : SIOP:: AP = 300,
,08-26 15:00:58.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:00:59.114   291   291 E SMD     : DCD OFF
,08-26 15:00:59.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:00.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:01:00.714  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:01.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:02.124   291   291 E SMD     : DCD OFF,
,08-26 15:01:02.714   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:03.714   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 15:01:05.124   291   291 E SMD     : DCD OFF
,08-26 15:01:07.454  1017  3332 D SSRM:n  : SIOP:: AP = 300,
,08-26 15:01:08.124   291   291 E SMD     : DCD OFF,
,08-26 15:01:10.774  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:11.124   291   291 E SMD     : DCD OFF
,08-26 15:01:12.384  1017  1320 E Watchdog: !@Sync 6,
,08-26 15:01:14.124   291   291 E SMD     : DCD OFF,
,08-26 15:01:15.024  1017  1096 V AlarmManager: waitForAlarm result :4
,08-26 15:01:15.034  1017  1017 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 15:01:15.034  1017  1017 V AlarmManagerEXT: <AppSync3 Whitelist>,
08-26 15:01:15.034  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-26 15:01:15.034  1017  1017 V AlarmManagerEXT: (AppSync) ### 0 added ###
08-26 15:01:15.034  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:01:15.044  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-26 15:01:15.044  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:01:15.054  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:15.054  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-26 15:01:15.054  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 15:01:15.084  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:15.094  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:15.094  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:15.114  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:01:16.154  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:01:17.084  1017  1050 I PowerManagerService: [PWL] Off : 140s ago
,08-26 15:01:17.124   291   291 E SMD     : DCD OFF
,08-26 15:01:17.494  1017  3332 D SSRM:n  : SIOP:: AP = 300
,08-26 15:01:18.584  1999  3082 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 15:01:20.124   291   291 E SMD     : DCD OFF,
,08-26 15:01:20.834  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:23.134   291   291 E SMD     : DCD OFF,
,08-26 15:01:26.134   291   291 E SMD     : DCD OFF,
,08-26 15:01:27.524  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:01:28.724   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-26 15:01:28.724   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:01:29.134   291   291 E SMD     : DCD OFF,
,08-26 15:01:30.894  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:32.134   291   291 E SMD     : DCD OFF,
,08-26 15:01:35.134   291   291 E SMD     : DCD OFF,
,08-26 15:01:36.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:01:37.564  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:01:38.134   291   291 E SMD     : DCD OFF,
,08-26 15:01:38.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:39.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:40.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:40.954  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:41.144   291   291 E SMD     : DCD OFF
,08-26 15:01:41.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:42.384  1017  1320 E Watchdog: !@Sync 7
,08-26 15:01:42.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:43.724   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:01:44.144   291   291 E SMD     : DCD OFF
,08-26 15:01:47.144   291   291 E SMD     : DCD OFF,
,08-26 15:01:47.604  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:01:48.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:49.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:50.144   291   291 E SMD     : DCD OFF,
,08-26 15:01:50.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:51.014  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:01:51.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:52.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:01:53.144   291   291 E SMD     : DCD OFF,
,08-26 15:01:53.724   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:01:56.144   291   291 E SMD     : DCD OFF,
,08-26 15:01:56.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:01:57.114  1017  1050 I PowerManagerService: [PWL] Off : 180s ago,
,08-26 15:01:57.634  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:01:59.154   291   291 E SMD     : DCD OFF,
,08-26 15:01:59.994  1017  1096 V AlarmManager: waitForAlarm result :8,
,08-26 15:02:01.074  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:02.144   291   291 E SMD     : DCD OFF,
,08-26 15:02:03.724   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:04.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:05.154   291   291 E SMD     : DCD OFF,
,08-26 15:02:05.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:06.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:07.674  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:07.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:08.154   291   291 E SMD     : DCD OFF,
,08-26 15:02:08.734   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:02:11.134  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:11.154   291   291 E SMD     : DCD OFF
,08-26 15:02:12.384  1017  1320 E Watchdog: !@Sync 8
,08-26 15:02:14.154   291   291 E SMD     : DCD OFF,
,08-26 15:02:16.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:02:17.154   291   291 E SMD     : DCD OFF,
,08-26 15:02:17.704  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:20.164   291   291 E SMD     : DCD OFF,
,08-26 15:02:21.194  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:21.194  1017  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:02:21.194  1017  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:02:21.194  1017  1322 D BatteryService: stay LED for fully charged
08-26 15:02:21.194  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:21.194  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:02:21.194  1017  1017 I MotionRecognitionService: Plugged
08-26 15:02:21.194  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:02:21.194  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:02:21.194  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:02:21.194  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:02:21.214  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:02:21.214  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:02:21.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:02:21.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:02:21.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:23.164   291   291 E SMD     : DCD OFF
,08-26 15:02:23.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:24.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:25.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:26.164   291   291 E SMD     : DCD OFF,
,08-26 15:02:26.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:27.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:02:27.744  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:02:28.734   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:02:29.164   291   291 E SMD     : DCD OFF,
,08-26 15:02:31.254  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:31.254  1017  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:02:31.254  1017  4339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:02:31.254  1017  4339 D BatteryService: stay LED for fully charged
08-26 15:02:31.254  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:02:31.254  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:02:31.254  1017  1017 I MotionRecognitionService: Plugged
08-26 15:02:31.254  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:02:31.254  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:02:31.254  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:02:31.254  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:02:31.264  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:02:31.274  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:02:31.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:31.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:02:31.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:02:32.164   291   291 E SMD     : DCD OFF,
,08-26 15:02:35.164   291   291 E SMD     : DCD OFF,
,08-26 15:02:36.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:02:37.774  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:38.164   291   291 E SMD     : DCD OFF,
,08-26 15:02:41.174   291   291 E SMD     : DCD OFF,
,08-26 15:02:41.304  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:42.124  1017  1050 I PowerManagerService: [PWL] Off : 225s ago,
,08-26 15:02:42.384  1017  1320 E Watchdog: !@Sync 9
,08-26 15:02:44.174   291   291 E SMD     : DCD OFF,
,08-26 15:02:47.174   291   291 E SMD     : DCD OFF,
,08-26 15:02:47.814  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:48.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:49.734   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:50.174   291   291 E SMD     : DCD OFF,
,08-26 15:02:50.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:51.374  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:02:51.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:52.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:02:53.174   291   291 E SMD     : DCD OFF,
,08-26 15:02:53.744   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:02:56.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:02:56.174   291   291 E SMD     : DCD OFF,
,08-26 15:02:57.854  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:02:59.184   291   291 E SMD     : DCD OFF,
,08-26 15:03:01.434  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:03:02.184   291   291 E SMD     : DCD OFF,
,08-26 15:03:05.184   291   291 E SMD     : DCD OFF,
,08-26 15:03:07.884  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:08.184   291   291 E SMD     : DCD OFF,
,08-26 15:03:09.384  1017  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:03:09.394  1017  1086 D TimaService: TimaServiceHandler.handleMessage what =1,
,08-26 15:03:09.394  1017  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:03:09.394  1017  1087 I TLC_TIMA_PKM_initialize: initializing...,
08-26 15:03:09.394  1017  1087 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
08-26 15:03:09.394  1017  1087 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
08-26 15:03:09.394  1017  1087 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
08-26 15:03:09.394  1017  1087 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
08-26 15:03:09.394  1017  1087 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
08-26 15:03:09.394  1017  1087 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040,
08-26 15:03:09.394  1017  1087 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
08-26 15:03:09.394  1017  1087 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
08-26 15:03:09.394  1017  1087 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:03:09.424  1017  1087 D QSEECOMAPI: : Loaded image: APP id = 11
,08-26 15:03:09.434  1017  1087 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,08-26 15:03:09.444  1017  1087 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,08-26 15:03:11.184   291   291 E SMD     : DCD OFF
,08-26 15:03:11.394  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:03:11.394  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:03:11.404  1017  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:03:11.404  1017  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:03:11.484  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:11.484  1017  4338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:03:11.484  1017  4338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:03:11.494  1017  4338 D BatteryService: stay LED for fully charged
08-26 15:03:11.494  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:03:11.494  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:03:11.494  1017  1017 I MotionRecognitionService: Plugged
08-26 15:03:11.494  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:03:11.494  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:03:11.494  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:03:11.494  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:03:11.504  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:03:11.504  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:03:11.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:11.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:11.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:03:12.384  1017  1320 E Watchdog: !@Sync 10
,08-26 15:03:14.184   291   291 E SMD     : DCD OFF,
,08-26 15:03:16.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:03:17.194   291   291 E SMD     : DCD OFF,
,08-26 15:03:17.924  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:18.744   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-26 15:03:18.744   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:03:20.194   291   291 E SMD     : DCD OFF,
,08-26 15:03:21.544  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:23.194   291   291 E SMD     : DCD OFF,
,08-26 15:03:26.194   291   291 E SMD     : DCD OFF,
,08-26 15:03:27.964  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:29.194   291   291 E SMD     : DCD OFF,
,08-26 15:03:31.604  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:32.144  1017  1050 I PowerManagerService: [PWL] Off : 275s ago,
,08-26 15:03:32.194   291   291 E SMD     : DCD OFF,
,08-26 15:03:33.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:34.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:35.204   291   291 E SMD     : DCD OFF,
,08-26 15:03:35.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:36.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:03:36.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:37.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:37.994  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:38.204   291   291 E SMD     : DCD OFF,
,08-26 15:03:38.744   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:03:41.204   291   291 E SMD     : DCD OFF,
,08-26 15:03:41.664  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:42.394  1017  1320 E Watchdog: !@Sync 11
,08-26 15:03:43.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:44.204   291   291 E SMD     : DCD OFF,
,08-26 15:03:44.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:45.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:46.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:47.214   291   291 E SMD     : DCD OFF,
,08-26 15:03:47.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:48.034  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:48.754   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:03:50.214   291   291 E SMD     : DCD OFF,
,08-26 15:03:51.724  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:03:53.214   291   291 E SMD     : DCD OFF,
,08-26 15:03:54.204  5900  6017 I PlayCommon: [1047] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:03:54.204  5900  6017 I PlayCommon: [1047] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:03:56.164  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:03:56.214   291   291 E SMD     : DCD OFF,
,08-26 15:03:58.064  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:03:58.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:03:59.214   291   291 E SMD     : DCD OFF,
,08-26 15:03:59.744   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:00.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:01.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:01.784  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:01.784  1017  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-26 15:04:01.784  1017  1221 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:01.784  1017  1221 D BatteryService: stay LED for fully charged
08-26 15:04:01.784  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:04:01.784  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:04:01.784  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:04:01.794  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:04:01.794  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:04:01.794  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:01.794  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:04:01.794  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:01.794  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:01.814  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:01.814  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:04:01.814  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:02.214   291   291 E SMD     : DCD OFF,
,08-26 15:04:02.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:03.754   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:04:05.214   291   291 E SMD     : DCD OFF,
,08-26 15:04:08.104  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:04:08.224   291   291 E SMD     : DCD OFF,
,08-26 15:04:11.224   291   291 E SMD     : DCD OFF,
,08-26 15:04:11.844  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:11.844  1017  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:04:11.844  1017  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:11.844  1017  1495 D BatteryService: stay LED for fully charged
08-26 15:04:11.844  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:11.844  1017  1017 I MotionRecognitionService: Plugged
08-26 15:04:11.844  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:04:11.854  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:04:11.854  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:11.854  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:04:11.854  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:04:11.864  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:11.864  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:11.864  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:11.874  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:11.874  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:12.384  1017  1320 E Watchdog: !@Sync 12
,08-26 15:04:14.224   291   291 E SMD     : DCD OFF,
,08-26 15:04:16.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:04:17.224   291   291 E SMD     : DCD OFF,
,08-26 15:04:18.144  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:04:18.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:19.354  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:04:19.354  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:04:19.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:20.224   291   291 E SMD     : DCD OFF,
,08-26 15:04:20.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:21.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:21.904  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:22.754   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:23.224   291   291 E SMD     : DCD OFF
,08-26 15:04:23.764   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-26 15:04:26.224   291   291 E SMD     : DCD OFF
,08-26 15:04:27.164  1017  1050 I PowerManagerService: [PWL] Off : 330s ago
,08-26 15:04:28.174  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:04:29.234   291   291 E SMD     : DCD OFF
,08-26 15:04:31.954  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:31.964  1017  3262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:04:31.964  1017  3262 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:31.964  1017  3262 D BatteryService: stay LED for fully charged
08-26 15:04:31.964  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:04:31.964  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:04:31.964  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:31.964  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:04:31.964  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:04:31.964  1017  1017 I MotionRecognitionService: Plugged
08-26 15:04:31.964  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:04:31.974  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:31.974  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:31.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:31.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:04:31.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:32.234   291   291 E SMD     : DCD OFF
,08-26 15:04:35.234   291   291 E SMD     : DCD OFF
,08-26 15:04:36.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:04:38.214  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:04:38.234   291   291 E SMD     : DCD OFF,
,08-26 15:04:41.244   291   291 E SMD     : DCD OFF,
,08-26 15:04:42.024  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:42.024  1017  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:04:42.024  1017  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:04:42.024  1017  1484 D BatteryService: stay LED for fully charged
08-26 15:04:42.024  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:04:42.024  1017  1017 I MotionRecognitionService: Plugged,
,08-26 15:04:42.024  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:04:42.024  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:04:42.024  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:04:42.034  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:04:42.034  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:04:42.044  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:04:42.044  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:04:42.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:42.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:04:42.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:04:42.384  1017  1320 E Watchdog: !@Sync 13
,08-26 15:04:43.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:44.244   291   291 E SMD     : DCD OFF,
,08-26 15:04:44.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:45.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:46.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:04:47.244   291   291 E SMD     : DCD OFF,
,08-26 15:04:47.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:04:48.254  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:04:48.764   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 15:04:50.244   291   291 E SMD     : DCD OFF
,08-26 15:04:52.084  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:04:53.244   291   291 E SMD     : DCD OFF,
,08-26 15:04:56.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:04:56.254   291   291 E SMD     : DCD OFF,
,08-26 15:04:58.284  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:04:59.254   291   291 E SMD     : DCD OFF,
,08-26 15:04:59.994  1017  1096 V AlarmManager: waitForAlarm result :8,
08-26 15:04:59.994  1017  1096 V AlarmManager: No more alarm at this time.nowELAPSED=425922 batch.start=802004
,08-26 15:04:59.994  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
08-26 15:04:59.994  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 15:05:00.014  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,08-26 15:05:00.014  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 15:05:00.014  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 15:05:00.014  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-26 15:05:00.014  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 15:05:00.054  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:05:00.054  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:05:00.054  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:05:00.074  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 15:05:02.144  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:02.254   291   291 E SMD     : DCD OFF,
,08-26 15:05:05.254   291   291 E SMD     : DCD OFF
,08-26 15:05:08.254   291   291 E SMD     : DCD OFF,
,08-26 15:05:08.324  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:11.254   291   291 E SMD     : DCD OFF,
,08-26 15:05:12.194  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:12.194  1017  4338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:05:12.194  1017  4338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:05:12.194  1017  4338 D BatteryService: stay LED for fully charged
08-26 15:05:12.194  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:05:12.204  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:05:12.204  1017  1017 I MotionRecognitionService: Plugged
08-26 15:05:12.204  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:05:12.204  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:05:12.204  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:05:12.204  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:05:12.214  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:12.214  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:05:12.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:12.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:12.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:12.394  1017  1320 E Watchdog: !@Sync 14,
,08-26 15:05:13.764   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-26 15:05:13.764   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:05:14.264   291   291 E SMD     : DCD OFF,
,08-26 15:05:16.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:05:17.264   291   291 E SMD     : DCD OFF,
,08-26 15:05:18.354  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:20.264   291   291 E SMD     : DCD OFF,
,08-26 15:05:22.254  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:22.254  1017  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-26 15:05:22.254  1017  4339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:05:22.254  1017  4339 D BatteryService: stay LED for fully charged,
08-26 15:05:22.254  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:05:22.264  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-26 15:05:22.264  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:05:22.264  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:05:22.264  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:05:22.264  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:05:22.264  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 15:05:22.274  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:22.274  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:05:22.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:22.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:22.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:23.264   291   291 E SMD     : DCD OFF,
,08-26 15:05:26.264   291   291 E SMD     : DCD OFF,
,08-26 15:05:27.164  1017  1050 I PowerManagerService: [PWL] Off : 390s ago,
,08-26 15:05:28.394  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:29.264   291   291 E SMD     : DCD OFF,
,08-26 15:05:32.264   291   291 E SMD     : DCD OFF
,08-26 15:05:32.324  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:33.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:05:34.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:35.274   291   291 E SMD     : DCD OFF,
,08-26 15:05:35.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:36.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:05:36.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:37.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:38.274   291   291 E SMD     : DCD OFF,
,08-26 15:05:38.434  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:38.764   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:05:41.274   291   291 E SMD     : DCD OFF,
,08-26 15:05:42.384  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:42.394  1017  1320 E Watchdog: !@Sync 15,
,08-26 15:05:43.764   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:44.274   291   291 E SMD     : DCD OFF,
,08-26 15:05:44.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:45.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:46.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:47.274   291   291 E SMD     : DCD OFF,
,08-26 15:05:47.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:48.474  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:48.774   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:05:50.284   291   291 E SMD     : DCD OFF,
,08-26 15:05:52.444  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:05:52.444  1017  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:05:52.444  1017  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:05:52.444  1017  1496 D BatteryService: stay LED for fully charged
08-26 15:05:52.444  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:05:52.444  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:05:52.444  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:05:52.444  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:05:52.444  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:05:52.454  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:05:52.454  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:05:52.454  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:05:52.454  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:05:52.474  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:52.474  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:05:52.474  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:05:53.284   291   291 E SMD     : DCD OFF,
,08-26 15:05:56.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:05:56.284   291   291 E SMD     : DCD OFF,
,08-26 15:05:58.504  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:05:58.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:59.284   291   291 E SMD     : DCD OFF,
,08-26 15:05:59.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:05:59.994  1017  1096 V AlarmManager: waitForAlarm result :8,
,08-26 15:06:00.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:01.244   332   332 I bootchecker: bootchecker wake up!!,
,08-26 15:06:01.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:02.284   291   291 E SMD     : DCD OFF,
,08-26 15:06:02.494  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:06:02.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:03.774   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:06:05.284   291   291 E SMD     : DCD OFF,
,08-26 15:06:08.294   291   291 E SMD     : DCD OFF,
,08-26 15:06:08.544  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:06:11.294   291   291 E SMD     : DCD OFF,
,08-26 15:06:12.394  1017  1320 E Watchdog: !@Sync 16,
,08-26 15:06:12.564  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:06:14.294   291   291 E SMD     : DCD OFF,
,08-26 15:06:16.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:06:17.294   291   291 E SMD     : DCD OFF,
,08-26 15:06:18.584  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:06:18.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:19.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:20.294   291   291 E SMD     : DCD OFF,
,08-26 15:06:20.774   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:21.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:22.634  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:22.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:06:23.294   291   291 E SMD     : DCD OFF,
,08-26 15:06:23.784   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:06:26.304   291   291 E SMD     : DCD OFF,
,08-26 15:06:28.614  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:06:29.304   291   291 E SMD     : DCD OFF,
,08-26 15:06:32.204  1017  1050 I PowerManagerService: [PWL] Off : 455s ago
,08-26 15:06:32.304   291   291 E SMD     : DCD OFF,
,08-26 15:06:32.694  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:35.304   291   291 E SMD     : DCD OFF
,08-26 15:06:36.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:06:38.304   291   291 E SMD     : DCD OFF
,08-26 15:06:38.644  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:06:41.314   291   291 E SMD     : DCD OFF
,08-26 15:06:42.394  1017  1320 E Watchdog: !@Sync 17
,08-26 15:06:42.754  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:43.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:06:44.314   291   291 E SMD     : DCD OFF,
,08-26 15:06:44.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:45.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:46.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:47.314   291   291 E SMD     : DCD OFF,
,08-26 15:06:47.784   335   335 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:06:48.674  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:06:48.784   335   335 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:06:50.314   291   291 E SMD     : DCD OFF,
,08-26 15:06:52.814  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:06:53.324   291   291 E SMD     : DCD OFF
,08-26 15:06:56.174  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:06:56.324   291   291 E SMD     : DCD OFF,
,08-26 15:06:58.714  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:06:59.324   291   291 E SMD     : DCD OFF,
,08-26 15:07:02.324   291   291 E SMD     : DCD OFF,
,08-26 15:07:02.884  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:05.324   291   291 E SMD     : DCD OFF
,08-26 15:07:08.324   291   291 E SMD     : DCD OFF,
,08-26 15:07:08.754  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:11.334   291   291 E SMD     : DCD OFF,
,08-26 15:07:12.394  1017  1320 E Watchdog: !@Sync 18,
,08-26 15:07:12.944  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:12.944  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:12.944  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:12.944  1017  1512 D BatteryService: stay LED for fully charged
,08-26 15:07:12.944  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:12.944  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:07:12.944  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:07:12.954  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:07:12.954  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:07:12.954  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:07:12.954  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:07:12.964  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:12.964  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:12.974  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:12.974  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:07:12.974  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:13.784   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
08-26 15:07:13.784   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:07:14.334   291   291 E SMD     : DCD OFF,
,08-26 15:07:16.184  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:07:17.334   291   291 E SMD     : DCD OFF,
,08-26 15:07:18.794  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:07:20.334   291   291 E SMD     : DCD OFF,
,08-26 15:07:23.004  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:23.004  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:23.004  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:23.004  1017  1135 D BatteryService: stay LED for fully charged
,08-26 15:07:23.004  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:23.004  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:07:23.004  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:07:23.014  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:07:23.014  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:07:23.014  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:07:23.014  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:07:23.024  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:23.024  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:23.044  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:23.044  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:07:23.044  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:23.334   291   291 E SMD     : DCD OFF
,08-26 15:07:26.334   291   291 E SMD     : DCD OFF,
,08-26 15:07:28.834  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:29.334   291   291 E SMD     : DCD OFF
,08-26 15:07:32.344   291   291 E SMD     : DCD OFF,
,08-26 15:07:33.064  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:33.064  1017  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:07:33.064  1017  4339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:07:33.064  1017  4339 D BatteryService: stay LED for fully charged
,08-26 15:07:33.064  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:07:33.074  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:07:33.074  1017  1017 I MotionRecognitionService: Plugged
08-26 15:07:33.074  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:07:33.074  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:07:33.074  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:07:33.074  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:07:33.084  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:07:33.084  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:07:33.094  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:33.094  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:33.094  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:07:35.344   291   291 E SMD     : DCD OFF
,08-26 15:07:36.184  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:07:38.344   291   291 E SMD     : DCD OFF,
,08-26 15:07:38.784   335   335 I Atfwd_Daemon: Stop the daemon....,
,08-26 15:07:38.864  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:41.344   291   291 E SMD     : DCD OFF,
,08-26 15:07:42.214  1017  1050 I PowerManagerService: [PWL] Off : 525s ago
,08-26 15:07:42.394  1017  1320 E Watchdog: !@Sync 19,
,08-26 15:07:43.124  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:44.344   291   291 E SMD     : DCD OFF
,08-26 15:07:47.344   291   291 E SMD     : DCD OFF
,08-26 15:07:48.904  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:50.344   291   291 E SMD     : DCD OFF,
,08-26 15:07:53.184  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:07:53.354   291   291 E SMD     : DCD OFF
,08-26 15:07:56.184  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:07:56.354   291   291 E SMD     : DCD OFF,
,08-26 15:07:58.944  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:07:59.354   291   291 E SMD     : DCD OFF,
,08-26 15:08:02.354   291   291 E SMD     : DCD OFF,
,08-26 15:08:03.244  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:05.354   291   291 E SMD     : DCD OFF,
,08-26 15:08:08.364   291   291 E SMD     : DCD OFF,
,08-26 15:08:08.984  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:08:09.384  1017  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
08-26 15:08:09.384  1017  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-26 15:08:09.384  1017  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:08:10.224  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:08:10.224  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:08:10.234  1017  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:08:10.234  1017  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:08:11.364   291   291 E SMD     : DCD OFF,
,08-26 15:08:12.394  1017  1320 E Watchdog: !@Sync 20,
,08-26 15:08:13.304  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:13.304  1017  4338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:08:13.304  1017  4338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:08:13.304  1017  4338 D BatteryService: stay LED for fully charged
,08-26 15:08:13.304  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:08:13.314  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:08:13.314  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:08:13.314  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:08:13.314  1017  1017 I MotionRecognitionService: Plugged
08-26 15:08:13.314  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:08:13.314  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 15:08:13.324  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:08:13.324  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:08:13.334  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:13.334  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:08:13.334  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:14.364   291   291 E SMD     : DCD OFF,
,08-26 15:08:16.184  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:08:17.364   291   291 E SMD     : DCD OFF
,08-26 15:08:19.014  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:08:20.364   291   291 E SMD     : DCD OFF,
,08-26 15:08:23.364   291   291 E SMD     : DCD OFF
,08-26 15:08:23.364  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:26.374   291   291 E SMD     : DCD OFF,
,08-26 15:08:29.054  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:08:29.374   291   291 E SMD     : DCD OFF,
,08-26 15:08:32.374   291   291 E SMD     : DCD OFF,
,08-26 15:08:33.424  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:35.374   291   291 E SMD     : DCD OFF,
,08-26 15:08:36.184  1017  3361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:08:38.374   291   291 E SMD     : DCD OFF,
,08-26 15:08:39.094  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:08:41.374   291   291 E SMD     : DCD OFF,
,08-26 15:08:42.394  1017  1320 E Watchdog: !@Sync 21,
,08-26 15:08:43.484  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:08:44.384   291   291 E SMD     : DCD OFF
,08-26 15:08:47.384   291   291 E SMD     : DCD OFF,
,08-26 15:08:49.144  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:08:50.384   291   291 E SMD     : DCD OFF,
,08-26 15:08:53.384   291   291 E SMD     : DCD OFF,
,08-26 15:08:53.544  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:08:53.544  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:08:53.544  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:08:53.544  1017  1135 D BatteryService: stay LED for fully charged
,08-26 15:08:53.544  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:08:53.554  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:08:53.554  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:08:53.554  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:08:53.554  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:08:53.554  1017  1017 I MotionRecognitionService: Plugged
08-26 15:08:53.554  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:08:53.564  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:08:53.564  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:08:53.574  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:53.574  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:08:53.574  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:08:56.384   291   291 E SMD     : DCD OFF
,08-26 15:08:57.224  1017  1050 I PowerManagerService: [PWL] Off : 600s ago,
,08-26 15:08:59.184  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:08:59.384   291   291 E SMD     : DCD OFF
,08-26 15:09:02.384   291   291 E SMD     : DCD OFF,
,08-26 15:09:03.604  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:05.394   291   291 E SMD     : DCD OFF,
,08-26 15:09:08.394   291   291 E SMD     : DCD OFF,
,08-26 15:09:09.224  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:09:11.394   291   291 E SMD     : DCD OFF
,08-26 15:09:12.394  1017  1320 E Watchdog: !@Sync 22,
,08-26 15:09:13.664  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:14.394   291   291 E SMD     : DCD OFF
,08-26 15:09:17.394   291   291 E SMD     : DCD OFF,
,08-26 15:09:19.264  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:09:19.454  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:09:19.454  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:09:20.404   291   291 E SMD     : DCD OFF,
,08-26 15:09:23.404   291   291 E SMD     : DCD OFF,
,08-26 15:09:23.724  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:26.404   291   291 E SMD     : DCD OFF
,08-26 15:09:29.304  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:09:29.404   291   291 E SMD     : DCD OFF,
,08-26 15:09:32.404   291   291 E SMD     : DCD OFF,
,08-26 15:09:33.784  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:35.404   291   291 E SMD     : DCD OFF
,08-26 15:09:38.414   291   291 E SMD     : DCD OFF,
,08-26 15:09:39.344  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:09:41.414   291   291 E SMD     : DCD OFF,
,08-26 15:09:42.394  1017  1320 E Watchdog: !@Sync 23,
,08-26 15:09:43.844  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:09:44.414   291   291 E SMD     : DCD OFF
,08-26 15:09:47.414   291   291 E SMD     : DCD OFF,
,08-26 15:09:49.384  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:09:50.414   291   291 E SMD     : DCD OFF,
,08-26 15:09:53.414   291   291 E SMD     : DCD OFF
,08-26 15:09:53.904  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:09:53.904  1017  4338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:09:53.904  1017  4338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:09:53.904  1017  4338 D BatteryService: stay LED for fully charged
08-26 15:09:53.904  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:09:53.904  1017  1017 I MotionRecognitionService: Plugged
08-26 15:09:53.904  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:09:53.904  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:09:53.904  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:09:53.904  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:09:53.904  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:09:53.914  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:09:53.914  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:09:53.934  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:09:53.934  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:09:53.934  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:09:56.424   291   291 E SMD     : DCD OFF,
,08-26 15:09:59.414   291   291 E SMD     : DCD OFF,
,08-26 15:09:59.424  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:10:02.424   291   291 E SMD     : DCD OFF,
,08-26 15:10:03.964  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:10:03.964  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:10:03.964  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:03.964  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:03.964  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:03.964  1017  1029 D BatteryService: stay LED for fully charged
08-26 15:10:03.964  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:10:03.964  1017  1017 I MotionRecognitionService: Plugged
08-26 15:10:03.964  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:10:03.964  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:10:03.964  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:03.974  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:10:03.974  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:03.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:03.994  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:10:03.994  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:05.424   291   291 E SMD     : DCD OFF
,08-26 15:10:08.424   291   291 E SMD     : DCD OFF,
,08-26 15:10:09.464  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:10:11.424   291   291 E SMD     : DCD OFF
,08-26 15:10:12.404  1017  1320 E Watchdog: !@Sync 24,
,08-26 15:10:14.024  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:14.024  1017  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:14.024  1017  1536 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:14.024  1017  1536 D BatteryService: stay LED for fully charged
,08-26 15:10:14.024  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:14.024  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:10:14.024  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:14.034  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:14.034  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:14.034  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:14.034  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:14.044  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:14.044  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:14.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:14.064  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:10:14.064  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:14.434   291   291 E SMD     : DCD OFF
,08-26 15:10:17.224  1017  1050 I PowerManagerService: [PWL] Off : 680s ago
,08-26 15:10:17.434   291   291 E SMD     : DCD OFF
,08-26 15:10:19.514  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:10:20.434   291   291 E SMD     : DCD OFF
,08-26 15:10:23.434   291   291 E SMD     : DCD OFF,
,08-26 15:10:24.084  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:24.084  1017  4337 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:24.084  1017  4337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:10:24.084  1017  4337 D BatteryService: stay LED for fully charged
08-26 15:10:24.084  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:24.084  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:10:24.094  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:24.094  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:24.094  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:24.094  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:24.094  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:24.104  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:24.104  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:24.124  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:24.124  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:10:24.124  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:26.434   291   291 E SMD     : DCD OFF
,08-26 15:10:29.434   291   291 E SMD     : DCD OFF
,08-26 15:10:29.554  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:10:32.444   291   291 E SMD     : DCD OFF
,08-26 15:10:34.144  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:34.144  1017  1322 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:34.144  1017  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:34.144  1017  1322 D BatteryService: stay LED for fully charged
,08-26 15:10:34.144  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:34.144  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:10:34.144  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:34.154  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:10:34.154  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:10:34.154  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:34.154  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:34.164  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:10:34.164  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:34.174  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:34.174  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:34.174  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:35.444   291   291 E SMD     : DCD OFF
,08-26 15:10:38.444   291   291 E SMD     : DCD OFF,
,08-26 15:10:39.594  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:10:41.444   291   291 E SMD     : DCD OFF
,08-26 15:10:42.404  1017  1320 E Watchdog: !@Sync 25,
,08-26 15:10:44.204  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:10:44.204  1017  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:44.204  1017  1221 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:44.204  1017  1221 D BatteryService: stay LED for fully charged
08-26 15:10:44.204  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:10:44.204  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:10:44.204  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:44.214  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:44.214  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:44.214  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:44.214  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:44.224  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:44.224  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:44.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:44.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:10:44.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:44.444   291   291 E SMD     : DCD OFF
,08-26 15:10:47.444   291   291 E SMD     : DCD OFF,
,08-26 15:10:49.634  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:10:50.444   291   291 E SMD     : DCD OFF,
,08-26 15:10:53.454   291   291 E SMD     : DCD OFF,
,08-26 15:10:54.264  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:10:54.264  1017  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:10:54.264  1017  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:10:54.264  1017  1484 D BatteryService: stay LED for fully charged
,08-26 15:10:54.264  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:10:54.274  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:10:54.274  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:10:54.274  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:10:54.274  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:10:54.274  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:10:54.274  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:10:54.284  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:10:54.294  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:10:54.304  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:54.304  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:10:54.304  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:10:56.454   291   291 E SMD     : DCD OFF
,08-26 15:10:59.454   291   291 E SMD     : DCD OFF
,08-26 15:10:59.684  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:11:02.454   291   291 E SMD     : DCD OFF
,08-26 15:11:04.324  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:05.454   291   291 E SMD     : DCD OFF,
,08-26 15:11:08.454   291   291 E SMD     : DCD OFF,
,08-26 15:11:09.724  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:11:11.464   291   291 E SMD     : DCD OFF,
,08-26 15:11:12.404  1017  1320 E Watchdog: !@Sync 26,
,08-26 15:11:14.384  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:14.464   291   291 E SMD     : DCD OFF
,08-26 15:11:16.074  1017  1096 V AlarmManager: waitForAlarm result :8
,08-26 15:11:17.464   291   291 E SMD     : DCD OFF
,08-26 15:11:19.764  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:11:20.464   291   291 E SMD     : DCD OFF,
,08-26 15:11:23.464   291   291 E SMD     : DCD OFF,
,08-26 15:11:24.454  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:11:26.464   291   291 E SMD     : DCD OFF,
,08-26 15:11:29.474   291   291 E SMD     : DCD OFF,
,08-26 15:11:29.804  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:11:32.474   291   291 E SMD     : DCD OFF,
,08-26 15:11:34.504  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:11:35.474   291   291 E SMD     : DCD OFF
,08-26 15:11:38.474   291   291 E SMD     : DCD OFF,
,08-26 15:11:39.854  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:11:41.474   291   291 E SMD     : DCD OFF,
,08-26 15:11:42.274  1017  1050 I PowerManagerService: [PWL] Off : 765s ago,
,08-26 15:11:42.394  1017  1320 E Watchdog: !@Sync 27,
,08-26 15:11:44.474   291   291 E SMD     : DCD OFF,
,08-26 15:11:44.564  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:47.484   291   291 E SMD     : DCD OFF
,08-26 15:11:49.894  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:11:50.484   291   291 E SMD     : DCD OFF
,08-26 15:11:53.484   291   291 E SMD     : DCD OFF,
,08-26 15:11:54.634  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:11:56.484   291   291 E SMD     : DCD OFF
,08-26 15:11:59.484   291   291 E SMD     : DCD OFF,
,08-26 15:11:59.934  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:12:02.484   291   291 E SMD     : DCD OFF,
,08-26 15:12:04.684  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:05.484   291   291 E SMD     : DCD OFF
,08-26 15:12:08.484   291   291 E SMD     : DCD OFF,
,08-26 15:12:09.974  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:12:11.494   291   291 E SMD     : DCD OFF,
,08-26 15:12:12.404  1017  1320 E Watchdog: !@Sync 28
,08-26 15:12:14.494   291   291 E SMD     : DCD OFF,
,08-26 15:12:14.744  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:14.744  1017  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:12:14.744  1017  1536 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:12:14.744  1017  1536 D BatteryService: stay LED for fully charged
,08-26 15:12:14.744  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:12:14.754  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:12:14.754  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:12:14.754  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:12:14.754  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:12:14.764  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:12:14.764  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:12:14.764  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:12:14.764  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:12:14.774  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:12:14.774  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:12:14.774  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:12:17.494   291   291 E SMD     : DCD OFF
,08-26 15:12:20.014  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:12:20.494   291   291 E SMD     : DCD OFF
,08-26 15:12:23.494   291   291 E SMD     : DCD OFF,
,08-26 15:12:24.804  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:26.494   291   291 E SMD     : DCD OFF
,08-26 15:12:29.504   291   291 E SMD     : DCD OFF,
,08-26 15:12:30.064  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:12:32.504   291   291 E SMD     : DCD OFF,
,08-26 15:12:34.864  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:35.504   291   291 E SMD     : DCD OFF
,08-26 15:12:38.504   291   291 E SMD     : DCD OFF,
,08-26 15:12:40.104  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:12:41.504   291   291 E SMD     : DCD OFF,
,08-26 15:12:42.404  1017  1320 E Watchdog: !@Sync 29,
,08-26 15:12:44.504   291   291 E SMD     : DCD OFF,
,08-26 15:12:44.924  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:44.924  1017  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:12:44.924  1017  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:12:44.934  1017  1495 D BatteryService: stay LED for fully charged
08-26 15:12:44.934  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:12:44.934  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:12:44.934  1017  1017 I MotionRecognitionService: Plugged
08-26 15:12:44.934  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:12:44.934  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:12:44.934  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:12:44.934  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:12:44.944  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:12:44.944  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:12:44.954  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:12:44.954  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:12:44.954  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:12:47.514   291   291 E SMD     : DCD OFF
,08-26 15:12:50.144  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:12:50.514   291   291 E SMD     : DCD OFF
,08-26 15:12:53.514   291   291 E SMD     : DCD OFF,
,08-26 15:12:54.984  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:12:56.514   291   291 E SMD     : DCD OFF
,08-26 15:12:59.514   291   291 E SMD     : DCD OFF,
,08-26 15:13:00.184  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:13:02.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:05.044  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:05.044  1017  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:13:05.044  1017  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:13:05.044  1017  1496 D BatteryService: stay LED for fully charged
,08-26 15:13:05.044  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:05.054  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:13:05.054  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:13:05.054  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:13:05.054  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:13:05.064  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:13:05.064  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:13:05.064  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:13:05.064  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:13:05.074  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:05.074  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:13:05.074  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:05.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:08.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:09.384  1017  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
08-26 15:13:09.384  1017  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-26 15:13:09.384  1017  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:13:10.214  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:13:11.334  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:13:11.334  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:13:11.344  1017  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:13:11.344  1017  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:13:11.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:12.274  1017  1050 I PowerManagerService: [PWL] Off : 855s ago,
,08-26 15:13:12.404  1017  1320 E Watchdog: !@Sync 30,
,08-26 15:13:14.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:15.104  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:15.104  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:13:15.104  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:13:15.104  1017  1512 D BatteryService: stay LED for fully charged
,08-26 15:13:15.104  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:13:15.104  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:13:15.104  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:13:15.114  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:13:15.114  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:13:15.114  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:13:15.114  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:13:15.124  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:13:15.124  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:13:15.134  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:15.134  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:15.134  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:13:17.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:20.254  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:13:20.524   291   291 E SMD     : DCD OFF,
,08-26 15:13:23.534   291   291 E SMD     : DCD OFF,
,08-26 15:13:25.164  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:26.534   291   291 E SMD     : DCD OFF,
,08-26 15:13:29.534   291   291 E SMD     : DCD OFF,
,08-26 15:13:30.294  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:13:32.534   291   291 E SMD     : DCD OFF,
,08-26 15:13:35.224  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:35.534   291   291 E SMD     : DCD OFF
,08-26 15:13:38.534   291   291 E SMD     : DCD OFF,
,08-26 15:13:40.344  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:13:41.544   291   291 E SMD     : DCD OFF,
,08-26 15:13:42.404  1017  1320 E Watchdog: !@Sync 31,
,08-26 15:13:44.544   291   291 E SMD     : DCD OFF,
,08-26 15:13:45.284  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:47.544   291   291 E SMD     : DCD OFF,
,08-26 15:13:50.384  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:13:50.544   291   291 E SMD     : DCD OFF,
,08-26 15:13:53.544   291   291 E SMD     : DCD OFF,
,08-26 15:13:55.344  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:13:56.544   291   291 E SMD     : DCD OFF
,08-26 15:13:59.554   291   291 E SMD     : DCD OFF,
,08-26 15:14:00.434  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:14:02.544   291   291 E SMD     : DCD OFF,
,08-26 15:14:05.404  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:05.554   291   291 E SMD     : DCD OFF
,08-26 15:14:08.554   291   291 E SMD     : DCD OFF,
,08-26 15:14:10.474  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:14:11.554   291   291 E SMD     : DCD OFF,
,08-26 15:14:12.404  1017  1320 E Watchdog: !@Sync 32,
,08-26 15:14:14.554   291   291 E SMD     : DCD OFF,
,08-26 15:14:15.464  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:17.554   291   291 E SMD     : DCD OFF,
,08-26 15:14:19.554  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:14:19.554  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:14:19.684  5900  6017 I PlayCommon: [1047] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:14:19.684  5900  6017 I PlayCommon: [1047] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:14:20.524  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:14:20.564   291   291 E SMD     : DCD OFF,
,08-26 15:14:23.564   291   291 E SMD     : DCD OFF,
,08-26 15:14:25.524  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:25.524  1017  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:25.524  1017  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:14:25.524  1017  1484 D BatteryService: stay LED for fully charged
08-26 15:14:25.524  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:14:25.534  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:14:25.534  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:14:25.534  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:14:25.534  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:14:25.534  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:14:25.534  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,08-26 15:14:25.544  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:14:25.544  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:25.554  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:25.554  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:25.554  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:26.564   291   291 E SMD     : DCD OFF,
,08-26 15:14:29.564   291   291 E SMD     : DCD OFF,
,08-26 15:14:30.564  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:14:32.564   291   291 E SMD     : DCD OFF,
,08-26 15:14:35.564   291   291 E SMD     : DCD OFF,
,08-26 15:14:35.584  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:38.574   291   291 E SMD     : DCD OFF,
,08-26 15:14:40.604  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:14:41.574   291   291 E SMD     : DCD OFF
,08-26 15:14:42.404  1017  1320 E Watchdog: !@Sync 33,
,08-26 15:14:44.574   291   291 E SMD     : DCD OFF,
,08-26 15:14:45.644  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:14:47.294  1017  1050 I PowerManagerService: [PWL] Off : 950s ago,
,08-26 15:14:47.574   291   291 E SMD     : DCD OFF,
,08-26 15:14:50.574   291   291 E SMD     : DCD OFF,
,08-26 15:14:50.644  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:14:53.574   291   291 E SMD     : DCD OFF,
,08-26 15:14:55.704  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:14:55.704  1017  3262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:14:55.704  1017  3262 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:14:55.704  1017  3262 D BatteryService: stay LED for fully charged
08-26 15:14:55.704  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:14:55.704  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:14:55.704  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:14:55.704  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:14:55.704  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:14:55.714  1017  1017 I MotionRecognitionService: Plugged
08-26 15:14:55.714  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:14:55.714  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:14:55.714  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:14:55.734  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:55.734  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:14:55.734  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:14:56.584   291   291 E SMD     : DCD OFF
,08-26 15:14:59.584   291   291 E SMD     : DCD OFF,
,08-26 15:15:00.684  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:15:02.584   291   291 E SMD     : DCD OFF
,08-26 15:15:05.584   291   291 E SMD     : DCD OFF
,08-26 15:15:05.754  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:05.764  1017  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:15:05.764  1017  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:15:05.764  1017  1495 D BatteryService: stay LED for fully charged
,08-26 15:15:05.764  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:15:05.764  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:15:05.764  1017  1017 I MotionRecognitionService: Plugged
08-26 15:15:05.764  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:15:05.764  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:15:05.764  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:15:05.764  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:15:05.774  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:15:05.774  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:15:05.794  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:05.794  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:15:05.794  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:08.584   291   291 E SMD     : DCD OFF,
,08-26 15:15:10.724  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:15:11.584   291   291 E SMD     : DCD OFF
,08-26 15:15:12.404  1017  1320 E Watchdog: !@Sync 34,
,08-26 15:15:14.594   291   291 E SMD     : DCD OFF,
,08-26 15:15:15.824  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:17.594   291   291 E SMD     : DCD OFF,
,08-26 15:15:20.594   291   291 E SMD     : DCD OFF,
,08-26 15:15:20.774  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:15:23.594   291   291 E SMD     : DCD OFF,
,08-26 15:15:25.884  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:26.594   291   291 E SMD     : DCD OFF,
,08-26 15:15:29.594   291   291 E SMD     : DCD OFF,
,08-26 15:15:30.814  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:15:32.604   291   291 E SMD     : DCD OFF,
,08-26 15:15:35.604   291   291 E SMD     : DCD OFF,
,08-26 15:15:35.944  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:38.604   291   291 E SMD     : DCD OFF,
,08-26 15:15:40.864  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:15:41.604   291   291 E SMD     : DCD OFF,
,08-26 15:15:42.404  1017  1320 E Watchdog: !@Sync 35,
,08-26 15:15:44.604   291   291 E SMD     : DCD OFF,
,08-26 15:15:46.004  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:46.004  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:15:46.004  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:15:46.004  1017  1512 D BatteryService: stay LED for fully charged
08-26 15:15:46.004  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:15:46.004  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:15:46.004  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:15:46.004  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:15:46.004  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:15:46.014  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:15:46.014  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:15:46.014  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:15:46.014  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:15:46.034  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:15:46.034  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:15:46.034  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:47.614   291   291 E SMD     : DCD OFF,
,08-26 15:15:50.604   291   291 E SMD     : DCD OFF,
,08-26 15:15:50.894  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:15:53.614   291   291 E SMD     : DCD OFF,
,08-26 15:15:56.054  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:15:56.064  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
08-26 15:15:56.064  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:15:56.064  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:15:56.064  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:15:56.064  1017  1135 D BatteryService: stay LED for fully charged
08-26 15:15:56.064  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-26 15:15:56.064  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:15:56.064  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:15:56.064  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:15:56.064  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:15:56.074  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:15:56.074  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:15:56.084  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:56.084  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:15:56.084  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:15:56.614   291   291 E SMD     : DCD OFF
,08-26 15:15:59.614   291   291 E SMD     : DCD OFF,
,08-26 15:16:00.934  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:16:02.614   291   291 E SMD     : DCD OFF
,08-26 15:16:05.624   291   291 E SMD     : DCD OFF,
,08-26 15:16:06.124  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:08.624   291   291 E SMD     : DCD OFF,
,08-26 15:16:10.984  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:16:11.624   291   291 E SMD     : DCD OFF,
,08-26 15:16:12.404  1017  1320 E Watchdog: !@Sync 36,
,08-26 15:16:14.624   291   291 E SMD     : DCD OFF,
,08-26 15:16:16.184  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:16.184  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:16.184  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:16.184  1017  1512 D BatteryService: stay LED for fully charged
08-26 15:16:16.184  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:16.184  1017  1017 I MotionRecognitionService: Plugged
08-26 15:16:16.184  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:16:16.194  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:16:16.194  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:16:16.194  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:16:16.194  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:16.204  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:16.204  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:16.214  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:16.214  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:16.214  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:17.624   291   291 E SMD     : DCD OFF
,08-26 15:16:20.624   291   291 E SMD     : DCD OFF,
,08-26 15:16:21.004  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:16:23.634   291   291 E SMD     : DCD OFF,
,08-26 15:16:26.244  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:26.244  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:26.244  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:26.244  1017  1135 D BatteryService: stay LED for fully charged
08-26 15:16:26.244  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:26.244  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:16:26.244  1017  1017 I MotionRecognitionService: Plugged
08-26 15:16:26.244  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:16:26.244  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:16:26.244  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:16:26.244  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:26.264  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:16:26.264  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:26.274  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:26.274  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:26.274  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:26.634   291   291 E SMD     : DCD OFF,
,08-26 15:16:27.294  1017  1050 I PowerManagerService: [PWL] Off : 1050s ago,
,08-26 15:16:29.634   291   291 E SMD     : DCD OFF,
,08-26 15:16:31.024  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:16:32.634   291   291 E SMD     : DCD OFF
,08-26 15:16:35.634   291   291 E SMD     : DCD OFF,
,08-26 15:16:36.294  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:36.304  1017  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:36.304  1017  4339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:36.304  1017  4339 D BatteryService: stay LED for fully charged
08-26 15:16:36.304  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:36.304  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:16:36.304  1017  1017 I MotionRecognitionService: Plugged
08-26 15:16:36.304  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:16:36.304  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:16:36.304  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:16:36.304  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:36.314  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:36.314  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:36.334  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:36.334  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:16:36.334  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:38.634   291   291 E SMD     : DCD OFF,
,08-26 15:16:41.044  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:16:41.644   291   291 E SMD     : DCD OFF,
,08-26 15:16:42.404  1017  1320 E Watchdog: !@Sync 37,
,08-26 15:16:44.644   291   291 E SMD     : DCD OFF,
,08-26 15:16:46.354  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:46.354  1017  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:46.354  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:46.354  1017  1030 D BatteryService: stay LED for fully charged
08-26 15:16:46.354  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:46.364  1017  1017 I MotionRecognitionService: Plugged
08-26 15:16:46.364  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:16:46.364  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:16:46.364  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:16:46.364  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:16:46.364  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:46.374  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:46.374  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:46.384  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:46.384  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:16:46.384  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:47.644   291   291 E SMD     : DCD OFF,
,08-26 15:16:50.644   291   291 E SMD     : DCD OFF,
,08-26 15:16:51.074  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:16:53.644   291   291 E SMD     : DCD OFF
,08-26 15:16:56.424  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:16:56.424  1017  4337 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:16:56.424  1017  4337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:16:56.424  1017  4337 D BatteryService: stay LED for fully charged
08-26 15:16:56.424  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:16:56.434  1017  1017 I MotionRecognitionService: Plugged
08-26 15:16:56.434  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:16:56.434  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:16:56.434  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:16:56.434  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:16:56.434  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:16:56.444  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:16:56.444  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:16:56.454  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:56.454  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:16:56.454  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:16:56.644   291   291 E SMD     : DCD OFF
,08-26 15:16:59.644   291   291 E SMD     : DCD OFF,
,08-26 15:17:01.094  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:17:02.654   291   291 E SMD     : DCD OFF,
,08-26 15:17:05.654   291   291 E SMD     : DCD OFF,
,08-26 15:17:06.484  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:06.484  1017  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:17:06.484  1017  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:17:06.484  1017  1495 D BatteryService: stay LED for fully charged
08-26 15:17:06.484  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:06.494  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:17:06.494  1017  1017 I MotionRecognitionService: Plugged
08-26 15:17:06.494  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:17:06.494  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:17:06.494  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:17:06.494  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:17:06.504  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:17:06.504  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:06.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:06.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:17:06.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:08.654   291   291 E SMD     : DCD OFF,
,08-26 15:17:11.124  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:17:11.654   291   291 E SMD     : DCD OFF
,08-26 15:17:12.404  1017  1320 E Watchdog: !@Sync 38,
,08-26 15:17:14.654   291   291 E SMD     : DCD OFF,
,08-26 15:17:16.544  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:16.544  1017  4338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:17:16.544  1017  4338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:17:16.544  1017  4338 D BatteryService: stay LED for fully charged
08-26 15:17:16.544  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:16.544  1017  1017 I MotionRecognitionService: Plugged
08-26 15:17:16.544  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:17:16.554  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:17:16.554  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:17:16.554  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:17:16.554  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:17:16.564  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:16.564  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:16.574  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:16.574  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:17:16.574  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:17.654   291   291 E SMD     : DCD OFF,
,08-26 15:17:20.664   291   291 E SMD     : DCD OFF,
,08-26 15:17:21.144  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:17:23.664   291   291 E SMD     : DCD OFF,
,08-26 15:17:26.604  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:26.664   291   291 E SMD     : DCD OFF,
,08-26 15:17:29.664   291   291 E SMD     : DCD OFF,
,08-26 15:17:31.164  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:17:32.664   291   291 E SMD     : DCD OFF,
,08-26 15:17:35.664   291   291 E SMD     : DCD OFF,
,08-26 15:17:36.664  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:38.674   291   291 E SMD     : DCD OFF,
,08-26 15:17:41.194  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:17:41.674   291   291 E SMD     : DCD OFF,
,08-26 15:17:42.404  1017  1320 E Watchdog: !@Sync 39,
,08-26 15:17:44.674   291   291 E SMD     : DCD OFF,
,08-26 15:17:46.724  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:46.724  1017  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:17:46.724  1017  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:17:46.724  1017  1484 D BatteryService: stay LED for fully charged
08-26 15:17:46.724  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:17:46.724  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:17:46.724  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:17:46.724  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:17:46.734  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:17:46.734  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:17:46.734  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:17:46.744  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:17:46.744  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:17:46.754  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:46.754  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:17:46.754  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:17:47.674   291   291 E SMD     : DCD OFF,
,08-26 15:17:50.674   291   291 E SMD     : DCD OFF,
,08-26 15:17:51.224  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:17:53.674   291   291 E SMD     : DCD OFF
,08-26 15:17:56.684   291   291 E SMD     : DCD OFF
,08-26 15:17:56.784  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:17:59.684   291   291 E SMD     : DCD OFF
,08-26 15:18:01.264  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:18:02.684   291   291 E SMD     : DCD OFF,
,08-26 15:18:05.684   291   291 E SMD     : DCD OFF,
,08-26 15:18:06.844  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:06.844  1017  1221 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:06.844  1017  1221 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:06.844  1017  1221 D BatteryService: stay LED for fully charged
08-26 15:18:06.844  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:06.844  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:18:06.844  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:18:06.844  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:18:06.844  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
08-26 15:18:06.854  1017  1017 I MotionRecognitionService: Plugged
08-26 15:18:06.854  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:18:06.864  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:18:06.864  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:06.874  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:06.874  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:18:06.874  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:08.684   291   291 E SMD     : DCD OFF,
,08-26 15:18:09.384  1017  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
08-26 15:18:09.384  1017  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
08-26 15:18:09.384  1017  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:18:10.004  1017  1042 I UsageStatsService: User[0] Flushing usage stats to disk,
,08-26 15:18:10.054  1017  1102 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,08-26 15:18:10.054  1017  1102 I ApplicationUsage: Updating Usage Statistics in DB @ 1472217490060
,08-26 15:18:10.054  1017  1102 I ApplicationPolicy: updateDataUsageMap
,08-26 15:18:10.224  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:18:10.224  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:18:10.224  1017  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:18:10.224  1017  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:18:10.554  1017  1102 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,08-26 15:18:10.554  1017  1102 I NetworkDataUsageDb: ::isTableExists: Table exists 
,08-26 15:18:10.574  1017  1102 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1472217490584
,08-26 15:18:11.304  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:18:11.684   291   291 E SMD     : DCD OFF
,08-26 15:18:12.304  1017  1050 I PowerManagerService: [PWL] Off : 1155s ago
,08-26 15:18:12.414  1017  1320 E Watchdog: !@Sync 40,
,08-26 15:18:14.684   291   291 E SMD     : DCD OFF,
,08-26 15:18:16.894  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:16.904  1017  1484 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:16.904  1017  1484 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:16.904  1017  1484 D BatteryService: stay LED for fully charged
08-26 15:18:16.904  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:16.904  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:18:16.904  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:18:16.904  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:18:16.904  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:18:16.904  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:18:16.904  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:18:16.914  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:18:16.914  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:16.934  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:18:16.934  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:18:16.934  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:17.694   291   291 E SMD     : DCD OFF,
,08-26 15:18:20.694   291   291 E SMD     : DCD OFF,
,08-26 15:18:21.344  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:18:23.694   291   291 E SMD     : DCD OFF
,08-26 15:18:26.694   291   291 E SMD     : DCD OFF
,08-26 15:18:26.954  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:26.954  1017  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:26.954  1017  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:26.954  1017  1496 D BatteryService: stay LED for fully charged
08-26 15:18:26.954  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:26.964  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:18:26.964  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:18:26.964  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:18:26.964  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:18:26.964  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:18:26.964  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:18:26.974  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:18:26.974  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:26.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:26.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:18:26.984  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:29.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:31.354  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:18:32.694   291   291 E SMD     : DCD OFF
,08-26 15:18:35.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:37.014  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:37.014  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:37.014  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:37.024  1017  1512 D BatteryService: stay LED for fully charged
,08-26 15:18:37.024  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:18:37.024  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:18:37.024  1017  1017 I MotionRecognitionService: Plugged
08-26 15:18:37.024  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:18:37.024  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:18:37.024  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:18:37.024  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:18:37.034  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:18:37.034  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:37.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:37.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:37.054  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:38.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:41.394  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:18:41.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:42.404  1017  1320 E Watchdog: !@Sync 41,
,08-26 15:18:44.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:47.074  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:47.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:50.704   291   291 E SMD     : DCD OFF,
,08-26 15:18:51.434  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:18:53.714   291   291 E SMD     : DCD OFF,
,08-26 15:18:56.714   291   291 E SMD     : DCD OFF,
,08-26 15:18:57.134  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:18:57.134  1017  1496 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:18:57.144  1017  1496 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:18:57.144  1017  1496 D BatteryService: stay LED for fully charged
08-26 15:18:57.144  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:18:57.144  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:18:57.144  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:18:57.144  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-26 15:18:57.144  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:18:57.154  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:18:57.154  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:18:57.154  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:18:57.154  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:18:57.174  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:57.174  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:57.174  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:18:59.714   291   291 E SMD     : DCD OFF,
,08-26 15:19:01.444  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:19:02.714   291   291 E SMD     : DCD OFF,
,08-26 15:19:05.714   291   291 E SMD     : DCD OFF,
,08-26 15:19:07.194  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:19:07.194  1017  4337 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:19:07.194  1017  4337 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:19:07.194  1017  4337 D BatteryService: stay LED for fully charged
08-26 15:19:07.194  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:19:07.204  1017  1017 I MotionRecognitionService: Plugged,
08-26 15:19:07.204  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:19:07.204  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:19:07.204  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:19:07.204  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:19:07.204  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:19:07.224  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:19:07.224  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:19:07.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:07.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:19:07.234  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:08.724   291   291 E SMD     : DCD OFF,
,08-26 15:19:11.484  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:19:11.724   291   291 E SMD     : DCD OFF,
,08-26 15:19:12.414  1017  1320 E Watchdog: !@Sync 42
,08-26 15:19:14.724   291   291 E SMD     : DCD OFF
,08-26 15:19:17.254  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:17.254  1017  1495 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:19:17.254  1017  1495 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:19:17.254  1017  1495 D BatteryService: stay LED for fully charged
08-26 15:19:17.254  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:19:17.254  1017  1017 I MotionRecognitionService: Plugged
08-26 15:19:17.254  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:19:17.264  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:19:17.264  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:19:17.264  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:19:17.264  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:19:17.274  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:19:17.274  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:19:17.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:17.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:19:17.284  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:17.724   291   291 E SMD     : DCD OFF
,08-26 15:19:19.654  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:19:19.654  5900  6791 I PlayCommon: [1065] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:19:19.784  5900  6017 I PlayCommon: [1047] com.google.android.play.a.l.e(787): Preparing logs for uploading,
08-26 15:19:19.784  5900  6017 I PlayCommon: [1047] com.google.android.play.a.l.e(789): No file ready to send
,08-26 15:19:20.724   291   291 E SMD     : DCD OFF
,08-26 15:19:21.514  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:19:23.724   291   291 E SMD     : DCD OFF,
,08-26 15:19:26.734   291   291 E SMD     : DCD OFF,
,08-26 15:19:27.314  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:29.734   291   291 E SMD     : DCD OFF,
,08-26 15:19:31.524  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:19:32.734   291   291 E SMD     : DCD OFF,
,08-26 15:19:35.734   291   291 E SMD     : DCD OFF,
,08-26 15:19:37.374  1017  4337 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:38.734   291   291 E SMD     : DCD OFF,
,08-26 15:19:41.574  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:19:41.734   291   291 E SMD     : DCD OFF,
,08-26 15:19:42.414  1017  1320 E Watchdog: !@Sync 43,
,08-26 15:19:44.744   291   291 E SMD     : DCD OFF,
,08-26 15:19:47.434  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:19:47.744   291   291 E SMD     : DCD OFF,
,08-26 15:19:50.744   291   291 E SMD     : DCD OFF,
,08-26 15:19:51.624  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:19:53.744   291   291 E SMD     : DCD OFF,
,08-26 15:19:56.744   291   291 E SMD     : DCD OFF,
,08-26 15:19:57.494  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:19:57.494  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:19:57.494  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:19:57.494  1017  1512 D BatteryService: stay LED for fully charged
08-26 15:19:57.494  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:19:57.504  1017  1017 I MotionRecognitionService: Plugged
08-26 15:19:57.504  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:19:57.504  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:19:57.504  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:19:57.504  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:19:57.504  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:19:57.514  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 15:19:57.514  3157  3269 D HeadsetStateMachine: Disconnected process message: 10,
,08-26 15:19:57.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:57.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:57.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:19:59.744   291   291 E SMD     : DCD OFF,
,08-26 15:20:01.634  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:20:02.304  1017  1050 I PowerManagerService: [PWL] Off : 1265s ago,
,08-26 15:20:02.744   291   291 E SMD     : DCD OFF,
,08-26 15:20:05.754   291   291 E SMD     : DCD OFF,
,08-26 15:20:07.554  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:07.554  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:20:07.554  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:20:07.554  1017  1135 D BatteryService: stay LED for fully charged
08-26 15:20:07.554  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:20:07.554  1017  1017 I MotionRecognitionService: Plugged
08-26 15:20:07.554  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 15:20:07.564  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:20:07.564  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:20:07.564  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-26 15:20:07.564  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:20:07.574  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:20:07.574  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:20:07.584  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:07.584  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:20:07.584  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:08.754   291   291 E SMD     : DCD OFF,
,08-26 15:20:11.674  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:20:11.754   291   291 E SMD     : DCD OFF,
,08-26 15:20:12.414  1017  1320 E Watchdog: !@Sync 44,
,08-26 15:20:14.754   291   291 E SMD     : DCD OFF,
,08-26 15:20:17.614  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:17.614  1017  4339 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:20:17.614  1017  4339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:20:17.614  1017  4339 D BatteryService: stay LED for fully charged
08-26 15:20:17.614  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:20:17.624  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:20:17.624  1017  1017 I MotionRecognitionService: Plugged
08-26 15:20:17.624  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:20:17.624  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:20:17.624  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:20:17.624  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:20:17.634  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:20:17.634  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:20:17.654  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:17.654  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:17.654  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:20:17.754   291   291 E SMD     : DCD OFF,
,08-26 15:20:20.764   291   291 E SMD     : DCD OFF,
,08-26 15:20:21.704  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:20:23.764   291   291 E SMD     : DCD OFF,
,08-26 15:20:26.764   291   291 E SMD     : DCD OFF,
,08-26 15:20:27.684  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:29.764   291   291 E SMD     : DCD OFF,
,08-26 15:20:31.724  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:20:32.764   291   291 E SMD     : DCD OFF,
,08-26 15:20:35.764   291   291 E SMD     : DCD OFF,
,08-26 15:20:37.744  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:38.774   291   291 E SMD     : DCD OFF,
,08-26 15:20:41.764  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:20:41.764   291   291 E SMD     : DCD OFF
,08-26 15:20:42.414  1017  1320 E Watchdog: !@Sync 45,
,08-26 15:20:44.774   291   291 E SMD     : DCD OFF,
,08-26 15:20:47.774   291   291 E SMD     : DCD OFF,
,08-26 15:20:47.824  1017  1496 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:20:50.774   291   291 E SMD     : DCD OFF,
,08-26 15:20:51.814  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:20:53.774   291   291 E SMD     : DCD OFF,
,08-26 15:20:56.784   291   291 E SMD     : DCD OFF,
,08-26 15:20:57.884  1017  1221 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:20:59.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:01.824  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:21:02.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:05.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:07.954  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:21:08.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:11.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:11.874  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:21:12.414  1017  1320 E Watchdog: !@Sync 46,
,08-26 15:21:14.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:17.784   291   291 E SMD     : DCD OFF,
,08-26 15:21:18.014  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:20.794   291   291 E SMD     : DCD OFF,
,08-26 15:21:21.924  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:21:23.794   291   291 E SMD     : DCD OFF,
,08-26 15:21:26.794   291   291 E SMD     : DCD OFF,
,08-26 15:21:28.074  1017  1495 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:29.794   291   291 E SMD     : DCD OFF,
,08-26 15:21:31.934  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:21:32.794   291   291 E SMD     : DCD OFF,
,08-26 15:21:35.794   291   291 E SMD     : DCD OFF,
,08-26 15:21:38.134  1017  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:21:38.804   291   291 E SMD     : DCD OFF,
,08-26 15:21:41.804   291   291 E SMD     : DCD OFF,
,08-26 15:21:41.984  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:21:42.414  1017  1320 E Watchdog: !@Sync 47,
,08-26 15:21:44.804   291   291 E SMD     : DCD OFF,
,08-26 15:21:47.804   291   291 E SMD     : DCD OFF
,08-26 15:21:48.194  1017  1135 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-26 15:21:48.194  1017  1135 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:21:48.194  1017  1135 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 15:21:48.194  1017  1135 D BatteryService: stay LED for fully charged
08-26 15:21:48.194  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:21:48.194  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:21:48.194  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:21:48.204  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:21:48.204  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 15:21:48.204  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:21:48.204  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:21:48.214  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:21:48.214  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:21:48.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:48.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:21:48.224  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:21:50.804   291   291 E SMD     : DCD OFF,
,08-26 15:21:52.014  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:21:53.814   291   291 E SMD     : DCD OFF
,08-26 15:21:56.814   291   291 E SMD     : DCD OFF,
,08-26 15:21:57.314  1017  1050 I PowerManagerService: [PWL] Off : 1380s ago,
,08-26 15:21:58.254  1017  4339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:21:59.814   291   291 E SMD     : DCD OFF,
,08-26 15:22:02.034  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:22:02.814   291   291 E SMD     : DCD OFF,
,08-26 15:22:05.814   291   291 E SMD     : DCD OFF,
,08-26 15:22:08.314  1017  1512 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:08.314  1017  1512 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:08.314  1017  1512 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:08.314  1017  1512 D BatteryService: stay LED for fully charged
08-26 15:22:08.314  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:08.314  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:22:08.314  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:22:08.324  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 15:22:08.324  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:22:08.324  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:22:08.324  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:08.324  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:22:08.324  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:08.344  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:08.344  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:22:08.344  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:08.814   291   291 E SMD     : DCD OFF,
,08-26 15:22:11.824   291   291 E SMD     : DCD OFF,
,08-26 15:22:12.064  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:22:12.414  1017  1320 E Watchdog: !@Sync 48
,08-26 15:22:14.814   291   291 E SMD     : DCD OFF,
,08-26 15:22:17.824   291   291 E SMD     : DCD OFF,
,08-26 15:22:18.374  1017  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,08-26 15:22:20.824   291   291 E SMD     : DCD OFF
,08-26 15:22:22.104  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:22:23.824   291   291 E SMD     : DCD OFF,
,08-26 15:22:26.824   291   291 E SMD     : DCD OFF,
,08-26 15:22:28.434  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:29.834   291   291 E SMD     : DCD OFF
,08-26 15:22:32.124  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:22:32.824   291   291 E SMD     : DCD OFF
,08-26 15:22:35.834   291   291 E SMD     : DCD OFF,
,08-26 15:22:38.494  1017  4338 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:38.494  1017  4338 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:38.494  1017  4338 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:38.494  1017  4338 D BatteryService: stay LED for fully charged
,08-26 15:22:38.494  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:38.504  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:22:38.504  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:22:38.504  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:22:38.504  1017  1017 I MotionRecognitionService: Plugged
08-26 15:22:38.504  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
08-26 15:22:38.504  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:38.514  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:38.514  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:38.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:38.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:22:38.524  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:38.834   291   291 E SMD     : DCD OFF
,08-26 15:22:41.834   291   291 E SMD     : DCD OFF,
,08-26 15:22:42.164  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:22:42.424  1017  1320 E Watchdog: !@Sync 49
,08-26 15:22:44.834   291   291 E SMD     : DCD OFF
,08-26 15:22:47.844   291   291 E SMD     : DCD OFF,
,08-26 15:22:48.554  1017  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:48.554  1017  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:48.554  1017  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:48.554  1017  1029 D BatteryService: stay LED for fully charged
,08-26 15:22:48.554  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:48.554  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:22:48.554  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:22:48.564  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:22:48.564  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:22:48.564  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:22:48.564  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:48.574  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:48.574  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:48.584  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 15:22:48.584  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:22:48.584  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:50.834   291   291 E SMD     : DCD OFF,
,08-26 15:22:52.194  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:22:53.844   291   291 E SMD     : DCD OFF,
,08-26 15:22:56.844   291   291 E SMD     : DCD OFF,
,08-26 15:22:58.604  1017  1536 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:22:58.604  1017  1536 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:22:58.614  1017  1536 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:22:58.614  1017  1536 D BatteryService: stay LED for fully charged
,08-26 15:22:58.614  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:22:58.614  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:22:58.614  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:22:58.614  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:22:58.614  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:22:58.624  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:22:58.624  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:22:58.624  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:22:58.634  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:22:58.644  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:58.644  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 15:22:58.644  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:22:59.844   291   291 E SMD     : DCD OFF
,08-26 15:23:02.214  1017  3332 D SSRM:n  : SIOP:: AP = 290,
,08-26 15:23:02.844   291   291 E SMD     : DCD OFF,
,08-26 15:23:05.844   291   291 E SMD     : DCD OFF
,08-26 15:23:08.674  1017  3262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:23:08.674  1017  3262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 15:23:08.674  1017  3262 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 15:23:08.674  1017  3262 D BatteryService: stay LED for fully charged
,08-26 15:23:08.674  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:23:08.674  1017  1017 I MotionRecognitionService: Plugged
,08-26 15:23:08.674  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:23:08.684  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:23:08.684  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:23:08.684  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:23:08.684  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 15:23:08.694  3157  3157 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:23:08.694  3157  3269 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:23:08.704  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:23:08.704  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:23:08.704  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 15:23:08.844   291   291 E SMD     : DCD OFF,
,08-26 15:23:09.384  1017  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
,08-26 15:23:09.384  1017  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,08-26 15:23:09.384  1017  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,08-26 15:23:11.344  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,08-26 15:23:11.344  1017  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,08-26 15:23:11.344  1017  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:23:11.344  1017  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,08-26 15:23:11.854   291   291 E SMD     : DCD OFF,
,08-26 15:23:12.254  1017  3332 D SSRM:n  : SIOP:: AP = 290
,08-26 15:23:12.424  1017  1320 E Watchdog: !@Sync 50
,TIME-OUT KILL (timeout was 1400000ms),08-26 15:23:12.884  7602  7602 D AndroidRuntime: 
08-26 15:23:12.884  7602  7602 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:23:12.894  7602  7602 D AndroidRuntime: CheckJNI is OFF
08-26 15:23:12.894  7602  7602 D AndroidRuntime: readGMSProperty: start
08-26 15:23:12.894  7602  7602 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:23:12.894  7602  7602 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 15:23:12.894  7602  7602 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 15:23:12.894  7602  7602 D AndroidRuntime: readGMSProperty: end
08-26 15:23:12.894  7602  7602 D AndroidRuntime: addProductProperty: start
08-26 15:23:13.034  7602  7602 E AffinityControl: AffinityControl: registerfunction enter
08-26 15:23:13.054  7602  7602 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 15:23:13.074  1017  1135 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-26 15:23:13.074  1017  1135 D PackageManager: START PACKAGE DELETE: observer{443152815}
08-26 15:23:13.074  1017  1135 D PackageManager: pkg{<packageName>}
08-26 15:23:13.074  1017  1135 D PackageManager: user{0}
08-26 15:23:13.074  1017  1135 D PackageManager: caller{2000}
08-26 15:23:13.074  1017  1135 D PackageManager: flags{2}
08-26 15:23:13.074  1017  1135 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 15:23:13.074  1017  1135 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 15:23:13.074  1017  1135 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:23:13.074  1017  1135 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:23:13.084  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 15:23:13.084  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 15:23:13.084  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 15:23:13.084  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 15:23:13.084  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-26 15:23:13.084  1017  1057 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
08-26 15:23:13.084  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-26 15:23:13.174  1017  1057 W PackageSettings: Skipping PackageSetting{2fc3e828 com.example.hello/10168} due to missing metadata
08-26 15:23:13.214  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
08-26 15:23:13.224  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
08-26 15:23:13.264  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 15:23:13.284  1999  2151 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 15:23:13.294  1868  1868 E SamsungIME: mOCRHelper is null
08-26 15:23:13.314  1017  1124 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-26 15:23:13.314  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:13.314  1017  1124 V NetworkStats: performPollLocked(flags=0x3)
08-26 15:23:13.314  2633  2633 I art     : Explicit concurrent mark sweep GC freed 19464(1111KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 780us total 69.673ms
08-26 15:23:13.324  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:23:13.324  1017  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:23:13.334  1017  1124 V NetworkStats: performPollLocked() took 24ms
08-26 15:23:13.334  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:13.344  2884  2884 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:23:13 GMT+02:00 2016
08-26 15:23:13.344  1458  1458 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:23:13.344  1017  3262 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 15:23:13.344  1017  3262 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-26 15:23:13.344  1017  3262 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:13.344  1017  3262 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:13.344  1017  3262 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-26 15:23:13.354  1458  1458 D RegisteredServicesCache: empty dynamic service
08-26 15:23:13.354  2884  2884 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-26 15:23:13.354  1017  1322 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-26 15:23:13.354  1017  1322 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-26 15:23:13.364  6730  6730 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-26 15:23:13.364  1017  1030 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-26 15:23:13.364  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-26 15:23:13.364  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:13.364  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:13.364  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-26 15:23:13.364  6730  6730 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-26 15:23:13.384  1458  1458 D RegisteredComponentCache: Collect Tech packages for Knox
08-26 15:23:13.384  1458  1458 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:23:13.384  2884  2884 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-26 15:23:13.384  6730  6730 D elm:15121: ElmAgentService : onCreate()
08-26 15:23:13.384  4748  4748 I art     : Explicit concurrent mark sweep GC freed 22463(1344KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 12MB/17MB, paused 9.178ms total 166.965ms
08-26 15:23:13.394  2884  2884 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-26 15:23:13.394  6730  7614 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-26 15:23:13.394  2884  2884 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-26 15:23:13.394  6730  7614 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-26 15:23:13.394  6730  7614 D elm:15121: MDMBridge.getInstance()
08-26 15:23:13.394  6730  7614 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-26 15:23:13.394  6730  7614 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
08-26 15:23:13.404  2884  7613 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-26 15:23:13.404  2884  7613 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-26 15:23:13.414  6730  6730 D elm:15121: ElmAgentService : onDestroy().
08-26 15:23:13.414  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 15:23:13.414  1017  1030 D SecContentProvider2: mCursor = null
08-26 15:23:13.434  2884  7613 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-26 15:23:13.434  2884  7613 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
08-26 15:23:13.464  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:13.464  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:23:13.464  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-26 15:23:13.474  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.474  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.474  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.474  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.474  1017  1017 I art     : Explicit concurrent mark sweep GC freed 52834(6MB) AllocSpace objects, 229(3MB) LOS objects, 33% free, 24MB/37MB, paused 9.629ms total 252.203ms
08-26 15:23:13.484  1017  1057 I art     : WaitForGcToComplete blocked for 237.958ms for cause Explicit
08-26 15:23:13.484  7615  7615 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.484  7615  7615 E Zygote  : v2
08-26 15:23:13.484  7615  7615 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:23:13.484  7615  7615 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.484  1017  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7615 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:23:13.494  7615  7615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.494  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-26 15:23:13.494  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.494  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.494  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.494  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.494  7615  7615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.494  7615  7615 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.504  1017  4338 I TactileAssist: enable value -1
08-26 15:23:13.504  1017  4338 I TactileAssist: internal enable value -1
08-26 15:23:13.504  1017  4338 I TactileAssist: intensity value -1
08-26 15:23:13.504  1017  4338 I TactileAssist: saveAppList value true
08-26 15:23:13.514  7624  7624 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.514  7624  7624 E Zygote  : v2
08-26 15:23:13.514  7624  7624 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:23:13.514  7624  7624 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.514  7624  7624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.514  7624  7624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.514  7624  7624 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.524  1017  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:23:13.544  1017  4338 I TactileAssist: List of disabled apps :
08-26 15:23:13.544  7615  7615 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.544  7615  7615 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.544  7624  7624 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.544  7624  7624 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.554  2884  7613 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-26 15:23:13.554  1017  1017 D RCPManagerService: PackageReceiver onReceive()
08-26 15:23:13.554  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-26 15:23:13.564  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 15:23:13.564  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 15:23:13.564  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
08-26 15:23:13.574  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
08-26 15:23:13.574  2884  7613 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-26 15:23:13.574  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-26 15:23:13.574  1017  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
08-26 15:23:13.584  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.584  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.584  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.584  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.584  2884  7613 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-26 15:23:13.594  7645  7645 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.594  7645  7645 E Zygote  : v2
08-26 15:23:13.594  1017  1221 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7645 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
08-26 15:23:13.594  7645  7645 I libpersona: KNOX_SDCARD checking this for 10048
08-26 15:23:13.594  7645  7645 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.594  7645  7645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.604  7645  7645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.604  7645  7645 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 15:23:13.614  2884  2884 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-26 15:23:13.624  7624  7624 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
08-26 15:23:13.624  1017  1536 D SecContentProvider2: uri = -1 selection = getSealedState
08-26 15:23:13.624  1017  1536 D SecContentProvider2: mCursor = null
08-26 15:23:13.624  7624  7624 I PopupuiReceiver_KNOX: getSealedState : true
08-26 15:23:13.624  1017  1484 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-26 15:23:13.624  1017  1484 D SecContentProvider2: mCursor = null
08-26 15:23:13.624  7624  7624 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-26 15:23:13.624  1017  1495 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-26 15:23:13.624  1017  1495 D SecContentProvider2: mCursor = null
08-26 15:23:13.624  7624  7624 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-26 15:23:13.624  7624  7624 D PopupuiReceiver: Action package removed
08-26 15:23:13.624  1017  1322 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-26 15:23:13.634  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.634  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.634  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.634  1017  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.644  7659  7659 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.644  7659  7659 I libpersona: KNOX_SDCARD checking this for 10145
08-26 15:23:13.644  7659  7659 E Zygote  : v2
08-26 15:23:13.644  7659  7659 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.644  7659  7659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.644  1017  1322 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7659 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:23:13.644  1017  1322 I ActivityManager: Killing 6670:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
08-26 15:23:13.654  7659  7659 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.654  7659  7659 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.664  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 15:23:13.664  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 15:23:13.664  7645  7645 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 15:23:13.664  7645  7645 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 15:23:13.664  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: uID is 10171
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 15:23:13.664  1017  3332 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-26 15:23:13.664  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 15:23:13.664  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-26 15:23:13.674  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-26 15:23:13.684  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.684  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.684  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.684  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.694  7673  7673 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.694  7673  7673 E Zygote  : v2
08-26 15:23:13.694  7673  7673 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:23:13.694  7673  7673 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.694  7673  7673 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.704  7659  7659 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.704  7673  7673 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.704  7659  7659 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.704  7673  7673 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.714  1017  1017 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:23:13.714  1017  1017 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-26 15:23:13.724  7673  7673 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.734  7673  7673 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.744  7615  7615 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-26 15:23:13.744  7645  7645 D Compatibility: onReceive() it will make start service
08-26 15:23:13.754  1017  1221 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-26 15:23:13.754  1017  1221 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-26 15:23:13.754  1017  1221 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:13.754  1017  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:13.754  1017  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-26 15:23:13.774  1017  4338 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-26 15:23:13.774  1017  1057 I art     : Explicit concurrent mark sweep GC freed 15196(1011KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 7.124ms total 290.521ms
08-26 15:23:13.774  1017  4338 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-26 15:23:13.774  1017  4338 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:13.774  1017  4338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:13.774  1017  4338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
08-26 15:23:13.774  1017  1512 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-26 15:23:13.784  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.784  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.784  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.784  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.784  7645  7691 D Compatibility: onHandleIntent()
08-26 15:23:13.784  7673  7673 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 15:23:13.784  7673  7673 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 15:23:13.784  7673  7673 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-26 15:23:13.794  7645  7691 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-26 15:23:13.794  7645  7691 D Compatibility: found: 2
08-26 15:23:13.794  7692  7692 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.794  7692  7692 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:23:13.794  7692  7692 E Zygote  : v2
08-26 15:23:13.794  7692  7692 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.794  7692  7692 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.794  7692  7692 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.804  7692  7692 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.804  1017  1512 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7692 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-26 15:23:13.804  7645  7691 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-26 15:23:13.804  7645  7691 D Compatibility: skipping ResolveInfo{3501133e com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-26 15:23:13.804  7645  7691 D Compatibility: considering ResolveInfo{546459f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-26 15:23:13.804  7645  7691 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-26 15:23:13.814  7645  7691 D Compatibility: enabling receiver ResolveInfo{201c46ec com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-26 15:23:13.814  1017  1512 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-26 15:23:13.814  7659  7659 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-26 15:23:13.814  7659  7659 D ThemeInfoUtil: isCurrentFestival = false
08-26 15:23:13.814  7645  7691 D Compatibility: enabling receiver ResolveInfo{102e4ab5 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-26 15:23:13.814  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.814  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.814  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.814  1017  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.824  7673  7673 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 15:23:13.824  7673  7673 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 15:23:13.824  7673  7673 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 15:23:13.824  7673  7673 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-26 15:23:13.834  7708  7708 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.834  7708  7708 I libpersona: KNOX_SDCARD checking this for 10052
08-26 15:23:13.834  7708  7708 E Zygote  : v2
08-26 15:23:13.834  7708  7708 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.834  7645  7691 D Compatibility: enabling receiver ResolveInfo{3b77254a com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-26 15:23:13.834  7708  7708 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.834  7692  7692 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.834  7692  7692 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.834  7708  7708 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.834  7708  7708 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:23:13.844  1017  1512 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7708 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-26 15:23:13.844  1017  1221 I ActivityManager: Killing 6687:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-26 15:23:13.854  7645  7691 D Compatibility: enabling receiver ResolveInfo{539cbb com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-26 15:23:13.854  7645  7691 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
08-26 15:23:13.854  1017  1221 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-26 15:23:13.854  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.854  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.854  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.854  1017  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.864  1017  1057 D PackageManager: delete codoeFile: 
08-26 15:23:13.864  7692  7692 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:23:13.874  7721  7721 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.874  7721  7721 E Zygote  : v2
08-26 15:23:13.874  7721  7721 I libpersona: KNOX_SDCARD checking this for 10148
08-26 15:23:13.874  7721  7721 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.874  7721  7721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.874  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-26 15:23:13.874  1017  1057 I AASA_removePackage: UID=10171 Target=com.test.thalitest
08-26 15:23:13.874  7708  7708 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.874  7708  7708 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.874  1017  1057 D PackageManager: result of delete: 1{443152815}
08-26 15:23:13.874  1017  1221 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7721 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-26 15:23:13.874  1017  1221 I ActivityManager: Killing 6704:com.qualcomm.timeservice/1000 (adj 15): empty #21
08-26 15:23:13.884  7721  7721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.884  7721  7721 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.884  7602  7602 D AndroidRuntime: Shutting down VM
08-26 15:23:13.884  7692  7692 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-26 15:23:13.894  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 15:23:13.894  1017  1057 D PackageManager: userId{-1}
08-26 15:23:13.894  1017  1057 D PackageManager: andCode{true}
08-26 15:23:13.894  1017  1484 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-26 15:23:13.894  1017  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.894  1017  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.894  1017  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.894  1017  1484 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.904  1017  1030 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-26 15:23:13.904  1017  1030 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-26 15:23:13.914  7735  7735 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.914  7735  7735 E Zygote  : v2
08-26 15:23:13.914  7735  7735 I libpersona: KNOX_SDCARD checking this for 10029
08-26 15:23:13.914  7735  7735 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.914  7735  7735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.914  1017  1484 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7735 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-26 15:23:13.914  7735  7735 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.914  1017  1484 I ActivityManager: Killing 6634:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-26 15:23:13.914  7735  7735 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:23:13.914  1017  4339 I ActivityManager: Killing 6747:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
08-26 15:23:13.934  1017  4339 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-26 15:23:13.934  1017  4339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.934  1017  4339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.944  1017  4339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.944  1017  4339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:13.944  7721  7721 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.944  7721  7721 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.954  7735  7735 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:13.954  7735  7735 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:13.974  7754  7754 E Zygote  : MountEmulatedStorage()
08-26 15:23:13.974  7754  7754 E Zygote  : v2
08-26 15:23:13.974  7754  7754 I libpersona: KNOX_SDCARD checking this for 10087
08-26 15:23:13.974  7754  7754 I libpersona: KNOX_SDCARD not a persona
08-26 15:23:13.974  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 15:23:13.974  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 15:23:13.974  1017  4339 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7754 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-26 15:23:13.974  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:23:13.974  1017  4339 I ActivityManager: Killing 6569:com.android.calendar/u0a131 (adj 15): empty #21
08-26 15:23:13.984  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-26 15:23:14.004  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:23:14.004  7754  7754 D ActivityThread: Added TimaKeyStore provider
08-26 15:23:14.034  7721  7721 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-26 15:23:14.044  1017  1322 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
08-26 15:23:14.044  1017  4338 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-26 15:23:14.044  1017  4338 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
08-26 15:23:14.044  1017  4338 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:23:14.044  1017  4338 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:23:14.044  1017  4338 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
08-26 15:23:14.054  1017  1135 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-26 15:23:14.054  1017  4337 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
08-26 15:23:14.054  1017  4337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:14.054  1017  4337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:14.054  1017  4337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:14.054  1017  4337 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:23:14.054  7735  7770 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-26 15:23:14.064  7773  7773 E Zygote  : MountEmulatedStorage()
08-26 15:23:14.064  7773  7773 E Zygote  : v2
08-26 15:23:14.064  7773  7773 I libpersona: KNOX_SDCARD checking this for 10152
08-26 15:23:14.064  7773  7773 I libpersona: KNOX_SDCARD not a persona

```
