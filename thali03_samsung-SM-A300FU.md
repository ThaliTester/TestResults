#### Test 80807573a62a5c7_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-17 14:03:56.992   292   292 E SMD     : DCD OFF
,08-17 14:03:57.562  7297  7297 D AndroidRuntime: 
08-17 14:03:57.562  7297  7297 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 14:03:57.562  7297  7297 D AndroidRuntime: CheckJNI is OFF
08-17 14:03:57.562  7297  7297 D AndroidRuntime: readGMSProperty: start
08-17 14:03:57.562  7297  7297 D AndroidRuntime: readGMSProperty: already setted!!
08-17 14:03:57.562  7297  7297 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-17 14:03:57.562  7297  7297 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-17 14:03:57.562  7297  7297 D AndroidRuntime: readGMSProperty: end
08-17 14:03:57.562  7297  7297 D AndroidRuntime: addProductProperty: start
08-17 14:03:57.682  7297  7297 E AffinityControl: AffinityControl: registerfunction enter
08-17 14:03:57.712  7297  7297 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-17 14:03:57.722  1017  1447 E PersonaManagerService: inState():  stateMachine is null !!
08-17 14:03:57.722  1017  1447 I PersonaManagerService: PersonaId don't exist
08-17 14:03:57.722  1017  1447 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-17 14:03:57.722  1017  1447 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-17 14:03:57.742  1017  1447 W ActivityManager: mDVFSHelper.acquire()
08-17 14:03:57.742  1017  1447 D FocusedStackFrame: Set to : 0
08-17 14:03:57.742  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-17 14:03:57.742  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-17 14:03:57.752  1017  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:03:57.752  1017  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:03:57.752  1017  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:03:57.752  1017  1447 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-17 14:03:57.762  7308  7308 E Zygote  : MountEmulatedStorage()
08-17 14:03:57.762  7308  7308 E Zygote  : v2
08-17 14:03:57.762  7308  7308 I libpersona: KNOX_SDCARD checking this for 10170
08-17 14:03:57.762  7308  7308 I libpersona: KNOX_SDCARD not a persona
08-17 14:03:57.762  7308  7308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-17 14:03:57.762  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-17 14:03:57.762  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-17 14:03:57.762   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-17 14:03:57.772  1017  1447 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7308 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 14:03:57.772  1017  1447 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-17 14:03:57.772  1017  1447 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-17 14:03:57.772  7308  7308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-17 14:03:57.772  7308  7308 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-17 14:03:57.772  1017  1447 D InputDispatcher: Focused application set to: xxxx
08-17 14:03:57.772  1017  1447 D InputDispatcher: Focus left window: 1491
08-17 14:03:57.782  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-17 14:03:57.782  7297  7297 D AndroidRuntime: Shutting down VM
08-17 14:03:57.782  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-17 14:03:57.792  7308  7308 D TimaKeyStoreProvider: TimaSignature is unavailable
08-17 14:03:57.792  7308  7308 D ActivityThread: Added TimaKeyStore provider
08-17 14:03:57.792  1017  3720 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-17 14:03:57.792  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-17 14:03:57.822  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{22753a88 token=android.os.BinderProxy@1703e067 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-17 14:03:57.822  1017  3720 D PersonaManager: isKioskContainerExistOnDevice
08-17 14:03:57.832  1491  1491 D Launcher: onTrimMemory. Level: 20
08-17 14:03:57.832  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-17 14:03:57.842   258  1097 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-17 14:03:57.842   258   450 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-17 14:03:57.952  7308  7308 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-17 14:03:57.982  7297  7297 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-17 14:03:57.982  7308  7308 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 1013-1027)
08-17 14:03:57.982  7308  7308 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 14:03:58.002  7308  7308 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {101f7410}
,08-17 14:03:58.012  7308  7308 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-17 14:03:58.012  7308  7308 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 14:03:58.052  7308  7308 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-17 14:03:58.052  7308  7308 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:03:58.062  7308  7308 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 14:03:58.112  7308  7308 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-17 14:03:58.112  7308  7308 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-17 14:03:58.112  7308  7308 I Adreno-EGL: Build Date: 04/06/15 Mon
08-17 14:03:58.112  7308  7308 I Adreno-EGL: Local Branch: 
08-17 14:03:58.112  7308  7308 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-17 14:03:58.112  7308  7308 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-17 14:03:58.112  7308  7308 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-17 14:03:58.182  7308  7308 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 14:03:58.202  7308  7308 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-17 14:03:58.202  7308  7308 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-17 14:03:58.212  7308  7308 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-17 14:03:58.212  7308  7308 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-17 14:03:58.312  7308  7308 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:03:58.322  7308  7308 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 14:03:58.332  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{3adf6131 u0 com.test.thalitest/.MainActivity t164}
,08-17 14:03:58.342  7308  7308 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-17 14:03:58.342  7308  7308 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-17 14:03:58.342  7308  7308 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-17 14:03:58.352  7308  7308 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:03:58.352  7308  7308 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 14:03:58.392  7308  7347 D OpenGLRenderer: Render dirty regions requested: true
,08-17 14:03:58.392  1017  1507 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-17 14:03:58.392  1017  1507 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-17 14:03:58.402  1017  1507 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-17 14:03:58.402  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-17 14:03:58.402  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-17 14:03:58.402  7308  7335 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-17 14:03:58.412  7308  7308 V ActivityThread: updateVisibility : ActivityRecord{3f63a70 token=android.os.BinderProxy@2eeb43ed {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-17 14:03:58.412  7308  7308 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-17 14:03:58.412  7308  7308 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-17 14:03:58.422   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-17 14:03:58.432  1017  1331 D InputDispatcher: Focus entered window: 7308
,08-17 14:03:58.442  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-17 14:03:58.442  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-17 14:03:58.442  7308  7308 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-17 14:03:58.442  7308  7347 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 14:03:58.452  7308  7347 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-17 14:03:58.452  7308  7347 D OpenGLRenderer: Enabling debug mode 0
,08-17 14:03:58.472  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-17 14:03:58.472  1017  7352 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 14:03:58.482  1179  1179 D PanelView: There is/are notification(s) 
,08-17 14:03:58.492  1017  1047 I ActivityManager: Displayed Component not be shown by security: +661ms (total +2m23s375ms)
,08-17 14:03:58.492  1017  1047 W ActivityManager: mDVFSHelper.release()
08-17 14:03:58.492  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3adf6131 u0 com.test.thalitest/.MainActivity t164} time:261532
,08-17 14:03:58.492   258  1097 I SurfaceFlinger: id=12 Removed uhalitest (7/9),
08-17 14:03:58.492   258   450 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-17 14:03:58.502  7308  7308 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
08-17 14:03:58.502  7308  7308 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2eeb43ed time:261546
,08-17 14:03:58.542  1017  3356 D SSRM:n  : SIOP:: AP = 260
,08-17 14:03:58.552  1883  1883 I SamsungIME: getCurrentCandidateView
,08-17 14:03:58.632  7308  7308 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7308
,08-17 14:03:58.662  1883  1883 D SamsungIME: Dismiss ExpandCandiate
,08-17 14:03:58.802  1883  1883 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 14:03:58.832  7308  7308 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 14:03:58.852  1883  1883 I SamsungIME: getDebugLevel  : 0x4f4c
,08-17 14:03:58.862  1883  1883 I SamsungIME: KeybaordView init() : load resources
,08-17 14:03:58.882  1883  1883 I SamsungIME: getCurrentKeyboard
,08-17 14:03:58.882  1883  1883 I SamsungIME: getTextKeyboard
,08-17 14:03:58.902  1883  1883 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-17 14:03:58.922  7308  7356 D jxcore_app_log: JniHelper::setJavaVM(0xb8a9e2b0), pthread_self() = -1191005328
,08-17 14:03:58.932  7308  7356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 14:03:58.932  7308  7356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 14:03:58.932  7308  7356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 14:03:58.932  7308  7356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 14:03:58.932  7308  7356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-17 14:03:58.932  7308  7356 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d54dd46 added. We now have 1 listener(s)
,08-17 14:03:58.942  7308  7356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-17 14:03:58.942  7308  7356 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,08-17 14:03:58.942  7308  7356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:03:58.942  7308  7356 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 14:03:58.942  7308  7356 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b2025d added. We now have 1 listener(s)
,08-17 14:03:58.942  7308  7356 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:03:58.952  7308  7356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,08-17 14:03:58.962  7308  7356 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:03:58.962  7308  7356 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:03:58.962  7308  7356 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 14:03:58.962  7308  7356 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:03:58.972  7308  7308 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 14:03:58.972  7308  7356 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:03:58.972  7308  7308 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:03:59.002  7308  7308 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 14:03:59.692  1017  3381 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-17 14:03:59.772  7308  7363 W jxcore-log: Initializing JXcore engine
08-17 14:03:59.772  7308  7363 W jxcore-log: JXcore engine is ready
,08-17 14:03:59.832  2004  2004 E audit   : type=1400 msg=audit(1471435439.832:205): avc:  denied  { ioctl } for  pid=7363 comm="Thread-1375" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 14:03:59.832  2004  2004 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-17 14:03:59.832  2004  2004 E audit   : type=1300 msg=audit(1471435439.832:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=9f4fb8f8 items=0 ppid=320 ppcomm=main pid=7363 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1375" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-17 14:03:59.832  2004  2004 E audit   : type=1320 msg=audit(1471435439.832:205): 
,08-17 14:03:59.842  7308  7363 W jxcore-log: Starting JXcore engine
,08-17 14:03:59.952  7308  7363 W jxcore-log: Platform android
08-17 14:03:59.952  7308  7363 W jxcore-log: 
08-17 14:03:59.952  7308  7363 W jxcore-log: Process ARCH arm
08-17 14:03:59.952  7308  7363 W jxcore-log: 
,08-17 14:03:59.992  1017  1095 V AlarmManager: waitForAlarm result :8
,08-17 14:03:59.992   292   292 E SMD     : DCD OFF
,08-17 14:04:00.212  7308  7363 I jxcore-log: JXcore Cordova bridge is ready!
08-17 14:04:00.212  7308  7363 I jxcore-log: 
,08-17 14:04:00.212  7308  7363 W jxcore-log: JXcore engine is started
,08-17 14:04:00.212  7308  7356 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 14:04:00.222  7308  7308 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 14:04:02.992   292   292 E SMD     : DCD OFF,
,08-17 14:04:03.742  1017  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-17 14:04:03.742  1017  1447 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-17 14:04:03.742  1017  1447 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-17 14:04:03.742  1017  1447 D BatteryService: stay LED for charging
08-17 14:04:03.742  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-17 14:04:03.742  1017  1017 I MotionRecognitionService: Plugged
,08-17 14:04:03.742  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-17 14:04:03.752  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-17 14:04:03.752  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-17 14:04:03.752  1422  1422 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-17 14:04:03.752  1422  1422 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-17 14:04:03.762  3217  3217 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-17 14:04:03.762  3217  3355 D HeadsetStateMachine: Disconnected process message: 10
,08-17 14:04:03.782  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-17 14:04:03.782  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 14:04:03.782  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-17 14:04:03.782  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-17 14:04:03.782  1179  1179 D SViewCoverView: level :100 plugged : 2

```
